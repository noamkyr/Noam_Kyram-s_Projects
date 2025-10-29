# Welcome to My Developer Portfolio

Hello! I'm Noam Kyram, a computer science student at Reichman University. Over the past few years, I've worked on a variety of projects that showcase my skills in software development, web technologies, and data analysis. This portfolio is a collection of my best work, demonstrating my ability to turn ideas into functional, scalable, and efficient solutions.

## 📁 Project Highlights

### [Project Overview - Code Something](https://github.com/noamkyr/code_something-_final_project_Noam_Kyram.git)
Code Something is an interactive platform for programming challenges designed to strengthen algorithmic thinking using LLM-powered feedback.
A challenge involves two users:
  1.	User A implements a function in a chosen source language and verifies it.
  2.	User A sends the code to User B as a challenge.
  3.	User B first writes a free-text explanation of what the code does.
  The system’s LLM verifies the accuracy of this description.
  4.	Upon a correct description, User B must reimplement the same logic in the target language.
  The result is verified using LLM scoring and unit tests.
  If both steps pass, both players earn a point.

**Key Features**

• Dynamic Flowchart Generation:  
  Real-time visualization of the code’s control flow using pyflowchart, Graphviz, and language-specific converters (for Python, JavaScript, and C#).  
  This helps users debug, reason, and explain logic visually.

• Daily “Student C” Challenge:  
  Presents code that looks correct but hides a conceptual flaw.  
  Players must identify the mistake in logic - testing deeper comprehension.

• LLM-Based Code Evaluation:  
  Uses a locally hosted model (qwen2.5-coder) through llama_cpp to assess code implementations and textual explanations according to accuracy, clarity, and alignment with the given mission.  
  It also provides a numeric grade based on different parameters.

• Monaco Editor Integration:  
  Provides an in-browser coding environment with syntax highlighting, autocomplete, and instant flowchart updates - giving users a familiar VS Code-like experience.

• Smartlook Analytics:  
  Tracks real user interactions on both client and server to analyze engagement and usability.



### [Noam's Jersey Shop](https://github.com/noamkyr/noams_jerseys_store)
This project, Noam's Jersey Shop, was developed as my final full-stack project course. It is an online store for NBA jerseys, built from scratch using Node.js, Express, and client-side in JavaScript, CSS, HTML. The project demonstrates backend design, RESTAPI development, and session authentication and management using persistent cookies. On the frontend, it features dynamic rendering, responsive layouts, and advanced user interactions such as a wishlist system with personal notes, product reviews, and real-time currency conversion (USD and NIS). Additional functionality includes NBA statistics pages powered by external APIs, administrative tools for product management and activity tracking, and automated test scripts that validate all server routes and edge cases.


### [Real-time multi-method e-commerce scraper](https://github.com/noamkyr/Hw3_Ex1_Noam_Kyram.git)
Allows users to compare product data from Amazon, BestBuy, and Walmart. The system features a javascript frontend connected to a FastAPI backend written in Python. It supports three scraping methods: Basic Scraping using requests and BeautifulSoup for structured HTML extraction, LLM Scraping using LLM models using OpenRouter to intelligently parse complex HTML and extract product details), and Firecrawl API Scraping. The scraper dynamically retrieves and displays product information including title, price, rating, and review count in a simple, responsive table. In addition, it includes a product recommendation feature powered by an LLM that suggests related products based on the user’s recent search history.

This project is demonstrating the integration of web automation, AI reasoning, and modern backend-frontend communication.


### [Table Tennis Analyzer](https://github.com/noamkyr/Hw2_ex1_Noam_Kyram_Table_Tennis_Analyzer.git)
A computer-vision system that automatically tracks and analyzes players in a table-tennis match using YOLO pose estimation, OpenCV, and EasyOCR. The program detects players in each frame of a match video, draws bounding boxes and pose joints, filters invalid frames, and records the player coordinates into a CSV file. It generates a heatmap of player movement patterns and a score-progress chart visualizing how each player’s performance evolves throughout the match. In addition, it calculates and displays real-time player speeds between score changes, showing the average movement intensity both on the video overlay and directly on the score chart.

### [Telegram Face Recognition Bot](https://github.com/noamkyr/Hw1_ex1_Noam_Kyram.git)

Built entirely in Python, combining real-time messaging automation with computer vision. Users can upload images to teach the bot new faces, recognize known individuals in new photos, and even find similar celebrities using a pre-encoded database. The system leverages the face_recognition library for encoding and comparison, TSNE and matplotlib for generating visual “familiarity maps” that cluster similar faces.


### [Special Icy Tower](https://github.com/noamkyr/Hw1_ex2_Noam_Kyram.git)
This project is a special version of the classic "Icy Tower" game, fully developed in JavaScript using HTML Canvas. The game now includes a scoring system that rewards faster climbs, platforms that collapse after being stood on for several seconds, moving platforms (both vertically and horizontally), and two types of animated enemies. I also introduced power-ups such as a star granting temporary invincibility, a spring that launches the player higher, collectible coins, and a unique zero-gravity boost that alters gameplay physics for a limited time. The game features visual upgrades with custom image assets, sound effects, background music, and a leaderboard system that tracks top scores. 

### [The quest for the Epsilon cup game](https://github.com/noamkyr/Hw3_trivia_game.git)
This project is a full-stack real-time multiplayer trivia game combining a FastAPI backend, Socket.IO communication, and a Next.js frontend. It features live multiplayer gameplay with synchronized questions, scoring, and chat. The question database was generated and validated automatically using multiple LLMs (Gemini / Gemma) to ensure uniqueness, balanced difficulty, and accuracy across ten categories. Additional scripts integrate hint generation and adaptive validation through AI pipelines. Players can choose their character (Archer or Warrior) and use strategic power-ups such as 50-50, Double Points, Triple Points, and Call a Friend (hint reveal). A real-time leaderboard updates after every round. 


### [FPL Points Predictor](https://github.com/noamkyr/Noam_Kyram_FPL_Prediction.git)
This project is designed to predict Fantasy Premier League (FPL) points for players based on historical data and upcoming fixtures. The model considers various factors such as player performance, opponent strength, and match location to make predictions. It’s a powerful tool for FPL enthusiasts who want to optimize their teams and make data-driven decisions.

**Features**
- **Data Extraction**: Gathers historical player and team performance data from the FPL API and upcoming game data.
- **Data Processing**: Cleans and preprocesses data, filtering for relevant player statistics and fixtures.
- **Prediction Model**: Utilizes a customized algorithm to forecast FPL points based on historical data, expected goals (xG), and assists (xA). The model predicts the players' FPL score in the next gameweek.
- **Visualization**: Provides insightful visualizations of player performance trends and upcoming match difficulties.

**Technologies**
- **Python**
- **Pandas**: Data processing and manipulation.
- **NumPy**: Numerical computations and operations.
- **Matplotlib**: Visualization of data and predictions.
- **SciKit-Learn**: Machine learning algorithms for predictive modeling.
- **FPL API**: Source of historical player data.

### [My Fantasy 2020 - Football Fantasy Game](https://github.com/noamkyr/Fpl_Fantasy_2020_Noam_Kyram.git)
My Fantasy 2020 is a game where users create fantasy football teams with real Premier League players and compete in leagues based on player statistics. Inspired by the official Premier League Fantasy game, this app offers a unique twist: teams are created once without any further player transfers, requiring strategic thinking based on last season's player stats.

**Key Features**:
- **Team Building**: Users select players by position (Goalkeeper, Defender, Midfielder, Forward) from a predefined list, creating their teams with a limited budget based on previous season stats.
- **Real-Time Statistics**: The app pulls live player stats from the Premier League's official website using REST API services, and scores are calculated based on actual match performances.
- **Competitive Play**: Users can challenge friends to create their own teams and compete based on aggregated player statistics from the current Premier League season.

**Technologies & Tools**:
- **Android Development**: The app is built natively for Android using Java for logic and XML for the user interface.
- **Backend Server**: The server is developed in Python, using the FPL API for the latest player statistics at regular intervals. It stores the data in an SQL database to ensure efficient data retrieval and management.
- **REST API**: The server communicates with the Premier League's REST API to keep updated player statistics and manages user interactions within the app.
- **Data Management**: The server utilizes an SQL database to store user data, team configurations, and track the status of challenges.
- **Push Notifications**: The app leverages Firebase to send push notifications to users when a challenge is sent.


### [My Fantasy - Basketball Fantasy Game](https://github.com/noamkyr/Noam_Kyram_client_server_project_2019.git)
My Fantasy is an Android app designed for basketball enthusiasts, offering a fantasy game based on real N.B.A. league players from specific seasons. This project demonstrates a blend of mobile development, data integration, and backend server management.

**Key Features**:
- **Team Building**: The user can select a specific N.B.A. season, draft players by position (Guard, Forward, Center), and create their ideal lineup from the active players of that season.
- **Real-Time Statistics**: Player stats are fetched from the official N.B.A. site using REST API services.
- **Competitive Play**: Users can challenge friends to build their own teams and compete based on aggregated player statistics, including points, assists, rebounds, blocks, and steals.

**Technologies & Tools**:
- **Android Development**: The app is built natively for Android using Java and XML for the user interface.
- **Backend Server**: A Python-based server, periodically scraping the N.B.A. API for the latest player stats and storing them at the server in JSON format.
- **Requests**: Used to interact with the N.B.A. REST API, ensuring accurate and up-to-date data.
- **REST API**: The server communicates with the client app via a custom REST API, managing user authentication, team creation, and real-time score updates.
- **Data Storage**: User data and team configurations are stored on the server for minimal local storage and user session management.

### [Football Game in Assembly 8086](https://github.com/noamkyr/Noam_Assembly_8086_football_project_2017-.git)
This project is a football game developed using Assembly 8086, showcasing a deep understanding of low-level programming and hardware interaction. The system efficiently handles various operations like updating and displaying the score, and timing functions, all optimized for performance and memory usage.

### [Modular Pipeline System]
This project is a modular, multithreaded string-processing pipeline written in C, designed to demonstrate real-world systems programming concepts such as dynamic linking, thread synchronization, and producer-consumer communication. The system allows users to dynamically construct a text-processing pipeline by specifying plugins at runtime - each implemented as a shared object (.so) and executed in its own thread. Inter-thread communication is handled through bounded, thread-safe queues implemented with custom synchronization primitives (monitors and condition variables). The project features a clean SDK design, enabling easy creation of new plugins like uppercaser, flipper, rotator, logger, typewriter, and expander. A robust build and test framework (build.sh and test.sh) ensures correctness, graceful shutdown, and synchronization safety across all modules, showcasing concurrency, modularity, and dynamic loading in C under Ubuntu. The project must run on Ubuntu 24.04 using GCC 13, linked only with pthread and dl libraries, and built via bash scripts (build.sh and test.sh) that compile and test all plugins and the main analyzer executable.




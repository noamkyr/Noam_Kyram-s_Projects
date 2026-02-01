# Welcome to My Developer Portfolio

I'm Noam Kyram, a computer science student at Reichman University. Over the past few years, I've worked on a variety of projects that showcase my skills in software development, web technologies, and data analysis. This portfolio is a collection of my best work, demonstrating my ability to turn ideas into functional, scalable, and efficient solutions.

## 📁 Project Highlights

### [Code Something](https://github.com/noamkyr/code_something-_final_project_Noam_Kyram.git)
Code Something is an interactive platform for programming challenges designed to strengthen algorithmic thinking using LLM-powered feedback.
A challenge involves two users:
  1.	User A implements a function in a chosen source language and verifies it.
  2.	User A sends the code to User B as a challenge.
  3.	User B first writes a free-text explanation of what the code does.
  The system’s LLM verifies the accuracy of this description.
  4.	Upon a correct description, User B must reimplement the same logic in the target language.
  The result is verified using LLM scoring.
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



### [Pet Store Microservices Platform](https://github.com/RonIsakov/project_2_Cloud_Computing)

A distributed pet store application built using microservices architecture with containerization and orchestration tools.

**Project Overview**
- Multi-service system including frontend APIs and order and transaction services
- Load balanced via Nginx reverse proxy
- Uses Docker Compose for service setup
- Data stored in MongoDB

**Features**
- Pet store services with full CRUD operations
- Pet order service handles purchases and transaction records
- Load balancing between services
- Clear, RESTful API endpoints

**Technology Stack**
- Backend: Python and Flask
- Database: MongoDB
- Orchestration: Docker and Docker Compose
- Proxy and Routing: Nginx


### [Pet Store Platform on Kubernetes](https://github.com/RonIsakov/project_3_Cloud_Computing)

A cloud-native pet store application deployed on Kubernetes using KIND, demonstrating a multi-service architecture with API gateway, persistent storage, and role-based access control.

**Architecture Overview**
- NGINX API gateway routing requests to backend services
- Two Pet Store services and one Pet Order service
- Persistent MongoDB storage with volumes
- Role-based access control for owner and customer roles

**Services**
- NGINX API Gateway with path-based routing
- Pet Store services (Flask REST APIs) with CRUD operations and image support
- Pet Order service handling purchases and transaction history
- MongoDB database for persistent data

**Deployment**
- KIND (Kubernetes in Docker) for local cluster setup
- Kubernetes manifests for all services and persistent volumes
- Automated deployment script (`test-submission.sh`)

**Technology Stack**
- Backend: Python and Flask
- Database: MongoDB with Kubernetes volumes
- Orchestration: Kubernetes (KIND)
- Reverse Proxy: NGINX API Gateway


### [Pet Store Platform with CI/CD Automation](https://github.com/RonIsakov/project_4_Cloud_Computing)

Automated CI/CD workflow for a pet store microservices platform, demonstrating continuous integration, testing, and deployment with GitHub Actions.

**Highlights**
- Microservices architecture with dedicated services and databases 
- Full CI/CD automation via GitHub Actions pipeline (build → test → dynamic query execution) 
- Container orchestration using Docker Compose with health checks and dependencies 
- Automated testing integrated with `pytest` and runtime query execution support 

**CI/CD Pipeline**
- **Build:** Parallel Docker image builds for all microservices  
- **Test:** Automated tests through `pytest` validating APIs and service behaviors  
- **Query Job:** Executes dynamic queries and purchases defined in an external file against live services 

**Services & Architecture**
- Separate Flask-based microservices for pet inventory and order processing  
- MongoDB for persistent storage and transaction tracking  

**Technology Stack**
- Python and Flask backend  
- Docker and Docker Compose for containerization  
- GitHub Actions for CI/CD  



### [Real-time multi-method e-commerce scraper](https://github.com/noamkyr/Hw3_Ex1_Noam_Kyram.git)
Allows users to compare product data from Amazon, BestBuy, and Walmart. The system features a javascript frontend connected to a FastAPI backend written in Python. It supports three scraping methods: Basic Scraping using requests and BeautifulSoup for structured HTML extraction, LLM Scraping using LLM models using OpenRouter to intelligently parse complex HTML and extract product details), and Firecrawl API Scraping. The scraper dynamically retrieves and displays product information including title, price, rating, and review count in a simple, responsive table. In addition, it includes a product recommendation feature powered by an LLM that suggests related products based on the user’s recent search history.

This project is demonstrating the integration of web automation, AI reasoning, and modern backend-frontend communication.


### [Table Tennis Analyzer](https://github.com/noamkyr/Hw2_ex1_Noam_Kyram_Table_Tennis_Analyzer.git)
A computer-vision system that automatically tracks and analyzes players in a table-tennis match using YOLO pose estimation, OpenCV, and EasyOCR. The program detects players in each frame of a match video, draws bounding boxes and pose joints, filters invalid frames, and records the player coordinates into a CSV file. It generates a heatmap of player movement patterns and a score-progress chart visualizing how each player’s performance evolves throughout the match. In addition, it calculates and displays real-time player speeds between score changes, showing the average movement intensity both on the video overlay and directly on the score chart.


### [Telegram Face Recognition Bot](https://github.com/noamkyr/Hw1_ex1_Noam_Kyram.git)

Built entirely in Python, combining real-time messaging automation with computer vision. Users can upload images to teach the bot new faces, recognize known individuals in new photos, and even find similar celebrities using a pre-encoded database. The system leverages the face_recognition library for encoding and comparison, TSNE and matplotlib for generating visual “familiarity maps” that cluster similar faces.


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






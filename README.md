# Welcome to My Developer Portfolio

Hello! I'm Noam Kyram, a passionate software developer with a solid foundation in Computer Science. Over the past few years, I've worked on a variety of projects that showcase my skills in software development, web technologies, and data analysis. This portfolio is a collection of my best work, demonstrating my ability to turn ideas into functional, scalable, and efficient solutions.

## 📁 Project Highlights

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

# Math Game Web Application
I have developed a simple Flask based web application. Basically, it is a Math Game website. It facilitates users to play a math-based game while tracking their progress and scores. Built using Flask, a lightweight Python web framework, this application features user authentication, score tracking, and an interactive gaming experience.

## Key Features:
•	User Authentication: Users can register, log in, and log out securely. The application utilizes Flask-Login for managing user sessions. <br>
•	Dashboard: Each authenticated user has access to a personalized dashboard displaying their highest score.
•	Math Game: The core of the application is an interactive math game where users answer randomly generated math sums within a set time limit. The game includes a countdown timer and updates users on their scores in real-time.
•	Score Management: Users' scores are stored in an SQLite database, allowing for the persistent tracking of their highest scores. The application compares new scores with previous ones and updates the database accordingly.

Technologies Used:
•	Backend: Flask, Flask-SQLAlchemy, Flask-Login
•	Frontend: HTML, CSS, JavaScript
•	Database: SQLite for user data and score management

📚 Quiz Application

A full-stack quiz platform where users can play quizzes on Java, Python, Data Structures, and more. The application supports dynamic quiz questions, score calculation, authentication, and real-time result tracking. 🚀 Features 🎯 Multiple quiz categories – Java, Python, DSA, General Knowledge, etc. 👤 User login & authentication 🧩 Randomized and stored quiz questions from database 📝 Automatic score calculation 📊 Result summary with correct/incorrect answers 🗄️ Admin module to add/update quiz questions (optional) 🧹 Clean and user-friendly UI built with HTML/CSS/JS 🔒 Secure backend with Spring Boot + MySQL 🛠️ Tech Stack Frontend HTML5 CSS3 JavaScript Backend Java Spring Boot Spring MVC Servlets Database MySQL

📂 Project Structure Quiz-Application/ │── src/ │ ├── main/ │ │ ├── java/com/quizapp/... │ │ ├── resources/ │ │ └── webapp/ │── pom.xml │── README.md

⚙️ How It Works User selects a quiz category Questions are fetched from the MySQL database Each question is displayed one by one Score is calculated automatically Final scorecard is shown at the end

🗃️ Database Schema (Sample) Table: questions Column Name Type Description id INT Primary Key question TEXT Quiz question option1 VARCHAR Option A option2 VARCHAR Option B option3 VARCHAR Option C option4 VARCHAR Option D correct_answer VARCHAR Right answer category VARCHAR (Java, Python, DSA) 🧪 Sample API Endpoints Method Endpoint Description GET /quiz/{category} Fetch quiz questions POST /quiz/submit Submit answers & calculate score GET /score/{userId} Get user scores 📸 Screenshots (Add your own later) /screenshots ├── home-page.png ├── quiz-screen.png └── results.png

▶️ How to Run Locally

Clone the repo git clone https://github.com/yourusername/quiz-application.git
Import into IDE Open in IntelliJ / Eclipse / VS Code (Java extension).
Configure MySQL Create database: CREATE DATABASE quizapp; Update application.properties: spring.datasource.url=jdbc:mysql://localhost:3306/quizapp spring.datasource.username=root spring.datasource.password=yourpassword
Run the application mvn spring-boot:run
Open in browser http://localhost:8080
📌 Future Enhancements Add timer for quizzes User leaderboard JWT authentication Export results to PDF Mobile version with Flutter

🤝 Contributing Feel free to fork the repository and raise a PR if you want to improve UI/UX or add more quiz categories!

📬 Contact

Sakshi Bharti 📧 Email: sakshibharti750@gmail.com 🔗 GitHub: https://github.com/sakshi188 🔗 LinkedIn: https://linkedin.com/in/sakshi-bharti-183168350

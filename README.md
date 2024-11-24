
---

# Indy Winner Results Viewer

## Overview
**Indy Winner Results Viewer** is a web-based application designed to display Indy race winner data with a clean and user-friendly interface. The application retrieves data from a MySQL database and dynamically generates HTML pages using Java Servlets. It also includes pagination to navigate through the results easily.

---

## Features
- **Database Integration**: Fetch and display race winner data using SQL queries.
- **Dynamic Web Pages**: HTML pages are generated on the fly using Servlets.
- **Pagination**: Navigate through results in chunks of 10 entries using "Next" and "Previous" buttons.
- **Error Handling**: Basic error messages for connectivity issues or data fetching errors.
- **Deployed on Tomcat**: Developed and deployed locally on Apache Tomcat.

---

## Project Structure
### Files and Directories
1. **`src/`** - Contains all Java source code files (Servlets, utility classes).
2. **`web/`** - Contains static assets, such as HTML, CSS, and JavaScript files.
3. **`doc/`** - Contains Java documentation (Javadoc) for all classes and methods.
4. **`uml/`** - UML diagram showing the structure and relationships between classes.
5. **`lib/`** - Contains external libraries like MySQL JDBC driver.

---

## Technologies Used
- **Java**: Core programming language for Servlets.
- **MySQL**: Database to store and retrieve race winner data.
- **HTML/CSS**: Front-end for displaying results.
- **Apache Tomcat**: Local server to run the application.
- **JDBC**: To connect the Java application with MySQL.

---

## Installation
### Prerequisites
1. JDK 8+ installed on your system.
2. Apache Tomcat server installed.
3. MySQL Database running with the required schema and data.
4. NetBeans IDE (optional, but recommended for ease of use).

---

### Steps
1. Clone the repository:
   ```
   git clone https://github.com/your-username/indy-winner-viewer.git
   ```
2. Import the project into NetBeans or your preferred IDE.
3. Configure the database connection in the `Database` class:
   ```
   String url = "jdbc:mysql://localhost:3306/your_database_name";
   String user = "your_username";
   String password = "your_password";
   ```
4. Deploy the project to the Apache Tomcat server.
5. Access the application via:
   ```
   http://localhost:8080/IndyWinnerResultsViewer/index.html
   ```

---

## Usage
1. **Homepage**: Navigate to the homepage (`index.html`) to see race winner results.
2. **Pagination**: Use the "Next" and "Previous" buttons to navigate through the results.
3. **Error Handling**: If the database connection fails, an error message will be displayed.


---

## Contributing
1. Fork the repository.
2. Create a new branch:
   ```
   git checkout -b feature-branch-name
   ```
3. Make changes and commit:
   ```
   git commit -m "Description of changes"
   ```
4. Push to your branch:
   ```
   git push origin feature-branch-name
   ```
5. Open a pull request.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments
- Professor Reg Dyer for guidance and project requirements.
- Java Documentation for detailed information on Servlets and JDBC.

---

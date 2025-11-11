# Modern Career Guidance: A Personalized Approach to Success

![Java](https://img.shields.io/badge/Java-17-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.0-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

This repository contains the source code for the "Modern Career Guidance" platform, a B.Tech final year project. The platform is a comprehensive Java Full Stack application designed to provide personalized career planning support for students and professionals.

---

## 🎯 About the Project

In today's fast-changing job market, making well-informed career decisions is vital. Many individuals struggle to identify the gaps between their existing skills and the skills required for their desired careers.

This project aims to solve that problem by providing an innovative, technology-driven solution. The **Modern Career Guidance** platform serves as a transformative tool that bridges the gap between a user's current competencies and their career aspirations. It leverages a robust Java Full Stack architecture to deliver reliable, scalable, and personalized career support.

## ✨ Key Features

The platform is built around four integrated modules to create a seamless user experience:

* **👨‍💻 Skill Gap Analysis:** The system evaluates a user's existing skills against industry standards for their target job roles. It identifies specific areas for improvement and generates a personalized learning plan.
* **📚 Personalized Course Recommendations:** To bridge identified skill gaps, the platform offers tailored course recommendations. These suggestions are updated regularly based on emerging market trends and industry practices.
* **🔎 Intelligent Job Matching:** A job matching engine connects users with employment opportunities that align with their capabilities and long-term career goals.
* **🗣️ Dynamic Feedback Mechanism:** Users can provide ratings and reviews for the courses they complete. This feedback loop helps maintain high-quality educational content.
* **🔒 Admin & User Management:** The application features separate dashboards for users (to manage their profiles, skills, and goals) and administrators (to manage course catalogs, job postings, and review user feedback).

## 💻 Technology Stack

The platform is built using a modern, robust technology stack:

* **Backend:**
    * **Java 17**
    * **Spring Boot 3.0** (for RESTful APIs and business logic)
    * **Spring Security** (for robust authentication and authorization)
* **Frontend:**
    * **HTML5**
    * **CSS3**
    * **JavaScript (ES6+)** (for a responsive and interactive user interface)
* **Database:**
    * **MySQL 8.0** (for reliable, scalable database management)
    * **Hibernate/JPA** (for Object-Relational Mapping)

## 🏗️ System Architecture

The project follows a multi-tier architecture to ensure scalability, reliability, and separation of concerns.

1.  **Client Layer (Frontend):** The user interface built with HTML, CSS, and JavaScript that interacts with the backend via REST API calls.
2.  **Presentation Layer (API Gateway):** Manages HTTP/HTTPS requests and routes them to the appropriate backend services, secured by Spring Security.
3.  **Application Layer (Backend Services):** The core business logic built with Spring Boot. This layer includes microservices for User Profiles, Skill Analysis, Job Matching, and Feedback.
4.  **Data Layer (Database):** The persistent storage layer using MySQL 8.0 to store user profiles, courses, job listings, and feedback.


*(You can add the 'Figure 2.2.2 System Architecture' image from page 20 here for a visual representation)*

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

* JDK 17 or higher
* Apache Maven
* MySQL 8.0
* A web browser

### Installation

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/your-username/modern-career-guidance.git](https://github.com/your-username/modern-career-guidance.git)
    cd modern-career-guidance
    ```

2.  **Database Setup:**
    * Create a new database in MySQL.
    * Update the `src/main/resources/application.properties` file with your MySQL server URL, username, and password.
        ```properties
        spring.datasource.url=jdbc:mysql://localhost:3306/your_database_name
        spring.datasource.username=your_mysql_username
        spring.datasource.password=your_mysql_password
        spring.jpa.hibernate.ddl-auto=update
        ```

3.  **Run the Backend (Spring Boot):**
    * Navigate to the project's root directory (where `pom.xml` is located).
    * Run the following Maven command:
        ```sh
        mvn spring-boot:run
        ```
    * The server will start on `http://localhost:8080` (or your configured port).

4.  **Run the Frontend:**
    * Since the frontend is built with vanilla HTML, CSS, and JavaScript, you can simply open the `index.html` file (or equivalent) from the frontend directory in your web browser.

You should now be able to register, log in, and use the application.

## 🏛️ Academic Context

This project was submitted in partial fulfillment of the requirements for the award of the degree of:

* **Bachelor of Technology** in **Computer Science and Engineering** (2021-2025)
* **Institution:** Usha Rama College of Engineering and Technology, Autonomous
* **University:** Jawaharlal Nehru Technological University, Kakinada

### Author
* **CHAVALA VENKAT KALYAN**

### Under the Guidance of
* **Dr. S M Roy Choudri** (Professor, Dept. of CSE)

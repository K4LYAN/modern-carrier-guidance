# Modern Career Guidance: A Personalized Approach to Success

![Java](https://img.shields.io/badge/Java-17-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.0-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

[cite_start]This repository contains the source code for the "Modern Career Guidance" platform, a B.Tech final year project[cite: 10, 11]. [cite_start]The platform is a comprehensive Java Full Stack application designed to provide personalized career planning support for students and professionals[cite: 61].

---

## 🎯 About the Project

[cite_start]In today's fast-changing job market, making well-informed career decisions is vital[cite: 60]. [cite_start]Many individuals struggle to identify the gaps between their existing skills and the skills required for their desired careers[cite: 209].

[cite_start]This project aims to solve that problem by providing an innovative, technology-driven solution[cite: 218]. [cite_start]The **Modern Career Guidance** platform serves as a transformative tool that bridges the gap between a user's current competencies and their career aspirations[cite: 157, 73]. [cite_start]It leverages a robust Java Full Stack architecture to deliver reliable, scalable, and personalized career support[cite: 159, 68].

## ✨ Key Features

[cite_start]The platform is built around four integrated modules to create a seamless user experience[cite: 153]:

* [cite_start]**👨‍💻 Skill Gap Analysis:** The system evaluates a user's existing skills against industry standards for their target job roles[cite: 62]. [cite_start]It identifies specific areas for improvement and generates a personalized learning plan[cite: 951].
* [cite_start]**📚 Personalized Course Recommendations:** To bridge identified skill gaps, the platform offers tailored course recommendations[cite: 63]. [cite_start]These suggestions are updated regularly based on emerging market trends and industry practices[cite: 63].
* [cite_start]**🔎 Intelligent Job Matching:** A job matching engine connects users with employment opportunities that align with their capabilities and long-term career goals[cite: 64].
* [cite_start]**🗣️ Dynamic Feedback Mechanism:** Users can provide ratings and reviews for the courses they complete[cite: 66, 241]. [cite_start]This feedback loop helps maintain high-quality educational content[cite: 67].
* [cite_start]**🔒 Admin & User Management:** The application features separate dashboards for users (to manage their profiles, skills, and goals) and administrators (to manage course catalogs, job postings, and review user feedback)[cite: 312, 385].

## 💻 Technology Stack

[cite_start]The platform is built using a modern, robust technology stack[cite: 183, 251]:

* **Backend:**
    * [cite_start]**Java 17** [cite: 69, 923]
    * [cite_start]**Spring Boot 3.0** [cite: 70, 927] (for RESTful APIs and business logic)
    * [cite_start]**Spring Security** [cite: 319] (for robust authentication and authorization)
* **Frontend:**
    * [cite_start]**HTML5** [cite: 907]
    * [cite_start]**CSS3** [cite: 913]
    * [cite_start]**JavaScript (ES6+)** [cite: 919] (for a responsive and interactive user interface)
* **Database:**
    * [cite_start]**MySQL 8.0** [cite: 70, 931] (for reliable, scalable database management)
    * [cite_start]**Hibernate/JPA** [cite: 320] (for Object-Relational Mapping)

## 🏗️ System Architecture

[cite_start]The project follows a multi-tier architecture to ensure scalability, reliability, and separation of concerns[cite: 461].

1.  [cite_start]**Client Layer (Frontend):** The user interface built with HTML, CSS, and JavaScript that interacts with the backend via REST API calls[cite: 315, 464].
2.  [cite_start]**Presentation Layer (API Gateway):** Manages HTTP/HTTPS requests and routes them to the appropriate backend services, secured by Spring Security[cite: 318, 319, 328].
3.  [cite_start]**Application Layer (Backend Services):** The core business logic built with Spring Boot[cite: 467]. [cite_start]This layer includes microservices for User Profiles, Skill Analysis, Job Matching, and Feedback [cite: 332-342].
4.  [cite_start]**Data Layer (Database):** The persistent storage layer using MySQL 8.0 to store user profiles, courses, job listings, and feedback [cite: 346, 471-473].

[cite_start]*(You can add the 'Figure 2.2.2 System Architecture' image from page 20 [cite: 349] here for a visual representation)*

## 📸 Screenshots

[cite_start]Here are a few screenshots from the application (as seen in Chapter 7 of the project book [cite: 137]):

| [cite_start]Home Page [cite: 1225] | [cite_start]User Dashboard [cite: 1262] |
| :---: | :---: |
|  |  |
| [cite_start]**Skill Gap Analysis Report** [cite: 1315] | [cite_start]**Course Recommendation Page** [cite: 1320] |
|  |  |
| [cite_start]**Job Recommendation Page** [cite: 1341] | [cite_start]**Admin Dashboard** [cite: 1365] |
|  |  |

*(**Note:** You will need to take these screenshots and upload them to your repository, then update the `` paths.)*

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

* [cite_start]JDK 17 or higher [cite: 923]
* Apache Maven
* [cite_start]MySQL 8.0 [cite: 931]
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
    * [cite_start]Since the frontend is built with vanilla HTML, CSS, and JavaScript [cite: 906-920], you can simply open the `index.html` file (or equivalent) from the frontend directory in your web browser.

You should now be able to register, log in, and use the application.

## 🏛️ Academic Context

This project was submitted in partial fulfillment of the requirements for the award of the degree of:

* [cite_start]**Bachelor of Technology** in **Computer Science and Engineering** (2021-2025) [cite: 10, 11, 13, 26]
* [cite_start]**Institution:** Usha Rama College of Engineering and Technology, Autonomous [cite: 22, 30]
* [cite_start]**University:** Jawaharlal Nehru Technological University, Kakinada [cite: 9]

### Author
* [cite_start]**CHAVALA VENKAT KALYAN** [cite: 15, 36]

### Under the Guidance of
* **Dr. [cite_start]S M Roy Choudri** (Professor, Dept. of CSE) [cite: 18, 38, 51]

# Cinematic - Online Cinema Ticket Booking System

## Overview
Cinematic is a web-based cinema ticket booking system built using **Java Server Pages (JSP) and Servlets**. It allows users to browse movies, select seats, and book tickets online while ensuring a seamless and secure transaction process. Administrators can manage schedules, ticket slots, and user bookings efficiently. The system includes secure authentication using **Bcrypt password encryption** and email notifications via **SMTP**.

## System Requirements

### 1. Development Environment
- **JDK (Java Development Kit) 8, 11, or newer** (Recommended: JDK 8)  
  - [Download JDK](https://adoptium.net/)  
- **Apache Tomcat 9.x or 10.x**  
  - [Download Apache Tomcat](https://tomcat.apache.org/download-90.cgi)  
- **Maven 3.5+** (If using dependency management)  
  - [Download Maven](https://maven.apache.org/download.cgi)  

### 2. Development Tools (IDE - Optional)
- **Eclipse IDE for Enterprise Java Developers**  
  - [Download Eclipse](https://www.eclipse.org/downloads/packages/)  
- **IntelliJ IDEA Ultimate** (Paid version required for full support)  
  - [Download IntelliJ IDEA](https://www.jetbrains.com/idea/download/)  
- **NetBeans** (Integrated support for JSP & Servlets)  
  - [Download NetBeans](https://netbeans.apache.org/download/index.html)  

### 3. Database (Optional)
- **SQL Server 2019 or newer**  
  - [Download SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)  

### 4. Related Technologies (If Used)
- **JSTL** (JavaServer Pages Standard Tag Library)  
- **JDBC** (Java Database Connectivity)  

## Technologies Used
- **Backend:** Java, Servlet, JSP  
- **Frontend:** JavaScript, HTML, CSS, Bootstrap, jQuery  
- **Database:** MS SQL  
- **Security:** Bcrypt for password encryption  
- **Services:** SMTP Email service for notifications  

## Role & Contributions
**Role:** Leader (Fullstack Developer)  
**Team Size:** 2 members  

### Key Responsibilities:
- **Database Design** - Analyzed business requirements and structured the database schema.  
- **Backend Development** - Implemented booking system functionalities & admin panel.  
- **Security** - Integrated Bcrypt for password hashing & email notifications via SMTP.  
- **Frontend Development** - Designed and developed a user-friendly interface.  

## Project Setup & Installation

### 1. Clone the Repository
```sh
git clone https://github.com/huypqse/CENEMATIC.git
```  

### 2. Import Project (Using Eclipse or IntelliJ)
1. Open your IDE and **import the project as a Maven project**.  
2. Ensure **Tomcat** is installed and configured in the IDE.  
3. Set up **SQL Server** and import the required database schema.  

### 3. Build & Run the Project
- **Using Maven:**  
  ```sh
  mvn clean install
  ```  
- **Deploy on Tomcat:**  
  1. Right-click the project → **Run on Server**.  
  2. Select **Apache Tomcat** and start the server.  

- **Access the Application:**  
  - **User Portal:** `http://localhost:8080/cinematic`  
  - **Admin Panel:** `http://localhost:8080/admin`  

## GitHub Repository
[Cinematic on GitHub](https://github.com/huypqse/CENEMATIC)  

## Contact
For inquiries or suggestions, feel free to reach out:  
- **Email:** huypqse@gmail.com  
- **LinkedIn:** [Your LinkedIn Profile](#)  

---


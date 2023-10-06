# Authentication with Servlet and JavaMail
A simple a web application that combines user authentication using servlets with email functionality through the JavaMail API.


![Java](https://img.shields.io/badge/Java-8%2B-blue)
![Servlet](https://img.shields.io/badge/Servlet-3.1%2B-green)
![JavaMail](https://img.shields.io/badge/JavaMail-1.6%2B-yellow)
![Tomcat](https://img.shields.io/badge/Tomcat-9.0%2B-orange)
![mysql-connector](https://img.shields.io/badge/mysql-connector-j-8.0.33.jar%2B-green)

This web application demonstrates a simple yet powerful combination of user authentication using Java servlets and email functionality via the JavaMail API. It provides a foundation for secure user access to protected resources and enables sending emails directly from your web application.

## Features

- **User Authentication:**
  - Secure user login using servlets.
  - Password validation and session management.
  
- **JavaMail Integration:**
  - Send email notifications or confirmations.
  - Customizable email templates.
  
- **Web Application Structure:**
  - Separation of concerns with servlets for authentication.
  - Easy integration of JavaMail for email functionality.
  
## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- Apache Maven 3.3 or higher
- Java Servlet API 3.1 or higher
- JavaMail API 1.6 or higher

### Installation and Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Bushaija/authentication-servlet-javamail.git

### Database Schema: studentAdmissionTest

```sql
CREATE DATABASE studentAdmissionTest;

USE studentAdmissionTest;

CREATE TABLE Student (
    student_id INT AUTO_INCREMENT PRIMARY KEY,
    firstName VARCHAR(30),
    lastName VARCHAR(30),
    password VARCHAR(30)
);

   
```
Author:
## MUGISHA Robert (23443)


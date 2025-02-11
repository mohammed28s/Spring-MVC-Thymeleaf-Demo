

# Spring MVC Thymeleaf Demo

A simple Spring Boot project demonstrating Thymeleaf integration with form handling.

## Features

- Student form with name, country, language, and system preferences.
- GET and POST request handling with Thymeleaf templates.
- Configurations for dynamic dropdowns (countries, languages, systems).

## Tech Stack

- **Java 8+**
- **Spring Boot**
- **Thymeleaf**
- **Maven**

## Setup

1. **Clone the repo:**
   ```bash
   git clone https://github.com/mohammed28s/Spring-MVC-project-sample
   ```
2. **Build & run:**
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```

## Key Endpoints

- `/showForm` – Displays a form.
- `/processForm` – Processes form submission.
- `/showStudentForm` – Displays the student form.
- `/processStudentForm` – Handles student data.

## Config: `application.properties`

```properties
countries=Brazil,France,India
languages=Java,Python,Rust
systems=Linux,Windows,macOS
```

---


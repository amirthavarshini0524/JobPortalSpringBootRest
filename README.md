# JobPortalSpringBootRest

[![Java](https://img.shields.io/badge/Java-17-blue)](https://www.oracle.com/java/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen)](https://spring.io/projects/spring-boot)
[![Build: Maven](https://img.shields.io/badge/Build-Maven-orange)](https://maven.apache.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-lightgrey)](LICENSE)
[![Contributions](https://img.shields.io/badge/Contributions-Welcome-blueviolet)](CONTRIBUTING.md)

A backend REST API built with **Spring Boot**.  
It supports user authentication, job posting, and application workflows.

If you use the React frontend, you can include it as a submodule under `/frontend`.

**Frontend Repo:**  
https://github.com/amirthavarshini0524/JobPortalFrontEndReact

---

## Features

- **Job Management**  
  - Create / update / delete jobs  
  - View job listings  

- **Application Workflow**  
  - Apply for jobs  
  - View applications
  - add jobs

---

## Tech Stack

| Layer         | Technology                  |
|---------------|-----------------------------|
| Backend       | Spring Boot                 |
| Database      | PostgreSQL                  |
| ORM           | Hibernate / JPA             |
| Build Tool    | Maven                       |
| API Style     | REST + JSON                 |

---

## Project Structure

```text
JobPortalSpringBootRest/
├── src/
│   ├── main/java/com/jobportal/…
│   └── main/resources/
│       └── application.properties
├── pom.xml
├── frontend/        # optional — React frontend submodule
└── README.md

# 95RAP (HillRAP) - Reading Achievement Program

## Overview

**95RAP** (formerly **HillRAP**) is an interactive educational platform designed to support students with learning difficulties in enhancing their literacy skills. By providing a structured, teacher-led curriculum through an engaging app, 95RAP helps bridge the achievement gap, ensuring that learners catch up academically with their peers.

## Problem

Many students with learning difficulties fall behind their peers in literacy skills, creating an achievement gap that can adversely impact their educational journey and future opportunities. These students require structured, personalized support to improve their reading abilities effectively.

## Solution

The **95RAP application** offers a comprehensive solution by delivering a guided, teacher-led curriculum through an intuitive educational app. Key features include:

- **Personalized Learning:** Adaptive lessons tailored to each student's unique needs.
- **Targeted Exercises:** Focused activities that address specific literacy challenges.
- **Progress Tracking:** Real-time monitoring of student performance and growth.
- **Adaptive Instruction:** Lessons that adjust based on student progress and feedback.

This systematic instruction empowers educators to provide targeted support, helping learners steadily improve their reading skills and close the achievement gap.

## Project Status

In 2023, HillRAP was acquired by **95 Percent Group** and integrated into their broader educational ecosystem. Our development team at **Code the Dream** successfully established a multi-tenant architecture that supports both the instructional and administrative applications. By leveraging a shared database and scalable infrastructure, we ensure secure, efficient, and seamless operations across all tenants within the platform.

## Technology Stack

### Instruction App

- **Frontend:**

  - **React:** Utilized for building a dynamic and responsive user interface, incorporating some legacy Redux components for state management.
  - **Chakra UI:** Employed as the component library to ensure a clean, accessible, and consistent design.
  - **SignalR:** Implemented for real-time messaging capabilities, enhancing interactive features between teachers and students.

- **Backend:**
  - **ASP.NET Core:** Serves as the robust framework for building the backend services.
  - **Entity Framework Core ORM:** Facilitates efficient database interactions and management.
  - **SQL Server:** Acts as the primary database for storing and retrieving application data.
  - **Docker:** Used for containerizing applications, ensuring consistency across different environments.
  - **Azure DevOps:** Manages code repositories, sprint planning, and continuous integration/continuous deployment (CI/CD) pipelines.

### Admin App

- **Frontend:**

  - **React:** Provides a consistent and user-friendly interface for administrators.
  - **Bulma UI:** Utilized as the component library to create a responsive and modern admin dashboard.

- **Backend (Microservices):**

  - **Nest.js:** Chosen for building scalable and maintainable backend services.
  - **Prisma ORM:** Enables type-safe database interactions and schema management.
  - **Microservices Architecture:** Divided into separate services for Training, Rostering, Reports, and Licensing to ensure modularity and scalability.
  - **Azure Service Bus:** Facilitates reliable inter-service communication.
  - **Docker:** Ensures containerization and consistent deployment of microservices.
  - **Azure DevOps:** Handles code management, sprint planning, and CI/CD processes.

- **Real-Time Communication:**
  - **SignalR & Azure Web PubSub:** Integrated to deliver real-time updates and notifications within the admin interface.

<!-- ## My Role

As a member of the **Code the Dream** development team, I contributed to the successful integration and enhancement of the 95RAP platform by:

- **Developing Multi-Tenant Architecture:** Designed and implemented a scalable architecture that supports multiple tenants, ensuring data isolation and security.
- **Enhancing User Interfaces:** Worked on refining the user-facing applications using React, Chakra UI, and Bulma to improve usability and accessibility for both instructors and administrators.
- **Backend Development:** Assisted in building and maintaining backend services using ASP.NET Core, Nest.js, and Prisma ORM, ensuring robust and efficient data management.
- **Real-Time Features:** Implemented real-time communication features using SignalR and Azure Web PubSub to enhance interactive capabilities within the app.
- **Collaboration & DevOps:** Utilized Azure DevOps for effective code management, sprint planning, and continuous integration/deployment, facilitating smooth development workflows. -->

## Repository

_Note: The original project repository is private on Azure. This public repository provides a summarized overview of the 95RAP (HillRAP) project for demonstration purposes._

## Contact

For more information about my work on 95RAP (HillRAP), feel free to reach out:

- **95 Percent Group:** [95percentgroup](https://www.95percentgroup.com/)
- **Partner Organization:** [Code The Dream](https://codethedream.org/)
- **Web:** [DevArts](https://devarts.notion.site/61c6b79808ce476290c753165851b070?v=9d442848a814451fba7a2e1b99bebb9b)
- **LinkedIn:** [Amir Olyaei](https://linkedin.com/in/amirolyaei)
- **GitHub:** [AmirhosseinOlyaei](https://github.com/AmirhosseinOlyaei)

---

_This project showcases my experience in developing scalable educational applications, and working with modern frontend and backend technologies to deliver impactful solutions in the education sector._

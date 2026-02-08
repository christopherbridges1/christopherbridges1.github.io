---
layout: page
title: Narratives
permalink: /narratives/
---

## Artifact Narrative: Grazioso Salvare Web Application

### Artifact Description

The artifact included in this ePortfolio is the Grazioso Salvare application.
I originally created this project in CS 340: Client/Server Development as a Python-based Dash application that supported basic CRUD operations.
For my CS 499 Capstone, I rebuilt and expanded the project into a modern, full-stack web application using a MEAN-style architecture and cloud-hosted services.
This evolution reflects how my skills developed throughout the program, moving from foundational concepts to a modern, production-style software development.

### Why I Chose This Artifact
I chose this artifact because it shows my growth across multiple areas of computer science within a single project.
Instead of working on separate projects, I wanted to take an existing application and push it further by redesigning its structure, improving how data is handled, and adding security and scalability considerations.
By enhancing the same artifact across software design and engineering, algorithms and data structures, and databases, I was able to make design decisions and see how changes in one area affect the system as a whole.

### [Software Design and Engineering Enhancements](/assets/3-2 Milestone Two.docx)
One of my main goals was to turn the original project into something that more closely resembles a real-world application.
I separated the application into a RESTful backend and a component-based front end, which made the code easier to maintain and reason about.
I added role-based authentication and authorization so that administrative features are protected and only accessible to authorized users. 
Environment-based configuration was introduced to keep sensitive information out of the codebase and support both local development and cloud deployment.
The application was deployed to Microsoft Azure, giving me experience with hosting and managing a cloud based web application.

### [Algorithms and Data Structures Enhancements](assets/4-2 Milestone Three Enhancement Two Algorithms and Data Structure.docx)
For the algorithms and data structures section, I focused on improving how the application handles user interactions and decision-making.
Using a unified login process,  allows both customers and administrators to log in through a single entry point while still being routed to the correct areas of the application based on their role.
Additional logic was added to validate input, manage application state, and efficiently handle user-specific data such as favorites.
These improvements required thinking through how data flows through the system and how different conditions should be handled in a predictable and secure way.

### [Database Enhancements](assets/5-2 Milestone Four Enhancement Three Databases.docx)
The original version of the project relied on a simple database setup, so a major part of the enhancement was designing a more robust, cloud-hosted database.
I implemented a document-based database using MongoDB concepts through Azure Cosmos DB and structured the data using Mongoose schemas to enforce consistency and validation.
Multiple collections were created to support users, animals, and favorites, and relationships between them were handled through document references.
Secure CRUD operations were implemented to support application functionality while maintaining data integrity and security.

### Reflection on the Process
Rebuilding this application was more challenging than I initially expected, especially when it came to restructuring the architecture and deploying everything to the cloud. 
Working through these challenges helped me better understand how real-world applications are developed, tested, and maintained.
Throughout the process, I applied feedback from coursework and learned to adapt my approach as new issues came up. 
By the end of the project, the application had grown from a basic  assignment into a more realistic system that reflects professional development practices.

### Course Outcomes Alignment
Through the enhancement of this artifact, I was able to demonstrate the following Computer Science program outcomes:
- Designing and evaluating computing solutions using algorithmic principles
- Applying software engineering practices to create secure and maintainable systems
- Building and integrating database-driven applications
- Demonstrating a security mindset through authentication, authorization, and secure configuration
- Using modern tools and cloud technologies to deliver practical software solutions

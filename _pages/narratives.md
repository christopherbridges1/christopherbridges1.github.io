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

### [Software Design and Engineering Enhancements](/assets/Narrative Software Design and Engineering Enhancements.docx)
One of my main goals was to turn the original project into something that more closely resembles a real-world application.
I separated the application into a RESTful backend and a component-based front end, which made the code easier to maintain and reason about.
I added role-based authentication and authorization so that administrative features are protected and only accessible to authorized users. 
Environment-based configuration was introduced to keep sensitive information out of the codebase and support both local development and cloud deployment.
The application was deployed to Microsoft Azure, giving me experience with hosting and managing a cloud-based web application.
Through these enhancements, I demonstrated the ability to apply software engineering practices aligned with SLDC. 
I defined requirements, separated architectural concerns, implemented modular design, and fully tested before each deployment.
The use of role-based authentication and environment configuration shows a design approach that meets real world production requirements.
These improvements also supported collaborative review by improving readability, maintainability, and clarity for future developers or stakeholders.

### [Algorithms and Data Structures Enhancements](/assets/Narrative Algorithm and Data Structure Enhancements.docx)
For the algorithms and data structures section, I focused on improving how the application handles user interactions and decision-making.
Using a unified login process allows both customers and administrators to log in through a single-entry point while still being routed to the correct areas of the application based on their role.
Additional logic was added to validate input, manage application state, and efficiently handle user-specific data such as favorites.
These improvements required thinking through how data flows through the system and how different conditions should be handled in a predictable and secure way.
I applied algorithmic thinking for authentication, routing, and user-specific data handling.
I used pseudocode and planning to define decision branches before implementation ensuring predictable and secure behavior.
I evaluated tradeoffs like the unified login logic versus separating user types, prioritizing maintainability and scalability.
These enhancements demonstrate my ability to design solutions using algorithmic principles while communicating the reasoning behind them.

### [Database Enhancements](/assets/Narrative Database Enhancements.docx)
The original version of the project relied on a simple database setup, so a major part of the enhancement was designing a more robust, cloud-hosted database.
I implemented a document-based database using MongoDB concepts through Azure Cosmos DB and structured the data using Mongoose schemas to enforce consistency and validation.
Multiple collections were created to support users, animals, and favorites, and relationships between them were handled through document references.
Secure CRUD operations were implemented to support application functionality while maintaining data integrity and security.
The database redesign shows technical growth and a security mindset.
I implemented schema validation, enforced structured data modeling, and secured CRUD operations to protect data privacy.
I selected an approach that balances performance and scalability when considering design tradeoffs.
By incorporating validation and access control at multiple layers, I demonstrated the ability to predict vulnerabilities and design defensively.

### Reflection on the Process
Rebuilding this application was more challenging than I initially expected, especially when it came to restructuring the architecture and deploying everything to the cloud. 
Working through these challenges helped me better understand how real-world applications are developed, tested, and maintained.
Throughout the process, I applied feedback from coursework and learned to adapt my approach as new issues came up. 
By the end of the project, the application had grown from a basic assignment into a more realistic system that reflects professional development practices.

### Course Outcomes Alignment
Enhancing the Grazioso Salvare application demonstrates growth across collaborative development, communication, algorithmic design, software engineering practices, and database principles while maintaining a security first mindset.
By restructuring the application into a modern full stack web application, performing a code review, documenting design decisions, testing, and deploying securely to the cloud, I demonstrated my abilities to perform at a professional level.
Rather than focus on functionality, I emphasized maintainability, scalability, and security.
Software development is more than simply writing code; It's about data protection, supporting stakeholders, and making informed architectural decisions that align with industry standards.  


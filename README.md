# UniConnect
**NOTE**

Main project code repository is private.
## Introduction:
The main objective of this web portal is to provide the digital platform to freshmen to connect with students sharing the same area of interest. Students can search for other student's profiles on various search terms like the stream, job role, university, etc. Students can view the profile without forming a connection with other students. However, to send messages they need to have a connection with the other student. The profile consists of a students’ professional experience, semester wise courses completed, internships/co-op, full-time job role, skillset, etc. Freshman can go through such sections from other student profiles, this will help them to develop their skillset and plan for the courses. This application consist of multiple roles and each role is associated with the set of functionalities.
## Functionalities:
This application consists of students across all the universities and to manage that we need operations that can be managed by SuperUser. Afterward, each university consists of multiple courses and professors that are associated with the courses and to manage that we need operations that can be managed by UniversityAdmin. These two roles play an essential role in the development of the backend for the application. The User i.e. student has a set of functionalities that we will discuss later.
### List of Functionalities:
- CRUD Universities with validations
- CRUD Courses and Professors with validations
- University email-based registration and authentication
- Password encryption using SHA-256
- Data association between multiple entities
- Searching users using various filters i.e. search by university name, aspired role, etc
- Accept, Reject, Remove, Send a connection request to users
- Messaging between the users using Websocket
- Course-professor mapping Request from student to university admin
- Implementation of Filters to implement Xss Validations
- Pagination of the search results
### Technology Stack:
- View/Presentation Layer - JSP
- Business Logic Layer - Spring MVC Java Controller using annotations and Hibernate
- Data Layer – MySQL

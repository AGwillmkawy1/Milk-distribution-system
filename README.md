# Milk-distribution-system
This project is designed to handle the report when some schools needs Milk to be distributed to them

Minister adding Head of teacher and school name where Milk will be delivered.
![Screenshot 2023-12-16 160716](https://github.com/AGwillmkawy1/Milk-distribution-system/assets/93640193/1b83a6b9-feb0-4354-a1ff-ee33acb2f594)

Distributor interface
![new](https://github.com/AGwillmkawy1/Milk-distribution-system/assets/93640193/5f3e9ff7-66c7-4475-aadb-ff8354a6e773)


Head of teacher approving the order and give feedback to those who deliver Milk
![Screenshot 2023-12-16 161124](https://github.com/AGwillmkawy1/Milk-distribution-system/assets/93640193/dfe60ee0-891c-4b1e-b2e2-6879fdc38307)


Approving orders on the order interface
![Screenshot 2023-12-07 160034](https://github.com/AGwillmkawy1/Milk-distribution-system/assets/93640193/21505662-2380-4a2c-9048-c65c26756202)


Adding new User to be able to use our system
![Screenshot 2023-12-16 180457](https://github.com/AGwillmkawy1/Milk-distribution-system/assets/93640193/f1de3854-865f-492a-aabc-1143c89955e1)

Inyange admin page to be to coordinate and monitor everything being done in the system
![Screenshot 2023-12-16 180933](https://github.com/AGwillmkawy1/Milk-distribution-system/assets/93640193/87c57b74-5c9d-4f5b-ab2a-82a6b6220c03)


View shcools added by Minister because He/she is the one who add schools where Milk will be delivered
![Screenshot 2023-12-16 181252](https://github.com/AGwillmkawy1/Milk-distribution-system/assets/93640193/800b066f-8635-47e7-b520-c583c2740499)



Documentation
===========


ID: 23608
NAMES: Jean Plaubert RUKUNDO

## Milk Distribution System
## PROJECT REQUIREMENTS

THE PURPOSE OF THE PROJECT
Coordinating and monitoring Milk being distributed in Schools for students to be able to access a cup of Milk in schools even though some student may be able to drink milk home but then each student at school get a cup of milk for health as future professionals, and also manage the schools, distributors and minister who is in charge of schools to make the work easier and automated.
## EXPECTED OUTCOME
-	Manages to add schools
-	Manages Milk being delivered in schools
-	Manages Distributor being deliver milk in school
-	Manages Schools to approve milk being delivered.
## SPECIFIC CONSTRAINTS OR LIMITATIONS
- The system is not allowing anyone to register themselves to be able to use the system but then it allows admin to add users afterward user receive an email for login credentials to get Role Based Access Control as this system it’s for Inyange, schools, Ministers in charge of schools and Distributors, no one else.


## FUNCTIONAL REQUIREMENTS

-	The system should have administrator to control the system and be able to add users in the system
-	The system should have ministers to have ability to add new schools to the system, including relevant details such as school name, address, contact information, and delivery schedule preferences.
-	The system should have Milk page so that admin can add any type of milk
-	View and manage a list of all registered schools.
-	The system should have distributors to have ability to update delivery schedules, routes, and quantities based on demand and logistics.
-	The system should have school page where to specify the quantity and type of milk required for each delivery
-	The system should have school page where access delivery schedules, track deliveries, and provide feedback on the quality of delivered products.


## NON-FUNCTIONAL REQUIREMENTS
-	Implement logging mechanisms for admin to track system activities, facilitating auditing and traceability of actions performed by users.
-	The system should allow emails to be sent to users to get an access to the system.
-	Load testing : Conducting regular load testing to ensure the system can handle peak loads without performance issues.
-	Performance requirements ensuring responsiveness and scalability
-	The system code must be easy to read and understand, with clear naming conventions, comments, and documentation.
-	The system must be developed following best practices for code maintainability, such as using design patterns, avoiding code duplication, and keeping code complexity to a minimum.
-	The system must be able to perform its functions efficiently and without errors under different load conditions, such as high traffic or peak usage.
-	The system shall able to run on window 10 or window 11 without change in its behavior.


   

 ##                                                                                       PROJECT PLAN


## PROJECT PLAN

-	Project Initiation Phase (1 day)
-	Define project objectives, 
-	Define scope
-	Define requirements.
-	Develop a high project level plan
-	Requirements gathering and analysis phase (1 day)
-	Conduct detailed requirements gathering sessions 
-	Analyze existing processes and systems to identify gaps and improvement opportunities.
-	Document functional and non-functional requirements
-	Prioritize requirements based on their importance and feasibility.
-	System Design Phase (1 day)
-	Develop a detailed system architecture and design
-	Design Database Schema
-	Create wireframes and user interface mockups
-	Development Phase (7 days)
-	Implement the student management system based on the approved design
-	Develop module for student registration
-	Conduct regular sprints and iterations
-	Perform unit testing to ensure functionality and quality of individual components
-	Testing Phase (1 day)
-	Conduct system testing to verify end-to-end functionality of the system
-	Perform integration system to ensure smooth interactions between the module
-	Identify any identified issues or bugs
-	Deployment (1 day)
-	Prepare the production environment for the deployment
-	
## RESOURCES USED IN THE PROJECT

-	 Project Team
-	Project manager
-	Software and Tools: Spring MVC
-	Integrated Development Environment (IDE): IntelliJ
-	Database Management System (DBMS): MySQL
-	Version Control System: Git
-	Training and Documentation: 
-	Training Materials: guides and training videos
-	Documentation Tools: Google Docs for creating project documentation


## DATABSE SCHEMA
![Screenshot 2023-12-16 204740](https://github.com/AGwillmkawy1/Milk-distribution-system/assets/93640193/b890272a-34ff-4206-98e7-686e6d11f71a)



##                                                USER DOCUMENTATION
Admin should login using email and password that he was assigned, and then starts to create minister who will manage schools and approve milk distribution from a certain distributor, and add schools.
Schools will be added by minister and make an order for a school, then after school will approve that order and distributor will deliver the milk with a certain quantity. And when the milk reach to them they will give feedback.

##                                                                               	TECHNICAL DOCUMENTATION
-	Architecture
-	The student registration systems follow the Model-View-Controller (MVC) architectural pattern
-	The backend is implemented using Java programming language and Spring boot framework
-	The frontend is developed using HTML, CSS and JavaScript
-	Development Environment
-	Operating system: Windows 11
-	IDE: IntelliJ
-	Database: MySQL
-	Backend Implementation
-	The backend is implemented using Java and Spring boot
-	The project is organized into different packages such as controllers, services, models and repositories.
-	Data persistence is achieved using HTML, CSS and JavaScript
-	Input validation and error handling are implemented using Spring validation and exception handling mechanisms
-	Frontend Implementation
-	The frontend is developed using HTML, CSS and JavaScript
-	Thyme leaf template engine is used for server-side rendering of dynamic webpages
-	Bootstrap is used for responsive
-	 Client-side form validation is implemented using JavaScript 
-	Database Implementation
-	The database is implemented using MySQL
-	The database Schema is used to store student information and their login credentials
-	Security
-	User authentication and authorization are implemented using spring security
-	Access control is enforced based on user role and permission
-	Deployment
-	Configuration files such as application.properties is used to specify database connection settings and other system properties.
-	Testing
-	Integration testing is conducted to test the interaction between different pages of the system.
-	Logging and Error handling
-	Custom error page or exceptions handlers are implemented to provide a user-friendly experience in case of errors.
-	Errors and exceptions are logged with appropriate severity and error messages.
-	Maintenance
-	The system is maintained using version control systems such as Git to track changes.
-	Regular updates and bug fixes are performed to ensure system stability and security.
-	System documentation is updated to reflect any changes or enhancements made to the system.


Admin Credentials
================
User: Admin
Email: admin@gmail.com
Password: admin



User: Minister
Email: engplaubert@gmail.com
Password: 539476-582405



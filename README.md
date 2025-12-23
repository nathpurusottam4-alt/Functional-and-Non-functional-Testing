# Functional-and-Non-functional-Testing
In software engineering, testing is categorized into functional and non-functional types, which together ensure that an application works correctly and provides a high-quality user experience.
1. Functional Testing
Functional testing verifies what the system does. It focuses on the business requirements and specific features of the software. 
Objective: To validate that each function of the software operates in conformance with the requirement specifications.
Key Characteristics:
Typically follows "black-box" testing methods (inner code is not examined).
Results are often binary (Pass/Fail) based on expected behavior.
Commonly performed manually but can be automated.
Examples:
User Login: Checking if a user can successfully log in with valid credentials.
Form Submission: Ensuring a registration form saves data correctly to the database.
Payment Processing: Verifying that a payment gateway correctly processes a transaction.
Types of Functional Testing:
Unit Testing: Testing individual components in isolation.
Integration Testing: Verifying that different modules work together correctly.
Regression Testing: Ensuring new changes haven't broken existing features.
User Acceptance Testing (UAT): Final check by users to see if the system meets their needs. 

2. Non-functional Testing
Non-functional testing evaluates how the system performs. it focuses on the quality attributes and overall user experience rather than specific features. 
Objective: To verify the system's readiness, performance, and reliability under various conditions.
Key Characteristics:
Evaluated on a scale (e.g., response time in seconds) rather than a simple pass/fail.
Usually automated because it requires simulating hundreds or thousands of users.
Focuses on the "ilities": Scalability, Usability, Reliability, and Security.
Examples:
Performance: Does the dashboard load within 2 seconds?
Load Handling: Can the site handle 10,000 concurrent users without crashing?
Security: Is the application protected against unauthorized access or SQL injection?
Types of Non-functional Testing:
Performance Testing: Checking speed, responsiveness, and stability.
Load/Stress Testing: Testing behavior under normal and extreme workloads.
Security Testing: Identifying vulnerabilities and protecting data.
Usability Testing: Checking how user-friendly and intuitive the interface is. 
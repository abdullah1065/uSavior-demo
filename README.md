# uSavior-demo [Website source code in Private mode]

uSavior is an Academic Aid & Online Education Based platform tailored for students and instructors. It offers an extensive range of related courses, interactive features, and personalized learning experiences.


## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Use Case Diagram](#use-case-diagram)
- [Tech Stack](#tech-stack)
- [Installation Guide](#installation-guide)
- [How to Use](#how-to-use)

<a href="https://ibb.co/9w7j11S"><img src="https://i.ibb.co/4sHxXX3/Capture1.png" alt="Capture1" border="0"></a>

## Project Overview
Education has evolved, and uSavior is designed to meet the growing demands of students and instructors in CSE. The platform allows students to choose from a vast catalog of courses, complete with lecture videos, reading materials, assignments, and quizzes. Instructors can create their own accounts, manage course materials, and interact with students.

## Features

### For Students
- Create accounts and enroll in courses
- Browse a wide range of CSE-related courses
- Access lecture videos, reading materials, assignments, and quizzes
- Get notifications about updates and deadlines
- Secure payment gateway for course purchases

### For Instructors
- Create courses and upload lecture materials
- Manage student performance and track progress
- Connect with students and provide feedback

### For Admins
- Manage student and instructor accounts
- Approve or reject instructor applications
- Add new courses and handle platform-related activities

## Use Case Diagram
A use case diagram is included to depict the interaction of students, instructors, and admins with the system.

## Tech Stack
<p align="left"> <a href="https://getbootstrap.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://flask.palletsprojects.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/pocoo_flask/pocoo_flask-icon.svg" alt="flask" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> </p>

- **Deployment**: Vercel [uSavior Platform](https://usavior.vercel.app/home)

## Installation Guide
1. Clone the repository:
    ```bash
    git clone https://github.com/abdullah1065/uSavior.git
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Set up MongoDB and configure the necessary databases (`Admin`, `Local`, `uSavior`).
4. Run the application:
    ```bash
    flask run
    ```

## How to Use

### For Students
1. Register for an account.
2. Browse the course catalog and select courses to enroll.
3. After payment, access your courses through the dashboard.

### For Instructors
1. Register and request courses to teach.
2. Upload course materials and manage student performance.

### For Admins
1. Login to the admin dashboard.
2. Manage courses, students, and instructors.

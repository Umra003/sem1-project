# Personal Digital Life Dashboard

**A centralized web-based application to manage, organize, track, and visualize different aspects of everyday life from a single platform.**

---

# 1. Project Overview

Personal Digital Life Dashboard is a web-based application developed using React Native Web, Python, and the Django framework. It provides users with a centralized platform to manage their daily activities, academic progress, financial records, personal goals, notes, and important events.

In everyday life, people often depend on multiple applications to manage different activities. For example, one application for maintaining notes, another for tracking expenses, another for managing tasks, and another for scheduling events.

Managing information across multiple applications can become difficult and time-consuming.

This project aims to solve that problem by bringing these different functionalities together into one integrated web application.

Users can access their personal information through a single dashboard and monitor their activities using statistics, charts, and visual summaries.

# 2. Problem Statement

Managing different aspects of daily life using separate applications makes it difficult to maintain information in one place.

Users may struggle to:

- Organize daily and weekly tasks.
- Monitor study activities and productivity.
- Maintain income and expense records.
- Track personal and academic goals.
- Store important notes.
- Remember deadlines and upcoming events.
- Understand overall productivity and spending patterns.

The Personal Digital Life Dashboard addresses these problems by providing a single web-based system for managing and monitoring different personal activities.

# 3. Project Objectives

The main objectives of this project are:

- To develop a centralized web application for personal activity management.
- To provide task management functionality.
- To record and analyze study sessions.
- To maintain income and expense records.
- To create and monitor personal and academic goals.
- To provide a digital space for maintaining notes.
- To manage important events and deadlines.
- To display useful statistics and visualizations.
- To provide reminders for upcoming activities.
- To ensure that each user can securely manage their own information.

# 4. Main Features and Modules

## 4.1 User Authentication

Provides secure access to the application.

Features:

- User registration.
- User login and logout.
- Personalized dashboard.
- User-specific data management.

## 4.2 Task Manager

Helps users organize and manage daily and weekly activities.

Features:

- Create new tasks.
- Edit and delete existing tasks.
- Set task priorities.
- Assign due dates.
- Mark tasks as completed or pending.
- Track task completion.

## 4.3 Study Tracker

Allows users to record their study activities and monitor the time spent on different subjects.

Features:

- Add study sessions.
- Select subjects.
- Record study dates and durations.
- View total study hours.
- Monitor subject-wise study time.
- Analyze study patterns through charts.

## 4.4 Expense Tracker

Helps users maintain their personal financial records.

Features:

- Record income and expenses.
- Select transaction categories.
- Enter transaction amounts and dates.
- Calculate total income and expenses.
- View remaining balance.
- Analyze category-wise spending.

## 4.5 Goal Tracker

Allows users to create and monitor personal, academic, and professional goals.

Features:

- Create goals.
- Set target dates.
- Update goal progress.
- Monitor ongoing goals.
- Track completed goals.

## 4.6 Notes Module

Provides a digital space for storing personal information and important notes.

Features:

- Create notes.
- View saved notes.
- Edit existing notes.
- Delete notes.
- Organize important information.

## 4.7 Calendar and Events

Helps users organize important dates and scheduled activities.

Features:

- Add events.
- Set event dates.
- Record important deadlines.
- View upcoming events.
- Keep track of scheduled activities.

## 4.8 Dashboard and Analytics

The dashboard provides an overview of the user's activities in one place.

It can display:

- Total tasks.
- Completed and pending tasks.
- Total study hours.
- Subject-wise study statistics.
- Total income and expenses.
- Goal progress.
- Upcoming events.

Python and Matplotlib will be used for relevant data analysis and visualization. Charts and statistical information will be displayed within the web application's dashboard.

## 4.9 Notifications and Reminders

Helps users remember important activities and deadlines.

Features:

- Upcoming task reminders.
- Event notifications.
- Goal deadline reminders.
- Important activity alerts.

# 5. Technology Stack

| Component | Technology |
|---|---|
| Frontend | React Native Web |
| Programming Language (Frontend) | JavaScript |
| Backend Programming Language | Python |
| Backend Framework | Django |
| API Framework | Django REST Framework |
| Database | MySQL |
| Data Analysis and Visualization | Python, Matplotlib |
| Code Editor | Visual Studio Code |
| Version Control | Git and GitHub |

## Technology Explanation

**React Native Web:** Used to build the frontend interface using reusable React Native components that can run in web browsers.

**JavaScript:** Used for frontend programming, component logic, and user interactions.

**Python:** Used for backend programming, application logic, and data processing.

**Django:** A Python-based web framework responsible for backend functionality, authentication, database operations, and application logic.

**Django REST Framework:** Used to create REST APIs that allow the frontend and backend to communicate.

**MySQL:** A relational database management system used to store user accounts and application data, including tasks, study sessions, expenses, goals, notes, and events.

**Matplotlib:** A Python library used to generate charts and graphical representations of study statistics, expenses, and productivity.

**Git and GitHub:** Used for version control, project management, and tracking development progress.

# 6. System Architecture

The application follows a client-server architecture.

The frontend and backend communicate through HTTP requests and API endpoints.

The general workflow is:

1. The user interacts with the application through a web browser.
2. React Native Web handles the user interface and user interactions.
3. API requests are sent to the Django backend.
4. Django receives and processes the requests.
5. Django models communicate with the MySQL database.
6. The requested information is retrieved or stored.
7. Django sends the response to the frontend through APIs.
8. React Native Web displays the updated information to the user.

**Architecture Flow:**

User → Web Browser → React Native Web → REST API → Django Backend → MySQL Database

The response is returned from Django to React Native Web and displayed in the browser.

# 7. Database

MySQL is used as the database management system.

The database stores information related to:

- User accounts.
- Tasks.
- Study sessions.
- Expenses and income.
- Goals.
- Notes.
- Calendar events.
- Reminders.

Each user's personal records will be associated with their account to maintain data separation.

Django ORM (Object-Relational Mapping) will be used to interact with MySQL and perform database operations without manually writing SQL queries for every operation.

# 8. Application Workflow

The general application workflow is:

1. The user opens the website.
2. The user registers or logs into their account.
3. After successful authentication, the user accesses their personalized dashboard.
4. The user selects the required module.
5. The user adds, views, updates, or deletes information.
6. React Native Web sends the required API request to Django.
7. Django processes the request and stores or retrieves information from MySQL.
8. The dashboard displays updated

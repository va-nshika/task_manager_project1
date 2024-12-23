# Task Manager System with SQL Dataset

## Introduction
The **Task Manager System** is a comprehensive SQL-based project designed to manage users, projects, tasks, and statuses. This repository includes a large dataset (10,000+ tasks, 100 users, and 50 projects) and SQL scripts that allow you to explore and manipulate task management data effectively. It’s an ideal project for learning SQL, practicing database schema design, and analyzing large datasets for real-world applications.

The system is built to simulate a typical task management system used in a workplace to assign and track the progress of tasks related to various projects. The project is especially useful for those who wish to enhance their SQL skills by working with large-scale datasets and real-world business logic.

## Features
- **Predefined Relational Database Schema**: 
  The system consists of four interconnected tables that represent different components of task management:
  - **Users**: This table manages users of the system, where each user can have different roles such as Developer, Tester, Manager, etc.
  - **Projects**: This table tracks project details including timelines, milestones, and project status.
  - **Tasks**: Tasks are assigned to users within the context of a project. This table manages task priorities, deadlines, and completion status.
  - **Statuses**: This table tracks the progress of tasks (e.g., "Not Started", "In Progress", "Completed").

- **Large Dataset**: 
  The project includes a sample dataset with over 10,000 tasks, 100 users, and 50 projects to help you practice SQL queries, database design, and optimization strategies. The dataset mimics real-world scenarios of task assignment, project timelines, and user roles.

- **SQL Scripts**: 
  - **Database Schema Creation**: SQL scripts to create the database and set up all required tables with necessary relationships (Foreign Keys, Indexes).
  - **Database Seeding**: Scripts to populate the database with sample data (tasks, users, projects, and statuses). This helps you to simulate real-world queries without having to manually insert data.
  - **SQL Queries**: Sample queries to help you practice various operations like filtering tasks by user, project, or status, as well as performing aggregate functions.

## Use Cases
- **Learn SQL**: Ideal for beginners and intermediate learners to gain hands-on experience with real-world datasets. This system allows you to practice SQL queries for tasks like filtering, joining, grouping, and optimizing queries.
- **Task and Project Management**: Perfect for learning how to design and implement a task management system from the database perspective. Learn to track users, assign tasks, and manage projects.
- **Advanced Query Development**: Build complex queries for analyzing the performance of tasks, tracking project progress, and optimizing database operations. You can also practice writing reports on project status, user workloads, and task completions.
- **Build Applications**: Use this dataset to build web applications, dashboards, or other task management tools that can integrate with this backend.

## Project Structure
The project structure consists of SQL scripts and data files to set up and interact with the Task Manager System:
### Database Setup
To set up the **Task Manager System** on your local machine, follow these steps:

1. **Clone the repository**: 
   Clone the repository to your local machine using the following command:
   ```bash
   git clone https://va-nshika/task_manager_project1.git
2. Database Creation
   ```bash
   create database db_project;
    use db_project;
2. Database Creation
   ```bash
   create database db_project;
    use db_project;
3. table creation
   a. **User** table creation
    ```bash
    CREATE TABLE Users (
    user_id INT AUTO_INCREMENT PRIMARY KEY,
    username VARCHAR(50),
    email VARCHAR(100),
    role VARCHAR(50)
    );
  



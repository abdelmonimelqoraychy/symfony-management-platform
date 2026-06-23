# Symfony Management Platform

## Description

Symfony Management Platform is a web application developed to manage academic oral examination activities, commonly known as "colles", within an educational institution.

The application centralizes the management of students, teachers, modules, academic programs, rooms, and users in order to simplify administrative tasks and improve the organization of pedagogical activities.

## Objectives

The main objectives of this project are:

* Centralize academic information
* Simplify the organization of oral examination sessions
* Manage students, teachers, modules, academic programs, and rooms
* Reduce manual administrative work
* Provide a structured system for academic management

## Main Features

### Student Management

* Add new students
* Edit student information
* Delete students
* View the list of registered students

### Teacher Management

* Add new teachers
* Edit teacher information
* View registered teachers

### Module Management

* Create modules
* Edit module information
* Associate modules with academic programs

### Academic Program Management

* Create academic programs
* Manage students associated with each program

### Room Management

* Register available rooms
* Organize room usage

### Authentication

* User login
* Secured access to the application

## System Actors

### Administrator

The administrator is responsible for managing users, students, teachers, modules, academic programs, and rooms.

### Teachers

Teachers are associated with modules and participate in the academic activities managed by the system.

### Students

Students belong to academic programs and follow different modules.

## Technologies Used

* PHP
* Symfony Framework
* Twig
* MySQL
* Doctrine ORM
* HTML
* CSS
* Bootstrap
* JavaScript

## Project Structure

```text
symfony-colle-management-system/
│
├── src/
│   ├── Controller/
│   ├── Entity/
│   ├── Form/
│   └── Repository/
│
├── templates/
│
├── public/
│
├── migrations/
│
├── config/
│
├── README.md
└── composer.json
```

## How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/symfony-colle-management-system.git
```

2. Enter the project folder:

```bash
cd symfony-colle-management-system
```

3. Install dependencies:

```bash
composer install
```

4. Configure the database in the `.env` file:

```env
DATABASE_URL="mysql://username:password@127.0.0.1:3306/database_name"
```

5. Create the database:

```bash
php bin/console doctrine:database:create
```

6. Run migrations:

```bash
php bin/console doctrine:migrations:migrate
```

7. Start the Symfony server:

```bash
symfony server:start
```

## Future Improvements

* Add scheduling for oral examination sessions
* Add role-based access control
* Add dashboards and statistics
* Add PDF export for reports
* Improve user interface and responsiveness
* Add notification system for students and teachers

## Author

Developed as an academic project in computer science.

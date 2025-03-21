# Course Registration System

The **Course Registration System** is a web application that allows students to register for courses, manage their schedules, and receive notifications when seats become available. Admins can manage courses, view student registrations, and override registrations in special cases.

## Features

### Student Features
- **View Available Courses**: Students can view a list of available courses with details such as department, level, available seats, and schedule.
- **Register for Courses**: Students can register for courses with available seats.
- **Drop Courses**: Students can drop courses they are registered for.
- **Subscribe for Notifications**: Students can subscribe to courses with no available seats and receive notifications when seats become available.
- **View Registered Courses**: Students can view a list of courses they are currently registered for.

### Admin Features
- **Manage Courses**: Admins can add, update, and delete courses.
- **View Student Registrations**: Admins can view and manage student registrations.
- **Override Registrations**: Admins can override registrations to add students to full courses in special cases.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **APIs**: RESTful APIs for communication between frontend and backend

## Setup Instructions

### Prerequisites
- **Node.js**: Install Node.js from [nodejs.org](https://nodejs.org/).
- **MongoDB**: Install MongoDB from [mongodb.com](https://www.mongodb.com/).
- **Git**: Install Git from [git-scm.com](https://git-scm.com/).

### Step 1: Clone the Repository
```bash
git clone https://github.com/MNoman-ijaz/Course-Registration-System.git
cd Course-Registration-System

Step 2: Install Dependencies
cd backend
npm install
Start the backend server:
node server.js

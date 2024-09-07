# Fitness-Slot-Booking-System

This project is a Fitness Slot Booking System that allows users to view details of booked classes, filter classes based on type and date, and handle large datasets with pagination. The project consists of a Django backend for handling API requests and a React frontend for displaying data and managing user interactions.

# Table of Contents
* Project Overview
* Features
* Tech Stack
* Prerequisites
* Setup Instructions
  * Backend (Django)
  * Frontend (React)
* Running the Project
* API Endpoints
* Screenshots
* Contributing
* License


# Project Overview
The system allows users to:

1. View details of already booked classes.
2. Filter classes by class type and date.
3. Handle large datasets with pagination.
4. Backend API built with Django.
5. Frontend built with React.js.

# Features
1. Filter Classes: Users can filter classes based on class type and date.
2. Pagination: Large data sets are handled efficiently with pagination.
3. Detailed Class Information: Users can view detailed booking information for each class.
4. Modern UI: Responsive frontend built with React.js.

# Tech Stack
1. Frontend
    React.js
    React Router
    Axios for HTTP requests
2. Backend
    Django REST Framework
    Python 3.8+
    SQLite (default, can be configured to use PostgreSQL)
   
# Prerequisites
Ensure you have the following installed on your local machine:

1. Python 3.8+
2. Node.js (version 16.x or higher)
3. npm (or yarn, as per your preference)
4. Git (to clone the repository)

# Setup Instructions
   Backend (Django)

1. Clone the repository:

   git clone https://github.com/yourusername/class-booking-management.git
   cd class-booking-management
   
2. Create a virtual environment:
   
   python -m venv env
   source env/bin/activate   # For Linux/Mac
   env\Scripts\activate      # For Windows

   
3. Install Python dependencies:

   pip install -r requirements.txt

4. Run database migrations:
 
   python manage.py migrate
   
5. Start the Django server:
   
   python manage.py runserver

   
The backend API will be running at http://127.0.0.1:8000.

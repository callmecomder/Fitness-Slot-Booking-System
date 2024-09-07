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

# Frontend (React)

1. Navigate to the frontend folder:

   cd frontend

2. Install the required dependencies:

   npm install
   
3. Start the React development server:
 
   npm start

   
The frontend will be running at http://localhost:3000.

# Environment Variables

   Make sure to create a .env file in the Django root directory and add any necessary environment variables (e.g., database configurations, Django secret key, etc.).

In the frontend directory, you can also use .env for the React application (if required).

# Running the Project

1. Run the Django Backend:
   
   python manage.py runserver

2. Run the React Frontend:

   npm start
   
Access the frontend at http://localhost:3000 and the backend API at http://127.0.0.1:8000.

# API Endpoints
Here are the key API endpoints available for this project:
   * GET /api/bookings-details/?class_id=<class_id>: Get booking details for a specific class.

# Screenshots 

# Book a class :
<img width="1440" alt="Screenshot 2024-09-07 at 6 51 00 PM" src="https://github.com/user-attachments/assets/a98d3ccc-8fae-42fc-b214-a68e65f36734">

# See Booking : 
<img width="1227" alt="Screenshot 2024-09-07 at 6 51 24 PM" src="https://github.com/user-attachments/assets/5951c4d5-ec52-4a87-b6b6-dabb94b5ed4b">

# Cancel Booking : 
<img width="1440" alt="Screenshot 2024-09-07 at 6 51 47 PM" src="https://github.com/user-attachments/assets/903af339-fe15-4019-93f4-0a1734e8a805">

# List of Booking Accprding to Class type and time : 
<img width="1427" alt="Screenshot 2024-09-07 at 6 52 06 PM" src="https://github.com/user-attachments/assets/2a4de56f-ea82-4583-8da5-a62e2e1fd7c1">

# Adding user in wait list :

<img width="1439" alt="Screenshot 2024-09-07 at 7 09 22 PM" src="https://github.com/user-attachments/assets/da83d20c-ebf2-422f-a699-03647a1c5aae">






## Technical Test: Laravel Attendance System

##### Objective:

Create a web-based attendance system using Laravel, Tailwind CSS, Livewire, and AlpineJS. The system should allow users to log in, mark their check-ins and checkouts, and calculate working hours.

##### Requirements:

1. Authentication:
   - Implement user authentication using Laravel's built-in authentication system.
   - Users should have roles (e.g., admin and regular user).
2. Database Design:
   - Create a database schema for users and attendance records.
3. Dashboard:
   - Create a dashboard accessible after login.
   - Display the user's name and role on the dashboard.
   - Include a section to display the user's attendance history.
4. Mark Check-in/Check-out:
   - Users should be able to mark their check-in and check-out times.
   - Use Livewire to update the UI in real time when a user marks their attendance.
5. Working Hours Calculation:
   - Calculate and display the total working hours for the current day.
   - Users should be able to see their total working hours for any selected date range.
6. Design and Styling:
   - Use Tailwind CSS for styling the application.
7. Validation:
   - Implement validation to ensure users cannot check out before checking in.
   - Ensure that users cannot check in multiple times without checking out.
8. Role-based Access:
   - Implement role-based access control.
   - Only admin users should be able to view and edit all users' attendance records.
9. AlpineJS Features:
   - Use AlpineJS for interactive UI components.
   - Implement a confirmation modal when users try to delete an attendance record.
10. Submission Instructions:

   - Fork this repository and create a new branch for your changes. [https://github.com/idoraa/Technical-Test]

   - Provide clear documentation on how to set up and run the project.

   - Submit a pull request with your changes.


**Note:** *You are free to make additional decisions not explicitly mentioned here, as long as they align with best practices in Laravel development.*

**Important Note**: *Laravel Version - v8.6.12, PHP Version - 7.4*

##### My Solution:
I have covered below points:

1. Authentication:
   - Implement user authentication using Laravel's built-in authentication system.
   - Users should have roles (e.g., admin and regular user).
2. Database Design:
   - Create a database schema for users and attendance records.
3. Dashboard:
   - Create a dashboard accessible after login.
   - Display the user's name and role on the dashboard.
6. Design and Styling:
   - Use Tailwind CSS for styling the application.
8. Role-based Access:
   - Implement role-based access control.

I have created two roles Admin and User.
A default user is created with credentials, email: admin@yopmail.com Pass: password

##### Project Setup:
Create database and update database credentials in .env file
Run the command "php artisan migrate:fresh --seed" for initial database setup.

 


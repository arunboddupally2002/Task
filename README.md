Student Registration and Login System
Description
This is a simple web-based application for student registration and login. The system allows students to sign up, log in, and view their profile details. It features a registration page, login page, and profile page, with functionality to capture user details and display them after logging in.

Features
Student Registration: Students can fill out a form to create an account, including personal details, username, password, gender, date of birth, and course selection.

Login: Students can log in using their email and password.

Profile: After logging in, students are redirected to their profile page, which displays their student ID, name, course, date of joining, skills, and profile picture.

Logout: Students can log out from the profile page.

Project Structure
bash
Copy
Edit
/assets
    ├── Registration.html      # Student Registration Form
    ├── Login.html             # Student Login Form
    ├── Profile.html           # Student Profile Page
    ├── bikepic-fotor-20250316203827.jpg  # Profile Picture
/index.html                   # Welcome page with links to Login and Registration
Requirements
This project requires a modern web browser like Google Chrome, Firefox, or Edge for proper viewing and functionality.

Setup and Installation
Clone or download the project files to your local machine.

Open the index.html file in your browser to view the welcome page.

From the welcome page, you can navigate to the Sign-Up or Login page by clicking the respective links.

After successful login, you will be redirected to the profile page where your details are displayed.

Usage
Registration
Navigate to the Sign-Up page (Registration.html).

Fill in the required details, including First Name, Last Name, Email, Date of Birth, Username, Password, Gender, and Course.

After filling the form, click Register to submit the form. You will be redirected to the Login page.

Login
On the Login page (Login.html), enter your email and password.

Click Login to access your profile.

Profile
After logging in, you will be taken to your profile page (Profile.html), which displays:

Student ID

Name of the Student

Course taken

Date of Joining

Skills

Profile picture

You can log out by clicking the Logout button, which will take you back to the welcome page.

Future Enhancements
Integrate a backend to store user data (e.g., using PHP, Node.js, or Python with a database).

Add input validation on the server side to ensure data integrity.

Enhance the profile page with the ability to edit personal details.

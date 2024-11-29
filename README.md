# RBAC-System
The Role-Based Access Control (RBAC) System ensures secure user authentication and authorization by assigning roles like Developer, Tester, Designer, or Manager. Built with Firebase, it features role-specific dashboards, admin approval for registrations, and a secure login process with added admin protections.
Features

Secure Authentication: User login with email and password, powered by Firebase Authentication.

Role-Based Authorization: Users are redirected to role-specific dashboards based on their assigned roles.

Admin Privileges:

Approve or deny user registrations.

Require an additional security key for admin access.

User Registration: New users can sign up with their role, pending admin approval.

Database Integration: Role and user details are stored and managed via Firebase Realtime Database.

Technologies Used

Frontend: HTML, CSS, JavaScript

Backend: Firebase Authentication, Firebase Realtime Database

Version Control: Git

Setup Instructions

Clone the repository:

git clone [repository URL]

Open the project folder and configure Firebase:

Create a Firebase project.

Enable Authentication and Realtime Database.

Replace the firebaseConfig in firebase.js with your Firebase project details.

Launch the application:

Open index.html in a web browser.

How It Works

Login:

Regular users log in with their email and password.

Admin logs in with additional security key verification.

Role Management:

Roles (Developer, Tester, Designer, Manager) determine user access to specific pages.

Admin Control:

Admin approves new users before granting access.

Role-Based Redirection:

Users are redirected to their respective dashboards based on their roles.

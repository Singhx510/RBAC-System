# RBAC-System
The Role-Based Access Control (RBAC) System ensures secure user authentication and authorization by assigning roles like Developer, Tester, Designer, or Manager. Built with Firebase, it features role-specific dashboards, admin approval for registrations, and a secure login process with added admin protections.
Features:
1. Secure Authentication: User login with email and password, powered by Firebase Authentication.
2. Role-Based Authorization: Users are redirected to role-specific dashboards based on their assigned roles.

Admin Privileges:
1. Approve or deny user registrations.
2. Require an additional security key for admin access.
3. User Registration: New users can sign up with their role, pending admin approval.
4. Database Integration: Role and user details are stored and managed via Firebase Realtime Database.

# LabFlow
This organization contains source code for LabFlow, a web application for managing laboratories.

## Features
- Authentication with JWT tokens
- Role-based authorization
- Notifications: not generated usage records, reagents with close expiration date, reagent requests, few crtitical reagents and new items pending approval for admins
- Wiki with the CLP classification (H and P codes, pictograms) and a user manual
- Usage records and reports (for Sanepid/PIP, admins and project managers) generation
- Personal reagents data PDF exports
- Personal reagents and project/procedures statistics
- Reagents requests: moving personal reagents between lab users
- Personal reagents archive
- Data filtering, sorting, searching
- Forms for adding, editing and removing data
- Database logs

## Technologies
- Frontend: React
- Backend: Django with Django REST framework
- Database: PostgreSQL

Both frontend and backend use many additional packages alongside the abovementioned technologies (details in respective repos).

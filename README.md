
AIM:
This project is about creating a  website to manage hostel life. 
It will help with things like registering students, giving them rooms, 
keeping track of attendance, 
storing room photos,
and making sure approvals go smoothly between the Admin, Principal, Warden, and Students.

Backend (Server Side)
🔹 Python
Main language of this project
Handles:
Login & registration
Role management (Admin, Principal, Warden, Student)
Database operations
Business logic
🔹 Flask (Python Framework)
Web framework used to connect frontend + backend
Handles:
URLs (/login, /student, /warden, etc.)
Routing
Sessions & authentication
Rendering HTML pages
🎨 Frontend (Client Side)
🔹 HTML
Used to create pages like:
login.html
student_dashboard.html
warden_dashboard.html
principal_dashboard.html
🔹 CSS
Used for:
Styling pages
Layout
Colors, buttons, cards, etc.
Written inside <style> tags or static files
🔹 Jinja2 (Template Engine)
Used inside HTML
Connects Python data to HTML
Examples:
Copy code
Html
{{ username }}
{% for room in rooms %}
{% if attendance %}
This is how Flask sends data to HTML
🗄️ Database
🔹 SQLite
Stores:
Users
Hostels
Rooms
Attendance
Applications
File-based database (database.db)
No need to buy anything 💰
Works locally & on deployment (with limits)
📦 Other Important Technologies
🔹 SQL
Used to:
Create tables (database.sql)
Insert, update, fetch data
Example:
Copy code
Sql
SELECT * FROM users WHERE role='student';

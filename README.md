✨ Key Features
Project Dashboard: Automatically calculates and displays a visual progress bar for each project based on completed tasks.

Kanban Board View: Organizes tasks into customizable stages (e.g., To Do, In Progress, Done).

Priority Color-Coding: Tasks are dynamically styled with color-coded borders (Red for High, Yellow for Medium, Green for Low) using database-driven logic.

Full CRUD Lifecycle: Users can Create, Read, Update (Edit), and Delete projects and tasks with safety confirmation screens.

Collaboration System: Integrated comment threads within each task to allow for team communication and tracking.

🛠️ Technical Stack
Backend: Python 3.x, Django 5.x (MTV Architecture)

Frontend: HTML5, CSS3, Bootstrap 5 (Responsive Design)

Database: SQLite3 (Relational database management)

Authentication: Django Contrib Auth (Session-based security)

🏗️ Installation & Setup
Clone the Repository:

Bash
git clone https://github.com/S4544/project-management-tool.git
cd project-management-tool
Create a Virtual Environment (Optional but recommended):

Bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install Dependencies:

Bash
pip install django
Database Setup:

Bash
python manage.py makemigrations
python manage.py migrate
Create Admin User (to manage projects):

Bash
python manage.py createsuperuser
Run the Server:

Bash
python manage.py runserver
📂 Project Structure
/core: Main project settings and configurations.

/tasks: The primary application folder containing models, views, and forms.

/templates: Custom HTML templates built with Bootstrap 5 components.


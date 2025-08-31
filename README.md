A simple To-Do List application built with Django that allows users to manage their daily tasks with authentication support.

🚀 Features:
🔐 User Authentication (Signup, Login, Logout)
➕ Add Tasks with title
✏️ Edit Tasks
🗑️ Delete Tasks
👤 User-Specific Todos (each user sees only their own tasks)
📅 Tasks sorted by date

🛠️ Tech Stack:
Backend: Django
Database: SQLite (default, can be switched)
Frontend: Django Templates (HTML, CSS)

📂 Project Structure:
views.py → Handles user authentication and CRUD operations for todos
models.py → Defines the TODOO model (task with title, user, date, etc.)
templates/ → HTML templates (signup.html, loginn.html, todo.html, edit_todo.html)

▶️ How to Run Locally

Clone this repository:
git clone https://github.com/rao-abhi2203/DjangoTodoApp.git

cd django-todo-app

Install dependencies:
pip install -r requirements.txt

Run migrations:
python manage.py migrate

Start the server:
python manage.py runserver


Open in browser: http://127.0.0.1:8000

👉 Perfect for beginners learning Django Authentication + CRUD operations.

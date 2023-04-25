
# Todo List App in Django with Authentications

This is a simple Todo List app built with Django, which allows users to create, read, update and delete their todo items. The app also includes user authentication using Django's built-in authentication system.

<br>
<img src="./.images/todoapp.png" width="700" height="500" alt="Todo App image"/>





## Features :fire:

- User registration and authentication
- Add, update, and delete todo items
- Mark todo items as completed
- List all todo items for a user
- Responsive design




## Installation

Clone the repository:

```bash
  git clone https://github.com/Sayakdutt/TodoApp-Django.git
```

Change into the project directory:

```bash
    cd TodoApp-Django
```
Create a virtual environment:

```bash
    python -m venv venv
```
Activate the virtual environment:
```bash
    source venv/bin/activate (for Linux or macOS)
    venv\Scripts\activate (for Windows)

```
Install the dependencies:

```bash
    pip install -r requirements.txt
```
Run database migrations:
```bash
    python manage.py makemigrations
    python manage.py migrate
```
Create a superuser:
```bash
    python manage.py createsuperuser
```
Run the development server:
```bash
    python manage.py runserver

```
Navigate to http://localhost:8000 in your web browser to view the app.

## Usage/Examples

1) Register a new user account.
2) Log in with your newly created user account.
3) Create new todo items, update or delete existing ones.
4) Mark todo items as completed.
5) Log out when done.




## Contributing

Contributions are welcome. Please fork the repository and create a new branch for your feature or bug fix. Once you have made your changes, submit a pull request and your changes will be reviewed..


# django-todo
A simple todo app built with django
### This web based application is based on ToDoList that has been developed for the accomplishment of Future Ready Talent Internship program launched by Microsoft, Future Skills Prime.Quess, Github and EY.

**project link** - https://todolistazurecloud.azurewebsites.net
**project demo video link** - https://youtu.be/X3sRMirTCQY

### About this project:☺️
This project is the full stack development regarding to the Django web-framework

The TODO list application is a web-based task management system that allows users to create, manage, and track their tasks. The application will be built using Django, a high-level Python web framework. Django provides a robust set of tools and features for developing web applications quickly and efficiently.

## Features and Functionalities 😊

#### Task Creation:
Users can create new tasks by providing a title, description, due date, and other relevant details. Each task will have a status (e.g., "to do," "in progress," "completed") to track its progress.

#### Task Listing and Sorting:
Users can view a list of their tasks, organized by different sorting options (e.g., due date, status, priority). This feature enables users to have a clear overview of their tasks.

#### Task Editing and Deletion:
Users can update task details or mark tasks as completed. Additionally, they can delete tasks that are no longer relevant or necessary.

#### Task Reminders:
Users can set reminders for tasks to receive notifications or email reminders before the due date. This feature ensures that important tasks are not forgotten.

## Technical overview

Django Framework: The application will be developed using Django's Model-View-Controller (MVC) architectural pattern. Django provides a powerful ORM (Object-Relational Mapping) system to interact with the database and simplifies the handling of URL routing, form validation, and authentication.

Database: Django supports various database backends, including SQLite database that suits your needs and configure it in the application.

Front-End: The user interface will be designed using HTML, CSS, and JavaScript. Django's template system will be utilized to render dynamic web pages with data from the backend.

Task Management: Django's models will be used to define the task data structure and handle CRUD (Create, Read, Update, Delete) operations. Views and templates will be created to present the task information and allow users to interact with their tasks.

Task Sorting, Filtering, and Searching: Django's query capabilities will be utilized to sort, filter, and search tasks based on user-defined criteria. This will ensure efficient retrieval of the desired tasks.

## Tech Stack 🔷
- [Azure(Hosting)](https://todolistazurecloud.azurewebsites.net)
- Python
- Django webframework
- sqlite3
- html
- css

# Screenshots
![todo App](https://raw.githubusercontent.com/shreys7/django-todo/develop/staticfiles/todoApp.png)
### Setup
To get this repository, run the following command inside your git enabled terminal
```bash
$ git clone https://github.com/Rajesh-2312/todolist.git
```
You will need django to be installed in you computer to run this app. Head over to https://www.djangoproject.com/download/ for the download guide

Once you have downloaded django, go to the cloned repo directory and run the following command

```bash
$ python manage.py makemigrations
```

This will create all the migrations file (database migrations) required to run this App.

Now, to apply this migrations run the following command
```bash
$ python manage.py migrate
```

One last step and then our todo App will be live. We need to create an admin user to run this App. On the terminal, type the following command and provide username, password and email for the admin user
```bash
$ python manage.py createsuperuser
```

That was pretty simple, right? Now let's make the App live. We just need to start the server now and then we can start using our simple todo App. Start the server by following command

```bash
$ python manage.py runserver
```

Once the server is hosted https://todolistazurecloud.azurewebsites.net, head over to  for the App.

Cheers and Happy Coding :)

# Especially need to Thank:
Future Ready Talent,Microsoft, Future Skills Prime.Quess, Github and EY


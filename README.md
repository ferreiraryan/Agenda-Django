# 📌 Agenda Django

A contact management system built with Django, allowing users to add, edit, and delete contacts, with a simple interface for managing the data.

## 🚀 Technologies

This project was developed with the following technologies:

- [Django](https://www.djangoproject.com/)
- [Python](https://www.python.org/)

## 📂 Project Structure


```
/project-root
│── .gitignore              # Git ignore file to exclude unnecessary files
│── manage.py               # Main entry point to run the Django server
│── /base_static/global/css  # Global CSS styles for the project
│── /base_templates/global  # Global templates used across the project
│── /contact                # The main app for managing contacts
│── /project                # Main project folder with settings and configurations
│── /utils                  # Utility functions and helpers
```

## 📥 Installation

```sh
# Clone this repository
$ git clone https://github.com/ferreiraryan/Agenda-Django

# Navigate into the project directory
$ cd Agenda-Django

# Create a virtual environment (optional but recommended)
$ python -m venv venv
$ source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install the project dependencies
$ pip install django

# Run migrations to set up the database
$ python manage.py migrate

# Create a superuser to access the Django admin panel
$ python manage.py createsuperuser

# Start the development server
$ python manage.py runserver

```


## 🛠️ Usage

Once the app is running, open your browser and manage your contacts!
You can add, edit, and delete contacts in the system.

## Accessing the Admin Panel
To access the Django admin panel, go to http://127.0.0.1:8000/admin/ and log in using the superuser credentials created during setup.

## 🤝 Contributing

Feel free to contribute! Just follow these steps:

1. Fork the project.
2. Create a **branch** with your feature (`git checkout -b my-feature`).
3. Commit your changes (`git commit -m 'Adding my feature'`).
4. Push to the branch (`git push origin my-feature`).
5. Open a **Pull Request**.

## 📬 Contact

- **Ryan** - [ryanferreira4883@gmail.com](mailto:ryanferreira4883@gmail.com)
- **GitHub** - [https://github.com/ferreiraryan](https://github.com/ferreiraryan)
- **LinkedIn** - [https://www.linkedin.com/in/ferryan/](https://www.linkedin.com/in/ferryan/)

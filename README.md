# Django-todo
A simple todo app built with Django

![todo App](https://raw.githubusercontent.com/shreys7/django-todo/develop/staticfiles/todoApp.png)
### Setup
To get this repository, run the following command inside your git-enabled terminal
```bash
$ https://github.com/akashpassi007/todolist.git
```
You will need django installed on your computer to run this app. Head over to https://www.djangoproject.com/download/ for the download guide

Once you have downloaded django, go to the cloned repo directory and run the following command

```bash
$ python manage.py makemigrations
```

This will create all the migrations files (database migrations) required to run this App.

Now, to apply these migrations run the following command
```bash
$ python manage.py migrate
```

One last step and then our todo App will be live. We need to create an admin user to run this App. On the terminal, type the following command and provide username, password and email for the admin user
```bash
$ python manage.py createsuperuser
```

That was pretty simple. Now let's make the App live. We need to start the server now and then we can start using our simple todo App. Start the server by following command

```bash
$ python manage.py runserver
```

Once the server is hosted, head over to http://127.0.0.1:8000/todos for the App.

Cheers, and Happy Coding :)

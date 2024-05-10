# Super Adventure Blog

## About The Project

Super Adventure Blog - personal blog about IT and travelling.

The blog administrator, who is also the owner, oversees the management of posts, authors, and tags, and moderates comments through an administrative interface provided by the Django framework. \
Visitors have the ability to view all posts and associated tags, comment on individual posts, and bookmark posts to a 'Read Later' list. These bookmarked posts can be accessed on the 'Stored Posts' page, which retains the saved posts for the duration of the visitor's HTTP session. Additionally, visitors can remove posts from their 'Stored Posts' list as needed.

### Built With

* [![SQLite][SQLite.com]][SQLite-url]
* [![Django][Django.com]][Django-url]
* [![VSCode][VSCode.com]][VSCode-url]

## Key Features

- Cross-Site Request Forgery (CSRF) Protection: Ensures the security of the site against unauthorized actions by authenticated users.
- Session-Based Bookmarking: Implements the storage of article IDs for the 'Read Later' feature within user sessions.
- Dual-Level Comment Validation: Provides thorough validation of visitor comments, both on the client-side (frontend) and server-side (backend)."

## Components Used In The Project:

- Django 5.0.6
- pillow 10.3.0
- asgiref 3.8.1
- sqlparse 0.5.0
- tzdata 2024.1

***

- __Administrator:__ login = `admin`, password = `61003355120518`

## Screenshots of Main Functionality

### Main Page:

![main-page]

### My Stored Posts Page:

![my-stored-posts-page-1]

### My Stored Posts Page (with empty posts collection):

![my-stored-posts-page-2]

### All Posts Page:

![all-posts-page]

### Specific Post Page:

![specific-post-page]

### Django Site Admin Pages:

![django-site-admin-page-1]

![django-site-admin-page-2]

![django-site-admin-page-3]

## Project Setup

### Clone the repository
```
$ git clone https://github.com/Aleksey2096/django_project.git
```

### Start development server
```
$ python manage.py runserver
```

### Create new project with the given name
```
$ django-admin startproject <project_name>
```

### Create new app within your project
```
$ django-admin startapp <app_name>
```

### Create new database migration files based on the changes you've made to your models
```
$ python manage.py makemigrations
```

### Apply pending database migrations to synchronize the database schema with your current set of models
```
$ python manage.py migrate
```

### Create new superuser account for accessing the Django admin interface
```
$ python manage.py createsuperuser
```

### Open up the Django shell, an interactive Python shell with Django environment loaded
```
$ python manage.py shell
```

### Collect static files from your apps into the static root directory defined in your settings
```
$ python manage.py collectstatic
```

### Run tests for your Django project
```
$ python manage.py test
```

### Open up the database shell for your configured database, allowing you to execute SQL commands directly
```
$ python manage.py dbshell
```

### Generate file in your project directory, listing all the installed Python packages along with their versions
```
$ pip freeze > <file_name>.txt
```

<!-- MARKDOWN LINKS & IMAGES -->

[SQLite.com]: https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white

[SQLite-url]: https://www.sqlite.org/

[Django.com]: https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white

[Django-url]: https://www.djangoproject.com/

[VSCode.com]: https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white

[VSCode-url]: https://code.visualstudio.com/


[main-page]:project-info/main_page.png

[my-stored-posts-page-1]:project-info/my_stored_posts_page_1.png

[my-stored-posts-page-2]:project-info/my_stored_posts_page_2.png

[all-posts-page]:project-info/all_posts_page.png

[specific-post-page]:project-info/specific_post_page.png

[django-site-admin-page-1]:project-info/django_site_admin_page_1.png

[django-site-admin-page-2]:project-info/django_site_admin_page_2.png

[django-site-admin-page-3]:project-info/django_site_admin_page_3.png

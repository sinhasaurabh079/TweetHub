# TweetHub

TweetHub is a Django-based web application that allows users to create, view, edit, and delete tweets. It includes functionalities for user authentication and profile management. The application features an admin interface for managing tweets and users.

## Deployed

You can access the live application at the following link: [Visit TweetHub](https://sinhasaurabh079.pythonanywhere.com/app/)

## Features

- **User Authentication:** Users can register, log in, and manage their profiles.
- **Tweet Management:** Users can create, view, edit, and delete their tweets. They can view all tweets but can only delete their own.
- **Home View:** Browse all tweets from all users.
- **My Tweets Section:** Access a dedicated page to view tweets specific to the logged-in user.
- **Search Functionality:** Search for tweets by keywords.
- **Admin Interface:** Admins can manage users and tweets through the Django admin panel.
- **Media Handling:** Support for uploading and displaying media files with tweets.


## Tech Stack

- **Django 5.1.1**: A high-level Python web framework for rapid development.
- **Python 3.10**: The programming language used to develop the application.
- **SQLite**: The database engine used for development and testing.
- **HTML/CSS**: For the structure and styling of web pages.
- **Bootstrap**: A front-end framework used for responsive design (included in Django admin).
- **PythonAnywhere**: The hosting platform where the application is deployed.

## Project Structure

The project is organized as follows:

- `TweetHub/` - Root directory containing the project files.
  - `manage.py` - Command-line utility for administrative tasks.
  - `media/` - Directory for uploaded media files.
  - `static/` - Directory for static files like CSS.
  - `templates/` - Directory for HTML templates for registration (register, login, logout).
  - `tweet/` - Django app for managing tweets.
  - `tweethub/` - Django project directory containing settings and configuration.
   

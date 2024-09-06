# TweetHub

TweetHub is a full-stack web application built with Django, allowing users to create, view, edit, and delete tweets. It includes functionalities for user authentication and profile management. The application features an admin interface for managing tweets and users.

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

- **Backend**: 
  - Django: Framework for building the server-side logic and handling database operations.

- **Frontend**: 
  - HTML/CSS: Basic web technologies for layout and styling.
  - Bootstrap: Framework for responsive design and styling.

- **Database**: 
  - SQLite (or configured database): For storing user data and tweets.

## Project Structure

The project is organized as follows:

- `TweetHub/` - Root directory containing the project files.
  - `manage.py` - Command-line utility for administrative tasks.
  - `media/` - Directory for uploaded media files.
  - `static/` - Directory for static files like CSS.
  - `templates/` - Directory for HTML templates for registration (register, login, logout).
  - `tweet/` - Django app for managing tweets.
  - `tweethub/` - Django project directory containing settings and configuration.
   

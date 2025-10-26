# Project-Flask-WebApp-Prototype

A basic Flask web application prototype built as part of a web development assignment.
This project demonstrates core Flask concepts including routes, templates, and session handling.

## Overview

This prototype includes several pages that demonstrate how Flask handles routing, template rendering, and mock user sessions.

### Features

🏠 Home Page – basic landing page introducing the project.

📋 Listings Grid – displays a list of mock data using Jinja2 templates.

🏡 Listing Detail Page – shows information for a single listing.

🔐 Mock Login – simulates user authentication using Flask sessions.

👤 User Dashboard – displays personalized data after login.

## Tech Stack

Python 3

Flask

HTML5 + Jinja2

CSS (basic styling)

## Run Instructions
1. Clone the repo
git clone https://github.com/ThaoHuynh94/Project-Airbnb-Activity.git

cd Project-Flask-WebApp-Prototype

3. Install Flask
pip install flask

4. Run the app
python run.py

5. Open in your browser
http://127.0.0.1:5000

## Folder Structure

```

myApp/
│
├── run.py
│
└── app/
    ├── __init__.py
    ├── routes.py
    │
    ├── templates/
    │   ├── base.html
    │   ├── home.html
    │   ├── listings.html
    │   ├── listing_detail.html
    │   ├── login.html
    │   └── dashboard.html
    │
    └── static/
        └── css/
            └── styles.css

```
## Author

Developed as part of a Flask Web Development Assignment

Author: Thao Huynh

Date: October 25, 2025


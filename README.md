# Project-Flask-WebApp-Prototype

A basic Flask web application prototype built as part of a web development assignment.
This project demonstrates core Flask concepts including routes, templates, and session handling.

## Overview

This prototype includes several pages that demonstrate how Flask handles routing, template rendering, and mock user sessions.

### Features

🏠 Home Page – basic landing page introducing the project.
<img width="518" height="179" alt="image" src="https://github.com/user-attachments/assets/34f17ebd-dac4-4acb-a53b-a950ec518674" />

📋 Listings Grid – displays a list of mock data using Jinja2 templates.

<p align="center">
<img width="758" height="457" alt="Screenshot 2025-10-25 at 5 37 20 PM" src="https://github.com/user-attachments/assets/9f1e81b9-75af-4759-96c2-fdf77eee1fcd" />
</p>


🏡 Listing Detail Page – shows information for a single listing.

<p align="center">
<img width="424" height="332" alt="image" src="https://github.com/user-attachments/assets/41b38343-ae5d-4edf-a8be-97f4efba1672" />
</p>

🔐 Mock Login – simulates user authentication using Flask sessions.

<p align="center">

<img width="385" height="283" alt="image" src="https://github.com/user-attachments/assets/84c34550-c23f-4ee2-acdb-3b17fa0da3d6" />

<img width="467" height="253" alt="image" src="https://github.com/user-attachments/assets/aa39fa5c-10b9-40f3-9f36-88ac22d176b8" />
</p>

👤 User Dashboard – displays personalized data after login.
<p align="center">

<img width="1006" height="472" alt="image" src="https://github.com/user-attachments/assets/a8e696fa-9264-40eb-b9e2-bdbf79163034" />

</p>

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


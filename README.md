# ProJango
## ProJango CRM Application

ProJango is a Customer Relationship Management (CRM) application built using Django. This application helps you manage customer data, create users, and perform CRUD (Create, Read, Update, Delete) operations on your customer database.

### Features

- **User Management**: ProJango allows you to create and manage user accounts.
- **Admin Dashboard**: It provides an admin dashboard for easy data management.
- **CRUD Operations**: You can perform Create, Read, Update, and Delete operations on customer data.

## Getting Started

1. **Clone the ProJango repository from GitHub: [ProJango GitHub Repository](https://github.com/krishnasowmya99/ProJango.git).**

2. Install the required Python packages by running:
  
   pip install -r requirements.txt
Apply database migrations to set up the initial database:

python manage.py makemigrations
python manage.py migrate

Start the development server:
    python manage.py runserver

    Access the application by navigating to http://127.0.0.1:8000/ in your web browser.

Usage

    Visit the application and create a user account.
    Log in with your user credentials.
    Access the admin dashboard to manage and perform CRUD operations on customer data.

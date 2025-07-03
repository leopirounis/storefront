1. Project Title
    ## Storefront Django Admin Site
2. Description
    A short summary about the project:

    A Django-based admin site for managing an e-commerce storefront. Features include product management, user authentication, and admin dashboard.
3. ## Features
    - User authentication with Django admin
    - Product and order management
    - Tagging and liking system
4. ## Installation
Clone the repository:
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
Create and activate a virtual environment:
    python3 -m venv venv
    source venv/bin/activate 
    On Windows: venv\Scripts\activate
Install dependencies:
    pip3 install -r requirements.txt
Set up environment variables:
    Create a .env file in the root directory

    Add your secrets (see .env.example for reference)
Apply migrations:
    python manage.py migrate
Create a superuser to access admin:
    python manage.py createsuperuser
Run the development server:
    python manage.py runserver

Open your browser at http://127.0.0.1:8000/admin and log in.

5. ## Database
    The seed.sql is my database
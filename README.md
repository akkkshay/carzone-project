# CarZone - Car Resale Platform

Welcome to **CarZone**, a comprehensive car resale platform designed to simplify and enhance the experience of buying and selling cars. This repository hosts the full codebase for CarZone, a powerful and user-friendly website built using Django.

___

## Key Features

- **User Authentication and Authorization**:
  - Secure user registration and login
  - Role-based access control for users and administrators

- **Car Listings Management**:
  - Add, edit, delete, and view car listings
  - Upload multiple images for each car
  - Detailed car information including make, model, year, price, and specifications

- **Advanced Search and Filtering**:
  - Search by keywords, price range, make, model, year, and more
  - Sort results by relevance, price, date listed, etc.

- **Responsive Design**:
  - Fully responsive layout optimized for desktops, tablets, and mobile devices
  - Intuitive and user-friendly interface

- **Admin Panel**:
  - Comprehensive dashboard for site management
  - Manage users, listings, and site settings
  - View site analytics and reports

- **Contact and Inquiry Forms**:
  - Integrated forms for users to contact sellers
  - Email notifications for new inquiries

- **Favorite Listings**:
  - Users can save their favorite car listings for easy access later

## Technologies Used

- **Backend**:
  - Django: High-level Python web framework for rapid development
  - PostgreSQL: Default database for development (easily switchable to MySQL for production)
  
- **Frontend**:
  - HTML5 & CSS3: Markup and styling for modern web standards
  - JavaScript: Enhances interactivity and user experience
  - Bootstrap: Responsive design framework for a consistent look and feel

___

## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/akkkshay/carzone-project.git

2. **Navigate to the Project Directory**:
   ```bash
   cd carzone-project
  
3. **Create and Activate a Virtual Environment**:
   ```bash
   python -m venv env
   source env/bin/activate   # On Windows use `env\Scripts\activate`

4. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt

5. **Run Migrations**:
   ```bash
   python manage.py migrate

6. **Create a Superuser**:
   ```bash
   python manage.py createsuperuser

7. **Start the Development Server**:
   ```bash
   python manage.py createsuperuser

8. **Access the Application**:
   ```bash
   - Open your web browser and go to http://127.0.0.1:8000/
   - Access the admin panel at http://127.0.0.1:8000/admin/

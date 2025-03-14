# Django BankWeb Project

## Overview
Django BankWeb Project is a comprehensive web application that simulates a bank's online services. Users can register for a new account, log in, manage their accounts, and perform various banking operations, such as checking account balances, adding funds, and withdrawing money.

## Features
- **User Registration**: Create a new bank account with a simple registration process.
- **User Authentication**: Secure login for existing users.
- **Account Management**: View account balance, add funds, and withdraw money.
- **Carousel for Services**: An image carousel on the homepage showcasing various bank services.
- **OTP Verification**: Secure transactions using OTP (One-Time Password) verification.
- **Responsive Design**: Fully responsive design using CSS and Bootstrap, ensuring compatibility across devices.

## Project Structure
- **base.html**: The main template that extends other templates.
- **static/**: Directory containing static files like images, CSS, and JavaScript.
- **templates/**: Directory containing HTML templates.
- **views.py**: Django views handling the logic behind each page.

## Installation

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/your-username/BankWeb.git
    ```

2. **Navigate to the Project Directory:**
    ```bash
    cd BankWeb
    ```

3. **Create and Activate a Virtual Environment:**
    ```bash
    python3 -m venv env
    source env/bin/activate
    ```

4. **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

5. **Run Migrations:**
    ```bash
    python manage.py migrate
    ```

6. **Run the Development Server:**
    ```bash
    python manage.py runserver
    ```

7. **Access the Application:**
    Open your browser and go to `http://127.0.0.1:8000/`.

## Usage

- **Homepage Carousel**: Displays key services such as Credit Cards, Nearby ATMs, and UPI Transactions.
- **Login and Registration**: Users can log in to their accounts or register for a new account.
- **Account Services**: After logging in, users can check their account balance, add funds, or withdraw money with OTP verification.

## Customization

- **Styling**: The project uses Bootstrap and custom CSS for styling. Modify the `static/css/style.css` file to change the appearance of the website.
- **Templates**: The HTML templates are located in the `templates` directory. Customize them as needed.
- **Static Files**: Images and other static resources can be added or modified in the `static` directory.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

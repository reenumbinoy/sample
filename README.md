Setup Instructions
Follow these steps to set up and run the project locally:

Clone the repository:
  git clone git@github.com:reenumbinoy/authentication.git


Navigate to the project directory:
  cd auth-system


Install dependencies:
  composer install
  npm install
  npm run dev


Configure your .env file
  DB_CONNECTION=mysql
  DB_HOST=127.0.0.1
  DB_PORT=3306
  DB_DATABASE=uasystem
  DB_USERNAME=root
  DB_PASSWORD=

  
Run database migrations
  php artisan migrate

  
Serve the application
  php artisan serve


Features
    User Registration: Allows new users to register with a unique alphanumeric user ID generated automatically.
    User Login: Secure authentication mechanism for registered users.
    User Logout: Allows users to securely log out of the application.

    
Technologies Used
    Laravel: Backend framework for PHP.
    Bootstrap: Frontend CSS framework for styling.
    JavaScript: Used for basic form interactions.

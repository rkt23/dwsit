
# DWSIT



## Requirements
To run this API, you will need the following installed on your system:

    PHP 8.0 or later
    MySQL 5.7 or later
    Laravel 9.0
    Composer
    Git
## Installation

1. Clone this repository using Git:

       git clone https://github.com/rkt23/dwsit.git

2. Change into the project directory:

       cd dwsit

3. Install the required packages using Composer:

       composer global require laravel/installer

4. Create a new MySQL database for the project.

5. Create a copy of the .env.example file and rename it to .env:

       cp .env.example .env

6. Update the database configuration settings in the .env file with your database credentials:

       DB_DATABASE=db_test
       DB_USERNAME=root
       DB_PASSWORD=

8. Run the database migrations to create the necessary tables:

        php artisan migrate

9. Seed the database with some sample data (optional):

        php artisan db:seed

10. Start the Laravel development server:

        php artisan serve

11. You can now access the API by visiting http://127.0.0.1:8000/api/user in your web browser or using a tool like Postman.

## API Endpoints

This API exposes the following endpoints for managing products:

    GET /api/user: Fetch all user

## License

This project is licensed under the MIT License. See the LICENSE file for details.

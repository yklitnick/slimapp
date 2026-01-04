# SlimApp RESTful API

This is a RESTful api built with the SlimPHP framework and uses MySQL for storage.

## Installation

1. Clone the repository:
    ```bash
    git clone
    ```
2. Navigate to the project directory:
    ```bash
     cd slimapp
    ```
3. Install dependencies using Composer:
    ```bash
     composer install
    ```
4. Set up your database:
    - Create a MySQL database.

You will need to create a database called `slimapp` and a user with appropriate permissions. - Update the database configuration in `config/settings.php` with your database credentials. - Add a `customers` table to the database. - Add the following columns to the `customers` table: - `id` (INT, Primary Key, Auto Increment) - `first_name` (VARCHAR) - `last_name` (VARCHAR) - `phone` (VARCHAR) - `email` (VARCHAR) - `address` (VARCHAR) - `city` (VARCHAR) - `state` (VARCHAR)

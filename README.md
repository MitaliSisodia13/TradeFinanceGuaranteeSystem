# Trade Finance Guarantee Issuance System

## Project Overview
The Trade Finance Guarantee Issuance System is a Laravel-based application designed to manage the lifecycle of financial guarantees, such as Bank Guarantees, Bid Bonds, Insurance, and Surety. The system supports secure CRUD operations, bulk data uploads, and role-based access to ensure efficient and reliable management of guarantees. It leverages Laravel's MVC architecture, Eloquent ORM, and Blade templates for a robust and scalable solution.

## Learning Objectives
By completing this project, we aim to achieve the following objectives:

- Implement a secure, modular architecture using Laravel and follow the MVC pattern.
- Design a database schema with validations to maintain data integrity.
- Use the Repository pattern to manage data interactions and enhance modularity.
- Implement Laravel's authentication middleware for secure access control.
- Enable bulk data uploads with support for CSV, JSON, and XML formats.
- Deploy and test the application locally for seamless integration and functionality.


## Setup Instructions
To set up the project locally, follow these steps:

- Clone the repository:
    Link: `https://github.com/MitaliSisodia13/TradeFinanceGuaranteeSystem.git`
- Set up the database:
    - Open MySQL and create a database named TradeFinanceGuaranteeSystem.
    - Run migrations to create tables using the following command: `php artisan migrate`
- Configure the environment:
    - Copy the .env.example file to .env: `cp .env.example .env`
    - Update the .env file with database credentials:
      ` DB_CONNECTION=mysql
        DB_HOST=127.0.0.1
        DB_PORT=3306
        DB_DATABASE=TradeFinanceGuaranteeSystem
        DB_USERNAME=your_username
        DB_PASSWORD=your_password`
- Generate the application key: `php artisan key:generate`
- Run the application: `php artisan serve`
- Access the application at: http://127.0.0.1:8000.

## Contribution Summary

### Team Members

Mitali Sisodia (Student Number: N01621572)
Contributions:
- Database schema design and implementation.
- Admin Panel - Manage Guarantee
- Forgot Password implementation
- Bulk data upload functionality (CSV, JSON, XML).
- Testing.

Samruddhi Chavan (Student Number: N01604191)
Contributions:
- Applicant Guarantee CURD
- UML Diagram
  
Saloni Patel (Student Number: N01603895)
Contributions:
- Login/Register
- Admin Panel - Manage users
  
Sruthi Pandiath (Student Number: N01618202)
Contributions:
- Admin and Applicant Dashboards
- Report







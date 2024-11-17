# Product App

A simple CRUD (Create, Read, Update, Delete) product app built using Laravel PHP framework.

## Features

*   **CRUD Operations**: Create, read, update and delete products
*   **User Management**: Manage users for product creation, editing, and deletion
*   **Authentication**: User authentication with default Laravel login system
*   **Basic Validation**: Basic validation checks for product fields

## Prerequisites

*   PHP 8.0 or higher
*   Composer (for dependency management)
*   MySQL or similar database server
*   A code editor or IDE of your choice

## Installation

1.  Clone the repository: `git clone https://github.com/Bishwajit-2810/crud_php`
2.  Install dependencies: `composer install`
3.  Set up database by creating `.env` file:
    *   Define your database credentials
    *   Set database name, host, username and password
4.  Run migrations to set up the database schema:
    ```bash
    php artisan migrate
5.  Run the project:
    ```bash
    php artisan serve

## Usage

### Creating a Product

1.  Go to `http://localhost:8000/products/create`
2.  Fill in product details (e.g., name, description, price)
3.  Click "Save and Continue"
4.  Review and submit changes

### Reading Products

1.  Go to `http://localhost:8000/products`
2.  Browse through a list of products

### Updating a Product

1.  Find the product you want to edit
2.  Click on its "Edit" button
3.  Fill in updated details
4.  Click "Save Changes"

### Deleting a Product

1.  Find the product you want to delete
2.  Click on the "Delete" button
3.  Confirm deletion (this will permanently remove data)

## Screenshot

Here's an image of what the app looks like:

[one](https://gifyu.com/image/SyGkE)
[two](https://gifyu.com/image/SyGkk)
[three](https://gifyu.com/image/SyGkv)
[four](https://gifyu.com/image/SyGkh)
[five](https://gifyu.com/image/SyGkm)


## API Endpoints

| Endpoint | Description |
| --- | --- |
| `/products` | List all products |
| `/products/create` | Create a new product |
| `/products/{id}` | Get specific product details |
| `/products/products/{id}/edit` | Update existing product details |
| `/products/delete` | Delete a product |

## Security

*   Always validate and sanitize user input
*   Use HTTPS for encryption
*   Store sensitive data securely (e.g., password hashing)

## Contributing

You're welcome to contribute! Please follow standard professional guidelines:

1.  Fork the repository
2.  Make changes in your fork
3.  Send a pull request back to the original repository

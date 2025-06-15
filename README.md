# Hi there! 👋

This GitHub repository provides a blog designed with laravel php

# laravel Blog with PHP

This project was bootstrapped with laravel

## For this repository the requisites are:

Before diving into the repository you have to install the following environments on your local machine

In the project directory, you can run:
1.  **Composer:** Which you can download from the [composer website]().
2.  **Wampserver:** Download wampserver from the official wampserver website:
3.  **Laravel:** Install the library using node npm install your bash terminal or your directory:

    ```bash
    composer install
    ```
    ```bash
    composer create-project laravel/lavarel myblog
    ```
## How to run this example

To execute the laravel app in this repository

1.  Navigate to the directory containing the files in your terminal.
2.  Run the desired script using the Python interpreter:
    ```bash
    php artisan migrate
    ```
3. Runs the app in the development mode.\
    ```bash
    php artisan serve
    ```
4.  Create database table for posts
    ```bash
    php artisan make:migrate create_post_table
    ```
5.  Create a post model to interact with the posts table
    ```bash
    php artisan make:model Post
    ```
6.  Create a Post controller to handle requests related to post
    ```bash
    php artisan make:controller PostController --resource
    ```
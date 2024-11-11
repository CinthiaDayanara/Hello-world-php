# Hello World PHP Project

This project is a simple PHP application that prints a "Hello World" message in the browser. It is designed to show the basics of PHP and how to configure it in a local environment using a web server such as Apache.

## Description

The purpose of this project is to provide a basic introduction to PHP programming, as well as setting up a local web server to run PHP applications. This project can serve as a foundation for beginners who want to learn PHP and integration with servers like Apache.

The main file of the application is `index.php`, which prints a message on the screen when accessed through a browser.

# Instructions to run the PHP application

Follow these steps to download, configure and run the PHP application on your local machine.

## 1. Clone the repository from GitHub

```bash
git clone https://github.com/CinthiaDayanara/Hello-world-php.git
```
## 2. Install PHP and a web server

On Windows:
The user can install XAMPP or WAMP, which includes Apache and PHP easily.

Download XAMPP from here and install.
XAMPP will include both PHP and Apache, allowing you to run the PHP file on the local server.
On Mac:
Using MAMP is a good option, which also includes Apache and PHP.

Download MAMP from here.
## 3. Place the files in the appropriate directory
The next step is to place the PHP files in the root directory of the web server:

In XAMPP (Windows): The directory where you should place your files is 
C:\xampp\htdocs\.

In MAMP (Mac): The directory to place the files is 
/Applications/MAMP/htdocs/.

## 4. Open the web server
In XAMPP or MAMP, you only need to start Apache from the application's graphical interface.

## 5. Access the PHP file from the browser
Once the files are in the correct directory and the web server is running, you can open your browser and access the application by:

```bash
Copy code
http://localhost/index.php
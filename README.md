# Personal Blog Website
Welcome to my personal blog website! You can access the website [here](https://leles-personal-blog-9rug.onrender.com). This is an end-to-end application that is managed from development through deployment to production.

## Functionality
The website offers the following functionality:

* **User Registration and Login:** Users need to register and login in order to comment on posts. Comments can be deleted only by the user that made it or by the admin. Passwords are securely encoded using hashing and salting functions from the '***werkzeug.security***' package. User authentication is handled by a '***flask_login***' object.

* **Post Management:** Only admin users have the privilege to create and delete posts.

* **Contact Form:** Users can get in touch with me by sending a message through the website. The messages are transferred via email using an SMTP client session object.

* **Rich Text Editing:** The application utilizes CKEditor, a WYSIWYG rich text editor that enables users to write content directly within web pages and online applications.

## Deployment Details
* **Production Environment:** The application is deployed on Render, and a WSGI server is set up with Gunicorn to run the live Python application. The production database used is PostgreSQL.

* **Development Environment:** Development and testing are done locally using a SQLite database.

## Topics Covered
The project covers various technologies and concepts, including:

* **Python:** The website is built using Python programming language.

* **HTML and CSS:** HTML and CSS are used to structure and style the web pages.

* **Render:** The website is deployed on the Render platform.

* **SQL:** SQL databases are utilized for data storage and retrieval.

* **Flask Web Framework:** The application is developed using the Flask web framework.

* **Decorators:** Decorators are used to modify the behavior of functions or methods.

* **Object-Oriented Programming (OOP):** The project incorporates OOP principles for organizing code.

* **Functions and Packages:** Functions and packages are used to modularize the code and provide reusable components.

Please refer to the ***requirements.txt*** file for a comprehensive list of packages and dependencies used in this project.

Feel free to explore the website and enjoy reading my blog posts! If you have any questions or feedback, you can contact me through the provided contact form.

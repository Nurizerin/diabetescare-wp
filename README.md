Diabetes Care Collaboration Hub (WordPress Project)

This repository contains the WordPress project files (themes, plugins, uploads) for our Assignment 2: WordPress Build and Content Management.
The project is developed locally using XAMPP and shared via GitHub for collaboration.

📂 Project Structure

/wp-content/themes/ → Custom Child Theme (Astra-based)

/wp-content/plugins/ → Any required plugins

/wp-content/uploads/ → Demo images, wireframes, documents

/db/database.sql → Database export (phpMyAdmin)

👉 WordPress core files (wp-admin, wp-includes, etc.) are excluded from this repo.

⚙️ Local Setup (XAMPP)

Follow these steps to run the project locally:

Clone this repo into your XAMPP htdocs folder:

cd C:/xampp/htdocs/
git clone https://github.com/your-username/diabetescare-wp.git diabetescare


Start XAMPP → Enable Apache and MySQL.

Create a new database in phpMyAdmin:

Go to http://localhost/phpmyadmin/

Create a database called diabetesdb

Import the SQL file from /db/database.sql

Open the site in your browser:

http://localhost/diabetescare/


Login to WordPress Admin:

http://localhost/diabetescare/wp-admin/


Username: admin (or as shared)

Password: ******

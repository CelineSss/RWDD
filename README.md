Quizzing You English Quiz Web App
Quick Start
1. Install and start XAMPP (or any other local server).
2. Move this project folder into your local server's htdocs directory (for XAMPP: C:\xampp\htdocs\).
3. Import the provided SQL database (quizzing_you (1).sql) into phpMyAdmin.
4. Open your browser and go to: http://localhost/rwdd/INDEX.html
** No need to install additional packages — only standard XAMPP setup!

Description
Quizzing You is a responsive English quiz platform designed for students aged 7–12 years.
It features three types of users:
- Students: Take quizzes by grade (1–6) on Grammar, Idioms, Verbs, and Vocabulary.
- Teachers: Create quizzes and manage content.
- Parents: View their children's quiz results and summaries.

How to Run
This project uses web technologies (HTML/CSS/JS) and needs PHP and MySQL to work properly.

Prerequisites
Install XAMPP (Apache + MySQL server)

Steps
1. Start Apache and MySQL in the XAMPP Control Panel.
2. Copy the project folder into your htdocs directory (C:\xampp\htdocs\).
3. Import the database:
- Open your browser and go to http://localhost/phpmyadmin
- Create a new database named quizzing_you.
- Import the SQL file: quizzing_you (1).sql
4. Open the project:
- Visit http://localhost/rwdd/INDEX.html in your browser.

Project Folder Structure
── INDEX.html      (Main entry page)
── config.php      (Database connection settings)
── quizzing_you (1).sql   (Database file)
── stylesheet.css  (Main styles)

Requirements
- Web Server (like XAMPP, WAMP, MAMP)
- PHP 7.x or higher
- MySQL 5.x or higher
- Web browser (Chrome, Firefox, Edge, etc.)

Important Notes
** Check if the config file (config.php) matches your MySQL username and password (default: root, no password).
- You must run this project on a local server (Apache) because it uses PHP and MySQL.
- Make sure your Apache and MySQL are running in the background when testing.
- No additional libraries (like npm, composer) are needed.

If you face any issues:
- Ensure your XAMPP is correctly installed and both Apache and MySQL services are running.
- Confirm the database is imported into phpMyAdmin without errors.

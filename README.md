# NotesHub

## Project Description
*NotesHub* is a full-stack web application designed for college and university students to share and access academic notes effortlessly. Whether you're preparing for exams or catching up on missed classes, NotesHub allows you to upload, categorize, and download PDF notes by subject. Built to foster collaboration, this platform makes it easy for students to help each other succeed academically.

The project was created to simplify note-sharing, reduce the hassle of finding reliable study materials, and build a community-driven resource hub for students.

---

## Features
- *User Authentication*: Secure signup and login system to manage user accounts.
- *Note Upload*: Upload PDF notes with details like subject.
- *Subject Categorization*: Organize notes by subjects for easy browsing.
- *Browse & Search*: Explore notes by subject or search for specific topics.
- *Download Notes*: Download PDF files with a single click.
- *User Dashboard*: View your uploaded notes and manage your profile.
- *Responsive Design*: Works seamlessly on desktops, tablets, and mobile devices.

---

## Tech Stack
- *Frontend*: HTML, CSS, JavaScript
- *Backend*: PHP
- *Database*: MySQL
- *Server Environment*: XAMPP (or any local server with Apache and MySQL)
- *File Handling*: PDF uploads and downloads
- *Tools*: Git, Visual Studio Code, phpMyAdmin (for database management)

---


---

## Installation Guide
Follow these steps to set up and run NotesHub locally using XAMPP (or a similar local server).

### Prerequisites
- *XAMPP*: Download and install from [Apache Friends](https://www.apachefriends.org/).
- *Git*: Install Git from [git-scm.com](https://git-scm.com/).
- A modern web browser (e.g., Chrome, Firefox).

### Step-by-Step Setup
1. *Clone the Repository*:
   - Open a terminal or command prompt.
   - Run the following command to clone the NotesHub repo:
     bash
     git clone https://github.com/shivamnanavare/NotesHub-v0).git
     
   - Replace your-username with your actual GitHub username or the correct repo URL.

2. *Move Project to XAMPP*:
   - Copy the cloned notes-hub folder to the htdocs directory in your XAMPP installation (e.g., C:\xampp\htdocs\ on Windows).
   - The project should now be in C:\xampp\htdocs\notes-hub\.

3. *Start XAMPP*:
   - Open the XAMPP Control Panel.
   - Start the *Apache* and *MySQL* modules.

4. *Set Up the Database*:
   - Open your browser and go to http://localhost/phpmyadmin.
   - Create a new database named noteshub_db.
   - Import the provided SQL file (database/notes_website.sql) from the project folder:
     - Click on the notes_website database.
     - Go to the *Import* tab, choose the .sql file, and click *Go*.

5. *Update Database Credentials*:
   - Open the config.php file in the project folder (e.g., notes-hub/config.php).
   - Update the database connection settings if needed (default settings for XAMPP):
     php
     $host = "localhost";
     $username = "root";
     $password = "";
     $database = "notes_website";
     

6. *Launch the Application*:
   - Open your browser and navigate to http://localhost/notes-hub/.
   - You should see the NotesHub homepage.
   - Register a new account or log in to start using the platform.

### Troubleshooting
- *Apache/MySQL not starting?* Check if ports 80 (Apache) or 3306 (MySQL) are in use by other apps (e.g., Skype).
- *Database errors?* Ensure the .sql file was imported correctly and credentials in config.php match your setup.
- *404 errors?* Confirm the project folder is in htdocs and the URL is correct.

---
---

## Usage
Here’s how a student would typically use NotesHub:

1. *Sign Up*:
   - Visit the homepage (http://localhost/notes-hub/).
   - Click *Register*, fill in your details (name, email, password etc.), and create an account.

2. *Log In*:
   - Use your username and password to log in from the *Login* page.

3. *Upload Notes*:
   - From the dashboard, click *Upload Note*.
   - Select a PDF file, choose a subject and submit.

4. *Download Notes*:
   - Go to the *Download* page.
   - Filter notes by subject or search for a topic.
   - Click on a note to view details and download the PDF.

5. *Top contributor*:
   - In the dashboard, view the highest contributor of notes.

---

## Contributors
- [Sanket Bhuite](https://github.com/sanketbhuite/)
- [Shreyash pise](https://github.com/YashPise07)
- [Vikrant Jadhav](https://github.com/vikrantjadhav07)
- [Pratik Salunkhe](https://github.com/pratiksalunkhe523)
---

## License
This project is for *personal and educational use*. It is not open-source at this time, but you may use and modify it for non-commercial purposes. Contact the author for permission to use in other contexts.

---

## Contact
Have questions, feedback, or suggestions? Reach out to the project author:
- *Email*: work.sanketbhuite@outlook.com


Happy studying with NotesHub! 📚

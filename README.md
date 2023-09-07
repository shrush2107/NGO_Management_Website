# NGO_Management_Website

## Table of Contents

1. [Project Introduction](#project-introduction)
2. [Tech Stack](#tech-stack)
3. [Prerequisites](#prerequisites)
4. [Installation](#installation)
5. [Societal Applications](#societal-applications)

## Project Introduction

"NGO_Management_Website" is a web application designed to facilitate non-governmental organizations (NGOs) in effectively managing their social services. The system collects and displays information about NGOs, including their name, location, history, and establishment date. NGOs are required to register and have their information verified before they can post their requirements. Donors can then browse through these requirements and choose which NGO they want to donate to. To ensure authenticity and safety, donors are also required to register.

This system addresses the manual record-keeping challenges faced by smaller NGOs and provides them with a platform to connect with potential donors interested in contributing to their cause. Built using PHP and MySQL, the user-friendly interface ensures ease of operation. The system allows for systematic maintenance and retrieval of NGO and donor activity data.

## Tech Stack

- **HTML:** HTML is the foundation of the web and defines the structure of web content.

- **CSS:** CSS is used for styling and layout, enhancing the presentation of web pages.

- **JavaScript:** JavaScript adds interactivity and behavior to web pages.

- **PHP:** PHP is used for server-side scripting and dynamic content management, including interaction with databases.

## Prerequisites
Before you begin, ensure you have met the following requirements:
- Web server with PHP support (e.g., Apache, Nginx)
- MySQL database server
- PHP version 7.x or higher
- A modern web browser

## Installation

1. **Clone the Repository:**
   ```
   git clone https://github.com/yourusername/NGO_Management_Website.git
   cd NGO_Management_Website
   ```

2. **Database Setup:**
   - Create a MySQL database for the project.
   - Import the database schema from the provided SQL file:
     ```
     mysql -u username -p your_database_name < database.sql
     ```

3. **Configuration:**
   - Open `config.php` located in the project's root directory.
   - Update the database configuration with your MySQL credentials:
     ```php
     $dbHost = 'localhost';
     $dbUser = 'your_mysql_username';
     $dbPass = 'your_mysql_password';
     $dbName = 'your_database_name';
     ```

4. **Web Server Setup:**
   - Configure your web server to point to the project's root directory.
   - Ensure that PHP is enabled and properly configured.

5. **Start the Web Server:**
   - Start your web server.

6. **Access the Application:**
   - Open a web browser and visit `http://localhost/NGO_Management_Website` (replace with your server configuration).
   - You should see the project's homepage.

Please make sure to replace placeholders like `yourusername`, `your_database_name`, `your_mysql_username`, and `your_mysql_password` with actual values. Additionally, provide any specific installation or configuration instructions that are unique to your project.

## Societal Applications

- **Connecting Donors and NGOs:** This website serves as an interface for users to discover and connect with NGOs from various domains, streamlining the donation process.

- **Donation Management:** Users can access NGO contact details for monetary donations and view NGO requirements for in-kind donations.

- **NGO Outreach:** NGOs gain a platform to post their needs and attract interested donors, ultimately benefiting society.


# Online Voting System for College Elections

This project is an **Online Voting System** designed to streamline the process of college gymkhana elections, allowing students to vote for their representatives through a secure, web-based platform. The system manages candidates, voters, and election positions, providing a user-friendly interface for both students and election administrators. 

The project focuses on ensuring secure and scalable backend operations using **PHP**, **MySQL**, **JavaScript**, and **CSS**.

## Features

- **Candidate Management**: Admins can add, edit, or remove candidates for various positions.
- **Position Management**: Customizable election positions can be created, managed, and assigned candidates.
- **Voting Process**: Students can securely cast their votes for multiple positions.
- **Encrypted Data Handling**: Ensures all sensitive data, such as votes, is encrypted to protect the integrity of the election.
- **Session Management**: Secure user sessions for voters and admins to authenticate and manage actions within the system.
- **Results Tabulation**: Automatic counting and display of election results after voting has concluded.
- **Scalable Backend**: Optimized database queries and backend structure to support future expansion to different types of elections.

## Backend-Specific Highlights

- **Encrypted Data Handling**: All sensitive information, including user credentials and votes, is encrypted to prevent tampering and ensure data privacy.
- **Session Management**: Voter and admin sessions are securely handled, including login/logout mechanisms and session timeout for enhanced security.
- **Database Optimization**: Optimized MySQL queries and indexing for faster access to election-related data and ensuring smooth scaling as the system grows.
- **Scalability for Future Expansion**: Backend structure supports future election types and can be extended to accommodate additional features like multi-level elections or external voting modules.
- **Security Practices**: Implemented XSS and SQL injection prevention mechanisms to safeguard the system from potential attacks.

## Installation and Setup

### Prerequisites
- Web server with **PHP 7.0+**
- **MySQL 5.7+** database
- **Apache** or **Nginx**
- Modern web browser (JavaScript enabled)

### Installation Steps

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Rishab-Bo/Voting-Management-System.git
    ```
2. **Navigate to the project directory**:
    ```bash
    cd Voting-Management-System
    ```

3. **Database setup**:
    - Import the provided `database.sql` file into your MySQL database to set up the necessary tables.
    ```bash
    mysql -u root -p your_database_name < database.sql
    ```

4. **Configure database credentials**:
    - Update the `config.php` file with your database host, username, password, and database name.
    ```php
    <?php
    // config.php
    $dbHost = 'localhost';
    $dbUsername = 'your_username';
    $dbPassword = 'your_password';
    $dbName = 'your_database_name';
    ?>
    ```

5. **Run the application**:
    - Place the project files into your web server's root directory.
    - Open your browser and navigate to `http://localhost/Voting-Management-System` to start the system.

## Usage

- **Admin Portal**:
    - Log in as an admin to manage candidates, positions, and election settings.
    - Encrypted credentials and secure session management ensure only authorized personnel can access the admin panel.

- **Voter Portal**:
    - Voters must log in to view and vote for available positions.
    - Secure session management ensures only authenticated users can cast votes.

## Technologies Used

- **PHP**: Backend logic and session handling.
- **MySQL**: Database for storing election data, voters, and results.
- **JavaScript**: Frontend interactivity and validation.
- **CSS**: Styling and responsive design.
- **HTML**: Structuring the web pages.

## Future Enhancements

- **Two-Factor Authentication**: Adding an extra layer of security for voter and admin logins.
- **Live Results Monitoring**: Real-time display of results during the voting process.
- **Multi-Language Support**: Expanding the platform to support multiple languages for broader accessibility.
- **Role-Based Access Control**: More granular permissions for different admin roles (e.g., election supervisor, candidate manager).


## Project developed by:

Rakim Middya

Cecily Ambooken

Rishab Bohra

Veerathu Sri Sindhu

Ebin Royce




# PHP Driving License Management System

A web-based application built using PHP for managing driving license processes, including application, health tests, practical tests, and license issuance.

---

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Folder Structure](#folder-structure)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Features
- **User Registration**: Register as a new applicant.
- **Health Test Management**: View and manage health test results.
- **Theory and Practical Tests**: Record and display test results.
- **License Issuance**: Issue and renew driving licenses.
- **Admin Management**: Admin panel to manage users and applications.
- **Secure Login**: User authentication for applicants and admins.

---

## Technologies Used
- **PHP**
- **HTML, CSS, JavaScript**
- **MySQL** (Database)
- **Apache** (Server)

---

## Folder Structure
```plaintext
.
├── image/                    # Images used in the project
├── images/                   # Additional images
├── scripts/                  # JavaScript files
├── styles/                   # CSS stylesheets
├── db_conn.php               # Database connection file
├── login.php                 # Login functionality
├── register.php              # User registration
├── issueL.php                # License issuance
├── update.php                # Update functionalities
├── display-theory.php        # Display theory test results
├── display_health.php        # Display health test results
├── display_practical.php     # Display practical test results
├── style.css                 # Main stylesheet
├── README.md                 # Documentation
```

---

## Clone the Repository
To get a copy of the project up and running on your local machine, clone the repository using the following command:

```bash
git clone https://github.com/21mebrat/php-driving-licence-managment-system.git
```

---

## Setup Instructions
1. Clone the repository using the command above.
2. Set up a local web server using Apache (e.g., XAMPP).
3. Import the provided SQL script into MySQL to set up the database.
4. Update the `db_conn.php` file with your database credentials.
5. Place the project files in your server's root directory (e.g., `htdocs` for XAMPP).
6. Start the Apache and MySQL servers and access the application via the browser.

---

## Usage
1. Access the application through your local server URL (e.g., `http://localhost/php-driving-licence-managment-system`).
2. Register as a new user or log in as an admin.
3. Use the application to manage driving license operations, including tests, applications, and renewals.

---

## Contributing
Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature description"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request.

---

## License
This project is licensed under the [MIT License](LICENSE).

---

## Contact
For any inquiries or feedback, contact:

**Mebrat Matebie**  
**Email**: maytotmat@gmail.com  
**GitHub**: [21mebrat](https://github.com/21mebrat)
```

Let me know if you need further adjustments!

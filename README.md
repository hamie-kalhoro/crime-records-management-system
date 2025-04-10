# 🕵️‍♂️ Crime Records Management System

A web-based application designed to streamline the process of recording, organizing, and analyzing criminal activities, 
ensuring a more efficient and data-driven approach for law enforcement agencies.

---

## 📂 Project Structure


---

## ⚙️ Features

- **Admin Interface**: Manage staff, assign cases, and oversee system operations.
- **Officer Interface**: Register complaints, view case details, and update investigation statuses.
- **CID Interface**: Access assigned cases, conduct investigations, and submit reports.
- **User Authentication**: Secure login system for different user roles.
- **Case Management**: Efficient tracking and management of criminal cases.
- **Responsive Design**: Accessible on various devices and screen sizes.

---

## 🛠️ Technologies Used

- **Front-end**: Graphical User Interface(Java)
- **Database**: MySQL

---

## 🗺️ Entity-Relationship Diagram

![ER Diagram](https://github.com/hamie-kalhoro/crime-records-management-system/blob/master/ER%20Mapping/dbms.png)

*Entity-Relationship Mapping*

---

## 🛠️ Setup Instructions

1. **Clone the repository**:

    ```bash
    git clone https://github.com/hamie-kalhoro/crime-records-management-system.git
    ```

2. **Navigate to the project directory**:

    ```bash
    cd crime-records-management-system
    ```

3. **Set up the database**:

    - Import the provided SQL file (located in the `database/` directory) into your MySQL server.
    - Update the database configuration in the `config.php` file with your database credentials.

4. **Deploy the application**:

    - Place the project folder in your web server's root directory (e.g., `htdocs` for XAMPP).
    - Start your web server and navigate to `http://localhost/crime-records-management-system` in your browser.

---

## 🚀 Usage

- **Admin**: Access the admin dashboard to manage staff and assign cases.
- **Officer**: Log in to register complaints and update case statuses.
- **CID**: View assigned cases and submit investigation reports.

---

## 🔒 Security Considerations

Be aware that earlier versions of similar systems have had vulnerabilities, such as SQL injection. 
Ensure that all user inputs are sanitized and use prepared statements to protect against such vulnerabilities. Regularly update and patch the system to maintain security.

---

## 👤 Author

**Hamie Kalhoro**  
GitHub: [@hamie-kalhoro](https://github.com/hamie-kalhoro)

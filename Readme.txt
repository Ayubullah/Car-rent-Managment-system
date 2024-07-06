# Car Rent Management System

The Car Rent Management System is a project designed to facilitate the management of car rental services. It provides a user-friendly interface built with Python and Tkinter for both customers and administrators to interact with the system. The system utilizes MySQL as the database management system. This README file provides an overview of the project and instructions for getting started.

## Prerequisites

Before running the Car Rent Management System, ensure you have the following software and libraries installed:

1. Python: Install Python from the official Python website (https://www.python.org) based on your operating system. The project is compatible with Python 3.

2. Tkinter: Tkinter is a standard Python library for creating graphical user interfaces. It is usually included with Python installations. If you don't have Tkinter installed, you can install it using the package manager `pip` by running the command: `pip install tk`.

3. MySQL: Install MySQL Community Server from the official website (https://dev.mysql.com/downloads/installer) based on your operating system. Follow the installation instructions provided in the MySQL documentation.

4. MySQL Connector/Python: MySQL Connector/Python is a Python driver for connecting to MySQL databases. You can install it using `pip` by running the command: `pip install mysql-connector-python`.

## Getting Started

To set up and run the Car Rent Management System, follow these steps:

1. Download the project files from the GitHub repository: [car-rent-management](https://github.com/ayubullah/car-rent-management).

2. Extract the downloaded project files to a convenient location on your system.

3. Launch the MySQL server and create a new database named `car_rent_management_system`.

4. Import the provided SQL file (`car_rent_management_system.sql`) into the newly created database. This file contains the necessary tables and sample data for the system to function properly.

5. Open the project folder and locate the `main.py` file.

6. Open the `main.py` file in a text editor and update the database connection details such as the hostname, username, password, and database name. Modify the following lines of code accordingly:

   ```python
   # Database Connection Configuration
   host = "localhost"
   user = "your_username"
   password = "your_password"
   database = "car_rent_management_system"
   ```

7. Save the `main.py` file after making the necessary changes.

8. Open a terminal or command prompt, navigate to the project folder, and run the following command to start the Car Rent Management System:

   ```bash
   python main.py
   ```

9. The application window will open, and you can now use the Car Rent Management System.

## Usage

1. Upon launching the Car Rent Management System, you will see the login screen.

2. If you're a new user, click on the "Register" button to create an account. Provide the required information and submit the form.

3. Once registered, log in using your credentials.

4. As a customer, you can browse available cars, reserve a car, and manage your reservations.

5. As an admin, you will have access to additional functionalities for managing cars, user accounts, and reservations.

6. Use the various buttons and forms provided in the application to perform desired actions.

**Note**: The provided instructions assume a default installation of Python, Tkinter, and MySQL. If you have customized installation paths or configurations, please adjust the instructions accordingly.

## Technologies Used

The Car Rent Management System is built using the following technologies:

- Python: A programming language used for the application's logic and functionality.
- Tkinter: A Python library for creating graphical user interfaces.
- MySQL: A relational database management system used for storing and retrieving data.

## Contributors

This project was developed by Ayubullah. Contributions and improvements are welcome. Feel free to fork the repository and submit pull requests.

## License

The Car Rent Management System is released under the [MIT License](https://opensource.org/licenses/MIT). Please see the `LICENSE` file for more details.

## Contact

If you have any questions or suggestions, feel free to contact the project maintainer at ayubullah@example.com.
# JavaEE WebPOS

JavaEE WebPOS is a Point of Sale (POS) application built using JavaEE technologies. It provides a user-friendly interface for managing sales, inventory, and customer data in retail environments.

## Features

- **User Authentication**: Secure login system for employees to access the POS functionalities.
- **Customer Management**: Add, update, and delete customer information.
- **Order Management**: Create, view, and manage customer orders.
- **Item Management**: Add, update, and delete items from the inventory.
- **Order Details**: View detailed information about each order, including items purchased and total cost.
- **Home**: Dashboard overview displaying key metrics and sales data.

## Technologies Used

- JavaEE (Enterprise Edition)
- JavaServer Faces (JSF)
- Java Persistence API (JPA)
- MySQL Database
- HTML/CSS/JavaScript
- Maven

## Setup

1. **Clone the repository**:

 https://github.com/Chamath-Gihan/JavaEE-WEB-POS-System.git

 
2. **Import the project into your IDE** (Eclipse, IntelliJ IDEA, etc.).

3. **Set up the database**:

- Install MySQL Server if not already installed.
- Create a new database named `webpos`.
- Import the database schema from `database.sql` file provided in the repository.

4. **Configure the database connection**:

- Open `persistence.xml` file located in `src/main/resources/META-INF`.
- Update the database connection properties (URL, username, password) according to your MySQL configuration.

5. **Build and Run**:

- Build the project using Maven: `mvn clean install`.
- Deploy the generated WAR file (`webpos.war`) to your JavaEE application server (e.g., Apache Tomcat, WildFly).

6. **Access the application**:

- Open a web browser and navigate to `http://localhost:8080/webpos` (adjust the port number if necessary).

## Usage

1. **Login**:
- Use the provided username and password to log in to the system.

2. **Home**:
- Upon successful login, you'll be directed to the home/dashboard page displaying key metrics and sales data.

3. **Customer Management**:
- Navigate to the customer management section to add, update, or delete customer information.

4. **Order Management**:
- Create new orders for customers and view existing orders.

5. **Item Management**:
- Add, update, or delete items from the inventory.

6. **Order Details**:
- View detailed information about each order, including items purchased and total cost.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

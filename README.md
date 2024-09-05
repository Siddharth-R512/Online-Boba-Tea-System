# Online Boba Tea Ordering System

The Online Boba Tea Ordering System is a Java-based application that allows users to order boba tea online. The system includes user authentication, menu browsing and an order placement.The project is built using Java Swing in an MVC architecture, ensuring a clear separation between the application logic, user interface, and data.

The main features include:
- User login and registration
- Viewing and selecting items from the boba tea menu
- Customizing orders with different toppings and sizes
- Order summary and checkout process

## Project Structure
The system follows an MVC (Model-View-Controller) architecture. Below are the key components:

- **Login.java**: Handles user authentication, including login and registration functionality. It interacts with the user interface for logging in and communicates with the backend to verify user credentials.

- **Dashboard.java**: Represents the admin dashboard where the administrator can view and manage orders, update the menu, and monitor the system's overall performance.

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/your-username/online-boba-tea-system.git
   ```
2. Open the project in your preferred IDE (e.g., IntelliJ, Eclipse).
3. Ensure you have Java JDK installed (version 8 or higher recommended).
4. Run the `Login.java` file to start the application.

## Usage
- **Login Screen**: Users can log in or register if they are new. Upon successful login, the user will be redirected to the menu screen.

  ![Login Screen](path/to/login_screenshot.png)

- **Menu Screen**: Users can browse the menu, select items, customize their orders, and add them to the cart.

  ![Menu Screen](path/to/menu_screenshot.png)

- **Checkout Screen**: Displays the order summary and provides an option to proceed with the payment.

  ![Checkout Screen](path/to/checkout_screenshot.png)

## Technologies Used
- Java
- Java Swing for GUI
- MVC Architecture

## Future Enhancements
- Adding a payment gateway for seamless transactions
- Implementing a notification system for order status updates
- Expanding the menu with more customizable options


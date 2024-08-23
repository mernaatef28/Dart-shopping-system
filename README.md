# Dart Shopping System

This Dart project simulates a simple shopping system where users and admins can interact with products and manage a shopping cart. The project demonstrates the application of data structure principles to create an interactive console-based application.

## Features

### User Mode
- **Browse Products**: Users can browse the available products.
- **Add Products to Cart**: Users can add products to their shopping cart and specify the quantity.
- **Remove Products from Cart**: Users can remove products from their shopping cart.
- **View Cart Details**: Users can view the contents of their cart, including the total price and the total price after applying discounts.

### Admin Mode
- **Manage Products**: Admins can add new products, remove existing products, and display the current product list.
- **Manage Visitors**: Admins can add new visitors and display the list of current visitors.
- **Search Products**: Admins can search for products by name or price.
- **View Visitors**: Admins can view the list of visitors who have interacted with the system.

## Code Structure

- **`Users.dart`**: Defines the `Users` class, which holds information about users and their shopping carts.
- **`Product.dart`**: Defines the `Product` class, representing individual products in the store.
- **`Shop.dart`**: Manages the store's products and visitors. Includes methods for adding/removing products, searching for products, and managing visitors.
- **`Cart.dart`**: Manages the user's shopping cart, allowing for adding/removing products, calculating the total price, and applying discounts.
- **`main.dart`**: The entry point of the application, handling the user interface and interactions for both users and admins.

## How to Run

1. Ensure you have Dart installed on your system.
2. Clone the repository or download the project files.
3. Navigate to the project directory.
4. Run the application using the following command:
   ```bash
   dart main.dart

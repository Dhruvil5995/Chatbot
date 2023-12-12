# FastAPI-Dialogflow Integration with MySQL for Restaurant Order Management

## Overview

Indian Restaurant is a comprehensive restaurant management system with Dialogflow integration. This project is designed to streamline restaurant operations, manage orders, and provide a seamless customer experience. It includes a MySQL database for order management, a FastAPI web service for handling user queries and order operations, a website template, and CSS styles for a restaurant.

## Project Components

### 1. MySQL Database Setup and Helper Functions

- Initializes a MySQL database named "indian restaurant."
- Sets up tables and functions necessary for order management.
- Provides helper functions for interacting with the database, including inserting order items, order tracking, calculating total order price, and more.

### 2. FastAPI Web Service for Dialogflow Integration

- Sets up a FastAPI web service to handle incoming requests from Dialogflow.
- Defines route handlers for different intents received from Dialogflow.
- Interprets user queries, processes them, and returns relevant responses.
- Utilizes FastAPI's asynchronous features for efficient request handling.

### 3. String Manipulation Functions

- Contains utility functions for string manipulation.
- `get_str_from_food_dict` formats a dictionary of food items and quantities into a human-readable string.
- `extract_session_id` extracts session IDs from strings using regular expressions.

### 4. FastAPI Web Service for Order Management

- Extends the FastAPI web service to handle order management operations.
- Defines handlers for adding items to an order, removing items, completing orders, and tracking orders.
- Maintains an in-memory dictionary (`inprogress_orders`) to track orders.
- Interacts with the MySQL database using helper functions to store order details.

### 5. HTML Template for Restaurant Website

- Provides an HTML template for a restaurant website.
- Includes sections for a banner, menu, location, contact information, and an embedded Dialogflow chatbot for customer interactions.

### 6. CSS Styles for the Website Template

- Defines CSS styles to visually enhance the restaurant website template.
- Sets fonts, colors, and layout for various sections of the website, ensuring an attractive and user-friendly design.

### 7. SQL Database Schema and Data

- Contains SQL statements to create the database schema and tables.
- Inserts sample data for food items, order tracking, and orders into the respective tables.

# Web Page

![2023-09-16](https://github.com/Dhruvil5995/FastAPI-Dialogflow-Integration-with-MySQL-for-Restaurant-Order-Management/assets/64741151/07edc8b4-2db0-4306-8434-4a1e40cf5d60)


## Usage

- Clone this repository to your local machine.
- Configure your MySQL database credentials in the appropriate configuration file.
- Start the FastAPI web service.
- Access the restaurant website via a web browser to interact with the chatbot and place orders.


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.


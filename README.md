**Name:** Gabby J
**Company:** CODTECH IT SOLUTIONS
**ID:** CT08DS3508
**Duration:** July to August 2024
**Mentor:** Neela Santhosh Kumar

## Overview of the project
### Project: Inventory Management System
This project is a simple inventory management system built using Python’s Tkinter library for the graphical user interface (GUI). 
It provides basic functionalities for managing an inventory, including adding, editing, deleting products, and generating reports. 
It also includes user authentication and low stock alerts.

### Features
- **User Authentication:** Allows users to log in using a username and password. Includes default admin credentials.
- **Product Management:**
    - **Add Product:** Add new products with name, quantity, and price.
    - **Edit Product:** Update existing products' quantity and price.
    - **Delete Product:** Remove products from the inventory.
    - **Inventory Reports:** Generate a detailed report of all products in the inventory.
    - **Low Stock Alerts:** Alert users when products fall below a specified stock threshold.
      
### Files
- **users.json:** Stores user credentials.
- **inventory.json:** Stores product details including name, quantity, and price.
 
### Dependencies
- **tkinter:** For the GUI.
- **json:** For data storage in JSON format.
- **os:*** For file operations.

### Code Summary
**Helper Functions**
- load_data(filename, default_data=None): Loads data from a JSON file or returns default data if the file does not exist.
- save_data(filename, data): Saves data to a JSON file.
  
**InventorySystem Class**
Handles the core functionality of the inventory system:
Methods:
- **add_product(name, quantity, price):** Adds a new product.
- **edit_product(name, quantity, price):** Edits an existing product.
- **delete_product(name):** Deletes a product.
- **get_low_stock_alert(threshold):** Returns products below a specified quantity threshold.
- **generate_report():** Returns the current inventory report.
- **authenticate_user(username, password):** Authenticates users.
- **add_user(username, password):** Adds a new user.

**InventoryGUI Class**
Manages the graphical user interface:
- **Authentication:** Provides login functionality.
- **Main Interface:** Includes buttons for adding, editing, deleting products, generating reports, and checking low stock alerts.
- **Custom Message Box:** Displays messages and alerts using custom-sized windows.

### Output:
![image](https://github.com/user-attachments/assets/803f7990-56ce-4212-8313-ee88f839eec9)

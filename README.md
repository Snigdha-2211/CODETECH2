Name:Yerrabelli Snigdha
Id:CT6PP606
Domain:Python Programming
Duration:June 25th,2024 to August 10th,2024.
Mentor:Neela Santhosh Kumar
Description:
This Python program utilizes the tkinter library to create a graphical user interface (GUI) for an inventory management system.
Here’s a detailed description of how each component works together:

Overview:
The program allows users to manage inventory data stored in a text file (inventory.txt) through a GUI.
It provides functionalities to add, update, search, remove, and generate a full list of inventory items.

Functions:
add_inventory(): Retrieves item name and quantity from input fields (item_name_entry and item_qty_entry). 
It appends the new item and quantity to inventory.txt, clears the input fields, and prepares for the next input.

update_inventory(): Updates the quantity of an existing item in inventory.txt based on the entered item name. 
It reads the current inventory data, modifies the quantity if the item exists, and writes back the updated data to the file.

search_inventory(): Searches for an item by name in inventory.txt. If found, it displays the item name and quantity in the GUI (result_label).
If not found, it notifies the user that the item is not in the inventory.

remove_inventory(): Deletes an item from inventory.txt based on the entered item name. It reads the inventory data, excludes the item to be removed,
and writes the remaining data back to the file.

generate_inventory(): Retrieves all inventory data from inventory.txt and displays it in the GUI (result_label).
This function provides a complete list of all inventory items and their quantities.
Conclusion:
This program exemplifies how to build a simple yet effective inventory management system using Python and tkinter.
It combines GUI elements for user interaction with file handling operations to manage inventory data seamlessly. 
Future enhancements could include error handling, data validation, sorting capabilities, or integration with a database for scalability
and additional functionalities.

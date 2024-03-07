# scanning_system

This Python script is a barcode scanner and inventory management system, using cv2 for video frames, pyzbar for decoding, anda openpyxl for Excel. It prompts users to scan or find items, captures frames, and saves changes.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Imports](#Imports)
- [Rating: 7/10](#Rating)

## About

This Python script is a barcode scanner and inventory management system that uses the cv2 library for video frames, the pyzbar library for decoding barcodes, and the openpyxl library for Excel file interaction. It prompts the user to choose between scanning an item or finding an item in the inventory. If scanning, the webcam initializes and captures frames, checks if the barcode is in the inventory, prompts the user to input the item's name and location, adds it to the Excel spreadsheet, and saves the changes. If finding, the script iterates through the inventory and prints out the item's location.

# Features

The Python script combines barcode scanning and inventory management by using several libraries. It captures video frames from a webcam using the cv2 library and decodes barcodes and QR codes from these frames. The script supports various barcode types, such as CODBAR, CODE39, CODE93, CODE128, DATABAR, ean13, I25, and QR codes. The goal is to identify items by scanning their barcodes.

The script maintains an inventory of items, allowing users to choose between scanning an item or finding an item. The script decodes the barcode data, prompts the user to input the item's name and location, and updates the Excel spreadsheet with this information. The script iterates through the inventory, printing out the location for each item.

The script uses the openpyxl library to interact with Excel files, reading and updating an inventory database. The script prompts the user to choose between scanning or finding items, providing clear instructions for inputting item details during scanning.

Incorporating this barcode scanner into Python applications can streamline processes and improve efficiency in tasks such as inventory management or retail solutions. For more advanced features, consider adding error handling, data validation, and a user-friendly interface. Overall, the script offers a practical solution for managing items and can be improved with more advanced features like error handling, data validation, and a user-friendly interface.

# Imports

cv2, pyzbar, openpyxl 

# Rating

The rating for this inventory management script is 7. It has barcode scanning capabilities but could benefit from improved error handling, robust user input validation, and a more user-friendly interface and documentation.

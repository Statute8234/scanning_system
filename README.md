# scanning_system
This Python script is a barcode scanner and inventory management system, using cv2 for video frames, pyzbar for decoding, anda openpyxl for Excel. It prompts users to scan or find items, captures frames, and saves changes.

[![Static Badge](https://img.shields.io/badge/cv2-black)](https://pypi.org/project/cv2/)
[![Static Badge](https://img.shields.io/badge/pyzbar-green)](https://pypi.org/project/pyzbar/)
[![Static Badge](https://img.shields.io/badge/openpyxl-gray)](https://pypi.org/project/openpyxl/)

## Table of Contents

- [About](#about)
- [Features](#features)
- [Imports](#Imports)
- [Rating: 8/10](#Rating)

# About

This Python script is a barcode scanner and inventory management system that uses the cv2 library for video frames, the pyzbar library for decoding barcodes, and the openpyxl library for Excel file interaction. It prompts the user to choose between scanning an item or finding an item in the inventory. If scanning, the webcam initializes and captures frames, checks if the barcode is in the inventory, prompts the user to input the item's name and location, adds it to the Excel spreadsheet, and saves the changes. If finding, the script iterates through the inventory and prints out the item's location.

# Features

The Python script combines barcode scanning and inventory management by using several libraries. It captures video frames from a webcam using the cv2 library and decodes barcodes and QR codes from these frames. The script supports various barcode types, such as CODBAR, CODE39, CODE93, CODE128, DATABAR, ean13, I25, and QR codes. The goal is to identify items by scanning their barcodes.

The script maintains an inventory of items, allowing users to choose between scanning an item or finding an item. The script decodes the barcode data, prompts the user to input the item's name and location, and updates the Excel spreadsheet with this information. The script iterates through the inventory, printing out the location for each item.

The script uses the openpyxl library to interact with Excel files, reading and updating an inventory database. The script prompts the user to choose between scanning or finding items, providing clear instructions for inputting item details during scanning.

Incorporating this barcode scanner into Python applications can streamline processes and improve efficiency in tasks such as inventory management or retail solutions. For more advanced features, consider adding error handling, data validation, and a user-friendly interface. Overall, the script offers a practical solution for managing items and can be improved with more advanced features like error handling, data validation, and a user-friendly interface.

# Imports

cv2, pyzbar, openpyxl 

# Rating

The code provides two main functionalities: scanning items using a webcam and searching for items in an Excel worksheet. It efficiently leverages libraries like OpenCV and pyzbar for barcode decoding and integrates with openpyxl for Excel file manipulation. The code is relatively modular, with distinct sections for different functionalities and clear separation of concerns. It interacts effectively with the user through console input/output, prompting them for input when needed and providing feedback based on their actions.
Error handling mechanisms, such as try-except blocks, improve the code's robustness and prevent crashes in case of unexpected errors. However, the use of global variables could lead to issues with maintainability and readability, especially as the codebase grows. Refactoring repetitive sections into reusable functions could improve code readability and reduce redundancy.
Input validation checks for user-provided inputs, such as item names and locations, can enhance the application's robustness and prevent invalid data from being stored. Lastly, integrating a graphical user interface (GUI) could enhance the user experience, especially for functionalities like scanning items. Libraries like Tkinter or PyQt provide tools for creating intuitive and interactive user interfaces that can improve usability.
In conclusion, the code has several pros and cons, including its functionality, modularity, user interaction, and error handling mechanisms.

# scanning_system

This Python script is a barcode scanner and inventory management system, using cv2 for video frames, pyzbar for decoding, anda openpyxl for Excel. It prompts users to scan or find items, captures frames, and saves changes.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Imports](#Imports)
- [Ratting: 7/10](#Rating)

## About

This Python script is a barcode scanner and inventory management system that uses the cv2 library for video frames, the pyzbar library for decoding barcodes, and the openpyxl library for Excel file interaction. It prompts the user to choose between scanning an item or finding an item in the inventory. If scanning, the webcam initializes and captures frames, checks if the barcode is in the inventory, prompts the user to input the item's name and location, adds it to the Excel spreadsheet, and saves the changes. If finding, the script iterates through the inventory and prints out the item's location.

## Imports

cv2, pyzbar, openpyxl 

# Ratting

The rating for this inventory management script is 7. It has barcode scanning capabilities but could benefit from improved error handling, robust user input validation, and a more user-friendly interface and documentation.

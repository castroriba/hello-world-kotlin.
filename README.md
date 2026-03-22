Project Description
This is a Kotlin-based Inventory Management System designed to help users track products, quantities, and pricing. In this second module, I expanded the application to include Data Persistence. The software now uses File I/O to save the entire inventory list to a local text file (inventory.txt) and automatically reloads that data whenever the program is launched. This ensures that no data is lost when the application is closed.

New Features in Module 2
Automatic Data Loading: On startup, the app reads from inventory.txt to restore the previous session's data.

Data Saving: Upon exiting, the app writes all current items into a structured text format.

Error Handling: Added checks to ensure the program starts "fresh" if no save file is found, preventing crashes.

Expanded Logic: Integrated Search, Update, and Delete functions to manage a dynamic list of over 100 lines of code.

Development Environment
Language: Kotlin

IDE: IntelliJ IDEA

Libraries: java.io.File for file management.

Future Improvements
JSON Integration: Switch from plain text to JSON format for more structured data storage.

Graphical Interface: Move the app from the console to a windowed GUI using TornadoFX or Compose for Desktop.

Input Validation: Add more robust "try-catch" blocks to prevent the user from entering letters where numbers are expected.
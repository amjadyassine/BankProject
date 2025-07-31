🏦 Bank Client Console App (C++)
A simple C++ console-based banking system to manage client accounts. This program allows you to add, view, update, find, and delete clients stored in memory using an intuitive menu-driven interface.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
📌 Features
Add new client with validation
View all clients in a clean table layout
Find client by account number
Update existing client details
Delete client with confirmation
Easy menu navigation
Clean and formatted output using iomanip
In-memory storage using vector<struct>
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🛠️ Technologies Used
Language: C++
Standard Libraries: <iostream>, <vector>, <string>, <iomanip>, <sstream>, <conio.h>, <algorithm>, <limits>
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🚀 How to Run
Clone or download the repository:
git clone https://github.com/labantch/Bank-Client-Console-App.git
Compile the program:
g++ Bank.cpp -o BankApp
Run the executable:
./BankApp       # Linux / macOS  
BankApp.exe     # Windows
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🧾 Example Menu
================ Main Menu Screen ================
    [1] Show Clients List
    [2] Add New Client
    [3] Update Client Info
    [4] Find Client
    [5] Delete Client
    [6] Exit
==================================================
Choose what do you want to do [1-6]:
📂 Data Structure
struct stClient_Info {
    string AccountNumber;
    string PinCode;
    string Name;
    string Phone;
    double Balance;
};
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
✅ Future Improvements
🔄 Save and load clients to/from a file
🔐 Login screen for employees
💻 Linux/macOS compatible version (remove conio.h)
📊 Sorting and search filters
📄 License
This project is open-source and available under the MIT License.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
👤 Author
Yassine Amjad 

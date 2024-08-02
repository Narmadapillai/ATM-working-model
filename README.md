# ATM-working-model

Objective:
The objective of this project is to design and implement an ATM (Automated Teller Machine) system using Verilog hardware description language. The system includes modules for user authentication, account management, balance inquiry, cash withdrawal, and inter-account transactions. The primary aim is to create a functional ATM system that simulates real-world functionalities while demonstrating proficiency in Verilog programming and digital design concepts.

Software Detail: EDA Playground is a free web application that allows users to edit, simulate, share, and view hardware description language (HDL) code

Finite State Machine (FSM) diagram:

![image](https://github.com/user-attachments/assets/b17f95bb-01fb-4ece-b5fd-da2b413995ca)

Working:
1.	User Authentication:
-	When a user initiates a transaction, they input their account number and PIN.
-	The authentication module compares the entered account number and PIN with the data stored in the system's database.
-	If the entered credentials match those in the database, the user is authenticated and granted access to their account. Otherwise, authentication fails, and the user is prompted to re-enter their credentials.

2.	Main Control Logic:
-	The main control logic of the ATM system manages the user's interactions and controls the flow of operations.
-	It monitors user inputs such as menu selections, transaction requests, and exit commands.
-	Based on these inputs, the control logic determines the next course of action, transitions between different states of operation, and executes the corresponding functionalities.
 
3.	Menu Navigation:
-	After successful authentication, the user is presented with a menu of available transactions, such as balance inquiry, cash withdrawal, and inter-account transfers.
-	The user navigates through the menu options by selecting the desired transaction using input controls provided by the ATM interface.

4.	Transaction Processing:
-	Depending on the user's selection from the menu, the system initiates various transaction processes.
-	For example, in a balance inquiry, the system retrieves the account balance from the database and displays it to the user.
-	Similarly, in a cash withdrawal transaction, the system deducts the requested amount from the user's account balance, provided sufficient funds are available.

5.	Error Handling:
-	The ATM system incorporates error handling mechanisms to address potential issues that may arise during operation.
-	Common errors include insufficient funds for a withdrawal, invalid account numbers or PINs, and transaction limits.
-	When an error occurs, the system notifies the user and prompts them to take appropriate action, such as retrying the transaction or contacting customer support.

6.	Database Management:
-	The ATM system maintains a database of account information, including account numbers, PINs, and account balances.
-	The database is utilized during authentication and transaction processing to validate user credentials and update account balances accordingly.

7.	State Management:
-	The system operates in different states or modes, such as waiting for user input, processing transactions, and returning to the main menu.
-	State transitions occur based on user actions, system responses, and predefined rules governing ATM operation.
 


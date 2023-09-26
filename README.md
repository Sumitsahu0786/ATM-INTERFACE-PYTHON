# ATM-INTERFACE-PYTHON
The ATMs in our cities are built on Python, as we have all seen them. It is a console-based application with five different classes. In order to use the system, the user must enter his or her user ID and pin when it starts. Once the details are entered successfully, ATM functionality is unlocked. As a result of the project.As a result of the project, the following operations can be performed:

**ATM Interface Project**
**Project Description**
This project simulates an ATM (Automated Teller Machine) through a graphical user interface (GUI). The application is written in Python using Tkinter for the GUI.

**Features**
User Login
Transaction History
Withdraw Funds
Deposit Funds
Transfer Funds between Accounts
**How to Run**
Make sure Python 3.x is installed on your system.
Clone this repository:
git clone https://github.com/Chethana010/atminterface.git
Navigate into the directory:
cd atminterface
Run the script:
python ATM_Interface_main.py
**Classes and Methods**
**Account**
Represents a bank account with user ID, PIN, and balance.

__init__(self, user_id, pin, balance=0): Initializes a new account.
record_transaction(self, description): Records a transaction description to the account history.
**TransactionHistory**
Handles the transaction history of an account.

show_history(account): Shows the transaction history for the given account.
**Withdraw**
Handles withdrawal transactions.

withdraw_funds(account, amount): Withdraws the specified amount from the given account.
**Deposit**
Handles deposit transactions.

deposit_funds(account, amount): Deposits the specified amount into the given account.
**Transfer**
Handles transfer transactions.

transfer_funds(src_account, dest_account, amount): Transfers the specified amount from the source to the destination account.
**ATMApp**
Main class that runs the Tkinter GUI application.

__init__(self, master): Initializes the Tkinter window and other attributes.
create_login_window(): Creates the login interface.
login(): Validates user ID and PIN.
show_options(): Shows the available ATM options after successful login.
withdraw_funds_gui(), deposit_funds_gui(), transfer_funds_gui(): GUI methods for respective transactions.
**License**
This project is open-sourced under the MIT License. See the LICENSE file for details.

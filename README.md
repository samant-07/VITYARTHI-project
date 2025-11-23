# VITYARTHI-project
project Title

Bank Management System(BMS)

Overview of the Project

A BMS is an integrated enterprise-wide information system that does not rely on manual paper-based processes for data maintenance, thus, it provides a secure and efficient interface to the end-users, which are bank personnel and customers.

Features

The system performs the following major banking activities:

Account Creation: This shall allow the creation of the new user, including all details required to open the account, which are used to create a unique number for this account and stored persistently in some type of file or simple database.

Deposit Funds: Deposit_amount-This enables a user to deposit funds into an already existing account number, upon proper verification of the account number.

Withdraw Amount: This will allow the user to draw funds from an account. This includes minimum balance and adequate funds checking logic.

display account-Displays Account Details: This fetches and then presents the current balance and account information for any given account number.

Delete Account: This will irreversibly remove an account from the system once confirmed.

Main Menu - main.py: This contains a simple, interactive, console-based menu to navigate through major functionalities.

Testing Instructions

Start the application with the command python main.py.

Test 1: Create Account • Enter choice 1 to choose create_account • Give inputs for initial details • Note down the generated Account Number

Test 2 Deposit Select option 2 deposit_amount Enter account number from test 1 and deposit amount.

Test 3: Display: Choose option 4 (display_account). If the deposited amount is reflected in the balance, input the account number.

Test 4 - Withdrawal (Successful): Choose option 3, withdraw_amount. Withdraw an amount less than the balance. Check the new balance using option 4.

Test 5: Withdrawal Failure: Choose option 3 to attempt withdrawal above the balance, and view the insufficient funds message.

Test 6: Account Delete: Choose option 5: Delete_account. Click on account number. Provide confirmation for deletion.

Test 7: Verification Attempt to view the deleted account (option 4) and verify "Account not found" is displayed.

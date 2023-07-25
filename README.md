# Bank Management System

This Bank Management System is a software application developed to manage various operations within a bank. It provides functionalities such as creating customers, branches, accounts, loans, making transactions, and retrieving customer information. The system utilizes an SQLite database for data storage and retrieval.

## Features

1. Create a new customer: Allows the user to create a new customer by providing their name, city, gender, date of birth, and occupation.

2. Create a new branch: Enables the creation of a new branch by specifying the branch ID, branch name, city, and assets of the branch.

3. Create a new account: Allows the user to create a new account for a customer. The user needs to provide the customer ID, branch ID, account balance, account type, and status. Minimum balance requirement is enforced (minimum of 2000 units).

4. Create a new loan: Enables the creation of a new loan by entering the loan number, customer ID, branch ID, and loan amount.

5. Make a transaction: Allows users to perform credit or debit transactions on existing accounts. The user needs to provide the account number, transaction date, transaction mode (credit or debit), and transaction amount.

6. Retrieve customer information: Allows users to retrieve customer information by providing the customer ID. The system displays details such as the customer's name, city, gender, date of birth, and occupation.


## Usage

1. Upon running the application, a main menu will be displayed.
2. Choose the desired option by entering the corresponding number.
3. Follow the prompts and provide the required information for the selected option.
4. The application will perform the operation and provide appropriate feedback.
5. Continue using the main menu to access different features.
6. Exit the application by selecting the corresponding option from the main menu.

## Requirements

- Python
- SQLite database
- flask

## Contributing

Contributions to the Bank Management System project are welcome. If you encounter any issues or have suggestions for improvements, please feel free to submit a pull request or open an issue in the repository.

When contributing, please ensure that you adhere to the existing code style and conventions. Also, provide clear and concise explanations for the changes made.




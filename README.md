# Bank-of-Harrenhal

A simple Python-based Banking Application that allows users to create accounts, log in, view account details, deposit, and withdraw funds.

## Features

- **Create Account**: Register with a username, password, and first name. Automatically assigns a new balance of $0.00.
- **Login**: Secure username and password authentication. Redirects to a personal dashboard upon successful login.
- **User Dashboard**:
  - **View Account Details**: Displays your username, first name, and current balance.
  - **Deposit Funds**: Increase your account balance by a specified amount.
  - **Withdraw Funds**: Decrease your account balance (with an insufficient funds check).
  - **Logout**: Returns to the main welcome screen.
- **Exit**: Terminates the application from the welcome menu.

## Code Overview

Below is a quick rundown of the functions and their responsibilities:

- **`welcome_page()`**: Displays the main welcome screen with available options and calls `intro_choices()` to handle the user's selection.
- **`intro_choices()`**: Processes the user’s choice from the welcome screen (create account, login, or exit).
- **`create_account()`**: Guides the user through setting up a new account, checking for duplicate usernames, and initializing a balance of $0.00.
- **`login_to_account()`**: Handles user login by verifying username and password. If valid, proceeds to `user_dashboard(username)`.
- **`user_dashboard(username)`**: The main interface after login, offering account details, deposit, withdrawal, and logout.
- **`view_account_details(username)`**: Shows the current balance, username, and account holder’s name.
- **`deposit_funds(username)`**: Deposits a valid amount into the user’s balance.
- **`withdraw_funds(username)`**: Withdraws a valid amount from the user’s balance, handling insufficient funds.
- **`main()`**: Starts the application by calling the `welcome_page()` function.

## License

This project is open source under the **MIT License**. You are free to use, modify, and distribute the code as you wish, but please include attribution to the original author.

# 💰 Bank of Harrenhal

A simple **Python-based Banking Application** that allows users to create accounts, log in, view account details, deposit, and withdraw funds — all through a console interface.

---

## 🚀 Features

- **Create Account**  
  Register with a **username**, **password**, and **first name**. Accounts are initialized with a **$0.00 balance**.

- **Login**  
  Secure login using **username and password**. Users are redirected to their personal dashboard upon successful login.

- **User Dashboard**
  - 🔹 **View Account Details**: See your username, first name, and current balance.
  - 🔹 **Deposit Funds**: Add money to your account balance.
  - 🔹 **Withdraw Funds**: Remove money (with a check for insufficient funds).
  - 🔹 **Logout**: Return to the welcome screen.

- **Exit Application**  
  Users can exit anytime from the main menu.

---

## 🧠 Code Overview

Here’s a breakdown of the main functions:

- `welcome_page()`  
  Displays the welcome screen and prompts the user for an action.

- `intro_choices()`  
  Handles user input from the welcome screen (create account, login, or exit).

- `create_account()`  
  Walks the user through account creation, checking for existing usernames and initializing balance.

- `login_to_account()`  
  Validates login credentials and directs the user to their dashboard upon success.

- `user_dashboard(username)`  
  Post-login interface where users can view details, deposit, withdraw, or log out.

- `view_account_details(username)`  
  Displays the user's first name, username, and current balance.

- `deposit_funds(username)`  
  Adds a valid deposit amount to the user’s balance.

- `withdraw_funds(username)`  
  Deducts a valid withdrawal amount, ensuring sufficient funds exist.

- `main()`  
  Entry point of the application; starts the experience via `welcome_page()`.

---

## 📈 Bonus: Compound Interest Calculator

*Coming soon!*  
A future feature to calculate compound interest based on principal, rate, and time.

---

## 📄 License

This project is open source under the **MIT License**.  
Feel free to use, modify, and distribute this project — just include attribution to the original author.

# Banking System Using Python OOP

A simple banking system project built in Python to demonstrate **Object-Oriented Programming (OOP)** concepts.

This project contains two main classes:

* `Bank_Account` – manages bank account operations.
* `ATM` – simulates ATM functionality such as PIN verification, deposits, withdrawals, and card blocking.

---

## Features

### Bank Account Features

* Create a bank account
* Deposit money
* Withdraw money
* Check account balance
* Block and unblock account
* Mini statement
* Change account holder details

  * Name
  * Mobile number
  * Email

### ATM Features

* Check balance using ATM PIN
* Deposit money
* Withdraw money
* Transfer funds
* Change ATM PIN
* Mini statement
* Block and unblock ATM card
* Automatic card blocking after 3 incorrect PIN attempts

---

## OOP Concepts Used

* Classes and Objects
* Constructors (`__init__`)
* Instance Variables
* Methods
* Encapsulation
* Conditional Logic
* State Management

---

## Project Structure

```text
Banking-System-OOP/
│── Bank_Account.py
│── ATM.py
│── README.md
```

---

## Example Usage

You can import the `Bank_Account` and `ATM` classes into any Python script or interactive session and call their methods to perform banking operations.

---

## Sample Output

```text
Bank Account Created...
Account Number : 1234567890
Holder Name : Omkar koli
Account IFSC Code : SBIN0001234
Balance = 10000

Account Number : 1234567890
Balance = 10000

Amount added on your account!!...
Total balance = 12000

Amount withdraw from your account!!...
Total balance = 10500

Your pin is successfully changed!!...
```

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/python-banking-system-oop.git
```

2. Move into the project folder:

```bash
cd python-banking-system-oop
```

3. Import the classes into your Python script or interactive session and start using them.

---

## Future Improvements

* Connect `ATM` directly to the `Bank_Account` object
* Store transaction history
* Save data to files or a database
* Add exception handling
* Create a graphical user interface
* Write unit tests

---

## Requirements

* Python 3.x

No external libraries are required.

---

## Author

Created by **Omkar koli** as a Python OOP practice project.

---

## License

This project is free to use for educational purposes.

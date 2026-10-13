  # BankAccount Class

A C++ class for representing and managing a customer's bank account within a banking system.

## Data Dictionary

| Attribute       | Data Type     | Description                                      |
|-----------------|---------------|--------------------------------------------------|
| `accountNumber` | `std::string` | Unique identifier for the bank account.          |
| `accountHolder` | `std::string` | The name of the person who owns the account.     |
| `balance`       | `double`      | The current financial balance of the account.    |
| `isActive`      | `bool`        | Status indicating if the account is open/active. |

## Methods List

| Method Signature                              | Return Type   | Description                                      |
|-----------------------------------------------|---------------|--------------------------------------------------|
| `BankAccount()`                               | (Constructor) | Default constructor.                             |
| `BankAccount(accNum, holder, initialBalance)` | (Constructor) | Parameterized constructor to initialize account. |
| `getAccountNumber() const`                    | `std::string` | Gets the account number.                         |
| `getAccountHolder() const`                    | `std::string` | Gets the name of the account holder.             |
| `getBalance() const`                          | `double`      | Checks the current account balance.              |
| `deposit(amount)`                             | `void`        | Adds a specified amount of money to the balance. |
| `withdraw(amount)`                            | `bool`        | Deducts money if funds are sufficient.           |
| `closeAccount()`                              | `void`        | Deactivates the bank account.                    |

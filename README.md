# VirtualCash

VirtualCash is a Java-based application that simulates a virtual banking system, allowing users to manage accounts, perform transactions, and monitor their financial activities in a secure and user-friendly environment.

## Features

- **Account Management**: Create and manage multiple user accounts with unique identifiers.
- **Deposit and Withdrawal**: Securely deposit and withdraw funds from user accounts.
- **Fund Transfers**: Transfer funds between accounts with real-time balance updates.
- **Transaction History**: View detailed transaction logs for each account.
- **Authentication**: Secure login system to protect user information and prevent unauthorized access.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Athena65/VirtualCash.git
   cd VirtualCash
   ```

2. **Compile the Application**:
   Ensure you have Java Development Kit (JDK) installed. Compile the Java files using:
   ```bash
   javac -d bin src/com/virtualcash/*.java
   ```

3. **Run the Application**:
   Navigate to the `bin` directory and execute the main class:
   ```bash
   cd bin
   java com.virtualcash.Main
   ```

## Usage

Upon launching the application:

- **New Users**: Register by providing necessary details to create an account.
- **Existing Users**: Log in using your credentials.
- **Dashboard**: Access features like deposit, withdrawal, fund transfer, and view transaction history.

## Project Structure

- `src/com/virtualcash/`: Contains the Java source files.
- `bin/`: Compiled Java classes.
- `resources/`: Any additional resources like configuration files or assets.

## Contributing

We welcome contributions to enhance VirtualCash. To contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/YourFeature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/YourFeature`
5. Open a pull request.

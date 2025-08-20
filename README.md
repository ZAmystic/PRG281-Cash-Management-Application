# 💰 Cash and Inventory Management Console App

A robust C# console application built to empower small businesses with essential tools for cash flow and inventory management. Leveraging all four OOP principles (Encapsulation, Inheritance, Abstraction, and Polymorphism), this app features secure UTF-8 hashing for password encryption, modular classes and objects, ASCII art-driven interfaces, events for control panel access, threads for loading bars, delegates for automated method invocation, enums for data structuring, and more—all in a user-friendly terminal environment.

## 🚀 Overview

This app serves as a practical solution for tracking cash inflows/outflows and maintaining inventory records, helping users avoid common financial pitfalls. It was created in response to extensive research highlighting that up to 82% of small businesses fail due to poor cash flow management. By providing intuitive features for adding cash/expenses, viewing net cash and stats, and managing inventory, it promotes better financial oversight and sustainability. Ideal for developers exploring advanced C# concepts or business owners seeking a simple, no-frills management tool.

## 🔍 How It Works

The application is divided into two main sections: Cash Management and Inventory Management. Users navigate via a menu-driven interface with ASCII art enhancements for visual engagement.

### Cash Management Section
1. **Add Cash**: Record incoming funds with details like amount, source, and date.
2. **Add Expense**: Log outgoing expenses, categorizing them for easy tracking.
3. **View Net Cash**: Calculate and display the current net cash balance in real-time.
4. **Cash Stats**: Generate summaries, including total inflows, outflows, averages, and trends.

### Inventory Section
1. **Add Item**: Input new inventory items with attributes like name, quantity, price, and category (using enums for consistency).
2. **Remove Item**: Deduct items from stock, updating quantities automatically.
3. **View Inventory**: Display a complete list of items with details, sorted and formatted for clarity.

Operations are secured with password-protected access, utilizing events for control panel entry and threads for smooth loading animations during data processing.

## ✨ Key Features

- **Full OOP Implementation**: Encapsulation for data protection, Inheritance for reusable code structures, Abstraction to hide complexities, and Polymorphism for flexible method behaviors.
- **Secure Password Handling**: Employs UTF-8 hashing for encryption to safeguard user credentials.
- **Modular Design**: Utilizes classes and objects extensively for everything from data models (e.g., CashTransaction, InventoryItem) to UI components.
- **ASCII Art Interfaces**: Custom ASCII-based menus and banners for an engaging, retro console experience.
- **Event-Driven Control**: Events trigger access to the control panel, ensuring controlled and responsive interactions.
- **Threaded Loading Bars**: Multi-threading powers dynamic progress bars during operations like data loading or calculations.
- **Delegate Automation**: Delegates automatically invoke methods, such as starting background tasks or event handlers.
- **Enum Utilization**: Defines structured options (e.g., for expense categories, item types) to enhance code readability and prevent errors.
- **Data Persistence**: Stores cash and inventory data in-memory (with potential for file-based extensions).
- **User-Friendly Validation**: Built-in checks for inputs to maintain data integrity.

## 🛠️ Tech Stack

- **Language & Framework**: C# (.NET Console Application)
- **Core Libraries**:
  - `System.Security.Cryptography` for UTF-8 hashing and encryption.
  - `System.Threading` for multi-threaded loading bars.
  - Standard .NET features for events, delegates, interfaces, enums, and console I/O.
- **Design Principles**: Strict adherence to OOP (Encapsulation, Inheritance, Abstraction, Polymorphism).

## 📋 Prerequisites

- .NET SDK (version 6.0 or later) installed on your machine.
- Basic familiarity with C# for customization.

## ⚙️ Installation & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/cash-inventory-manager.git
   cd cash-inventory-manager
   ```

2. Restore dependencies:
   ```bash
   dotnet restore
   ```

3. Run the app:
   ```bash
   dotnet run
   ```

   Sample Interaction:
   ```
   💰 Welcome to Cash & Inventory Manager! 💰

   [ASCII Art Banner Here]

   Enter password to access control panel: ********

   Main Menu:
   1. Cash Management
   2. Inventory Management
   3. Exit

   Select option: 1

   Cash Management:
   a. Add Cash
   b. Add Expense
   c. View Net Cash
   d. Cash Stats

   ...
   ```

   Follow prompts to manage cash or inventory, with loading bars for processing and automated delegate calls for efficiency.

## 🤝 Contributing

Contributions are welcome! Submit pull requests for improvements, such as adding file persistence or advanced stats. Adhere to OOP best practices and include documentation.
---

Crafted to bridge business needs with coding excellence. Report issues or suggest features on GitHub! 🚀

# Personal Finance Tracker App

A simple and user-friendly Android app built with **Kotlin** to help users manage their income, expenses, and budgets. The app supports adding, editing, and deleting transactions, viewing charts, setting budgets, and exporting/importing financial data.

## Features

- **Dashboard Overview**
  - Displays total income, expenses, and balance.
  - Simple, clean UI using Material Design.

- **Add Transactions**
  - Input transaction title, amount, category, and date.
  - Categories: Food, Transport, Bills, Shopping, etc.

- **View / Edit / Delete Transactions**
  - View all transactions in a list using `RecyclerView`.
  - Edit or delete individual transactions.

- **Budget Management**
  - Set monthly budget limits per category.
  - Visualize remaining budget.

- **Data Export / Import**
  - Export all transaction data as a JSON file.
  - Import from existing JSON backup.

- **Notifications**
  - (Optional) Get alerts when approaching budget limits.

## Technologies Used

- **Kotlin**
- **Android SDK**
- **SharedPreferences** (for lightweight data storage)
- **Gson** (for JSON parsing)
- **MPAndroidChart** (for visualizing expenses)
- **Material Components** (UI)


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/finance-tracker-android.git
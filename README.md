# Finance Dashboard UI

## Live Demo

https://vijaya-2110.github.io/Finance-Dashboard-UI/


## Overview

This project is a simple and interactive finance dashboard built using HTML, CSS, and JavaScript. It allows users to track financial activity, view summaries, and understand spending patterns through visualizations.

The goal of this project is to demonstrate frontend development skills including UI design, state management, and handling dynamic data.

## Features

### Dashboard Overview

* Displays Total Balance, Income, and Expenses
* Line chart showing transaction trends over time
* Pie chart showing income vs expense distribution
* Monthly comparison chart for spending analysis

### Transactions Section

* View all transactions with:

  * Date
  * Category
  * Amount
  * Type (Income/Expense)
* Search transactions by category
* Filter transactions (Income/Expense)
* Add new transactions (Admin role)
* Delete transactions

### Role-Based UI

* Viewer: Can only view data
* Admin: Can add and delete transactions
* Role switching implemented using a dropdown

### Insights

* Displays highest spending category for better financial understanding

### Data Persistence

* Uses browser localStorage
* Data remains saved even after page refresh

## How to Use

###  Viewer Mode (Default)

1. Open the dashboard
2. View summary cards (Balance, Income, Expense)
3. Analyze charts (Line chart, Pie chart, Monthly chart)
4. Use:

   * Search bar → filter by category
   * Dropdown → filter by income/expense
 Viewer **cannot add or delete transactions**

###  Admin Mode

1. Change role from **Viewer → Admin** (top right dropdown)
2. You will see input fields:

   * Category
   * Amount
   * Type (Income/Expense)

#### ➕ Add Transaction

3. Enter details
4. Click **Add**
    Transaction will be added
    Charts and balance update automatically

####  Delete Transaction

5. Click **Delete** button in any row
    Transaction will be removed
    UI updates instantly

## Setup Instructions

1. Download or clone the project files
2. Open the project folder in VS Code (optional)
3. Open the `index.html` file in a browser

OR

* Right-click `index.html` in VS Code
* Click **"Open with Live Server"**

## Approach

The project is built using a simple and modular approach:

* HTML is used to structure the dashboard layout
* CSS is used for styling and responsive design
* JavaScript manages application state and UI updates

Transactions are stored in an array and updated dynamically. Whenever data changes (add/delete), the UI and charts are re-rendered. Chart.js is used for visualization, and localStorage is used to persist data across sessions.

## Technologies Used

* HTML
* CSS
* JavaScript
* Chart.js

## Author

Chekka Vijaya Lakshmi

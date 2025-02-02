# Personal Budget Tracker

## Overview

The **Personal Budget Tracker** is a simple web application that helps users manage their monthly income and expenses. It allows users to:

- Add new income or expense entries with details like amount, category, description, and date.
- View a summary of the recorded transactions categorized by Food, Transportation, Entertainment, Salary, Savings, Utilities, and Housing.
- Edit or delete any transaction directly from the summary table.

![Personal Budget Tracker Screenshot](images/screenshot.png)

## Features

- **Add New Income/Expense**:
  - **Amount**: Users input the amount for income or expense.
  - **Category**: Select from predefined categories such as Food, Transportation, Entertainment, etc.
  - **Description**: A brief description of the transaction.
  - **Date**: Select the date when the transaction occurred.
  - **Type**: Choose between Income and Expense using radio buttons.

- **Budget Summary**:
  - Displays a table listing all the recorded transactions.
  - Includes details like the category, amount, description, status (Completed/Pending), and options to **Edit** or **Delete** each entry.

## Technologies Used

- **HTML5**: Structure and content of the web page.
- **CSS** (optional for future styling): For enhancing the visual appearance.
- **JavaScript** (optional for future functionality): For handling form submissions and dynamic updates (may be added later).

## How to Use

1. Clone or download this repository to your local machine.
2. Open the `index.html` file in any web browser.
3. Add new transactions by entering the amount, selecting the category, adding a description, and choosing a date.
4. Specify whether the entry is an income or an expense using the radio buttons.
5. Click **Add Entry** to save the transaction.
6. View your budget summary with all recorded transactions. You can **Edit** or **Delete** any entry.

## Future Enhancements

- Add JavaScript functionality to store and update transactions dynamically (currently, the form and table are static).
- Integrate with a backend to store data in a database (e.g., using Node.js, Express, and MongoDB).
- Implement user authentication for secure personal budget management.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to any resources or libraries you might have used (add here if applicable).

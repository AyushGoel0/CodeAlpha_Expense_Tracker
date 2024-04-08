# CodeAlpha_Expense_Tracker
## Expense Tracker

This is a simple expense tracker application implemented using HTML, CSS, and JavaScript. It allows users to add, edit, and delete expenses. The application integrates local storage to save user data, ensuring that expenses persist even after the page is refreshed or closed.

### Features

- **Add Expense**: Users can add a new expense by entering a description and the amount spent.
- **Edit Expense**: Users can edit existing expenses by modifying the description and amount.
- **Delete Expense**: Users can delete expenses they no longer want to track.
- **Local Storage Integration**: User data, including expenses, is stored locally using browser's local storage feature, ensuring persistence of data across sessions.

### Usage

1. Enter the description of the expense in the "Enter expense description" field.
2. Enter the amount spent on the expense in the "Amount" field.
3. Click on the "Add Expense" button to add the expense to the list.
4. To edit an expense, click on the "Edit" button next to the expense, enter the new description and amount, and click "OK".
5. To delete an expense, click on the "Delete" button next to the expense.

### How it Works

- When the page is loaded, expenses are loaded from local storage if available.
- The `renderExpenses()` function displays the list of expenses on the page.
- Adding, editing, or deleting an expense triggers the respective functions, which update the expenses list and re-render the UI.
- User data is saved to local storage after each update, ensuring persistence.

### Technology Stack

- **HTML**: Structure of the web page.
- **CSS**: Styling of the elements.
- **JavaScript**: Implementing functionality such as adding, editing, and deleting expenses, as well as integrating with local storage.

Feel free to use and modify this expense tracker according to your needs!

# Expense Tracker
This project—a budgeting and expense tracking app—allows you to practice refactoring with `Redux Toolkit`.

The app allows you to set budgets for various categories, such as food and transportation, and track transactions in those categories.

It then sums your spending in each category to calculate the amount of money that remains to be spent.

> ![Diagram](https://raw.githubusercontent.com/RahimGuerfi/expense-tracker/main/public/component_diagram.png)

To help you to understand how the data of the application works, consider an example of the Redux store’s state:

```
{
  budgets: [
    { category: 'housing', amount: 400 },
    { category: 'food', amount: 100 },
    ...
  ],
  transactions: {
    housing: [
      {
        category: 'housing',
        description: 'rent',
        amount: 400,
        id: 123
      }
    ],
    food: [
      {
        category: 'food',
        description: 'groceries on 1/12/2021',
        amount: 50,
        id: 456
      },
      {
        category: 'food',
        description: 'dinner on 1/16/2021',
        amount: 12,
        id: 789
      },
    ]
  }
}
```

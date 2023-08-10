# Expense Management Website

## Overview

Welcome to the Expense Management Website - a full-stack web application developed using the MERN (MongoDB, Express.js, React.js, and Node.js) stack. This platform offers users a seamless and intuitive experience to efficiently manage their income and expenses. The website provides a comprehensive set of features, including user registration and login, tabular representation of expenses, and graphical visualizations for better financial insights.

## Features

- **User Registration and Login**: Users can easily create accounts and securely log in to access the website's functionality.
  ![image](https://github.com/raunak-dev-edu/ExpenseManagement/assets/95216822/13c8d8af-56d1-42d6-ade1-a2fc423406d5)
- **Tabular Form of Expenses**: The website displays a well-organized tabular form that shows all the expenses added by the user.
  ![image](https://github.com/raunak-dev-edu/ExpenseManagement/assets/95216822/7a17ff5a-6a3e-4b67-bae8-cffc7167342a)
- **Add, Edit, and Delete Transactions**: Once logged in, users can add their income and expense transactions, specifying details like the amount, category, and date. They can also edit or delete previously added transactions as needed.
  ![image](https://github.com/raunak-dev-edu/ExpenseManagement/assets/95216822/003c414a-415c-4c1b-9827-a6a8c4d44cff)
- **Graphical Representation**: The website harnesses the power of React-based charting libraries to generate dynamic and visually appealing graphs for each income and expense source. These graphical visualizations offer users a clear understanding of their financial patterns, enabling better expense management.
  ![image](https://github.com/raunak-dev-edu/ExpenseManagement/assets/95216822/08e0c2af-7fc5-4e55-a3f3-a02a633a33bc)

## Technologies Used

- **Frontend**: Developed using React.js, the website provides a seamless and interactive user interface.
- **Backend**: The server-side logic and API routes are handled using Express.js and Node.js, ensuring smooth data communication.
- **Database**: The user information and transaction data are securely stored and managed in a MongoDB database.

## Run the App

1. Clone the repository: `git clone https://github.com/username/expense-management.git`
2. Navigate to the 'config' directory and create a `config.env` file.
3. Inside the `config.env` file, add MongoDB URI:
   `MONGO_URI="mongodb+srv://expenseManagement:expenseManagement@cluster0.gpsl03g.mongodb.net/?retryWrites=true&w=majority"`
5. Start the Backend Server: In the root directory, run `npm start`.
6. Start the Frontend: Navigate to the 'client' directory using `cd client`, and run `npm start` to launch the frontend.






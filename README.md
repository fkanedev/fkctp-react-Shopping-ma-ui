![React](https://img.shields.io/badge/React-v17.0.2-blue.svg)
![Bootstrap](https://img.shields.io/badge/Bootstrap-v5.2.2-purple.svg)
![Node.js](https://img.shields.io/badge/Node.js-v14.17.0-green.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

# Company's Budget Allocation App
This project involves developing a shopping cart expense tracker application using React.js. The main objective is to provide a user-friendly interface for adding items to a shopping cart, managing quantities, and tracking the total expenses. This project is part of my training in the [IBM Full Stack Software Developer Professional Certificate](https://www.coursera.org/professional-certificates/ibm-full-stack-cloud-developer), utilizing a [template](https://github.com/ibm-developer-skills-network/kduia-shopping-app) provided by IBM Developer Skills Network.

## Table of Contents
1. [Introduction](#introduction)
2. [Technologies Used](#technologies-used)
3. [Installation and Configuration](#installation-and-configuration)
4. [Usage](#usage)
5. [Development](#development)
6. [Sources](#sources)
7. [License](#license)
8. [Contact](#contact)

## 1. Introduction <a name="introduction"></a>

### Project Objective:
The main objective of this project is to create a user-friendly expense tracking application that allows users to manage their shopping cart by adding, editing, and removing items, as well as tracking the total expenses. This project uses React.js to build an interactive interface and leverages the context API for state management.

### Key Features:
- Add, edit, and delete items in the shopping cart.
- Track total expenses.
- Dynamic adjustment of budget and currency settings.
- User-friendly interface with responsive design.

## 2. Technologies Used <a name="technologies-used"></a>

### Programming Languages:
- JavaScript

### Tools and Frameworks:
- React.js: A JavaScript library for building user interfaces.
- Bootstrap: A CSS framework for developing responsive and modern web applications.

## 3. Installation and Configuration <a name="installation-and-configuration"></a>

### Prerequisites:
- Node.js and npm installed on your system.

### Installation Steps:
1. Clone the GitHub repository:
    ```bash
    git clone https://github.com/fkanedev/fkctp-react-Shopping-ma-ui
    cd fkctp-react-Shopping-ma-ui
    ```
2. Install the dependencies:
    ```bash
    npm install
    ```

### Environment Configuration:
No specific environment configuration is needed for this project.

## 4. Usage <a name="usage"></a>

### Running the Application:
To start the application, use the following command:
```bash
npm start
```
### Use Case Examples:
- Add a new item to the shopping cart.
- Edit the quantity of an existing item in the shopping cart.
- Remove an item from the shopping cart.
- Track the total cost of items in the cart.
- Change the currency setting.

## 5. Development <a name="development"></a>
Project Structure:
The frontend project is organized around the React framework. The directory structure includes the following folders:

- src/: Contains the core of the application.
  - components/: Contains the React components.
  - context/: Contains context providers for state management.
  - App.js: Main entry point of the application.
  - index.js: Entry point for React rendering.

```plaintext
.
├── src/
│   ├── components/
│   │   ├── CartValue.js
│   │   ├── ExpenseItem.js
│   │   ├── ExpenseList.js
│   │   ├── ItemSelected.js
│   │   ├── Location.js
│   ├── context/
│   │   ├── AppContext.js
│   ├── App.js
│   ├── index.js
│   └── ...
├── package.json
├── LICENSE
├── README.md
└── ...
```

It's organized with a component-based structure using React.js and Context API for state management. The main components include:

- **CartValue.js**: Calculates and displays the total value of items in the shopping cart based on quantity and unit price.
- **ExpenseItem.js**: Renders a single item in the expense list, allowing users to view, edit, and delete each item.
- **ExpenseList.js**: Displays a table listing all items in the expense list, using ExpenseItem.js for each row.
- **ItemSelected.js**: Provides a form interface for users to add or reduce quantities of selected items in the expense list.
- **Location.js**: Allows users to select and change the currency location for displaying item prices.
- **App.js**: The main application component that integrates all the other components.

## 6. Sources <a name="sources"></a>

- **Template: [IBM Developer Skills Network - Shopping app template](https://github.com/ibm-developer-skills-network/kduia-shopping-app)**

- **Useful links**:
  - **[Create React App](https://github.com/facebook/create-react-app)**
  - **[Developing Front-End Apps with React](https://www.coursera.org/learn/developing-frontend-apps-with-react/home/week/1)**
  - **[IBM Full Stack Software Developer Professional Certificate](https://www.coursera.org/professional-certificates/ibm-full-stack-cloud-developer)**

## 7. License <a name="license"></a>

This project is licensed under the MIT License - see the [LICENSE](/LICENSE) file for details.

## 8. Contact <a name="contact"></a>

### Contact Information :

- Send me email : **fkanecloudtech@gmail.com**
- Connect with me on [LinkedIn](https://www.linkedin.com/in/your-profile/)
- Visit my [portfolio](https://yourname.github.io) to explore my projects and services.


### Contribution and Support :

Contributions are welcome. Please refer to the [CONTRIBUTING](/CONTRIBUTING) file for more information on how to contribute.

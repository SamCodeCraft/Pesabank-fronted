# PesaBank

PesaBank is a modern, full-featured banking solution designed to provide users with seamless financial management. This application empowers users to manage their bank accounts, process transactions, apply for loans, and monitor their savings with ease. Built using React for the frontend and Flask for the backend, PesaBank offers a highly interactive and user-friendly experience while ensuring data security and reliability.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [API Documentation](#api-documentation)
- [Installation Guide](#installation-guide)
  - [Prerequisites](#prerequisites)
  - [Backend Setup](#backend-setup)
  - [Frontend Setup](#frontend-setup)
- [Running the Application](#running-the-application)
- [Contributing](#contributing)
- [License](#license)
- [Contact Information](#contact-information)

## Project Overview

PesaBank aims to redefine digital banking with a simple and intuitive interface that supports multiple financial services. Whether it's making payments, checking balances, or applying for loans, PesaBank provides a comprehensive platform that is secure, scalable, and easy to use.

This project highlights the core functionality of a banking system, featuring a robust backend for managing transactions and a dynamic frontend to ensure users can easily interact with the platform.

## Features

- **User Authentication:** Secure sign-up and login system with two-factor authentication.
- **Account Management:** Create, view, and manage bank accounts with detailed transaction histories.
- **Deposit & Withdrawal:** Seamlessly deposit or withdraw funds from accounts.
- **Loan Application:** Users can apply for loans, track their status, and view repayment schedules.
- **Savings Tracker:** Manage savings accounts and monitor progress over time.
- **Responsive Design:** The platform is fully responsive and accessible on all device types.
- **Detailed Transaction Logs:** View and export past transactions, filtered by date or type.
- **Notifications:** Get notified of important account activities like low balance alerts or loan approvals.

## Technologies Used

PesaBank leverages a modern tech stack to provide both frontend and backend functionality:

**Frontend:**

- **React.js:** JavaScript library for building user interfaces.
- **React Router:** For managing application routes and navigation.
- **Redux:** For state management.
- **Axios:** For handling HTTP requests to the backend API.

**Backend:**

- **Flask:** Lightweight web framework for Python.
- **Flask-RESTful:** For building RESTful APIs.
- **SQLAlchemy:** Object-relational mapping (ORM) tool for interacting with the database.
- **PostgreSQL:** Relational database management system used to store account and transaction data.

**Testing:**

- **Jest:** For unit testing React components.
- **PyTest:** For backend unit testing in Flask.

**CI/CD Tools:**

- **GitHub Actions:** Automating testing and deployment pipelines.
- **Docker:** For containerization and ensuring consistency across environments.

## API Documentation

PesaBank’s backend API provides multiple endpoints for interacting with the banking system. Below is a summary of the main API endpoints:

| HTTP Method | Endpoint                     | Description                                  |
| :---------- | :-------------------------- | :------------------------------------------- |
| POST        | /api/auth/register          | Register a new user account                  |
| POST        | /api/auth/login             | Login a user and generate an authentication token |
| GET         | /api/accounts                | Get all bank accounts for the logged-in user |
| POST        | /api/transactions           | Create a new transaction (deposit/withdrawal) |
| GET         | /api/loans                   | View user’s loan applications                |
| POST        | /api/loans/apply            | Apply for a new loan                         |

For full API documentation, refer to the Swagger API Documentation hosted at /api/docs.

## Installation Guide

Follow these steps to set up the project locally:

### Prerequisites

Ensure you have the following installed:

- Node.js
- Python
- PostgreSQL
- Docker (optional, for containerization)

### Backend Setup

1. Clone the repository:

```bash
git clone https://github.com/your-username/pesabank.git
cd pesabank


## License

PesaBank is licensed under the MIT License.

## Contact Information

For inquiries or support, please reach out via:

- Email: siyajalis@gmail.com
- LinkedIn: [Samuel Siyajari](linkedin.com/in/samuel-siyajari-970365167) 

- GitHub: [PesaBank Repository](https://github.com/SamCodeCraft/Pesabank-frontend) 

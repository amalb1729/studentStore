# Student Store Full-Stack Application

This is the main repository for the Student Store project, a full-stack e-commerce application. The project is structured as a monorepo using Git submodules to manage the backend server, the admin user interface, and the customer-facing user interface.

## Project Architecture

The application is split into three main components, each managed in its own repository and included here as a submodule:

*   **`server`**: A Node.js and Express.js backend that provides a RESTful API for handling business logic, data storage, and authentication.
*   **`admin-ui`**: A React-based single-page application for store administrators to manage products, orders, and users.
*   **`user-ui`**: A React-based single-page application for students (users) to browse products, manage their cart, and place orders.

## Technology Stack

*   **Backend**: Node.js, Express.js, MongoDB (with Mongoose)
*   **Frontend**: React, React Router
*   **Version Control**: Git, Git Submodules

## Prerequisites

Before you begin, ensure you have the following installed on your local machine:
*   Git
*   Node.js (v16 or later recommended)
*   npm (comes with Node.js)
*   MongoDB (running locally or a cloud instance)

## Getting Started

1.  **Clone the Repository with Submodules**

    Use the `--recurse-submodules` flag to clone the repository and automatically initialize and update each submodule.

    ```bash
    git clone --recurse-submodules https://github.com/amalb1729/studentStore.git
    cd studentStore
    ```

2.  **Install Dependencies and Run Each Service**

    Each submodule has its own `README.md` file with specific instructions for installation and startup. Please navigate into each directory and follow the steps:

    *   **Setup the Server**
    *   **Setup the Admin UI**
    *   **Setup the User UI**
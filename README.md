# E-commerce Data Visualization Web Application

This is a full-stack data visualization web application that analyzes e-commerce data from a sample Shopify store stored in MongoDB. The application is built using Node.js (with Express) and React.js. It provides several visualizations for e-commerce metrics like total sales, sales growth rate, customer lifetime value, and more.

## Features

- **Total Sales Over Time**: Visualization of total sales grouped by intervals (daily, monthly, quarterly, yearly).
- **Sales Growth Rate Over Time**: Visualization of sales growth over time.
- **New Customers Added**: Visualization of new customers based on their creation date.
- **Repeat Customers**: Visualization of customers with more than one purchase across different intervals.
- **Geographical Distribution of Customers**: Visualization of customers based on their location (city).
- **Customer Lifetime Value by Cohorts**: Visualization of customer lifetime value grouped by cohort based on their first purchase.

## Technologies Used

- **Frontend**: React.js, Chart.js
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Deployment**: Vercel (Frontend), Render (Backend)

## Live Demo

You can access the live version of the app here: [App Link](#) (Replace this with your actual URL)

## Setup Instructions

To run the app locally, follow these steps:

### Prerequisites

- Node.js and npm installed
- MongoDB database with the provided connection string

### Backend Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name/backend
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Set up your environment variables in a `.env` file:
    ```
    MONGODB_URI=mongodb+srv://db_user_read:LdmrVA5EDEv4z3Wr@cluster0.n10ox.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0
    PORT=5000
    ```

4. Start the server:
    ```bash
    npm start
    ```

### Frontend Setup

1. Navigate to the frontend folder:
    ```bash
    cd ../frontend
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Set the backend API URL in your environment:
    ```bash
    REACT_APP_API_URL=http://your-backend-url.com
    ```

4. Start the React app:
    ```bash
    npm start
    ```

## Deployment Instructions

### Backend (Render)
- Follow the steps provided in the [Render Deployment Guide](https://render.com/docs/deploy-node-express-app) to deploy your backend.

### Frontend (Vercel)
- Follow the steps provided in the [Vercel Deployment Guide](https://vercel.com/docs).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

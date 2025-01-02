**Access the WebApp here:**
https://findb.vercel.app/

# MERN Finance Dashboard

A full-stack finance dashboard application built with the MERN stack (MongoDB, Express.js, React, Node.js) and Machine Learning capabilities. 
The dashboard provides comprehensive financial analytics, data visualization, and predictive insights. 
It is designed to assist businesses in understanding their financial performance, identifying trends, and making data-driven decisions.

This project is designed to give businesses actionable insights into their financial data through advanced analytics and intuitive visualizations. 
By leveraging Machine Learning for revenue predictions, it provides a forward-looking perspective for financial planning. 
While building this project, I learned how to integrate Machine Learning models into a full-stack application and how to create interactive dashboards that simplify complex financial data for end-users. 
It also deepened my understanding of React, Redux, and data visualization with Recharts.


## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
  - [Frontend](#frontend)
  - [Backend](#backend)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Environment Variables](#environment-variables)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [API Endpoints](#api-endpoints)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Features
- Interactive dashboard with real-time financial data visualization.
- Revenue and expense analytics for business insights.
- Product performance metrics for decision-making.
- Transaction history tracking and detailed analysis.
- Machine Learning-powered revenue predictions.
- Responsive design for seamless use across devices.
- Dark theme UI for enhanced user experience.

## Technologies Used

### Frontend
- **React 18**
- **TypeScript**
- **Material-UI (MUI)** for styling and components.
- **Redux Toolkit** for state management.
- **Recharts** for interactive data visualization.
- **Regression.js** for predictive analytics.
- **Vite** for fast builds and development.

### Backend
- **Node.js** for server-side scripting.
- **Express.js** for building RESTful APIs.
- **MongoDB** with **Mongoose** for database management.

## Prerequisites
- **Node.js** (v20.15.0 or higher).
- **MongoDB** database.
- npm or yarn package manager.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yg2005/MERN-ML-Finance-Dashboard.git
   cd MERN-ML-Finance-Dashboard
   ```

2. **Install dependencies** for both the client and server:
   ```bash
   # Navigate to the client folder
   cd client
   npm install

   # Navigate to the server folder
   cd ../server
   npm install
   ```

3. **Set up MongoDB**:
   - Ensure you have MongoDB running locally or use a cloud-hosted MongoDB service.

4. **Add environment variables**:
   - Create a `.env` file in the `server` directory with the following keys:
     ```env
     MONGO_URI=your_mongo_connection_string
     PORT=5000
     ```

5. **Run the application**:
   ```bash
   # Start the backend
   cd server
   npm run dev

   # Start the frontend
   cd ../client
   npm run dev
   ```

6. **Access the dashboard**:
   - Open `http://localhost:3000` in your browser.

## Environment Variables
| Key           | Description                          |
|---------------|--------------------------------------|
| `MONGO_URI`   | MongoDB connection string            |
| `PORT`        | Backend server port (default: 5000) |

## Usage
This project is intended to provide businesses with an intuitive interface for analyzing and monitoring financial data. With advanced visualizations and Machine Learning-powered predictions, users can make data-driven decisions to optimize their operations and finances.

## Project Structure
```
MERN-ML-Finance-Dashboard/
├── client/         # Frontend React application
├── server/         # Backend Express application
├── README.md       # Project documentation
└── .gitignore      # Ignored files
```

## API Endpoints
- `GET /kpi/kpis`:
- `GET /product/products`: 
- `GET /transaction/transactions`: 
- `POST /api/predictions`: Generate predictions for future revenue.

## Deployment
1. **Build the frontend**:
   ```bash
   cd client
   npm run build
   ```

2. **Use Fly.io for backend hosting | Vercel for frontend hosting**
   OR **Set up a hosting service** (e.g., Heroku, AWS, Netlify) and deploy both the frontend and backend.

## Contributing
Contributions are welcome! Please fork the repository, create a branch, and submit a pull request.

## License
This project is licensed under the MIT License.

---


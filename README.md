# SubAnalytics

SubAnalytics is a subscription analytics tool designed to help SaaS businesses gain insights into their customer data. It offers predictive analytics on churn rates, MRR (Monthly Recurring Revenue), revenue churn, and Customer Lifetime Value (CLV), empowering businesses to make data-driven decisions.

## Features

- **User-Friendly Dashboard:** Interactive gallery of cards displaying various charts and insights.
- **Data Upload:** Upload customer data via Excel files.
- **Predictive Analytics:** AI-powered predictions on future churn rates and other metrics.
- **Key Metrics Tracking:** Insights into:
  - Churn rate
  - Monthly Recurring Revenue (MRR)
  - Revenue churn
  - Customer Lifetime Value (CLV)

## Technology Stack

- **Frontend:** React.js, Chart.js
- **Backend:** Node.js with Express, Flask
- **Database:** MongoDB
- **AI/ML:** Python for predictive modeling (using Pandas, Scikit-learn)

## Installation

### Prerequisites
- Node.js and npm installed
- MongoDB database set up
- Python installed with necessary ML libraries

### Backend Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/tusharsrivastav/subanalytics.git
   cd subanalytics/backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables in a `.env` file:
   ```env
   PORT=5000
   MONGO_URI=your_mongo_connection_string
   JWT_SECRET=your_jwt_secret
   ```
4. Start the server:
   ```bash
   npm start
   ```

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd ../frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```

### Predictive Model Setup
1. Navigate to the `ml` directory:
   ```bash
   cd ../ml
   ```
2. Install Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the model:
   ```bash
   python model.py
   ```

## Usage

1. Register or log in to the platform.
2. Upload your customer data (Excel format).
3. View analytics and predictions on the dashboard.
4. Use insights to improve customer retention and revenue.

## Contributing

We welcome contributions! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push the branch:
   ```bash
   git push origin feature-name
   ```
4. Open a pull request.

## Authors

- **Tushar Srivastava** - [GitHub](https://github.com/tusharsrivastav)  
- **Tushar Kr. Sharma** - [Github](https://github.com/tush1809)
- **Varun Mishra** - [GitHub](https://github.com/var-mishra)  
- **Utkarsh Mishra** 

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- AI/ML libraries like Scikit-learn and TensorFlow
- Frontend design inspiration from various open-source projects
- MongoDB for seamless database management

---

For any questions or support, feel free to contact us at [tusharsrivastava2003@gmail.com](mailto:tusharsrivastava2003@gmail.com).

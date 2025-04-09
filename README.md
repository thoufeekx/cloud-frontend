# Credit Risk Predictor - Simple Frontend

This is a simplified frontend for the Credit Risk Predictor application. It's built as a static HTML page that connects to the backend API.

## Features

- Simple form interface for credit risk prediction
- Real-time connection to backend API
- Clean and responsive design
- Error handling and loading states

## Deployment

This application is deployed using Azure Static Web Apps. The deployment is triggered automatically on pushes to the main branch.

## Backend API

The frontend connects to the backend API hosted at:
- https://credit-risk-backend.azurewebsites.net/api/predict

## Usage

1. Enter the required information:
   - Credit Limit
   - Age
   - Credit Utilization
   - Payment Ratio
2. Click "Predict Risk" to get the prediction
3. View the risk level and credit utilization ratio in the results section

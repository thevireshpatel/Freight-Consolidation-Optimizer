# Freight Consolidation Optimizer

## Overview
The Freight Consolidation Optimizer is an AI/ML-powered solution designed to minimize transportation costs in logistics operations. By predicting the total cost of shipments, this tool enables companies to make data-driven decisions for optimal freight consolidation and route planning.

## Problem Statement
The logistics industry faces significant challenges in minimizing transportation costs while meeting delivery deadlines and handling various operational constraints. Traditional methods often fail to account for the complex interplay of factors affecting shipment costs, leading to suboptimal routing and increased expenses.

## Solution Approach
Our solution employs a machine learning pipeline that:
1. Processes and cleans logistics data
2. Engineers relevant features capturing geographical, temporal, and operational aspects
3. Trains a gradient boosting regression model to predict total transportation costs
4. Provides actionable insights for cost optimization

## Dataset
The model is trained on a comprehensive dataset containing shipment information with the following features:
- Geographical coordinates (pickup and delivery)
- Vehicle specifications
- Cost components
- Time-related information
- Operational constraints

## Features
- **Cost Prediction**: Accurately predicts total transportation costs
- **Geospatial Analysis**: Incorporates Haversine distance calculations
- **Temporal Features**: Extracts meaningful time-based information
- **Operational Constraints Handling**: Accounts for special requirements and deadlines
- **Scalable Architecture**: Designed for easy integration with existing logistics systems

## Getting Started
### Prerequisites
- Python 3.7+
- Required libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

### Installation
1. Clone the repository:
   ```
   git clone https://https://github.com/thevireshpatel/Freight-Consolidation-Optimizer
   ```
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage
1. Prepare your dataset in CSV format with the required columns
2. Update the configuration file with your specific parameters
3. Run the notebook:
   ```
   jupyter notebook freight_optimizer.ipynb
   ```
4. Follow the step-by-step instructions in the notebook

## Model Performance
| Metric         | Value  |
|----------------|--------|
| MAE            | 12.45  |
| RMSE           | 18.76  |
| R² Score       | 0.89   |

## Deployment
The model can be deployed as a REST API using Flask or FastAPI. The saved model file (`freight_optimizer_model.joblib`) can be loaded for real-time predictions.

## Contributing
 Contributions are welcome! Please submit a pull request or create an issue for any improvements or bug fixes.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

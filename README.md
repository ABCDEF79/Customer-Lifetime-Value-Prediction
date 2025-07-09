# Customer Lifetime Value Prediction

This project predicts the future value of a customer using historical retail transaction data.

## Dataset
- **Features:** InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

## Method

1. Clean data (remove cancellations, missing values)
2. Engineer RFM features
3. Train linear regression model to predict CLV
4. Save predictions

## Project Structure

## How to Run

1. Clone this repo
2. Place dataset in `/data`
3. Run the notebook in `/notebooks`
4. Explore predictions in `clv_results.csv`


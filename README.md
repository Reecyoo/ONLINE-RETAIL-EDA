## Online Retail - Customer Behavior EDA

This project performs an exploratory data analysis (EDA) of an online retail store's transactional data. The primary objective is to uncover insights into customer purchasing behavior, top-selling products, and sales trends, and to segment customers using RFM analysis.

---

## Project Structure

```
online-retail-eda/
├── data/
│   └── Online Retail.xlsx
├── notebooks/
│   └── 01_EDA_Customer_Behavior.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Project Overview

This dataset contains transactions from a UK-based online retail store. The analysis explores:
- Customer segmentation using **RFM (Recency, Frequency, Monetary)** analysis
- Revenue trends over time
- Top-selling products
- Country-wise revenue analysis
- Feature engineering for better insights

---

## Libraries Used

- pandas  
- numpy  
- matplotlib  
- seaborn  
- plotly  
- datetime

---

## Key Analyses Performed

- **Data Cleaning**: Removed missing values, filtered out invalid quantities/prices  
- **Feature Engineering**: Created `TotalPurchase`, extracted date parts  
- **Visualizations**:
  - Top countries by revenue
  - Top products sold
  - Monthly revenue trend
- **RFM Analysis**: Scored each customer by Recency, Frequency, and Monetary value

---

## Sample Insights

- Majority of sales come from the **United Kingdom**
- Certain products are purchased in very high volumes
- Customer segments identified with high RFM scores can be targeted for marketing

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/online-retail-eda.git
   cd online-retail-eda
   ```

2. (Optional) Create a virtual environment and activate it.

3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Open the notebook:
   ```bash
   jupyter notebook notebooks/01_EDA_Customer_Behavior.ipynb
   ```

---

## Dataset

This project uses the **Online Retail dataset**, which includes transactions from 2010–2011 for a UK-based online retailer. *(You must have the Excel file placed under `data/Online Retail.xlsx`)*

---

## Contact

For any suggestions or questions, feel free to reach out at [your-email@example.com].

---

## License

This project is open-source under the MIT License.

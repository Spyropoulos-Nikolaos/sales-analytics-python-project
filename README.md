\# Sales Analytics Python Project



\## Project overview



This project is an end-to-end sales analytics case study built with Python, pandas and matplotlib.



The goal of the project is to analyse a synthetic sales dataset for a frame distribution business and extract business insights related to revenue, profitability, products, customers, inventory, sales channels and discount behaviour.



The project follows a complete data analysis workflow:



\- data loading

\- data cleaning

\- data validation

\- table merging

\- KPI calculation

\- product analysis

\- customer analysis

\- time-based analysis

\- inventory and reorder analysis

\- sales channel and sales representative analysis

\- discount analysis

\- export of final summary tables and figures

\- business insights and recommendations



\## Tools used



\- Python

\- pandas

\- NumPy

\- matplotlib

\- Jupyter Notebook



\## Dataset



The project uses three synthetic CSV files:



\- `sales\_orders.csv`

\- `products.csv`

\- `customers.csv`



These tables are joined together to create a final analysis dataset.



Only completed orders are used for the main business analysis.



\## Key KPIs



The final completed-orders dataset includes:



\- Total net revenue: €210,752.67

\- Total gross profit: €77,276.63

\- Overall margin: 36.7%

\- Total completed orders: 569

\- Total customers: 90

\- Total products: 36

\- Overall return rate: 1.0%



\## Main analysis areas



\### Product performance



The project analyses products by net revenue, gross profit, margin, return rate and inventory status.  

The analysis shows that product decisions should not be based only on revenue, because some high-revenue products have weaker profitability.



\### Customer performance



Customers are analysed using revenue, gross profit, margin, discount behaviour and returns.  

The project separates high-volume customers from high-margin customers and identifies customers requiring closer commercial review.



\### Time-based performance



Monthly and quarterly trends are analysed to understand how revenue and gross profit evolve during the year.  

Q4 and December appear as the strongest sales periods in the dataset.



\### Inventory and reorder analysis



Inventory risk is analysed using current stock, reorder points, average monthly net quantity and stock coverage in months.  

The analysis identifies urgent reorder items, watchlist products and slow-moving products with overstock risk.



\### Sales channel and sales representative analysis



Sales channels and sales representatives are compared using revenue, gross profit, margin, discount behaviour, payment days and returns.



\### Discount analysis



Discount bands are created to compare profitability across different discount ranges.  

The 3%–7% discount range generated the highest total gross profit in this dataset, but this is a descriptive finding and does not prove a causal relationship.



\## Selected outputs



The project exports final summary tables to the `outputs/` folder, including:



\- `kpi\_summary.csv`

\- `product\_summary.csv`

\- `customer\_summary.csv`

\- `monthly\_summary.csv`

\- `inventory\_summary.csv`

\- `channel\_summary.csv`

\- `sales\_rep\_summary.csv`

\- `discount\_summary.csv`

\- `immediate\_reorder\_list.csv`

\- `over\_stock\_list.csv`

\- `strategic\_products\_list.csv`



Selected figures are exported to:



```text

outputs/figures/


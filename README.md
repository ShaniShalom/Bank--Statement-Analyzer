# Bank--Statement-Analyzer
Bank Statement Analyzer: Boston Living Expenses 📊
A Python-based data science project designed to automate the analysis of monthly bank statements (PDF format). This tool was specifically developed to track and categorize personal spending in the Boston area, providing clear visual insights into financial habits.

🚀 Features
PDF Data Extraction: Automatically parses text from Bank of America statements using PyPDF2.

Smart Categorization: Uses a custom keyword-mapping engine to classify transactions (e.g., Groceries, Dining Out, Transport, Leisure).

Multi-Account Support: Capable of processing multiple PDF files simultaneously to provide a unified family budget view.

Data Visualization: Generates informative pie charts and summary tables using Matplotlib and Pandas.

Export Capabilities: Converts processed data into clean CSV files for further analysis in Excel.

🛠️ Tech Stack
Language: Python

Libraries: Pandas, Matplotlib, PyPDF2, Re (Regular Expressions)

Environment: Google Colab

📈 Sample Analysis Results
The analyzer splits spending into granular categories to help distinguish between essential living costs and discretionary spending:

Groceries: (Trader Joe's, Costco, The Butcherie)

Dining Out: (Local Boston pizzerias and bakeries)

Transport: (MBTA, Uber, U-Haul)

Super Store USA Data Analysis
This project contains a comprehensive data analysis of a Super Store based in the USA. Analyzed using Python in Jupyter Notebook. The analysis includes various visualizations created using Numpy, Pandas, and Seaborn.
![image](https://github.com/user-attachments/assets/b5b81abd-8655-4d3a-b0be-ea72721a8d4d)


Table of Contents
Introduction
Dataset
Installation
Usage
Data Analysis
Visualizations
Conclusion
License
Introduction
This project aims to perform an in-depth analysis of a Super Store's dataset to uncover insights and patterns in the data. The analysis covers various aspects such as sales performance, customer segmentation, and product categories.

Dataset
It contains information on sales transactions, customer segments, product categories, and more.

Installation
To run this project, you need to have Python and Jupyter Notebook installed on your system. Additionally, you need to install the required Python libraries.

Clone the repository:

bash
Copy code
git clone  https://github.com/PranjalF-5/Exploratory-Data-Analysis
cd superstore-usa-data-analysis
Install the required libraries:

bash
Copy code
pip install -r requirements.txt
Usage
Open the Jupyter Notebook and run the cells to perform the analysis.

bash
Copy code
jupyter notebook Superstore_USA_Data_Analysis.ipynb
Data Analysis
The analysis includes:

Data cleaning and preprocessing
Exploratory data analysis (EDA)
Analysis of sales performance
Customer segmentation analysis
Product category analysis
Visualizations
The visualizations are created using Pandas and Seaborn. Some of the key visualizations include:

Sales distribution by product category
Sales trend over time
Customer segmentation breakdown
Heatmap of sales across different regions
Example visualization code:

python
Copy code
import matplotlib.pyplot as plt
import seaborn as sns
import pandas as pd

# Load dataset
dataset = pd.read_csv('Superstore_USA.csv')

# Example plot
plt.figure(figsize=(5, 4))
sns.countplot(x="Product Category", data=dataset[dataset["Product Category"] == "Office Supplies"], hue="Product Sub-Category")
plt.title("Product Category: Office Supplies")
plt.show()
Conclusion
The data analysis provides valuable insights into the performance of the Super Store, helping to identify trends and patterns that can be used for strategic decision-making.

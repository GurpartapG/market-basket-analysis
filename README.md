# 🛍️ Market Basket Analysis with Apriori Algorithm

This project explores **frequent itemset mining** and **association rule learning** using real-world retail transaction data. Using the **Apriori algorithm**, we identify which products are commonly bought together and generate actionable business insights per region.

## 📌 Objective

To uncover hidden patterns in retail transaction data and generate association rules that reveal common co-purchase behavior. The analysis includes a **region-wise comparison** across the UK, France, and Germany.

## 🧰 Tools & Libraries

- Python, Pandas, NumPy
- mlxtend (Apriori, Association Rules)
- Seaborn, Matplotlib, NetworkX

## 📚 Dataset

- [Online Retail Dataset (UCI)](https://archive.ics.uci.edu/ml/datasets/Online+Retail)
- Transactional data from 2010–2011 for a UK-based online store
- Countries included: UK, France, Germany, etc.

## 🛠️ Key Steps

1. Data Cleaning and filtering by region
2. Transforming transactions to basket format
3. Applying Apriori algorithm to find frequent itemsets
4. Generating association rules (confidence, lift, support)
5. Visualizing frequent pairs and rule networks
6. Comparing patterns across countries

## 📊 Sample Insights

- In the **UK**, customers who bought "paper" and "pen" often also bought "notebooks"
- In **Germany**, "candles" are frequently paired with "gift bags"
- In **France**, "tea sets" are linked with "porcelain trays"

## 📈 Visualizations

- Heatmaps of top itemsets
- Bar plots of rule confidence and lift
- (Optional) Network graphs showing item linkages

## 🚀 Project Status

- [x] Dataset loaded and cleaned
- [x] Region-wise segmentation
- [ ] Visualizations and comparative insights
- [ ] Business summary writeup

## 📦 Folder Structure

# 🛍️ Market Basket Analysis with Apriori Algorithm

This project explores **frequent itemset mining** and **association rule learning** using real-world retail transaction data. Using the **Apriori algorithm**, we identify which products are commonly bought together and generate actionable business insights per region.

## 📌 Objective

To uncover hidden patterns in retail transaction data and generate association rules that reveal common co-purchase behavior. The analysis includes a **region-wise comparison** across the UK, France, and Germany.

## 🧰 Tools & Libraries

- Python, Pandas, NumPy
- mlxtend (Apriori, Association Rules)
- Seaborn, Matplotlib, NetworkX

## 📚 Dataset

- [Online Retail Dataset (UCI)](https://archive.ics.uci.edu/ml/datasets/Online+Retail)
- Transactional data from 2010–2011 for a UK-based online store
- Countries included: UK, France, Germany, etc.

## 🛠️ Key Steps

1. Data Cleaning and filtering by region
2. Transforming transactions to basket format
3. Applying Apriori algorithm to find frequent itemsets
4. Generating association rules (confidence, lift, support)
5. Visualizing frequent pairs and rule networks
6. Comparing patterns across countries

## 📊 Sample Insights

- In the **UK**, customers who bought "paper" and "pen" often also bought "notebooks"
- In **Germany**, "candles" are frequently paired with "gift bags"
- In **France**, "tea sets" are linked with "porcelain trays"

## 📈 Visualizations

- Heatmaps of top itemsets
- Bar plots of rule confidence and lift
- (Optional) Network graphs showing item linkages

## 🚀 Project Status

- [x] Dataset loaded and cleaned
- [x] Region-wise segmentation
- [ ] Visualizations and comparative insights
- [ ] Business summary writeup

## 📦 Folder Structure
market-basket-analysis/
│
├── data/ # Raw and processed data files
├── notebooks/ # Jupyter notebook(s)
├── visuals/ # Plots and graphs
└── README.md # Project overview


## 📍 Next Steps

- Add interactive dashboard (Streamlit) [optional]
- Improve rule filtering (min threshold tuning)
- Add more country segments

## 💡 Learnings

This project demonstrates the power of **unsupervised learning** in discovering shopping behavior, and highlights how association rules can support product bundling, layout optimization, and targeted marketing.

---


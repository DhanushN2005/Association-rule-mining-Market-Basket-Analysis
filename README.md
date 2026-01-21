# Association Rule Mining

This repository contains a Jupyter Notebook that demonstrates how to perform **association rule mining** on transactional data using Python, uncovering frequent itemsets and interesting relationships between items. :contentReference[oaicite:0]{index=0}

## 🧠 Overview

Association rule mining is a data mining technique used to discover **interesting relations between variables** in large datasets. It is commonly applied in market basket analysis, where it helps identify items that frequently occur together. :contentReference[oaicite:1]{index=1}

## 📦 Contents

- `Association_rule_mining.ipynb` – A step-by-step notebook that:
  - Loads and preprocesses transactional data  
  - Finds frequent itemsets based on support  
  - Generates association rules using metrics like confidence and lift  
  - Visualizes or interprets the mined rules

## 🛠️ Dependencies

Make sure you have the following (or install them via `pip`):

```bash
pip install pandas mlxtend jupyter

#How to Run
#Clone this repository:

git clone https://github.com/DhanushN2005/Association-rule-mining.git


#Navigate to the project folder:

cd Association-rule-mining

#Open the notebook:

jupyter notebook Association_rule_mining.ipynb

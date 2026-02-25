# Market Basket & Sequential Pattern Analysis

## Overview
This project analyzes customer purchasing behavior using descriptive data mining techniques. The objective is to uncover frequently co-purchased items and sequential buying patterns to support product bundling and recommendation strategies.

---

## Dataset
- Online Retail II Dataset (UCI Repository)
- 1.04 million cleaned transactions
- Features: Invoice, StockCode, Description, Quantity, Price, Customer ID, Country

---

## Objectives
- Identify frequent itemsets using Apriori
- Generate strong association rules
- Compare support & confidence thresholds
- Evaluate lift and rule strength
- Discover sequential purchasing patterns using PrefixSpan
- Analyze robustness across random seeds

---

## Techniques Used

### Association Rule Mining
- Apriori (multiple support/confidence experiments)
- FP-Growth
- Lift-based evaluation

### Sequential Pattern Mining
- PrefixSpan algorithm
- Time-sorted customer transaction sequences

---

## Key Findings

- Moderate thresholds (Support=2%, Confidence=50%) produced the best balance of rule quality and coverage.
- Average Lift ≈ 14 indicates strong co-purchase relationships.
- Sequential patterns show themed item purchasing behavior.
- Results are robust across multiple random seeds.

---

## Business Impact

- Enables product bundling strategies
- Improves recommendation systems
- Supports inventory planning
- Identifies high-value item combinations

---

## Technologies Used

- Python
- Pandas
- mlxtend
- PrefixSpan
- NumPy
- Matplotlib

---

## How to Run

1. Install dependencies:
   ```
   pip install pandas mlxtend prefixspan
   ```

2. Open:
   ```
   purchase_pattern_analysis.ipynb
   ```

3. Run all cells sequentially.# customer-purchase-pattern-mining

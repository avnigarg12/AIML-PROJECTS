Week 1 - E-Commerce EDA Challenge


Questions & Answers
1. How was the dataset audited?
Checked dataset shape and column types.
Identified missing values and duplicate records.
Reviewed numerical distributions and potential outliers.
2. Is the pricing data skewed?

Answer: Yes.

The price distribution is positively skewed, with most products concentrated at lower prices and a small number of expensive products creating a long right tail.

3. Which categorical columns may cause issues during modeling?

Answer:

High-cardinality features such as customer IDs and city names can increase dimensionality and require careful encoding.

4. Why are customers returning products?

Answer:

Return behavior varies across product categories, customer segments, and regions. Certain groups show consistently higher return rates than others.

5. What preprocessing steps were performed?
Missing value handling
Categorical encoding
Feature scaling
Preprocessing pipeline creation
6. Which features appear most important?

Answer:

Customer-related, transaction-related, and pricing-related features showed the strongest relationship with return behavior.

Tools Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn

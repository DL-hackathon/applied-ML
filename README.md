## Applied Machine Learning (ML)

Usage of algorithms of classical ML.

### Given
A dataset based on the census data extracted from the 1994 and 1995 current population surveys conducted by the U.S. Census Bureau.

### Task

Predict level of income of a person: "- 50000" (means less than \$50k/year) or "50000+" (means more than \$50k/year)

### Solution steps

#### 1. Exploratory data analysis
#### 2. Data preprocessing
* feature engineering;
* PCA for numeric features;
* Missing values substitution;
* sampling techniques for imbalanced classes;
* Features encoding;
* Pipe-lines.
#### 3. Model training
Three models were trained and fine-tuned to compare the results of their predictions:
 * **Support Vector Mashine**;
 * **Randomforest classifier**;
 * **XGBoost**;
 * and their Blending as well.
#### 4. Summary
Regression task successfully solved.
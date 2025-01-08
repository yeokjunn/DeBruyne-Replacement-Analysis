# ⚽ Kevin De Bruyne Replacement - Analysis Project ⚽

## About
This project is inspired by a love for football and data science, particularly the concept of the movie "Moneyball." The focus is on identifying potential replacements for Kevin De Bruyne (*KDB*), one of the most creative midfielders in world football, based on statistical outputs rather than emulating his playing style. The project applies various machine learning methods and similarity measures to analyse players from the top 5 European leagues (England, Germany, Spain, Italy, and France).

The objective is to provide data-driven recommendations by identifying players who can replicate De Bruyne’s creative output, thereby helping Manchester City maintain its offensive effectiveness.

This project implements a complete data pipeline:  
- **Data Collection**  
- **Data Preparation & Cleaning**  
- **Exploratory Data Analysis**  
- **Normalisation Techniques**  
- **Machine Learning Models**  

For a detailed walkthrough, please view the source code in order from:  
1. **ReadMe File**  
2. **Data Cleaning**  
3. **CDR Calculation & Analysis**  
4. **RScore Calculation & Analysis**  
5. **Pearson's Correlation Analysis**  
6. **Euclidean Distance Analysis**  
7. **K-Means Clustering Analysis**  
8. **Conclusions**

---

## **Problem Definition**

How can Manchester City identify the best replacement(s) for Kevin De Bruyne based on multiple creative and attacking metrics across the top 5 European leagues? Which machine learning methods are most effective in finding players with similar outputs to KDB?

---

## **Machine Learning Models Used**

- **For CDR Calculation**:  
  - K-Nearest Neighbors (KNN)  
  - Ridge Regression  
  - Support Vector Machines (SVM)

- **For RScore Calculation**:  
  - Linear Regression  
  - Polynomial Regression  
  - K-Nearest Neighbors (KNN)

- **For Similarity Analysis**:  
  - Pearson's Correlation  
  - Euclidean Distance  
  - K-Means Clustering

---

## **Key Results**

### **CDR Conclusion**  
Players identified with similar CDR scores include:  
- **Ousmane Dembélé**  
- **Jeremy Doku**  
- **Florian Wirtz**  
- **Kevin Stöger**  
- **Toni Kroos**  
- **Luka Modrić**  
- **Isco**

The Support Vector Machines (SVM) model provided the best predictions with the lowest Mean Squared Error (MSE) for CDR.

---

### **RScore Conclusion**  
RScore was used to rank midfielders by combining multiple factors:  
- CDR (65%)  
- League Difficulty (25%)  
- Age (10%)

The top players based on RScore include:  
- **Luka Modrić**  
- **Toni Kroos**  
- **Ivan Rakitić**  
- **Isco**  
- **James Maddison**  
- **Florian Wirtz**

---

### **Pearson's Correlation Conclusion**  
Pearson's correlation was used to find players with the closest statistical output to KDB. Top players include:  
- **Ezequiel Ávila**  
- **Morgan Gibbs-White**  
- **Pablo Sarabia**  
- **Aleksei Miranchuk**  
- **Arne Maier**

---

### **Euclidean Distance Conclusion**  
Using both Min-Max and Z-Score normalization techniques, Euclidean distance was employed to identify players with the shortest distance to KDB. The top players appearing in both results include:  
- **Aleksei Miranchuk**  
- **Luka Modrić**  
- **Thomas Müller**  
- **Raphinha**  
- **Ivan Rakitić**  
- **Harvey Elliott**

---

### **K-Means Clustering Conclusion**  
Players were clustered using K-Means (K=70 for Min-Max, K=50 for Z-Score). Kevin De Bruyne was grouped with players such as:  
- **Raphinha**  
- **Harvey Elliott**  
- **Michael Olise**  
- **Marco Asensio**  
- **Aleksei Miranchuk**

---

## **Conclusion**

While no single player perfectly replicates Kevin De Bruyne’s unique style of play, several players across different leagues can be identified based on their similar output. This approach highlights that replacing KDB may require multiple players in different positions to collectively match his creative impact.

- **Key Insight**: Player replacement should focus on replicating De Bruyne’s output rather than his playing style. If a single replacement cannot fully cover his CDR, adding multiple players with high CDR in different attacking positions (e.g., a winger or attacking midfielder) can help make up for the lost output.

---

## **What Did We Learn?**

1. **Applying Data Cleaning Techniques**:  
   Merging large datasets, handling missing values, and removing outliers were crucial steps.
   
2. **Experimenting with Normalization Methods**:  
   Both Min-Max scaling and Z-score normalization were used to improve the accuracy of similarity analysis.
   
3. **Using Advanced Machine Learning Models**:  
   Techniques such as Support Vector Machines (SVM), K-Nearest Neighbors (KNN), and Polynomial Regression were explored.

4. **Evaluating Similarity Measures**:  
   Pearson’s correlation, Euclidean distance, and K-Means clustering were compared to find the best method for identifying similar players.

---

## **Future Work**

- **Explore More Metrics**:  
  Including defensive metrics or passing accuracy could enhance the analysis.
  
- **Test Other Clustering Methods**:  
  Methods like DBSCAN or Agglomerative Clustering could be explored.
  
- **Integrate Advanced Models**:  
  Using deep learning models could improve prediction accuracy.

---

## **References**

- **Data Source**: [FBRef Dataset](https://fbref.com/en/)  
- **Inspiration**: The movie *Moneyball* and advanced football analytics.

---

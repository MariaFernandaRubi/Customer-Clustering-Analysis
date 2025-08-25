# 👥 Customer Clustering and Data Cleaning Using K-Means in Python

## 📖 Objective
The purpose of this project is to **segment customers into different groups using clustering techniques (K-Means)**.  
By analyzing customer characteristics, the study identifies meaningful groups that can support tailored marketing strategies and business decision-making.

## 🛠️ Tools & Libraries
- **Python (Jupyter Notebook):** For data analysis, modeling, and visualization in an interactive environment.  
- **pandas:** For structuring, cleaning, and manipulating tabular data efficiently using DataFrames.  
- **matplotlib:** For building customizable charts such as line, bar, histogram, and scatter plots.  
- **seaborn:** For professional and statistical visualizations (scatter plots, heatmaps, boxplots).  
- **scikit-learn (sklearn):** For machine learning tasks such as clustering (K-Means), classification, and model evaluation.  

## 📊 Dataset
- **Source:** Ventas_2025.csv
- **Features analyzed:**
- Age
- Purchase Frequency
- Average Amount
- Annual Purchases

## 🔎 Process
1. **Data Preparation**  
   - Cleaned the dataset, handled missing values, and ensured consistent formats.  
   - Selected the most relevant features for clustering.  

2. **Exploratory Data Analysis (EDA)**  
   - Scatter plots and distribution analysis of customer attributes.  
   - Initial visualizations to understand data grouping tendencies.  

3. **Clustering (K-Means)**  
   - Used the **Elbow Method** to determine the optimal number of clusters (k=4).  
   - Applied K-Means algorithm to segment customers into four distinct groups.  

4. **Cluster Analysis**  
   - Interpreted each cluster by analyzing average values and distributions.  
   - Labeled and explained the characteristics of each customer group.  

5. **Business Strategy**  
   - Proposed targeted **marketing strategies for each cluster** to maximize engagement, loyalty, and sales.  

## 📈 Results
- Customers were segmented into **4 groups** with distinct characteristics.  
- Each cluster was profiled (e.g., high spenders, budget-conscious, average buyers, etc.).  
- Clear insights into customer behavior allowed the definition of personalized marketing strategies.  
- Visualizations highlighted the distribution and separation of customer segments.

## 📂 Repository Structure
-	Raw dataset -> Ventas_2025.csv
-	Cleaned dataset -> Clustering_2025.csv
-	Jupyter Notebook with Python code -> Clustering.ipynb
-	Data Insights Presentation -> PT Customer Clustering Analysis.pdf



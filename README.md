# Unlocking-Customer-Insights-Segmentation-Using-Clustering-Techniques
This project focuses on analyzing customer purchasing behavior for an online retail store and segmenting customers into distinct groups using unsupervised ML (K-Means clustering). The segmentation is based on RFM (Recency, Frequency, Monetary) analysis, which helps businesses better understand their customers and make data-driven decisions.

**If you are not taking care of your customers, your competitor will.**

An online retail store wants to:

•	Understand customer purchase patterns. 

•	Identify different types of customers based on their behavior. 

•	Improve business strategies by targeting the right customer segments. 

Traditional analysis does not clearly reveal hidden patterns in large datasets. This project solves that by applying clustering techniques to automatically group similar customers.

**💡 Solution Approach**

The project follows these major steps:

1. Data Understanding & Exploration
•	Dataset: Online retail transactional data (~541K records) 
•	Key features: InvoiceNo, Quantity, UnitPrice, CustomerID, Date, etc. 
•	Performed EDA (Exploratory Data Analysis) to understand distributions and missing values.

3. Data Preprocessing
•	Removed missing values (especially CustomerID) 
•	Converted data types appropriately 
•	Created a new feature:
Amount = Quantity × UnitPrice

5. Feature Engineering (RFM Analysis)
•	Recency (R): Days since last purchase 
•	Frequency (F): Number of transactions 
•	Monetary (M): Total spending 

6. Data Cleaning
•	Removed outliers using IQR method 
•	Standardized features using StandardScaler 

7. Model Building (K-Means Clustering)
•	Used Elbow Method to determine optimal clusters 
•	Used Silhouette Score for validation 
•	Final model built with K = 3 clusters 

8. Visualization & Insights
•	Used boxplots to analyze clusters based on RFM features 
•	Identified behavioral differences among customer groups

**📊 Results & Insights**

•	Some customers contribute significantly more revenue. 

•	A group of customers is inactive and may need re-engagement strategies. 

•	Customer segmentation enables targeted marketing and better resource allocation.

This project helps businesses to Identify high-value customers, improve customer retention strategies, design personalized marketing campaigns and optimize business decision-making using data. Instead of treating all customers the same, the business can now focus on specific customer segments.

🛠️ Tech Stack # K-Mean Clustering # Python # Numpy # Pandas # Matplotlib # Seaborn

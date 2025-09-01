🛍️ Mall Customer Segmentation using K-Means
📌 Project Overview

Customer segmentation is one of the most important applications of unsupervised machine learning in marketing.
In this project, we use the K-Means clustering algorithm to segment mall customers based on their demographic and spending behavior.

The goal is to help businesses understand customer groups better and design targeted marketing strategies.

📂 Dataset

Source: Mall Customers dataset (commonly available in Kaggle / ML repositories)

Columns:

CustomerID – Unique ID assigned to the customer

Gender – Male/Female

Age – Age of the customer

Annual Income (k$) – Customer’s yearly income

Spending Score (1-100) – Score assigned by the mall based on customer spending behavior

⚙️ Steps Involved

Data Preprocessing

Handling missing values (if any)

Selecting important features for clustering (Age, Annual Income, Spending Score)

Feature scaling

Exploratory Data Analysis (EDA)

Visualizing distributions of customers by age, gender, income, and spending score

Scatter plots and pair plots for relationships between variables

Finding the Optimal Number of Clusters (k)

Elbow Method – Identify the point where inertia decreases slowly

Silhouette Score – Evaluate cluster quality

Model Building: K-Means Clustering

Applying K-Means algorithm on selected features

Assigning cluster labels to each customer

Visualization of Clusters

2D scatter plots (Income vs Spending Score, Age vs Spending Score)

Cluster distribution insights

📊 Results & Insights

Customers can be broadly grouped into 5 clusters (e.g., High income–High spenders, Low income–Low spenders, etc.)

Businesses can use these clusters for:

Targeted marketing campaigns

Loyalty programs for high-value customers

Discounts/offers for low-spending groups to improve engagement

🛠️ Tech Stack

Language: Python 🐍

Libraries:

numpy, pandas → Data manipulation

matplotlib, seaborn → Data visualization

scikit-learn → K-Means, metrics

jupyter notebook → Experimentation & reporting

Clone the repository:

git clone https://github.com/Aatishmaurya/Mall-Customer-segmentaion-Kmean.git
cd Mall-Customer-segmentaion-Kmean

Install dependencies:

pip install -r requirements.txt

👤 Author

Aatish Maurya

🌐 GitHub
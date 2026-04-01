📊 Survey Data Analysis + Clustering Model (EDA + K-Means + PCA)

This project provides a complete end-to-end data exploration pipeline using EDA, feature preprocessing, dimensionality reduction (PCA), and clustering (K-Means) to uncover hidden patterns in a survey dataset.

The goal is to help understand behavioral groups, trends, and insights from survey responses using unsupervised machine learning.

🛠️ Tools & Technologies Used
Programming Language
Python 3.x
Libraries & Frameworks
📦 Data Analysis & Visualization
pandas
numpy
matplotlib
seaborn
🤖 Machine Learning
scikit-learn (sklearn)
StandardScaler
KMeans
PCA
LabelEncoder / OneHotEncoder


📌 Requirements (from requirements.txt)

You must install the following libraries:

pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter

Optional (if needed):

scipy
plotly

🔍 Project Workflow
1️⃣ Exploratory Data Analysis (EDA)

Performed using EDA.ipynb:

Check dataset structure
Identify data types
Missing value analysis
Outlier detection
Summary statistics
Category distributions
Correlation heatmap (numeric only)
Visual exploration of patterns in the survey

2️⃣ Data Preprocessing
Convert date/time columns to datetime format
Extract date features (year, month, day, hour)
Encode categorical variables (Label Encoding / One-Hot Encoding)
Scale numeric data using StandardScaler
Drop invalid or constant columns
Prepare data for clustering

3️⃣ Dimensionality Reduction (PCA)
Reduce high-dimensional data to 2 principal components
Preserve maximum variance
Used for visualizing clusters
Helps remove noise

4️⃣ K-Means Clustering
Use Elbow Method to find best K
Train final K-Means model
Assign cluster labels to each survey response
Compute:
Numeric cluster profiles (mean values)
Categorical cluster profiles (most frequent values)

5️⃣ Visualizations
PCA 2D Cluster Plot
Elbow Curve
Correlation heatmaps
Distribution plots
Cluster-level summary tables
📊 Final Outputs

By the end of this project, you will have:

✔ Cleaned, processed dataset
✔ PCA-transformed dataset
✔ K-Means cluster model
✔ Cluster assignments for each entry
✔ Visualizations for understanding hidden patterns
✔ Insights on numeric & categorical cluster groups

▶️ How to Run the Project
Clone the repository
https://github.com/Chief1234/Mentat-Health-and-Tech-survey-eda-clustering-project/tree/main

⭐ Use Cases

This project is ideal for:

Survey analytics
Customer/user segmentation
HR analytics
Marketing research
Behavioral profiling
Unsupervised ML projects
Academic machine learning assignments
🤝 Contributing

Contributions, issues, and suggestions are welcome.
Feel free to fork the repo and submit a pull request!

📄 License

This project is licensed under the MIT License.

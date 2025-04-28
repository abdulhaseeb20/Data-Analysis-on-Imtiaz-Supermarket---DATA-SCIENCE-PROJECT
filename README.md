Customer Segmentation and Purchase Behavior Analysis
This project performs end-to-end customer segmentation and purchase behavior analysis using machine learning models on an electronics retail dataset.

📂 Modules
1. Data Acquisition & Preprocessing
Loaded data from electronics.json

Converted to CSV format for easier processing

Handled missing values, mainly Customer_ID

Initial cleaning and preparation

📸 [Insert screenshot of the first few rows of the dataset]

2. Exploratory Data Analysis (EDA)
Visualized numerical variables: Age, Purchase Amount, etc.

Visualized categorical variables: Gender, Product Category, Brand

📸 [Insert screenshots of a few numerical and categorical plots]

3. Feature Engineering
Encoded categorical variables using Label Encoding and One-Hot Encoding.

4. Clustering
Applied KMeans clustering to segment customers

Used Elbow Method to choose the optimal number of clusters

Visualized the clusters based on important features

📸 [Insert screenshot of Elbow curve and cluster plot]

5. Classification Modeling
Built and evaluated multiple classification models:

Logistic Regression

Decision Tree

Random Forest


Evaluated based on:

Accuracy

Confusion Matrix


📸 [Insert screenshots of model evaluation metrics and ROC curves]

6. Feature Importance
Identified the top factors driving customer behavior using feature importance from Random Forest and XGBoost.

📸 [Insert screenshot of feature importance plot]

⚙️ Technologies Used
Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn


📈 Results
Successfully segmented customers into distinct groups.

Identified key drivers behind customer purchase behavior.

Achieved high accuracy with ensemble models like Random Forest and XGBoost.

📌 Recommendations
Tailor marketing strategies based on identified customer clusters.

Focus on important features like Age, Brand Affinity, and Purchase Frequency.

📎 How to Run
Clone this repository

Install dependencies:
pip install -r requirements.txt

Run the Jupyter Notebook:
jupyter notebook analysis.ipynb

📸 Screenshots
(Place screenshots in a screenshots/ folder and link them above.)

🚀 Next Steps
 -Generate screenshots from your notebook (if you want, I can do this automatically!)

 -Bundle them into a folder

 -Final polish if needed
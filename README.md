**Customer Segmentation and Purchase Behavior Analysis**<br>
This project performs end-to-end customer segmentation and purchase behavior analysis using machine learning models on an electronics retail dataset.

**📂 Modules**<br>
**1. Data Acquisition & Preprocessing**<br>
Loaded data from electronics.json

Converted to CSV format for easier processing

Handled missing values, mainly Customer_ID

Initial cleaning and preparation

📸 ![Cleaned Dataset](image.png)

**2. Exploratory Data Analysis (EDA)**<br>
Visualized numerical variables: Age, Purchase Amount, etc.

Visualized categorical variables: Gender, Product Category, Brand

📸 ![Categorical Plot](image-1.png)
    ![Numerical Plot](image-2.png)

**3. Feature Engineering**<br>
Encoded categorical variables using Label Encoding and One-Hot Encoding.

**4. Clustering**<br>
Applied KMeans clustering to segment customers

Used Elbow Method to choose the optimal number of clusters

Visualized the clusters based on important features

📸 ![Elbow Curve](image-5.png)

**5. Classification Modeling**<br>
Built and evaluated multiple classification models:

Logistic Regression

Decision Tree

Random Forest


Evaluated based on:

Accuracy

Confusion Matrix


📸 ![Confusion Matrix](image-4.png)

**6. Feature Importance**<br>
Identified the top factors driving customer behavior using feature importance from Random Forest.

📸 ![Avg Spending Over Time](image-3.png )

**⚙️ Technologies Used**<br>
Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn


**📈 Results**<br>
Successfully segmented customers into distinct groups.

Identified key drivers behind customer purchase behavior.

Achieved high accuracy with ensemble models like Random Forest and XGBoost.

**📌 Recommendations**<br>
Tailor marketing strategies based on identified customer clusters.

Focus on important features like Age, Brand Affinity, and Purchase Frequency.

**📎 How to Run**<br>
Clone this repository

Install dependencies:
pip install -r requirements.txt

Run the Jupyter Notebook:
jupyter notebook analysis.ipynb

**📸 Screenshots**<br>
(Place screenshots in a screenshots/ folder and link them above.)

**🚀 Next Steps**<br>
 -Generate screenshots from your notebook (if you want, I can do this automatically!)

 -Bundle them into a folder

 -Final polish if needed
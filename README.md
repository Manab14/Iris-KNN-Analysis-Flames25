🌸 Iris-Data-Analysis-Summer-Training-Flames-25
🌼 Iris Dataset Analysis & KNN Classification
This project was developed as part of my Summer Training Program under the guidance of Ms. Gaurika Dhingra on the Flames'25 platform, as a proud member of the Angaar Batch. The main objective is to explore the classic Iris dataset, perform data cleaning, visualization, feature engineering, and build a K-Nearest Neighbors (KNN) classification model.

📂 Dataset
The dataset contains 150 samples of iris flowers across three species, with the following features:

sepal_length (cm)

sepal_width (cm)

petal_length (cm)

petal_width (cm)

Species (Iris-setosa, Iris-versicolor, Iris-virginica)

📁 Dataset Used: Iris.csv (included in this repository)

🔍 What This Project Covers
📊 Exploratory Data Analysis (EDA)
Overview of dataset structure and summary

Detection of missing values and duplicates

Descriptive statistics using .describe(), .info(), .nunique()

🧼 Data Preprocessing
Renamed columns for clarity and dropped irrelevant columns like Id

Handled duplicate entries and outliers (IQR method on sepal_width)

📈 Data Visualization
Used Seaborn and Matplotlib to generate:

Count plots and distribution plots

Box plots, violin plots

Histograms, scatter plots, pair plots

📌 Insights:

petal_length and petal_width are highly discriminative features

Iris-setosa is clearly separable; versicolor and virginica have some overlap

🧠 Feature Engineering
Created new features:

sepal_ratio = sepal_length / sepal_width

petal_ratio = petal_length / petal_width

petal_size categorized into Small, Medium, Large via binning

📌 Insights:

Setosa has a high petal_ratio and low sepal_ratio

Virginica usually has higher ratios than Versicolor

🏷️ Label Encoding
Converted categorical variables Species and petal_size to numeric format using LabelEncoder

🤖 Model Training: K-Nearest Neighbors
Dataset split into training and test sets

Trained and evaluated KNN models with k = 3, 5, and 9

Compared model performance using accuracy and classification reports

📊 Accuracy vs K Plot
Plotted accuracy scores for k = 1 to 19

Found k = 5 yields the best classification performance

📌 Summary of Findings
Iris-setosa is easily separable from other species

Petal length and width are the strongest features

Feature engineering significantly improved model performance

KNN at k=5 achieved high accuracy on the test set

💻 Technologies Used
Python 3

Pandas, NumPy – for data handling

Seaborn, Matplotlib – for visualization

Scikit-learn – for preprocessing and machine learning

🎓 Training Details
Project Title: Iris Dataset Analysis and Classification using KNN

Mentor: Ms. Gaurika Dhingra

Platform: Flames'25

Batch: Angaar Batch

Training Type: Summer Training Program (Data Science / Machine Learning)

📚 Credits
Dataset Source: Iris Dataset - UCI Machine Learning Repository

Guidance: Ms. Gaurika Dhingra Mam

Organized By: Flames'25

Batch: Angaar Batch

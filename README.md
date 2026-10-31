
Social Media Impact on Student Life Prediction and Analysis


📌 About the Project

Social Media Impact on Student Life Prediction and Analysis is a Data Science and Machine Learning project developed using Python. The project focuses on analysing social media usage patterns, identifying behavioral characteristics associated with students' mental health, sleep, and performance, and predicting the overaching lifestyle impact of social media.
By applying structured data preprocessing, Exploratory Data Analysis (EDA), interactive statistical visualizations, feature engineering, and Machine Learning classification pipelines, this project discovers meaningful behavioral correlations and predicts student wellness profiles.

🎯 Project Objectives

The main objectives of this project are:
1. To analyse the distribution of categorical overall impact groups among students.
2. To investigate the relationship between daily social media usage hours and overall life impact.
3. To identify sleep patterns and duration trends across separate impact classifications.
4. To examine the relationship between student stress levels and social media usage.
5. To evaluate how social media impact correlates with academic performance (GPA).

📂 Dataset Description

• Dataset Name: Social Media Impact on Student Life Dataset
• File Name: Social_media_impact_on_life.csv
• Target Variable: Overall_Impact
• Problem Type: Multi-class Classification
The dataset contains a rich set of student behavioral and academic metrics:
• Unique student reference (removed during cleaning): Student_ID
• Demographics and academic status: Age, Gender, Academic_Level
• Device preferences and engagement metrics: Primary_Platform, Daily_Usage_Hours, Weekend_Extra_Hours, Device_Type
• Health indices: Sleep_Duration_Hours, Sleep_Quality_Score, Late_Night_Usage
• Psychological metrics: Social_Comparison_Frequency, Perceived_Stress_Score, Mental_Health_Index
• Academic scores: Academic_Performance_GPA
• Lifestyle status classification: Overall_Impact

🛠️ Technologies and Libraries


Technology	Purpose
Python	Programming language
Pandas	Data manipulation and structural analysis
NumPy	Scientific computing and handling structural anomalies
Matplotlib	Base charting and data visualization engine
Seaborn	Advanced statistical distribution plots and theme styling
Scikit-learn	Scalers, preprocessing encoders, pipelines, and machine learning models


🧹 Data Preprocessing

The following preprocessing steps are programmatically executed by the pipeline:
• Standardized all raw column headers by stripping out hanging trailing whitespaces.
• Evaluated and systematically dropped duplicated records from the dataset pool.
• Erased the high-cardinality student identifier column (Student_ID) to maintain generalized feature spaces.
• Purged trailing empty strings from categorical variables and cast object columns to standardized string representations.
• Re-mapped messy Boolean, string, and categorical variations inside Late_Night_Usage into numerical encoding spaces.
• Set programmatic boundary rules to filter out structural data noise, coercing variables into precise type declarations.
• Dropped incomplete entries that were missing critical tracking targets (Overall_Impact).

🔍 Exploratory Data Analysis (EDA)

Exploratory Data Analysis is performed under a clean statistical layout theme to identify core behavioral connections:
• Overall class distribution counting for the categorical Overall_Impact target types.
• Strategic calculation of the group-wise mean daily usage hours mapped against the final impact metrics.
• Descriptive aggregation of sleep duration hours grouped alongside the student lifecycle categories.
• Tracking stress trends and perceived tension variances against the final target classes.
• Computing contextual GPA means to identify intersections between media saturation and school performance.
• Generating cross-tabulations to map standard behavioral deviations against preferred online communication platforms.
• Building a linear relationship correlation matrix map across all localized numeric features.

📊 Data Visualization

The project script generates and saves a robust array of ten statistical charts directly into the environment folders:
• 01_impact_distribution.png — Distribution of Social Media Impact classes
• 02_daily_usage.png — Average Daily Social Media Usage Bar Chart
• 03_sleep_analysis.png — Sleep Duration grouped by Social Media Impact category
• 04_stress_analysis.png — Perceived Stress Score by Social Media Impact type
• 05_academic_performance.png — Academic Performance GPA differences across target levels
• 06_correlation_heatmap.png — Feature Correlation Heatmap Matrix
• 07_platform_impact.png — Normalized stacked distribution of Social Media Impact by Primary Platform
• 08_model_accuracy.png — Machine Learning Classifier Accuracy comparison bar chart
• 09_model_f1_score.png — Macro F1-Score evaluation metric comparison
• 10_confusion_matrix.png — Detailed Confusion Matrix heat array for the selected champion algorithm

⚙️ Feature Engineering

New metrics are engineered and structural pipeline chains are established to process target metrics safely:
• Estimated Total Usage: A newly engineered feature combining Daily_Usage_Hours and Weekend_Extra_Hours to capture cumulative exposure.
• Numeric Pipeline Processing: Automates the handling of missing numbers using a SimpleImputer configured with median substitution strategy before centering indices via standard normal scaling (StandardScaler).
• Categorical Processing Pipelines: Imputes missing strings using the most_frequent class and transforms multi-class nominal features into machine-readable numeric formats via full One-Hot Encoding (OneHotEncoder).
• Data Flow Separation: Combines divergent columns through a unified ColumnTransformer layout to avoid leakage during execution.

🤖 Machine Learning Models

Four distinct predictive classification estimators are built and optimized inside an architecture network:
1. Logistic Regression: Configured with robust class_weight='balanced' constraints over a 2000 maximum iteration capacity.
2. K-Nearest Neighbors (KNN): Calculated using standard Euclidean distance profiles with an evaluation window of \(k=5\).
3. Naive Bayes: Deployed using dense Gaussian distribution paths (GaussianNB).
4. Decision Tree Classifier: Hard-coded to evaluate splitting choices down to a maximum path length of 8 while incorporating balanced row weighting schemes.
The dataset is partitioned into training and validation sets using a stratified 75:25 train-test split over a fixed seed (random_state=42) to maintain class proportions.

📈 Model Evaluation

Estimator validation is tracked under high-precision conditions across standard validation sets:
• Performance matrices evaluate models using: Accuracy Score, Precision, Recall, Weighted F1, and Macro F1-Score.
• Algorithms are systematically ranked based on their Macro F1 performance to pick out the best-fit model architecture.
• Exports model rankings into a structured evaluation lookup sheet named model_comparison.csv.
• Generates a validation report matrix displaying true classifications side-by-side with predicted groups in best_model_predictions.csv.

📁 Project Structure

text
Social-Media-Impact-Student-Life/
│
├── Social_media_impact_on_life.csv
│
├── prog_file.py
│
└── README.md
Use code with caution.

🚀 How to Run the Project

Step 1: Download or copy your local asset repository workspace.
Step 2: Install the required operational ecosystem libraries:
bash
pip install numpy pandas matplotlib seaborn scikit-learn
Use code with caution.
Step 3: Place your working file dataset named Social_media_impact_on_life.csv inside the exact matching path script folder.
Step 4: Execute the primary Python analysis file:
bash
python prog_file.py
Use code with caution.
Step 5: Analyse the terminal logs, evaluation tables, and the ten stored trend visualizations.

💡 Key Outcomes

• Discover deep connections between high online activity and changes in sleep schedules or student stress markers.
• Uncover how platform preferences relate to distinct levels of lifestyle impact among students.
• Compare four different classification algorithms directly using Macro F1-Scores to choose the best-performing model.

📝 Conclusion

This project demonstrates the application of Data Science and Machine Learning pipelines to explore social media dependency trends across active student populations. By organizing preprocessing blocks, executing descriptive EDA charts, engineering interaction metrics, and comparing classifiers, the architecture accurately categorizes user dependency profiles into corresponding lifestyle impact brackets.
Four distinct machine learning algorithms are tested under multi-class categorization rules, allowing you to select a resilient prediction champion based on the highest achieved Macro F1-Score.
The resulting insights help educators, developers, and health professionals spot negative behavior trends early and design data-backed digital wellness strategies.

🔮 Future Scope

• Integrate advanced machine learning techniques like ensemble tree networks or hyperparameter grid optimization tuning.
• Connect dynamic Business Intelligence dashboards using tools like Power BI to track real-time behavioral insights.
• Build a lightweight web application to serve the predictive model as a user-facing self-assessment tool.

👨‍💻 Author

Name: Kunuthuru Balaji Reddy


Course: Computer Science and Engineering

Project Domain: Data Science and Machine Learning

Now that your documentation perfectly matches your social media impact code, would you like to:
• Write a brief summary explaining how to interpret the 06_correlation_heatmap.png file?
• Generate a template script to help deploy this model into a web framework like Streamlit for future use?
• Create a troubleshooting checklist to quickly handle any data loading or directory errors?

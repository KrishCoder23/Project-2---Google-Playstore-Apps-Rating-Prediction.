This project focuses on predicting the ratings of Android applications listed on the Google Play Store based on various app attributes. The objective is to uncover the key factors influencing app ratings and to develop a predictive model capable of estimating an app’s rating before launch.

Dataset Features:

App Name & Category – Type of application (e.g., Tools, Games, Business).

Rating – Target variable (1.0 to 5.0).

Reviews – Number of user reviews.

Size – App size in MB.

Installs – Total downloads.

Type – Free or Paid app.

Price – App cost.

Content Rating – Age restriction level.

Genres – Specific app genres.

Last Updated – App update date.

Current Version & Android Version – Compatibility and release info.

Workflow:

Data Cleaning – Addressed missing ratings, removed duplicates, standardized numerical fields (e.g., Installs, Price).

Feature Engineering – Encoded categorical variables, extracted numeric values (from Size/Installs), transformed textual data.

Exploratory Data Analysis (EDA) – Explored relationships between features and ratings using histograms, scatter plots, and correlation matrices.

Model Training – Implemented regression models such as Linear Regression, Decision Tree, Random Forest, and Gradient Boosting.

Model Evaluation – Assessed performance using MAE, MSE, and R² Score.

Technologies Used:

Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

Environment: Google Colab

Insights:

App ratings are strongly influenced by the number of installs, reviews, category, and app type.

Free apps with frequent updates and higher user engagement generally perform better.

Applications:

Helps developers optimize features before launch.

Assists marketers in targeting high-potential categories.

Provides investors and product teams with insights into rating trends.

Overall, this project demonstrates a complete machine learning pipeline—from raw data preprocessing to building and evaluating predictive models—delivering practical insights for app creators, marketers, and investors.

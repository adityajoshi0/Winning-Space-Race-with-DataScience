# Winning-Space-Race-with-DataScience
🚀 Project Title: Winning the Space Race with Data Science (SpaceX Landing Prediction):
This section should clearly state the project's purpose and its alignment with the IBM Data Science Professional Certificate.


🎯 Business ObjectiveProvide a concise, high-impact summary of the business problem and the value of your solution.
The primary objective of this project was to leverage historical SpaceX launch data to predict the success of the Falcon 9 first-stage landing. This prediction is crucial for a hypothetical competitor ("Space Y") to accurately forecast launch costs and create effective pricing strategies, as successful reuse significantly lowers the cost per launch.


🛠️ Tools and TechnologiesHighlight the key technologies and libraries used, which showcases your technical breadth (Python, SQL, ML libraries, and visualization tools).Languages and EnvironmentPythonSQL (for data querying/analysis within notebooks)Data Science LibrariesData Manipulation: Pandas, NumPyMachine Learning: Scikit-learn (for classification models and GridSearchCV)Web Operations: Requests (for API calls), Beautiful Soup (for Web Scraping)Visualization and Interactive ToolsFolium (for geographical mapping and launch site visualization)Plotly Dash (for creating the interactive launch data dashboard)


📊 Methodology and Analysis StepsBreak down the project into logical steps, matching the structure of your Jupyter Notebooks.

1 Data Acquisition and WranglingFetched historical launch data using the SpaceX REST API.Scraped additional data points (e.g., launch site coordinates, landing outcomes) from Wikipedia using Beautiful Soup for comprehensive feature engineering.Performed data cleaning, handling missing values, and created a final dataset with features like PayloadMass, Orbit, and LaunchSite.

2 Exploratory Data Analysis (EDA)Statistical EDA: Used Python and SQL to query the dataset and analyze correlations between variables (e.g., between FlightNumber and success rate).Geospatial EDA (Folium): Visualized launch sites on a map and calculated distances to potential recovery infrastructure (coastlines, railways).Interactive Visualization (Plotly Dash): Built a dashboard to explore launch outcomes based on filters like LaunchSite and PayloadMass.

3 Machine Learning PredictionFeature Engineering: Transformed categorical variables (e.g., Orbit, LaunchSite) into numerical format using one-hot encoding.Model Selection: Tested four classification algorithms: Logistic Regression, Support Vector Machine (SVM), Decision Tree, and K Nearest Neighbor (KNN).Hyperparameter Tuning: Optimized each model using the GridSearchCV method to find the best-performing parameters.Evaluation: Evaluated models using accuracy scores and the Confusion Matrix on the test dataset.4. Key Results and ConclusionConclude with your most significant finding, such as which variables were the strongest predictors (e.g., specific orbits like HEO, SSO have $\mathbf{100\%}$ success) and the accuracy of your best-performing model (e.g., Decision Tree achieved $\sim 83\%$ test accuracy).


🔗 Repository ContentsInclude a list of the main files and what they contain, which adds clarity for reviewers:Data Collection.ipynb: Notebook for API and Web Scraping.Data Wrangling.ipynb: Notebook for cleaning, one-hot encoding, and feature creation.EDA with visualizations.ipynb: Initial EDA using basic Python visualizations (Matplotlib/Seaborn).EDA with SQL.ipynb: Analysis using SQL queries on the dataset.Visual Analytics with Folium.ipynb: Code for the Folium geographical map.spacex-dash-app.py: Code for the Plotly Dash interactive dashboard.Machine Learning Prediction_Part_5.ipynb: Final notebook containing model training, GridSearchCV optimization, and evaluation.

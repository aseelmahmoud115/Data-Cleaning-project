
📊 Data Cleaning and Exploration of Baby Health Dataset
This project involves the exploration, cleaning, and visualization of a dataset containing baby health records. The goal is to prepare the data for future analysis or modeling by handling missing values, detecting anomalies, and understanding the relationships between variables through visualizations.

🔍 Features
Loads a CSV dataset interactively using Google Colab.
Performs initial data inspection (head, summary, data types).
Identifies and handles missing values:
Fills numerical columns with the median.
Fills categorical columns with the mode.
Detects and removes inconsistent or invalid entries (e.g., negative weights).
Visualizes data distributions with histograms.
Displays a correlation heatmap for numerical variables.

🛠️ Technologies Used
Python
Google Colab
Pandas
NumPy
Matplotlib
Seaborn

🧪 How to Run
Open the notebook in Google Colab.
Upload your babies.csv dataset when prompted.
Execute each cell in order to:
Load and explore the dataset.
Clean and preprocess the data.
Visualize distributions and correlations.

🗃️ Dataset
File: babies.csv (uploaded manually)
Contents: Various baby-related attributes (e.g., weight, health metrics)
Missing Data: Automatically filled based on data type
Cleaning Rules: Customizable logic for removing invalid entries

📈 Output
A cleaned and consistent version of the dataset, ready for analysis.
Histograms showing the distribution of numerical features.
A correlation heatmap to identify strong linear relationships between features.

# Product_Recommendation_System_For_Dropshippers

Overview This project demonstrates a complete machine learning pipeline for a binary classification task on a sales dataset. It includes data preprocessing, model training, evaluation, and visualization using a logistic regression model.

Table of Contents Prerequisites Installation Project Structure Usage Output Explanation License Prerequisites Before you begin, ensure you have met the following requirements:

Python 3.6 or later installed on your machine. Required Python libraries installed (see Installation section). Installation Clone the repository: git clone https://github.com/your-username/sales-data-classification.git cd sales-data-classification

Install the required Python libraries: pip install pandas scikit-learn matplotlib seaborn tkinter pillow

Project Structure: sales-data-classification/ │ ├── sales_dataset.csv ├── main.py ├── README.md └── requirements.txt

sales_dataset.csv: The dataset containing sales data. main.py: The main Python script for the project. README.md: The readme file you are currently reading. requirements.txt: A list of required Python libraries. Usage Ensure the sales dataset (sales_dataset.csv) is in the project directory.

Run the main.py script to execute the data preprocessing, model training, evaluation, and visualization: python main.py

Output After running the script, you will see the following output:

The confusion matrix printed in the console. A heatmap of the confusion matrix displayed in a window. Example confusion matrix output: Confusion Matrix: [[TN FP] [FN TP]]

Explanation Data Preprocessing The dataset is read from a CSV file into a Pandas DataFrame. The Order_Priority column is mapped from categorical values to numeric values for modeling purposes. Features and Target Variable Features (X): 'Sales', 'Order_Quantity', 'Profit', and 'Order_Priority'. Target (y): 'result'. Data Splitting The data is split into training (80%) and testing (20%) sets. Model Training A logistic regression model is trained using the training data. Evaluation The model makes predictions on the testing data. A confusion matrix is computed to evaluate the model's performance. Visualization A heatmap of the confusion matrix is created and displayed using Seaborn and Matplotlib.

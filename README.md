# **Customer Churn Prediction System**

## **Overview**
This project aims to predict customer churn in a subscription-based business. By analyzing customer data and behavior, the model identifies at-risk customers, allowing businesses to proactively implement retention strategies. This end-to-end project demonstrates the application of data science, machine learning, and deployment techniques to solve a real-world business problem.

---

## **Features**
- Predict whether a customer is likely to churn.
- Analyze the key factors driving customer churn using feature importance techniques.
- Interactive dashboard for making predictions on new data.
- Comprehensive visualizations for insights into customer behavior and trends.

---

## **Technologies Used**
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost  
- **Visualization Tools:** Plotly, Streamlit  
- **Model Deployment:** Flask / Streamlit  
- **Version Control:** Git, GitHub  
- **Data Source:** [Telco Customer Churn Dataset](https://www.kaggle.com/datasets)

---

## **Project Structure**
```plaintext
customer-churn-prediction/
├── data/                # Dataset files
├── notebooks/           # Jupyter notebooks for EDA and experiments
├── src/                 # Source code for preprocessing and model training
├── models/              # Trained machine learning models
├── app.py               # Dashboard or API code for deployment
├── requirements.txt     # List of dependencies
├── README.md            # Project documentation
└── .gitignore           # Files and folders to ignore in Git
```
## **Installation**

git clone https://github.com/<your-username>/customer-churn-prediction.git

cd customer-churn-prediction

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

pip install -r requirements.txt

## **Usage**
Data Exploration:

Run the notebooks/eda.ipynb file to explore the dataset and understand patterns.

Train the Model:

Execute the preprocessing and model training scripts:

python src/preprocessing.py

python src/model_training.py

Start the application to make predictions:

python app.py

Access the dashboard at http://127.0.0.1:5000/.

## **Results**
Model Accuracy: 78%

Key Features Driving Churn:

Contract type

Monthly charges

Tenure

Customer support interactions

## **Future Work**

-Enhance the model by incorporating more complex algorithms.

-Add more features (e.g., customer social media data, reviews).

-Scale the deployment using cloud services like AWS or Google Cloud.





Churn Prediction Model: Customer Retention AI

🚀 Overview
Welcome to the Churn Prediction Model project! This AI-driven application predicts whether a customer is likely to churn based on key features such as age, gender, contract type, and monthly charges. The model uses Logistic Regression, a well-established machine learning algorithm, to classify customers into two categories: Churn: Yes or Churn: No.
In this project, the model is trained using a dataset and then deployed through a simple and interactive Tkinter-based GUI. The user can input customer data, train the model, and get instant churn predictions.



⚙️ Key Features
Train Model: This button allows users to train the model. The system trains and evaluates the model over multiple rounds and presents detailed reports on accuracy and performance metrics.
Predict Churn: Users can input data (e.g., age, gender, contract type, and monthly charges) and get a prediction on whether a customer is likely to churn or not.
Performance Reports: After training, the model generates a detailed classification report showcasing precision, recall, and F1 score for each class.
Clear Output: Clears the text area for easier reading and better management of training results.



📊 Technologies Used
Python 3.x
Scikit-learn: For implementing the machine learning model and evaluation metrics.
Tkinter: For creating an intuitive graphical user interface (GUI).
Pandas: For data manipulation and processing.
Matplotlib: For data visualization (if included in the future).



🧠 How It Works
The model is trained on a sample dataset containing the following features:
Age: Age of the customer.
Gender: Gender of the customer (Male/Female).
Contract: Type of contract the customer is on (Month-to-month, One year, Two year).
MonthlyCharges: Monthly charges paid by the customer.
Using these features, the model is trained to predict whether a customer will churn or stay. The application allows you to input new customer details and get a prediction on their churn likelihood.



📝 Performance Metrics
After training, the model outputs various evaluation metrics:
Accuracy: The percentage of correct predictions.
Precision: The proportion of true positive predictions among all positive predictions.
Recall: The proportion of actual positive instances correctly identified by the model.
F1-score: The harmonic mean of precision and recall.



📈 Sample Scenario

Example 1:
Customer Input:
Age: 30
Gender: Female
Contract: Month-to-month
Monthly Charges: 80
Predicted Churn: No

The model predicts that this customer is less likely to churn based on their characteristics and contract type.


Example 2:
Customer Input:
Age: 50
Gender: Male
Contract: One year
Monthly Charges: 50
Predicted Churn: Yes


In this case, the model predicts a higher likelihood of churn for this customer, based on the patterns it has learned from the dataset.



💡 Future Enhancements
Data Visualization: Add graphs to visualize churn trends and model performance.
Model Improvement: Use other machine learning algorithms like Random Forest, Support Vector Machines, or Neural Networks for better accuracy.
Real-Time Data: Implement real-time data collection and churn prediction in a live environment.



🧑‍🤝‍🧑 Contributing
Feel free to contribute to this project! Open an issue for suggestions or improvements. Pull requests are always welcome.

# **ML Task - 3 : Customer Churn Prediction 📊**
**🤔Can we Predict if a custermer will leave the service before they leave it?**

My answer is YES😊, I am glad to share my project called  Customer Churn Prediction,a Machine Learning Project to help Business People in which this model is build to predict weather the customer will leave(churn) or continue in the service.
This project is done as a part of "GrowthLink Internship ML Assignment".

### **Objective of the Project:**
The objective is to predict whether a customer will discontinue a subscription-based service.
By using the historicall customer data, building a ML model to classify customers who are likely to churn and likely to stay based on the features in the data.

### **What is Inside:**
| Component           | Description                                         |
|---------------------|-----------------------------------------------------|
| ML_Customer_Churn_Prediction.ipynb   | Main Google Colab notebook with end-to-end code     |
| churn_Modelling.csv      | Input dataset used for training and testing         |
| README.md           | Project overview and instructions                   |

### **Steps to Run the code**
1. Open the Colab Notebook:
   👉 [Click here to run in Google Colab](https://colab.research.google.com/github/Bandi-Lavanya/ML-Assignment/blob/main/ML_Customer_Churn_Prediction.ipynb)
   
2. Upload the Churn_Modelling.csv data set:
   In left side of the colab there is a symbol to upolad the file(file-->upload file), through that upload Churn_Modelling.csv file
   
3. Run all cells:
   Simply click Runtime--> Run all or manually reun each cell one by one.

### **Tools and Techniques**
**📚 Libraries:** 

* pandas & numpy for data manipulation
* scikit-learn for model evaluation
* matplotlib for visualizations
* xgboost for building the prediction model

**🔄 Preprocessing:**

One-Hot Encoding & Label Encoding

**🤖 Models:**

XGBoost Classifier for advanced accuracy

**📊 Evaluation:**

Accuracy Score, Classification Report, Confusion Matrix

**💻 Feature Interpretation:**

plot_importance() from XGBoost with a custom-colored plot (e.g., pink)

### **End Result:**
1. High accuracy achieved because of XGBoost Classifier Algorithm.
2. Key Features Influencing Churn are:
   * EstimatedSalary
   * CreditScore
   * Balance
   * Age
   * Tenure
     
![Model Evaluation](https://github.com/Bandi-Lavanya/ML-Assignment/blob/main/images/Screenshot%20(228).png)

### **📊 Visualization**

Using plot_importance to get the features which are considered the most significant in determining whether a customer churns.
![Feature Importance](https://github.com/Bandi-Lavanya/ML-Assignment/blob/main/images/Screenshot%20(227).png)
### **Why this prediction matters?**

* It Reduces the Marketing Cost: By predcting the churns and getting what to do next it improve the business.
* For Better Customer Experience: Based on the predictions head of the business can try to improve customer satisfaction by addressing the customer needs.
* Increasing the Customer Lifetime Value: By reducing the churn, businesses can retain the customer longer.

### **Connect Me!**

Reach be out freely and friendly for questions or feedbacks:

📧 **Email:** [bandilavanya2004@gmail.com](mailto:bandilavanya2004@gmail.com)  

💻 **GitHub:** [github.com/Bandi-Lavanya](https://github.com/Bandi-Lavanya)

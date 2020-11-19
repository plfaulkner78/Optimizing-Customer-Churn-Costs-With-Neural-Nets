# Optimizing Customer Churn Costs With Neural Nets

  While most of my other projects involve interesting computer vision, natural language processing, or data viz, the business analytics degree in me forced me to tackle a cost optimization problem. Therefore, in this project I work with customer churn data from an Iranian telecoms company to build a prediction and optimization model.

  What makes this project different from other classification problems I’ve worked on is that the creators of this dataset included unique false negative and false positive costs for each customer in the dataset. It’s not clear how these costs are determined, but I took them at face value. These misclassification costs allowed me to build a predictive model that prioritizes cost optimization. 
The difference between a standard customer churn prediction model and a cost optimization model can be captured in the question the model asks itself. A regular churn classifier seeks to answer the question “Is this customer going to churn?” However, the optimization model seeks to answer a different question: “Should I flag the customer as churn?” The nuance here is that the former question is concerned with the truth of whether a customer will churn, while the latter question is concerned with the financial decision of whether it’s worth it for the business to behave as if the customer will churn.

  My code that prepares the data and builds the model is included as a Jupyter Notebook with ample comments throughout. Additionally, the churn dataset is included in this repo but it can also be downloaded directly from the link below. Finally, a trained model is included as an HDF5 file.
  
  Churn dataset: https://www.kaggle.com/royjafari/customer-churn
  
  Description of the features: https://archive.ics.uci.edu/ml/datasets/Iranian+Churn+Dataset

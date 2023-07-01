# CUSTOMER_CHURN_PREDICTION

## INTRODUCTION

![customer_image](https://github.com/eldhose-95/CUSTOMER_CHURN_PREDICTION/assets/83853757/85251093-eb7f-44c2-912f-3bdbeac0c7bd)

Customer churn is a major problem for businesses of all sizes. When customers churn, they take their business elsewhere, which can lead to lost revenue, increased costs, and a decline in customer satisfaction.

### There are many reasons why customers churn. Some of the most common reasons include:

Price: Customers may churn if they find a competitor offering a better price.

Service: Customers may churn if they are dissatisfied with the service they receive from a business.

Product: Customers may churn if they are not satisfied with the product they have purchased.

Businesses can use customer churn prediction to identify customers who are at risk of churning. By identifying these customers, businesses can take steps to prevent them from churning.

### Once businesses have identified customers who are at risk of churning, they can take steps to prevent them from churning. Some of the most common steps businesses can take include:

Offering discounts or promotions: Businesses can offer discounts or promotions to customers who are at risk of churning.

Personalizing the customer experience: Businesses can personalize the customer experience by providing customers with recommendations, special offers, and other information that is relevant to them.

Solving customer problems: Businesses can solve customer problems by quickly and efficiently addressing any issues that customers may have.

### In this project, we will build a machine learning model to predict customer churn. We will use a dataset of historical customer data to train our model. Once our model is trained, we will be able to use it to predict which customers are at risk of churning. We can then use this information to take steps to prevent customer churn.

### In this repository, we have performed the end to end Exploratory Data Analysis, and idenfitied the characteristics of the customers that are more likely to churn, and I have used them wisely to create a model, and lately, have deployed the model.

* ### For EDA, please refer to : customer_churn_analysis_EDA.ipynb
* ### For Model Building, please refer to: customer_churn_prediction_model_building.ipynb 
* ### For Model Deployment, please refer to churn_pred_app1.py

### Creating the flask API

```app = Flask("__name__", template_folder='temp')```

The loadPage method calls our home.html.

```@app.route("/")```

```def loadPage():```
   
```return render_template('home.html', query="")```
 
The predict method is our POST method, which is basically called when we pass all the inputs from our front end and click SUBMIT.

```@app.route("/", methods=['POST'])```

```def predict():```

The run() method of Flask class runs the application on the local development server.

```app.run()```

Yay, our model is ready, let’s test our bot. The above given Python script is executed from Python shell.

Go to Anaconda Prompt, and run the below query.

```python churn_pred_app1.py```

Below message in Python shell is seen, which indicates that our App is now hosted at http://127.0.0.1:5000/ or localhost:5000

* Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)

HERE'S HOW OUR FRONTEND LOOKS LIKE:

![app_run_scrn_sht](https://github.com/eldhose-95/CUSTOMER_CHURN_PREDICTION/assets/83853757/9e85e6ce-3784-4dee-9655-d3f4b61ef209)

This project will be a valuable learning experience for anyone interested in machine learning, data science, or customer churn prediction. By completing this project, you will gain experience with:

Data analysis

Machine learning

Customer churn prediction

I hope you enjoy this project!

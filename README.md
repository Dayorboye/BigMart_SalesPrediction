## 
# OUTLET SALES PREDICTIONS FOR BIG MART

Sales data were collected for 1559 products across 10 stores in different cities in 2013.

A detailed list of the specific attributes of each product and store is provided.

The aim of the project is to develop a predictive model that is able to predict the sales of<br>each product at a given timeframe at particular outlets.

A careful examination of the dataset led to the following models being selected for training:
    
     <li> LinearRegression Model</li>
     <li> RandomForestRegressor</li>
     <li> XGBRegressor</li>
     
     *** ***

### Data collection and methodology
* Data Collection From working directory

  First to carry out the analysis, all the necessary and relevant libraries were imported on the jupiter Notebook.
  these libraries includes:
  * numpy
  * pandas
  * seaborn
  * matplotlib
  * plotly.expres* plotly.graph_object
  * plotly.subplots
  * warnings
  
  ## Evaluation Metric

test.csv dataset will be used for prediction and model perfomance will be evaluated on the basic of predicted values, the following evalution technique are consider for the model evalution:
    
    Root Mean Square Error
    R squared value
    Mean Absolute Error
    Accuracy Score               

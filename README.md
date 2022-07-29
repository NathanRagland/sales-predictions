# Predicting Sales
## Creating graphs and models to predict sales for retailers 
**Author**: Nathan Ragland 
### Business problem:
The goal of this is to help the retailer understand the properties of products and outlets that play crucial roles in predicting sales.
### Data:
https://drive.google.com/file/d/1syH81TVrbBsdymLT_jl2JIf6IjPXtSQw/view
## Methods
- Dropping columns that were irrelevant to the target. Deleting duplicate values and filling in missing data to give better correlation between the features and the target. Build multiple tree models to get the best variation scores.
## Results
#### Sales by Store Type Bar Graph
![image](https://user-images.githubusercontent.com/107736327/181789155-2a2db76e-1d76-4966-aed8-15a2d6228a06.png)

> This bar graph displays which type of stores record the highest sales.
#### Product Sales Bar Graph
![image](https://user-images.githubusercontent.com/107736327/181798891-762fcc7a-fe8a-4ee1-baa7-4d9fe14b82fd.png)

> This bar graph displays each product type's sales numbers.
## Model

My final model is a Regression Tree Model. 

The metrics I used were Mean Absolute Error, Mean Squared Error, Root Mean Squared Error, and R-Squared Score.

The model produced an R-Sqaured Score of about 59%. I do not think this model would perform well in a real world situaion. I believe the dataset is not sufficient enough.

## Recommendations:

I would not recommend using this model. While it is a balanced model, there doesn't seem to be enough relevant data in the dataset.

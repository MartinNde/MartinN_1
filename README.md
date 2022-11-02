# MartinN_1

California Housing Prices

[### Project Data Science Predicting Housing Prices : Project overview](https://github.com/MartinNde/MartinN_1)


Predict the housing prices of California using Linear Regression Model. 
The dataset which was taken from Kraggle(https://www.kaggle.com/code/shibumohapatra/linear-regression-and-rmse). 
This is then save in MongoDB where it is retrieve for the analysis.
It is import to understand that the original dataset is not altered in MongoDB only the copy that was taken out is manipulated.
Meaning that is anything goes wrong with the dataset, the original version will still be in tact.


The process of collecting the dataset from MongoDB is represented in the screenshot below,
The dataset is in a CSV file. This is first imported and MongoClient is imported from pymongo. 

![image](https://user-images.githubusercontent.com/117248670/199480259-84510caf-e653-48f4-b5c1-7063581b8f9b.png)

Using the logon details generated by MongoDB, python is then connected to MongoDB to retrive the data which appear in pythong in the format shown below. This is done using the article and collection function and the print function as shown in the screenshot.

![image](https://user-images.githubusercontent.com/117248670/199491443-699169c5-a10d-4e32-b923-95d08f2f5b56.png)

## Linear Regression

For the linear regression process to begin, the necessary packages needs to be imported. All the relevant libraries and packages are then imported as follows:
![image](https://user-images.githubusercontent.com/117248670/199494041-90f6d02d-8587-4949-80a5-1dee56367fe5.png)

# Importing and viewing the head of the dataframe

The dataset is now impported into the model and viewed intothe dataframe. 
This is to obtain a perspective of the data and see if all the information in the data has been correctly included.

![image](https://user-images.githubusercontent.com/117248670/199495019-b4dd5b81-b8e7-4054-8ab8-c6f68ae5125b.png)

## viewing the information on the dataframe and also get the discription of the data.

This is done using the two short and simple functions of info and describe as shown below:
![image](https://user-images.githubusercontent.com/117248670/199496402-5cd319a9-df78-4001-90df-f9eeb583a655.png)

## Checking the data for null values.

Once that is completed the null values are then removed and the total amount of the data before the null value is then compared to the data after the null values have been removed. It should be small. False values total 20433 these are actuall values whereas cells without with null values total 207. These null values were included in one column, which when removed the number of columns were reduced to 9. 
![image](https://user-images.githubusercontent.com/117248670/199499561-9fc82624-86ed-4778-9b3a-8a30483db622.png)

## View the coloumns of the dataframe.
The columns are then viewed again to ensure and the values counted. The table is then recalled again to see how these coloumns fit in it. x and y values are then defined and called which gives the two tables. The train data and test data are then printed. 
![image](https://user-images.githubusercontent.com/117248670/199502823-d1f98085-5c6a-45ec-8b23-2b5c76de035d.png)

# Prediction
The scaler is obtaine and defined for the model to be trained and fit the linear regression model using x_train through which the value of the houses are then predicted.

![image](https://user-images.githubusercontent.com/117248670/199504919-6b76be5f-4f8e-4a9a-b089-948af6b8fda2.png)

## Testing the dataset of errors.
The dataset is then tested for errors. The error value is 0.00 meaning that there is no issue with the dataset. The fucntions used for testing the dataset is as follows:
![image](https://user-images.githubusercontent.com/117248670/199505895-234bb1a4-0254-46b4-b665-482b264e60e5.png)

##Visualisation of the data.
The data is then visualised using plotly.express and seaborn both imported as px and sns. This will enable the exploration of the data using chats.
![image](https://user-images.githubusercontent.com/117248670/199507837-3d9dd4c4-ddef-4326-ab67-bfadb15bc642.png)

##Establishing correlation in the dataset using a visual diagram.
![image](https://user-images.githubusercontent.com/117248670/199509374-3589a93a-4076-47a9-af88-aed131ca24f9.png)



![image](https://user-images.githubusercontent.com/117248670/199510595-43560c99-f21d-4952-a274-254c6a54ec89.png)

![image](https://user-images.githubusercontent.com/117248670/199511221-697d6d0f-89f0-45b2-bd89-76715333e155.png)

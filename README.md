<h1 align="center">DATA ANALYSIS AND SALES PREDICTION OF BIG MART</h1>
<h2>ABSTRACT</h2>
<p align="justify">In recent years, shopping malls and Big Marts manage and keep a record of their sales data for any and every unique item with the goal to estimate client demand in future periods. Every firm and organization is working on meeting customer needs while also improving their inventory management in the present era of achieving new heights of progress. In a data warehouse, these data stores hold a vast quantity of customer data and specific item information. More importantly, abnormalities and regular patterns are discovered through mining the data warehouse. The resulting data may be utilized to forecast future sales volume using various machine-learning algorithms. In this project, we provide a linear regression based predictive model to forecast sales for a firm like Big Mart. A detailed comparison of the model to others in terms of performance measures is also provided. With the use of numerous datasets gathered for Big Mart and the process used to create a predictive model, very accurate findings are produced, and these observations may be used to make decisions to increase sales.</p>
<h2>INTRODUCTION</h2>
<p align="justify">Day-by-day competition among different shopping malls as well as big marts is getting more serious only due to the rapid growth of global malls and online shopping. In order to draw in more consumers depending on the moment, every mall or market tries to give unique, limited-time deals. This way, the volume of sales for each item can be forecasted for inventory management of the organization, logistics, transport service, etc. The collecting of sales data for commodities or products together with their different dependent or independent aspects is a crucial step in today's contemporary world for helping to estimate future demand and inventory management. Large shopping centers like major malls and marts are examples of this. The dataset, which was created utilizing a range of dependent and independent variables, is made up of information on the attributes of the items and information acquired from customers and inventory management information maintained in a data warehouse. The data is then changed in order to generate accurate forecasts as well as to collect new and exciting results that shed new light on our comprehension of the task's data. In order to predict forthcoming sales, this might then be utilized in conjunction with machine learning techniques. In this project, we address the problem of anticipating big-mart sales or projecting an item based on the consumers' expected future demand in various big-mart stores across various locations and goods. For the prediction or forecasting of sales volume, several machine learning methods, such as linear regression analysis, random forest, etc., are applied. In any retail center, the ability to predict sales is crucial since strong sales are the lifeblood of every business. Always a better prediction is helpful, to develop as well as to enhance the strategies of business about the marketplace which is also helpful to improve the knowledge of marketplaces. A conventional sales prediction research may assist in carefully analyzing prior scenarios or conditions and the inference can then be used to client acquisition, money insufficiency and strengths before making a budget and marketing strategies for the following year. In other words, sales forecasting is based on the resources that were accessible in the past. In-depth knowledge of the past is required for  enhancing  and  improving  the  likelihood  of  marketplaces  irrespective  of  any circumstances,  especially the external circumstance, which allows for the preparation of the upcoming needs of the business.</p>
<p align="justify">Data Analysis:</p>
<p align="justify">Data visualization tools and technologies are crucial in the space of big data to analyze vast volumes of information. Data visualization is the depiction of data using conventional graphics like infographics, plots and even animations. These informational visual representations make complicated data relationships and data-driven insights simple to comprehend.</p>
<p align="justify">Machine Learning:</p>
<p align="justify">The amount of data accessible is growing daily, and this massive volume of unprocessed data must be carefully analyzed in order to provide outcomes that meet the current standards for being highly useful and flawlessly pure. Data is incredibly important in current aspects, therefore as technology advances, so will the analysis and interpretation of data to provide effective outcomes. Both supervised and unsupervised types of tasks are dealt with in machine learning, and typically, a classification-type issue serves as a source for knowledge acquisition. Machine Learning appears in many guises. Various machine learning algorithm includes:</p>
<dl>
  <dt>1.	Linear Regression</dt>
  <dd>Linear regression is a popular supervised machine learning algorithm used for predicting numerical values. It models the relationship between an independent variable (input feature) and a dependent variable (output or target variable) as a linear equation. The goal of linear regression is to find the best-fit line or hyperplane that minimizes the error between the predicted values and the actual values of the target variable.</dd>
  <dt>2.	Lasso Regression</dt>
  <dd>The term Lasso regression is an acronym for Least Absolute Shrinkage and Selection Operator. Lasso regression is a type of regularization. It is preferred over regression approaches for more precise prediction. This model makes advantage of shrinkage. Shrinkage is the process of shrinking data values towards a central point known as the mean.</dd>
</dl>
<h2>PROJECT DESCRIPTION</h2>
<h3>PROBLEM STATEMENT</h3>
<p align="justify">Sales forecasting is a quite common real-world challenge that every organization experiences at some point in its entire existence. If done correctly, it may have a substantial influence on the company's success and performance. Big Mart's data scientists gathered 2013 sales data for numerous items across stores in several cities. Certain characteristics of each product and shop have also been determined. The goal is to create a predictive model that predicts the sales of each product at a certain location.</p>
<h3>PROPOSED SYSTEM</h3>
<p align="justify">The project is about building a model to predict accurate results for the dataset of Big Mart sales. This undergoes several sequences of steps as mentioned in the methodology and in this work, we propose a model using the Linear Regression technique. Every step plays a vital role in building the proposed model. In our model, we have used the 2013 Big Mart dataset. After preprocessing and filling in missing values, we used an ensemble classifier using Linear Regression, Ridge Regression and Lasso regression. Both the R2 score and RSME are used as accuracy metrics for predicting sales in Big Mart.</p>
<h3>OBJECTIVES</h3>
<ul>
  <li>Converting data into an appropriate form using various preprocessing techniques for the implementation of Machine Learning algorithms.</li>
  <li>The objective of this project is to predict future sales from given data of the previous years using Machine Learning Techniques.</li>
  <li>To determine and conclude the best model which is more efficient and gives fast and accurate results.</li>
</ul>
<h2>DATASET DESCRIPTION</h2>
<p align="justify">The data which was required for the project is collected through a Kaggle Dataset. In the project, I have used the 2013 Sales data of Big Mart as the dataset. Big Mart’s data scientists collected sales data from their 10 stores situated in different locations with each store having different products. The dataset set contains certain attributes like:</p>
<table>
  <tr>
    <th>Variable</th>
    <th>Type</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>Item_Identifier</td>
    <td>Numeric</td>
    <td>Unique product ID.</td>
  </tr>
  <tr>
    <td>Item_Weight</td>
    <td>Numeric</td>
    <td>Weight of the product.</td>
  </tr>
  <tr>
    <td>Item_Fat_Content</td>
    <td>Categorical</td>
    <td>Indicates if the product is low fat or not.</td>
  </tr>
  <tr>
    <td>Item_Visibility</td>
    <td>Numeric</td>
    <td>The percentage of a store’s total display area dedicated to a specific product.</td>
  </tr>
  <tr>
    <td>Item_Type</td>
    <td>Categorical</td>
    <td>It specifies the category to which the product belongs.</td>
  </tr>
  <tr>
    <td>Item_MRP</td>
    <td>Numeric</td>
    <td>The product’s Maximum Retail Price (list price).</td>
  </tr>
  <tr>
    <td>Outlet_Identifier</td>
    <td>Numeric</td>
    <td>Unique Store ID.</td>
  </tr>
  <tr>
    <td>Outlet_Establishment_Year</td>
    <td>Numeric</td>
    <td>The year in which the store was established.</td>
  </tr>
  <tr>
    <td>Outlet_Size</td>
    <td>Categorical</td>
    <td>Specified the size of the store in terms of the amount of ground area it covers.</td>
  </tr>
  <tr>
    <td>Outlet_Location_Type</td>
    <td>Categorical</td>
    <td>The sort of the city in which the shop is situated.</td>
  </tr>
  <tr>
    <td>Outlet_Type</td>
    <td>Categorical</td>
    <td>Whether the shop is only a grocery store or a supermarket.</td>
  </tr>
  <tr>
    <td>Item_Outlet_Sales</td>
    <td>Numeric</td>
    <td>Sales figures for the product at the shop. This is the outcome variable that has to be forecasted</td>
  </tr>
</table>
<h2>METHODOLOGY</h2>

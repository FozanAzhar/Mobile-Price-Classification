# MOBILE PRICE CLASSIFICATION

This is a project where we create a classification model to predict the price range of
mobiles that a company owns based on certain specifications.
![alt text](https://s3b.cashify.in/blog/wp-content/uploads/2018/05/mobile-phone-evolution.jpg)

## CONTEXT
An entrepreneur has started his own mobile company. He wants to give a tough fight to big companies like Apple, Samsung etc.
He does not know how to estimate price of mobiles his company creates. In this
competitive mobile phone market, one cannot simply assume things. To solve this
problem, he collects sales data of mobile phones of various companies.
He wants to find out some relation between features of a mobile phone (e.g., RAM,
Internal Memory etc) and its selling price. But he is not so good at Machine Learning.
So, he needs your help to solve this problem.
In this problem you do not have to predict actual price but a price range indicating
how high the price is

## Dataset 
https://drive.google.com/file/d/1yYRflcXVzEJ_yaaEw0cJ2Peyz3d-YVYe/view?usp=sharing

## Details of features:
The columns are described as follows:<br>
Dataset as 21 features and 2000 entries. The meanings of the features are given
below.<br>
• <b>battery_power:</b>  Total energy a battery can store in one time measured in mAh<br>
• <b>blue:</b>   Has bluetooth or not<br>
• <b>clock_speed:</b>   speed at which microprocessor executes instructions<br>
• <b>dual_sim:</b>   Has dual sim support or not<br>
• <b>fc:</b>   Front Camera mega pixels<br>
• <b>four_g:</b>   Has 4G or not<br>
• <b>int_memory:</b>   Internal Memory in Gigabytes<br>
• <b>m_dep:</b>    Mobile Depth in cm<br>
• <b>mobile_wt:</b>   Weight of mobile phone<br>
• <b>n_cores:</b>   Number of cores of processor<br>
• <b>pc:</b>   Primary Camera mega pixels<br>
• <b>px_height:</b>   Pixel Resolution Height<br>
• <b>px_width:</b>   Pixel Resolution Width<br>
• <b>ram:</b>   Random Access Memory in Mega Bytes<br>
• <b>sc_h:</b>   Screen Height of mobile in cm<br>
• <b>sc_w:</b>   Screen Width of mobile in cm<br>
• <b>talk_time:</b>   longest time that a single battery charge will last when you are<br>
• <b>three_g:</b>   Has 3G or not<br>
• <b>touch_screen:</b>   Has touch screen or not<br>
• <b>wifi:</b>   Has wifi or not<br>
• <b>price_range:</b>   This is the target variable with value of 0(low cost), 1(medium cost),<br>
2(high cost) and 3(very high cost).

## Steps to consider:
<b>1)</b> Remove handle null values (if any).<br>
<b>2)</b> Split data into training and test data.<br>
<b>3)</b> Apply the following models on the training dataset and generate the predicted value for<br>
the test dataset<br>
<b>a)</b> <strong>Logistic Regression</strong><br>
<b>b)</b> <strong>KNN Classification</strong><br>
  <b>c)</b> <strong>SVM Classifier with linear and rbf kernel</strong><br>
  <b>4)</b> Predict the price range for test data<br>
  <b>5)</b> Compute Confusion matrix and classification report for each of these models.<br>
  <b>6)</b> Report the model with the best accuracy.<br>

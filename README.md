# ML-Project-Part-2

Part 1 
1.Distribution plots:

<img width="453" alt="Screen Shot 2022-05-08 at 11 02 50 PM" src="https://user-images.githubusercontent.com/57150270/167338608-1471d6c3-3a80-4807-9ce3-a3894758551a.png">

<img width="470" alt="Screen Shot 2022-05-08 at 11 03 03 PM" src="https://user-images.githubusercontent.com/57150270/167338629-76f5df4c-5f88-45a5-88d2-59de76f99753.png">

-In 96453 rows in this dataset, humidity (0.89) is the most frequent which means it has the highest probablity. The second plot shows the concave down trend and the maximum point is from 8 to 18°C

6. The values of column ‘Loud Cover’ are all 0 so it can be dropped. Since the data already have the column ‘Summary’, column ‘Daily Summary’ is not necessary as well as column ‘Formatted Date’ and ‘Apparent Temperature (C)’  . Column ‘Precip Tye’ and ‘Summary’ should be one hot encoded because their values are not ordinal (do not have rankings, orders). One hot encoded works well with nominal data. 

Part 3:
3.

<img width="500" alt="Screen Shot 2022-05-08 at 11 14 28 PM" src="https://user-images.githubusercontent.com/57150270/167339577-e1068080-0651-4ffa-9545-dfd8651e93f7.png">

This plot shows the relationship between accuracy score and percent of training data. The accuracy score tends to get higher when the percentage of training data increases.
It reaches the highest accuracy score when the percentage of training data is 40%.

Residual Plot
<img width="563" alt="Screen Shot 2022-05-08 at 11 19 16 PM" src="https://user-images.githubusercontent.com/57150270/167339968-bf0ec005-b494-4dec-98f0-c21cf5f2ac44.png">
The plot indicates that the points are randomly dispersed around the horizontal axis which means that it supports the linear model. From the histogram on the right side of the plot, the error is distributed around zero which shows that the linear model performs well. 

Linear Regression
<img width="459" alt="Screen Shot 2022-05-08 at 11 17 32 PM" src="https://user-images.githubusercontent.com/57150270/167339808-59076fb7-3477-436c-8411-86e342905f32.png">

SGD Regression
<img width="484" alt="Screen Shot 2022-05-08 at 11 21 44 PM" src="https://user-images.githubusercontent.com/57150270/167340163-de740551-c25d-4269-a6ce-4e6b3c1958bc.png">

Between these two models, linear regression performs better with this dataset. Based on the coefficient of determination, the accuracy score of linear regression model is 61% while the score of SGD regression is negative. It shows that SGD repression model does not follow the trend of the data and does not fit well with the dataset.


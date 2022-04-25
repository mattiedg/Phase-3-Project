# Phase 3 Project
--------------------------------------------------------------------------------------------------------------------------------
## Churn Likelihood in Customer Data
--------------------------------------------------------------------------------------------------------------------------------
![Syriatel_logo](https://user-images.githubusercontent.com/100098968/165168740-4b73432b-ab55-446b-a27b-65df4c0ae244.jpg)

## Business Probelem

### The goal of our data analysis here will be to ascertain customers of SyriaTel that are the most likely to 'churn'.  To do this we will take a look at data for customers that includes information such as how many calls they have made, how long they have held an account with the company, as well as numerous fields related to the number of calls made per customer per day. We will analyze the relationship between these fields and whether or not the customer left the company with the aim of being able to target customers who are at risk of churn to attempt to keep their business. 

--------------------------------------------------------------------------------------------------------------------------------

## Churn

![0*dzmm3qresODlScte](https://user-images.githubusercontent.com/100098968/165170013-2da1560d-4ee5-420b-97dc-3b18e8413251.jpeg)

### To begin we should take a closer look at what exactly customer churn means. The churn rate, also known as the rate of attrition or customer churn, is the rate at which customers stop doing business with an entity. Churn can further be classified into two subsections. One of these is customers who no longer require the services of the company becuase they are moving, deceased, or any other cause that is not variable to personal carrier preference. The second, and the churn we shall primarily be concerned with here, are customer who have the option to retain the services of a company but instead choose to cancel their contract and move to a competitor in the same industry.  With the second type of churn there is the option that the customer can be persuaded or incentivized to stay with the company. 

--------------------------------------------------------------------------------------------------------------------------------

## Looking into the Data

<img width="659" alt="Screen Shot 2022-04-25 at 4 43 17 PM" src="https://user-images.githubusercontent.com/100098968/165171547-e2a241a4-2a03-4ca0-9cea-344d75d471f1.png">

### To begin analyzing the data we should first take a look into how churn is represented in the data set. In the above graph we can see a visualization of the churn data. To the left of the .5 margin here are customers who have not churned, or who currently have an account with SyriaTel, conversely to the right of the .5 are those who have churned and terminated their contracts with the company. From this graph we can see that we have much more data on customers who are still with the company than those who have churned. 

<img width="476" alt="Screen Shot 2022-04-22 at 12 25 20 PM" src="https://user-images.githubusercontent.com/100098968/165172104-6814570a-bfce-4b4e-bd99-71904559fb3f.png">

### Next we can analyze some of the other data fields against the churn data. In the above graph we can see a histrogram representing the account length of customers and the number of customers who have held the account for that long. As well the shading on the graph represents the distribution of customers who have or have not churned. Those who have churned represented in orange and those who have not shown in blue. From this we can see that while there are many more customer at nearly each account length that are still with the company this can be attributed to the fact that we simply have more data from those customers. Instead we should focus here on the fact that among those who have churned and those who have not there is a fairly similar distibution. This means that there are not more new customers leaving the company than tenured customers and vice versa. 

<img width="349" alt="Screen Shot 2022-04-22 at 10 05 11 AM" src="https://user-images.githubusercontent.com/100098968/165172678-851b10dc-b406-44d2-945c-3f714037d4a3.png">

### Then we can turn to look at customers who have made calls to the SyraiaTel customer service department and see if they have any relation to the churn data. The above graph here is representing the numbe of customers who have made calls to the customer service department as well as the high and low ranges. From this we can see that customers who have left SyriaTel are more likely to have called into customer service, as well they are more likely to have called in multiple times. 

--------------------------------------------------------------------------------------------------------------------------------

### Modelling the data

##



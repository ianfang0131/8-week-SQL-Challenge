# Case Study #1: Danny's Diner
![dinner](https://github.com/ianfang0131/8-week-SQL-Challenge/assets/124013330/61a9174d-e3f5-4219-b9bf-9b7e2d4cdebe)


## Table of Contents

- [Introduction](#introduction)
- [Entity Relationship Diagram](#entity-relationship-diagram)
***
## Introduction
Danny seriously loves Japanese food so in the beginning of 2021, he decides to embark upon a risky venture and opens up a cute little restaurant that sells his 3 favourite foods: sushi, curry and ramen.

***
## Entity Relationship Diagram
![Entity Relations Diagram](https://github.com/ianfang0131/8-week-SQL-Challenge/assets/124013330/eef59e02-f2b6-4f9c-aae6-beb98ac5748e)
***
## Question and answer
  **1.What is the total amount each customer spent at the restaurant?**
  ````sql



````
#### solutions:
- Use **JOIN** to connect two tables
- 
***
 **2.How many days has each customer visited the restaurant?**
````sql


````
#### solutions:
- Use
- 
***
 **3.What was the first item from the menu purchased by each customer?**
````sql



````
#### solutions:
- Use
- 
***
**4.What is the most purchased item on the menu and how many times was it purchased by all customers?**
````sql


````
#### solutions:
- Use
- 
***
**5.Which item was the most popular for each customer?**
````sql

````
#### solutions:
- Use
- 
***
**6.Which item was purchased first by the customer after they became a member?**
````sql

````
#### solutions:
- Use
- 
***
**7.Which item was purchased just before the customer became a member?**
````sql

````
#### slutions:
- Use
- 
***
**8.What is the total items and amount spent for each member before they became a member?**
````sql

````
#### solution:
- Use
- 
***
**9.If each $1 spent equates to 10 points and sushi has a 2x points multiplier - how many points would each customer have?**
````sql
````
#### solution:
- Use
- 
***
**10.In the first week after a customer joins the program (including their join date) they earn 2x points on all items, not just sushi - how many points do customer A and B have at the end of January?**
````sql

````
#### solution:
- Use
- 
***

## BONUS QUESTIONS

**Join All The Things**
**Recreate the following table output using the available data**
**customer_id, order_date, product_name, price, member**

````sql


````
#### Solution:


***
**Rank All The Things**
**Danny also requires further information about the ranking of customer products, but he purposely does not need the ranking for non-member purchases so he expects null ranking values for the records when customers are not yet part of the loyalty program.**

````sql




````

#### Solution:




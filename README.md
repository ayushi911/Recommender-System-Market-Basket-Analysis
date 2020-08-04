# Market Basket Analysis on Purchase data <hr>

![alt text](https://github.com/ayushi911/Project-Market-Basket-Analysis/blob/master/Plots%26imgs/MBA_1.png)

## Introduction
A market basket analysis or recommendation engine is what is behind all these advices we get when shopping
online or when we receive targeted advertising. The underlying engine collects information about people’s habits
and then provides the most suitable advices as recommendations to increase the sales.\
<br>**For example:** Let in a store, if people buy pasta and wine, they are usually also interested in pasta sauces. So, the next
time you go to the supermarket and buy pasta and wine, be ready to get a recommendation for some pasta sauce !
So basically we have,<br><br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **IF{pasta, wine, garlic} THEN{pasta-sauce}** <br><br>
The first part of the rule is called “antecedent”, the second part is called “consequent”. A few measures, such as
support, confidence, and lift, define how reliable each rule is. We will be dealing with some relevant algorithms for this purpose while we proceed.

<!--![alt text](https://github.com/ayushi911/Project-Market-Basket-Analysis/blob/master/Plots%26imgs/MBA_2.png)-->

### Objectives: 
- The main objective of my project is to recommend items to purchase to the customer visiting the shops/webshops.
- The following image clearly shows types of recommender systems that can be implemented.
![alt text](https://miro.medium.com/max/1000/1*rCK9VjrPgpHUvSNYw7qcuQ@2x.png)

### About the dataset:
- The dataset we will be using is obtained from the dataset resources of Retail Rocket, an organizations which helps the webshops to have amazing recommendation systems to increase their sellings.
- The link to the dataset is: [DataSet](https://drive.google.com/file/d/1ul5Sm02wuzuK6DV1_jYSDJv5f-vbMhoo/view?usp=sharing) 

## Working Methodology:
- So basically recommendations is
![alt text](https://github.com/ayushi911/Project-Market-Basket-Analysis/blob/master/Plots%26imgs/RS.jpeg)
- The Rocket Retail dataset, that I am using has more than 20 million purchase history data with 4 CSV files namely:
  - *Category_tree.csv*
  - *events.csv*
  - *item_properties_part1.csv*
  - *item_properties_part2.csv*
- The events that were categoried in the working were *VIEWED* , *ADDTOCART* and *TRANSACTIONED*.
- One can also look upto the graphical format in which the data is represented in the coding file.
- On the basis of grouping the data together into relevent pieces of information the final output we have is when we give a item_id, we obtain a recommended item list.
- For the detailed analysis, one can look up to the code of the project in joining files.
- Moving to the model of the project, taking 70:30 ratio for train and test respectively, we obtain the following results:
![alt text](https://github.com/ayushi911/Project-Market-Basket-Analysis/blob/master/Plots%26imgs/model.png)

#### References:
- For the most basic knowlegde of Recommender systems one can look upto this adjacent [LINK](https://towardsdatascience.com/introduction-to-recommender-systems-6c66cf15ada)

# Market Basket Analysis on Purchase data <hr>
## Introduction
A market basket analysis or recommendation engine is what is behind all these advices we get when shopping
online or when we receive targeted advertising. The underlying engine collects information about people’s habits
and then provides the most suitable advices as recommendations to increase the sales.\
**For example:** Let in a store, if people buy pasta and wine, they are usually also interested in pasta sauces. So, the next
time you go to the supermarket and buy pasta and wine, be ready to get a recommendation for some pasta sauce !
So basically we have,<br> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **IF{pasta, wine, garlic} THEN{pasta-sauce}** <br>
The first part of the rule is called “antecedent”, the second part is called “consequent”. A few measures, such as
support, confidence, and lift, define how reliable each rule is. We will be dealing with some relevant algorithms for this purpose while we proceed. 

### Objectives: 
- Analyze the anonymized data of 3 million grocery orders from more than 200,000 Instacart users open sourced by Instacart
- Find out hidden association between products for better cross-selling and upselling
- Perform customer segmentation for targeted marketing and anticipate customer behavior
- *Basically the above three points need to be revised.* **And more primarily we will work on returning a recommendation list**

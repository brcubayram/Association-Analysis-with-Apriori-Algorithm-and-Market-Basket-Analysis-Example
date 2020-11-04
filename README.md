# Association-Analysis-with-Apriori-Algorithm-and-Market-Basket-Analysis-Example

## What is Association Analysis?
Data mining methods that enable future studies by analyzing historical data and determining the coexistence in these data are called Association Analysis. These methods reveal the rules of association with certain probabilities. We can give examples of Netflix series & movie recommendations, Youtube video suggestions, Yemeksepeti additional product recommendations to fit our minds perfectly.

The most common use of association rules is market basket analysis. With this analysis, the purchasing behaviors of the customers are analyzed by finding the rates of getting together between the shopping habits and the products. For example, with market basket analysis, "If a customer buys milk, which products will he buy with the milk?" By searching for answers to such questions, market managers can redesign the shelves of milk and related products and increase their sales by organizing discount campaigns.

Some algorithms used for Association Rules Analysis: Apriori, Carma, Sequence, GRI, Eclat, FP-Growth and others. We should say that among these, the most commonly used Apriori Algorithm. In the rest of this article, we will give information about the Apriori Algorithm and make an example.

## Apriori Algorithm
The Apriori Algorithm was developed in 1994 by Agrawal and Srikant. The name of the algorithm is "Apriori" meaning prior because it uses the prior knowledge of common sets of elements. This algorithm has an iterative (repetitive) nature on the basis of it and is used to discover frequently occurring sets of items in databases containing motion information.

Let's take a look at some terms we need to know.
 1- Support Value
 It is the probability of seeing a product / relationship in all events.
 N: Total number of purchases
 
 Support (X -> Y) = Frequency(X, Y) / N
 
 2- Confidence Value
 It is the probability that a customer who buys product X will buy product Y.
 
 Confidence (X -> Y) = Frequency (X, Y) / Frequency (X)
 
 3- Lift
 It shows how many times the occurrence of the X event increases the probability of the Y event happening.
 
 Lift = Support (X, Y) / (Support (X) x Support (Y))
 
 After giving information about the subject, you can examine a simple example in the attached Excel file and the Python example in the attached notebook.

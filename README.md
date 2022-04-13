### DecisionTree_VALE3_returns

This project serves as a beginning for my studies in Machine Learning. 

As I read various introductory texts about ML, one of the most quoted models initially was Decision Trees, so I figured out I would try to apply it to financial and quantitative problems. As independent variables were used returns from: CC Fut BVSP, CC Fut USD/BRL, Iron Ore 62% Fe CFR and CSI 1000 (China); - CC meaning current contract - and as the target or dependent variable was used VALE3 (former "Vale do Rio Doce") returns. All data is daily, and the period of analysis is:  26/09/2011 - 08/04/2022.

*Crucial point: as we try to predict today's VALE3 return, we use yesterday's data from all the independent variables.*

The code has two main parts: 

1) Data gathering ("investing.com") and cleaning, as well as transforming continuous variables (assets returns) into discrete ones (by defining intervals and a correspondent index number to each of them); 


2) Actually creating the model, training it, making predictions, and measuring it's general accuracy. 

One important thing to point out is the inefficiency of the final results. Trying to predict returns is something extremely difficult, and it wasn't going to be a model as simple as Decision Trees that would be able to have a relevant accuracy. In spite of that, this project serves as a foundation/starting point for improvements in utilizing Machine Learning algorithms for financial analysis.

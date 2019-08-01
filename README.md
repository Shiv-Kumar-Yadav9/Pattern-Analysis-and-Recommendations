# Pattern-Analysis-and-Recommendations
Analyzing the cutoff in every sector for achieving the goal that are set by the user for themselves.

The Finding_Trend_and_Analyzing_cutoff.ipynb file shows how the logic of the idea flows.


## REQUIREMENTS:
  1) Python 3.5 or above.
  2) Jupyter Notebook.
  3) Django Framework.
  4) Brackets.


## STEPS OF FINDING TREND
  1) The company of the mobile phone is selected by the user.
  2) The program uses the changes in price value of the mobiles previously manufactured by the company.
  3) The time series of the price is then splitted in Trend and Seasonality components.
  4) The trend of the price of previous mobile phones is used as a baseline trend that the new products will also follow.
 
## Concept :
  The concept on which the project is based is that the sales that occur all over world always occur at the same point in the year. Some common sales are like the 'Black Friday', 'Christmas Sale', 'New Year Sale', etc...
  
  
  The customer can thus tap these opportunities and achieve his goal before time. In case the price keeps on decreasing then the customer can just wait till the point his savings can ammount to money he need for the goal.
  
## STEPS OF RECOMMENDING CUTOFFS
  1) The total of the users spending in each sector is divided by total spendings in order to get ratio of the user's spending.
  2) The ratio of user's spending is then judicially used to guide the user to focus on reducing his expenditure in certain areas that will help him achieve his goal.
  3) The user has the option to increase and decrease the target month for goal. Thus he can analyze the pressure he will have on his expensis if he plans to buy it after particular months.
  
## Concept :
  The ability to tweek with the target month will give better knowledge of the areas in which the person has to reduce his spendings in order to meet the goals.
  
  
  Thus it gives the user the ability to change the pressure on spendings based on the urgency and importance of the device.
  

# DEMO SLIDES :

The home page of the software allows the user to choose the brand name, the targetted month and the current price of the mobile phone.
The images shows the same:

### FIRST PAGE
![page1][page1]


The second page shows the distribution of cutoff from each sector and the amount in Rupees that the person should reduce in entire target time from each sector so that his savings amount equal to the needed amount to purchase the product.


### SECOND PAGE - Part 1
![page2][page2]

### SECOND PAGE - Part 2
![page3][page3]

<!--Images-->
[page1]:misc/images/page1.png "page1"
[page2]:misc/images/page2.png "page2"
[page3]:misc/images/page3.png "page3"

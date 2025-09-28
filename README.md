# Car-Coupons
Customer coupon acceptance rates

**Assignment notebook:** [https://github.com/ryanmw99/Car-Coupons/blob/main/prompt.ipynb ](https://github.com/ryanmw99/Car-Coupons/blob/main/prompt.ipynb)

## What is the problem?
This project aims to understand differences between customers who accept the diriving coupon and those who do not. 
It uses explorartory data analysis, statistical summarization, and data visilualiztion to discern some findings. 

## What is the data?
This data is from the UCI Machine Learning Repository and was collected via a survey on Amazon Mechinical Turk. The survey describes different driving scenarios, including the current time, weather, and passenger, and then asks people whether they will accept the coupon if they are the driver. There are three possible answers people can choose from:

- **"Right away"**
- **"Later, before the coupon expires"**
- **"No, I do not want the coupon"**


## What are the findings?
The findings show that the older and the more people that the people travel with the more likely they are to be paying customers that accept coupons. Additionally, those with income below 50k accept coupons at the highest rates. Meanwhile, those under 30 who visit establishments regularly do not accept coupons and their business can be relied upon. 
## What do I recommend?
That being said, if the coupons are marketed to the two extremes, then more will be accepted.
_**This shows that regular bar-goers are already invested and a good target audience are groups and low incomes.**_

## Independent Investigations

### Investigating Expensive Restuarants
**Hypothesis: _Could it be that redemption rate is affected by the type of restuarant and value of coupon they are going to?_**
If the restuarant is more expensive then the customer is less likely to accept a coupon, because they are already willing to spend more money. The data supports this, but not to the observed level you would expect. The rate is similar but still less than cheap restuarants. 


**Observations when comparing home versus other as a destination**
If the driver is heading home versus another destination then the acceptance rate is much higher. This indicates that when people are going out they have what they need with them and plan on using the coupons on their return. 


**Observations when comparing having a friend, partner, or something other than that in the car**
If there is a friend or partner in the car the acceptance rate is higher than any other scenario. This indicates that groups of two or more share the coupons more regularly and accept them more than people who are traveling alone. However, more people travel alone than with someone else so while they accept the coupon at the lowest rate they use the highest count of coupons.  


**Observations when the of the overall trends in their acceptances**
If the overall trends are observed then they will be mostly negative indicating less than half the time people at expensive restuarants will accept coupons. The expections are if they are restuarants closer to their home meaning they are regulars. They are least likely to accept if they are traveling far with a direct negative correlation. 


## Actionable Learnings & Recommendations

**Patterns to exploit**
While people who go out alone use coupons at a lower rate they are the largest population group and use the most coupons, so they are a steady baseline to rely upon. One pattern to exploit is anyone traveling with passengers as they use coupons at a higher rate at cheap restuarants, expensive ones, and bars especially. Also, in the bars category, anyone under 30 uses coupons at the highest rate, so they should be marketed to. 

**Missed opportunities**
The coupons were accepted much more regularly by friends and passengers and people in certain occupations. If other occupations could be marketed to the same as Farming Fishing and Forestry and groups, which accept twice as much, then other occupations would accept more regularly. People also used coupons alarmingly more on the way home than away from there, which means there is an untapped market for half of their travel. 

**Overal Product Recommendations**
The most effective strategy would be to continue to market to patrons who are alone and under 30 as well as those who regularly go out with passengers within 15-25 minutes of their home. In addition, since certain occupations accept twice as many coupons the product should be marketed to other occupations through their companies, so that those in the occupations use coupons while they go out in the untapped market away from home. 

Checkout the ```prompt.ipynb notebook``` for all the details!!!


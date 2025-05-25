# <p align=center> Assignment 5.1: Will the Customer Accept the Coupon?

## Quick links
* Link to the dataset used in this analysis can be found <a href="https://github.com/Cxpher/nutcracker/blob/main/data/coupons.csv">here</a>.
* Link to Jupiter Notebook containing code and visualization for the performed analysis can be found <a href="https://github.com/Cxpher/nutcracker/blob/main/prompt.ipynb">here</a>.
* Link to folder containing all saved visualized plots depicted in the Jupiter Notebook can be found <a href="https://github.com/Cxpher/nutcracker/tree/main/plotted_images">here</a>.

## Context
Imagine driving through town and a coupon is delivered to your cell phone for a restaurant near where you are driving. Would you accept that coupon and take a short detour to the restaurant? Would you accept the coupon but use it on a subsequent trip? Would you ignore the coupon entirely? What if the coupon was for a bar instead of a restaurant? What about a coffee house? Would you accept a bar coupon with a minor passenger in the car? What about if it was just you and your partner in the car? Would weather impact the rate of acceptance? What about the time of day?

## Business goal
What are the factors that determine whether a driver accepts the coupon once it is delivered to them? How would you determine whether a driver is likely to accept a coupon? 
<br/><br/>
**Determining these factors would allow us to use more target approaches to increase coupon acceptance rate for our establishment partners.**

## Table of findings - Concluding hypothesis

|No. | Findings | Remarks |
|:--- |:---	  |:---      |
|1.  | As the most popular coupons were the 'Coffee House' and the 'Restaurant<20' coupons respectively, prices charged by these establishments likely had a part to play. The typically more expensive establishments such as 'Bar' and 'Restaurant(20-50)' had far lesser accepted coupons comparatively. |      |																							                                            
|2.  | Temperature of the weather had a significant effect on the coupons being accepted in general. Drivers were more likely to accept coupons during normal weather of 80 degrees fahrenheit as opposed to colder weather of 30 or 55 degrees fahrenheit. |      |
|3.  | Among those who accepted bar coupons, drivers were much more likely to accept bar coupons if they were 25 or older versus if they were younger than 25. |      |
|4.  | Among those who accepted bar coupons though, drivers were more likely to accept bar coupons if they were younger than 30 vs if they were older than 30. The acceptance rate shifted down quite a bit between the two groups (compared to the result for hypothesis #3) and there was a higher number of drivers in the amended younger group that accepted the bar coupon vs the amended older group. This shows that most of those who accepted the bar coupons were between age 25 to 30. |      |
|5.  | Among those who accepted bar coupons, drivers were much more likely to accept bar coupons if they had no kids with them. Only a small amount of them accepted bar coupons while having kids with them as passengers. |      |
|6.  | In general, drivers were much more likely to accept bar coupons if they went to bars 1 to 3 times in a month. |      |
|7.  | Finding #6 also applies for the most popular accepted coupon type, 'Coffee House', and is likely generally applicable across all coupons. |      |
|8.  | 'Price being a factor' in my independent investigation, while looking at most popular accepted category of coupons ('Coffee House'), there wasn't much of a difference in rate of acceptance between lower and higher income groups. While price was a factor for selection as indicated in hypothesis #1, income wasn't the key show stopper for the higher income group when it came to going to more expensive establishments. Everyone seems to love a good deal on a cost effective meal to begin with, regardless of income. |      |
|9.  | 'Direction towards destination (same or opposite)' being a factor in my independent investigation, while looking at most popular accepted category of coupons ('Coffee House'), it was clear that most drivers were not willing to take a detour when their destination was home or work. Similar numbers applied to acceptance rates when their direction was the same towards home or work. Majority of the accepted coupons were accepted by drivers who had no urgent place to go to and were willing to take a detour as needed to use the coupon. |      |

## Recommendations to establishment partners
1. Ensure coupons are sent to drivers during seasons of warmer weather (approx. 80 degrees fahrenheit).
2. Check to ensure that a driver has not been to an establishment (accepted and used vouchers could be one way) more than 3 times within the month before sending him or her a coupon.
3. Target specific age group of between 25 to 30 years old for bar coupons. Additionally, it'll be good to ensure that these drivers are not married, which will reduce the likelihood of them being with kids as passengers.
4. It will be good to target drivers during weekends instead of weekdays as this would mean that they will likely not be on the way to home or work and may not have any urgent place to go, thus increasing the likelihood of them accepting coupons.
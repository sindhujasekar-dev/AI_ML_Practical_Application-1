# AI_ML_Practical_Application-1
This is a practical application assignment that focuses on using data analysis skills, in an effort to seek answer to the question based on survey results, “Will a driving customer accept the coupon if offered for visiting a restaurant/bar/coffee_shop on their way to destination?”.

Will the Customer Accept the Coupon?

**Context**

Imagine driving through town and a coupon is delivered to your cell phone for a restaurant near where you are driving. Would you accept that coupon and take a short detour to the restaurant? Would you accept the coupon but use it on a subsequent trip? Would you ignore the coupon entirely? What if the coupon was for a bar instead of a restaurant? What about a coffee house? Would you accept a bar coupon with a minor passenger in the car? What about if it was just you and your partner in the car? Would weather impact the rate of acceptance? What about the time of day?

Obviously, proximity to the business is a factor on whether the coupon is delivered to the driver or not, but what are the factors that determine whether a driver accepts the coupon once it is delivered to them? How would you determine whether a driver is likely to accept a coupon?

**Overview**

The goal of this project is to use what you know about visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not.

**Data**

This data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. Answers that the user will drive there ‘right away’ or ‘later before the coupon expires’ are labeled as ‘Y = 1’ and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’.  There are five different types of coupons -- less expensive restaurants (under \$20), coffee houses, carry out & take away, bar, and more expensive restaurants (\$20 - $50).


General Findings:
General findings:

A total '13370' null values, spread across 6 columns and of which 'car' column has the most number of null values.
car 12576

Following are the remaining columns that had minimal null values that can be filled with according mode values.
Bar 107 CoffeeHouse 217 CarryAway 151 RestaurantLessThan20 130 Restaurant20To50 189

Bar Coupon related findings:

The bar coupon acceptance overall was 41% and non acceptance stood at 59%.

The 'more frequent visitors' to bar have accepted the coupons to the most (~76%) compared to the 'less frequent visitors' who have showed only less interest in coupon acceptance (~37%).

The 'frequent elderly visitors' to bar have accepted the coupons to the most (69%) compared to 'less frequent young visitors' who have showed only less interest (33%).

The 'frequent elderly visitors without farming/fishing/forestry job' to bar have accepted the coupons to the most (70%) compared to 'less frequent young visitors with farming/fishing/forestry job' who have showed only less interest (30%).

The 'frequent younger visitors' to bar have accepted the coupons to the most (39%) compared to 'frequent visitors that are elder and widowed' who have slightly less interest (37%) or 'frequent visitors to cheap restaurants with low income' who have even less interest (24%).

In general, those drivers, who has the habit of going to bar more frequently are taking advantage of the coupon and acceoting the same more compared to anyone else.

Drivers who are within low income or use cheap restaurants does not much care about the bar coupons and that was evident from the outcomes.

Coffee Coupon related findings:

Coffee coupons were accepted comparatively more by the passanger with friends group whereas comparatively less when travelling alone.

Income does not influence much when it comes to coffee coupon acceptance and it mostly shows around 50% acceptance on all income groups.

Gender does not influence much either when it comes to coffee coupon acceptance and it mostly shows around 50% acceptance for both male and female.

It is interesting to notice the young drivers with age below 21 has higher acceptance for coffee coupons, whereas elderly population with 50 plus shows slightly less acceptance but all other intermediate groups show around 50% acceptance.

There is wide acceptance of coffee coupon from students, unemployed folks. Drivers belong to 'building/grounds cleaning/maintenance' have close to 100% acceptance, similar case for 'farmiing/fishing/forestry' & 'healthcare' jobs as well. 'Sales' job folks show comparatively less interest on coffee coupons.

While one can normally think the weather could play a role in coffee consumption, but it was not creating any impact in acceptance of coupons. Infact, the acceptance was slightly low when snowy, so the guess is the driving comfort could have influenced.

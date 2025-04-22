# Summary of Business Problem and Project Objective:
## The business problem is optimizing Swire Coca-Cola’s logistics by determining the right threshold for transitioning low-volume customers to ARTM. While this reduces costs, there’s a risk of moving high-growth potential customers too soon, which could limit future revenue. The challenge is identifying which low-volume customers should stay on direct delivery routes to maximize growth opportunities.

# Solution to the Business Problem:
## We used modeling approaches to predict high-growth customer accuracy. Evaluated high volume costumers by state and delivery costs to discover relationships between the two. Performed customer segmentation through XGBoost with Classification Trees as a cross-validation to determine the characteristics of high-growth customers. These things led us to the discovery that Swire should focus on high potential customers within the states that have the highest volume of sales i.e. Massachusetts and Kansas. 

# My contribution to this project with associated steps below:
## First thing I did was model for outliers
## In order to do this I had to clean the datasets, merge necessary columns, and make sure I had the latest data set downloaded.
## Next, I wanted to keep my data "current" with my group so I copied over there code to ensure data scrutiny.
## Then, I modeled for the outlier detection to increase proficient accuracy. There were very few outliers in the dataset which meant that I could move forward with my modeling.
## After I modeled the actual delivered cases within a decision tree model to understand the accuracy ofthis model method. My RMSE was high which meant that the model was not accurate in its prediction.
## Lastly, I modeled customer segmentation by classification trees to cross validate the XGBoost segmentation created by Anais, I found that we had identical results which meant that the models showed signs of accuracy through this compatability.
## This is all of my code for these steps.

# The Business Value of the Solution:
## This solution enables Swire to identify and prioritize high-growth customers, particularly in Massachusetts and Kansas, where sales volumes are highest. By leveraging predictive modeling and customer segmentation, the company can optimize its sales and marketing strategies, reduce acquisition costs, and drive more efficient revenue growth.

# Difficulties that the group encountered along the way:
## The difficulties we as a group encountered for this project were mainly with our predictive models. It took us a while to find out which models would be most accurate with the handling of the Swire dataset. The models that we found to have high RMSE scores that showcased very little accuracy were decision tree models, linear regression models, and neural networking models. The other difficulty that we had as a group was understanding the technical relevance of our findings for the presentation. We were able to find a solution to this issue by going through our customer segmentation portion and solely focusing on high-growth customers because low and medium-growth customers are at the breakeven point for business value.

# What I learned from this project:
## I learned through this project the importance of relevant analytical information. The reason is because a lot of what we tried to do early on with this project didn't make the final presentation cut as we found that the models either weakly performed or that they didn't fit our business solution to our problem. 
## Another thing I learned and took away from this project is to be more confident in my solutions. I always felt like I had to rely on the strengths of others in regards to analytical reasoning and would shy away from exploring deeper within my predictive modeling. This project however, felt like a more complete process and I was able to dive deeper into my research (this also could be because of the great organization of the data files shared with us by Swire.)

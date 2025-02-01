<<<<<<< HEAD
# Customer-Satisfaction
=======
Customer Satisfaction Analysis for a Business

**Goal**: 
    Evaluate customer satisfaction based on different factors like **product quality**, **service**, and **pricing**.
**Objective**: 
    Determine if there are any significant differences in satisfaction based on these factors.

As this is a simulated project means am going to generate data on my own through python numpy module
1. installation packages
numpy, pandas, matplotlib, seaborn, handle warnings, scipy module

# what my dataset will consists
    Customer_ID: A unique identifier for each customer (can be random).
    Product_Quality_Rating: Rating (1 to 10 scale).
    Service_Rating: Rating (1 to 10 scale).
    Price_Rating: Rating (1 to 10 scale).
    Region: Customer’s region (e.g., North, South, East, West).
    Satisfaction: Whether the customer is satisfied (1) or not (0).

# conclusion 
    1. All the means of the data are same and satisfaction in all regions is same 
    2. Our product has equal ratings in all of the regions 
    3. As we can see the diffrence in means in barplot but actually there is no difference in satisfaction in terms of regions.
    4. So our customers in all the regions has equal point of view in terms of satisfaction.

1. All sample means are the same: The t-test suggests there is no statistically significant difference in satisfaction between the regions, indicating that the sample means for satisfaction are similar across all regions.

2. Product ratings are equal across regions: Our analysis of the data indicates that customer satisfaction ratings for the product are comparable in each region, as per the statistical test results.

3. Difference in means in the barplot is due to random variability: While the barplot visually shows a difference in the average satisfaction between regions, the t-test results (p-value = 0.31) indicate that this difference is likely due to random variability rather than a true effect.

4. No significant difference in customer satisfaction: Statistically, customers in all regions have a similar level of satisfaction with the product, despite the apparent differences shown in the barplot. This suggests that the observed differences in the barplot are not significant enough to conclude that regions perceive the product differently in terms of satisfaction.

Key Learning : Always the sample data must be of large size so that we can draw statistical driven decisions that are accurate enough for the business decisions.
>>>>>>> 46be91f (Initial commit for Customer Satisfaction Project)

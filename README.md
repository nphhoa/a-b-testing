# 🔬 A/B Testing in Ads Campaign
## 📊 1. Project Background
Marketing A/B testing dataset Marketing companies want to run successful campaigns, but the market is complex and several options can work. So normally they tun A/B tests, that is a randomized experimentation process wherein two or more versions of a variable (web page, page element, banner, etc.) are shown to different segments of people at the same time to determine which version leaves the maximum impact and drive business metrics.

The data consists of these columns:

- `Index`: Row index
- `user id`: User ID (unique)
- `test group`: If "ad" the person saw the advertisement, if "psa" they only saw the public service announcement
- `converted`: If a person bought the product then True, else is False
- `total ads`: Amount of ads seen by person
- `most ads day`: Day that the person saw the biggest amount of ads
- `most ads hour`: Hour of day that the person saw the biggest amount of ads

Data source from [Kaggle](https://www.kaggle.com/datasets/faviovaz/marketing-ab-testing/data).
## 📊 2. Business Problem 
The companies are interested in answering two questions:

- Would the campaign be successful?
- If the campaign was successful, how much of that success could be attributed to the ads?

With the second question in mind, we normally do an A/B test. The majority of the people will be exposed to ads (the experimental group). And a small portion of people (the control group) would instead see a Public Service Announcement (PSA) (or nothing) in the exact size and place the ad would normally be.

## 📊 3. Process
My journey begins with a meticulous exploration of the dataset, which includes variables such as the day of the week with the highest ad displays, the hour of the day with the most ad displays, and the total number of ads shown to prospects. 

* **Data Overview**: I began by exploring the dataset to understand its structure and contents. This included identifying key features, data types, etc.
* **Univariate Analysis**: In this stage, I analyzed each variable individually to gain insights into their distributions and key statistics.
* **Bivariate Analysis**: Here, I examined the relationships between pairs of variables. This involved using visualizations and correlation metrics to identify patterns and potential interactions between different features.
* **Statistical Tests**: Finally, I conducted statistical tests to validate our findings from the previous analyses. These tests helped in determining the significance of relationships and differences observed in the dataset.

## 📊 4. Conclusion

In this analysis, I explored the effectiveness of advertisements versus public service announcements (PSAs). Findings from exploratory data analysis (EDA) revealed higher purchase probabilities among users exposed to ads. Hypothesis testing further validated these differences, emphasizing the significant impact of targeted advertising on purchase behavior. By integrating EDA with robust statistical methods, we underscored the pivotal role of ads in shaping consumer decisions, providing valuable insights for optimizing future marketing strategies.

**Recommendations**:
- Optimize Ad Placement by Day: Because Friday and Monday have the person saw the biggest amount of ads, ensure that these days are effectively utilized.
- Adjust Advertising Timing: Consider increasing the number of ads during peak times such as 1 PM, 12 PM, and 11 AM when users are more likely to see ads.
- Increase the number of ads displayed: Showing ads multiple times to users can lead to higher conversion rates. Users with higher conversion rates have typically seen more ads.

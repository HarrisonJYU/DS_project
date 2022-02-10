#### Improve Conversion Rate

Data - users who hit an E-commerce site. 
Characteristics - their country, marketing channel, age, whether they are repeat users, and the number of pages
visited during that session, whether they converted or not.

Process of the analysis

1. Use Exploratory and descriptive stats to sum up the data

2. Use graph to visualize the data and observe the patterns

3. Apply machine learning models to predict conversion rate

4. Come up with recommendations for the product and the marketing teams to improve conversion rate.

#### Data
- country : user country based on the IP address
- age : user age. Self-reported at sign-up step
- new_user : whether the user created the account during this session or had already an account and simply came back to the site
- source : marketing channel source
- Ads: came to the site by clicking on an advertisement
- Seo: came to the site by clicking on search results
- Direct: came to the site by directly typing the URL on the browser
- total_pages_visited: number of total pages visited during the session. This can be seen as a proxy for time spent on site and engagement
- converted: this is our label. 1 means they converted within the session, 0 means they left without buying anything. The company goal is to increase conversion rate: # conversions / total sessions


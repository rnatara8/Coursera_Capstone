# Coursera_Capstone

This segment describes about the project developed to demostrate the data science capabilities to analyse data and propose a solution.

# Background:

The problem statement proposed here is to identify the type of restaurant which could be set up in New York city based on the analysis of number of user chekins with the current restaurants around the city.

### Target Audience:
Stakeholders/Business chains who are interested to extend their branches around New York city. This analysis would help them to identify their favourite area.

# Data:
Leverage the number of resturants around New York city and their food offerings with most number of checkins by the users. Based on the analysis we need to extract what the most preferred food options by the users around the city and propose a solution for the stakeholders to take a decision on this. We will use FourSquare location data to resolve this problem. Below are the key data to be analyzed,

1. Number of restaurants in NY city
2. Type of restaurant
3. Number of checkin by users

# Methodology:
Initially extracted the New York neighborhood information with all the areas.
And then picked Brooklyn area for my analysis to identify all the neighborhoods. With FourSquare, the type and name of the venues identified as neighborhoods are filtered and the data frame is formed.
Finally the number of likes for each venue is populated using Foursquare API and the final data frame is achieved.
And then for each vanue the top five neighborhood with most likes is processed.
Clustering k-means is applied to the neighborhoods for the type of venues to populate the number of venues with most likes.
Four clusters were arrived and the top five most liked venues were identified.

# Results:
Based on the cluster results, below are the venue types which are famous in Brooklyn area of New York.
1. Bagel shop
2. Breakfast spot
3. Sports Bar
4. Grocery store
5. Juice Bar

# Discussion:
The stakeholders who belongs to the category listed in results section could consider finding an opportunity to open new shops in Brooklyn area of New York.

# Conclusion:
All my findings and observation are shared in my blogspot [here.](https://applieddatascience-byrk.blogspot.com/)

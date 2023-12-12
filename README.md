# Ford-gobike-analysis
data analysis project for visualization

[The link for the dataset](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv)
---

## Investigation Overview

in this analysis I covered the Ford gobike service and I explored the users and their gender and what type of users and what is the duration for each gender.

## Dataset Overview and Executive Summary

the dataset is Ford gobike service which is a dataset for the serivce that Ford lunched in San Francisco. in this analysis I found that one time customer is way more than subscribers and the duration for each gender where women are more than men when using the service and the type of users who share their bikes and it wasn't the subscribers but the customers.


## Visualization 1

here in this plot will be showing the ratio between subscribers and the customers and the customers are way more than subscribers.

**The code for the visual**
{
x = df['user_type'].unique()
y = df['user_type'].value_counts(normalize=True)


plt.bar(x,y);
plt.title('Bar chart of user type using the service');
}

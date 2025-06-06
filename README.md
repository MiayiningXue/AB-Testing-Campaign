[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]
(https://colab.research.google.com/github/MiayiningXue/AB-Testing-Campaign/blob/main/AB_Testing_Analysis.ipynb) 

# AB-Testing-Campaign
This A/B testing project analyzes the impact of a website background color change by comparing three key engagement metrics—page views, time spent, and conversion rate—between Group A (white background) and Group B (black background).

# About the dataset 
This dataset contains 7 variables and two experimental groups:

- Group A (Control group): Website with a white background
- Group B (Treatment group): Website with a black background

Columns:
- User ID: Unique identifier for each user
- Group: Randomly assigned groups of users (A / B)
- Page Views: Number of pages the user viewed during their session
- Time Spent: Total duration (in seconds) the user spent on the website
- Conversion: Whether the user completed a desired action (Yes / No)
- Device: Type of device used (e.g., Desktop or Mobile)
- Location: Geographic region within the UK

Data source: https://www.kaggle.com/cdatasets/adarsh0806/ab-testing-practice

# Project Summary
In this project, we conducted a statistical comparison between Group A and Group B to determine whether the background color change had a significant impact on user engagement.

We analyzed three key metrics:
1. Page Views
2. Time Spent
3. Conversion Rate

Statistical Methods Used:
- Independent samples t-test for comparing average page views and time spent
- Proportion z-test for comparing conversion rates
- Chi-square test to examine relationships involving categorical variables such as device and location

We also evaluated whether device type and user location were associated with meaningful differences in the above metrics.

# Key Findings
No significant difference was found between Group A and Group B in terms of:
- Page Views (t-test, p > 0.05)
- Time Spent on the website (t-test, p > 0.05)

Conversion Rate, however, was significantly higher in Group B:
- Group A (white background): ~5.4%
- Group B (black background): ~14.1%, (z-test, p < 0.001)

Device type had no significant effect on conversion rate:
- Desktop vs. Mobile users showed no statistically significant difference (z-test, p > 0.05)

Location had no significant effect on conversion, (Chi-square test, p > 0.05)

# Conclusion: 
Changing the background color from white to black led to a significant improvement in conversion rate. While device type and location did not independently influence outcomes, the new background design (Group B) consistently outperformed the control (Group A), supporting its potential implementation.











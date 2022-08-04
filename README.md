# Individual Self-Assessment 
Name: Sied Mohamed

Group name: Dream Team
## Project Topic:  An analysis of the effect of school ranking and prime rate on the housing price in the Washington DC Metropolitan area.

## Motivation for the project
Housing is one of the key issues for DC residents and the real state is one of the hot markets in the area. Residents considered many factors in their decision to buy a house. One among this is the school raking. The quality of schools will have an effect on the house price. The team members were interested in seeing how various factors affect the value of a home in the DC area. The model and visualizations could be used to help a home buyer determine if the property they're interested in is accurately valued.
## Self-Assessment
The project has four members and each of us has responsibility on the following components of the project: Presentation, Database, Machine Learning and Dashboard. 
My role in the project was handling the machine learning part.  The data I received from the database was not fully cleaned  and hence it was not ready for the machine learning models. For example, the housing price or housing price per room obtained from the database shows that it is a numeric variable. However, whenever I tried to do some descriptive statistics, such as mean it given me no values. It was showing me “inf”. I found the solution through a google search, and I replaced infinite values with “nan” and then drop the null values. 
Further, I conducted the standard machine learning data pre-processing i.e., encoding categorical variables and scaling of the features. Once the data is cleaned and scaled, I run the models. 
One of the challenges I had was accessing the database that was developed by one of the team members (Emanuel). I did not set up the database in PGadmin using SQLAlchemy. I downloaded the final table from our GitHub and load to Jupyter notebook. 
Further during the initial stage, all the models were giving me a very low R2. The R-square was too low because the data were not cleaned for outliers of the target variable. After cleaning for outliers, I managed to get a model with good R2. 
## Team Assessment
As a team, we divide roles based on interest and previous experience. Although I did not have previous experience in machine learning, from my economics background, I was familiar with some of machine learning statistical models and I took the initiation to handle that. One of our team members had previous experience in Tableau and I learned a lot from her experience. Whenever we faced challenges, we discussed during the breakout session and we all take assignment to search for solutions. For example, our prime data has breaks (no values) for certain years (during the financial crisis) and we took the assignment on how to impute these values and we find the solution (use Fed interest rates).
Our communication tools were Slack and email. Whenever, I faced challenges or get new results I update my team members via slack. We shared materials via email and GitHub. 
We benefited for being active members of three, although initially it was five. I suggest for the next cohort not to have a group more than three and assign tasks based on interest.
## Summary
Our results showed that there is a direct correlation between housing price and school ranking.  Within the same Zip code, the price per Bedroom (example 3-bedroom house/apt) varies by 30% between high and lower-ranked school. Although overall, there is negative correlation between prime rate and housing price, , in the past 10 years, that correlation is less vivid. It looks like depending on the location and size of the house, the impact of Prime Rate is variable. 

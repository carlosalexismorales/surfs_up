# surfs_up_challenge

Using SQLite, SQLAlchemy, Python, and Jupyter Notebooks to conduct weather analysis. 

## Project Overview

The purpose of this analysis is to analyze a weather condition dataset stored in a SQLite database to unconver any trends that can provide information on whether a Surf n Shake shop in Oahu, Hawaii, is worth opening and investing in. It is critical to determine consistent weather conditions throughout the year, specifically looking at June and December, because the business depends on good climate - meaning sunny and warm weather is pivotal for success. To secure the invest, statistical analysis must be conducted so that they can convinced it will be a successful business venture.

This assignment consists of two technical analysis deliverables and a written report. This will be accomplished by inspecting the data in the SQLite databas and using SQLAlchemy to connect and generate queries. This will import the necessary data needed for our analysis. Jupiter notebook is also to import dependencies and create the commands to pull the data from the SQLite database. 

1. Determining the Summary Statistics for June
2. Determining the Summary Statistics for December
3. Writing a report for the statistical analysis

## Resources

- Anaconda version 1.10.0
- Conda version 4.13.3
- Python version 3.9.12
- Jupyter-Notebook version 6.4.11
- Pandas version 1.4.2
- ipykernal version 6.9.1
- Numpy version 1.21.5

## Results

Weather in June:

In the image below, we see the code that was written in order to retrieve the weather stats. Dependencies were imported and functions were created to connection to the SQLite database. 





<img width="1119" alt="Screen Shot 2022-07-26 at 7 40 11 PM" src="https://user-images.githubusercontent.com/102444078/181148962-f2268c4e-2bce-468d-9e2e-df54625e8971.png">





In the image below, we see the output as a result of the code above.



<img width="141" alt="Screen Shot 2022-07-26 at 7 40 36 PM" src="https://user-images.githubusercontent.com/102444078/181148997-39ee8c8d-f1ff-43fa-85ab-daf14f2dbbfc.png">




Weather in December:

In the image below, we see the code that was written in order to retrieve the weather stats. Dependencies were imported and functions were created to connection to the SQLite database.




<img width="1141" alt="Screen Shot 2022-07-26 at 7 44 12 PM" src="https://user-images.githubusercontent.com/102444078/181149443-355b71c7-a796-422f-9a98-db94add0a3cb.png">




In the image below, we see the output as a result of the code above. 



<img width="174" alt="Screen Shot 2022-07-26 at 7 44 59 PM" src="https://user-images.githubusercontent.com/102444078/181149543-dff7f8ba-9cac-43c3-a5a6-d870a839553b.png">



3 key differences: 
- June has a higher mean temp than December. This indicates that it is more likely to have warmer weather, however, December's mean isn't too far off. June has a mean temp of 75 and December has mean temp of 71. 
- December has a lower min temp than June. This indicates that it is more likely to have cooler weather. The discrepancy between the min temps is higher than the max, meaning, that December is more inclined to be a lot colder than June. This could result is less business/profits since the weather will work against generating business
- June has a higher max temp than December. This indicates that the weather is warmer during that time period than December, thus leading to more potiental business - assuming that warmer weather generates more revenue. 


## Summary
 
Ultimately, the analysis has determined that the weather does not fluctuate too far off and is relatively consistent. In other words, the weather, specifically the temperature, in Oahu is suitable to open up shop. This is further backed by conducting additonal analysis. There were two more queries performed to capture more data to back up the claim. In the images below, we looked at the data for precipitation for both months. Precipiation was used as another factor to assist the argument. If it rained too much or too frequently, this can damper the amount of business generated. If we take a look at the images below, we see that both months show a low percentage of rainfall. This indicates that there is a very low chance that the shop will have to close frequently. The less amount of times the shop will have to close, the more time it can stay open for business.





<img width="239" alt="Screen Shot 2022-07-26 at 8 31 30 PM" src="https://user-images.githubusercontent.com/102444078/181154728-ca3c2ecf-3e88-47f8-885e-1a63589788cb.png">







<img width="281" alt="Screen Shot 2022-07-26 at 8 31 55 PM" src="https://user-images.githubusercontent.com/102444078/181154775-189710d2-bdca-4ee8-9e49-93dc4ab49d70.png">








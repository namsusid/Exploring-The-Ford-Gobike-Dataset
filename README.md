# Exploring The Ford Gobike Dataset
# by Muhammad Usman Siddiqui
# Dataset
I chose the Ford GoBike System Data from the list of datasets provided by Udacity, and the the bike sharing data of New York City provided on the github page linked to on the dataset options google doc. The wrangling done includes dropping all the rows with null values in the San Francisco dataset, and removing all rows with a value of 0 in the gender column of the New York data set, as a value of 0 corresponded to an unknown gender. Furthermore, all birth years below 1897 were dropped as they correspond to an age greater than 122 which is the longest recorded.

# Summary of Findings
Most of the longest trips were undertaken by riders born after 1970 regardless of gender, type, and city. There is not a significant affect of gender on the trip duration. Customers tend to have longer rides than subscribers. And longer riders were taken in New York than in San Francisco, but the average duration was similar for both cities.

# Key Insights for Presentation
The presentation aims to show three of the most important plots. The relation between the type of user and the trip duration is presented as it is a key result of the analysis. The relation between the gender, the birth year, and the trip duration is presented as this covers a few important conclusions. And the relation beetween the year of birth and the trip duration for New York and San Francisco is presented to see if the data is consistent and explore the differences.

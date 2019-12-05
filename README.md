# Google-code-in-R-
Contains my tasks for GCI

1) For this task, I opened the dataset and used the nrow() and ncol() functions to get the number of observations and variables. These came out as 1593 observations and 45 variables

2) I created a variable called "australianCities" to hold all the observations where the country was "Australia", this was added to using subset. Next I took only the value of the city from the observation as all other information was unnecessary, then I used the function "table()" to get the number of each time a city appears. The last operation was to use subset again to find the city with the most visitors and print out the name. This gave the answer of Melbourne with 8 visitors

3) The variable "siteVisits" contains all the user data related to the number of times they visited. The "boxplot()" function an then be called to plot the graph and the "horizontal = TRUE" tag specifies that it should be horizontal.

4) The first step was to get rid of cities that were left blank, this cleaning of the data is essential as otherwise it would come up as the most popular city. Then excess data is removed so only the city value remains and the "table()" function calculates the number of each value. The "which.max()" function tells us that the most popular city is Denver and returns the place value which can be used to find out how many visits are from there (13).

5) The code uses a function as the same function can be reused in the next task making it more efficient. The variable "siteVisits" will collect the values of the number of times each user visited, this is then put into the function "averageDifference". The function takes the data and works out the mean then the difference and takes one away from the other before returning the result. The result is then printed out. The difference was 0.7715003

6) This program is exactly the same as the one before it except it finds which value is the highest using "which.max()" and removes it. This removes the anomoly and allows the data to be more representative of the data. The difference this time was 0.7091709 which is about 0.07 lower than before removing the outlier.

# Excel-Bike-Sales
Dashboard made in Excel

1. Cleaning the data
a. Removed duplicates
b. Find and Replace to make the data easier to read for the client
i. Marital Status Column
ii. Gender Column

Fixed spelling mistakes in other columns

Needed an age bracket.
Created age brackets column
Used nested IF statements to sort the ages based on the Age column

Pivot Tables:
1. Average income of someone who either bought or hasn't bought.
We can deduce that:
- On average, people who bought a bike has a higher salary
- On average, male make more than female regardless if they've purchased a bike

Visualisation:
Clustered column chart

2. Commute distance. How far is the commute distance for the average person who bought a bike.
We can deduce that:
- The most common commute distance for people that bought a bike is 0-1 miles.
- The most uncommon commute distance for people that bought a bike is 10 miles+.
- If a person's commute distance is 5-10 miles or 10 miles+, then they're unlikely to buy a bike.
- If a person's commute distance is 0-1 miles or 2-5 miles, then they're more likely to buy a bike.

Visualisation:
Line chart

3. How common it is for people in each bracket group to buy a bike.
We can deduce:
- The most common age bracket to buy a bike is 31-54.
- More people in the middle age bracket has a bike.
- People who are <31 and >54 are less likely to get a bike.

4. Same as before but with actual age instead of brackets.
We can deduce:
- The peak of people not buy a bike is around age 26-32
- The peak of people buying a bike is around 33-39
- The linear regression line for people who has purchased a bike is y = -0.2876x + 17.15
- The linear regression line for people who hasn't purchased a bike is y = -0.2208x + 15.946
- If we follow the logarithmic regression line, we can see that people are less interested in bikes the older they get, whether they have purchased a bike or not.

Added Slicers to filter out by:
- Marital Status
- Region
- Education

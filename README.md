# Pandas-challenge

In this activity, it was requested to analyze 2 school district datasets, creating various categories, such as size, types, budget per school, budget per capita and the performance on the standardized test results. 
The aggregate data showcase trends in the school district performance and it will inform future school priorities and decisions:


* Although the total budget for the 15 schools is 24,649,428.00, the overall passing percentage is only 65.172326. The total budget is not evenly distributed: while Bailey High School receives 3,124,928.00 (628.00 per student and 54.642283 of overall passing percentage), Holden High School receives only 248,087.00 (581.00 per student and 89.227166 of overall passing percentage).

![district_summary.PNG](https://github.com/githubemail5326/pandas-challenge/blob/main/PyCitySchools/district_summary.PNG)

![per_school_summary](https://github.com/githubemail5326/pandas-challenge/blob/main/PyCitySchools/per_school_summary.PNG)


* A higher spending per capita does not mean higher overall passing percentage. In fact, the higher overall passing percentage are in schools that spend less than 585 per student and the schools that spend more (between 645-680) have the lowest overall passing percentage. More data analysis will be required to understand the difference on the spending efficiency.

![spending_summary](https://github.com/githubemail5326/pandas-challenge/blob/main/PyCitySchools/spending_summary.PNG)


* It seems that the gap between the top 5 highest schools and the bottom 5 schools are higher in math: while the difference of the Average Reading Score is 2.926842, the difference of the Average Math Score is more than the double, 6.479951.

![top_schools](https://github.com/githubemail5326/pandas-challenge/blob/main/PyCitySchools/top_schools.PNG)

![bottom_schools](https://github.com/githubemail5326/pandas-challenge/blob/main/PyCitySchools/bottom_schools.PNG)

* Charter schools have better overall passing percentages than district schools.

![type_summary](https://github.com/githubemail5326/pandas-challenge/blob/main/PyCitySchools/type_summary.PNG)

* Medium schools (1000 -2000 students) seem to have the optimal size for a higher overall passing percentage when compared to small (<1000 students) and large schools (2000-5000 students).

![size_summary](https://github.com/githubemail5326/pandas-challenge/blob/main/PyCitySchools/size_summary.PNG)


—
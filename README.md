# Business-Case-Apollo-Hospitals - Hypothesis-Testing
Apollo Hospitals was established in 1983, renowned as the architect of modern healthcare in India. As the nation's first corporate hospital, Apollo Hospitals is acclaimed for pioneering the private healthcare revolution in the country.

**Business Insights:**
1. We see that the age group 18-20 has a lot of patients (above 130). The rest of the groups have below 60 patients each.
2. The gender distribution is 50-50 (both genders equally represented) in the data.
3. Only 16% of the patients are smokers where as 84% are non smokers.
4. All the 4 regions have almost similar distribution (25% each).

5. The viral load ditribution looks approximately normal. 
- The mean viral load is around 10. 
- 68% of observations have viral load between 8 and 12.
- 95% of observations have viral load between 6 and 14.
- 99% of observations have viral load between 4 and 16.

6. Severity level 0 has highest observations (almost 43%), followed by 1 (24%), 2 (17%) and 3 (12%). Very few have severiy 4 and above (less than 2%).

7. Hospitalization charges have a distribution with two peaks. We see many observations with hospitalization charges between INR 0 to INR 40000. The number of observations with charges from INR 40000 to INR 80000 reduces. It rises again between INR 80000 and INR 111000. 

This might be because of higher hospitalization charges incurred by smokers. So the second rise is probably due to smoker patients, while the first peak is non smokers.
-  Hospitalization Charges incurred increases with increase in age. 
 - Hospitalization charges increase with age for each gender.
 - In age groups 10-20, 20-30, 30-40, 40-50, males tend to incur more charges than female. However in the 50-60 and 60+ age group, females incur more charges than males.
 - The above point might be because there are more female patients in the 50-60 and 60+ age group. However for the 40-50 age group, despite there being more female patients, male patients still incur more charges overall.
 - Male and female patients have similar hospitalization charges.
 - Smokers have a much greater hospitalization charge than non-smokers.
- The different regions seem to have similar trends in median hospitalization charge.
-  Severity level 0 strangely, has a little higher median hospitalization charge than 1 and 2. There is a slight increasing trend from levels 1 to 4.
-  Severity level 5 again has lower charge (but has only about 1% observations).
- There does not seem to be a clear correlation between viral load and hospitalization charges.
- There does not seem to be a clear correlation between viral load and age.

8. Viral Load : 
- There does not seem to be much difference between the viral load of male and female patients.
 - There again does not seem to be a clear relation between severity levels and viral load.
 - Viral load of smokers seems to be lower than non-smokers. (Since lower CT values indicate higher load, it appears that the viral load reported is actually the CT value. So smokers have lower CT values and hence higher load).
 - Patients from SouthEast seem to have highest CT value (lowest viral load).

9. Southeast and Northeast have higher smoker percentage (18%) than Southwest and Northwest (15%).

10. Viral load in women :
- The viral load distributions for severity levels 0 and 1 seem to follow similar distributions.  Severity level 2 is slightly differently distributed.
- However the mean viral load is almost same across all the groups.




**Hypothesis Test Conclusions and Recommendations:**

1. The mean hospitalization charge of smokers is significantly greater than that of non-smokers.
2. The mean viral load of male and female patients is not significantly different.
3. The proportion of smoking is significantly different across different regions.
3.  The mean viral load of women with different severity levels (0,1,2) are not significantly different.

* We see that smokers incur higher charges. Companies can urge their employees who are smokers, to opt for additional insurance coverage.
* This can also be treated as a lesson in dangers of smoking and companies can use the findings to raise awareness among employees, introduce rehabilitation programs and plans to incentivize stopping smoking.
* The regions where there are greater proportion of smokers (SouthEast and NorthEast) can be the target candidates for a pilot run of such programs, and these can gradually be introduced elsewhere.
* Employees in the older age brackets might be advised to exercise more caution.
* Employees who have recently quit smoking or are in the process of quitting can be provided with additional targeted check up sessions to assess their risk and health status. 

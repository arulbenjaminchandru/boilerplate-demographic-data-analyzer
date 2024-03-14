# Demographic Data Analyzer

This is the boilerplate for the Demographic Data Analyzer project. Instructions for building your project can be found at https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/demographic-data-analyzer


Number of each race:
 race
White                 27816
Black                  3124
Asian-Pac-Islander     1039
Amer-Indian-Eskimo      311
Other                   271
Name: count, dtype: int64
Average age of men: 39.4
Percentage with Bachelors degrees: 16.4%
Percentage with higher education that earn >50K: 46.5%
Percentage without higher education that earn >50K: 17.4%
Min work time: 1 hours/week
Percentage of rich among those who work fewest hours: 10.0%
Country with highest percentage of rich: United-States
Highest percentage of rich people in country: 24.583476174151524%
Top occupations in India: Prof-specialty
..FF......
======================================================================
FAIL: test_highest_earning_country (test_module.DemographicAnalyzerTestCase.test_highest_earning_country)
----------------------------------------------------------------------
Traceback (most recent call last):
  File "c:\Users\arulb\OneDrive\Documents\GitHub\boilerplate-demographic-data-analyzer\test_module.py", line 47, in test_highest_earning_country
    self.assertEqual(actual, expected, "Expected different value for highest earning country.")
AssertionError: 'United-States' != 'Iran'
- United-States
+ Iran
 : Expected different value for highest earning country.

======================================================================
FAIL: test_highest_earning_country_percentage (test_module.DemographicAnalyzerTestCase.test_highest_earning_country_percentage)   
----------------------------------------------------------------------
Traceback (most recent call last):
  File "c:\Users\arulb\OneDrive\Documents\GitHub\boilerplate-demographic-data-analyzer\test_module.py", line 52, in test_highest_earning_country_percentage
    self.assertAlmostEqual(actual, expected, msg="Expected different value for highest earning country percentage.")
AssertionError: 24.583476174151524 != 41.9 within 7 places (17.316523825848474 difference) : Expected different value for highest earning country percentage.

----------------------------------------------------------------------
Ran 10 tests in 0.068s

FAILED (failures=2)
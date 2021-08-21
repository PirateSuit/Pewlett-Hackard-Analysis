# Pewlett-Hackard-Analysis

## Overview

The purpose of this analysis is to discern how many employees are likely to retire in the new future and to sort them by department. Also, we are taking into consideration which employees would be eligible to participate into a mentorship program to help train a new generation of employees.

## Results

- 90,398 employees are likely to be retiring in the near future.
- The jobs with the highest amount of pending retirees are Senior Engineer with 29,414 and Senior Staff with 28,254.
- The jobs with the lowest amount of pending retirees are Assistant Engineer with 1,761 and Manager with 2.
- 1,549 employees are eligible for the mentorship program.


## Summary

If retirements happen as expected, then in four years just over 90,000 roles will need to be filled. At just 1,549 mentorship-eligible employees, the burden would be far too high for this comparitively small group of employees to bring the next generation of Pewlett Hackard up to speed.

Using this query, we can see that there are currently 9 managers employed.

![current_managers](https://user-images.githubusercontent.com/84999050/130306221-15a1c09a-091c-42fb-a14d-7371da83f886.png)


Out of those 9, 2 will be retiring soon, or about 22%

If we use the same code but change it to search for Senior Engineers, we see there are near 86,000 currently employed.
And again, if we use the code to search for Senior Staff, we come up with 82,000.

This means that 1/3 of employees from those departments are soon to retire.

Curiously, there seems to be a cliff on hiring as far as age goes.
Below is a query that searches for employees hired who were born on or after 1965.

![1965 hire](https://user-images.githubusercontent.com/84999050/130307038-72fa7a28-4d63-425b-a455-42edcdf999fc.png)

The query returns these results:

![1965 hires return](https://user-images.githubusercontent.com/84999050/130307050-91e395ac-7a05-44a7-bef1-66f3d8efbe8a.png)

Now, if we change the query parameters to search for people hired who were born on or after 1966, this is what is returned:

![1966 hires return](https://user-images.githubusercontent.com/84999050/130307172-d063c300-23d4-43e3-be48-62358f30aadd.png)



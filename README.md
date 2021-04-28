Q,Find out the population and life expectancy for people in Argentina.
ans:  
Q.Using IS NOT NULL, ORDER BY, and LIMIT, which country has the highest life expectancy?
ans SELECT * FROM country ORDER BY LifeExpectancy DESC LIMIT 1;
Q.Using a single query, list 25 cities around the world that start with the letter F.
ans: SELECT * FROM city WHERE name LIKE "F%" LIMIT 25;.
q.Using IS NOT NULL, ORDER BY, and LIMIT, which country has the lowest population? Discard non-zero populations.
ans: SELECT * FROM country WHERE population !=0 ORDER BY population ASC LIMIT 1;
q. largest country by area top 10.
![image](https://user-images.githubusercontent.com/82040073/116391436-11b94200-a817-11eb-8de4-c093a0eb4928.png)
ans:SELECT * FROM country ORDER BY SurfaceArea DESC LIMIT 10;         
q.Using COUNT, get the number of cities in the USA.
ans:SELECT COUNT(Name) FROM city WHERE countryCode ="USA";
q.Using aggregate functions, return the number of countries the database contains
ans:SELECT COUNT(Name) FROM country;
countries with headofstate elisab*
ans: SELECT * FROM country WHERE Name ="United Kingdom";

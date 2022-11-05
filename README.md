# HackerRank SQL Solutions

# Subdomains Wise Questions

## Basic Select
- [Revising the Select Query I](https://www.hackerrank.com/challenges/revising-the-select-query/problem)
```SQL
    select * from CITY where COUNTRYCODE = 'USA' AND POPULATION > 100000;
```
- [Revising the Select Query II](https://www.hackerrank.com/challenges/revising-the-select-query-2)
```SQL
    select NAME from CITY where COUNTRYCODE = 'USA' AND POPULATION > 120000;
```
- [Select All](https://www.hackerrank.com/challenges/select-all-sql)
```SQL
    select * from CITY;
```
- [Select By ID](https://www.hackerrank.com/challenges/select-by-id)
```SQL
    select * from CITY where ID = 1661;
```
- [Japanese Cities' Attributes](https://www.hackerrank.com/challenges/japanese-cities-attributes)
```SQL
    select * from CITY where COUNTRYCODE = 'JPN';
```
- [Japanese Cities' Names](https://www.hackerrank.com/challenges/japanese-cities-name)
```SQL
    select NAME from CITY where COUNTRYCODE = 'JPN';
```
- [Weather Observation Station 1](https://www.hackerrank.com/challenges/weather-observation-station-1)
```SQL
    select CITY, STATE from STATION;
```
- [Weather Observation Station 3](https://www.hackerrank.com/challenges/weather-observation-station-3)
```SQL
    select distinct(CITY) from STATION where MOD(ID,2) = 0;
```

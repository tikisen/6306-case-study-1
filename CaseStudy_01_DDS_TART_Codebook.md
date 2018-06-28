---
title: "MSDS 6306 Case Study 01 Codebook"
author: "Tahir Ahmad, Alec Neff, Rick Farrow, TQ Senkungu aka TART"
date: "6/28/2018"
output:
    html_document:
        keep_md: true
---



## Study design and data processing

### Notes on the original (raw) data 

The raw data has been added to the two files we were given to us for investigation. Those two files are Beers.csv and Breweries.csv.

## Creating the tidy datafile

### Guide to create the tidy data file Description on how to create the tidy data file

The clean file we create in the analysis is merged from the two files we were given. We renamed one variable of data in each original data set. The Name variable in Beers.csv would be renamed to Beer_Name and the Name variable in Breweries.csv is renamed to Brewery_Name.

### Cleaning of the data Short, high-level description

No cleaning is necessary beyond what has been described.

## Description of the variables in the tiny_data.txt file General description of the file including:

- Dimensions of the data set when merged: 2408 observations of 10 variables.
- Here's a summary of the data

```r
summary(beers2)
```

```
##     Brew_ID       Beers Name          Beer_ID               ABV         
##  Min.   :  1.0   Length:2408        Length:2408        Min.   :0.00100  
##  1st Qu.: 94.0   Class :character   Class :character   1st Qu.:0.05000  
##  Median :206.0   Mode  :character   Mode  :character   Median :0.05600  
##  Mean   :232.7                                         Mean   :0.05978  
##  3rd Qu.:367.2                                         3rd Qu.:0.06700  
##  Max.   :558.0                                         Max.   :0.12800  
##                                                        NA's   :62       
##       IBU            Style              Ounces          Breweries Name    
##  Min.   :  4.00   Length:2408        Length:2408        Length:2408       
##  1st Qu.: 21.00   Class :character   Class :character   Class :character  
##  Median : 35.00   Mode  :character   Mode  :character   Mode  :character  
##  Mean   : 42.71                                                           
##  3rd Qu.: 64.00                                                           
##  Max.   :138.00                                                           
##  NA's   :1003                                                             
##      City              State          
##  Length:2408        Length:2408       
##  Class :character   Class :character  
##  Mode  :character   Mode  :character  
##                                       
##                                       
##                                       
## 
```
- Variables present in the data set
-- Brewery_id
-- Beer_Name
-- Beer_ID
-- ABV
-- IBU
-- Style
-- Ounces
-- Brewery_Name
-- City
-- State


### Variable 1: Brewery_id
- Class of the variable: int
- Unit of measurement: ordinal assigned to each brewery

### Variable 2: Beer_Name
- Class of the variable: character
- Unit of measurement: name given to each Beer

### Variable 3: Beer_ID
- Class of the variable: character
- Unit of measurement: numbers assigned as an ID for each beer

### Variable 4: ABV
- Class of the variable: number
- Unit of measurement: decimal value which is a percentage of volume of each beer which is alcohol

### Variable 5: IBU
- Class of the variable: number
- Unit of measurement: International Bittering Units which is a measure of bitterness of beer.

### Variable 6: Style
- Class of the variable: character
- Unit of measurement: name for the style of the beer

### Variable 7: Ounces
- Class of the variable: character
- Unit of measurement: how many ounces of beer in a container

### Variable 8: Brewery_Name
- Class of the variable: character
- Unit of measurement: name of the brewery

### Variable 9: City
- Class of the variable: character
- Unit of measurement: name of the city

### Variable 10: State
- Class of the variable: character
- Unit of measurement: state abbreviation

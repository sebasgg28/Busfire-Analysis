# Bushfire-Analysis
Using R and advanced regression techniques to explore and predict bushfires from meteorological data. 

## Introduction

Forest fires have been an issue that causes many damages such as habitat, structure, and life losses. In some areas, the animal’s
ecosystem is not able to recover, and the human loss tally a big number. An extract from Paulo Cortez and Anibal Morais from
their paper: “A Data Mining Approach to Predict Forest Fires using Meteorological Data” (you can find it here http://www3.dsi.uminho.pt/pcortez/fires.pdf), give us a new perspective on how to predict forest fires. Using sensors, the tell variables such as temperature, wind, humidity, and rain, models can be developed to
determine which factors are critical to potentially avoid a fire. On this approach, we will measure different models to see which one is more accurate.

## Libraries

- `ggplot2` 
- `caTools`
- `reshape2`
- `stats`
- `caTools`
- `caret`
- `kernlab`


### Variables
<br>
X - x-axis spatial coordinate within the Montesinho park map: 1 to 9 <br>
Y - y-axis spatial coordinate within the Montesinho park map: 2 to 9<br>
month - month of the year: 'jan' to 'dec'<br>
day - day of the week: 'mon' to 'sun'<br>
FFMC - FFMC index from the FWI system: 18.7 to 96.20<br>
DMC - DMC index from the FWI system: 1.1 to 291.3<br>
DC - DC index from the FWI system: 7.9 to 860.6<br>
ISI - ISI index from the FWI system: 0.0 to 56.10<br>
temp - temperature in Celsius degrees: 2.2 to 33.30<br>
RH - relative humidity in %: 15.0 to 100<br>
wind - wind speed in km/h: 0.40 to 9.40<br>
rain - outside rain in mm/m2 : 0.0 to 6.4<br>
area - the burned area of the forest (in ha): 0.00 to 1090.84<br>

## Models
<br>
1) Multiple Linear Regression<br>
2) SVM<br>
3) Logistic Regression<br>

## Data Exploration:

### Loading Data

![Imgur](https://imgur.com/4lnLvus.png)

### Variables That Produced a Fire

![Imgur](https://imgur.com/CNYhLQA.png)

### Analysing Correlations

![Imgur](https://imgur.com/uXPsIR4.png)

These are just some techniques that were used to understand the data and get a glimpse of what we are dealing with.

## Reference Paper

P. Cortez and A. Morais. "A Data Mining Approach to Predict Forest Fires using Meteorological Data" http://www3.dsi.uminho.pt/pcortez/fires.pdf

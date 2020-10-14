# Problem Statement:Concrete Strength Prediction

## Objective To predict the concrete strength using the data available in file concrete_data.xls. 

Apply feature engineering and model tuning to obtain 80% to 95% of R2score.

Resources Available 

The data for this project is available in file https://archive.ics.uci.edu/ml/machine-learning-databases/concrete/compressive/. 
The same has been shared along with the course content.

Attribute Information: Given are the variable name, variable type, the measurement unit and a brief description. 

The  concrete  compressive  strength is  the  regression  problem.  The  order  of  this  listing corresponds  to  the order of numerals along the rows of the database.

## Name --Data Type --Measurement --Description

-Cement (cement) --quantitative --kg in a m3 mixture --Input Variable

-Blast Furnace Slag (slag) --quantitative --kg ina m3 mixture --Input Variable

Fly Ash (ash) --quantitative --kg ina m3 mixture --Input Variable

Water (water) --quantitative --kg in a m3 mixture --Input Variable

Superplasticizer (superplastic) --quantitative --kg in a m3 mixture --Input Variable

Coarse Aggregate (coarseagg) --quantitative --kg in a m3 mixture --Input Variable

Fine Aggregate (fineagg) --quantitative --kg in a m3 mixture --Input Variable

Age(age) --quantitative --Day (1~365) --Input Variable

Concrete compressive strength(strength) --quantitative --MPa --Output Variable

Resutls: 

Gradient Boosting after RandomCV:

Training Score: 0.994772

Testing Score: 0.930501

Slightly overfitting, would need to make some adjustments to correct that. 

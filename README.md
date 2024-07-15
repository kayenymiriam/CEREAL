# A NUTRITIONAL BREAKDOWN OF COMMON BREAKFAST CEREALS

![](https://github.com/kayenymiriam/CEREAL/blob/main/11%2B%20Best%20Low%20Calorie%20Cereals%20for%202024%20(%2B%20Recipe!).jpeg)

### INTRODUCTION
This is a Power BI  project on the analysis of nutritional data from cereal on the market.

### DATA SOURCING
This data was obtained from kaggle, an online website containing datasets. It contains 77 rows with 16 columns (name, manufacturer, type, calories, protein, fat, sodium, fiber, carbohydrates, sugars, potassium, vitamin, shelf, weight, cups, rating). These nutritional details were per serving.


### OBJECTIVES
- What cereals would be most suitable for consumers looking for low-carb diets?
- What brand produces cereal with the highest amount of calories?
- Is there a correlation between sugars and calories?
- What cereal brand received the highest ranking?
- What cereal has the highest amount of calories per serving?

### SKILLS DEMOSTRATED
The following Power BI features were incorporated;
Calculated columns, quick measures, measures.


![](https://github.com/kayenymiriam/CEREAL/blob/main/correlation.png)



![](https://github.com/kayenymiriam/CEREAL/blob/main/highest%20calories.png)





### DATA TRANSFORMATION AND MODELLING
This dataset was already cleaned. Using power query, data types were then changed to whatever was appropriate for each column. I replaced negative nutritional values with 0 (zero). Data modeling was not done since it was only one table.

### ANALYSIS AND VISUALISATION
- The average amount of carbohydrates per serving in this dataset is 14.64g and values below this were categorized as being “low” while those above it were categorized as being “high” in the table shown. A calculated column using the IF function was used to add these categories. So the table shows the cereal name and whether or not the carbohydrate amount preserving is high following the parameters mentioned.
 
![](https://github.com/kayenymiriam/CEREAL/blob/main/carbohydrate%20category.png) 




- The average amount of calories per serving in this dataset is 107 and values below this were categorized as being “low” while those above it were categorized as being “high.” A calculated column using the IF function was used to add these categories. According to the clustered column chart below, General mills manufactured the most cereals with a high number of calories compared to other brands.
![](https://github.com/kayenymiriam/CEREAL/blob/main/calories%20categories.png)
  



- Sugars and calories have a strong positive correlation. Using quick measures, a correlation coefficient of 0.98 was obtained when sugars and calories were correlated for calories.
- Nabisco received the highest average rating of 67.97 from the consumers of cereal manufactured by them. However, only 6 of the 77 cereal types in this dataset were manufactured by Nabisco. Majority of the cereal in this dataset was manufactured by Kellogs and it received an average rating of 44 from the consumers of their products.
- With calories of 160g,Mueslix crispy blend has the highest amount of calories per serving in this data set. This was obtained using the calculate, MAX and filter functions

![](https://github.com/kayenymiriam/CEREAL/blob/main/cereal%20dashboard.png)




### CONCLUSIONS AND RECOMMENDATIONS
- The data set contains nutritional information of cereals per serving. These values are significantly lower than the FDA recommended daily intake so it is up to an individual to regulate the number of servings they consume daily. 
- Caution should be taken when consuming cereals with higher calories per serving as they can cause significant weight gain overtime.
- The concept of weight gain deals with the balance between energy/calorie intake and use. An imbalance causes either weight gain or loss. 
Therefore to effectively lose weight/maintain a normal BMI, substitute high calorie cereals with those having lower calories, control the number of servings per day and carry out physical  exercises.




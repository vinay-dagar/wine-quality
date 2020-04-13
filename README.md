
[Here is the link to original dataset used](https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009)

______

![The Read Wine Image](https://www.thespruceeats.com/thmb/Fv9_8yovhCtj_HYhZXIL6jba43E=/960x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/red-wine-is-poured-into-a-glass-from-a-bottle--light-background--1153158143-98320451802c485cb6d7b5437c7fd60a.jpg)

_______

### To use this notebook clone this repository (https://github.com/vinay-dagar/wine-quality.git) 

* Python packages used:
  * Pandas
  * NumPy
  * Seaborn
  * Matplotlib
  * Sklearn



> By analyzing the wine data we'll see that, there are some ingredients that are coorelated with the Wine Quality





* Relation of Ingredients of wine
  * There is negative coorelation b/w VOLATILE ACIDITY and the quality of wine, higher the VOLATILE ACIDITY, the lower the quality of the wine
  * These is positive coorelation B/W CITRIC ACID and QUALITY of wine





### The quality of the Wine is defined by range of number from 2 - 8 (worst - better  respectively)
> To perform mathematical operations we need to convert the range to actual quality

##### For that we'll use the pandas cut function to change the range to label, and the LabelEncoder class from SKlearn library to convert the categorical labels of quality into numeric values
> We could also use the map function to map the numeric values to the categories


______

# CONCLUSION

_________

## After analyzing the WINE data we can conclude


####  physiochemical properties make a wine quality better!

> RESIDUAL SUGAR, FIXED ACIDITY, SULFUR DIOXIDE does not impact the quality of the wine.

> There is a positive coorelation between CITRIC ACID & the quality of wine.

> There is a negative coorelation between VOLATILE ACIDITY & the quality of wine.

> There are some other properties like CHLORIDES and SULPHATES impact somewhat quality of the wine

---
title       : U.S. State Data App
subtitle    : Get Key Information About U.S. States
author      : Lori Bisch
job         : Data Scientist
logo        : logo.png
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [bootstrap, quiz, shiny, interactive]
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides



--- .class #id 
## U.S. State Data App

### Get information about U.S. states with this easy-to-use [online application](https://loribisch.shinyapps.io/CourseraProj/)!
* Uses the state.x77 data set
* generate scatter plots
* calculate min/max/mean on all variables
* compare states on all variables with an interactive map

### Data Set and Variables

```r
library(datasets)
df<-data.frame(state=row.names(state.x77),state.x77,row.names=NULL)
names(df)
```

```
## [1] "state"      "Population" "Income"     "Illiteracy" "Life.Exp"  
## [6] "Murder"     "HS.Grad"    "Frost"      "Area"
```

--- 
## Plot State Data

### Uses R, Shiny, and Google Charts to create an interactive web page:

![Google ScatterPlot](C:/Users/Lori/Documents/Data Science/Data and Assignments/DevDataProds/State_data_app/assets/img/plot.JPG)




---
## Interactive Mapping 

![Google GeoChart](C:/Users/Lori/Documents/Data Science/Data and Assignments/DevDataProds/State_data_app/assets/img/map.JPG)

---
## Get Min/Mean/Max

![Example Plot](C:/Users/Lori/Documents/Data Science/Data and Assignments/DevDataProds/State_data_app/assets/img/calc.JPG)


### Don't forget to [try it out](https://loribisch.shinyapps.io/CourseraProj/)!



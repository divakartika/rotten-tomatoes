# rotten-tomatoes
Published Article: [Rotten Tomatoes Data Visualization](https://rpubs.com/divakartika/rotten-tomatoes)

## Introduction

Rotten Tomatoes is a movie and TV show review website. The name "Rotten Tomatoes" is related to the term used to rate a show. When a film is judged good, the film is said to be *fresh*, while if it is judged to be bad, the film is said to be *rotten*.

Not only hosting reviews from general audiences, Rotten Tomatoes also collects reviews from leading critics. Even the assessment of these critics has its own naming system, namely Tomatometer®. This has resulted in Rotten Tomatoes being one of the most trusted entertainment industry review sites in the world.

This time we will create a visualization of Rotten Tomatoes review data! The data we will use can be accessed from [Kaggle: Rotten Tomatoes Top Movies Ratings and Technical](https://www.kaggle.com/datasets/thedevastator/rotten-tomatoes-top-movies-ratings-and-technical).

## Libraries

```{r}
# for data wrangling
library(reshape2)
# for datetime-related data processing
library(lubridate)
# dplyr (function piping), tidyr (data cleaning), and ggplot2 (visualization)
library(tidyverse)
```

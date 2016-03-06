# Reproducible Research: Peer Assessment 1


## Loading and preprocessing the data

```{
require(plyr)
require(ggplot2)
unzip(~/RepData/activity.zip)
activity <- read.csv("activity.csv", header = TRUE)
activity <- transform(activity, date = as.Date(date))
}

```

## What is mean total number of steps taken per day?



## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?

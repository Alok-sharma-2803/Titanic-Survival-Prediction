# Importing data from source -------------------------------------------

Train <- read.csv(file = "/Users/aloksharma/Desktop/Titanic Dataset/train.csv",
                  stringsAsFactors = F)
Test <- read.csv(file = "/Users/aloksharma/Desktop/Titanic Dataset/test.csv",
                 stringsAsFactors = F)
str(Train)

#Combining Train and Test datasets for data preparation, cleaning, feature engineering etc.

Titanic <- bind_rows(Train,Test)

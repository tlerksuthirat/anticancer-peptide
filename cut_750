library(readxl)
library(dplyr)

ML3_top1500 <- read.csv("file.csv", header = TRUE)

##execute this fisrt to store in merge1
ML3_top1500_1 <- ML3_top1500[51:100,]
ML3_top1500_2 <- ML3_top1500[151:200,]
ML3_top1500_3 <- ML3_top1500[251:300,]
ML3_top1500_4 <- ML3_top1500[351:400,]
ML3_top1500_5 <- ML3_top1500[451:500,]
ML3_top1500_6 <- ML3_top1500[551:600,]
ML3_top1500_7 <- ML3_top1500[651:700,]
ML3_top1500_last <- ML3_top1500[1451:1500,]
merge1 <- bind_rows(ML3_top1500_1,ML3_top1500_2,ML3_top1500_3,ML3_top1500_4,ML3_top1500_5,ML3_top1500_6,ML3_top1500_7)

##execute this second in merge2
ML3_top1500 <- ML3_top1500[701:1500,]
ML3_top1500_1 <- ML3_top1500[51:100,]
ML3_top1500_2 <- ML3_top1500[151:200,]
ML3_top1500_3 <- ML3_top1500[251:300,]
ML3_top1500_4 <- ML3_top1500[351:400,]
ML3_top1500_5 <- ML3_top1500[451:500,]
ML3_top1500_6 <- ML3_top1500[551:600,]
ML3_top1500_7 <- ML3_top1500[651:700,]
merge2 <- bind_rows(ML3_top1500_1,ML3_top1500_2,ML3_top1500_3,ML3_top1500_4,ML3_top1500_5,ML3_top1500_6,ML3_top1500_7,ML3_top1500_last)

##merge1 and merg2
ML3_top1500_cut_750 <- bind_rows(merge1,merge2)
write.csv(ML3_top1500_cut_750,file = "ML3_top1500_cut_750.csv")

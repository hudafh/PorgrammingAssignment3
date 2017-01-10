# PorgrammingAssignment3

#30-day Mortality Rate from Heart Attack -> 11
#[17] "Hospital.30.Day.Death..Mortality..Rates.from.Heart.Failure"      
#[23] "Hospital.30.Day.Death..Mortality..Rates.from.Pneumonia" 



best<- function(state, outcome) {
  
    fdata <- read.csv("outcome-of-care-measures.csv")
  
    stdata <- fdata["State"]== "AL"
    stdata 
    
     if(fdata["State"]== "AL")
       stdata <-fdata
 #   stdata[,13]
    colnames(stdata)
}

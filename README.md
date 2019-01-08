# Acadgild_Data-Analytics_Session-3-Assignment-3.4

# A.	Implement user defined functions within apply function using the mtcars data set and produce column wise summary statistics using apply function and mtcars dataset.

	View(mtcars) 

  tapply(mtcars$mpg,mtcars$disp,median)        # finding the median of the data 

	tapply(mtcars$mpg,mtcars$disp,mean)           # finding the mean of the data
  
  

# B.	write a program to extract the names of the list.
 
n=list(mtcars$mpg,mtcars$cyl,mtcars$disp,mtcars$hp) 

n 

colnames(mtcars)

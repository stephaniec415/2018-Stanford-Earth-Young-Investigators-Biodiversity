#Problem Set 1

1. mtcars - data.frame

2. precip is defined as a vector because dim(precip) = NULL 
3. trees: as.matrix(trees)
4. 14th City: Atlanta - precip[14]
5. Data Frame 
6. precip consist of numeric data - class(precip) = Numeric
7. four ways: 
	* mtcars["Mazda RX4 Wag", "qsec"] 
	* mtcars[2, "qsec"] 
	* mtcars["Mazda RX4 Wag", "qsec"]
	* mtcars[2, 7]
8. Change by:
	* Juneau - precip[2] <- 23
	* Phoenix - precip[match("Phoenix", names(precip))] <- 46
	* Sacramento - precip[6] <- 12
9. No, because trees[1:31]>=trees[63:93] showed all false results.
10.	Word Problem:
	* sum of the height of trees - sum(trees[32:62])=2356=A 
	* sum of Valiant of ntcars - sum(mtcars[6, ])=385.54=B 
	* sum of first 8 elements of precip - as.matrix(precip) then sum(precip[1:8])=249.4=C
	* C/B+A=2356.647
	

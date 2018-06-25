#Problem Set 1

1. mtcars - data.frame
2. precip is defined as a vector because dim(precip) = NULL 
3. trees: as.matrix(trees)
4. 14th City: Atlanta - precip[14]
5. Data Frame 
6. precip consist of numeric data - class(precip) = Numeric
7. four ways: 
	mtcars["Mazda RX4 Wag", "qsec"] 
	mtcars[2, "qsec"] 
	mtcars["Mazda RX4 Wag", "qsec"]
	mtcars[2, 7]
8. Change by
	Juneau - precip[2] <- 23
	Phoenix - precip[match("Phoenix", names(precip))] <- 46
	Sacramento - precip[6] <- 12
9. Yes 
10. 

# Section 1 Questions 

1. REPLACE= in the argument of the sample() can replace a number with another possible number at random and it allows each number to be sampled more than once. 
2. MyMatrix*1
3. MyMatrix[which(MyMatrix)] or apply(MyMatrix, 1, sum) == ncol(MyMatrix)

# Section 2 Questions 

1. MyMatrix[which(MyMatrix==7)] or mySevens <- MyMatrix[MyMatrix == 7] then length(mySevens) - 16 times
2. apply(MyMatrix,1,sum) or colSums(MyMatrix)
3. apply(MyMatrix,2,prod)
4. MyMatrix[which(MyMatrix==10)]<-12
5. length(MyMatrix[which(MyMatrix>3 & MyMatrix<8)]) - 33 values
6. MyDataFrame <- as.data.frame(MyMatrix)
then MyDataFrame[,12] <- as.character(MyDataFrame[,12])
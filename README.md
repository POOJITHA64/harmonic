#harmonic
print("Enter values in an array")
x<- scan()
n<-length(x)
sum<-0
for(i in 1:n)
  {
    sum=sum+(1/x[i])
  }
  hm<-n/sum
print("Harmonic mean of the given values")
print(hm)
print("Harmonic mean value using built in function")
print(n/sum((1/x)))

x<-c(6,8,9,10,50,16)
n<-length(x)
n<-scan()
k=1
for(i in 1:n)
{
  k=k+(1/x[i])
}
hm=n/k
sprintf("harmonic mean %f",hm)


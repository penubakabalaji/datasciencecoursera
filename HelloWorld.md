> "Hello World !"
[1] "Hello World !"
> name <- "Balaji"
> age <- 45
> 
> for(x in 1:10) {print(x)}
[1] 1
[1] 2
[1] 3
[1] 4
[1] 5
[1] 6
[1] 7
[1] 8
[1] 9
[1] 10
> a <- 33
> b <- 200
> 
> if (b > a) {
+     print("b is greater than a")
+ }
[1] "b is greater than a"
> 
> a <- 33
> b <- 33
> 
> if (b > a) {
+     print("b is greater than a")
+ } else if (a == b) {
+     print ("a and b are equal")
+ }
[1] "a and b are equal"
> 
> a <- 200
> b <- 33
> c <- 500
> 
> if (a > b & c > a) {
+     print("Both conditions are true")
+ }
[1] "Both conditions are true"

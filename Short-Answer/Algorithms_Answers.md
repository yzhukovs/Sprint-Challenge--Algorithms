Add your answers to the Algorithms exercises here.
##Exercise I

a. O(n) -> this method depends on n input for any n grater than 0 and it will take n times to finish the loop. the operation is 0(n)

b. O(n^3) - > this loop has 3 nested  O(n) therefore n*n*n will give this loop an O(n^3). 4th loop only runs fixed number of times.

c. O(n) - -> It runs recursively till bunnies == 0,  as n increases the number of operation increases that's why I believe this function is  O(n)



##Exercise II

I think the best strategy that will result in the least amount of wasted egss will be the binary search, _O(log n)_. First we will devide the number of floors in half and then we will throw an egg, if the egg breaks we eliminate the above floors and will move down half again and so on. If it doesn't break, we eliminate the below floors and we will move up half again. I think it's the best strategy to find that value of _f_. 



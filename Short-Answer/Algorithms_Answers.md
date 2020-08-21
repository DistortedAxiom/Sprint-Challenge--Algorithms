#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)

The run time complexity for this function will be O(n), while n is multiplied 3 times, 
it will combine so that it will only run once

b)

The run time complexity would be O(n log n), since the first for loop will be O(n), the while loop would be another O(n). However, it is increasing by x2 
for every pass, making it O(log n). O(n) * O(log n) = O(n log n)

c)

The run time complexity would be O(n), as the recursive function is called additionally by n for every
additional n is added

## Exercise II

It seems like we can utilize binary search to solve this problem. 

I would start in the middle of the building, if the egg does not break at the middle,
I would move up to the middle floor between the CURRENT floor and the top floor. 

If the egg breaks at the middle, I would do the opposite, going to the middle floor between the 
CURRENT floor and the bottom floor. 

This process would be repeated until we find the floor where egg does not break.

This would have the time complexity of O(log n)

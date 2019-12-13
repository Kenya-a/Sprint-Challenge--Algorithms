#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)O(n)


b) O(n(log n))


c) O(n)

## Exercise II
Goal: Find out what floor f is. 

First I would take the total number of floors and divide it in half. From thier we could test whether the egg breaks on the floor on the first half or the second half. If the egg breaks on both sides then, I would divide the two halves in two creating a smaller range for the egg to break almost like using merge sort but testing to see if the egg breaks as we split up the sides. This would narrow the range of floors to find out the highest point the egg can be dropped before it breaks. I because this process will be similar to merge sort the runtime complexity should be O(n(log n))


# Selection-Sort
DAA program1 in java-

Sort a given set of n integer elements using Selection Sort method and compute its time 
complexity. Run the program for varied values of n> 5000 and record the time taken to sort. 
Plot a graph of the time taken versus n. The elements can be read from a file or can be 
generated using the random number generator. Demonstrate using Java how the brute 
force method works along with its time complexity analysis: worst case, average case and best 
case.


# ALGORITHM
1. k ← length [A]
2. for j ←1 to n-1
3. smallest ← j
4. for I ← j + 1 to k
5. if A [i] < A [ smallest]
6. then smallest ← i
7. exchange (A [j], A [smallest])


# Time Complexities:

Best Case Complexity: The selection sort algorithm has a best-case time complexity
of O(n2) for the already sorted array.

Average Case Complexity: The average-case time complexity for the selection sort
algorithm is O(n2), in which the existing elements are in jumbled ordered, i.e., neither in
the ascending order nor in the descending order.

Worst Case Complexity: The worst-case time complexity is also O(n2), which occurs when
we sort the descending order of an array into the ascending order.

In the selection sort algorithm, the time complexity is O(n2) in all three cases. This is
because, in each step, we are required to find minimum elements so that it can be placed
in the correct position. Once we trace the complete array, we will get our minimum
element.

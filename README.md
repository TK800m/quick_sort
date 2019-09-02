# quick_sort
quick sort algorithm has 2 functions to function that require manual inputs.

First is the function: setup_pivot(unsorted_array)
This function takes an array as input and finds a median value based on 3 values (start, mid, end) in this array and puts the median at the end of the array to improve the speed of quick_sort. This is not a vital step in the sorting array, but will increase efficiency

The second function is quick_sort(unsorted_array, start, end) that takes the array, the first index (start) and the last index (end) as input to order the array properly


quicksort(easy_arr, 0, len(easy_arr)-1)  
print(easy_arr)

# merge_sort
merge sort algorithm 
This uses a divide and conquer strategy that divides the array into increasingly smaller arrays until only the values are left. From there the new array c is created with the smallest values first

The function is used as follows: sorted_array = merge_sort(unsorted_array)
The function returns the sorted array and takes the unsorted_array as input

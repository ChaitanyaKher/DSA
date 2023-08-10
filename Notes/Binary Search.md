Binary Search is defined as a searching algorithm used in a **sorted** array by ***repeatedly dividing*** the search interval in half.

The idea of binary search is to use the information that the array is sorted and reduce the time complexity to O(log N).

Steps include:
1. Divide the search space into two halves by finding the middle index "mid". 
	>mid = low + (high-low)/2
2. Compare the middle element of the search space with the key.
3. If the key is not found at the middle element, choose which half will be used as the next search space.
	1. If the key is smaller than the middle element, then the left side is used for next search.
	2. If the key is bigger than the middle element, then the right side is used for next search.
4. The process is continued until the key is found or the total search space is exhausted.


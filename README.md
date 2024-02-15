# Searching-Algorithm

##  Linear Search 

- Linear search is a simple searching algorithm that sequentially checks each element in a list until the target element is found or the end of the list is reached. It has a time complexity of O(n), where n is the number of elements in the list.	

|                |Best                          |Worst                         |
|----------------|-------------------------------|-----------------------------|
|Time Complexity |`O(1)`                      |`O(n)`         |


##  Binary Search 

- Binary search is a fast search algorithm used to find a target value within a sorted array. It compares the target value to the middle element of the array and halves the search space each time by discarding one half based on the comparison. It achieves a time complexity of O(log n), where n is the number of elements in the array.	

|                |Best                          |Worst                         |
|----------------|-------------------------------|-----------------------------|
|Time Complexity |`O(log n)`                      |`O(n)`         |
|Space Complexity (Recursive) |`O(log n)`                      |`O(n)`         |
|Space Complexity (Iterative) |`O(1)`                      |`O(n)`         |

##  Ternary Search 

- Ternary search is a divide-and-conquer algorithm used to find the maximum or minimum of an unimodal function within a given interval. It operates by recursively dividing the interval into three equal parts and determining which part the maximum or minimum lies in. It has a time complexity of O(log3 n), where n is the size of the search space.

|                |Best                          |Worst                         |
|----------------|-------------------------------|-----------------------------|
|Time Complexity |`O(log3 n)`                      |`O(log3 n)`         |
|Space Complexity (Recursive) |`O(log3 n)`                      |`O(log3 n)`         |
|Space Complexity (Iterative) |`O(1)`                      |`O(n)`    |

In ternary search, both the time and space complexities are determined by the logarithm with base 3 due to the splitting of the search space into three parts at each step.    


# Hybrid Merge sort and Selection sort algorithms 
This project develops a hybrid sorting algorithm combining Selection Sort and Merge Sort to optimize performance across various input sizes. It dynamically switches between the two based on dataset size, leveraging Merge Sort's efficiency for large data and Selection Sort's simplicity for small data, aiming for balanced, improved performance.


## Merge sort
Merge Sort is a divide-and-conquer algorithm that excels in handling large datasets by recursively dividing 
them into smaller subproblems. The sorted subarrays are then merged to produce the final ordered array. 
Merge Sort is renowned for its stable time complexity of O(n log n), which ensures efficient sorting. 
This makes it an attractive choice for scenarios where predictability and reliability are paramount.


![merrg](https://github.com/user-attachments/assets/712100a8-fc5f-4bf3-b885-422cdcfd07b9)


![table merg](https://github.com/user-attachments/assets/6d19d619-4738-47d7-a394-dfd11cf73fb9)









## Selection sort
Selection Sort is an algorithm that works by repeatedly selecting the smallest (or largest) element from the 
unsorted portion of an array and placing it in its correct position. Even though it has a time complexity of 
O(n^2), it is easy to implement and can be useful when there are memory constraints.

![sele](https://github.com/user-attachments/assets/0c6c31de-9b28-4fd5-aba7-915684b01b29)



![sele table](https://github.com/user-attachments/assets/e3dc32e0-4d2c-40de-b402-79d25ad1ed2d)



## Hybrid algorithm 
The hybrid sorting algorithm optimally combines the simplicity of Selection Sort 
with the efficiency of Merge Sort, adapting dynamically based on the size of the input array to 
achieve improved overall performance. The choice of the threshold k allows for fine-tuning 
based on the specific requirements of the application.


### Implementation of algorithms individually:
We used Java code to implement the merge sort, selection sort and Hybrid algorithm. At first, the 
user will enter the length of the array, then the program will use a random () function to generate 
array elements and implement sorting on them

### Merge sort:
Run implementation:

![merg run](https://github.com/user-attachments/assets/1ccd8f67-a7c5-4a66-842b-5d81cde4bc38)


### selection sort
Run implementation:

![selec run](https://github.com/user-attachments/assets/b4dac15d-f1ed-4f34-a86a-d38d1d12d093)



### HybridSort:
Run implementation :


![hybrid run](https://github.com/user-attachments/assets/1f49b952-4866-4d6b-a6e3-0cc0c55246ab)




















#### ARRAY

An array is a collection of elements (values or variables), each identified by an index or key. All the elements in an array are stored in contiguous memory locations and are usually of the same data type (e.g., all integers, all characters).

🔹 Features of an Array:
    
  1. Fixed size: Once an array is declared, its size cannot be changed (in static arrays).

  2. Same data type: All elements must be of the same type.

  3. Indexed: Array elements are accessed using their index, starting from 0 (in most languages).

  4. Efficient access: Accessing any element takes constant time: O(1).

🔹 Types of Arrays:

 1. One-Dimensional Array

Example:

    int numbers[5] = {10, 20, 30, 40, 50};
    
2. Two-Dimensional Array (Matrix)

Example:

    int matrix[3][3] = {
    {1, 2, 3},
    {4, 5, 6},
    {7, 8, 9}
    };
    
3. Multi-Dimensional Array
   
Example: 
  
    int arr[3][4][2];

    
Used in scientific computing, image processing, etc.


### 🔹 Basic Operations on Arrays

| Operation         | Description                         | Time Complexity         |
|------------------|-------------------------------------|-------------------------|
| Traversal        | Visit all elements                  | O(n)                    |
| Insertion        | Insert an element at a position     | O(n) (worst case)       |
| Deletion         | Remove an element                   | O(n) (worst case)       |
| Search           | Find an element                     | O(n) linear / O(log n)* |
| Update           | Change the value of an element      | O(1)                    |
| Access by Index  | Retrieve value at a given index     | O(1)                    |

\* Binary search only applies if the array is sorted.



🔹 Advantages of Arrays:

    Fast random access.

    Easy to implement and use.

    Useful for static, fixed-size collections.


🔹 Disadvantages:

    Fixed size (not dynamic).

    Insertion and deletion are expensive (need shifting).

    Memory wastage if not fully used.


🔹 Example in Python:

    arr = [10, 20, 30, 40, 50]
    print(arr[2])  # Output: 30

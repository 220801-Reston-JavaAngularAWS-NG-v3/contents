## Linear Search

**Contents**

**1. Searching**

**2. Linear Search**

2.1 Working of Linear search

2.2 Linear Search Algorithm

**3. Linear Search complexity**

3.1. Time Complexity

3.2 Space Complexity

**4. References**

## 1. Searching

-   Searching is the process of finding some particular element in the list.
-   If the element is present in the list, then the process is called successful, and the process returns the location of that element; otherwise, the search is called unsuccessful.
-   Two popular search methods are **Linear Search and Binary Search.**

## 2. Linear Search

-   Linear search is also called as **sequential search algorithm.**
-   It is the simplest searching algorithm.
-   Linear search helps to search for an element in the list in sequential order.
-   Sequential search is performed for each item, i.e. every item is checked, and if there is a match found, then that item is returned; else, the search continues until the end of data collection.
-   It is widely used to search an element from the unordered list, i.e., the list in which items are not sorted.

## 2.1 Working of Linear search

## ![Linear Search Animation](media/9ba362fd1cb889120f307638e2ecb8f4.gif)

## 2.2 Linear Search Algorithm

Linear Search (A: array of item, n: total no. of items ,x: item to be searched)

Step 1: Set i to 1

Step 2: if i \> n then go to step 7

Step 3: if A[i] = x then go to step 6

Step 4: Set i to i + 1

Step 5: Go to Step 2

Step 6: Print Element x Found at index i and go to step 8

Step 7: Print element not found

Step 8: Exit

## 3. Linear Search complexity

### 3.1. Time Complexity

**Best Case Complexity**

-   In Linear search, best case occurs when the element we are finding is at the first position of the array.
-   The best-case time complexity of linear search is **O(1).**

**Average Case Complexity**

-   The average case time complexity of linear search is **O(n).**

**Worst Case Complexity**

-   In Linear search, the worst case occurs when the element we are looking is present at the end of the array.
-   The worst-case in linear search could be when the target element is not present in the given array, and we have to traverse the entire array.
-   The worst-case time complexity of linear search is **O(n).**

The time complexity of linear search is **O(n)** because every element in the array is compared only once.

| **Case**         | **Time Complexity** |
|------------------|---------------------|
| **Best Case**    | O(1)                |
| **Average Case** | O(n)                |
| **Worst Case**   | O(n)                |

### 3.2 Space Complexity

-   The space complexity of linear search is O(1).

## 4. References

1.  https://www.javatpoint.com/linear-search

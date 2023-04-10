# What is binary search?
Binary search is an algorithm to find the position of a value in a **sorted** array.

# How does it work?
1. Compare the element in the middle of the array with the target value.
2. If the middle element matches the target value, return the position of the value.
3. If the middle element is less than target value, discard the first half of array. OR if the middle element is more than target value, discard the second half of the array.
4. Repeat until the middle element matches the target (return position of element) or if there are no more elements in the list (return null).


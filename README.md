# DS_Quick_Sort

It picks an element as pivot and partitions the given array around the picked pivot.
There are many different versions of Quick Sort that picks pivot in diffrent ways:
1. Always pick first element as pivot.
2. Always pick last element as pivot.
3. Pick a random element as pivot.
4. Pick median as pivot.

The key process in Quick Sort is partition ().
Target of partition is given a array and an element x of array as pivot, put x at its correct position in sorted array and put all smaller elements (greater than x) after x.
All this should be done in linear time. 

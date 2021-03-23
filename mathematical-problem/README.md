# Mathematical Problem

Create an API that accepts two values. The first value is an array of N integers. The second value is a positive integer. Convert the array to a two-dimensional array. The positive integer determines the length of each row. You can assume that N is a multiple of the row length. The API should find the sub-rectangle with the largest sum and return that sum. A sub-rectangle is a sub-array of size MxN located in the two-dimensional array.

## Example

For the values `[0, -2, -7, 0, 9, 2, -6, 2, -4, 1, -4, 1, -1, 8, 0, -2]` and `4` the two-dimensional array is:

```
 0 -2 -7  0
 9  2 -6  2
-4  1 -4  1
-1  8  0 -2
```

The sub-rectangle with largest sum is in the lower left-hand corner:

```
 9 2
-4 1
-1 8
```

The sum of the sub-rectangle's values is 15. This is the value your API should to return.

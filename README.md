# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over arrays.  The `bug.java` file contains the erroneous code, resulting in an `ArrayIndexOutOfBoundsException`. The corrected version is in `bugSolution.java`.

This type of error frequently occurs when the loop's termination condition is not carefully considered.  Always remember that array indices in Java are zero-based, and the last valid index is `array.length - 1`. 
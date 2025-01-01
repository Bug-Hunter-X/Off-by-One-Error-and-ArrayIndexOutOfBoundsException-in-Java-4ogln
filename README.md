# Off-by-One Error and ArrayIndexOutOfBoundsException in Java

This repository demonstrates a common Java error: an off-by-one error leading to an `ArrayIndexOutOfBoundsException`. The `Bug.java` file contains the erroneous code, while `BugSolution.java` provides the corrected version.

The error occurs because the loop condition `i <= arr.length` in the `Bug.java` causes the loop to iterate one time too many. Arrays are zero-indexed in Java, and the index ranges from 0 to length - 1. Thus, trying to access `arr[5]` in an array of size 5 causes an `ArrayIndexOutOfBoundsException`.

The solution demonstrates how to correct this type of error.
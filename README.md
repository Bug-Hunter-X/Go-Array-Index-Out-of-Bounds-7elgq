# Go Array Index Out of Bounds Error

This repository demonstrates a common error in Go: accessing an array index that is out of bounds.  This leads to a runtime panic, crashing the program. The solution shows how to avoid this error by correctly checking array bounds.

## Bug
The `bug.go` file contains code that attempts to access an index beyond the valid range of an array, resulting in a runtime panic.

## Solution
The `bugSolution.go` file demonstrates the corrected version, ensuring that the loop iterates within the valid array index range.
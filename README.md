==============================
README: Algorithm Solutions
==============================

This README explains the two problems solved in the accompanying file. Each problem is solved using structured pseudocode and follows all required instructions, including the use of arrays, loops, and procedure/function design.

------------------------------------------------------------
Problem 1: Sum of All Distinct Elements from Two Sets
------------------------------------------------------------

🔹 Description:
Given two sets of integers, find the sum of elements that are present in only one of the sets (i.e., distinct elements).

🔹 Example:
Set1 = [3, 1, 7, 9]
Set2 = [2, 4, 1, 9, 3]
Output = 13  (distinct elements: 2, 4, 7)

🔹 Approach:
- Arrays were used to represent the sets.
- A nested loop structure compares each element in Set1 to Set2 and vice versa.
- If an element is not found in the other set, it is added to the sum.
- The final result is the sum of all unique elements.

🔹 Requirements Met:
✅ Use of arrays  
✅ Use of nested loops  
✅ Proper variable initialization  
✅ Comparison logic


------------------------------------------------------------
Problem 2: Dot Product and Orthogonality Check
------------------------------------------------------------

🔹 Description:
You are given pairs of vectors. The task is to:
1. Compute their dot product using a procedure.
2. Determine if the vectors are orthogonal (dot product = 0).
3. Modify the algorithm to use a function instead of a procedure.

🔹 Approach:
- Vectors are represented using arrays.
- The dot product is calculated using a FOR loop.
- A PROCEDURE version and a FUNCTION version of the dot product were both implemented.
- A main algorithm calls the procedure or function and checks whether the result is zero (orthogonal vectors).

🔹 Example:
v1 = [1, 0, 0]
v2 = [0, 1, 0]
Dot product = 0 → Vectors are orthogonal.

🔹 Requirements Met:
✅ Use of arrays  
✅ Parameter passing (value and output)  
✅ Procedure and function implementation  
✅ Scalar dot product logic  
✅ Orthogonality condition (dot product == 0)


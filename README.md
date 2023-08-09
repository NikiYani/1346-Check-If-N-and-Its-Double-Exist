# 1346. Check If N and Its Double Exist

Given an array arr of integers, check if there exist two indices i and j such that : </br>

i != j </br>
0 <= i, j < arr.length </br>
arr[i] == 2 * arr[j] </br>

## Example 1:

Input: arr = [10,2,5,3] </br>
Output: true </br>
Explanation: For i = 0 and j = 2, arr[i] == 10 == 2 * 5 == 2 * arr[j] </br>

## Example 2:

Input: arr = [3,1,7,11] </br>
Output: false </br>
Explanation: There is no i and j that satisfy the conditions. </br>

## Constraints:

2 <= arr.length <= 500 </br>
-103 <= arr[i] <= 103 </br>


###	Easy
1.Write a program to reverse an array or string.

Examples:

Input  : arr[] = {1, 2, 3}
Output : arr[] = {3, 2, 1}

Input :  arr[] = {4, 5, 1, 2}
Output : arr[] = {2, 1, 5, 4}



2. Given an array of N integers, and an integer K, the task is to find the number of pairs of integers in the array whose sum is equal to K.

Examples:  

Input: arr[] = {1, 5, 7, -1}, K = 6
Output:  2
Explanation: Pairs with sum 6 are (1, 5) and (7, -1).

Input: arr[] = {1, 5, 7, -1, 5}, K = 6
Output:  3
Explanation: Pairs with sum 6 are (1, 5), (7, -1) & (1, 5).         

Input: arr[] = {1, 1, 1, 1}, K = 2
Output:  6
Explanation: Pairs with sum 2 are (1, 1), (1, 1), (1, 1), (1, 1), (1, 1).

Input: arr[] = {10, 12, 10, 15, -1, 7, 6, 5, 4, 2, 1, 1, 1}, K = 11
Output:  9
Explanation: Pairs with sum 11 are (10, 1), (10, 1), (10, 1), (12, -1), (10, 1), (10, 1), (10, 1), (7, 4), (6, 5).

3. Given an array arr[] of size N-1 with integers in the range of [1, N], the task is to find the missing number from the first N integers.

Note: There are no duplicates in the list.

Examples: 

Input: arr[] = {1, 2, 4, 6, 3, 7, 8}
Output: 5
Explanation: Here the size of the array is 7, so the range will be [1, 8]. The missing number between 1 to 8 is 5

Input: arr[] = {1, 2, 3, 5}, N = 5
Output: 4
Explanation: Here the size of the array is 4, so the range will be [1, 5]. The





 ###	Medium
							

1. Tower of Hanoi is a mathematical puzzle where we have three rods (A, B, and C) and N disks. Initially, all the disks are stacked in 
decreasing value of diameter i.e., the smallest disk is placed on the top and they are on rod A. The objective of the 
puzzle is to move the entire stack to another rod (here considered C), obeying the following simple rules: 

Only one disk can be moved at a time.
Each move consists of taking the upper disk from one of the stacks and placing it on top of another stack i.e. a disk can only be moved if it is the 
uppermost disk on a stack. No disk may be placed on top of a smaller disk.
Examples:

Input: 2
Output: Disk 1 moved from A to B
Disk 2 moved from A to C
Disk 1 moved from B to C

Input: 3
Output: Disk 1 moved from A to C
Disk 2 moved from A to B
Disk 1 moved from C to B
Disk 3 moved from A to C
Disk 1 moved from B to A
Disk 2 moved from B to C
Disk 1 moved from A to C

2. Write a program to make a calculator.

3. Find the factorial of a large number. 

Examples: 

Input: 100
Output: 933262154439441526816992388562667004-
         907159682643816214685929638952175999-
         932299156089414639761565182862536979-
         208272237582511852109168640000000000-
         00000000000000

Input: 50
Output: 3041409320171337804361260816606476884-
         4377641568960512000000000000

###	Hard

1. Given two numbers  a and b as interval range, the task is to find the prime numbers in between this interval.

Examples: 

Input : a = 1, b = 10
Output : 2, 3, 5, 7
Input : a = 10, b = 20
Output : 11, 13, 17, 19

2. Given a non-negative integer n. The problem is to reverse the bits of n and print the number obtained after reversing the bits. Note that the actual
binary representation of the number is being considered for reversing the bits, no leadings 0’s are being considered.
Examples : 
 

Input : 11
Output : 13
Explanation: (11)10 = (1011)2.
After reversing the bits we get:
(1101)2 = (13)10.

Input : 10
Output : 5
Explanation : (10)10 = (1010)2.
After reversing the bits we get:
(0101)2 = (101)2
        

3. Given an array of positive integers arr[] and an integer x, The task is to find all unique combinations in arr[] where the sum is equal to x. 
The same repeated number may be chosen from arr[] an unlimited number of times. Elements in a combination (a1, a2, …, ak) must be printed in non-descending 
order. (ie, a1 <= a2 <= … <= ak). If there is no combination possible print “Empty”.

Examples: 

Input: arr[] = 2, 4, 6, 8, x = 8
Output: 
[2, 2, 2, 2]
[2, 2, 4]
[2, 6]
[4, 4]
[8]
**Instructions** 

- Discuss and answer the following questions (Make sure to elaborate and justify your responses):
- If you would like to hand write or draw your answers, then scan or take a picture of a file called exercises.pdf or exercises.png and put it in this directory.


# Exercises

1. Explain: What do you think the Big-O (worst-case) complexity of the merge sort algorithm is and why? 

   n*log2(n).

2. Explain: What do you think the best-case complexity of the merge sort algorithm is and why?

   n. When it is the best-case, log(n) could be nearly equal to '1'.

3. Does merge sort require any additional storage beyond the original array? If so how much and why?

   Yes. at least one additional storage when we break down our array in to very tiny pieces.

4. How much time in Big-O does it take to merge all of the subarrays together? Explain or draw why?

   n. For the mergesort ,the BIG-o is n*log2(n). log2(n) levels where it break down our array into very tiny pieces,Then we make ‘n’ selections combining our array.Thus n*log2(n) complexity.



## Interview Prep (Optional +1% Bonus on assignment)

> **Rules** 
> 
> This is for bonus--and you may not ask TA's, Professors, or anyone about the question until after the homework is due.
> 
> Stratigically, you should not attempt this problem until you complete the rest of the homework (1% is less than 100% :) )

A bit ago a student asked me about this course, CS 5800, and other courses and how they may prepare you for interviews. I was recently talking to a Google, now Microsoft Engineer who told me that the reality is having a lot of LeetCode practice will help. LeetCode is a website to practice solving algorithmic challenges.

Let's finish off this exercise with a small C programming sample.

###

Solve the following: https://leetcode.com/problems/merge-sorted-array/

**Copy and paste your code into** a file in this directory called [challenge.c](./challenge.c) that solves the following problem.

**Given:** Two sorted integer arrays `nums1` and `nums2`, merge nums2 into nums1 as one sorted array and return the sorted array as a new array.

The number of elements initialized in `nums1` and `nums2` are *m* and *n* respectively.

Example 1:

```
Input: nums1 = [1,2,3,0,0,0], m = 3, nums2 = [2,5,6], n = 3
Output: [1,2,2,3,5,6]
```

Example 2:

```
Input: nums1 = [1], m = 1, nums2 = [], n = 0
Output: [1]
```

Constraints:

```
nums1.length == m + n
nums2.length == n
0 <= m, n <= 200
1 <= m + n <= 200
-109 <= nums1[i], nums2[i] <= 109
```

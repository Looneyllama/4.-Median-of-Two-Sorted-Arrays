# 4.-Median-of-Two-Sorted-Arrays

Thought this leet code problem was interesting and wanted to try it out. Still just trying to help better my knowledge with python.

This is one of the hardest problems I have ever done and it took me forever to conceptually grasp even with the editorial guide on leet code. 
My first go-through did not satisfy the big O notation, and it took me forever to figure out how to satisfy it. 

Overall I think I jumped into this level of coding while trying to learn python way too fast, but I did learn a lot from it.

LeetCode problem :

Given two sorted arrays nums1 and nums2 of size m and n respectively, return the median of the two sorted arrays.
The overall run time complexity should be O(log (m+n)).

Example 1:
Input: nums1 = [1,3], nums2 = [2]
Output: 2.00000
Explanation: merged array = [1,2,3] and median is 2.

Example 2:
Input: nums1 = [1,2], nums2 = [3,4]
Output: 2.50000
Explanation: merged array = [1,2,3,4] and median is (2 + 3) / 2 = 2.5.

Constraints:
nums1.length == m
nums2.length == n
0 <= m <= 1000
0 <= n <= 1000
1 <= m + n <= 2000
-106 <= nums1[i], nums2[i] <= 106

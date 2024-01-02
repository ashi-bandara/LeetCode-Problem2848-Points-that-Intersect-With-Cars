
# LeetCode Challenge D19

## Overview

Welcome to my LeetCode solution repository! This project addresses the coding challenge presented by [2848.  Points That Intersect With Cars](https://leetcode.com/problems/points-that-intersect-with-cars/). Below, you'll find details about the problem, my approach to solving it, and the implemented solution.

## Problem Statement
Given a  **0-indexed**  2D integer array  `nums`  representing the coordinates of the cars parking on a number line, for any index  `i`,  `nums[i] = [starti, endi]`  where  `starti`  is the starting point of the  `ith`  car and  `endi`  is the ending point of the  `ith`  car,  return  _the number of integer points on the line that are covered with  **any part**  of a car._

**Example**
>**Input:** nums = [[3,6],[1,5],[4,7]]
>
>**Output:** 7
>
>**Explanation:** All the points from 1 to 7 intersect at least one car, therefore the answer would be 7.

**Language Used**
> Java

**Difficulty**
> Easy

## Solution Overview

This Java solution utilizes a HashSet to efficiently count the number of unique integer points on a line covered by any part of a car. It iterates through the provided list of coordinates, which represent the starting and ending points of cars, and adds each integer within a car's range to the HashSet. By leveraging the HashSet's property of storing only unique elements, the algorithm avoids double counting and returns the total count of distinct integer points covered by any part of a car on the number line. This approach ensures a concise and effective solution to the given problem.

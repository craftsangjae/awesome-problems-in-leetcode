## LeetCode 문제 유형 정리

### Objective

> 코딩 면접을 준비하는 동안 풀었던 LeetCode들의 주요 문제 유형들을 정리 (<span style="color:green">easy</span>  ~ <span style="color:orange">medium</span> 수준). 
> 단순히 자료 구조 (예 : heap / BST / Linked List)의 기능을 구현하는 문제들은 배제



### 문제 유형 리스트 



#### Two sum : 숫자를 더했을 때, 특정 값이 되는 숫자의 조합 찾기 문제

* topic : `Pointer` , `Search`

1. [Two sum](https://leetcode.com/problems/two-sum/) : <span style="color:green">easy</span> 
2. [Sorted Two Sum ](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/) : <span style="color:green">easy</span> 
4. [3Sum](https://leetcode.com/problems/3sum/) : <span style="color:orange">medium</span> 
5. [3Sum Smaller](https://leetcode.com/problems/3sum-smaller/) : <span style="color:orange">medium</span> 
6. [4 Sum II](https://leetcode.com/problems/4sum-ii/description/) : <span style="color:orange">medium</span>
7. [Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/) :  <span style="color:orange">medium</span>



#### Anagam : 두 단어가 동일한 철자로 이루어져 있는지 확인하는 문제

* topic : `String`

1. [Valid Anagram](https://leetcode.com/problems/valid-anagram/) : <span style="color:green">easy</span> 

2. [Group Anagrams](https://leetcode.com/problems/group-anagrams/) : <span style="color:orange">medium</span> 



#### Palindrome : 단어가 대칭 꼴인지(like: 토마토, 오레오) 확인하는 문제

* topic : `String`

1. [Valid Palindrome](https://leetcode.com/problems/valid-palindrome/) : <span style="color:green">easy</span> 
2. [Palindrome Permutation](https://leetcode.com/problems/palindrome-permutation/) : <span style="color:green">easy</span> 
3. [Longest Palindromic Substring ](https://leetcode.com/problems/longest-palindromic-substring/) : <span style="color:orange">medium</span> 
4. [Palindromic Substrings](https://leetcode.com/problems/palindromic-substrings/) : <span style="color:orange">medium</span> 
5. [Shortest Palindrome](https://leetcode.com/problems/shortest-palindrome/) : <span style="color:red">hard</span>



#### number of cases : 순열과 조합

* topic : `Backtracking`

1. [Permutations](https://leetcode.com/problems/permutations/) :  <span style="color:orange">medium</span> 
2. [combinations](https://leetcode.com/problems/combinations/) :  <span style="color:orange">medium</span> 
3. [Combination Sum](https://leetcode.com/problems/combination-sum/) : <span style="color:orange">medium</span> 
4. [Unique Paths](https://leetcode.com/problems/unique-paths/) : <span style="color:orange">medium</span>



#### Sort : 행렬을 정렬하는 문제

1. [K closest Points to Origin](https://leetcode.com/problems/k-closest-points-to-origin/) :  <span style="color:orange">medium</span>
2. [Meeting Rooms II](https://leetcode.com/problems/meeting-rooms-ii/) : <span style="color:orange">medium</span>

3. [sort Colors](https://leetcode.com/problems/sort-colors/) : <span style="color:orange">medium</span>



#### Binary Search: 정렬된 행렬에서 값을 찾는 문제

1. [sqrt(x)](https://leetcode.com/problems/sqrtx/) :  <span style="color:green">easy</span> 
2. [Find First and Last Position of Element in Sorted Array](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/) : <span style="color:orange">medium</span>

3. [Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/) : <span style="color:orange">medium</span>



#### Parenthesis Valiadation : 문장 내 괄호가 올바르게 구성되어 있는지 확인하는 문제

* topic : `stack`

1. [Valid Parentheses](https://leetcode.com/problems/valid-parentheses/) : <span style="color:green">easy</span> 

2. [Generate Parentheses](https://leetcode.com/problems/generate-parentheses/) : <span style="color:orange">medium</span>
3. [Minimum Remove to Make Valid Parentheses](https://leetcode.com/problems/minimum-remove-to-make-valid-parentheses/) : <span style="color:orange">medium</span>
4. [Score of Parentheses](https://leetcode.com/problems/score-of-parentheses/) : <span style="color:orange">medium</span>

5. [Longest Valid Parentheses](https://leetcode.com/problems/longest-valid-parentheses/) : <span style="color:red">hard</span>



#### longest common subsequence : 최장 공통 부분 수열을 구하는 문제

* topic : `Dynamic Programming`

1. [Longest Common Subsequence](https://leetcode.com/problems/longest-common-subsequence/) : <span style="color:orange">medium</span>

2. [Longest Palindromic Subsequence](https://leetcode.com/problems/longest-palindromic-subsequence/) : <span style="color:orange">medium</span> 

3. [Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/) : <span style="color:orange">medium</span> 

4. [Maximal Square](https://leetcode.com/problems/maximal-square/) : <span style="color:orange">medium</span> 
6. [edit distance](https://leetcode.com/problems/edit-distance/) : <span style="color:red">hard</span>



#### Prefix Search : 접두사를 포함한 단어들을 찾는 문제

* topic : `Trie`

1. [Longest Common Prefix](https://leetcode.com/problems/longest-common-prefix/) : <span style="color:green">easy</span>

2. [Implement Prefix Tree](https://leetcode.com/problems/implement-trie-prefix-tree/) : <span style="color:orange">medium</span>
3. [Search Suggestions System](https://leetcode.com/problems/search-suggestions-system/) : <span style="color:orange">medium</span>



#### Coin Change : 동전 교환 문제

* topic : `Dynamic Programming`

1. [Coin Change](https://leetcode.com/problems/coin-change/) : <span style="color:orange">medium</span> 
2. [Coin Change 2](https://leetcode.com/problems/coin-change-2/) : <span style="color:orange">medium</span> 



#### Graph Exploration : Graph를 탐색하기

* topic : `Topological Sorted Order`

1. [Find the Town Judge](https://leetcode.com/problems/find-the-town-judge/) : <span style="color:green">easy</span>
2. [Course Schedule](https://leetcode.com/problems/course-schedule/) : <span style="color:orange">medium</span> 
3. [Number of Islands](https://leetcode.com/problems/number-of-islands/) :  <span style="color:orange">medium</span> 
4. [Course Schedule II](https://leetcode.com/problems/course-schedule-ii/) :  <span style="color:orange">medium</span> 



#### Maximum Benefit : 최대 이익이 되는 점 찾기

* Topic : `pointer`, `dynaimc programming`, `divide and conquer`

1. [Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/) : <span style="color:green">easy</span>
2. [Maximum Subarray](https://leetcode.com/problems/maximum-subarray/) : <span style="color:green">easy</span>
3. [Maximum sum Circular Subarray](https://leetcode.com/problems/maximum-sum-circular-subarray/) : <span style="color:orange">medium</span> 
4. [Container With Most Water](https://leetcode.com/problems/container-with-most-water/)  : <span style="color:orange">medium</span> 
5. [Maximum Product SubArray](https://leetcode.com/problems/maximum-product-subarray/) : <span style="color:orange">medium</span> 



#### Path Planning : 최소 경로 찾기 문제 

1. [Minimum Path Sum](https://leetcode.com/problems/minimum-path-sum/) : <span style="color:orange">medium</span> 

2. [Network Delay Time](https://leetcode.com/problems/network-delay-time/) : <span style="color:orange">medium</span> 


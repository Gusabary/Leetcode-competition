## Directory: Weekly Contest 115

In the directory are my codes in the [weekly contest 115](https://leetcode-cn.com/contest/weekly-contest-115).

### Files:

#### prison.cpp

the code for [question 1](https://leetcode-cn.com/contest/weekly-contest-115/problems/prison-cells-after-n-days/).

At first, I tried to use brute force, whose time complexity is O(n). But I exceeded the time limit.

Then I found that there existed a rule that the status of prisons will return to the one in the first day after a certain period so no matter how much the N is, it can be mapped into a relatively small range and the time complexity is O(1), maybe.

Finally, I passed the test cases. (But it cost me too much time.)

I have refactored the code now.

#### completeTree.cpp

the code for [question 2](https://leetcode-cn.com/contest/weekly-contest-115/problems/check-completeness-of-a-binary-tree/).

Pass, using BFS.

#### rank.png

the final rank.

##### Last-Modified date: 2018.12.22, 5 p.m.
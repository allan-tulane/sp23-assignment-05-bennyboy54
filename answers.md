# CMPS 2200 Assignment 5
## Answers

**Name:** Ben Russell


Place all written answers from `assignment-05.md` here for easier grading.





- **1a.**

v = value of largest coin less than N dollars
v(OPT([2^k],N))=max{v(2^k)+v(OPT([2^k−1],N−2^k)),v(OPT([2^k−1],N))}

- **1b.**
Work = O(2n-1)
Span = log2(n)


- **2a.**

Since there is an arbitrary number of denominations, there may not be a combination of coins that equals N dollars. If N = 7, and there is only one coin value v = 2, you could not exchange all of N dollars. The greedy algorithm cannot work optimally because the optimal solution may not be the largest value coin, given the arbitrary denominations.


- **2b.**
Arbitrary denominations k, vk is unpredictable
N = weight




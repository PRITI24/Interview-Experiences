# DSA
Listen to the question carefully because they give standard question in scenario.
# <br>
Q.1 Given an unsorted array, find the subarray range in which each element is maximum.
Input : [5,4,1,6,8,2]

Output : 5 -> (0,2)
4 -> (1,2)
1 -> (2,2)
6 -> (0,3)
8 -> (0,5)
2 -> (5,5)

# <br>

Similar to  
Word Search II (#212)

Q.2 You are a school teacher. You realise your students are cheating by hiding words in a 2D grid of letters, The word may start anywhere in the grid, and consecutive letters can be either immediately below or immediately to the right of the previous letter.
GIven a grid and a word, write a function that returns the location of the word in the grid as a list of coordinates.If there are multiple matches, return any one.

grid1 = [
    ['c', 'c', 't', 'n', 'a', 'x'],
    ['c', 'c', 'a', 't', 'n', 't'],
    ['a', 'c', 'n', 'n', 't', 't'],
    ['t', 'n', 'i', 'i', 'p', 'p'],
    ['a', 'o', 'o', 'o', 'a', 'a'],
    ['s', 'a', 'a', 'a', 'o', 'o'],
    ['k', 'a', 'i', 'o', 'k', 'i'],
]
word1 = "catnip" -- [(1,1,), (1,2), (1,3), (2,3), (3,3), (3,4)]
word2 = "cccc" -- [(0,0), (1,0), (1,1), (2,1)]
        OR [(0,0), (0,1), (1,1), (2,1)]
word3 = "s" -- [ (5,0) ]
word4 = "ant" -- [(0,4), (1,4), (2,4)] OR [(0,4), (1,4), (1,5)]


# <br>

Q.3 Given the root of a binary search tree and the lowest and highest boundaries as low and high, trim the tree so that all its element lies in [low, high]
Trimming the tree should not change the relative structure of the element that will remain in the tree
(i.e., any node's descendant should remain a descendant). It can be proven that there is a unique answer.

Input low = 1, high =4

Input 
                3
        0           5
    x       2   4       6
        1

Output
        3
    2
1

        3
    2       4
1           


# <br>

Q.4 Given a string path, which is an absolute path (starting with a slash '/') to a file or directory in a unix style format.
convert it  to the simplified canonical path. In a Unix-style file system,
a perid '.' refers to a current directory, a double period '..' refers to a directory up a level, and any multiple consecutive slashes (i.e. '//') are treated as a single slash '/'.
For this problem, any other format of periods such as a single slash '/'.
For this problem, any other format of periods such as '...' are treated as file/directory names.
The canonical path should have the following format:

* The path starts with a single slash '/'.
* Any two directories are separated by a single slash '/'.
* The path does not end with a trailling '/'.
* The path only contains the directories on the path from the root directory to the target file or directort(i.e.,)

return the simplified path.
Samples - 
*Input:* path = "/a/./b/../../c/" Output: "/c"
Input: path = "///home/../" Output "/"

Usually for modifiying string: like brackets or this consider stack


# <br>

Two Sum (#1)
Median of Two Sorted Arrays * (#4)
Longest Palindromic Substring (#5)
String to Integer (atoi) (#8)
Integer to Roman (#12)
Roman to Integer (#13)
Valid Parentheses (#20)
Merge K Sorted Lists (#23)
Valid Sudoku (#36)
Combination Sum (#39)
Permutations (#46)
Merge Intervals (#56)
Rotate List (#61)
Minimum Path Sum (#64)
Word Search (#79)
Validate Binary Search Tree(#98)
Same Tree ~ (#100)
Symmetric Tree ~ (#101)
Binary Tree Level Order Traversal (#102)
Convert Sorted List to Binary Search Tree (#109)
Populating Next Right Pointers in Each Node (#116)
Best Time to Buy and Sell Stock (#121)
Word Ladder II (#126)
Word Ladder (#127)
LRU Cache (#146)
Min Stack (#155)
Number of Islands (#200)
Course Schedule (#207)
Course Schedule II (#210)
Add and Search Word - Data structure design (#211)
Integer to English Words (#273)
Game of Life (#289)
Find Median from Data Stream (#295)
Longest Increasing Subsequence (#300)
Design Tic-Tac-Toe (#348)
Pacific Atlantic Water Flow (#417)
Minesweeper (#529)
Diameter of Binary Tree (#543)
Reorganize String (#767)


# LeetCode-leafSimilar

## Description 

Consider all the leaves of a binary tree, from left to right order, the values of those leaves form a leaf value sequence.



For example, in the given tree above, the leaf value sequence is (6, 7, 4, 9, 8).

Two binary trees are considered leaf-similar if their leaf value sequence is the same.

Return true if and only if the two given trees with head nodes root1 and root2 are leaf-similar.

![image](https://github.com/So47/LeetCode-leafSimilar/assets/39069270/06160197-ac7d-4621-890a-0d48a7fe2a40)


## Example 1:

![image](https://github.com/So47/LeetCode-leafSimilar/assets/39069270/f7a504bd-58c0-4627-a96e-205b740f4afd)


```
Input: root1 = [3,5,1,6,2,9,8,null,null,7,4], root2 = [3,5,1,6,7,4,2,null,null,null,null,null,null,9,8]
Output: true

```
## Example 2:

![image](https://github.com/So47/LeetCode-leafSimilar/assets/39069270/8d3dd4df-a20d-487a-96b7-3dee82623140)

```
Input: root1 = [1,2,3], root2 = [1,3,2]
Output: false
```

## Constraints:

* The number of nodes in each tree will be in the range [1, 200].
* Both of the given trees will have values in the range [0, 200].

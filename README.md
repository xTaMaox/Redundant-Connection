# Redundant-Connection

In this problem, a tree is an undirected graph that is connected and has no cycles.

You are given a graph that started as a tree with n nodes labeled from 1 to n, with one additional edge added. The added edge has two different vertices chosen from 1 to n, and was not an edge that already existed. The graph is represented as an array edges of length n where edges[i] = [ai, bi] indicates that there is an edge between nodes ai and bi in the graph.

Return an edge that can be removed so that the resulting graph is a tree of n nodes. If there are multiple answers, return the answer that occurs last in the input.

Example 1:

![reduntant1-1-graph](https://user-images.githubusercontent.com/88260025/222917424-837f1abb-2604-4b4d-afb7-d73e37f2cf01.jpg)

Input: edges = [[1,2],[1,3],[2,3]]
Output: [2,3]

Example 2:

![reduntant1-2-graph](https://user-images.githubusercontent.com/88260025/222917441-0bb765c4-792f-4b41-b203-1b5451901713.jpg)

Input: edges = [[1,2],[2,3],[3,4],[1,4],[1,5]]
Output: [1,4]
 

Constraints:

n == edges.length
3 <= n <= 1000
edges[i].length == 2
1 <= ai < bi <= edges.length
ai != bi

There are no repeated edges.
The given graph is connected.

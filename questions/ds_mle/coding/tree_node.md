## Tree Node

Use **Pandas** for this exercise

Each row of this table contains information about the id of a node and the id of its parent node in a tree.
The given structure is always a valid tree.

<pre>
Table: Tree
+-------------+------+----------------+
| Column Name | Type | Description    |
+-------------+------+----------------+
| id          | int  | Node ID        |
| p_id        | int  | Parent node ID |
+-------------+------+----------------+
</pre>

Each node in the tree can be one of three types:

* "Leaf": if the node is a leaf node.
* "Root": if the node is the root of the tree.
* "Inner": If the node is neither a leaf node nor a root node.

Write a solution to report the type of each node in the tree. Return the result table in any order.

Example:
Assume this tree:
<pre>
      1
    /   \
   2     3
  /  \     \
4     5     6
</pre>

Tree table:
<pre>
+----+------+
| id | p_id |
+----+------+
| 1  | null |
| 2  | 1    |
| 3  | 1    |
| 4  | 2    |
| 5  | 2    |
| 6  | 3    |
+----+------+
</pre>

Output:
<pre>
+----+-------+
| id | type  |
+----+-------+
| 1  | Root  |
| 2  | Inner |
| 3  | Inner |
| 4  | Leaf  |
| 5  | Leaf  |
| 6  | Leaf  |
+----+-------+
</pre>

Explanation:
* Node 1 is the root node because its parent node is null and it has child nodes 2 and 3.
* Node 2, 3 are inner nodes because they have parent node 1 and child node 4, 5 and 6.
* Nodes 4, 5 and 6 are leaf nodes because they have parent nodes and they do not have child nodes.

TreeNode is a separate class (custom data type) used to represent a node in a binary tree.

We don't use int because we need to store more than just the node's value. We also need access to its left and right children.
1. What does TreeNode look like?
In LeetCode, a binary tree node is generally defined like this:
public class TreeNode {
    int val;
    TreeNode left;
    TreeNode right;
}
Current should point to the root node (1), not just store its integer value.

That means we can do:
current.val;    // 1
current.left;   // Node 2
current.right;  // Node 3

yeah exactly for this backtrack are we gonna use stack or we have the parent vaue stored?
Great question! You're now getting into how recursion actually works internally. 🔥
Yes, a stack is used behind the scenes! It's called the Call Stack.
You don't need to create a stack manually. Java manages it for you whenever you use recursion.

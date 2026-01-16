# AVL Tree Implementation in C#

This project demonstrates a basic implementation of an **AVL Tree**, a self-balancing binary search tree, using C#.

## Features
- Insert nodes into the AVL Tree
- Delete nodes while maintaining balance
- Search for values
- Automatic rebalancing using rotations:
  - LL (Left-Left)
  - RR (Right-Right)
  - LR (Left-Right)
  - RL (Right-Left)
- In-order traversal display

## Notes
- Height is calculated recursively, which may affect performance for large trees.
- This implementation is intended for **educational purposes**.

## Technologies
- C#
- Console Application
- Visual Studio

## Example
```csharp
AVL tree = new AVL();
tree.Add(5);
tree.Add(3);
tree.Add(7);
tree.DisplayTree();
```

## Future Improvements
- Store node height to optimize performance
- Add unit tests
- Implement iterative traversal

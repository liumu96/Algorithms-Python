## Implementation of an auto-balanced binary tree!
```commandline
t = AVLtree()
t.insert(4)
print(str(t).replace(" \\n", "\\n"))
// 4
t.insert(2)
//  4
// 2 *
t.insert(3)
//  3
// 2 4
t.get_height()
// 2
t.del_node(3)
//  4
// 2 *
```
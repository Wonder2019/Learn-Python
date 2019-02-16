## 剑指offer 用 Python 实现

```
"""
self-defined python data structure
"""

class ListNode:
    def __init__(self, data):
        self.val = data
        self.next = None

class TreeNode:
    def __init__(self, data):
        self.val = data
        self.left = None
        self.right = None

class RandomListNode:
    def __init__(self, data):
        self.val = data
        self.next = None
        self.random = None

class TreeLinkedNode:
    def __init__(self, data):
        self.val = data
        self.left = None
        self.right = None
        self.next = None

"""
Methods for python data structure
"""

def print_list(head_node):
    vals = []
    while head_node:
        vals.append(head_node.val)
        head_node = head_node.next
    if len(vals)>0:
        print(" ".join(map(str, vals)))
    else:
        print("The node list is empty!")
        
```

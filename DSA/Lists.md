
### Data Structures & Algorithms - Lists, Arrays, Stacks and Heaps

"The first rule of data structures is: You do not confuse lists, arrays, stacks, and heaps. The second rule of data structures is: You do not confuse lists, arrays, stacks, and heaps."

---

### What are lists? 
- Straight forward - lists are a collection of items that can differ in type. For example we could have an integer and string combined into one collection and this could be termed a list

### What are arrays? 
- Arrays are a collection of items that are all of the same type

### What are stacks?
- Stacks are a collection of items that operate on a last in first out basis (LIFO basis)


### What are heaps?
- Heaps are a binary tree based structure. 


You may ask yourself - 'What is the difference betweeen a heap a  binary tree?'
- A heap has order. 
- The term min based heap refers to when the child nodes are less than or equal to the parent node. 
- The term max based heap refers to the child nodes being greater than or equal to the parent node
- Although heaps are sometime referred to as complete binary trees - because all levels of the treee are populated - nodes can have more than two chilren and therefore would not be defined as a strict binary tree.
  - In instances like this we can refer to the heaps as 'd-ary heap' - ternary heap (3 nodes), quaretnery heaps (4 nodes). By increasing the number of child nodes we can decrease the the height of the tree and therefore increase the speed.
  - That being said there with more child nodes mean more comparisons per level, so there will be a trade off (in specific use cases - test these)
  

What about the time complexity?
- Accesingeaps have a time complexity of O(1). Why? 

Real world applications of heaps include:
- Search engines 

[insert black and white image of heap]

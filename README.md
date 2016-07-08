# Algorithms Structures Concepts
Here I'll put my notes about basic programming (algorithms, structures, optimization)
These are mostly notes from my lecture: "Crackin the Coding Interview" by Gayle Laakmann Mcdowell



## Data Structures
* arrays and strings
    *  hashTables : maps keys to values for efficient lookup
    *  ArrayList & Resizable Arrays
        * In java ArrayList is the resizable array. The resizing factor is 2
        * amortized insertion runtime O(1)
    *  String Builder:
        * string that is optimized when we are adding and adding again data to the string  
* linked lists
* trees, tries, graphs
    * trees have a root node and some child nodes and cannot contain cycles
    * leaf=node without any child
    * binray tree != binary search tree
    * binary search tree: all left descendents <= n < all right descendents
    * balanced search tree = not terribly imbalanced, balanced enough to ensure O(log n) for insert and find
    * balanced trees: AVL and red-black trees
* stacks(FILO), queues(FIFO)
    * queues are used in breadth-first search and in implementing caches
* heaps
* vectors



## Algorithms
* breath - First Search
* Depth - First Search
* binary Search
* Merge Sort
* Quick Sort


## Concepts:
* Bit Manipulation
* Memory
* Recursion
* Dynamic Programming
* Big O time & Space
    * binray search: O(log N)
    * recursive functions with Multiple calls => O(branch ^ depth)
* Optimization acronymes
    * BUD: Buttlenecks, Unnecesary work, duplicated work
    * BCR: Best Conceivable Runtime != Best Case Runtime

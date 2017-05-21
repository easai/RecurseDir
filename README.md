# RecurseDir
RecurseDir is an abstract class that calls on the specified file directory recursively.

The term "recursive" means in computer science a function call that calls itself, in a way such that you can traverse a tree.  A tree contains nodes and leaves.  You would process the leaves and call the function again for nodes recursively. 

Consider traversing a directory structure.  File#list() does not list up all the subdirectories.  It is a matter of writing a function that calls itself, i.e., process the files and call the same function for directories. 

This procedure can be generalized.  Instead of writing the recursive call, here I wrote a class called RecurseDir.  This is an abstract class that calls on the specified file directory recursively. 

<a href="http://easaionprogramming.blogspot.com/2017/05/the-term-recursive-means-in-computer.html">Read more</a>

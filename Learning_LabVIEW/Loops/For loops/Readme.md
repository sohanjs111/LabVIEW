# Loops

## For Loops

Repeat a section of code a set number of times

## For Loops Vs While Loops

**While you know how many times a loop will need to execute before starting it, use a FOR loops**

Example: individually processing each element in an array

**While you do not know how many times a loop will need to execute, use a WHILE loops**

Example: processes that repeat until the user stops the program 

## Auto-Indexing Tunnels with For Loops
When you have small brackets inside the tunnels, auto-indexing is enabled. This is the default setting when you wire in or out of For Loops. If you enable auto-indexing on an array wired to a For Loop input terminal, LabVIEW sets the count terminal to the array size so you do not need to wire the count terminal.

### Build Arrays with For Loops
Auto-indexing is enabled by default for every array you wire to a For Loop because a common application of a For Loop is to process individual array elements. Disable auto-indexing if you do not need to process the elements of an array individually. When you disable auto-indexing input, the For Loop handles all the elements in the array at once, instead of handling an element per iteration. 

### Process Arrays with For Loops
Likewise, when you auto-index an array output tunnel, the output array receives a new element from every iteration of the loop. Therefore, auto-indexed output arrays are always equal in size to the number of iterations unless you select the conditional terminal mode. If you disable auto-indexing in the output tunnel, you receive the value of data from the last iteration, not the elements from every iteration.

*Scientific Approach:

Build mathematical models
do experiments to validate models


*Problem
Given a set of N objects (o-n)
*Union Command: connect two objects

Command model:

connected(0,7)
union(5,0)

*Doesn't state path, but tells if a path

Applications:

* Photo pixels
* Networks
* Social Networks
* Circut Elements
* Variable names
* Mettalic sites in a composite system


Convenient to name objects 0 to n
Use integers as array index
suppress details not relevant to union find

Properties of connections

*Reflecive: p is connected to p
*Symmetric: if p is connected to q then q is connected to p
*Transitive: if p is conected to q and q is connected to p then p is connected to r

Connected components maximal set of connected objects

Implementing

Java:

UF(int N)

Quick find in (x,y) if they have the same y they're connected
or in computer science terms id's

Initially each id is equal to its index
change id by union command

Code effeciency:

N^2 time (To slow)

Don't scale:

*Touch all words in approximately 1 second

10^18 opperations: 30+ years of computation time                                                  


Quick Union [Lazy Approach]:

Integer array id[] of size n
Each entry in array contains a reference to its parent in a tree
Parents point to themselves
 
Merging trees:
Only one value changes

Find: Check if p has the same root as q

Effectivity:

Quick union is also too slow:

Trees can get to tall 

Intalize = N union = N find = N

Improvement 1: Weighting

Weighted quick union

Modify quick-union to avoid tall tres 

Keep track of size of each tree 

balance by linking root

Smaller tree always goes below

No object is to far from root

Modify code to check sizes

Increment size changes

Depth of any node x is lg N

Tree can double log(n) times

Path compression- 
Make every node on path go to tree
id[i] = id[id[i]]

NO LINEAR TIME ALGORITHM FOR UNION FIND ALGORITHM

Image proccesing
Games(Go,Hex)
Least common ancestor

Percolation
*N by N gir
* Each site is open with probability p (or blocked with probability 1-p)
* System percolates if top and bottom are connected by open sites

Percolation value: 0.5964 

Model the probem
Bad models
Solved problems


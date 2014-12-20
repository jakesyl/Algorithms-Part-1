No answers (because screw cheating)

length = 9

starting:

0 1 2 3 4 5 6 7 8 9 
    
  2   4     8 9
  ^   ^       ^
  6   1       3
  ^   ^       ^
  0   7       5
  
Screwup

rule change first entry to second entrys

6 1 6 5 1 5 6 1 8 3

0   2 3 4 5     8 9 
          7       x
x=1,6

Questions:
(seed = 680749)
Which of the following id[] array(s) could be the result of running the weighted quick union
algorithm on a set of 10 items? Check all that apply.

Recall that our weighted quick union algorithm uses union by size (number of nodes)
(and not union by height).




3 3 3 3 7 7 3 3 3 5 
 
2 3 8 2 9 3 2 2 5 2 
 
5 1 2 5 4 5 6 7 8 5 
 
9 9 1 1 1 2 2 1 0 9 
 
4 1 9 8 8 5 8 0 1 4 


(seed = 473582)
Give the id[] array that results from the following sequence of 9 union
operations on a set of 10 items using the weighted quick-union algorithm from lecture.

    5-7 9-1 1-6 3-4 8-0 8-7 4-9 8-1 8-2 

Recall: when joining two trees of equal size, our weighted quick union convention is to
make the root of the second tree point to the root of the first tree. Also, our weighted
quick union algorithm uses union by size (number of nodes), not union by height.


(seed = 947192)
Give the id[] array that results from the following sequence of 6 union
operations on a set of 10 items using the quick-find algorithm.

    4-1 2-6 2-0 9-3 7-1 3-5 

Recall: our quick-find convention for the union operation p-q is to change id[p]
(and perhaps some other entries) but not id[q].
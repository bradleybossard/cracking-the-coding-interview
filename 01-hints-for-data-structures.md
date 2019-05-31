# Hints for Data Structures

* 1 1.2 Describe what it means for two strings to be permutations of each other. Now, look at that definition you provided.  Can you check the strings against that definition?

* 2 3.1 A stack is simply a data structure in which the most recently added elements are removed first.  Can you simulate a single stack using an array?  Remember that there are many possible solutions, and there are tradeoffs of each.

* 3 2.4 There are many solutino to this problem, most of which are equally optimal in runtime.  Some have shorter, cleaner code than others.  Can you brainstorm different solutions?

* 4 4.10 If T2 is a subtree of T1, how will ti's in-order traversal compare to T1's?  What about it's pre-order and post-order traversal?

* 5 2.6 A palindrome is something which is the same when written forwards and backwards.  What if you reversed the linked list?

* 6 4.12 Try simplifying the problem.  What if the path had to start at the root?

* 7 2.5 Of course, you could convert the linked lists to integers, compute the sum, and then convert it back toa new linked list.  If you did this in an interview, your interviewere would likely accept the answer, and then see if you could do this without converting it to a number and back.

* 8 2.2 What if you knew the linked list size?  What is the difference between finding the Kth-to-last element and finding the Xth element?

* 9 2.1 Have you tried a hash table?  You should be able to do this in a single pass of the linked list.

* 10 4.8 If each node has a link to its parent, we could leverage the approach from question 2.7 on page 95.  However, our interviewer might not let us make this assumption.

* 11 4.10 The in-order traversals won't tell us much.  After all, every binary search tree with the same values (regardless of structure) will have the same in-order traversal.  This is what in-order traversal means.  contents are in-order.  (And if it won't work in the specific case of a binary tree, then it certainly won't work for the general binary tree).  The pre-order traveral, however, is much more indicative.

*12 3.1 We could simulate three stacks in an array by just allocating the first third of the array to the first stack, the second thrid to the second stack, and the final third to the third stack.  One might actually be much bigger than the others, though.  Can we be more flexible with the divisions?

*13 2.6 Try using a stack.

14 4.12 Don't forget that paths could overlap.  For example, if you're looking for the sum 6, the apths 1-> 3 -> 2 and 1 -> 3 -> 2 -> 4 -> 6 -> 2 are both valid.

15 3.5 One way of sorting an array is to iterate through the array and insert each element into a new array in sorted order.  Can you do this with a stack?

16 4.8 The first common ancestor is the deepest node such that p and q are both descendents.  Think about how you might identify this node.

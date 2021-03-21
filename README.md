(1) For the bstsort, I have done it using inorder traversal
Time complexity = O(n).

(2) For finddepth function, I have performed level-order traversal using queues until I have found the element that we were looking for.
I have done this dequeuing the parents and enqueing the children till the element to be found has been reached. The I have emptied the queue.

(3) For the findheight function, I have performed level-order traversal using queues.
I have dequeued the parents and enqueued the children, till the  queue is empty.
Time complexity = O(n).

(4) For the isbst function, I have traversed each node using  recursion, checking at each step if the left child(if it exists) is less than the parent and right child(if it exists) is greater than the parent. 
Time complexity = O(n).

(5) The plot given by the 2D array is logarithmic in nature. This can also be inferred by putting various values of m and n in the function.
Time complexity = O( m(n^2) )   /*worst case= when the tree is in increasing or decreasing order( making it equivalent to a LinkedList) 

(6)For the inRange function, I have traversed each node recursively using inorder traversal, checking at each step if the node in consideration
falls in the range provided by the user.
Time complexity = O(n).

# Linked List

Implement a doubly linked list.

Like an array, a linked list is a simple linear data structure. Several 
common data types can be implemented using linked lists, like queues, 
stacks, and associative arrays.

A linked list is a collection of data elements called *nodes*. In a 
*singly linked list* each node holds a value and a link to the next node. 
In a *doubly linked list* each node also holds a link to the previous 
node.

You will write an implementation of a doubly linked list. Implement a 
Node to hold a value and pointers to the next and previous nodes. Then 
implement a List which holds references to the first and last node and 
offers an array-like interface for adding and removing items:

* `push` (*insert value at back*);
* `pop` (*remove value at back*);
* `shift` (*remove value at front*).
* `unshift` (*insert value at front*);

To keep your implementation simple, the tests will not cover error 
conditions. Specifically: `pop` or `shift` will never be called on an 
empty list.

If you want to know more about linked lists, check [Wikipedia](https://en.wikipedia.org/wiki/Linked_list).

## Resources

Remember to check out the Perl 6 [documentation](https://docs.perl6.org/) and
[resources](https://perl6.org/resources/) pages for information, tips, and
examples if you get stuck.

## Running the tests

There is a test script included with the exercise; a file with the extension
`.t`. You can run the test script for the exercise by executing the command
`prove . --exec=perl6` in the exercise directory. You can also add the `-v` flag
e.g. `prove . --exec=perl6 -v` to display all tests, including any optional
tests marked as 'TODO'.

## Source

Classic computer science topic

## Submitting Incomplete Solutions
It's possible to submit an incomplete solution so you can see how others have completed the exercise.

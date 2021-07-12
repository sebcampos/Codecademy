# Python Technical Interview

## Nodes
- Contain data which can be a variety of datatypes
- Contain links to other nodes. If a node has no links or they are all `null` you jave reached the end of the path you were following
- Can be orphaned if there are no existing links to them

## Linked lists
- Are comprised of Nodes
- The nodes contain a link to the next node (and also the previous node for bidirectional linked lists)
- Can be unidirectional or bidirectional
- Are a basic data structure, and form the basis for many other data structures
- Have a single head node, which serves as the first node in the list
- Require some maintenance in order toa dd or remove nodes
- The methods we used are examples and depend on the exact use case and/or programming language being used
- doubley linked lists, or bidirectional lists, are sequential lists with pointers to the next node as well as pointers to the previous node
- in a doubley linked lists added and removing nodes in the list is more complicated in the sense that we must update the nodes previous and next pointers. Not just one pointer


## Doubley linked lists
- Are comprised of nodes that contain links to the next and previous nodes
- Are bidriectional, meaning it can be traversed in both directions
- Have a pointer to a single head node which serves as the first node in the list
- have a pointer to a single tail node which serves as the last node in the list
- Require the pointers at the head of the list to be updated after addition to or removal of the head
- Require the pointers at the tail of the list to be updated after addition to or removal of the tail
- Require the pointers of the surrounding nodes to be updated after removal from the middle of the list

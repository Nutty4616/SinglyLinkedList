# Linked List Pseudocode 😥

### Pushing Pseudocode

- This function should accept a value.
- Create a new node using the value passed to the function.
- If there is no head property on the list, set the head and tail to be the newly created node.
- Otherwise set the next property on the tail to be the new node and set the tail property on the list to be newly created node.
- Increment the length by 1.
- Return the linked list.

### Popping Pseudocode

- If there are no node in the list, return undefined.
- Loop through the list until you reach the tail.
- Set the next property of the 2nd to last node to be null.
- Set the tail to be 2nd to last node.
- Decrement the length of the list by 1.
- Return the value of the node removed.

### Shifting Pseudocode

- If there are no nodes, return undefined.
- Store the current head property in a variable.
- Set the head property to be current head's next property.
- Decrement the length by 1.
- Return the value of the node removed.

### Unshifting Pseudocode

- This function should accept a value.
- Create a new node using the value passed to the function.
- If there is no head property on the list, set the head and tail to be newly created node.
- Set the head property on the list to be that newly created node.
- Increment the length of the list by 1.
- Return the linked list.

### Get Pseudocode

- This index should accept an index.
- If the index is less than zero or greater than or equal to the length of the list, return null.
- Loop through the list until you reach the index and return the node at that specific index.

### Set Pseudocode

- This function should accept an index and a value.
- Use get menthod to find the specific node.
- If the node is not found return false.
- Otherwise, set the value of that node to be the value passed to the function and return true.

### Insert Peseudocode

- If the index is less than zero or greater than or equal to the length of the list, return null.
- If the index is the same length, push a new node to the end of the list.
- If the index is 0, unshift a new node to the start of the list.
- Otherwise, using the get method, access the node at the index -1.
- Set the next property on that node to be the new node.
- Set the next property on the new node to be the previous next.
- increment the length.
- return true.

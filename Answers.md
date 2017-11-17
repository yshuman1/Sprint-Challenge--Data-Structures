## Answers
1. The order of insertions/removals for Stack is:
    - LIFO
   The order of insertions/removals for Stack is:
    - FIFO
2. The retreival time complexity for the following data structures:
   - **Linked List** O(n)
   - **Hash Table** O(1)
   - **Binary Search Trees** o(log n)
3. Some of the advantages to using a Hash Tables over an array in JavaScript are:
   - The advantage of using a hash table is that given the value you can calculate the hash you got had when inserting. That will give you an index to where your info is. The nice thing is that with hash tables that index you get will point you to the information. Worst case scenario, you have multiple items with the same hash and that means that the hash table index will give you a hash which points bucket. the bucket will is usually an array of info. Then you would just have to iterate over the array of that bucket to find the correct info. 

  With a regular array you would have to iterate over the array to find your value. This will, in most cases, be more expensive than using a hash table.  



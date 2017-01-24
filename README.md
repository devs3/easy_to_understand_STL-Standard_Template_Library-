# Easy_to_understand_STL_C++

CONTAINERS | usages
-----------|-------------
 vector | one-dimensional resizable array
 deque  | Double-ended queue
 forward_list | singly linked list
 list  | doubly linked list
 map  | associative array(name-value pairs)
 multimap | associative array(duplicate_Allowed)
 set | Set(duplicate_not_allowed)
 multiset | Set(duplicate_allowed)
 unordered_map | hashed associative array
 unordered_set | Hashed set
 queue | Queue
 stack | Stack
 array | one-dimensional array(fixed-size array)
 bitset | array of bool(0 or 1)
 


## Key points:
  
### Map:
  1. it uses balanced binary tree.
  2. used for hash table
 
               
##Change string to upper case letters:
    for(int i=0;<s.size();i++)
    { 
          char c=s[i];
          toupper(c);
    }
  
####input: helloworld
  
####output: HELLOWORLD
  
  
##change string to lower case letters:

    for(int i=0;i<s.size();i++)
    {
       char c=s[i];
       tolower(c);
    }

####input:HELLOWoRLd
####output:helloworld
 

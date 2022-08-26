## Hash Tables 
- a a key value pair
  - Key unique integer that is used for indexing the values
  - Value - data that are associated with keys.
  - In a hash table, a new index is processed using the keys. And, the element corresponding to that key is stored in the index. (Hashing)
- Hashing is used to find a particular object in a group of similar objects
- a hash code turns a key into an integer
 
 
 chainedHashSearch(T, k)
 <br>
  return T[h(k)]
  <br>
chainedHashInsert(T, x)
<br>
  T[h(x.key)] = x //insert at the head
  <br>
chainedHashDelete(T, x)
<br>
  T[h(x.key)] = NIL 

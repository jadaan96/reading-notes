# Hash Table

## What is a Hash Table:
A **hash table**, also known as a **hash map**, is a crucial data structure in computer science used for efficient storage and retrieval of key-value pairs. It's commonly used to implement structures like associative arrays, dictionaries, and maps.

## Why Hash Table:
Hash tables offer several compelling advantages that make them a popular choice for storing and retrieving data:

- **Fast Data Retrieval:** Hash tables provide an average-case constant-time complexity for essential operations like insertion, deletion, and retrieval. This means that regardless of the number of items in the hash table, these operations take roughly the same amount of time on average.

- **Key-Value Storage:** Hash tables are particularly well-suited for managing key-value pairs. This makes them perfect for scenarios where you need to associate unique keys with specific values, such as building dictionaries or implementing caching systems.

- **Efficient Searching:** Hash tables use a hash function to map keys to specific locations in memory. This enables direct access to values associated with keys, eliminating the need for searching through the entire dataset. As a result, hash tables can offer very fast access times.

- **Flexibility with Keys:** Hash tables can accommodate a wide range of data types as keys. Whether you're using strings, numbers, or even more complex objects, hash tables can efficiently manage the associations between keys and values.

## How to use Hash Table:
Using a hash table involves a few key operations:

1. **Creating a Hash Table and Adding Pairs:** To create a hash table, you typically initialize an empty data structure. Then, you can add key-value pairs to it. In languages like JavaScript, hash tables are often implemented using objects:

   ```javascript
   const hashTable = {
     "key1": "value1",
     "key2": "value2",
     // ...
   };

2.**ccessing Values: You can access values in a hash table by providing their corresponding keys. This is done using square brackets:**
   ```javascript

const value1 = hashTable["key1"];  // Retrieves "value1"
const value2 = hashTable["key2"];  // Retrieves "value2"
```


3- **Adding Pairs: To add a new key-value pair to the hash table, simply assign a value to a new or existing key:**
   ```javascript

> hashTable["key3"] = "value3";
```

4-**Deleting Pairs: If you want to remove a key-value pair from the hash table, you can use the delete keyword:**

   ```javascript

delete hashTable["key2"];
```
![HASH MAP](https://www.devlinkage.com/wp-content/uploads/2018/12/1380px-HASHTB12.svg.png)


# Hash-Map-
Hash map implementation in python 
Hash maps are indexed data structures. A hash map uses a hash function to compute an index with a key/value into an array of buckets.
Its value is mapped to the bucket with the corresponding index. The key is unique just like a currency note and these keys are immutable.

### In Python, dictionaries are examples of hash maps.

# The search complexity of a hash map is O(1).

# Working
* It takes key as an argument
* Than convert each char of the key into the ASCII Code and sum them all
* As we know that it's a bucket of the array, so we take modulusof  sum with the length of the bucket
* Result of the modulus is our hash known as index on which we store our value corresponding to that key 



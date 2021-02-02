# ordered-json


Maintaining key order within the JSON object makes it easier for testing and comparing JSON strings
The original JSON library uses a HashMap which can put the keys in any order.  
This uses LinkedHashMap to maintain key order.
For examples of the differences, see:
https://stackoverflow.com/questions/2889777/difference-between-hashmap-linkedhashmap-and-treemap

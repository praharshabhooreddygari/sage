building a tool that does the following process.
process: 
1. take in a prompt and convert it into tokens 
2. claissfy the types of tokens( ip, op, reasoning, cache) and maintain the count
3. understand and connect the probable costs taken for each
4. finally the total cost for the entered prompt 
output: table like 
+------------+-----------------+-----+
+    token      numberoftokens cost 
+    input
+    output 
+   reasoning 
+    cache 

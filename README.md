# RedisVsMySql
Comparing the speeds of Redis and MySql
Adding 1 Million records in Redis And MySql and comparing the speed.

output is 
time taken for redis to add 1000000 records is 22916 millis
time taken for mysql to add 1000000 records is 57353 millis


verdict
mysql takes double the time of redis, despite using preparedstatement to avoid string operation overhead

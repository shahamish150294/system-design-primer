## Estimation tips:

- 2 ^ 10 is 1024 ~ 1000 ~ 10^3
- 2 ^ 20 ~ 10 ^ 6 - 1 Million
- 2 ^ 30 ~ 10 ^ 9 - 1 Billion


- 1 kb - 1000 bytes 
- 1 mb - 1000 kb ~ 2 ^ 10 kb
- 1 gb - 1000 mb ~ 2 ^ 20 kb

- 1 day - 86400 sec ~ 10^5 seconds ~ 2 ^ 16 seconds

- How to calculate 2 ^ 32? Seperate 2 ^ 30 = 10 ^ 9 + 2^2 = 4 billion

## Non functional requirements tips:

Vocalize 3 things
1. Service is read heavy or write heavy
2. Service is expected to serve how many active users or how many requests per second?
3. Service should be highly available or consistent

## Caching 

- Use 80-20 logic to store data in cache. Normally server are 256 gb memory. So a 170 gb cache can be stored in it.
- Write policy?
- Cache eviction policy 
- Cache miss

# Caching

In modern applications facing performance problems and scaling limits, implementing a robust caching strategy can be transformational. Caching refers to the practice of storing frequently-accessed data in a faster storage tier (for example in-memory or in a distributed cache) so that subsequent requests avoid the latency of the primary data store.

Caching includes several dimensions to consider during the process like where to catch (cliet-side, server side ) and how to keep the cache consistent.

For my new project, the key benefits are reduce database loads better and better responsiveness for every requests of users.

Caching is not automatic like one must handle invalidations and consistency of it.


### References
1. AWS Database caching strategies [ https://docs.aws.amazon.com/whitepapers/latest/database-caching-strategies-using-redis/welcome.html ].
2. GeeksforGeeks, “Design Distributed Cache | System Design,” [ https://www.geeksforgeeks.org/design-distributed-cache-system-design/ ].
3. GeeksforGeeks, “Caching Strategies for API,” [ https://www.geeksforgeeks.org/system-design/caching-strategies-for-api/ ].

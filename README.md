A cache simulator which simulates 2 level caching. There is an L1 which is first-level cache which consist two parts L1D and L1I. L1D only holds data, on the other hand L1I only holds instructions. Also there is an L2 which is holds data and instruction. L2 is used when the specified data or instruction could not find in the L1D and L1I. If the requested data or instruction could not find both of the caches then the requested value will be found in the RAM, then it will be stored in the L1 and L2 cache.
The program can be run like this.

cache_simulator.o -L1s 5 -L1E 5 -L1b L2s 5 L2E 5 L2b 5 -t RAM.trace

You can specify the s, E, b of the cache with the given options above.

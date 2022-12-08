ACA-1 Project (Fall 2022) -
Cache Replacement Policy: Dynamic Insertion Policy via Set Duelling for High performance Cache.


Description of the topic:
To implement a cache controller that demonstrates an effective replacement policy called the
Dynamic Insertion Policy (DIP) which basically selects between LIP (Least Recently Used Insertion
Policy) and BIP (Bimodal Insertion Policy) based on what incurs fewer misses. To prevent
unnecessary storage, we used Set Duality DIP in this project. Without needing to change the
current cache design, this insertion policy aids in improving cache utilization by supporting
workloads that are LRU-friendly and LRU-averse by adding the least amount of circuitry.

Motivation:
The least recently used (LRU) policy is the replacement policy that is currently used the most. The
cache replacement policy is composed of the eviction policy and the insertion policy. The
outgoing data block is moved from the LRU position to the MRU position using the traditional
LRU technique. Despite its typically good performance, LRU still doesn't utilize caches for all
workloads. When used for applications with a high degree of locality, it performs well, but when
used for memory-intensive workloads with working sets that are larger than the size of the
available cache, it can display pathological behavior. The objective of our project is to create a
cache replacement policy with little hardware overhead and modifications that performs well for
workloads that are LRU-friendly and those that are LRU averse.

Methods to be used for evaluating the proposed idea:
• Using the Simple Scalar architecture to simulate the cache behavior that uses Set Dueling
DIP.
• We would vary the cache size and evaluate for significant improvements.
• Then compare and examine results based on several performance metrics like System
Performance like Speedup, IPC, Miss Rate and Hit rate. 

References:
[1] Moinuddin K. Qureshi Aamer Jaleel Yale N. Patt Simon C. Steely Jr. Joel Emer Adaptive
Insertion Policies for High Performance Caching ,2007.
[2] L. A. Belady. A study of replacement algorithms for a virtual-storage computer. In IBM
Systems journal, pages 78–101, 1966. 


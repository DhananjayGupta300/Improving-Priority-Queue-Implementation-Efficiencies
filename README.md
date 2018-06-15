# Improving-Priority-Queue-Implementation-Efficiencies

## Authors: Dhananjay Gupta (main author), Avani Kothari, Neetesh Gupta, Akshay Khandelwal

### ABSTRACT

This paper is an extension to our previous [work](http://dgupta.us/Efficiency-of-Priority-Queues/paper.pdf). Based on their running time efficiencies, earlier we
gave a comparative study of various available ways to implement priority queues. In this paper we
demonstrate a way to further improve their running time efficiency. We bring an introduction to memory
pooling and later describe how this concept may be used to improve the running time efficiency of
priority queues. Priority queues involve a large number of system calls during memory allocation. This
leads to extra time being required for node generation. However, this problem can be solved by using a
already available memory pool. For the purpose of memory allocation, a pre assigned pool of memory
could be used instead of making system calls on every node generation. This approach significantly
reduces the time frame of program execution. Although no changes in algorithm for priority queues have
been made, this approach works on the system level and is very beneficial when a very large number of
data nodes have to be created. Likely so, in our previous work [1] we had shown that we already have the
constant time executable algorithms available. So with this approach we go out of the box to improve the
efficiency of priority queues.

**Keyword:** - Priority queues, Memory pooling, efficiency, running time, complexity analysis.

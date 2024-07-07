# Performance
Performance has 2 aspects:
- Latency - how fast does the software execute a process
- Throughput - how many times can that process be executed in a particular timeframe, usually 1 second.
## Latency drives Throughput
Improvements to latency brings improvements to throughput; the reverse does not apply. Furthermore, any latency improvements will enhance the efforts of throughput improvements.

## Code level Improvements
Code level improvements are those improvements that you can only do by modifying the code, basically creating a new version of the code and going through the entire SDLC process. 
### Latency
#### Algorithms and Data Structure
Are you using the proper algorithms? Are you using the proper data structures? This is all about the Big O Notation.
#### Parallel Programming
Parallel Programming can increase latency but only in the case where the different activities can be performed concurrently or when disk access or network time is a factor. [Amdahl's Law](https://en.wikipedia.org/wiki/Amdahl%27s_law) is commonly used to gauge how much latency improvement one might get by parallelizing parts of the process. 
If parallel computing is used otherwise, it may lead to an increase in latency, due to context switching. This will happen if there aren't enough CPU cores to service the requests.
### Throughput

## Infrastructure level Improvements or Scaling
Also known as Scaling, it basically answers the question how much hardware can I throw at the software to improve its performance and in what way?

There are 2 ways, Vertical Scaling and Horizontal Scaling. Vertical Scaling means increasing the characteristics of the hardware: more RAM, more CPU...or better.
### Latency
#### Memory
#### CPU

### Throughput

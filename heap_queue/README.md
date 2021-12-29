# Optimizing-Python-Code 
# Heap Queue Module

## To Run The Files With Queue:
* Linux: Run in your Terminal: `ipython`
* Then: Run in your Terminal: `%run ptasks.py`
* Then: Run in your Terminal: `cases = gen_cases(1000)`
* Then: Run in your Terminal: `%timeit benchmark_pq(cases)`
* To see the time of every part of code: Run in your Terminal: `%prun benchmark_pq(cases)`

## To Run The Files With Heapq:
* Linux: Run in your Terminal: `ipython`
* Then: Run in your Terminal: `%run optimized_ptasks.py`
* Then: Run in your Terminal: `%timeit benchmark_pq(cases, cls=HPriorityQueue)`
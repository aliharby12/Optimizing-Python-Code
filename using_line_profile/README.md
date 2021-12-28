# Optimizing-Python-Code 
# Use cProfile Module and Snakeviz Package

## General Requirements
* Linux: Run in your Terminal: `sudo apt install python3-line-profiler`

## To Run The Files
* Linux: Run in your Terminal: `kernprof -l prof.py` then run `python3 -m line_profiler prof.py.lprof`

## If you using ipython
* remove @profile from login file
* Linux: Run in your Terminal: `ipython`
* Run in your Terminal: `%run -n prof.py` to load all functions
* Run in your Terminal: `cases = list(gen_cases(1000)`
* Run in your Terminal: `%load_ext line_profiler` to load line profiler extention
* Run in your Terminal: `%lprun -f login bench_login(cases)`

## Compare between two hashing algorithm
* Linux: Run in your ipython Terminal: `%run login.py`
* Run in your Terminal: `password = 'ali harby'`
* Run in your Terminal: `%run enc256.py`
* Run in your Terminal: `%timeit encrypt_passwd(password)` will be approximately 3.45 ms
* Run in your Terminal: `%timeit encrypt_passwd2(password)` will be approximately 1.03 µs
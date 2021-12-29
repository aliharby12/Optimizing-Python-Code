# Optimizing-Python-Code 
# Track Memory Allocation

## To Run The Files With Python3:
* Linux: Run in your Terminal: `python3 enc.py`

## Using memory_profile package:
* Install memory_profiler by using: `pip3 install memory_profiler`
* Linux: Run in your Terminal: `python3 -m memory_profiler sos.py`

## If you want to check if your memory will continuously grow
* remove the @profile decorator from the code and increase the number in sos file from 1_000_000 to 100_000_000
* Run in your Terminal: `mprof run sos.py` this will generate an output file
* Then install : matplotlib from: `pip3 install matplotlib`
* Then Run in your Terminal: `mprof plot the_out_put_file_name` will see th output in `output.png` file
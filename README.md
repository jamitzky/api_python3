# api_python3
api: python3 to J shared library

this is cloned from jsoftware/api_python3

# usage:
 - jbase.init(True)  # True (default) loads profile - False avoids
 - jbase.dor('i.2 3 4')    # run sentence and print output result
 - jbase.do(('+a.')        # run and return error code
 - jbase.getr()            # get last output result
 - jbase.do('abc=: i.2 3') # define abc
 - q= jbase.get('abc')     # get q as numpy array from J array 
 - jbase.set('ghi',23+q)   # set J array from numpy array
 - jbase.jdor('ghi')       # print array 
 - jbase.j()               # J repl - .... to exit

# types:
 python types supported: strings, bytes, numpy int64/float64 
 
 numpy arrays have shape
 
 json covers some other requirements
 
Developed with Python 3.6.4 (Anaconda) and J807.

Works with python kernel in Jupyiter.

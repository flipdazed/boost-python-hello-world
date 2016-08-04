A Most Basic Example of `boost-python`
======

The following example can be used by:

python setup.py build_ext --inplace

which will create the following `build/` directory and file:
    	
    build/
    hello_ext.so

This can be directly now called by python with:

    In [1]: import hello_ext
    
    In [2]: hello_ext.greet()
    Out[2]: 'Greetings!'
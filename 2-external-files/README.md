Another simple example `boost-python`
======

The following example showing how to include multiple external files as objects and is against build by:

    python setup.py build_ext --inplace

This can be directly now called by python as objects:

	In [1]: %paste
	import hello_ext
	hello_ext.greet()
	hello_ext.meet()
	
	## -- End pasted text --
	Out[1]: 'Nice to meet you from Boost!'
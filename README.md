Brainf*ck with tagged integers in rpython
===========

This is comparision of different [brainf*ck](http://en.wikipedia.org/wiki/Brainfuck) implementations in RPython.

It's based on the BF [example5.py](https://bitbucket.org/brownan/pypy-tutorial/src/tip/example5.py) of Andrew Brown's [JIT Tutorial](http://morepypy.blogspot.de/2011/04/tutorial-part-2-adding-jit.html).

It comes with three different integer variants:

	* Language default ints
	* A manually created boxed type (`W_SmallInteger')
	* A class derived from `pypy.rlib.objectmodel.UnboxedValue`

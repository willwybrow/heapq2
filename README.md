# heapq2
Port of Python3's heapq to Python2

##Intro
Original Python2.7 heapq module documentation can be found [here](https://docs.python.org/2/library/heapq.html).

The [documentation](https://docs.python.org/3.5/library/heapq.html) for Python3.5's heapq module lists two parameters added to the `merge` function in 3.5; **key** and **reverse**. I needed to use this functionality in my Python2.7 project so I have modified [this file](https://hg.python.org/cpython/file/3.5/Lib/heapq.py) for 2.7 compatibility.

##Usage
`import heapq2 as heapq`

Then use as heapq as documented above.

##Known Issues
I've only tried the `merge` function. 
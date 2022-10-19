# Cython: A First Look 

Often we write programs in Python for convenience, not for speed. When work becomes elevated to High Performance Computing (HPC) environments, speed once again becomes a concern. Cython is an extension of Python which allows functions to be compiled as C (or C++) and recover the significant performance trade-offs of Python. Cython achieves this by supporting calling C functions, declaring of type information, as well as providing access to C++ STL functionality. Popular packages and libraries that take advantage of Cython include: TensorFlow, OpenCV, NumPy, Pandas, and more. This webinar will cover a basic introduction to Cython, a demo translating vanilla Python into Cython, followed by a short demo of how to run Cython in our own Compute Canada HPC environments. Experience with Python will be expected, while familiarity with C/C++ and Jupyter notebooks will be helpful. Webinar material and code will be made available on GitHub for reference.

## Given as both a SHARCNET General Interest Webinar and Intro to ARC course material

This repository contains the slides and jupyter notebooks for my general interest webinar.

A completed version of the live demo can be found in `reference.ipynb`.

Inside of the `cc_use` directory are instructions for how to compile and use Cython on the Compute Canada systems outside of a notebook environment.

# Installing virtualenv on Ubuntu 14.04

*Steps to install Python2.7, Numpy, Scipy in virtual environment on Ubuntu 14.04*

1.   Install virtual environment

``sudo apt-get install python-virtualenv``

2.   Create a directory where you want to install Python

``mkdir ~/virtualenv_python2``

3.   Create virtal environment

``virtualenv virtualenv_python2/ --no-site-packages``

Option ``--no-site-packages`` will create separate isolated Python environment

4.   Activate virtual environment

``cd virtualenv_python2/bin``

`` source ./activate``

5.   Install Python2.7-dev

``sudo apt-get install python2.7-dev``

6.   Install numpy 

``pip install numpy``

7.   Install scipy

``sudo apt-get install libblas-dev liblapack-dev libatlas-base-dev gfortran``

``pip install scipy``

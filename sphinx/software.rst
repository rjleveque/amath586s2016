
.. _software:

=============================================================
Software for the course
=============================================================

Python
------

Please use Python for computing in this class. If you don't know Python but are
used to Matlab, this 
`Numpy for Matlab Users
<https://docs.scipy.org/doc/numpy-dev/user/numpy-for-matlab-users.html>`_
page might be very useful.

Some other resources:

- `AMath 583 notes on Python <http://faculty.washington.edu/rjl/classes/am583s2014/notes/index.html#python>`_
- `Python Tutorial <https://docs.python.org/2/tutorial/>`_
- Many other tutorials can be found online.

To use Python effectively you will need `numpy <http://www.scipy.org/>`_ 
(which supports arrays and
many mathematical operations), `matplotlib <http://matplotlib.org/>`_
(matlab-style plotting).  The
`IPython shell <http://ipython.org/>`_ and/or 
`Jupyter notebooks <http://jupyter.org>`_
are highly recommended for interactive work, see below.  

The `Anaconda Python Distribution <https://store.continuum.io/cshop/anaconda/>`_
is one easy way to get everything you need.  If you install this, you can
also then use the `conda package installer
<http://conda.pydata.org/docs/install/quick.html>`_ to install various
extensions easily.  

You should install Python 2.7 (not 3.x) to be compatible with what is used
in the notebooks posted for this this class.

Jupyter notebooks
-----------------

See http://jupyter.org for more information and documentation. 

The notebook platform is rapidly being improved but as a result how things
behave often depend on what version you have installed.  If you installed
the Anaconda Python, you can insure you have jupyter and  are up to date 
via the bash commands::

    conda install jupyter
    conda update jupyter

Then in a bash shell you should be able to execute::

    jupyter notebook

to start the notebook server.  You can then navigate your browser
to the address shown when the notebook starts, e.g. ::

    http://localhost:8888/tree

If you want to easily run notebooks without installing any software, you
might try :ref:`smc`.  



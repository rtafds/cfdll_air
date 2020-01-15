.. -*- mode: rst -*-

|PythonVersion|_

.. |PythonVersion| image:: https://img.shields.io/pypi/pyversions/scikit-learn.svg
.. _PythonVersion: https://img.shields.io/pypi/pyversions/scikit-learn.svg


cfdll_air
============
~~~~~~~~~~~~
For experiment design.
cfdll_air is a Python module for Approximate explanatory variable → objective variable with ML,DL or others and then,
the optimum objective variable is found by GA using the evaluation function made from the objective variable.

It is currently maintained by a rtafds.


Installation
------------
environment
~~~~~~~~~~~~
| Install go and direnv.
| Direnv can setting environment variable in sevaral directory.
```
    sudo apt install golang
    git clone https://github.com/direnv/direnv
    cd direnv
    sudo make install
    echo 'eval "$(direnv hook bash)"' >> ~/.bashrc
```
Make .envrc file.
```
    cd /path/to/cfdll_air/
    echo -n 'export PATH=$PWD/script:$PATH' >> .envrc
    source ~/.bashrc
    direnv allow
```

Dependencies
~~~~~~~~~~~~

Phepe requires:

- Python (>= 3.6)
- NumPy (>= 1.12.0)
- Pandas (>= 0.21.0)
- scikit-learn (>= 0.21)
- Pytorch

**cfdll_air 0.00 and later require Python 3.6 or newer.

cfdll_air plotting capabilities (i.e., functions start with "plot_"
and classes end with "Display") require Matplotlib (>= 1.5.1) or Plotly.
A few examples require pandas >= 0.18.0.

cfdll_air use non-linear correlation require minepy or PyHSICLasso.

User installation
~~~~~~~~~~~~~~~~~

environment
~~~~~~~~~~~~~~~~~



Changelog
---------


Development
-----------

Important links
~~~~~~~~~~~~~~~

Source code
~~~~~~~~~~~

You can check the latest sources with the command::

    git clone https://github.com/rtafds/cfdll_air.git

Contributing
~~~~~~~~~~~~

Testing
~~~~~~~

Simultaneously with installation, you can launch the test suite in the solution directory (you will need to have ``pytest`` >= 3.3.0 installed)::


Submitting a Pull Request
~~~~~~~~~~~~~~~~~~~~~~~~~

Pull Request welcome.


Project History
---------------

The project was started in 2019.

Help and Support
----------------

Documentation
~~~~~~~~~~~~~

Communication
~~~~~~~~~~~~~

- Mailing address: n.rtafds@gmail.com

Citation
~~~~~~~~

If you use cfdll_air in a scientific publication, we would appreciate citations: Is not yet.

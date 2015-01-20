=====
pydii
=====

Equilibrium defect concentrations and solute site preference in intermetallic compounds

Installation
------------
pydii requires pymatgen, sympy and monty packages. 

Source Code
------------
If not available already, use the following steps.

#. Install `git <http://git-scm.com>`_, if not already packaged with your system.

#. Download the pydii source code using the command::

    git clone https://github.com/pydii/pydii.git

Installation
------------
#. Navigate to pydii root directory::

    cd pydii

#. Install the code, using the command::

    python setup.py install

The command tries to obtain the required packages and their dependencies and install them automatically.
Access to root may be needed if ``virtualenv`` is not used.

# The package can be installed at non-standard locations using the command::

    python setup.py install --prefix PYDII_ROOTDIR

where PYDII_ROOTDIR is your choice of directory. In UNIX/Linux environments, 
add PYDII_ROOTDIR to PATH and PYTHONPATH variables by the following commands::
    
    export PATH=$PATH:PYDII_ROOTDIR
    export PYTHONPATH=$PYTHONPATH:PYDII_ROOTDIR    


Examples
--------

From the pydii, go to examples folder by typing::

    cd examples

The examples folder contains two subfolders for Al3V and NiAl intermetallic systems. For a description of
the compounds and how to generate the defect concentration profiles, refer to the manuscript. 




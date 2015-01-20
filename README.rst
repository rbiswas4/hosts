
If this does not work on default system. Install virtualenv (maybe using pip). After that.::

    virtualenv venv 
    source venv/bin/activate
    pip install -r pip-requirements.txt


To go back to default shell::

    deactivate



I will also need a set of utilities for reading file. I do the following::

    git clone https://github.com/rbiswas4/basicio
    cd basicio
    python setup.py install --user


I also set the location of the DES directory using setup.sh. This should be 
modified to point DESData to the directory containing SVAIGOLD

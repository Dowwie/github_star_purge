
![](logo.png)

# Github Star Purge

This is a Python script that will help you remove **all** of the stars from your github profile.

Its use is straightforward:

1. Create a Python3 virtual environment:  ``pyvenv my_venv``
2. Activate your newly created Python virtual environment:  ``source my_venv/bin/activate``
3. Install purge_github_stars and its Github API dependency:  ``python setup.py install``

The utility installs itself as an executable script from within the activated
virtual environment.  So, at this point you can run it from the command line: 

``purge_github_stars <username> <password>``

When you are finished removing your stars, simply type ``deactivate`` to 
exit the virtual environment.

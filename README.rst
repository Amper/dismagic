.. -*- rst -*-

dismagic
========

disassembling magic command for ipython
-------------------

.. image:: https://img.shields.io/pypi/v/dismagic.svg
    :target: https://pypi.python.org/pypi/dismagic
    :alt: Latest Version
.. image:: https://img.shields.io/pypi/dm/dismagic.svg
    :target: https://pypi.python.org/pypi/dismagic
    :alt: Downloads

Installation
------------
The package may be installed as follows: ::

    pip install dismagic

or in iPython shell:

    %install_ext https://raw.githubusercontent.com/Amper/dismagic/master/dismagic.py

After installation, the extension may be loaded within an IPython session
with ::

    %load_ext dismagic

Usage Examples
--------------
Disassembly a source:
    
    %dis x = a + b

    %dis "x = a + b"

    src = "x = a + b"

    %dis src

Disassembly an object:

    func = lambda x, y: x + y

    %dis func

Author
------
See the included AUTHORS.txt file for more information.

License
-------
This software is licensed under the
`BSD License <http://www.opensource.org/licenses/bsd-license.php>`_.
See the included LICENSE.txt file for more information.
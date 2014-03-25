PyGramETL: ETL in Python
=========================

This is a port of pygrametl for use in Python 3.

pygrametl (pronounced py-gram-e-t-l) is a Python framework which offers commonly used functionality for development of Extract-Transform-Load (ETL) processes.

pygrametl allows developers to code the ETL process in Python code, instead of drawing it using a graphical user interface. In order to facilitate this, pygrametl provides object oriented abstractions for commonly used operations, such as providing a uniform interface to data from various sources, performing data processing in parallel, maintaining slowly changing dimensions, or creating snowflake schemas.

Providing these abstractions as a framework instead of as an integrated application, allows pygrametl to seamlessly integrate with other Python code. This allows developers to quickly create ETL flows using the abstractions provided, and have direct access to a complete programming language if more complex operations are needed.

Checkout the documentation at http://people.cs.aau.dk/~chr/pygrametl/doc/index.html and the white paper on using pygrametl vs graphical ETL tools at http://dbtr.cs.aau.dk/DBPublications/DBTR-25.pdf

**Note:** The parallel capabilities of pygrametl are currently considered experimental and subject to change, and will in many cases give better results if Jython is used instead of CPython, due to its lack of GIL.

Compatibility
----------------

This version of pygrametl is compatible with Python 3.0+, a separate version for Python 2.X is available on PyPI and http://code.google.com/p/pygrametl/source/browse/#svn%2Ftrunk%2Fpygrametl

Installation
----------------

	clone this git repository and run
.. code-block
	python3 setup.py install


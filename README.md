 This is the README file for LING490 HW2
# LING506 President speech analysis

This is a python project developed for LIN490 to analyze the president's speeches.
Please make sure you have 1789-Washington, 2001-Bush, 2009-Obama, 2016-Trump txt
Please make sure at the beginning of the code (corpus root) you use the correct path to the texts.
For the sake of clarity, please reference to the excel file for summarized output
Functions and corresponding output are explained in comments within the python file.
## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.


#### Installing Python3

Go to https://www.python.org/downloads/ to install python for your machine

#### Installing required package: NLTK and matplotlib

Please refer to https://www.nltk.org/install.html for detailed instructions and requirement

For Mac/Unix

```
sudo pip install -U nltk
```

For Windows

```
pip install nltk
```

## Running the test

### In Terminal

```
python corpus.py
```

### In Python Interpreter

```
execfile('corpus.py')
```

##install matplotlib
`install <http://matplotlib.org/users/installing.html>`_ documentation. If you
think you may want to contribute to matplotlib, check out the `guide to
working with the source code
<http://matplotlib.org/devel/gitwash/index.html>`_.

Testing
=======

After installation, you can launch the test suite::

  pytest

Or from the Python interpreter::

  import matplotlib
  matplotlib.test()
  
 

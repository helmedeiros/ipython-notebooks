===========================================

My studies in numerical computing
=================================

Overview
========

Welcome to IPython. IPython is a command shell for interactive computing in multiple programming languages, originally developed for the Python programming language, that offers enhanced introspection, rich media, additional shell syntax, tab completion, and rich history.

Its full documentation is available [here](http://ipython.org/documentation.html);

Development installation
========================

First install [homebrew](http://brew.sh/).

Second verify the python version and update it:

```ssh
  # install a brewed python
  $ brew install python

  $ which python
  # should say /usr/local/bin/python

  $ echo $PATH
  # /usr/local/bin should appear in front of /usr/bin
```

Now you will install ipython and its packages:

```ssh
  $ pip install --upgrade "ipython[all]"
  $ pip install pyzmq
  $ pip install numpy
  $ pip install scipy
  $ pip install pandas
```

First steps
===========

Now, you can work on your local repo copy and run it from anywhere::

```ssh
  $ ipython notebook
```

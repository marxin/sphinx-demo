.. Demo documentation master file, created by
   sphinx-quickstart on Tue Mar  8 17:02:41 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Demo's documentation!
================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:


I'm a demo documentation page.

.. option:: -Wno-shift-overflow, -Wshift-overflow=n, -Wshift-overflow

  .. note::

    Default value is :option:`-Wno-shift-overflow`, :option:`-Wshift-overflow` is enabled by :option:`-Wall`.

  These options control warnings about left shift overflows.

  ``-Wshift-overflow=1``
    This is the warning level of :option:`-Wshift-overflow` and ...


.. option:: -Wno-shift-overflow2, -Wshift-overflow2=n (non-default), -Wshift-overflow2 (non-default)

  These options control warnings about left shift overflows.

  ``-Wshift-overflow2=1``
    This is the warning level of :option:`-Wshift-overflow2` and ...

.. option:: -Wno-shift-overflow3

  Default option value for :option:`-Wshift-overflow3`.

Code block:

.. code-block::

  gcc a.c
  ./a.out

And then there's a note:

.. note::

   I am a note!

And then there's something else.

Listing:

:samp:`{file}.cc` :samp:`{file}.cp` :samp:`{file}.cxx` :samp:`{file}.cpp` :samp:`{file}.CPP` :samp:`{file}.c++` :samp:`{file}.C`
  C++ source code that must be preprocessed.  Note that in :samp:`.cxx`,
  the last two letters must both be literally :samp:`x`.  Likewise,
  :samp:`.C` refers to a literal capital C.

:samp:`{file}.mm` :samp:`{file}.M`
  Objective-C++ source code that must be preprocessed.

:samp:`{file}.mii`
  Objective-C++ source code that should not be preprocessed.

:samp:`{file}.hh` :samp:`{file}.H` :samp:`{file}.hp` :samp:`{file}.hxx` :samp:`{file}.hpp` :samp:`{file}.HPP` :samp:`{file}.h++` :samp:`{file}.tcc`
  C++ header file to be turned into a precompiled header or Ada spec.

.. program:: make

.. option:: --verbose

Use verbose mode.

.. program:: None

Use :option:`--verbose` mode.

This works: :option:`--verbose <make --verbose>`

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

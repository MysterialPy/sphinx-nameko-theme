===================
Sphinx Nameko Theme
===================

A fork of `Sphinx Readable Theme <https://github.com/ignacysokolowski/sphinx-readable-theme>`_ for use in `Nameko <https://github.com/onefinestay/nameko>`_.


Installation and setup
======================


Install from PyPI::

    $ pip install sphinx-nameko-theme

And add this to your ``conf.py``:

.. code-block:: python

    import sphinx_nameko_theme

    html_theme_path = [sphinx_nameko_theme.get_html_theme_path()]
    html_theme = 'nameko'


License
=======

Sphinx Nameko Theme is licensed under the MIT license.


Changelog
=========

Version 0.0.1
-------------

First release.


Theme style
===========

.. index::
   single: Headings

Headings
--------

.. raw:: html

   <h1>H1: Lorem ipsum dolor sit amet</h1>

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

.. raw:: html

   <h2>H2: Lorem ipsum dolor sit amet</h2>

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

.. raw:: html

   <h3>H3: Lorem ipsum dolor sit amet</h3>

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

.. raw:: html

   <h4>H4: Lorem ipsum dolor sit amet</h4>

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

.. raw:: html

   <h5>H5: Lorem ipsum dolor sit amet</h5>

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

.. raw:: html

   <h6>H6: Lorem ipsum dolor sit amet</h6>

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.


.. index::
   single: Paragraphs

Paragraphs
----------

Duis **aute irure dolor** in `reprehenderit` in voluptate velit esse cillum
dolore eu fugiat nulla pariatur.  Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

`Lorem ipsum`_ dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua.  Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat.  Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur.  Excepteur sint occaecat `cupidatat`_
non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.



.. _footnotes:

Footnotes
---------

.. target-notes::

.. _Lorem ipsum: http://www.google.com
.. _`cupidatat`: http://docutils.sourceforge.net/rst.html


.. index::
   single: Tables

Tables
------

+----------------------+------------------------------------------------+
| Header row, column 1 | Header row, column 2                           |
+======================+================================================+
| body row 1           | Second column of row 1                         |
+----------------------+------------------------------------------------+
| body row 2           | Second column of row 2                         |
|                      |                                                |
|                      | Second line of paragraph                       |
+----------------------+------------------------------------------------+
| body row 3           | Unordered list:                                |
|                      |                                                |
|                      | * Second column of row 3                       |
|                      | * Second item in bullet list (row 3, column 2) |
+----------------------+------------------------------------------------+
| \                    | Row 4; column 1 will be empty                  |
+----------------------+------------------------------------------------+


.. index::
   single: Lists

Lists
-----

Unordered list
~~~~~~~~~~~~~~

* Lorem ipsum
* Dolor sit amet

  * Dolor
  * Sit
  * Amet

* Consectetur adipiscing elit

Ordered list
~~~~~~~~~~~~

#. Lorem ipsum
#. Dolor sit amet

   #. Dolor
   #. Sit
   #. Amet

#. Consectetur adipiscing elit

Definition Lists
~~~~~~~~~~~~~~~~

Lorem
    Lorem ipsum dolor sit amet.
Ipsum
    Ipsum dolor amet sit.
Dolor : classifier
    Dolor lorem ipsum.
Sit amet : classifier one : classifier two
    Sit amet consectetur adipiscing elit.


.. index::
   single: Topics

.. _topic:

Topics
------

.. topic:: Lorem ipsum

   Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
   tempor incididunt ut labore et dolore magna aliqua.

Sidebars
--------

.. sidebar:: Sidebar title

   Lorem ipsum dolor sit amet, nunc iaculis nulla molestie neque varius vulputate. Aenean hendrerit condimentum arcu ut porta.

   Nullam ac velit lobortis, tincidunt est varius, condimentum lectus. In eu sapien nec lacus interdum ultricies. Aliquam in luctus metus. Nulla mattis, sem quis fringilla pharetra, dui eros consequat velit, at bibendum Mauris sed velit non nibh aliquet mattis.

Mauris sed velit non nibh aliquet mattis. Nullam ac velit lobortis, tincidunt est varius, condimentum lectus. In eu sapien nec lacus interdum ultricies. Aliquam in luctus metus. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.


.. index::
   single: Admonitions

.. _admonitions:

Admonitions
-----------

.. admonition:: Admonition title

   Lorem ipsum dolor sit amet, consectetur adipisicing elit.

.. attention::
   Lorem ipsum dolor sit amet, consectetur adipisicing elit.

.. caution::
   Lorem ipsum dolor sit amet, consectetur adipisicing elit.

.. danger::
   Lorem ipsum dolor sit amet, consectetur adipisicing elit.

.. error::
   Lorem ipsum dolor sit amet, consectetur adipisicing elit.

.. hint::
   Lorem ipsum dolor sit amet, consectetur adipisicing elit.

.. important::
   Lorem ipsum dolor sit amet, consectetur adipisicing elit.

.. note::
   Lorem ipsum dolor sit amet, consectetur adipisicing elit.

.. seealso::

   Module :py:mod:`zipfile`
      Documentation of the :py:mod:`zipfile` standard module.

   `GNU tar manual, Basic Tar Format <http://link>`_
      Documentation for tar archive files, including GNU tar extensions.

.. tip::
   Lorem ipsum dolor sit amet, consectetur adipisicing elit.

.. warning::
   Lorem ipsum dolor sit amet, consectetur adipisicing elit.


.. index::
   single: Code

Code
----

.. code-block:: python

  """An example module docstring to show Pygments style."""

  # Some comment.

  import datetime
  from functools import partial

  number = 123
  word = 'foo'


  class ExampleClass(object):

      """An example class docstring to show Pygments style."""

      def __init__(self, arg1, arg2=None, *args, **kwargs):
          self.attr1 = attr1
          self.attr2 = attr2 or datetime.datetime.now()
          for arg in args:
              print('Argument: '.format(arg))
          for k, v in kwargs.iteritems():
              print('Keyword argument named {}: {}'.format(k, v))

      def call_method(self, arg):
          """An example method docstring."""
          if not isinstance(arg, int):
              raise ValueError('Only ints allowed.')
          self.attr1 = arg

      @property
      def example_property(self):
          """An example property docstring."""
          return self.attr1 * 2


  def example_function(arg1, arg2=None, *args, **kwargs):
      """An example function docstring to show Pygments style."""
      raise NotImplementedError()


.. index::
   single: Autodoc

Autodoc
~~~~~~~

.. automodule:: example

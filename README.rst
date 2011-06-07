=======================================
    Solarized (Dark) Pygments Style
=======================================

What Is It?
===========

This is a simple style for Pygments_ that is inspired by the `Solarized
project`_ by Ethan Schoonover.

This theme is for the dark background variant of Solarized. If you're looking
for a light background version, try `john2x's solarized-pygment`_.

.. _Pygments: http://pygments.org/
.. _Solarized project: http://ethanschoonover.com/solarized
.. _john2x's solarized-pygment: https://github.com/john2x/solarized-pygment

How Do I Use It?
================

This is just a ``Style``, not a plugin, so you need to add it to the ``styles``
directory of your Pygments distribution. Here is an excerpt from the
`relevant documentation`_:

    drop it into the styles subpackage of your Pygments distribution one style
    class per style, where the file name is the style name and the class name is
    ``StylenameClass``. For example, if your style should be called "mondrian",
    name the class MondrianStyle, put it into the file mondrian.py and this file
    into the pygments.styles subpackage directory.

.. _relevant documentation: http://pygments.org/docs/styles/

Acknowledgements
================

I built it mostly by adapting the various editor syntax coloring themes that
are available in the project proper, especially the TextMate theme.


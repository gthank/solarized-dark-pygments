# Solarized (Dark) Pygments Style

## What Is It?

This is a simple style for [Pygments][pygments_home] that is inspired by the
[Solarized project][solarized_home] by Ethan Schoonover.

This style is for the dark background variant of Solarized. If you're looking
for a light background version, try
[john2x's `solarized-pygment`][light_bg_pygments].

[pygments_home]: http://pygments.org/
[solarized_home]: http://ethanschoonover.com/solarized
[light_bg_pygments]: https://github.com/john2x/solarized-pygment

## How Do I Use It?

This is just a `Style`, not a plugin, so you need to add it to the `styles`
directory of your Pygments distribution. Here is an excerpt from the [relevant
documentation][style_docs]:

> drop it into the styles subpackage of your Pygments distribution one style
> class per style, where the file name is the style name and the class name is
> `StylenameClass`. For example, if your style should be called "mondrian",
> name the class `MondrianStyle`, put it into the file `mondrian.py` and this
> file into the `pygments.styles` subpackage directory.

[style_docs]: http://pygments.org/docs/styles/

## Acknowledgements

I built it mostly by adapting the various editor syntax coloring themes that
are available in the project proper, especially the TextMate theme.


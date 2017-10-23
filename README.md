# pyquotes

This is a quote style checker for use with pylama.

For now this is hard-coded check for:

* Double-quote style on doc strings, e.g. `"""Hello World."""`
* Single-quote style on everything else, e.g.
  `d['key'] = 'value {}:{}'.format('Hello', 42)`

## Installing

You need to install this one using pip from this directory:
`pip3 install --user --upgrade .`

If you are hacking on this module, you can also add the `-e` switch to that: 
`pip3 install --user --upgrade -e .`

## One day it would be nice to:

* Allow specifying style options
* Have a real, public github repo
* Be in PyPI (and so pip installable by name instead of fs location)

## License

This package is licensed under the MIT license. See `./LICENSE` for details.

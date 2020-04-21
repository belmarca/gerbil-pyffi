# Gerbil wrapper for Gambit's pyffi module

WIP.

## Installation

You first need to compile the `pyffi` gambit module available at
[github.com/feeley/pyffi](https://github.com/feeley/pyffi). Follow the
instructions and make sure it works or else it won't work in Gerbil either.

Note that you need an up-to-date Gambit and Gerbil.

Once `pyffi` is working, just `./build.ss` and then import the module in Gerbil:
`(import :feeley/pyffi)`. I kept the `feeley` prefix to mirror the Gambit
module's name.

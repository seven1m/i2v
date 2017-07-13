# i2v

This is a small Ruby script to convert a folder full of images into small movie files for use as a slideshow.

Vertical (portrait) photos will have pillarbox bars added to both sides.

We use this at our church for our wall-mounted screens.

## Installation

Just download the script and install ImageMagick.

Google the best way to install ImageMagick on your operating system. On a Mac with homebrew, I use `brew install imagemagick`.

## Usage

```
Usage: i2v [options] source destination
    -d, --duration                   seconds per video (default 4)
    -v, --verbose                    increase verbosity (more than one print extra info)
    -c, --cores                      number of simultaneous encodes to perform (default 8)
    -h, --help                       print this help
```

## Copyright

Copyright [Tim Morgan](https://timmorgan.org). Licensed MIT.

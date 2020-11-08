
![Honeybee](http://www.ladybug.tools/assets/img/honeybee.png)

[![Build Status](https://travis-ci.com/ladybug-tools/lbt-honeybee.svg?branch=master)](https://travis-ci.com/ladybug-tools/lbt-honeybee)

[![Python 2.7](https://img.shields.io/badge/python-2.7-green.svg)](https://www.python.org/downloads/release/python-270/) [![Python 3.6](https://img.shields.io/badge/python-3.6-blue.svg)](https://www.python.org/downloads/release/python-360/) [![IronPython](https://img.shields.io/badge/ironpython-2.7-red.svg)](https://github.com/IronLanguages/ironpython2/releases/tag/ipy-2.7.8/)

# lbt-honeybee

Collection of all Honeybee core Python libraries.

Note that this repository and corresponding Python package does not contain any
code and it simply exists to provide a shortcut for installing all of the honeybee
core libraries together.

## Included Honeybee Packages

Running `pip install lbt-honeybee` will result in the installation of the following
honeybee Python packages:

* [honeybee-core](https://github.com/ladybug-tools/honeybee-core)
* [honeybee-radiance](https://github.com/ladybug-tools/honeybee-radiance)
* [honeybee-radiance-folder](https://github.com/ladybug-tools/honeybee-radiance-folder)
* [honeybee-radiance-command](https://github.com/ladybug-tools/honeybee-radiance-command)
* [honeybee-energy](https://github.com/ladybug-tools/honeybee-energy)
* [honeybee-energy-standards](https://github.com/ladybug-tools/honeybee-energy-standards)

## All Ladybug Packages Are Also Included

Since honeybee uses ladybug, the following is also included:

* [lbt-ladybug](https://github.com/ladybug-tools/lbt-ladybug)

## The CLI option

Running `pip install lbt-honeybee[cli]` will ensure that all dependencies for the
command line interfaces (CLI) are also installed, including:

* [honeybee-schema](https://github.com/ladybug-tools/honeybee-schema)


![Honeybee](http://www.ladybug.tools/assets/img/honeybee.png)

[![Build Status](https://github.com/ladybug-tools/lbt-honeybee/workflows/CI/badge.svg)](https://github.com/ladybug-tools/lbt-honeybee/actions)

[![Python 3.7](https://img.shields.io/badge/python-3.7-blue.svg)](https://www.python.org/downloads/release/python-370/) [![Python 2.7](https://img.shields.io/badge/python-2.7-green.svg)](https://www.python.org/downloads/release/python-270/) [![IronPython](https://img.shields.io/badge/ironpython-2.7-red.svg)](https://github.com/IronLanguages/ironpython2/releases/tag/ipy-2.7.8/)

# lbt-honeybee

A collection of Honeybee core Python libraries and extensions.

Note that this repository and corresponding Python package does not contain any source
code and it simply exists to provide a shortcut for installing all of the honeybee
extensions together.

## Included Honeybee Extensions

Running `pip install lbt-honeybee -U` will result in the installation of the following
honeybee Python packages:

* [honeybee-radiance](https://github.com/ladybug-tools/honeybee-radiance)
* [honeybee-radiance-folder](https://github.com/ladybug-tools/honeybee-radiance-folder)
* [honeybee-radiance-command](https://github.com/ladybug-tools/honeybee-radiance-command)
* [honeybee-energy](https://github.com/ladybug-tools/honeybee-energy)
* [honeybee-energy-standards](https://github.com/ladybug-tools/honeybee-energy-standards)

## Included Honeybee Core Libraries

Since both honeybee extensions use the honeybee core libraries, the following
dependencies are also included:

* [honeybee-core](https://github.com/ladybug-tools/honeybee-core)
* [honeybee-schema](https://github.com/ladybug-tools/honeybee-schema)

## All Ladybug Packages Are Also Included

Since honeybee uses ladybug, the following is also included:

* [ladybug-geometry](https://github.com/ladybug-tools/ladybug-geometry)
* [ladybug-core](https://github.com/ladybug-tools/ladybug)
* [ladybug-comfort](https://github.com/ladybug-tools/ladybug-comfort)


![Honeybee](http://www.ladybug.tools/assets/img/honeybee.png)

[![Build Status](https://github.com/ladybug-tools/lbt-honeybee/actions/workflows/ci.yaml/badge.svg)](https://github.com/ladybug-tools/lbt-honeybee/actions)

[![Python 3.10](https://img.shields.io/badge/python-3.10-orange.svg)](https://www.python.org/downloads/release/python-3100/) [![Python 3.7](https://img.shields.io/badge/python-3.7-blue.svg)](https://www.python.org/downloads/release/python-370/) [![IronPython](https://img.shields.io/badge/ironpython-2.7-red.svg)](https://github.com/IronLanguages/ironpython2/releases/tag/ipy-2.7.8/)

# lbt-honeybee

A collection of Honeybee core Python libraries and Honeybee extensions.

Note that this Python package and corresponding repository does not contain any source
code and simply exists to provide a shortcut for installing all of the honeybee
extension packages together.

## Installation

```console
pip install lbt-honeybee -U
```

## Included Honeybee Extensions

Running `pip install lbt-honeybee -U` will result in the installation of the following
honeybee Python packages:

* [honeybee-display](https://github.com/ladybug-tools/honeybee-display)
* [honeybee-radiance-postprocess](https://github.com/ladybug-tools/honeybee-radiance-postprocess)
* [honeybee-radiance](https://github.com/ladybug-tools/honeybee-radiance)
* [honeybee-radiance-folder](https://github.com/ladybug-tools/honeybee-radiance-folder)
* [honeybee-radiance-command](https://github.com/ladybug-tools/honeybee-radiance-command)
* [honeybee-energy](https://github.com/ladybug-tools/honeybee-energy)
* [honeybee-energy-standards](https://github.com/ladybug-tools/honeybee-energy-standards)

## Included Honeybee Core Libraries

Since the honeybee extensions use the honeybee-core libraries, the following
dependencies are also included:

* [honeybee-core](https://github.com/ladybug-tools/honeybee-core)
* [honeybee-schema](https://github.com/ladybug-tools/honeybee-schema)

## Also Included (All Ladybug Packages)

Since honeybee uses ladybug, the following are also included (installed through [lbt-ladybug](https://github.com/ladybug-tools/lbt-ladybug)):

* [ladybug-geometry](https://github.com/ladybug-tools/ladybug-geometry)
* [ladybug-core](https://github.com/ladybug-tools/ladybug)
* [ladybug-comfort](https://github.com/ladybug-tools/ladybug-comfort)
* [ladybug-display](https://github.com/ladybug-tools/ladybug-display)

stations
========

[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/gersolar/stations?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[![License](https://img.shields.io/pypi/l/stations.svg)](https://pypi.python.org/pypi/stations/) [![Downloads](https://img.shields.io/pypi/dm/stations.svg)](https://pypi.python.org/pypi/stations/) [![Build Status](https://travis-ci.org/gersolar/stations.svg?branch=master)](https://travis-ci.org/gersolar/stations) [![Coverage Status](https://coveralls.io/repos/gersolar/stations/badge.png)](https://coveralls.io/r/gersolar/stations) [![Code Health](https://landscape.io/github/gersolar/stations/master/landscape.png)](https://landscape.io/github/gersolar/stations/master) [![PyPI version](https://badge.fury.io/py/stations.svg)](http://badge.fury.io/py/stations)
[![Supported Python versions](https://img.shields.io/pypi/pyversions/stations.svg)](https://pypi.python.org/pypi/stations/) [![Stories in Ready](https://badge.waffle.io/gersolar/stations.png?label=ready&title=Ready)](https://waffle.io/gersolar/stations)

Stations is a python service that provides you a sensed data database. It also, manage an inventory of the field devices (including sensors and calibrations).

Requirements
------------

If you want to deploy this repository with the default settings, on any GNU/Linux or OSX system you just need to execute the next bash command to setting up all the requirements (GNUMakefile should have been installed to this point).

	$ make deploy

Running
-------

To run the service use the command (the first time you should provide with a password for the **dev** username):

	$ make run

Now you can go to a browser on the same machine and use the address <http://localhost:8000/admin> to login to the service. You should complete the username field with "dev" and in the password field you should use your previously selected password.

About
-----

This software is developed by [GERSolar](http://www.gersol.unlu.edu.ar/). You can contact us to <gersolar.dev@gmail.com>.

AcmeFetch
=========

Version: #VERSION#

Date: #DATE#

AcmeFetch is a thin wrapper arount he ACME::Protocol library to fetch and maintain
ssl certificates using the the services of Let's Encrypt!

Setup
-----

Get a copy of AcmeFetch from https://github.com/oetiker/AcmeFetch/releases
and unpack it into your scratch directory and cd there.

    ./configure --prefix=$HOME/opt/acmefetch
    make

Configure will check if all requirements are met and give
hints on how to fix the situation if something is missing.

Any mising perl modules will be built and installed into the prefix
directory. Your system perl will NOT be affected by this.

To install the application, just run

    make install

Configuration
-------------

Take a look at the etc/acmefetch.cfg.dist file for inspiration.

Enjoy!

Tobias Oetiker <tobi@oetiker.ch>

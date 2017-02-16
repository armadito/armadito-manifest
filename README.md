# Armadito Manifest #

Armadito is an open-source antivirus.

This repository contains Armadito repo manifest.

Copyright (C) Teclib', 2015, 2016, 2017

## Installing repo ##

Download the Repo script:

    $ curl http://commondatastorage.googleapis.com/git-repo-downloads/repo > repo

Make it executable:

    $ chmod a+x repo

Move it on to your system path:

    $ sudo mv repo /usr/local/bin/

If it is correctly installed, you should see a Usage message when invoked
with the help flag.

    $ repo --help

## Get the sources ##

Create an emty directory:

	$ mkdir armadito
	$ cd armadito

Init the repo and sync:

	$ repo init -u git@github.com:armadito/armadito-manifest.git -b DEV
	$ repo sync


## Build the project (linux only) ##

	$ ./compile_all.sh

## More informations ##

Project home : http://www.teclib-edition.com/teclib-products/armadito-antivirus
 
See Online documentation at : http://armadito-av.readthedocs.io/en/latest/
 
License : LGPLv3 https://www.gnu.org/licenses/license-list.html#LGPLv3
 
IRC channel on freenode.net: #armadito
 
Mailing list: armadito-av-dev@gna.org
 
Follow @ArmaditoAV on twitter
 
Forum Armadito: https://forum.armadito.org/

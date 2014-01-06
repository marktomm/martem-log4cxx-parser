log4cxx-parser
==
A simple script to quickly make changes to 'Apache log4cxx' log-conf.xml file.
Apache log4cxx is a logging framework for C++.

I needed this bc our embedded devices didn't have perl with libs or any other
easy xml parsing tools.

In case of [[ (double bracket error) run script explicitly with bash, eg. 
'bash ./log4cxx -d' or change '#!/bin/sh' to '#!/bin/bash'
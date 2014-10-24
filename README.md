MyProxyClient
=============
This a pure* Python implementation of a client to the MyProxy Credential
Management Server (http://grid.ncsa.uiuc.edu/myproxy/)

*i.e. MyProxy C client libraries are not required for this package. 

It uses pyOpenSSL to make an SSL connection to the server following the
messaging interface as outlined in: http://grid.ncsa.uiuc.edu/myproxy/protocol/

The code is based on an original program myproxy_logon by Tom Uram of ANL.

Tests
-----
Unit test module with test files is in test/.  See the README in that directory.
This package has been tested on Linux Ubuntu Gutsy Gibbon, and Windows XP
Professional SP2

Documentation
-------------
Epydoc generated documentation is available in documentation/.  run the 
Makefile to regenerate if required.

Thanks
------
 * to OMII-UK for funding development of NDG Security over the past year (2007-
2008)
 * Tom Uram who wrote the myproxy_logon program on which this package is based.

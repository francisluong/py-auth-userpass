py-auth-userpass
================

Simple but not so secure username and password storage and retrieval

[![Build Status](https://travis-ci.org/francisluong/py-auth-userpass.svg?branch=master)](https://travis-ci.org/francisluong/py-auth-userpass)

Requirements
------------

 - PyYAML>=3.10
 - pycrypto>=2.6.1


Usage Example
-------------

```
from auth.userpass import Userpass
userpass = Userpass.load(path_to_userpass)
user = userpass.user()
password = userpass.passwd()
```

Example Userpass File
---------------------

See [example](https://github.com/francisluong/py-auth-userpass/blob/master/examples/yamlpass).

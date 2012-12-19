SSHVM
==============

SSHVM provides packages system like to RVM. There will be some situation when you have different keys to access different repositories.

Installation
------------

For installation just type in terminal:

``` shell
git clone git@bitbucket.org:sgsdev/sshvm.git ~/.sshvm
```

Add the following text to your .bashrc for scripting:

``` shell
PATH=$PATH:$HOME/.sshvm/script
```

Usage
-----

For get all possible usage commands type in terminal the following:

``` shell
sshvm help
```

Contributing
------------

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
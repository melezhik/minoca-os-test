# SYNOPSIS


Run system tests against running [Minoca OS](https://github.com/minoca/os)


# INSTALL

***NOTE:*** Installation and test run should be taken on server under Minoca OS.

Install Sparrow tool

    $ opkg update
    $ opkg install perl curl bash gcc make 
    $ ln -s /bin/env /usr/bin/env
    $ curl -L -k http://cpanmin.us -o /usr/bin/cpanm && chmod +x /usr/bin/cpanm
    $ cpanm --notest -q Sparrow
    $ sparrow index update

Install minoca-os-test plugin


    $ sparrow plg install minoc-os-test


# USAGE

Just run minoc-os-test plugin:


    $ sparrow plg run minoc-os-test

# See also

* [Sparrow](https://github.com/melezhik/sparrow)
* [Minoca OS](https://github.com/minoca/os)


# Author

[Alexey Melezhik](mailto:melezhik@gmail.com)    



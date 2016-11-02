# SYNOPSIS

Run some tests against running Minoca system



# INSTALL


Install Sparrow tool

    $ opkg update
    $ opkg install perl curl gcc make 
    $ ln -s /bin/env /usr/bin/env
    $ curl -L -k http://cpanmin.us -o /usr/bin/cpanm && chmod +x /usr/bin/cpanm
    $ cpanm --notest -q Sparrow
    $ sparrow index update

Install minoca-os-test plugin


    $ sparrow plg install minoc-os-test





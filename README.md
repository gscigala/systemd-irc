README
======

Systemd service starting IRC with an irssi client

Install
-------
Download the service and place it under `/etc/systemd/system` in your system.

Configuration
-------------
To enable the irc service at startup:

    # systemctl enable irc
    
To start the service:

    # systemctl start irc
    
You can check the status of the service by calling:

    $ systemctl status irc


For more information about systemd, please visit https://www.freedesktop.org/wiki/Software/systemd/

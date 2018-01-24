README
======

Systemd service starting IRC with an irssi client

Install
-------
Download the service and place it under `/etc/systemd/system` in your system.

Configuration
-------------
Enable and run the service with the following commands:

    # systemctl daemon-reload
    # systemctl enable irc
    # systemctl start irc

You can check the status of the service by calling

    $ systemctl status irc

# notify-ssh

A notify-send wrapper for use via remote shell. Display desktop notifications remotely.

Installation
------------

Install notify-ssh on the system in which you want the notifications to be displayed:

    sudo install notify-ssh /usr/local/bin

Usage
-----

Use `notify-ssh` exactly the same as you would use `notify-send`.

For example, enter the following from your SSH terminal session:

    notify-ssh --urgency=critical "Message Subject" "content..."

I personally use this to send alerts to my PC from my android phone and other devices. I've seen many posts of people struggling to make this happen reliably, so I figured I'd post the script for anyone to use.

*Note: It is only possible to send desktop notifications to the same account that you are logged into.*

License
-------

Copyright (c) 2015 Six (brbsix@gmail.com).

Licensed under the GPLv3 license.

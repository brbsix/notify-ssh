# notify-ssh

A notify-send wrapper for use via remote shells (SSH). Display desktop notifications remotely.


Installation
------------

On your Linux system running an SSH server... Copy notify-ssh to /usr/local/bin and mark as executable.

    sudo chmod a+x /usr/local/bin/notify-ssh

Usage
-----

Use notify-ssh exactly the same as you would use notify-send.

For example, enter the following from your SSH terminal session:

    notify-ssh --urgency=critical "Message Subject" "content..."

I personally use this to send alerts to my PC from my android phone. I'm sure there are plenty of other uses out there as well...

*Note: it is only possible to send desktop notifications to the same account that you are logged into from*

License
-------

Copyright (c) 2015 Six (brbsix@gmail.com).

Licensed under the GPLv3 license.

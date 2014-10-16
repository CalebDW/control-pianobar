[control-pianobar](http://bruce-connor.github.io/control-pianobar/)
================

We have a much nicer front page at
[http://bruce-connor.github.io/control-pianobar/](http://bruce-connor.github.io/control-pianobar/).
Go there instead!


Download option by CalebDW


To use this you need to have the package dsniff and sudo privaleges(to capture traffic on your interface).
You may need to install the package using this ppa ppa:evarlast/dsniff
This is because there is a timeout issue with urlsnarf exiting as soon as it runs.

In order to run this script I recommend adding "<user> ALL = NOPASSWD: /usr/sbin/urlsnarf" to the /etc/sudoers
This allows urlsnarf to be run as root without a password.

You will need to edit control-pianobar with your interface name if it's not "wlan0"
You may also edit the pianobar-notify if you wish to enable automatic downloads. All you need to do
is uncomment the specified lines.

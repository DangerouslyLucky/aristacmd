# aristacmd

This script is designed for Arista switches.
Attempting to recreate the functionality of ciscocmd without using expect, but rather pyeapi.

Oftentimes we wish to run a command or set of commands against multiple switches at the same time, without the burden of logging into each device individually. This is useful to generate reports from show commands or to configure a portion of the network at once.

Allows input of a single command or multiple commands (via textfile) to be run against a single switch or multiple switches (via textfile)

IMPORTANT: Commands entered must be the full and exact command the switch would expect. No shortened commands. Future functionality perhaps.

DISCLAIMER: Configuring a network via a script can be very dangerous business. Keep an eye on any errors and manually check everything on your devices if you choose to configure anything with this. Use at your own risk.

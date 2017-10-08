# Bad Chromecast Desktop

A good way to activate Chromecast desktop mirroring is to do some reverse-engineer and send proper packets to it. But I don't know how...

This shell script is a bad way to activate Chromecast desktop mirroring.


## Usage

1. Open up Google Chrome.
1. Type `./cast`
1. Watch your Google Chrome open up Chromecast desktop mirroring.


## Why

My desktop computer and my monitor are not physically closed enough to be connected with an HDMI cable. Therefore, the only way to show the screen is via Chromecast.

All I have to do after turnning on my computer is:

1. Open up Google Chrome blindly.
1. Type `cast` blindly (I added it in `$PATH`).

Then the screen will show up on my monitor.

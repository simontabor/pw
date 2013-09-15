# pw

[View it!](http://simontabor.com/labs/pw)

Password generator based on service name, master password and keyfile(s).

## Usage

Can be used either in-browser or as a `node-webkit` application.

Enter a service name (case and space insensitive), e.g. `Twitter`, then a password that you can remember. A nice secure password (SHA1 of everything together) is generated with every even letter being capitalised (as some fields require uppercase, lowercase and a number).

Keyfiles can be dropped onto the window, they'll be read and hashed up so you can make things even more secure.

## Notes

The `PW.app` should work on any Mac out of the box, theoretically the app.nw file can be run/packaged up by following the instructions over at [node-webkit](https://github.com/rogerwang/node-webkit)

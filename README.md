# rssht [![License](http://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE) [![Documentation Status](https://readthedocs.org/projects/rssht/badge/?version=latest)](http://rssht.readthedocs.org/en/latest/?badge=latest)

**rssht** creates a reverse SSH tunnel with optional SSH over HTTP.

In other words, it opens a port on a *remote client* (ie. the machine you want to connect from) forwarding to a port on the *local host* (ie. the machine you want to connect to) so that the remote client can connect to the local host even if the latter is not visible from the outside network (because it's behind some proxy, gateway, firewall or some NAT device).

## Documentation

An extensive documentation is available on [Read the Docs](http://rssht.readthedocs.org/).

## Reporting bugs

Please report bugs and feature requests on [Github](https://github.com/Arkanosis/rssht/issues).

## License

rssht is copyright (C) 2015 Jérémie Roquet <jroquet@arkanosis.net> and licensed under the MIT license.

## Related projects

openssh, autossh, corkscrew, httptunnel

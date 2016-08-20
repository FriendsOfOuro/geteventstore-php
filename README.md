GetEventStore PHP client
=====================

PHP client for [EventStore 3.x HTTP API](http://docs.geteventstore.com/http-api/latest)

This is the metapackage, to see the actual code https://github.com/FriendsOfOuro/php-eventstore-client

[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/dbellettini/geteventstore-php?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

[![Latest Stable Version](https://poser.pugx.org/FriendsOfOuro/eventstore-client/v/stable.svg)](https://packagist.org/packages/dbellettini/eventstore-client) [![Total Downloads](https://poser.pugx.org/dbellettini/eventstore-client/downloads.svg)](https://packagist.org/packages/dbellettini/eventstore-client) [![Latest Unstable Version](https://poser.pugx.org/dbellettini/eventstore-client/v/unstable.svg)](https://packagist.org/packages/dbellettini/eventstore-client) [![License](https://poser.pugx.org/dbellettini/eventstore-client/license.svg)](https://packagist.org/packages/dbellettini/eventstore-client)

[![Build Status](https://travis-ci.org/FriendsOfOuro/geteventstore-php.svg?branch=master)](https://travis-ci.org/FriendsOfOuro/geteventstore-php)
[![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/FriendsOfOuro/geteventstore-php.svg)](http://isitmaintained.com/project/FriendsOfOuro/geteventstore-php "Average time to resolve an issue")
[![Percentage of issues still open](http://isitmaintained.com/badge/open/FriendsOfOuro/geteventstore-php.svg)](http://isitmaintained.com/project/FriendsOfOuro/geteventstore-php "Percentage of issues still open")

Roadmap
-------

Development started in April 2014. Not ready for production use. Things may break between versions.

API can currently:

- Read from streams
- Navigate streams
- Read events
- Write to streams
- Delete streams

Integrations
------------
* [EventStore Client Bundle](https://github.com/FriendsOfOuro/eventstore-client-bundle) integrates this project in Symfony 2
* [Broadway Integration](https://github.com/FriendsOfOuro/broadway-eventstore)

Documentation
-------------
See our [wiki](https://github.com/dbellettini/geteventstore-php/wiki)

Contributing
------------

See [CONTRIBUTING](/CONTRIBUTING.md) file.


License
-------

EventStore PHP Client is released under the MIT License. See the bundled
[LICENSE](/LICENSE) file for details.

See also
--------
If you are looking for the TCP implementation you may be interested in [madkom/event-store-client](https://github.com/madkom/event-store-client)

Disclaimer
----------

This project is not endorsed by Event Store LLP.

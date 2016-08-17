GetEventStore PHP client
=====================

PHP client for [EventStore 3.x HTTP API](http://docs.geteventstore.com/http-api/latest)

This is the metapackage, to see the actual code https://github.com/dbellettini/php-eventstore-client

[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/dbellettini/geteventstore-php?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

[![Latest Stable Version](https://poser.pugx.org/dbellettini/eventstore-client/v/stable.svg)](https://packagist.org/packages/dbellettini/eventstore-client) [![Total Downloads](https://poser.pugx.org/dbellettini/eventstore-client/downloads.svg)](https://packagist.org/packages/dbellettini/eventstore-client) [![Latest Unstable Version](https://poser.pugx.org/dbellettini/eventstore-client/v/unstable.svg)](https://packagist.org/packages/dbellettini/eventstore-client) [![License](https://poser.pugx.org/dbellettini/eventstore-client/license.svg)](https://packagist.org/packages/dbellettini/eventstore-client)

[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/dbellettini/geteventstore-php/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/dbellettini/geteventstore-php/?branch=master)
[![Code Coverage](https://scrutinizer-ci.com/g/dbellettini/geteventstore-php/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/dbellettini/geteventstore-php/?branch=master)
[![Build Status](https://travis-ci.org/dbellettini/geteventstore-php.svg?branch=master)](https://travis-ci.org/dbellettini/geteventstore-php)
[![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/dbellettini/geteventstore-php.svg)](http://isitmaintained.com/project/dbellettini/geteventstore-php "Average time to resolve an issue")
[![Percentage of issues still open](http://isitmaintained.com/badge/open/dbellettini/geteventstore-php.svg)](http://isitmaintained.com/project/dbellettini/geteventstore-php "Percentage of issues still open")

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
* [EventStore Client Bundle](https://github.com/dbellettini/eventstore-client-bundle) integrates this project in Symfony 2
* [Broadway Integration](https://github.com/dbellettini/broadway-eventstore)

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

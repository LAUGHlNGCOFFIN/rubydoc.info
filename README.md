RubyDoc.info: YARD Doc Server
===============================

RubyDoc.info is the next generation Ruby doc server, replacing
[http://rdoc.info](http://rdoc.info) and
[http://yardoc.org/docs](http://yardoc.org/docs).
This doc server uses YARD to generate project documentation on the fly, for
both published RubyGems as well as GitHub projects.

The public doc server is hosted at [http://www.rubydoc.info](http://www.rubydoc.info)

Getting Started
---------------

This site is a public service and is community-supported. Patches and
enhancements are welcome.

Running the doc server locally is easy:

```
$ git clone git://github.com/lsegal/rubydoc.info
$ cd rubydoc.info
$ bundle install
$ rake gems:update
$ rackup config.ru
```

Thanks
------

RubyDoc.info was created by Loren Segal (YARD) and Nick Plante (rdoc.info) and is a project of DOCMETA, LLC.
Additional help was provided by [our friendly developer community](https://github.com/lsegal/rubydoc.info/graphs/contributors).
Pull requests welcome!

(c) 2018 DOCMETA LLC. This code is distributed under the MIT license.


NanoSpec.go
======

NanoSpec.go is a *minimal* [BDD](http://dannorth.net/introducing-bdd)-style testing framework for the [Go programming language](http://golang.org/). Its purpose is to *bootstrap* other more advanced testing frameworks, while still enabling the writing of [specification-style](http://blog.orfjackal.net/2010/02/three-styles-of-naming-tests.html) tests. For use in regular programs [GoSpec](http://github.com/orfjackal/gospec) is recommended.

Source code is available at <http://github.com/orfjackal/nanospec.go>

For discussion, use the [golang-nuts mailing list](http://groups.google.com/group/golang-nuts). You may also contact NanoSpec.go's developer, [Esko Luontola](http://github.com/orfjackal), by email.


Quick Start
-----------

Have a look at [nanospec_example_test.go] and how [GoSpec](http://github.com/orfjackal/gospec) uses this framework and read the source code. This framework is not meant for beginners, but for testing framework developers. This can be used as a library in other testing frameworks for Go, or as an reference implementation of how to create a similar testing framework for some other language.

[nanospec_example_test.go]: https://github.com/orfjackal/nanospec.go/blob/master/src/nanospec/nanospec_example_test.go


Version History
---------------

**1.x.x (2012-xx-xx)**

- ...

**1.0.11 (2012-02-14)**

- Upgraded to Go weekly.2012-02-07

**1.0.10 (2011-11-04)**

- Upgraded to Go weekly.2011-11-02

**1.0.9 (2011-10-13)**

- Upgraded to Go weekly.2011-09-01

**1.0.8 (2011-07-08)**

- Upgraded to Go weekly.2011-07-07

**1.0.7 (2011-06-27)**

- Upgraded to Go weekly.2011-06-23

**1.0.6 (2011-04-30)**

- Upgraded to Go weekly.2011-04-27

**1.0.5 (2011-04-15)**

- Upgraded to Go weekly.2011-04-13

**1.0.4 (2010-10-01)**

- Upgraded to Go release.2010-09-29

**1.0.3 (2010-09-06)**

- Upgraded to Go release.2010-08-25

**1.0.2 (2010-07-20)**

- Upgraded to Go release.2010-07-14

**1.0.1 (2010-05-11)**

- Changed reporting format: show full file paths, have expected and actual values on different lines

**1.0.0 (2010-04-29)**

- Initial release


License
-------

Copyright © 2010 Esko Luontola <<http://www.orfjackal.net>>  
This software is released under the Apache License 2.0.  
The license text is at <http://www.apache.org/licenses/LICENSE-2.0>

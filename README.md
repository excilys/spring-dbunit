# spring-dbunit 1.1.12

## What for?

spring-dbunit provides [DBUnit](http://www.dbunit.org) add-ons for Spring.

It allows you to easily insert and cleanup test data into the database of your choice.

Use cases examples :

* "pseudo" unit tests on a DAO layer, with an in-memory database like [HSQLDB](http://hsqldb.org) or [H2](http://www.h2database.com) and a schema automatically created with Hibernate hibernate.hbm2ddl.auto=create-drop.
* GUI integration tests with Selenium, with a persistent database and an existing schema.
* application prototype development, with data reloaded on application startup

## Documentation

Have a look at the Wiki for modules documentation :

* [Test support](https://github.com/excilys/spring-dbunit/wiki/spring-dbunit-test-module)
* [Servlet support](https://github.com/excilys/spring-dbunit/wiki/spring-dbunit-servlet-module)

## Where are the binaries?

See [Maven](https://github.com/excilys/spring-dbunit/wiki/maven) Wiki page.

## Release Notes
See [Milestones](https://github.com/excilys/spring-dbunit/issues/milestones?state=closed)


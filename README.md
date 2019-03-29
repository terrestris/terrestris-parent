# terrestris parent pom

This is a simple maven pom with dependency and plugin management using
sane defaults. It can be used as a starting point for any Java
project.

In particular, to use it in SHOGun-based projects, be aware of the
following:

* uses Spring 5.1.5.RELEASE
* uses Spring security 5.1.4.RELEASE
* uses Hibernate 5.3.4.Final
* uses Geotools 19.1
* uses Ehcache 3.5.2

This means you'll have to configure your spring-db context file to
use the JCacheRegionFactory for caching.

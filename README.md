# Tiny — A constant key/value store

A fork of [TinyCDB](http://www.corpit.ru/mjt/tinycdb.html). A very fast and simple package for creating and reading “constant databases,” a data structure introduced by [Dan J. Bernstein](http://cr.yp.to/djb.html) in his [cdb](http://cr.yp.to/cdb.html) package. A constant database cannot be updated at a runtime, only rebuilt. Rebuilding is atomic operation and is very fast — much faster than of many other similar packages. Once created, CDB may be queried, and a query takes very little time to complete.


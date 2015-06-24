# Introduction

[_dataSet_][ds] provides easy test support for testing of different datastore (currently) using [JUnit][ju].

## Features

First of all it's fast and easy to use and brings fun back(?) to the testing of datastores. 

Second [it][ds] will 

- __eleminate boilerplate code__, 
- makes your tests __more expressive__, 
- better organized and 
- therefore __maintainable__.


### Datastore

- Supports any kind of datastore 
- ... currently SQL and [Neo4J][n4j].

- Supports one or many datastores
- ... homegenious: two or more databases of the same type (SQL __or__ [Neo4J][n4j])
- ... heterogenious (two or more databases of different types (SQL __and__ [Neo4J][n4j])
- It's also possible to use different SQL datastores. This is also somehow hetergenious.


### Test fixtures (or datasets)

- Multiple dataSets
- Mixture of fixed and shared test fixtures (called DataSet)
- Mixin of datasets
- Organization of your test fixtures
- Test fixture as template scripts

### Templates

- Well known [Apache Velocity][vc] as _template engine_.
- Injecting data and functionality from specific test (method or class). Example: Known account names.
- Bunch of predefined template objects like generators or encoders. In the future there will be more.
- Adhoc template objects for fast custom template objects.
- Ease of generating a lot of data.

### Extendable

Almost everything is extendable. You can write your own 

- Template object like 
	- generators, 
	- encoders or
	- any functionality [dataSet][ds] does and will not support. 
- or even write your own bunch for your project(s).

- Have a datastore which is not yet supported. _Write your own_.
- Or you wan't to use your own dataset format, because the customer is providing test data. Just do it.

- Don't like [velocity][vc] as _template engine_. _Write your own_.

## Where to start?




[ds]: http://github.com/loddar/dataset "dataSet (core) on github"
[n4j]: http://neo4j.com/ "Home of Neo4J"
[ju]: http://junit.org/ "Home of JUnit"
[vc]: http://velocity.apache.org/ "Home of Apache Velocity"


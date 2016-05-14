# Introduction

[_dataZ_][dz] provides easy test support for testing of different datastore (currently) using [JUnit][ju].

## Features

First of all dataZ is fast and easy to use and brings fun back(?) to the testing of databases. 


Second dataZ will 
- __eleminate boilerplate code__, 
- makes your tests __more expressive__, 
- better organized and 
- therefore __maintainable__.

Third dataZ is highly extendable and adaptable.

### Databases

Within a Database we call it a __Datastore__.

- Supports any kind of datastore 
 ... currently any SQL databases and [Neo4J][n4j].
- Supports one or many datastores
	*  ... _homegenious_: two or more databases of the same type (any SQL database __or__ [Neo4J][n4j])
	*  ... _heterogenious_ (two or more databases of different types (any SQL database __and__ [Neo4J][n4j])
	*  It's also possible to use different SQL databases. This is also somehow hetergenious.
	

### Test fixtures (or datasets)

- Multiple datasets
- Mixture of fixed and shared test fixtures
- Reuse of predefined datasets (by using @Use)
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
	- any other functionality [dataZ][dz] is typical to your project and won’t be useful for any other.
- or even write your own bunch for your project(s).

- Have a datastore which is not yet supported. _Write your own_.
- Or you wan't to use your own format, because the customer is providing test data. Just do it.

- Don't like [velocity][vc] as _template engine_. _Write your own_.

## Where to start?




[dz]: http://github.com/dataz "dataZ@github"
[n4j]: http://neo4j.com/ "Home of Neo4J"
[ju]: http://junit.org/ "Home of JUnit"
[vc]: http://velocity.apache.org/ "Home of Apache Velocity"


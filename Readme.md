# C# TextMate Bundle #

This is a substantial rewrite of the original C# bundle.
It was heavily inspired by the Java bundle.

It has a hierarchical definition, allowing inner classes, etc.
The symbol list will show up to several layers deep.

Regions are marked in the symbol list as well.

# Todo #

## Features ##

* Symbol List:
	* Properties
	* Operators
	* #defines?
	* Empty Regions?

## Known Issues

* object foo = new object() marked as function
* The var type is not currently a keyword
* delegate needs to be a storage type?

Foy - Python Handler
===================

Python handler for __Fountain of Youth__ Project, using Pypi packages.

Usage
-----

Parse packages from requirements.txt:

	foy.python -R <file>

Check for a package's new version:

	foy.python -C <package>

Project requirements
------------

Your project should have a requirements.txt file in the following format:

	[package]==[version]

Note that you can also use:

	[package]>=[version]
	[package]<=[version]
	[package]>[version]
	[package]<[version]
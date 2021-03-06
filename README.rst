SwingLabs SwingX Project
======

.. image:: https://travis-ci.com/Softec-Open-Source-Division/swingx.svg?branch=master
    :target: https://travis-ci.com/Softec-Open-Source-Division/swingx


SwingX is a library of components and utilities extending the Java Swing library. Originally published by SwingLabs,
their site is now closed, and the project is available in a number of public clones.

This fork is a (still cautious) update to Java 8.

Building the Source
---------------

SwingX relies on Maven for controlling compilation, building docs, testing, etc. You can use our POM files to build the project, some IDEs can directly invoke Maven for you.

To compile from the command line, you'll need to have Apache Maven 3.x installed; see http://maven.apache.org. 

You can build SwingX by going to the command line and typing
mvn package

That should be it--this will test and build swingx.jar in the target directory. 

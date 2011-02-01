DooSo6 Dependencies
=============

This project contains the missing dependencies of DooSo6. Mainly, it provides
.jar files from libraries that are not available in public maven repositories.

Requirements
------------

* [Maven2](http://maven.apache.org/)


Usage
---------


To add these dependencies to your local maven repository, you have to type the following commands:

	mvn -N install:install-file -DgroupId=fr.loria.ecoo -DartifactId=jlibdiff -Dversion=2.0 -Dpackaging=jar -Dfile=lib/jlibdiff-2.0.jar
	mvn -N install:install-file -DgroupId=fr.loria.ecoo -DartifactId=jxydiff -Dversion=1.0 -Dpackaging=jar -Dfile=lib/jxydiff-1.0.jar


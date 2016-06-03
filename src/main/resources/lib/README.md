## Setup Maven dependency for Microsoft SQL Server:

* The driver is downloaded from this [link](http://www.microsoft.com/en-us/download/details.aspx?id=11774).
* SQL Server driver is not included in maven repository. Thus, it needs to get installed manually.
* From  the lib/ dierctory un This cmd:
```
mvn install:install-file -Dfile=sqljdbc4.jar -DgroupId=com.microsoft.sqlserver -DartifactId=sqljdbc4 -Dversion=4.0.2206.100 -Dpackaging=jar
```
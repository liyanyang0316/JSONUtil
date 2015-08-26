
This is a JSON generation library for Java.  It is oriented towards being
used in web servers and includes several options for validation and
controling the way that the JSON is generated.  Defaults for those options
can be set using JNDI or JMX/MBean access which is normally available with
JEE web tier containers.  If you don't have those, a debug log message
may be generated, but it is harmless.  Those log messages can be supressed
by setting system properties on the java command line.

The trunk branch requires Java 8, but there are branches for Java 5,
Java 6 and Java 7, which maintain the same functionality except for
the default methods in an interface.

Files are included for the Maven project and an Eclipse project.

It has JUnit tests for most of the functionality.

There is a run time dependency on Apache Commons Logging facade.

Binaries are available [here](https://github.com/billdavidson/JSONUtil/releases)

Javadoc is available online [here](http://kopitubruk.org/JSONUtil/javadoc)

From Maven Central Repository [here](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22org.kopitubruk.util%22%20AND%20a%3A%22JSONUtil%22)

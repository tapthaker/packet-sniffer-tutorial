## What is Maven ?

https://maven.apache.org/

Package Manager: "Install jpcap for me" 


Maven should take care of manual steps like:

```
   o In your Java CLASSPATH, include jars/net.sourceforge.jpcap-x.yy.zz.jar
        plus all jars found in thirdParty/jars.

      o Native bindings to libpcap are provided precompiled for intel Linux.
        The Java wrapper shared object is 
          src/java/net/sourceforge/jpcap/capture/libjpcap.so
```


Maven in 5 minutes: https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html


jpcap in maven central: https://mvnrepository.com/artifact/jpcap/jpcap/0.1.18-002


To execute run:
`mvn install exec:java -Djava.library.path=<path to jpcap>`

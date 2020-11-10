Not maven specific (you can use this recipe to setup a custom truststore for any JVM), but I put it here because I use it mainly in maven (and keep looking for it here).


```
-Djavax.net.ssl.trustStore2=/Users/any/my_cacerts -Djavax.net.ssl.trustStorePassword=changeit
```


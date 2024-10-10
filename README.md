# utopialib-java

Utopia Ecosystem API wrapper written in Java

![utopialogo](https://github.com/user-attachments/assets/869e4213-9b66-4a8e-90e5-5e789da5fa76)

This library is a must have for anyone who wants to start their web3 journey with the Utopia ecosystem in Java. The library greatly simplifies working with the Utopia API for Java programming.

How to

1. Add a jar file to your project located in out/artifacts/utopalib_java_main_jar
2. Import library 
```java 
import com.company.libUtp; 
```

example class

```java
public class Main {

    public static void main(String[] args) throws IOException {
        // sample using

        libUtp lol = new libUtp();

        lol.port = "20000";
        lol.token =  "219C91A00340B54F7AD4C1DB40E9B9E3";

        System.out.println(lol.getSystemInfo());
        //System.out.println(lol.getReleaseNotes());
    }
}
```

response:

```
{"result": {"buildAbi": "x86_64-little_endian-llp64","buildCpuArchitecture": "x86_64","build_number": "1.0.7114","currentCpuArchitecture": "x86_64","netCoreRate": 25,"networkCores": 4,"networkEnabled": true,"numberOfConnections": 15,"packetCacheSize": 977753,"uptime": "01:37:58"},"resultExtraInfo": {"elapsed": "0"}}
```

How can this be used?
creating a web service that processes client requests;
creation of a payment service;
development of a bot for the channel;
utility for working with uNS;
experiments to explore web3.0;

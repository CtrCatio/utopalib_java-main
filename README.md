# utopialib-java

Utopia Ecosystem API wrapper written in Java

![utopialogo](https://github.com/user-attachments/assets/869e4213-9b66-4a8e-90e5-5e789da5fa76)

This library is a must have for anyone who wants to start their web3 journey with the Utopia ecosystem in Java. The library greatly simplifies working with the Utopia API for Java programming.

-----
How to

1. Download the JAR file of the library:

[CtrCatio/utopalib_java-main/blob/main/libs/utopalib_java-main.jar](https://github.com/CtrCatio/utopalib_java-main/blob/main/libs/utopalib_java-main.jar)

2. Adding the JAR File to Your Project or use Gradle
   
For Gradle

Create a libs folder in the root of your project (if it doesn't already exist).
Place the downloaded utopalib_java-main.jar in the libs folder.

Add the following dependency to your build.gradle file:
```groovy
dependencies {
    implementation files('libs/utopalib_java-main.jar')
}
```
Import library 


```java 
import com.company.libUtp; 
```

example class

```java
public class Main {

    public static void main(String[] args) throws IOException {
        // sample using

        libUtp utpAPI = new libUtp();

        utpAPI.port = "20000";
        utpAPI.token =  "219C91A00340B54F7AD4C1DB40E9B9E3";

        System.out.println(utpAPI .getSystemInfo());
    }
}
```

response:

```
{"result": {"buildAbi": "x86_64-little_endian-llp64","buildCpuArchitecture": "x86_64","build_number": "1.0.7114","currentCpuArchitecture": "x86_64","netCoreRate": 25,"networkCores": 4,"networkEnabled": true,"numberOfConnections": 15,"packetCacheSize": 977753,"uptime": "01:37:58"},"resultExtraInfo": {"elapsed": "0"}}
```

How can this be used?
1. creating a web service that processes client requests;
2. creation of a payment service;
3. development of a bot for the channel;
4. utility for working with uNS;
5. experiments to explore web3.0;

---

<a href="https://udocs.gitbook.io/utopia-api/">
  <img align="center" width="200" src="https://github.com/Sagleft/ures/blob/master/udocs-btn.png?raw=true">
</a>

<a href="https://utopia.im/RUTECH">
  <img align="center" width="200" src="https://github.com/Sagleft/ures/blob/master/rutopia_tech.png?raw=true">
</a>


## CICS Transaction Gateway Liberty JCA ECI sample code

### Pre-reqs
* CICS Transaction Gateway v8.1 or later
* WebSphere Liberty 8.5.5 FP3 or later with the jca-1.6 feature installed or
* Eclipse with WebSphere Development Tools installed

### Configuration
The supplied `server.xml` file shows the required configuration paramters for adding the ECI resource adapter, 
creating a connection factory and adding the classes supplied with the resource adapter to the classpath of the application. 
This file can be used as-is or the configuration options can be copied into an existing server configuration.

### Compiling the sample
The sample servlet code can be added to a Web Project. To correct any compilation errors the cicsjee.jar library supplied by CICS TG
should be added to the build path.


### Reference
* More information about working with CICS TG resource adapters in WebSphere Liberty can be found [here](https://www.ibm.com/docs/en/cics-tg-zos/9.3.0?topic=configuring-eci-resource-adapter-liberty)

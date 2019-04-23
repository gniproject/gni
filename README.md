# gNI: Generalized Network Interfaces 

P4Runtime, gNMI, and gNOI each provide an API for configuration and control of network devices and all of them use gRPC as an underlying communication mechanism. 
Management applications use gNMI for configuration of network devices, P4Runtime to implement control plane applications and services, and gNOI for executing 
operational commands on network devices.. Although details differ, P4Runtime, gNMI, and gNOI employ the same 
conceptual abstractions and messaging paradigms when communicating with network devices. 
 The similarity makes it possible to define a single, unified API that supports all configuration,
 management, and control plane services that gNMI, P4Runtime, and gNOI provide.
 The essence of the work consists of a set of generalized network configuration and 
 control interfaces called Generalized Network Interfaces (gNI) that started with the
  following design goals:

 - Provide a set of unified Northbound (NB) interfaces that can be used to configure, manage,
   and control network devices and services.
 - Minimize the number of remote procedure call functions that a network administrator 
  need to know for configuring, managing, and controlling of network devices.


# Note: 

This is a work in progress project. 


# License 
gNI is released under the Apache Licesne Version 2.0.

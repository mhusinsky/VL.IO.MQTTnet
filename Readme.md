# VL.IO.MQTTnet

MQTT nodes for [VL](https://visualprogramming.net/), based on [MQTTnet](https://github.com/chkr1011/MQTTnet).

## Features

Nodes to publish and subscribe topics with a client node, based on the MQTTnet.Extensions.ManagedClient.

* MQTT over TCP
* Supports wildcards in topics (+ and #)
* Experimental support for TLS (but no certificate loading)



### TODO

* MQTT over WebSockets



## Installing

To use the nodes in VVVV gamma, install the available nuget from nuget.org.

```
    nuget install VL.IO.MQTTnet -pre
```


For information on how to use nugets with VL, see [Managing Nugets](https://thegraybook.vvvv.org/reference/libraries/dependencies.html#manage-nugets) in the VL documentation. 
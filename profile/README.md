# Hive Of Things

## Introduction
The Hive Of Things connects and shares IoT devices, services and users in a secure manner. 

The Hive consists of a Hub to which IoT devices, Services and Consumers connect. 
For security reasons the IoT devices and services remain hidden from the outside world. 
All access is routed via the Hub which implements stringent security measures.

The Hive is a 'Capabilities Based' solution to enhance security. It is implemented using '[capnproto'(https://capnproto.org/)'. 

The status of the project is in-development. Currently the work focuses on a switch from http based interfaces to Capabilities based interfaces using capnproto (go-capnproto).


## Contributions
It is still a bit early for serious contributions but if you are that serious, create an issue with the request to join. Please check out the other repositories and the contibuting guidelines first.

## Resources

1. IoT devices are defined using W3C's [WoT (Web of Things)](https://www.w3.org/TR/wot-architecture/) standard.
2. Hive Of Things is using the highly secure Capabilities based communication:
- capnproto: https://capnproto.org/
- go-capnproto: https://github.com/capnproto/go-capnproto2
- wikipedia has something to say as well: https://en.wikipedia.org/wiki/Capability-based_security
- sandstorm uses capnproto: https://sandstorm.io/how-it-works#grains
- MIT has a youtube courseware episode on capabilities: https://www.youtube.com/watch?v=TQhmua7Z2cY

## Fun Fact

The concept of Capabilities based development dates back to the 60's: https://homes.cs.washington.edu/~levy/capabook/


# Multi Sensor Fusion 2

A full rewrite and redesign of the [Multi Sensor Fusion package](https://www.google.com) by ETH-ASL.

Features added to MSF:

* Will a modular sensors implementation, so any sensor can be used at runtime
* Adding sensor will be intuitive, not as currently in MSF
* Does not use `boost::` for meta-programming, will mostly use `std::`
* Support a modular outlier rejection system, allowing multiple different rejectors to be available
* The use can choose to use the Automatic Differentiation module for calculating measurement Jacobians.
* Support x86, x86_64 and ARM (Aarch64 and armhf)

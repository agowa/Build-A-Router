# Build-A-Router

This project is about building a new innovative CPE-router for prosumers. After the decline of AVM Fritz!Box as the goto prosumer device and their stagnation in development of new features it is time for a new product.

## Features

* RAM: 4 GB
* NAND: 256GB
* Kernel: Mainline, always the most recent, secure and feature richest kernel directly build from mainline
* IPv6 first design for a modern network
* IPv6-only on internal networks
* Jool for NAT64 and NAT46 (port forwardings)
* Dualstack on public interface
* Site2Site-VPN
* Client2Site-VPN (road warrior VPN)
* Privacy VPN
* IDS + IPS built-in
* Podman for user extendability with custom apps.
* Root access optional (will trigger a flag in UI)
* Unbound recursive DNS resolver
* Zeroconf
* Squid3 (transparent) proxy
* Multi WAN compatible
* Modular design
* Low power consumption
* Slim form factor (Mini-ITX, ...)
* Multi Site deployment (share configuration over Site2Site VPN link)
* SFP+ Slots (or bundled media converters) for VDSL, DOCSIS, Fiber, ...

## Architecture

![architecture diagram of the Build-A-Router project](./architecture/overview.svg)
<img src="./architecture/overview.svg">

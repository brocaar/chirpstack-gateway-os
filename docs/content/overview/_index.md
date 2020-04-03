---
title: ChirpStack Gateway OS
menu:
    main:
        parent: overview
        weight: 1
listPages: false
---

# ChirpStack Gateway OS

ChirpStack Gateway OS is an open-source Linux based embedded OS which can run on
various LoRa<sup>&reg;</sup> gateway models. The goal is to make it easy to get started with
LoRaWAN<sup>&reg;</sup> and the ChirpStack open-source LoRaWAN Network Server stack with the minimum steps required to setup
your gateway(s).

![gateway-config](/gateway-os/img/gateway-config.png)

## Image types

### chirpstack-gateway-os-base

Provides the ChirpStack Concentratord and ChirpStack Gateway Bridge pre-installed
including a CLI utility for gateway configuration.

### chirpstack-gateway-os-full

Provides a full [ChirpStack Network Server](/network-server/) and [ChirpStack Application Server](/application-server/)
environment running on the gateway, on top of all the features that are provided
by the **chirpstack-gateway-os-base** image.

## Targets

### Raspberry Pi

* Raspberry Pi 1
* Raspberry Pi 3
* Raspberry Pi 4

#### Shields / kits

* [IMST - iC880A](https://wireless-solutions.de/products/long-range-radio/ic880a.html)
* [IMST - iC980A](http://www.imst.com/)
* [IMST - Lite Gateway](https://wireless-solutions.de/products/long-range-radio/lora-lite-gateway.html)
* [Pi Supply - LoRa Gateway Hat](https://uk.pi-supply.com/products/iot-lora-gateway-hat-for-raspberry-pi)
* [RAK - RAK2245](https://store.rakwireless.com/products/rak2245-pi-hat)
* [RAK - RAK831 Gateway Developer Kit](https://store.rakwireless.com/products/rak831-gateway-module?variant=22375114801252)
* [RisingHF - RHF0M301 LoRaWAN IoT Discovery Kit](http://risinghf.com/#/product-details?product_id=9&lang=en)
* [Sandbox Electronics - LoRaGo PORT](https://sandboxelectronics.com/?product=lorago-port-multi-channel-lorawan-gateway)
* [Semtech - SX1302 CoreCell](https://www.semtech.com/products/wireless-rf/lora-gateways/sx1302cxxxgw1)

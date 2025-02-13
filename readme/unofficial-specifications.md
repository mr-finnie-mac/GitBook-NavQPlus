---
description: Unqualified Specifications for guidance only
---

# Unofficial Specifications

### Introduction

General specifications have been requested for NavQPlus. Currently there are no official qualified specifications.&#x20;

{% embed url="https://a360.co/408nS79" %}
NavQPlus Enclosure and board (may be downloaded through link)
{% endembed %}

\
_**The values below may be used for guidance, but are not guaranteed**_

### OS/Software

* NXP Yocto Linux 5.15 kernel
  * Gstreamer
  * eIQ AI/ML tools
  * Ethernet over USB-C Gadget mode (SSH connection to laptop using USB cable)
*   Ubuntu 22.04 built on top of NXP Yocto 5.15

    * ROS2 Humble enabled



### Voltage input&#x20;

* 5-20V&#x20;
* Power supplied via High voltagte USB PD power switch&#x20;
  * Power input and can be from dedicated connector or through USB-C

### Power consumption

* TBD&#x20;
  * Expectation is MAX 5W and typical 3W
  * 5W =\~12V@450mA

### Enclosure dimensions

* CAD files available for board outline and case though the [link above](https://a360.co/408nS79)
* 90mmx70mm exclusive of case mounting tabs
* Tabs 82mm at max width.
* CASE Mounting tabs are 72mmx72mm
* CASE / Heatsink secondary mounting 53mmx53mm&#x20;

### Weight

* 98.4grams with heatsink attached\*
  * \* production units may use a flat aluminum plate which will be lighter.


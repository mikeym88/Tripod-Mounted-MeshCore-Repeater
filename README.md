# MeshCore Repeater <!-- omit from toc -->

- [Summary](#summary)
  - [What's the purpose of MeshCore?](#whats-the-purpose-of-meshcore)
  - [Does it have any other functionalities? Like Eartquake detection?](#does-it-have-any-other-functionalities-like-eartquake-detection)
- [Project Overview](#project-overview)
- [Tools](#tools)
- [Parts List](#parts-list)
  - [Main Parts](#main-parts)
  - [Enclosure](#enclosure)
  - [Tripod](#tripod)
  - [Power Management](#power-management)

## Summary

[MeshCore](https://meshcore.io/) has been described as "off-grid SMS messaging." People are able to message each other through devices that use the [ISM](https://en.wikipedia.org/wiki/ISM_radio_band) frequency band. These devices form a Mesh, hence the name **MeshCore**.

However, for these devices to be able to talk to one another effectively, solar-powered **repeaters** are needed to expand the range of these MeshCore devices. Hence why I decided to build a **1 Watt Solar-Powered MeshCore Repeater**.

### What's the purpose of MeshCore?

In major emergencies and disaser, cell phone networks would probably be down due to power outages or overloaded due to overuse. MeshCore would alleviate this problem by providing an alternative mode of communication. Since thee devices are Solar- and battery-powered, they would work even in the event of severe power outages.

### Does it have any other functionalities? Like Eartquake detection?

Why yes! These MeshCore devices can also be used for [Earthquake detection](https://www.reddit.com/r/meshcore/comments/1wx45sv/a_new_meshcore_repeater_project_earthquake/)! My next step is to upgrade this repeater with eartquake detection capabilites.

## Project Overview

I decided to build a 1 Watt solar-powered and tripod-mounted MeshCore repeater. This way the repeater could be easily deployed or relocated as needed. Below is a picture of the repeater deployed to a rooftop.

<img src="img/tripod_repeater.jpg" alt="Tripod-mounted MeshCore repeater deployed on the rooftop of a condo building." heigh="500px" width="375px" />

## Tools

I've used various tools to make this repeater:

* Drill
* Electric Screwdriver
* Step bits
* Hole Saw bits &amp; deburring tool
* Soldering iron
* Heat gun / Lighter
* Calipers
* Multimeter

## Parts List

The repeater is based around a [RAK WisMesh 1W Booster kit](https://store.rakwireless.com/products/meshtastic-1w-lora-booster-kit-rak3401?variant=46639158657222).

**NOTE:** if any of the links are out of date, please let me know!

Below is an image of the components that are inside the repeater's enclosure.

<img src="img/repeater_internals.jpg" alt="Components that are inside the repeater's enclosure." heigh="500px" width="375px" />

### Main Parts

* RAK WisMesh 1W Booster (3401 + 13302) [Battery Powered 9xx variant] - [AliExpress](https://www.aliexpress.com/item/1005012898074933.html?spm=a2g0o.order_list.order_list_main.24.38bd18025T6YNh)
* 10W USB-C Solar Panel - [AliExpress](https://www.aliexpress.com/item/1005009983374214.html)
  * Camera Clamp - [Amazon](https://www.amazon.ca/dp/B07PHNRS3N)
  * 1/4" Male to 1/4" Male Tripod Screw Adapter - [Amazon](https://www.amazon.ca/dp/B077SBSJM2)
* Antenna, similar to this one - [Amazon](https://www.amazon.ca/ALFA-Network-AOA-915-5ACM-802-11ah-Application/dp/B08H8J6ZV6)

Future Additions:

* RAK12027 WisBlock Earthquake Sensor Module - [Specs](https://docs.rakwireless.com/product-categories/wisblock/rak12027/overview/), [DigiKey](https://www.digikey.ca/en/products/detail/rakwireless-technology-limited/RAK12027-0-WB-N/18682799)

### Enclosure

* IP67 Waterproof Gray Outdoor Electronic Enclosure - [AliExpress](https://www.aliexpress.com/item/1005009909495336.html)
* Waterproof USB C Connector with DustCover - [AliExpress](https://www.aliexpress.com/item/1005002843708158.html)
* Superbat N Type Female Bulkhead Pigtail - [Amazon](https://www.amazon.ca/dp/B0FD9WJRB7)
* Pole Mounting Bracket - [Amazon](https://www.amazon.ca/dp/B0B4DW4HFM)
* M5x12mm Bolts and Nuts
* M2 nuts and bolts - for securing the components to the breadboard-like mounting plate
  * M2x8mm Screws - [Amazon](https://www.amazon.ca/dp/B0DLK6QXH7)
  * M2 Washers - [Amazon](https://www.amazon.ca/dp/B0C2BZTRZC)
  * M2 Nuts - [Amazon](https://www.amazon.ca/dp/B0FMRH1492)

### Tripod

* Carbon Fiber Tripod - [AliExpress](https://www.aliexpress.com/item/1005004728019710.html)
* Tripod Extender - [Amazon](https://www.amazon.ca/dp/B07N3X2ZDS)
* Antenna Tripod Mount Adapter - [AliExpress](https://www.aliexpress.com/item/1005012841232845.html)
* N Male to N Female Plug Bulkhead connector - [AliExpress](https://www.aliexpress.com/item/1005008927857684.html)
* Sandbag - [Amazon](https://www.amazon.ca/dp/B0CKMH9D6R)
* Quikrete Sand - [Home Depot](https://www.homedepot.ca/product/quikrete-premium-play-sand-25kg/1000166231)

### Power Management

* 18650 Parallel 4x 18650 Battery Holder - [AliExpress](https://www.aliexpress.com/item/1005005449039449.html)
* 4x18650 LiFePo4 batteries - [Canadian Tire](https://www.canadiantire.ca/en/pdp/noma-li-ion-18650-2000mah-rechargeable-batteries-for-solar-outdoor-lighting-3-7v-4-pk-0525913p.html)
* 5.5*2.1mm DC Power Socket - [AliExpress](https://www.aliexpress.com/item/1005008014808796.html)
* JST ZH 1.5mm power connector (for solar panel connection) - [AliExpress](https://www.aliexpress.com/item/1005009901785111.html)
* JST PH2.0 2.0mm power connector (for battery connection) - [AliExpress](https://www.aliexpress.com/item/1005011983455632.html)
* Shrinkg Tubing - [Amazon](https://www.amazon.ca/Heat-Shrink-Tubing-270-Pcs/dp/B0B9S2LF94/)
* Tactile Switch - [Amazon](https://www.amazon.ca/dp/B01MU8ST7D)

Future Addition:

* Waveshare Solar Power Manager Module - [AliExpress](https://www.aliexpress.com/item/1005009719169321.html), [Specs](https://www.waveshare.com/solar-power-manager-d.htm)
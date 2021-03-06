---
layout: documentation
title: Zooz Zen26 - ZWave
---

{% include base.html %}

# Zooz Zen26 Zooz Zen26 S2 on/off switch
This describes the Z-Wave device *Zooz Zen26*, manufactured by *[Zooz](http://www.getzooz.com/)* with the thing type UID of ```zooz_zoozzen26badxml_00_000```.

The device is in the category of *Wall Switch*, defining Any device attached to the wall that controls a binary status of something, for ex. a light switch.

![Zooz Zen26 product image](https://www.cd-jackson.com/zwave_device_uploads/956/956_default.jpg)


The Zooz Zen26 supports routing. This allows the device to communicate using other routing enabled devices as intermediate routers.  This device is also able to participate in the routing of data between other devices in the mesh network.

## Overview

  * Manual or Z-Wave on/off control with instant status updates
  * Simple Direct 3-Way: connect with existing on/off switches in 3-way,4-way, and 5-way set-ups, no add-on needed (neutral wire required)
  * Remembers and restores on/off status after power failure
  * LED indicator signals inclusion, exclusion, reset, and setting changes
  * Built-in Z-Wave Plus signal repeater to extend network range
  * Works with LED, CFL and incandescent bulbs
  * S2 security protocol and the latest 500 Z-Wave chip

### Inclusion Information

1. Initiate inclusion (pairing) in the app (or web interface).

2. Finalize inclusion at the switch. TAP 3 TIMES QUICKLY. The LED indicator will blink to signal communication and remain on for 2 seconds to confirm inclusion.

### Exclusion Information

1. Bring your Z-Wave gateway (hub) close to the switch if possible

2. Put the Z-Wave hub into exclusion mode

3. Tap the lower paddle on the switch 3 times quickly

4. Your hub will confirm exclusion and the device will disappear from your controller's device list

### General Usage Information

FACTORY RESET

tap-tap-tap’n’hold the upper paddle for at least 10 seconds. The LED indicator will flash to confirm successful reset.

NOTE: All previously recorded activity and custom settings will be erased from the device’s memory.

## Channels

The following table summarises the channels available for the Zooz Zen26 -:

| Channel Name | Channel ID | Channel Type | Category | Item Type |
|--------------|------------|--------------|----------|-----------|



## Device Configuration

The following table provides a summary of the 4 configuration parameters available in the Zooz Zen26.
Detailed information on each parameter can be found in the sections below.

| Param | Name  | Description |
|-------|-------|-------------|
| 1 | Paddle Control | Choose Paddle Functionality (Invert) |
| 2 | LED Indicator Control | Change behavior of the LED indicator |
| 3 | Auto Turn-Off Timer | enable the Auto Turn-Off Timer |
| 5 | On Off Status After Power Failure | Set the on off status for the switch after power failure. |

### Parameter 1: Paddle Control

Choose Paddle Functionality (Invert)
Choose if you want the upper paddle to turn the light on or turn the light off when tapped
The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | Top on, Bottom off |
| 1 | Top off, Bottom on |

The manufacturer defined default value is ```0``` (Top on, Bottom off).

This parameter has the configuration ID ```config_1_1``` and is of type ```INTEGER```.


### Parameter 2: LED Indicator Control

Change behavior of the LED indicator
Choose if you want the LED indicator to turn on when the switch (light) is on or off, or if you want it to remain on or off at all times

OR

6 x TAP PADDLE to change the LED indicator mode
The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | LED on when switch off |
| 1 | LED on when switch on |
| 2 | LED off |
| 3 | LED on |

The manufacturer defined default value is ```0``` (LED on when switch off).

This parameter has the configuration ID ```config_2_1``` and is of type ```INTEGER```.


### Parameter 3: Auto Turn-Off Timer

enable the Auto Turn-Off Timer
Use this parameter to set the time which you want the switch to automatically turn off once it has been turned on. The number entered as value corresponds to the number of seconds.
Values in the range 0 to 32768 may be set.

The manufacturer defined default value is ```0```.

This parameter has the configuration ID ```config_3_2``` and is of type ```INTEGER```.


### Parameter 5: On Off Status After Power Failure

Set the on off status for the switch after power failure.
Set the on off status for the switch after power failure.
The following option values may be configured -:

| Value  | Description |
|--------|-------------|
| 0 | Off |
| 1 | On |
| 2 | last state |

The manufacturer defined default value is ```2``` (last state).

This parameter has the configuration ID ```config_5_1``` and is of type ```INTEGER```.


## Association Groups

Association groups allow the device to send unsolicited reports to the controller, or other devices in the network. Using association groups can allow you to eliminate polling, providing instant feedback of a device state change without unnecessary network traffic.

The Zooz Zen26 supports 2 association groups.

### Group 1: Lifeline

The Lifeline association group reports device status to a hub and is not designed to control other devices directly. When using the Lineline group with a hub, in most cases, only the lifeline group will need to be configured and normally the hub will perform this automatically during the device initialisation.
This device will send BINARY SWITCH REPORT to Group 1 and 2 when operated manually

Association group 1 supports 1 node.

### Group 2: Control

This device will send BINARY SWITCH REPORT to Group 1 and 2 when operated manually

Association group 2 supports 5 nodes.

## Technical Information

### Endpoints


### Documentation Links

* [zen26 manual](https://www.cd-jackson.com/zwave_device_uploads/956/zooz-z-wave-plus-s2-on-off-switch-zen26-manual.pdf)

---

Did you spot an error in the above definition or want to improve the content?
You can [contribute to the database here](http://www.cd-jackson.com/index.php/zwave/zwave-device-database/zwave-device-list/devicesummary/956).

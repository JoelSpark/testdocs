---
title:	XQUBEAIS_1.0_MI
---

# Required Materials
* 1x PCAN 232 serial to picoblade adaptor with pull-up resistor
* 1x AIS CAN and power test harness
* 1x AIS programming cable (USB - picoblade)

# PCB Inspection

@include@ common/pcb_inspection @include@

# Power-on + Self Check

1. Set Up
	1. Plug the AIS CAN
		1. detailed description
	1.	Connect the USB to CAN
    	1. detailed description of that
1. Power On
  	1. Pull AIT tag
    	@include@ common/pulling_ait @include@

# Rebuild docker images
@include@ common/rebuilding_docker_images @include@

# Turn on power supply
@include@ equipment/power/power_supply @include@
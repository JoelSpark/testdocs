---
title:	XQUBEAIS_1.0_MI

---

# Required Materials
	* 1x PCAN 232 serial to picoblade adaptor with pull-up resistor
	* 1x AIS CAN and power test harness
	* 1x AIS programming cable (USB - picoblade)

# PCB Inspection

common/pcb_inspection

# Power-on + Self Check

1. Set Up

1.1. Plug the AIS CAN
detailed description

1.1. Connect the USB to CAN
detailed description of that

1. Power On

1.1. Pull AIT tag
@include@ common/pulling_ait @include@

1.1. Rebuild docker images
@include@ common/rebuilding_docker_images @include@

1.1 Turn on power supply
@include@ equipment/power/power_supply @include@
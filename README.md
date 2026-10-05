# Cisco Enterprise Network

A practical Cisco Packet Tracer lab focused on building and configuring a small enterprise network.

## Implemented

* VLAN segmentation
* Inter-VLAN routing using Router-on-a-Stick
* 802.1Q trunking
* Spanning Tree Protocol (STP)
* Root Primary / Root Secondary
* STP failover testing
* PortFast
* BPDU Guard
* Basic switch hardening
* IP addressing and subnetting

BPDU Guard:

BPDU Guard was configured on PortFast-enabled access ports where only end devices such as PCs are expected.

As a practical test, a second switch named Test-BPDU-Guard was connected to one of these protected access ports. Since the switch transmitted BPDUs, BPDU Guard detected the BPDU and automatically placed the access port into an err-disabled state.

The test demonstrates how BPDU Guard helps prevent unauthorized switches and potential Layer 2 loops from being introduced through end-device ports.

Purpose:

The lab was built to practice network configuration, redundancy, troubleshooting and basic Layer 2 security mechanisms using Cisco IOS.

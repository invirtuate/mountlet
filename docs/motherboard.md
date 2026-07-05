# motherboard

## overview
Build requirements for a new system.

## hardware
CPU:
- Must support virtualization, Intel or AMD are acceptable, prefer AMD

Memory:
- 128GB preferred, 64GB is acceptable

Storage:
- NVMe is preferred, but M.2 is acceptable
- 1TB storage minimum
- SATA optional for additional storage

NIC:
- 1G or 10G NIC, more than 1 nic will bonded to br0

## limitations
Motherboards that do not follow atx/matx require a custom chassis, this is not ideal and expensive

small form factor motherboards have the following limitations:
- usually no PCIe
- usually require a custom chassis
- usually have limits in the amount of drives

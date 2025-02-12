# Connecting Cisco Devices

## Objective
Demonstrate knowledge of configuring and managing Cisco devices. Learn how to establish basic connectivity between Cisco routers and switches using Packet Tracer.
### Skills Learned


- Setting up and connecting Cisco devices (routers and switches).

### Tools Used


- Packet Tracer.

## Steps
* **Step 1: Connect PCs to Switches and Server to Switch**<p>
For the purpose of this lab we are assuming auto MD-X is not enabled. Auto MD-X allows devices to automatically detect which pins they are transmitting on and adjust.
  - PCs send data on pins 1 and 2 and recieves data on pins 3 and 6. Switches are opposite. They send data on 3 and 6 and recieve data on 1 and 2.
  - Proper cable to use is a straight-through b
  - Set Domain Controller’s NIC Private IP address to be static (shown in photos below)
  - Create the Client VM (Windows 10) named “Client-1”. Use the same Resource Group and Vnet that was created prior.
  - Ensure that both VMs are in the same Vnet

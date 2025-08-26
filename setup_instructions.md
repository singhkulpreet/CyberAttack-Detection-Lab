# Lab Setup Instructions

## Environment
- Hypervisor: VMware/VirtualBox
- Network Mode: Host-only (vmnet8)
- VMs:
  - Kali Linux (192.168.25.200)
  - Windows Host (192.168.25.1)
  - QRadar CE (192.168.25.100)

## Steps
1. Install Kali Linux and QRadar CE in VMware.
2. Configure network interfaces to vmnet8 (Host-only).
3. Install WinCollect on Windows and forward logs to QRadar.
4. Enable rsyslog on Kali and forward logs to QRadar.
5. Install Wireshark on Windows to capture traffic.
6. Verify connectivity between all machines with `ping`.

✅ Environment ready for attack simulations.

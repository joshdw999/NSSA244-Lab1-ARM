# This template provisions these resources in the West US 2 region
- Virtual Machine
  - Ubuntu Server 22.04 LTS
  - Size: Standard_D2s_v3
  - Key based SSH authentication
  - 30 GB Premium SSD OS disk
  - 16 GB Standard SSD attached disk
  - Static Public IP: 20.51.117.5
- Networking (10.0.0.0/16)
  - Subnet 10.0.0.0/24
  - Subnet 10.0.1.0/24
- NSGs
  - ALLOW Inbound TCP port 22 (SSH)
  - ALLOW Inbound TCP port 80 (HTTP)

# Exported from Azure Resource Manager on January 29th, 2026

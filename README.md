# AWS VPC Peering Project

## Overview
This project demonstrates AWS VPC Peering between two custom VPCs enabling private communication between EC2 instances using private IP addresses.

---

## Services Used
- AWS VPC
- EC2
- Route Tables
- Internet Gateways
- Security Groups
- VPC Peering

---

## Architecture Details

### VPC-A
- CIDR: 10.0.0.0/16
- Public Subnet: 10.0.1.0/24

### VPC-B
- CIDR: 20.0.0.0/16
- Public Subnet: 20.0.1.0/24

---

## Steps Performed

1. Created two custom VPCs
2. Configured public subnets
3. Attached Internet Gateways
4. Configured route tables
5. Launched EC2 instances
6. Created VPC peering connection
7. Added peering routes
8. Verified private communication using ping

---

## Screenshots

### VPC Configuration
![VPC](screenshots/vpc.png)

### VPC Peering Active
![Peering](screenshots/peering.png)

### Route Tables
![Routes](screenshots/route-table.png)

### Successful Ping Test
![Ping](screenshots/ping-success.png)

---

## Outcome
Successfully established private communication between EC2 instances across different VPCs using AWS VPC Peering.

# T216B - TMA: Network Configuration (Static Route, HSRP & OSPF)

## Overview
This repository contains my TMA (Tutor-Marked Assignment) for the T216B Networking course. 
The project demonstrates the practical configuration of routing protocols and redundancy using Cisco Packet Tracer.

Author: Mohammed Haron Habbat

## Technologies & Protocols Used
- Static Routing: Configuration of manual routes between routers (R1, R2, R3).
- HSRP (Hot Standby Router Protocol): Implemented on R1 and R3 to provide gateway redundancy (Virtual IP: 192.1.0.3).
- OSPF (Open Shortest Path First): Single-area OSPF configuration (Area 0) across multiple routers (R1, R2, R3, R4).
- Switch Port Security: Configured on switch S1 to restrict MAC addresses and prevent unauthorized access.

## Repository Contents
- `Report.pdf`: The full lab report containing screenshots of the CLI configurations and connectivity tests.
- `T216B-TMA-FA2026-Q3-KSA.pkt`: Cisco Packet Tracer file for Question 3 (Static Route & HSRP).
- `T216B-TMA-FA2026-Q4-KSA.pkt`: Cisco Packet Tracer file for Question 4 (OSPF).
- `README.md`: Project documentation.

## Connectivity Testing
The report includes successful Ping tests from PC1 to remote networks (e.g., 172.16.1.10, 56.105.3.10, 172.56.1.10, and 172.56.2.10) to verify that the routing and HSRP configurations are working correctly.

## Academic Context
This project was completed as part of the T216B course requirements. It showcases hands-on skills in network design, router configuration, and troubleshooting.

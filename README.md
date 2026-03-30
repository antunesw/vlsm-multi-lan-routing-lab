# VLSM Multi-LAN Routing Lab

## 📌 Overview

This project demonstrates subnetting using VLSM and routing between multiple LANs connected via two routers.

## 🗺️ Topology


## 🌐 Network Design

| LAN   | Subnet           | Hosts |
| ----- | ---------------- | ----- |
| LAN A | 192.168.1.0/26   | 60    |
| LAN B | 192.168.1.64/27  | 30    |
| LAN C | 192.168.1.96/28  | 14    |
| LAN D | 192.168.1.112/29 | 2   |

## 🔗 Router Link

* Network: 192.168.1.116/30
* R1: 192.168.1.117
* R2: 192.168.1.118

## ⚙️ Features

* VLSM subnetting
* Static routing
* Inter-LAN communication
* Point-to-point WAN link

## ✅ Verification

* Successful ping between all LANs
* Verified routing tables

## 📂 Project Structure

* configs/ → router configurations
* verification/ → test outputs
* packet-tracer-file/ → lab file

## 🚀 Skills Demonstrated

* IP Subnetting (VLSM)
* Routing (Static)
* Network Design
* Troubleshooting

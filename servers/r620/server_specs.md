# R620 Server Specification

## Table of Contents
1. [Introduction](#introduction)
2. [Server Overview](#server-overview)
3. [Hardware Specifications](#hardware-specifications)
4. [Software Specifications](#software-specifications)
5. [Network Configuration](#network-configuration)

## Introduction
The purpose of this document is to provide a overview of the hardware and software requirements for my homelab Virtualization Server.

## Server Overview
- Server Name: prd-pve-01
- Server Type: Virtualization Server
- Purpose: Hosting virtual machines

## Hardware Specifications
- CPU:
    - Model: Intel Xeon E5-2660
    - Processor Count: 2 
    - Cores: 8 Cores / 16 Threads (16 Cores / 32 Threads)
    - Clock Speed: 2.20 GHz
- Memory (RAM):
    - Size: 128 GB
    - Type: DDR3
- Storage:
    - Type: SSD
    - Capacity: 500 GB
    - Drive Count: 9
        - OS: 1
        - Storage : 8
    - RAID Configuration: 
        - OS: None
        - Storage: RAID-Z2
- Network Interface:
    - Number: 4 Ports
    - Speed: 1 Gbps
- Power Supply:
    - Power Supply Count: 2
    - Wattage: 750 Watts

## Software Specifications
- Operating System:
    - Version: Proxmox 8.2

## Network Configuration
- IP Address:
    - Static IP: 192.168.3.3
    - Subnet Mask: 255.255.255.0
    - Gateway: 192.168.3.1
- DNS Servers:
    - Primary: 8.8.8.8
    - Secondary: 8.8.4.4
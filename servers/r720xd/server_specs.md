# R720XD Server Specification

## Table of Contents
1. [Introduction](#introduction)
2. [Server Overview](#server-overview)
3. [Hardware Specifications](#hardware-specifications)
4. [Software Specifications](#software-specifications)
5. [Network Configuration](#network-configuration)

## Introduction
The purpose of this document is to provide a overview of the hardware and software requirements for my homelab Storage Server.

## Server Overview
- Server Name: prd-truenas-01
- Server Type: Storage Server
- Purpose: File storage space

## Hardware Specifications
- CPU:
    - Model: Intel Xeon E5-2690
    - Processor Count: 2 
    - Cores: 8 Cores / 16 Threads (16 Cores / 32 Threads)
    - Clock Speed: 2.90 GHz
- Memory (RAM):
    - Size: 128 GB
    - Type: DDR3
- Storage:
    - Type: HDD / SSD
    - Capacity: 8 TB HDD / 500 GB SSD 
    - Drive Count: 14
        - OS: 2 (SSD)
        - Storage : 12 (HDD)
    - RAID Configuration: 
        - OS: Mirrored
        - Storage: RAID-Z2
- Network Interface:
    - Number: 4 Ports
    - Speed: 1 Gbps
- Power Supply:
    - Power Supply Count: 2
    - Wattage: 1100 Watts

## Software Specifications
- Operating System:
    - Version: TrueNAS Scale 24.04.2

## Network Configuration
- IP Address:
    - Static IP: 192.168.3.4
    - Subnet Mask: 255.255.255.0
    - Gateway: 192.168.3.1
- DNS Servers:
    - Primary: 8.8.8.8
    - Secondary: 8.8.4.4
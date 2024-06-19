# Interconnect Robots, Network Experiment, and Wireshark Analysis

This repository contains the project work for the "Interconnect Robots," "Network Experiment (Real-World or Emulation)," and "Wireshark Analysis and Firewall" tasks as part of the B205 Computer Networks module.

## Project Overview

This project is designed to transition a robotics manufacturer's communication setup from wired to wireless, conduct network experiments, and perform a Wireshark analysis to configure firewall rules. The tasks involve:

Designing a holistic concept for transitioning from wired to wireless communication.
Setting up and experimenting with a small network using either real-world hardware or network emulation.
Analyzing network traffic using Wireshark and creating appropriate firewall rules.

## Task 1: Interconnect Robots

This task involves developing a detailed plan to switch from a wired communication setup to a wireless one for a robotics manufacturer. It includes assumptions about the existing wired setup, a proposed wireless setup, and detailed explanations of changes at various network layers.

### Key Components:
Wired Setup: Uses EtherCAT, a star topology, hard-wired emergency stops, and teach-pendants.
Wireless Setup: Proposes TSN over IEEE 802.11 and 5G technology in a mesh topology, ensuring low latency and high reliability.
Protocol Design: Focuses on the MAC layer, including a Finite State Machine (FSM) and Message Sequence Chart (MSC) to illustrate protocol transitions and message exchanges.

## Task 2: Network Experiment (Real-World or Emulation)

This task involves setting up a small network, either using real hardware or an emulator like GNS3, and conducting experiments to test network communication.

### Key Experiments:
Topology 1: A simple network with two hosts and a switch, testing basic ping and tracepath commands.
Topology 2: Hosts in different IP ranges, requiring routing and testing the impact on communication protocols.
Helper Services/Protocols:
DNS Service: Resolves local hostnames to IP addresses for communication.

## Task 3: Wireshark Analysis and Firewall

This task involves analyzing a Wireshark dump to understand network traffic patterns and configuring firewall rules to protect the network.

### Key Analysis Points:
Flow Graphs: Visual representation of packet flow over time.
Packet Length Analysis: Distribution of packet sizes.
Firewall Rules: Comprehensive set of DROP/PERMIT rules based on the analysis to filter out unwanted traffic.

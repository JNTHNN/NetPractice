# NetPractice

**NetPractice** is a 42 school project designed to teach the fundamentals of computer networking. It provides a web-based simulator where you must configure small network topologies to allow machines to communicate with each other.

Through a series of 10 levels, this project introduces the core concepts of IP addressing, subnet masking, and routing.

## Goals

The objective is to successfully configure the interfaces and routing tables of various devices (hosts, switches, routers) to fulfill the requirements of each level. You will learn to:
- Understand IPv4 addresses and CIDR notation.
- Calculate subnets and identify network vs. broadcast addresses.
- Configure default gateways and static routes.
- Prevent routing loops and isolate specific subnets.

## Concepts Covered

### 1. IP Addressing & Subnetting
Every machine on a network needs a unique IP address. A subnet mask (like `255.255.255.0` or `/24`) defines which part of the IP address represents the network and which part represents the host. Devices in the same subnet can communicate directly.

### 2. Routing
When a machine wants to send a packet to an IP address that is not in its own subnet, it must send it to a router (the "gateway"). The router looks at its **routing table** to determine where to forward the packet next.
- **Default Route (`0.0.0.0/0`)**: The "catch-all" route used when no specific route matches the destination IP.

## Repository Contents

This repository contains the solution files for all 10 levels (`level1.json` to `level10.json`). These JSON files represent the valid configurations required to pass each stage of the simulator.

## Usage

To use these configurations:
1. Open the `net_practice` simulator provided by 42.
2. Load the corresponding level.
3. Apply the IP addresses, subnet masks, and routing rules as saved in the JSON files.

## Authors
- JNTHNN
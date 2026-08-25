# Configuration Notes

This repository contains a sanitized CORE topology file for a network configuration and security lab.

## Configuration Areas

- Static routing across multiple routers and network segments.
- DHCP configuration for client address assignment.
- Linux iptables firewall policy on R3.
- Default DROP posture with explicit allowances for expected traffic.
- DMZ/public service allowances and internal/external forwarding controls.

## Validation Approach

The project can be explained through connectivity and security validation:

- `ping` tests for basic reachability.
- `traceroute` tests for expected routing paths.
- Positive tests for allowed traffic.
- Negative tests for blocked traffic.

## Scope Note

This is a simulated lab environment in CORE. It is not a production enterprise deployment.

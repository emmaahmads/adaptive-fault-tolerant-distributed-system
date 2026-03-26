# Distributed High Availability System

This project is based on my Master's thesis, where I designed and implemented a fault-tolerant distributed system to improve system availability and reliability.

## Overview

The system transforms a single-node application into a distributed architecture with replication and automated recovery mechanisms to eliminate single points of failure. It achieves high availability through replication, heartbeat-based failure detection, and automated failover with proxy-level traffic redirection.

## System Architecture

<p align="center">
  <img src="images/overview.JPG" width="800"/>
</p>

## Failure Handling Flow

<p align="center">
  <img src="images/failover.JPG" width="800"/>
</p>

## Key Features

- Distributed system architecture with replicated modules
- Heartbeat-based failure detection using socket communication
- Automated failover and recovery mechanisms
- Neighbor-based replication strategy
- Improved system availability by ~70%

## System Design

The system consists of:
- Multiple application nodes (cluster)
- Monitoring component for failure detection
- Replication mechanism for redundancy
- Failover process for recovery

## Key Concepts

- Fault tolerance
- High availability
- Distributed systems
- Replication strategies
- Failure detection (heartbeat)
- System recovery

## Notes

This project focuses on system design and reliability engineering rather than UI or application-layer features.

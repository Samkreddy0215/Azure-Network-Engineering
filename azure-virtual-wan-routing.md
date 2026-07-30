# Azure Virtual WAN Routing

## Overview

Azure Virtual WAN is a managed networking service that provides centralized connectivity between branch offices, Azure Virtual Networks (VNets), remote users, and on-premises environments.

## Routing Components

- Virtual WAN
- Virtual Hub
- Hub Route Table
- Connection Route Table
- Route Propagation
- Static Routes

## Traffic Flow

1. Branch office connects to the Virtual Hub.
2. VNets connect using Virtual Network Connections.
3. Routes are propagated through the Hub Route Table.
4. Traffic is forwarded to the correct destination based on learned and static routes.

## Common Use Cases

- Multi-region Azure deployments
- Hybrid cloud connectivity
- Branch-to-branch communication
- Secure internet breakout
- Centralized network management

## Verification Checklist

- Verify Virtual Hub connectivity.
- Confirm route propagation.
- Validate effective routes on connected VNets.
- Test branch-to-VNet communication.
- Review Network Watcher diagnostics.

## Best Practices

- Use separate route tables for different environments.
- Enable route propagation only where required.
- Document hub-and-spoke topology.
- Monitor routing changes regularly.
- Validate failover after topology updates.

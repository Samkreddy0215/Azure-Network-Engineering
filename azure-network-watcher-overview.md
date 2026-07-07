# Azure Network Watcher Overview

## Overview

Azure Network Watcher is a regional service that provides monitoring, diagnostics, and troubleshooting capabilities for Azure virtual networks and hybrid cloud connectivity.

## Key Features

- Topology Visualization
- Connection Monitor
- IP Flow Verify
- Next Hop
- Effective Security Rules
- NSG Flow Logs
- Packet Capture
- VPN Diagnostics

## Common Use Cases

- Verify VM connectivity
- Troubleshoot Network Security Group (NSG) rules
- Identify routing issues
- Monitor ExpressRoute and VPN connectivity
- Capture packets without logging into the VM

## Validation Steps

1. Enable Network Watcher in the Azure region.
2. Verify VM connectivity using Connection Monitor.
3. Check effective NSG rules.
4. Validate the next hop for traffic.
5. Review NSG Flow Logs for denied traffic.
6. Use Packet Capture for deep packet analysis.

## Best Practices

- Enable Network Watcher in every production region.
- Retain Flow Logs in a secure storage account.
- Integrate diagnostics with Azure Monitor.
- Use Connection Monitor for critical workloads.
- Regularly review routing and security diagnostics.

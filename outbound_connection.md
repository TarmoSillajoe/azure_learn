---
tags:virtual_network
---
[link]([Default outbound access in Azure - Azure Virtual Network | Microsoft Learn](https://learn.microsoft.com/en-us/azure/virtual-network/ip-services/default-outbound-access))

## What is default outbound access?
Virtual machines are assigned a **default public ip**, unless you explicitly set the outbound connection.
- Your service is opened to the internet
- You do not own the IP-address. The address belongs to Microsoft and is subject to change.
### Choosing your own outbound access
[NAT gateway](nat_gateway) is the recommended way.

<h1 align="center">Virtual Private Cloud (VPC)</h1>

A virtual private cloud (VPC) is a virtual network dedicated to our AWS account. It is logically isolated from other virtual networks in the AWS Cloud.

**The following are the key concepts for VPCs:**

+ **Virtual private cloud (VPC)** — A virtual network dedicated to your AWS account.<br />
+ **Subnet** — A range of IP addresses in your VPC.<br />
+ **Route table** — A set of rules, called routes, that are used to determine where network traffic is directed.<br />
+ **Internet gateway** — A gateway that you attach to your VPC to enable communication between resources in your VPC and the internet.<br />
+ **VPC endpoint** — Enables you to privately connect your VPC to supported AWS services and VPC endpoint services powered by PrivateLink without requiring an internet gateway, NAT device, VPN connection, or AWS Direct Connect connection. Instances in your VPC do not require public IP addresses to communicate with resources in the service. Traffic between your VPC and the other service does not leave the Amazon network.<br />

**Accessing Amazon VPC** <br />
+ We can create, access, and manage our VPCs using any of the following interfaces: <br />
+ AWS Management Console — Provides a web interface that you can use to access your VPCs. <br />
+ AWS Command Line Interface (AWS CLI) — Provides commands for a broad set of AWS services, including Amazon VPC, and is supported on Windows, Mac, and Linux.
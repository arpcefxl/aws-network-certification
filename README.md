# aws-network-certification

Materials for AWS Certified Advanced Network Specialty Certification Crash Course.

*Pre-reqs:* Familiarity with the [OSI Model](https://www.imperva.com/learn/application-security/osi-model/) and [IPv4 subnetting](https://www.techrepublic.com/blog/data-center/ip-subnetting-made-easy-125343/).

## AWS

### Billing

* [Twitter: AWS Data Transfer Costs](https://twitter.com/QuinnyPig/status/1172239124251709449/photo/1)
* [AWS Direct Connect pricing](https://aws.amazon.com/directconnect/pricing/)
* [Amazon CloudFront Pricing](https://aws.amazon.com/cloudfront/pricing/)
* [AWS VPN pricing](https://aws.amazon.com/vpn/pricing/)
* [AWS Transit Gateway pricing](https://aws.amazon.com/transit-gateway/pricing/)

### Direct Connect

* [AWS Direct Connect: Getting Started](https://aws.amazon.com/directconnect/getting-started/?nc=sn&loc=4&dn=1)
* [AWS Direct Connect virtual interfaces](https://docs.aws.amazon.com/directconnect/latest/UserGuide/WorkingWithVirtualInterfaces.html)

### VPC

* [Amazon Virtual Private Cloud Documentation](https://docs.aws.amazon.com/vpc/index.html)
* [VPCs and subnets](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Subnets.html)
* [Network-to-Amazon VPC connectivity options](https://docs.aws.amazon.com/whitepapers/latest/aws-vpc-connectivity-options/network-to-amazon-vpc-connectivity-options.html)
* [Slideshare: Amazon VPC: Security at the Speed Of Light (AWS re:Invent 2018)](https://www.slideshare.net/AmazonWebServices/amazon-vpc-security-at-the-speed-of-light-net313-aws-reinvent-2018)
* [VPC Flow Logs](https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs.html)
* [Flow log record examples](https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs-records-examples.html)

### Security

* [Overview of AWS Security - Network Security (PDF - 2016)](https://d1.awsstatic.com/whitepapers/Security/Networking_Security_Whitepaper.pdf)
* [Amazon EC2 security groups for Linux instances: Connection tracking](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-security-groups.html#security-group-connection-tracking)
* [Building a Scalable and Secure Multi-VPC AWS Network Infrastructure (PDF - 2020)](https://d1.awsstatic.com/whitepapers/building-a-scalable-and-secure-multi-vpc-aws-network-infrastructure.pdf)

## Layer 2

* [Wikipedia: IEEE 802.1ad - VLAN Stacking or QinQ](https://en.wikipedia.org/wiki/IEEE_802.1ad)

## Layer 3

### BGP

* [Cisco: BGP Best Path Selection Algorithm](https://www.cisco.com/c/en/us/support/docs/ip/border-gateway-protocol-bgp/13753-25.html)
* [Google Sites blog: BGP AS-Path Prepending and AS-Path Filters](https://mobile.sites.google.com/site/amitsciscozone/bgp/bgp-as-path-prepending-and-as-path-filters)
* [Cisco: How BGP Routers Use the Multi-Exit Discriminator for Best Path Selection (CCO Account Required)](https://www.cisco.com/c/en/us/support/docs/ip/border-gateway-protocol-bgp/13759-37.html)

### VPN

* [Site-to-Site VPN routing options](https://docs.aws.amazon.com/vpn/latest/s2svpn/VPNRoutingTypes.html)

### Layer 7 Services

#### DHCP

* [DHCP options sets](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_DHCP_Options.html)

#### DNS

* [Choosing a DNS routing policy](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html)
* [How Amazon Route 53 uses EDNS0 to estimate the location of a user](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html#routing-policy-edns0)
* [How can I determine whether my DNS queries to the Amazon provided DNS server are failing due to VPC DNS throttling?](https://aws.amazon.com/premiumsupport/knowledge-center/vpc-find-cause-of-failed-dns-queries/)
* [How to Set Up DNS Resolution Between On-Premises Networks and AWS Using AWS Directory Service and Amazon Route 53](https://aws.amazon.com/blogs/security/how-to-set-up-dns-resolution-between-on-premises-networks-and-aws-using-aws-directory-service-and-amazon-route-53/)
* [Hybrid Cloud DNS Options for Amazon VPC (PDF)](https://d1.awsstatic.com/whitepapers/hybrid-cloud-dns-options-for-vpc.pdf)
* [How to Set Up DNS Resolution Between On-Premises Networks and AWS Using AWS Directory Service and Microsoft Active Directory](https://aws.amazon.com/blogs/security/how-to-set-up-dns-resolution-between-on-premises-networks-and-aws-using-aws-directory-service-and-microsoft-active-directory/)
* [Amazon Route 53 Resolver for Hybrid Clouds](https://aws.amazon.com/blogs/aws/new-amazon-route-53-resolver-for-hybrid-clouds/)

#### Load Balancing

* [Application Load Balancers Now Support Multiple TLS Certificates With Smart Selection Using SNI](https://aws.amazon.com/blogs/aws/new-application-load-balancer-sni/)
* [Listeners for your Application Load Balancers: Rule action types](https://docs.aws.amazon.com/elasticloadbalancing/latest/application/load-balancer-listeners.html#rule-action-types)

#### Lambda@Edge

* [Slideshare: Securing Your AWS Infrastructure with Edge Services (May 2017 AWS Online Tech Talks)](https://www.slideshare.net/AmazonWebServices/securing-your-aws-infrastructure-with-edge-services-may-2017-aws-online-tech-talks)

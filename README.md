> **Update:** Hello! As of 1 January 2017 this content is no longer being actively managed and updated. It is provided as-is and may contain information that has changed. Any Issues will be addressed on a best-effort basis. Please see [Azure.com](http://www.azure.com) for the latest guidance. Thank you for your understanding.

---

# Networking

Virtual Networks provide a layer of isolation for your compute and data resources in the cloud and are can be carved up into subnets like an on-premises network.  However, Azure Virtual Networks don't have to be isolated to cloud-only deployments.  In fact, it is common for today's Solution Architect to have to bridge the gap between on-premises and cloud environments.  See how you can extend an on-premises network to Azure Virtual Networks using point-to-site, site-to-site, and private connections using ExpressRoute.  Understand scenarios appropriate for each solution.  Then, see how to conquer multi-site networking topologies and how network security groups and access control lists can be used to further protect resources.  Finally, understand how to leverage the load-balancing features of Azure (internal and external) to achieve highly available architectures.


## Presentation

Download the [PowerPoint](Networking.pptx).
The PowerPoint includes full speaker notes helping you understand the slides, and everything you need to deliver the session.

## Demos

* Traffic Manager
[[Demo script & source code](./Demo-TrafficManager/)]
[[demo video](https://azurecatgsicontent.blob.core.windows.net/networking/TrafficManager.mp4)]

* User Defined Routes
[[Demo script & source code](./Demo-UserDefinedRoutes)]
[[setup video](https://azurecatgsicontent.blob.core.windows.net/networking/Networking-UDR-Demo-Setup.mp4)]
[[demo video](https://azurecatgsicontent.blob.core.windows.net/networking/Networking-UDR-Demo.mp4)]

* Network Security Groups
[[Demo script & source code](./Demo-NetworkSecurityGroups/)]
[[demo video](https://azurecatgsicontent.blob.core.windows.net/networking/NSG.mp4)]

## Session objectives

* Understand Hybrid-Networking options
* Understand how to configure Traffic Manager
* Understand how to configure user defined routes
* Understand how to configure network security groups
* Understand when to use Application Gateway

## Session Prerequisits

- Knowledge of Azure Virtual Machines

These prerequisits are covered in the [[Compute](https://github.com/GSIAzureCOE/Compute)] session.

## Azure Services Covered

- [[Virtual Networks](https://azure.microsoft.com/en-us/documentation/services/virtual-network/)]
- [[Network Security Groups](https://azure.microsoft.com/en-us/documentation/articles/virtual-networks-nsg/)]
- [[User Defined Routes](https://azure.microsoft.com/en-us/documentation/articles/virtual-networks-udr-overview/)]
- [[Traffic Manager](https://azure.microsoft.com/en-us/documentation/services/traffic-manager/)]
- [[ExpressRoute](https://azure.microsoft.com/en-us/documentation/articles/expressroute-introduction/)]

## Code of Conduct

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.




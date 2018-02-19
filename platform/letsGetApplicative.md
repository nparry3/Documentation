# Let’s get Applicative

   * [Intro](#intro)
      * [Datacenter Tooling](#datacenter-tooling)
      * [Engineering Tooling](#engineering-tooling)
   * [Summing Up](#summing-up)

# Intro
In other sections, we have alluded to many of the RelateID Community Platform (RCP) capabilities and how we will be leveraging community tooling to support it. This ensures best in architecture and design, tooling, security, and a million other things.

Although this choice was evident from the beginning, a few points worth noting… The tools:
* selected are familiar to a large audience
* selected are popular and maintain significant market share
* are for the core RCP functionality are open source. Peripherals may not be
* maintain large communities
* are well documented
* are under active development

## Datacenter Tooling
Kubernetes1 will be the datacenter OS RCP is built upon. Kubernetes is an open source container management system that is built by the community for the community. Its reliable, battle tested, popular, and extremely configurable. Additionally, it is backed by an extended community of products and tooling required by enterprise customers through which the RCP will thrive. Also, Kubernetes is a container management platform. As a result, application developers are free to create services in any language they choose.

Going further, Kubernetes is part of the Clout Native Cloud Computing Foundation (CNCF)2. This community's efforts will also be integrated into the RCP as it enriches the platform considerably.

Of note, the CNCF and Kubernetes communities are innovating quickly. Today Docker is selected as the container of choice. However, rkt and others are challenging them in a healthy way. Docker, and all its rivals, have been working collaboratively to abstract the concept of a container such that any container variant will run on Kubernetes. Some of the most interesting projects are working on unikernals. As unikernals mature, along with their advantages, RCP will be prepared to take advantage of them. 

Finally, Kubernetes has defined many levels of abstraction within its architecture. As this is available to the service developers, they would be able to take advantage of them when producing their service. For example:
* Daemon sets: Guarantees a given pod will execute on each node. Logging, metrics, monitoring, etc.
* Initializers: Executed during time of creation. For example, Istio injects a sidecar into each pod as it's created. It is then able to proxy calls to the deployed service. This allows for security, circuit breaking, routing, and reporting capabilities.
* Ingress: L7 routing requests from the outside into the cluster. Products such as Traefik4, Ambasador5, and others are already available.
* Custom Resource Definition (CRD): For creating your own custom functionality into native Kubernetes.
* RBAC: Fine grained access api. Services will be able to provide security rules to increase their products integrity and appeal
* And more: Custom api servers, controllers, resources, roles, etc. Almost anything you can think of.

Additionally, the ecosystem supporting Kubernetes provide capabilities that the RCP plans on leveraging. Some, but not all, are: 
* Secure Networks: Tools such as Project Calico6 and Flannel7 provide low level (L2) monitoring, SDN, and security at scale.
* Operational Monitoring: Prometheus8, OpenTracing9, fluentd10, and others allow for cluster monitoring at scale.
* Cluster Health Check: Tools like Sonobuoy from Heptio11 can be run on a cluster to ensure it is installed and configured correctly.
* Service Catalogue: Kubernetes is building an implementation12 of the of the Open Service Broker API13. This is part of a larger community effort, involving many vendors and service providers, to define a global standard for publishing to a service catalogue.

It is important to note that, although the above capabilities are available, it is assumed that a large portion of the developer community will not need to leverage them when creating their service. Once a service is deployed, it will simply plugin to its surrounding. Billing, logging, updates, etc. will all be orchestrated through the customer's selected capabilities in isolation.

In conclusion, Kubernetes is a platform rich in capabilities, support, documentation, and services. It provides the right levels and areas of abstraction on which the RCP will be able to be built securely, reliably, and with confidence. Additionally, the core Kubernetes team have a clear vision of the boundaries of the tool. For a while, the team was adding feature after feature to the core. However, they cannot keep up with demand, nor do many of these facets belong in the core code base. As a result, they have begun working towards an eco-system in which pluggability is paramount. Developers will be enabled to create their feature without the need to gain a broader community consensus. The end result will be a platform that focuses on its core responsibilities, thereby setting the foundation for a growth in its own innovation.

## Engineering Tooling
This section details the strategy on maximizing our potential for enticing engineers to participate in the RCP. The strategy boils down to two important facets:

* Have engineers leverage the tools they use today when creating their services
* RelateID team to create additional tooling, with community standards, that simplifies the publishing of services and products

On the first point. As we deploy in services through containers, developers are free to continue writing code in whatever language they choose. Additionally, they are free to use the IDE’s and tooling they are most familiar with.

With regards to the second point, the RelateID team will publish tools for engineers to use when generating and/or packaging their product. For example, a Yeoman generator14 that set up the scaffolding for the engineer based on industry best practices and tooling.

Additionally, product level tooling that facilitates the ‘wiring’ of multiple services. This tool is envisioned to be as simple as dragging and dropping services together. In this way, less technical entrepreneurs are able to create products without knowledge of the underlying applicative architecture. Finally, this tooling will provide mechanics that enable product level tooling to test themselves and integration between components, thereby ensuring a distributed application portfolio that is foundationally sound and secure.

Going further, within this ecosystem, a market place will be generated to meet the demands of the engineering community. Services will be constructed that allow developers to sandbox their efforts, during development, easing the burden of developing services on the RCP.

In conclusion,the RCP will integrate seamlessly with current engineering tooling and methodology. Additionally, tools will be created in order to facilitate the inclusion of efforts by providers who are not sophisticated on the DL technology. Finally, the potential for new ecosystem focused on engineering tooling is expected to emerge.

# Summing Up

RelateID intends to leverage the best open source tooling available in order to build ontop of the amazing work that the community has already given. We do not want to get in the business of trying to build better mouse traps. This is in sharp contrast to many of the other teams out in the wild today whom seem to be trying to solve the same problems that these kinds of tools have already solved. 
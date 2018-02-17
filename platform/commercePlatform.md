# Commerce Platform

# Disclaimer
This document is vague on blockchain complexities and the mechanics of decentralized trustless computing. Much has already been written in this area and it is assumed that the reader is familiar with blockchain techniques and implementations. As a result, this paper will primarily focus on the components outside of the core blockchain technology.

[RelateID Documentation](../README.md) provides the full list of whitepapers for additional resources.

# RelateID Commerce Platform (RCP)

![Meta](/images/gateway.png)

The RCP has three primary abstractions:

* Bazaars are where goods and services avialable to the platform are sold. Store fronts for the underlying 'services' of the commerce platform
* Services are the underlying functions available on the platform. These functions can be datacenters and/or dapps and/or collections of dapps. Anyone will be able to develop services for the platform using the tooling and frameworks they are most comfortable with
* Gateways are the communication between bazaars and services, as well as, services and services. Gateways manage any contract resolution required by the service. In short, gateways consolidate billing and manage state-channels. Note that the assignment of a gateway is the responsibility of the service provider. The consumer can choose to accept the gateway or not.

The platform will support the chaining of any number of bazaars to any number of services. For example, a service on the Bazaar may need to compose with other services. This relationship can be visualized as follows:

![Meta](/images/CommerceMeta.png)

Due to the design, complex scenarios of configuration will be supported. An example complex relationship can be visualized as follows:

![Complex Chaining](/images/ComplexChaining.png)

Not present in the above, is a services abity to be leveraged by many bazaars and services through a single gateway. This relationship can be visualized as follows:

![Single Gateway](/images/SingleGateway.png)

Additionally, services will also have the ability to manage separate gateways for separate consumers. For example, services may have commercial lines as well as free licenses available to the consumer that will be attached during the point of sale. This relationship can be visualized as follows:


![Multi Gateway](/images/MultiGateways.png)

Finally, the bazaars interactions with its consumers will act in the same fashion. As follows:

![Multi Gateway](/images/consumergateway.png)

## Summing Up

In conclusion, the systems can be abstracted to 3 distinct components. These components aid in understanding the relationships between bazaars and the underlying services they sell. Additionally, through dynamic injectable gateways, service requirements, contracts, and payments can be orchestrated in an automated way. This allows for entrepreneurs to distribute their products and consumers to buy them in an independent and autonomous way.

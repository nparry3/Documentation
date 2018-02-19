# Layers of Economy

   * [Intro](#intro)
      * [Technologists](#technologists)
         * [Miners](#miners)
         * [Datacenter Operators (DcO's)](#datacenter-operators-dcos)
         * [Developers](#developers)
      * [Business](#business)
         * [Skilled Worker](#skilled-worker)
         * [Product](#product)
         * [Bazaar](#bazaar)
      * [Sovereign Entities](#sovereign-entities)
         * [Users](#users)
         * [Organizations](#organizations)
   * [Summing Up](#summing-up)

# Intro

The RCP aims to create an ecosystem for entrepreneurs. With enhancements in infrustructure, ai, blockchain, and robotic, jobs are destined to be lost. Autonomous vehicles will replace truck drivers and taxi cabs. Other areas of AI are already disrupting services in FinTec as well disrupting well established ‘white collar’ jobs such as law.

As a result, many are concerned with becoming outdated and obsolete. It has many imaging dystopia outcomes for all. In sharp contrast, we believe that we are now entering the age of the entrepreneur. An age in which it is as easy to set up your business as it is plugging a lamp into the wall. An age of specialty services at the micro level of intent that is hyper-focused and hyper-regional.

Because of this broad stroke and the opportunities, it enables, we need to begin in abstracting the various, high level, services that the RCP facilitates. This will help us in describing and semantically aligning the various use cases.

The economy can be visualized as follows:

![Meta](/images/layersofeconomy2.png)

## Technologists

At the lowest level of the commerce architecture is the technologists. These are individuals whos craft it is to develop functional services in the platfom. The base building blocks. The technologists will be able to develop with familiar tooling and methods. For example, the datacenter operator leverages K8S as its main operational system. Similarily, developers will be able to write applications using languages that they are familiar with such as Go, Javascript, etc. In essence, if you can containerize it and deploy it to K8S you can use it.

![Meta](/images/technologists.png)

### Miners

Miners will be required to manage the blockchains distribution. This section does not go into details about managing, govern, or monitize miners, however, they are seen as an intregral part of the systems economic success. Note that the role of the miner is similar to most blockchains.

### Datacenter Operators (DcO's)

Currently we are seeing the centralization of cloud infrastructure into the hands of a few. This has resulted in lack of choice, centralization, and generalization over specialization.

If we ask ourselves why this trend continues, and its barrier to decentralization, it’s because all of these services (cloud providers) have one function that impedes others to enter the market place. The providers manage a billing system for users to manage compute resources. That’s it. It is true that all these vendors have built up additional services to ‘sweeten the pot’, however, at their core function, it is just a utility billing system. 

For comparison, Google is an advertising platform. It has many functions and utility that generate user adoption, however, its core function remains that of an advertising service. The same is true of cloud providers. The core is billing.

With this idea in mind, RCP will provide gateways that enable individual DcO’s to offer compute resources to the public at large. A DCO will be enabled to set up a hosted environment and bill for the usage of the service.  As a result, DCO’s will be free to focus on services offerings and capabilities that differentiate them in the marketplace. For example, A DCO may provide a service that is focused on IoT and the management of data and services around this market. In this way, DCO’s are able to innovate upon the marketplace with a narrower intent than the current range of large cloud providers. As a result, DCO can specialize, rather than generalize to produce a factor of differentiation.

Of course, IoT is a simple use case, and there exists many. Security, audits, compliance, AI, etc. are all specific requirements that DCO’s may monetize upon.

Note that in order to manage a DCO, operators will need to provide stake. This stake is the accumulated 'trust' score and 'token' amount. Other whitepapers will provide more detailed requirements for datacenter operator.

### Developers

Developers are considered a skilled resource, empowered within the architecture, to deliver services that integrate into the RCP ecosystem. Developers are considered anyone who writes code. This can be code for an application, smart contract, platform components, infrustructure, ai, etc.

The development community has fostered and embraced the concepts of open source. Individuals are improving and providing value constantly, however, developers who wish to monetize on their contributions are left to their own devices. This works in some cases where the offering is large in scope, however, it quickly breaks down as scale diminishes.

With this in mind, the RCP will provide gateways and mechanics for developers to create executable services and sell them in a bazaar or other services however they choose.

As an example, the developer has created a private chat service. This chat service provides permissions management, content management, and whatever else people want in a chat client. The developer may then choose a gateway and publish its service into a bazaar or be consumed by other services.

The difference in the Relateid model is that the developer is not interested in hosting or running the service. The developer is only interested in continuing to improve the chat service. In a traditional model, the developer would need to set up a hosted cloud environment, manage security, availability, accounts payable, accounts receivable, and a million other issues. By developing on top of RCP, the developer is able to utilize the platforms deployment and payment services as a way of deploying the software without the incumbance of a traditional options.

Going further, the client requesting the chat service will be free to choose which DCO to host the service on outside of the developers interest. During and after deployment the gateways will ensure contact management and monetizational assurances.

Finally, it is worth mentioning that a developer will be free to offer their services as a skilled resource. Skilled resources are covered in the following section.

## Business

The business section of the economy is focused on highlighting areas in which entrepreneurs can create businesses and provide services for the various bazaars. This section is focused at people who may not have the background to develop technology components for the datacenters or miners. These economic actors are focused on the building and management of business services. These businesses will be self managed, however, will need to manage stake in accordance with the RCP guidelines. These guidelines will be outlined in future papers.

![Meta](/images/businessEconomy.png)

### Skilled Worker

Individuals will have the ability to contribute their real life skills as a commodity available for trade. For example, developers may offer their skills to entrepreneurs seeking to develop products. However, other skills outside of technology will also be able to be commoditized on the platform. Maid services, driver services, gardening, handyman, etc.

By identifying the skills marketplace as a first-class identity in the RCP (RelateID Community Platform), real work skills and assets will be marketable, consumable, and composable.

In order to achieve this, as will provide the DCO with gateways for the marketplace to leverage when building up these potential lines of business. Billing will become transparent, secure, and guaranteed for all parties.

### Product

Products are where lower level services are composed into a larger service offering. For example, an individual wants to create a 'start-up' product. This product will need many componenst such as timesheet management, agile boards, build servers, environments, etc. Because of the systems archicture, the entrepreneur would be able to 'plug' other services available on the platform together into a holistic 'start-up' product. These product owners would then be able to manage upgrade lifecycle as well as additional services on top of the product.

Products are what the consumers of the platforms will interact with through the bazaars. They are holistic and driven by a business case. Successful products will meet client expectations at the business level rather than at the technical level.

As with the engineering services, products need not go through the trials and tribulations of setting up cloud accounts, etc. As RCP provides the required abstractions (gateways and messaging (detailed below)) for disparate executable services to follow, they will be easily composed by the product provider in a systematic and reliable way.

Finally, as with all other layers of the ecosystem, products have gateways and the services they leverage also have gateways. The result being billing is managed transparently for all parties.

### Bazaar

Bazaars are viewed as the top level of service. This is the ‘front door’ for the consumer to search, evaluate, and buy services from the community. Astute readers will note that a Bazaar is in fact just another type of service, however, the semantic classification is deemed essential in providing a vision for the community to adopt. Additionally, bazaars will include ways for users to manage their data and consolodated billing which no other service offers.

With this in mind, the Bazaar will focus on grouping services in order that the consumer is given a choice when selecting a service. For example, a bizaar may choose to focus on 'start-up kits'. Each one may have different types of capabilities in order to target appropriate use cases. Note that each one of these starter kits may use some of the same services underneath them. For example, the same generic chat service may be something found within many different starter kits.

As the bazaar are the most visible service provided by the platform, they are able to append additional services that differentiate them from competitors. For example, a bazaar may have a rating capability gathered through customer feedback. Additionally, it may have another rating service that uses AI in collecting information about products and services from services outside of RCP. For example, LinkedIn, Facebook, Github, etc. In short, a successful bazaar will provide the consumer with confidence when leveraging the RCP.

In another use case, bazaars may differentiate themselves from the competition is by providing services for compliance. For example, if a customer requires that its data centers must remain within a region, a Bazaars would be able to manage this expectation for the customer. This scenario would require some form of real-world guarantee. An assurance of that these goals are met. In order to achieve this, the bazaar may need to provide a business license and any certificates or accreditation, in order to guarantee a level of compliance to the customer. Of course, as the operational overhead of this bazaar is higher than others, they would be able to charge a premium for their services.

Note that this would extend, in a future state, to governments having bazaar services that have been guaranteed, by said government, to be in compliance with regulations. Services on that bazaar may charge a premium due to the amount of overhead a government would impose upon them. 

It is worth pointing out that, at this level, the blockchain and state-channels have been completely abstracted away. As a result, entrepreneurs are only limited by their imaginations. Additionally, as with the products and DCO’s, RCP will provide the gateways required for businesses to be built without the need to handle the complexities of setting up an online business. In effect, becoming an online retailer is considerable easier than in the past. No need to invest, as Amazon and others have done, in managing the tedious tasks required for a digital presence.

To drive this point home, bazaars may choose to build themselves on top of DCO’s available in the ecosystem. In effect, they will have no datacenter to manage. Gateways handle billing. Additionally, it is envisioned that services specific to Bazaars may begin to emerge. For example, an AI for product recommendations. Personalization engines. Ad campaign managers. As a result of this, as the platform matures, bazaars will be easier and easier to envision, assemble, deploy and monetize.

## Sovereign Entities

This section of the diagram represents the indivisuals and organizations that leverage the network. In essence, as each entity controls and owns its data, it is also free to monetize it should it so choose.

![Meta](/images/sovereignCommerce.png)

### Users

Individuals on the system. These individuals manage who and what can access their data. In this manner, users are free to share or sell portions of their data to third parties. It will be completely in the control of each user.

### Organizations

Organizations work much the same as users in that they own their data and the access to it. As a result, should they so choose, organizations can share and monetize any data assets they like.

# Summing Up

By providing a clear delineation of economic participants, individuals are guided into the network in a soft-handed way. In essence, the system has been designed to allow individuals to interact with the platform in a friendly and familiar way from the lowest level of technologists to the highest level of enterprise.

# Next Gen Telecommunication Impact on Business and Solution Engineering

This article is focused on how the technology revolution is unwrapping, fastening, enabling business decisions, and creating new business verticals. Will discuss how the businesses have utilized the newer communication systems ahead of time to make a company or dissipate. Monitoring the communication system progression and implementing in business model is a keystone to write their own success story. It also covers how next-generation telecommunication is creating new business opportunities and maximizes the result using a wearable device, IoT, BOT, XR, virtualization, cloud solutions. This article doesn’t cover the new solution engineering offered by next-generation compute power (HPC), shared memory (IPC), Network on Chip (NoC), NVMe protocol to provides high throughput capabilities (Data analytics, AI, etc..).

## Learning from telecommunication history

AT&T (Bell lab), the mighty monopoly as a universal communication service provider company, after 100 years of monopoly in telecommunication, lost the market leadership in the early 20th century because of its wrong prediction on wireless communication impacts, and its monopoly was systematically brought down through FCC. Though AT&T launched its first communication satellite in 1962 for long-distance wireless communication. Tracking and adapting new communication methodologies are key for business success.  
 
Walmart launched its private satellites in 1987 to centralize its store operations and for their disaster recovery plan, though it comes with higher latency. It became fruitful to expand their stores outside of the US in the late 20th century when other retailers couldn't even think of expanding their presents outside of their continent.  That's the power of adopting a communication system ahead of time.

4G has helped to multiplex the resource utilization and gave higher network bandwidth with lower latency. Broadband and FTTH have given reliable communication as well. These new capabilities have changed human life once forever and have created new multitrillion-dollar business verticals like eCommerce, VoIP, interactive multimedia, virtual-banking, on-line trading, etc... eCommerce business has adversely impacted the traditional retail model and created new B2B and B2C environments. VoIP has created a new revolution in the multibillion-dollar telecommunication industry which replaced the heavily hardware intensive and expensive packet-switching infrastructure.

Keep the tap on telecommunication changes and adhere in business are keystones for Forward-looking companies
 
## Disruptive technology revolutions for the last two decades

The below technologies have changed the perspective of IT service from supportive service to part of the business service and even became a business enabler. These disruptive technologies had changed solution engineering. 
* Moved from lesser performance, less scalable RDBMS to open source No-SQLs (Cassandra, MongoDB, CockroachDB, etc…) with less to no compromise on CAP/ACID/BASE requirements for non-transactional data, in some case transactional data as well with few fine-tunings.
* Moving from the resource-intensive, less scalable, monolithic application development language/methodologies to the minimum resource-usage, on-demand scalable, service-oriented application language/development. Use the compiler-based language for server-side programming, use interpreter-based language for client-side programming and get rid of the languages that do both which are resource-intensive. It’s a choice between higher performance and quick development based on NFRs (Non-functional requirements).
* Moved from a monolithic to containers and hypervisors as the increased resource utilization and on-demand scalability, increase in portability and gave better HA with less resource usage.
* Moving from a monolithic application to docker container, SAS, Serverless Arch, even moving to vendors’ cloud SAS solution for non-business critical functionalities and based on their data classification.
* Moved to HTTP Cache at the “Edge Computing” for all non-transaction data and low volatile data (> 1 sec) gives better user experience (performance, fault tolerance, reduced load to the content origin server), increase the security (from DDoS attack, secured connection to the origin server),. It became inevitable for all larger user-based web content delivery.
* Moving from persistent storage (Block Storage, File storage) to in-memory cache as the increase in storage reliability for volatile data, and Object Storage for non-transactional data for less TCO (Total Cost of Ownership).
* Moved from TCP (greater computation overhead to ensure reliable delivery) to UDP (Connectionless, checksums for data integrity) based communication as the increase in network packet delivery reliability. It helps to maximize the network resource instead of holding a persistent connection.
* Moved from synchronized communication to asynchronous communication had multiplexed the infra resources utilization (specifically IOPS) and cost-effective scalable system, which intent brought a lot of changes in solution designing (Event-driven, Non-blocking, SOA, push/pull communication, IO caching, Micro Service architecture, Streaming architecture, etc...). Most of the new age tools (Kafka, Camel, Spark, Storm, Splunk, Ngnix, HAProxy, Chef, K8S, Docker, Open Stack, Redis, NodeJS, AJAX, React, Ratpack, Apigee, Varnish, AIOPs tools, Spinnaker, Console, ELK Stack, etc..) uses async communication.
* Moved from physical infrastructure to virtual infrastructure as the need to increase infra resource utilization and on-demand provisioning. Moved from hardware-based load balancing, routing, switch, storage (NAS, SAN), racks of servers to software-based infrastructure had reduced the TCO and agility to build the environment on the fly.
* Moving from expensive Redhat/MS OS-based clustering to cloud env clustering (K8S, AWS, GCP) has changed the application scalability, availability, resource utilization, and TCO.
* Moved from bare mettle server to inhouse VM and then cloud infra (like Open Stack) as the increase in network stability, improvement in interoperability, and cloud-agnostic capability to reduce the operation cost and enables on-demand scalability.
* Moving to IPv6 has opened the window for a large number of IoT-connected devices and collect data from a larger volume of IoT devices.
* Moved from Active, Passive mode of infrastructure to Active, Active mode has increased the infrastructure utilization, using OSS to reduce the TCO.
* Being moved from licensed/Proprietary software to OSS has increased the nimbleness, innovation, customization, community support, better integration, and reduced dependency and TCO.  

Many more reasons for these technology changes were adopted by forward-thinking businesses, based on their data classification, to create their success stories. These technologies gave their agility, scalability, and ability to get the right information available at the right time to make the right decision.

But still, we are **waiting for a better technological solution for a few requirements**. Some of these are 
* Moving from physical to virtual service industries (like healthcare), AR, XR, the gaming industry are required high speed and low latency network for each end-user that will lead to aggressive bandwidth demands.
* For web content delivery, we heavily rely upon CDN (Content Delivery Network) across the globe to reduce the number of hopping to minimize the latency. Infra cost is escalating because of the undersea cable networks, security risk (availability), and duplication of the region-based data center. The long-distance undersea network increases the latency for real-time data analysis from various sources.
* For transactional and non-volatile data, higher data redundancy, higher frequency of backup, and point in time recovery requirements have increased the TCO because of less reliance on data availability.
* Low latency requirement has pushed some of the business verticals to keep DR (destroy recovery) center near to primary DC which is not fully meeting the DR purpose.
* Scarcity of network availability within a private network or private virtual network is continuously increasing the TCO for ever-increasing higher network demand. Data segregation and Network tunneling are not a sustainable solution for next-generation data requirements.
* Split-second (Nanosecond) are most valuable for online trading and the money market. Algorithmic and high-frequency traders are hosting their servers’ closure to the stock exchange server (Co-location model) for low latency communication to take advantage of PTP (Precision Time Protocol) within the stock exchange network. But every trader is deserved to get an almost equal low latency communication platform for the level playing field.
* **Regulatory or License Raj**: Proprietary hardware ASIC/FPGA boards had created only big corporate companies to offer telecom solutions. Get rid of this hardware-based business solution to software-based solution will bring more innovation and cost-cutting. 

## Benefits that can be achieved with split-second advantage in next-generation business

Optical fiber has reduced the network latency but the long-distance undersea network doesn't give the desired result. Laying ~500 million km of OFC every year (With a lifetime of 25 years) has increased the TCO. The number of hops is also a concern area to reach optimum latency results. The business will get immense benefit by reducing the network latency in long-distance communication.
 
5G has provided high bandwidth, reliable network availability, interoperability even in a densely populated location, RLC/MAC protocol, and support an all-Internet Protocol (IP) network. But it doesn’t help in a remote location with weak mobile network availability. 

Reliable and low latency network communication in conjunction with other technological progressions (IPv6, Cloud, etc..) will help us to achieve the following capabilities and many more. 
* Provides a thinner interactive user interface than the current system, even without local persistent storage. Interfacing system OS can be as small as Alpine container OS.
* Raspberry Pi (SoC-System on Chip) devices are sufficient enough to perform most of the user tasks.
* The wearable device can be used for a larger array of activities (like google home, healthcare service, Role of PA).
* The wearable devices and any user interface can use a cloudboot (Like SAN boot LUN) and offer a new array of low-cost cloud solutions.
* POS environment can be remotely connected with less to no maintenance work, dynamic price modeling, and avoid redundancy of resources in a distributed environment. In turn, it avoids unnecessary network failure data sync-up work. 
* A task that requires infra resources can be moved to the shared remote environment instead of a dedicated in-house infra resource.
* Connecting to a larger number of IoT devices (including BOT) and collecting a larger volume of data for data analytics. It helps to automize the continuous monitoring of machine, device, environment and send the data periodically for monitoring and action (Like maintenance, replenishment, implement dynamic regulation, etc..) using various types of sensors, even in a hostile work environment. A larger number of use cases can be solved in every industry and law enforcement and govt agencies. 
* LoRa chips, RLC/MAC protocol over 5G RAT will be useful for few IoT use cases (Long life battery, low data communication) to bring down IoT device cost around $2. This will create disruptive change in scheduled monitoring use cases.
* Increase in usage of AR, VR, XR, and gaming industries require high bandwidth and low latency. An increase in the virtual service industry (like healthcare, hospitality, personal banking), interactive classrooms, amusement park, museum, store, automobile/electronics self-service.
* Move towards SAS (Software as Service) and Serverless Arch provides the business solutions with less operation cost, highly scalable, reliable, and target any size customer. This is helpful for small-scale business users. For example, ZOHO kind of services will create a new buzz in the market.
* Reduce the number of CDN POP requirements or bring the CDN closure to the Virtual/Physical data center.
* Move the Retail, BFSI industry to a low-cost global location and remove the regional technology operation centers to the central location. Improve the decision-making process from the real-time data stream.
* move the data center (DC) to convenient locations where DC resource availabilities are higher, cheaper, less possible natural disasters, and less-security risk. It can be moved to anywhere in the globe if we get 10ms latency and fewer hops.
* Increase in business operation outsourcing and business process outsourcing.
* Increase in real-time data-driven and data-based decision making (Data Analytics, Machine learning, AI, etc..) from a larger number of global sources.
* 5G is helping us to move from hardware ASIC/FPGA boards that were proprietary to software-based functionality. It has enabled smaller companies to create a software-based solution to meet the size of telecom operator work. The smaller player can bring in low-cost solutions in the multibillion-dollar industry.
* Reduce the need of location-based data replication and distributed environment in the name of performance and data availability. Most of these requirements can be replaced with on-demand replication if required.

All these can be addressed in combination with low earth orbit (LEO) satellite network (like StarLink, OneWeb) availability and 5G technology. StarLink is building a network of satellites (~30k) in a lower orbit and targeting 10ms latency (currently POC gives 30 ms) which is like network communication within the same subnet mask or VLAN. Low latency and higher bandwidth have become mandatory for real-time decision-making.

### Other larger picture

The difference between urban cities and rural cities is based on their infrastructure availability, similarly developed nations, and developing nations. Most of the white-collar employees need a reliable and low latency network for remote work than the other urban infrastructures (airport, metro, road, transportation, apartment, hotels, water/sewage, electricity, etc.). Virtual collaboration among team members has drastically increased using new-age collaboration tools during corona travel restrictions. It can change the need for urban infrastructure to an extent. Better Govt policies on virtualization and decentralization can reduce the accumulation of wealth in urban populations and eventually developed nations. Those who have knowledge and interest in any part of the world can equally participate in borderless global development, compared to the current environment.

## Conclusion

Though the new age languages have provided larger capabilities in business solution engineering, the infrastructure changes were enablers for new solution engineering. Without these infra changes, we wouldn’t have achieved the required NFRs. The new chapter of infrastructure changes (i.e. 5G, Low earth orbit satellite) is on our table for the next round of disruptive changes in solution engineering and changes in business opportunities.


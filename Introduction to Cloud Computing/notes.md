1. # Introduction to Cloud Computing

# week 1 overview

### After completing this course, you will be able to:

- Define cloud computing and explain its essential characteristics, evolution, and the business case for cloud adoption
- Explain how some of the emerging technologies, such as the Internet of Things, Artificial Intelligence, Blockchain, and Analytics, are being supported by the cloud
- Describe the key features, benefits, and use cases of different types of cloud service and deployment models
- Explain the concepts and components of cloud infrastructure such as virtual machines, bare metal servers, cloud networking, and container-based technologies
- Describe the features, benefits, and use cases for different types of cloud storage
- Explain how Content Delivery Networks work
- Describe the features, use cases, and benefits of emergent cloud trends such as Hybrid Multicloud, Microservices, and Serverless computing
- Explain the key concepts, development principles, use cases, and benefits of cloud native applications
- Describe how DevOps practices help tackle some of the complexities posed by the cloud
- Explain how organizations can modernize their applications
- Explain the key concepts and components of cloud security, including Identity and Access Management, and Cloud Encryption
- List the job roles and career opportunities available in cloud computing
- Create an account on IBM Cloud
- Create an object storage instance on IBM Cloud and add items to your storage

what is cloud computing is the delivery of on demand computer resources…

![Image.png](/assets/images/Image%20(26).png)

### In this lesson, you have learned:

- Cloud computing is the delivery of on-demand computing resources over the internet on a pay-as-you-go basis; resources are dynamically assigned and reassigned among multiple users and scale up and down in response to users’ needs.
- The origins of cloud computing can be traced back to the mainframes of the 1950s, with virtualization technologies and hypervisors serving as catalysts for the emergence of modern-day cloud computing.
- Organizations must consider their business needs, investment viability, and risk capacity in order to create a cloud adoption strategy that delivers desired benefits without causing business disruptions and security, compliance, or performance issues.
- Cloud adoption is growing faster than predicted. Driving this technological wave are cloud service providers with a host of services ranging from Infrastructure, Platform, and Software services. Some major Cloud providers of our times include AWS, Alibaba Cloud, Google, IBM, and Microsoft Azure.

### In this lesson, you have learned:

The adoption of cloud technologies is enabling enterprises, big and small, to be agile, innovative, and competitive, and to create differentiated customer experiences. The question organizations are asking is not whether they should move to the cloud, rather what strategy they should adopt to move to the cloud.

Some case studies that demonstrate the impact businesses have created by adopting cloud:

- American Airlines adopting cloud technologies to deliver customer value rapidly across its enterprise
- UBank leveraging cloud platform services to give more control to their developers thereby removing barriers to innovation
- Bitly leveraging the scalability offered by cloud infrastructure for low-latency delivery to its geographically disbursed enterprise customers
- ActivTrades leveraging the infrastructure, storage, network, and security offerings on the cloud to accelerate execution and delivery of new functions in their online trading systems to their customers

### In this lesson, you have learned:

Emerging technologies, powered by the cloud, are disrupting existing business models and creating unprecedented opportunities for businesses to grow, innovate, and create value for their customers.

Some case studies that demonstrate how the use of emerging technologies on the cloud is creating value for millions around the world:

- The use of the Internet of Things on the cloud to combat poaching of endangered rhinos in South Africa
- Artificial Intelligence on the cloud being leveraged to deliver unique digital experiences to millions of fans around the world by the United States Tennis Association
- Blockchain on the cloud helping farmers reduce waste by building traceability and transparency in the food supply chain
- The use of data analytics for driving predictive maintenance solutions for a city’s infrastructure by KONE

# week 2 service models and deployment models

week 2 service and deployment models

![Image.png](/assets/images/Image%20(27).png)

saas is uber

paas is rental

iaas is buying a car

---

infrastructure as a services (compute networking and storage)

platform as a service pods, docker

software as a service youtube, managed databases

IaaS

## Infrastructuer as a Service

cloud computing

   (compute networking and storage)

   pay as you go

   hypervisor layer

   can provision vms with OS etc

managed large data centers

compute (hypervisors) autoscaling and load balancing

network

storage object, file and block

By abstracting the low-level components, cloud infrastructure is helping developers focus

more on business logic than infrastructure management.

Business continuity and disaster recovery require a significant amount of technology

and staff investments.

IaaS is helping organizations reduce this cost and make applications and data accessible

as usual during a disaster or outage.

Organizations are using cloud infrastructure to deploy their web applications faster and

also scale infrastructure up and down as demand fluctuates.

---

5 iaas use cases

test and development

continuity and disaster recovery

fast deployments and scale

hpc high performance computing

big data analysis

concerns - lack of transparency, vendor lock in this is a big one 3rd party

## Platform as a service

![Image.png](/assets/images/Image%20(28).png)

they install configure and operation

users write code

purchase resources on demand

chars of paas

high level of abstraction

support services and apis

hsa middleware

use cases

api development

IoT

business anylitics

business process management

master data management

### advantages

scalability, faster time to market, reduced written code, greater agility and innovation (more experimentation)

elastic beanstalk, cloud foundry, openshift, azure

### disadvantages

cybersecurity threats

dependant oninfrastructure of provider

## Software as a service

timebutler is the greatest example, office 365

salesforce

workday

![Image.png](/assets/images/Image%20(29).png)

reduce on premises IT infrastructure

needs good internet lol

### In this lesson, you have learned:

- Cloud computing allows us to utilize technology as a service, leveraging remote resources on-demand, on a pay-as-you-model. There are three main service models available on the cloud—Infrastructure-as-a-Service (IaaS), Platform-as-a-Service (PaaS), and Software-as-a-Service (SaaS).
- IaaS provides the fundamental compute, network, and storage resources for customers on-demand.
- PaaS provides customers the hardware, software, and infrastructure to develop, deploy, manage, and run applications created by them or acquired from a third-party.
- SaaS provides access to users to a service provider’s cloud-based software. Users simply access the applications on Cloud while the Cloud provider maintains the infrastructure, platform, data, application code, security, availability, and performance of the application.

## deployment models

![Image.png](/assets/images/Image%20(30).png)

public

![Image.png](/assets/images/Image%20(31).png)

![Image.png](/assets/images/Image%20(32).png)

private cloud

internal of external.. its a cloud but just 1 company has access (its pretty fuckign stupid)

but takes care of the security bullshit VPC

summery

- Deployment models indicate where the infrastructure resides, who owns and manages it, and how cloud resources and services are made available to users. There are three main deployment models available on the cloud—Public, Private, and Hybrid.
- In the Public cloud model, the service provider owns, manages, provisions, and maintains the physical infrastructure such as data centers, servers, networking equipment, and storage, with users accessing virtualized compute, networking and storage resources as services.
- In the Private cloud model, the provider provisions the cloud infrastructure for exclusive use by a single organization. The private cloud infrastructure can be internal to the organization and run or on-premises. Or, it can be on a public cloud, as in case of Virtual Private Clouds (VPC) and be owned, managed, and operated by the cloud provider.
- In the Hybrid cloud model, an organization’s on-premise private cloud and third-party, public cloud is connected as a single, flexible infrastructure leveraging the features and benefits of both Public and Private clouds.

# week 3 architecture

regions - clusters of data centers

A cloud region, is a geographic area or location where a cloud provider’s infrastructure is clustered, and may have names like NA South or US East. The cloud regions are isolated from each other so that if one region was impacted by a natural disaster like an earthquake, the cloud operations in other regions would keep running.

availibility zones (AZ)

![Image.png](/assets/images/Image%20(33).png)

data centers

![Image.png](/assets/images/Image%20(34).png)

**compute** - VMs, bare metal servers, serverless

**storage** - data persistence - block storage and file storage are common, but struggle, object is the best for the cloud

**networking -** software defined networking, public vs private interfaces

   ip adresses and subnets, security groups and access control lists. VLAN,

![Image.png](/assets/images/Image%20(35).png)

## Virtualization and Virtual Machines Explained

hypervisor is software that runs just above the bare metal

type 1 is baremetal (most oft used)

type 2 layer of host OS (hosted hv, virtualbox)

VMs run on top of the HV

multiple VMs on a HV

vms are portable

**benefits**: cost savings, reduce infrastructure footprints

agility and speed - virtuilization is fast and agile

lowers dowtime - moving vms from downded servers

## Types of Virtual Machines

vituals servers, virtual instances, instances

region and zone and OS are user decided

different type

spot vms are for unused capacities

reserved is the opposite

dedicated host is the server for just your machine. meeting compliance and regulatory shit

## Bare Metal Servers

omg they changed the song this video is terrible

- A bare metal server is a single-tenant, dedicated physical server.
- In other words, it's dedicated to a single customer.
- Because bare metal servers are physical machines, they take longer to provision than virtual servers.
- As Bare Metal servers are dedicated for use by a single client at any given time, they tend to be more expensive than similarly sized Virtual Machines.
- Also note that unlike virtual servers, not all cloud providers provide Bare Metal servers.
- If you use any applications that require high degrees of security control or apps that you've typically run in an on-premises environment, then a bare metal server is a good alternative in the cloud.
- When comparing bare metal servers to virtual servers, some of the most important considerations are found in customer need.
- Whereas, virtual servers are rapidly provisioned, provide an elastic and scalable environment, and are low cost to use, however since they share underlying hardware with other virtual servers, they can be limited in throughput and performance.

## Secure Networking in Cloud

As cloud environments gain greater adoption, and digital data invites rapidly increasing cybersecurity threats, building secure networks on the cloud is crucial.

Let's look at how we can build a secure cloud networking presence.

The main difference stems from the fact, that in the cloud, we use logical instances of networking elements as opposed to physical devices.

Subnets are also the main area where security is implemented in the cloud.

Once you build a subnet, then it is time to add some VSIs and storage to it so that you could run your applications.

While public gateways are great for Internet access to the cloud, enterprises are interested in extending their on-premises resources to the cloud by securely connecting them using Virtual Private Networks, or VPNs.

Enterprises with hybrid cloud environment find using dedicated high-speed connections between clouds and on-premises resources is a more secured and more efficient way than public connectivity solutions.

## containers

manifest (yml)

imagine

container

![Image.png](/assets/images/Image%20(36).png)

### In this lesson, you have learned:

Cloud infrastructure consists of data centers, storage, networking components, and compute resources.

Virtualization is the process of creating a software-based version of physical resources, made possible through the use of hypervisors.

A few different types of Virtual Machines can be provisioned on the cloud. These include:

- Shared or Public Cloud VMs that are provider-managed, multi-tenant deployments that can be provisioned on-demand with predefined sizes
- Transient or Spot VMs that take advantage of unused capacity in a cloud data center
- Reserved VMs that allow you to reserve capacity and guarantee resources for future deployments
- Dedicated hosts that offer single-tenant isolation

Bare metal servers are single-tenant physical servers that are dedicated to a single customer. Bare metal servers fulfill the demanding needs of high-performance computing (HPC) and data intense applications and are ideal for applications that have a high degree of security or compliance requirements.

Networking capabilities in the cloud are delivered as a service rather than in the form of rack-mounted devices. Cloud resources, such as VMs (or VSIs), storage, network connectivity, and load balancers, are deployed into subnets within Virtual Private Clouds (VPCs). Using private and public subnets allows users to deploy multi-tier enterprise applications securely. Load balancers distribute the traffic and allow applications to be responsive.

Containers are an executable unit of software in which application code is packaged, along with its libraries and dependencies, in common ways so that it can be run anywhere—desktops, traditional IT, or the cloud. Containers are lighter weight and consume fewer resources than Virtual Machines - helping streamline the development and deployment of cloud native applications.

# **storage and cdn**

## Basics of Storage on Cloud

[index (1).mp4](/assets/images/index%20(1).mp4)

Cloud storage is where you save data and files in the cloud.

Cloud providers host, secure, manage, and maintain the cloud storage and associated infrastructure to ensure you have access to your data when you need it.

Cloud storage is available in four main types – Direct Attached, File Storage, Block Storage and Object Storage.

File-based storage is a simple, straightforward approach to data storage and works well for organizing data in a hierarchical folder structure, that desktop users are familiar with.

Block storage is presented to compute nodes using high-speed fibre connections, which means that read and write speeds are typically much faster and reliable than with file storage, making block storage suitable for use with databases and other applications where disk speed is important.

You typically provision block storage in 'volumes', which can then be mounted onto a compute node, which it then effectively sees as another hard drive.

Volumes can normally only be mounted onto one compute node at a time.

With both File and Block storage, you may also hear the term 'IOPS'.

IOPS stands for 'Input/Output Operations Per Second' and relates to the speed of the storage or to put it another way, how quickly data can be read from or written to the storage.

Persistence is a term that is used when provisioning File or Block storage and relates to what happens to the storage once the compute node it is attached to is terminated.

If the storage is set to 'persist' then it will not be deleted along with the compute node, meaning that it and its data are preserved and available to mount onto another compute node, though you will continue to pay for the storage.

## CDN

reduces time for requests by cahing everything locally

# Lesson Summary

### In this lesson, you have learned:

- Cloud storage is available in four main types–Direct Attached, File, Block, and Object Storage. These storage types differ in how they can be accessed, the capacity they offer, how much they cost, the types of data they are best suited to store, and their read-write speed.
- Direct Attached (or Local) Storage is storage that is presented directly to a cloud-based server and is effectively either within the host server chassis or within the same rack.
- File Storage is typically presented to compute nodes as a Network File System (NFS), which means that the storage is connected to compute nodes over a standard ethernet network.
- Block Storage is presented to compute nodes using high-speed fiber connections, typically provisioned in volumes, which are mounted onto a compute node.
- Object Storage is accessed via an API and doesn’t need an underlying compute node. Object Storage offers infinite capacity as you can keep adding files to it and just pay for what you use. Compared to the other storage types, object storage is slowest in terms of read and write speeds.
- A Content Delivery Network (CDN) is a distributed server network that accelerates internet content delivery by delivering temporarily stored or cached copies of website or media content to users based on their geographic location.

# week 4 emergent trends and practices

   This week you will learn about some of the emergent trends in cloud computing, such as Hybrid Multicloud, Serverless Computing, and Microservices. You will also learn about how cloud native applications work, the role of DevOps in addressing some of the complexities of cloud computing, and the components of application modernization.

# Hybrid Multi-cloud

is a computing environment that connects and organizations on-premise private cloud and third-party public cloud into a single infrastructure for running the organization's applications. Multicloud is a cloud adoption strategy that embraces a mix of cloud models from different service providers - public, private, and managed, across infrastructure, platform, or software services.

using different cloud

composite cloud

# Microservices

loosely coupled independantly deployble services, own tacks and own containers

communications - apis event streaming and message brokers

Microservices architecture is an approach in which a single application is composed of many loosely coupled and independently deployable, smaller components or services. These services typically have their own stack running on their own containers. They communicate with one another over a combination of event streaming, and message brokers. In this video, we'll look at how microservices have shaped application development, and also look at a use case that illustrates microservices in action. Dream Game is using microservices to improve the user experience for viewers like Ron. When he logs in, he sees the most popular content among all Dream Game users. These three microservices are all in their separate containers ready to join the application. When microservices find each other, they communicate using an application programming interface or an API.

# serverless

The serverless model requires no provisioning of servers, installation of application stacks and software, or operation of the infrastructure by the developer. Serverless computing runs code only on-demand on a per-request basis, scaling transparently with the number of requests being served. Serverless enables end users to pay only for resources being used, never paying for idle capacity, which is unlike virtual servers on the cloud—where end users pay for VMs as long as they are running even if idle. Effectively, serverless abstracts the infrastructure away from developers. Code is executed as individual functions where each function runs inside a stateless container.

Applications that qualify for a serverless architecture include some of the following characteristics: Short-running stateless functions (seconds or minutes). Seasonal workloads with varying off-peak and peaks. Production volumetric data that shows too much idle time. Event-based processing or asynchronous request processing for implementing use cases.

![Image.png](/assets/images/Image%20(37).png)

# Lesson Summary

### In this lesson, you have learned:

- Hybrid Multicloud is a cloud adoption strategy that makes it possible for public clouds, private clouds, and on-premises IT to interoperate seamlessly while leveraging the best cloud-based services from different public cloud providers.
- Microservices architecture is an approach in which an application is built as a collection of loosely coupled and independently deployable components or services, leading to efficient development, maintenance, and upgradation cycles.
- Serverless Computing is an approach to computing that offloads responsibility for common infrastructure management tasks for application runtimes to cloud providers, allowing developers to focus their time and effort on development and testing, and not have to worry about provisioning, maintaining and scaling compute resources.

# Cloud Native Applications

a cloud native application is an application developed from the outset to

work only in the cloud environment, or an existing app that has been refactored and

reconfigured with cloud native principles.

A cloud native application consists of microservices working together as a whole to comprise an

application, yet each can be independently scaled and iterated through automation and

orchestration processes.

![Image.png](/assets/images/Image%20(38).png)

layers

![Image.png](/assets/images/Image%20(39).png)

standardized logging

standardized evemt management

# DevOps on the Cloud

![Image.png](/assets/images/Image%20(40).png)

Continuous Delivery, which is about delivering

small, well-designed, high-quality, increments of software to customers.

Continuous Integration; creating packaged builds of the code changes released as immutable

images; where immutable implies that when modifications are needed, the entire component

is replaced with an upgraded version.

Continuous Deployment, which involves progressing each new packaged build through the deployment

lifecycle as rapidly as possible.

Continuous Monitoring; with tools that help developers understand the performance and

availability of their applications, even before they are deployed to production.

Delivery Pipeline; which is an automated sequence of steps that involves the stages of

Ideation, Coding, Building, Deploying, Managing, and Continuous Improvement; which loops back

to the Ideation phase in the delivery pipeline.

# Application Modernization

- Many organizations have huge investments in existing applications that are often siloed in legacy systems and are very difficult and expensive to update and maintain.
- Modernizing these applications can unlock great benefits for these organizations such as accelerating their digital transformations, enabling them to take advantage of new technologies and services, and becoming more responsive to their customers' needs and changing market dynamics.
- Cloud computing is one of the three main ingredients in Application Modernization.

waterfalll sucks lol

![Image.png](/assets/images/Image%20(41).png)

service oriented architecture

# summery

- Cloud native applications are applications that are built or refactored to work in the cloud environment. These applications, developed using DevOps methodologies, consist of microservices packaged in containers that can run in any environment—making it possible to create and update features in quick iterative cycles.
- DevOps is a collaborative approach that enables development and operations teams to continuously deliver software in quick iterative cycles while reducing overhead, duplication, and rework. DevOps’ tools, practices, and processes help tackle the complexities and challenges posed by the cloud, allowing solutions to be delivered and updated —quickly and reliably.
- Application Modernization helps organizations accelerate their digital transformation, take advantage of new technologies and services, and become more responsive to changing market dynamics. Cloud computing is one of the key enablers of application modernization.

# week 5 Cloud Security, Monitoring, Case Studies, Jobs and **IBM CLOUD EXPERIENCE**

## Cloud Security and Monitoring

![Image.png](/assets/images/Image%20(42).png)

## identity

access group is a group of users and service IDs created so that the same access can be

assigned to all entities within the group with one or more access policies.

Access policies define how users, service IDs, and access groups in the account are

given permission to access account resources

## encryption

![Image.png](/assets/images/Image%20(43).png)

vloud based monetoring

![Image.png](/assets/images/Image%20(44).png)

# Lesson Summary

### In this lesson, you have learned:

- Cloud security refers to the policies, technological procedures, services, and solutions designed to secure the enterprise applications and data on cloud against insider threats, data breaches, compliance issues, and organized security threats.
- Cloud security is a shared responsibility between the cloud provider and the user organization.
- Security architecture and methods for achieving continuous security need to be embedded through the life cycle of an application to ensure that the application runs on a safe platform, the code is free from vulnerabilities, and the operational risks are understood.
- Identity and Access Management, also known as access control, helps authenticate and authorize users, and provide user-specific access to cloud resources, services, and applications.
- As part of their Identity and Access Management services, most cloud providers offer users the ability to define access groups and create access policies that define permissions for users on account resources.
- Cloud encryption, often referred to as the last line of defense, not only encrypts data, but also provides robust data access control, key management, and certificate management.
- Data needs encryption in three states -
- Encryption at rest; protecting data while it is stored
- Encryption in transit; protecting data while it is transmitted from one location to another
- Encryption in use; protecting data when it is in use in memory
- There needs to be active monitoring of all connected systems and cloud-based services to maintain visibility of all data exchanges between public, private, and hybrid cloud environments. This ensures that the cloud provides a trusted platform that can securely integrate with your enterprise data centers.

# case studies and jobs

### In this lesson, you have learned:

Businesses all over the world are realizing tangible benefits from the use of cloud technologies and services.

- The Weather Company migrating to the cloud to reliably deliver critical weather data at high speed, especially during major weather events such as hurricanes and tornadoes
- American Airlines using the cloud platform and technologies to deliver digital self-service tools and customer value more rapidly across its enterprise
- Cementos Pacasmayo achieving operational excellence and insight to help drive strategic transformation and reach new markets using cloud services
- Welch choosing cloud storage to drive business value from hybrid cloud
- LiquidPower using cloud-based SAP applications to fuel business growth

The market size of the cloud services industry is at nearly three times the growth of overall IT services, escalating the need for qualified cloud computing professionals. Some of the common job roles that are available in this domain include Cloud Software Engineers, Cloud Integration Specialists, Cloud Data Engineers, Cloud Security Engineers, Cloud DevOps Engineers, and Cloud Solution Architects
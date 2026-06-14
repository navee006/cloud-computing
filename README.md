1. What are App Services and what are the different types of options available in App Services?

Azure App Service is a fully managed Platform as a Service (PaaS) offering from Microsoft Azure that allows developers to build, deploy, and host web applications, mobile applications, REST APIs, and business applications without managing the underlying infrastructure.

Types of Azure App Services:
Web Apps – Used to host websites and web applications.
API Apps – Used to build and host RESTful APIs.
Mobile Apps – Provides backend services for mobile applications.
WebJobs – Runs background tasks and scheduled jobs.
Logic Apps – Automates workflows and integrates different services.
Function Apps (Azure Functions) – Executes event-driven serverless code.

2. Explain Cloud Availability Set and Availability Zones
Availability Set

An Availability Set is a logical grouping of virtual machines that helps protect applications from hardware failures, maintenance events, and unexpected downtime.

It works by distributing VMs across:

Fault Domains – Protect against hardware failures.
Update Domains – Protect against planned maintenance.
Availability Zones

Availability Zones are physically separate datacenters within an Azure region. Each zone has independent power, cooling, and networking.

Benefits:

High availability.
Fault tolerance.
Disaster recovery within the same region.
Difference
Availability Set	Availability Zone
Logical grouping within a datacenter	Physically separate datacenters
Protects against hardware and maintenance failures	Protects against datacenter failures
Lower cost	Higher resilience

3. What are the responsibilities of users when it comes to different cloud offerings like Infrastructure as Service, Platform as Service and Function as Service and mention which Azure resource falls under each option.
   Infrastructure as a Service (IaaS)

In IaaS, Azure manages the physical infrastructure while users manage the operating system, applications, middleware, runtime, and data.

User Responsibilities:

Install and maintain OS.
Configure software and applications.
Manage security updates.
Manage networking and storage.

Azure Resource Example:

Azure Virtual Machines (VMs)
Platform as a Service (PaaS)

In PaaS, Azure manages infrastructure, operating systems, and runtime environments. Users focus on application development and data.

User Responsibilities:

Develop and deploy applications.
Manage application data.
Configure application settings.

Azure Resource Example:

Azure App Service
Azure SQL Database
Function as a Service (FaaS)

In FaaS, Azure manages almost everything. Users only provide the function code.

User Responsibilities:

Write and maintain function code.
Configure triggers and bindings.

Azure Resource Example:

Azure Functions

4.In a brief paragraph, explain networking options available in Azure mentioning each service discussed in the class.
  Azure provides several networking services to enable secure communication between cloud resources and users.

Azure Virtual Network (VNet)

Provides a private network environment for Azure resources.

Network Security Groups (NSG)

Controls inbound and outbound network traffic using security rules.

Azure Load Balancer

Distributes incoming traffic across multiple servers to improve availability.

Azure Application Gateway

Provides Layer 7 load balancing and web application firewall capabilities.

Azure VPN Gateway

Creates secure connections between on-premises networks and Azure.

Azure ExpressRoute

Provides a dedicated private connection between on-premises infrastructure and Azure datacenters.

Azure DNS

Hosts and manages DNS domains.

These services help organizations build secure, scalable, and highly available cloud networks.

5. What are Storage Accounts and the Different Options Available to Access Storage Accounts?

A Storage Account is a container that stores Azure storage services such as blobs, files, queues, tables, and disks.

Types of Storage Services
Blob Storage

Stores unstructured data such as images, videos, and documents.

File Storage

Provides managed file shares accessible through SMB protocol.

Queue Storage

Stores messages for communication between applications.

Table Storage

Stores structured NoSQL data.

Disk Storage

Provides persistent storage for Azure Virtual Machines.

Access Methods
Azure Portal
Azure Storage Explorer
Azure CLI
Azure PowerShell
REST APIs
SDKs (.NET, Java, Python, etc.)
Shared Access Signatures (SAS)
Access Keys
Azure Active Directory Authentication

6. What are Different Options Available to Scale Up and Scale Out Azure App Services?
Scale Up (Vertical Scaling)

Scale Up increases the resources of a single App Service instance.

Examples:

More CPU.
More RAM.
Higher pricing tier.

Example:

Basic → Standard → Premium Plan.

Advantages:

Improved performance.
Easy to implement.
Scale Out (Horizontal Scaling)

Scale Out increases the number of App Service instances running the application.

Examples:

1 instance → 5 instances → 10 instances.

Azure Load Balancer automatically distributes traffic among instances.

Advantages:

Better availability.
Handles more users.
Supports automatic scaling based on CPU, memory, or schedules.
Comparison
Scale Up	Scale Out
Increase server resources	Increase number of servers
Vertical scaling	Horizontal scaling
Limited by server size	Can handle large traffic growth
Easier configuration	Better availability and reliability



Submitted By: Naveena
Course: Cloud Computing 

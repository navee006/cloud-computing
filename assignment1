# Azure Cloud Services Assignment

**Submitted By:** Naveena

**Course:** Cloud Computing 

---

# 1. What are App Services and what are the different types of options available in App Services?

Azure App Service is a fully managed Platform as a Service (PaaS) that enables developers to build, deploy, and host web applications, APIs, and mobile backends without managing the underlying infrastructure.

## Types of Azure App Services

### Web Apps

Used for hosting websites and web applications.

### API Apps

Used for creating and hosting REST APIs.

### Mobile Apps

Provides backend support for mobile applications.

### WebJobs

Runs background tasks and scheduled operations.

### Logic Apps

Automates workflows and integrates different services.

### Function Apps (Azure Functions)

Runs event-driven serverless code.

---

# 2. Explain Cloud Availability Set and Availability Zones

## Availability Set

An Availability Set is a logical grouping of Virtual Machines that improves application availability by distributing VMs across multiple fault domains and update domains.

### Benefits

* Protects against hardware failures.
* Protects against planned maintenance.
* Improves application uptime.

## Availability Zone

Availability Zones are physically separate datacenters within an Azure region. Each zone has independent power, cooling, and networking.

### Benefits

* High availability.
* Disaster recovery support.
* Protection against datacenter failures.

## Comparison

| Availability Set                   | Availability Zone                    |
| ---------------------------------- | ------------------------------------ |
| Logical separation                 | Physical separation                  |
| Protects against hardware failures | Protects against datacenter failures |
| Uses fault and update domains      | Uses independent datacenters         |

---

# 3. What are the responsibilities of users when it comes to different cloud offerings like Infrastructure as Service, Platform as Service and Function as Service and mention which Azure resource falls under each option.

## Infrastructure as a Service (IaaS)

Azure manages the physical infrastructure while the user manages the operating system, applications, middleware, and data.

### User Responsibilities

* Operating system maintenance
* Security updates
* Software installation
* Application management

### Azure Resource

* Azure Virtual Machines (VMs)

---

## Platform as a Service (PaaS)

Azure manages infrastructure, operating systems, middleware, and runtime environments.

### User Responsibilities

* Application development
* Application deployment
* Data management

### Azure Resources

* Azure App Service
* Azure SQL Database

---

## Function as a Service (FaaS)

Azure manages almost everything except the function code.

### User Responsibilities

* Writing code
* Configuring triggers and bindings

### Azure Resource

* Azure Functions

---

# 4.In a brief paragraph, explain networking options available in Azure mentioning each service discussed in the class.

Azure provides several networking services to ensure secure and reliable communication.

## Azure Virtual Network (VNet)

Creates a private network for Azure resources.

## Network Security Groups (NSG)

Controls inbound and outbound traffic through security rules.

## Azure Load Balancer

Distributes incoming traffic across multiple servers.

## Azure Application Gateway

Provides web traffic load balancing and web application firewall capabilities.

## Azure VPN Gateway

Creates secure connections between Azure and on-premises networks.

## Azure ExpressRoute

Provides dedicated private connectivity between Azure and on-premises environments.

## Azure DNS

Hosts and manages DNS domains in Azure.

These services help organizations build secure, scalable, and highly available network infrastructures.

---

# 5. What are Storage Accounts and the Different Options Available to Access Storage Accounts?

A Storage Account is an Azure resource that provides a unique namespace for storing data.

## Types of Storage Services

### Blob Storage

Stores unstructured data such as images, videos, and documents.

### File Storage

Provides managed file shares.

### Queue Storage

Stores messages for communication between applications.

### Table Storage

Stores structured NoSQL data.

### Disk Storage

Provides storage for Azure Virtual Machines.

## Access Methods

* Azure Portal
* Azure Storage Explorer
* Azure CLI
* Azure PowerShell
* REST APIs
* SDKs (.NET, Java, Python, etc.)
* Shared Access Signatures (SAS)
* Access Keys
* Azure Active Directory Authentication

---

# 6. What are Different Options Available to Scale Up and Scale Out Azure App Services?

## Scale Up (Vertical Scaling)

Scale Up increases the resources allocated to a single App Service instance.

### Examples

* More CPU
* More RAM
* Higher pricing tier

### Advantages

* Improved performance
* Simple implementation

---

## Scale Out (Horizontal Scaling)

Scale Out increases the number of App Service instances.

### Examples

* 1 instance to 5 instances
* 5 instances to 10 instances

Azure automatically distributes traffic among instances using load balancing.

### Advantages

* Better availability
* Handles increased traffic
* Supports automatic scaling

---

## Comparison

| Scale Up                   | Scale Out                   |
| -------------------------- | --------------------------- |
| Increases server resources | Increases number of servers |
| Vertical scaling           | Horizontal scaling          |
| Limited by hardware size   | Handles larger workloads    |
| Easier configuration       | Better fault tolerance      |

---

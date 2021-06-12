# AZ-900-fundamentals-notes
> Microsoft Azure Fundamentals Certification

[TOC]



## Change Log / Progress Track

### 2021-06-13

https://marczak.io/az-900/episode-09/practice-test/

| Topics | Done? ✅ |
| ------ | ------- |
| 1-11   | ✅       |
|        |         |
|        |         |

10 questions on exam topics a day

| Questions | Done? ✅ |
| --------- | ------- |
| 1-10      |         |
|           |         |
|           |         |
|           |         |



| Mon  | Tue  | Wed  | Thu  | Fri  | Sat  | Sun  |
| :--- | ---- | ---- | ---- | ---- | ---- | ---- |
|      |      |      |      |      |      | 13   |
|      |      |      |      |      |      | 20   |
|      |      |      | 24   |      |      |      |
|      |      |      |      |      |      |      |
|      |      |      |      |      |      |      |
|      |      |      |      |      |      |      |



# Describe Cloud Concepts (20-25%) 

## Identify the benefits and considerations of using cloud services 

- identify the benefits of cloud computing, such as High Availability, Scalability, Elasticity, Agility, and Disaster Recovery 

fault tolerance 

-  ability of a system to continue to function in the event of a failure of some of its components



- identify the differences between Capital Expenditure (CapEx) and Operational Expenditure (OpEx) 
- describe the consumption-based model 

## Describe the differences between categories of cloud services 

- describe the shared responsibility model



![laas, paas, saas responsibility and control](https://stackify.com/wp-content/uploads/2017/09/word-image-7-1024x550.png)

- describe Infrastructure-as-a-Service (IaaS), 
  - Compute
    - VMs / Servers
    - Azure virtual machines
  - Storage
  - Networking
  - ... any kinds of servers



- describe Platform-as-a-Service (PaaS) 



### PaaS

- **doesn't provide full control** of OS that hosts applications
  - only IaaS provides this
- can scale platform automatically ✅ 
- has **pre-coded** application components built into the platform :white_check_mark:
- 



Types of service in Azure that are PaaS 

- App service
  - Web App
  - Mobile App
  - Logic App
- Functions
- Web Jobs
- Azure SQL databases



- describe serverless computing 

  

- describe Software-as-a-Service (SaaS) 

you are responsible for Configuring the SaaS solution ✅



- identify a service type based on a use case

- identify a service type based on a use case 

## Describe the differences between types of cloud computing 

- define cloud computing 
- describe Public cloud 

mean no data center ✅

metered pricing ✅

self service management ✅

no dedicated hardware ✅

connections to public cloud are secure ✅ 

storage is not limited ✅ 



- describe Hybrid cloud 



- compare and contrast the three types of cloud computing 

# Describe Core Azure Services (15-20%) 

## Describe the core Azure architectural components 

- describe the benefits and usage of Regions and Region Pairs 
- describe the benefits and usage of **Availability Zones** 
  - Data Centers
- describe the benefits and usage of Resource Groups 
  - Resource Groups can represent logic grouping of *services*
    - by their life cycle
    - for billing and tracking purposes
    - by their resource type
    - by assigned departments
    - geographical location
  - It is not recommended for resource groups to be nested
    - In fact, "there is no structure for a “nested” resource group in Azure
    - https://blog.turbonomic.com/microsoft-azure-resource-groups-introduction-best-practices
    - It is recommended to use Resource Groups, Subscriptions, and Management Groups
  - A resource group can contain resources from different regions

- describe the benefits and usage of Subscriptions 
- describe the benefits and usage of Management Groups 

![Organize your resources with management groups - Azure Governance - Azure  governance | Microsoft Docs](https://docs.microsoft.com/en-us/azure/governance/management-groups/media/tree.png)

![Azure Resource Manager overview - Azure Resource Manager | Microsoft Docs](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/media/overview/scope-levels.png)



- describe the benefits and usage of Azure Resource Manager 
  - ARM is a Central Management Layer for managing all Azure resources
  - It uses JSON

![Resource Manager request model](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/media/overview/consistent-management-layer.png)



- explain Azure resources 

## Describe core resources available in Azure 

 describe the benefits and usage of Virtual Machines, Azure App Services, Azure Container Instances (ACI), Azure Kubernetes Service (AKS), and Windows Virtual Desktop 

- AKS customizable and container orchestration platform

 describe the benefits and usage of Virtual Networks, VPN Gateway, Virtual Network peering, and ExpressRoute 

- VPN Gateway
  - connect on-premise networks to Azure Virtual network via public internet

 describe the benefits and usage of Container (Blob) Storage, Disk Storage, File Storage, and storage tiers 

<u>Blob storage</u> 

- General purpose file structure in Azure

Types of storage:

- Blob
- Disk
  - Can mount drives on their PM
- File
- Queue
  - storing large number of messages
- Table



 describe the benefits and usage of Cosmos DB, Azure SQL Database, Azure Database for MySQL, Azure Database for PostgreSQL, and SQL Managed Instance 

 describe the benefits and usage of Azure Marketplace 

# Describe core solutions and management tools on Azure (10-15%) 

## Describe core solutions available in Azure 

describe the benefits and usage of Internet of Things (IoT) Hub, IoT Central, and Azure Sphere 

 describe the benefits and usage of Azure Synapse Analytics, HDInsight, and Azure Databricks 

 describe the benefits and usage of Azure Machine Learning, Cognitive Services and Azure Bot Service 

 describe the benefits and usage of serverless computing solutions that include Azure Functions and Logic Apps 

 describe the benefits and usage of Azure DevOps, GitHub, GitHub Actions, and Azure DevTest Labs 

## Describe Azure management tools 

 describe the functionality and usage of the Azure Portal, Azure PowerShell, Azure CLI, Cloud Shell, and Azure Mobile App 

 describe the functionality and usage of Azure Advisor 

 describe the functionality and usage of Azure Resource Manager (ARM) templates 

 describe the functionality and usage of Azure Monitor

![Overview of Azure Monitor, Security Center & Sentinel](https://www.systemcenterautomation.com/wp-content/uploads/2020/03/2020-03-18_18-14-13-1024x650.png)

**Service health** can see health of Azure services



Azure Monitor

- can see multiple subscriptions 
- Application Insights
  - ![Application Insights instrumentation in your app sends telemetry to your Application Insights resource.](https://docs.microsoft.com/en-us/azure/azure-monitor/app/media/app-insights-overview/diagram.png)
  - 
- ...



 describe the functionality and usage of Azure Service Health 

# Describe general security and network security features (10-15%) 

## Describe Azure security features 

 describe basic features of Azure Security Center, including policy compliance, security alerts, secure score, and resource hygiene 

 describe the functionality and usage of Key Vault 

 describe the functionality and usage of Azure Sentinel 

 describe the functionality and usage of Azure Dedicated Hosts Describe Azure network security 

 describe the concept of defense in depth 

 describe the functionality and usage of Network Security Groups (NSG) 

 describe the functionality and usage of Azure Firewall 

 describe the functionality and usage of Azure DDoS protection 

# Describe identity, governance, privacy, and compliance features (20- 25%) 

## Describe core Azure identity services 

 explain the difference between authentication and authorization 



 define Azure Active Directory 

![Classic subscription administrator roles, Azure roles, and Azure AD roles |  Microsoft Docs](https://docs.microsoft.com/en-us/azure/role-based-access-control/media/rbac-and-directory-admin-roles/rbac-admin-roles.png)

- each subscription can contain **multiple** account administrators 
- one resource group is tied to **one and only one** subscription
- each subscription can be managed by **multiple** Microsoft account only



 describe the functionality and usage of Azure Active Directory 

 describe the functionality and usage of Conditional Access, Multi-Factor Authentication (MFA), and Single Sign-On (SSO) Describe Azure governance features 

 describe the functionality and usage of Role-Based Access Control (RBAC) 



 describe the functionality and usage of resource locks 

**a resource** can have **multiple** locks of the same type (READ-only, DELETE)

you are able to create **READ + DELETE** locks on the same resource

**inherit locks** from parent resource groups



 describe the functionality and usage of tags 

 describe the functionality and usage of Azure Policy 

 describe the functionality and usage of Azure Blueprints 

 describe the Cloud Adoption Framework for Azure Describe privacy and compliance resources 

 describe the Microsoft core tenets of Security, Privacy, and Compliance 

 describe the purpose of the Microsoft Privacy Statement, Product Terms site, and Data Protection Addendum (DPA) 

 describe the purpose of the Trust Center 

Compliance

 describe the purpose of the Azure compliance documentation 

 describe the purpose of Azure Sovereign Regions (Azure Government cloud services and Azure China cloud services) 

# Describe Azure cost management and Service Level Agreements (10- 15%) 

## Describe methods for planning and managing costs 

 identify factors that can affect costs (resource types, services, locations, ingress and egress traffic)  identify factors that can reduce costs (reserved instances, reserved capacity, hybrid use benefit, spot pricing)  describe the functionality and usage of the Pricing calculator and the Total Cost of Ownership (TCO) calculator  describe the functionality and usage of Azure Cost Management Describe Azure Service Level Agreements (SLAs) and service lifecycles 

 describe the purpose of an Azure Service Level Agreement (SLA) 

 identify actions that can impact an SLA (i.e. Availability Zones) 

 describe the service lifecycle in Azure (Public Preview and General Availability)



---



![The trophy for the Describe core Azure concepts learning path.](https://docs.microsoft.com/en-us/learn/achievements/az-900-describe-cloud-concepts.svg)

# [Part 1: Describe core Azure concepts](https://docs.microsoft.com/en-us/learn/paths/az-900-describe-cloud-concepts/)

![Diagram showing overall view of popular Azure services with sections for security and management, platform services, hybrid cloud, and infrastructure services.](https://docs.microsoft.com/en-us/learn/azure-fundamentals/intro-to-azure-fundamentals/media/azure-services-6c41a736.png)

## Cloud Models

![The trophy for the Describe core Azure services learning path.](https://docs.microsoft.com/en-us/learn/achievements/az-900-describe-core-azure-services.svg)

CapEx - capital expenditure

OpEx - operation expenditure



## Networking Services

Distribution:

- non-HTTP web traffic > Azure Load balancer 

- HTTP traffic > Azure Application Gateway

CDN 

- Caching and global distribution of web application content to minimize latency of delivery to customers

Subnets

- cannot be nested

# [Part 2: Azure services](https://docs.microsoft.com/en-us/learn/paths/az-900-describe-core-azure-services/)

![The trophy for the Describe core solutions and management tools on Azure learning path.](https://docs.microsoft.com/en-us/learn/achievements/azure-fundamentals-describe-core-solutions-and-management-tools-on-azure.svg)

![Decision tree for Azure compute services](https://docs.microsoft.com/en-us/azure/architecture/guide/technology-choices/images/compute-choices.png)

# [Part 3: solutions and management tools on Azure](https://docs.microsoft.com/en-us/learn/paths/az-900-describe-core-solutions-management-tools-azure/)

![The trophy for the Describe general security and network security features learning path.](https://docs.microsoft.com/en-us/learn/achievements/examine-microsoft-azure-security-privacy-compliance-trust.svg)

# [Part 4: security and network security features](https://docs.microsoft.com/en-us/learn/paths/az-900-describe-general-security-network-security-features/)

![The trophy for the Describe identity, governance, privacy, and compliance features learning path.](https://docs.microsoft.com/en-us/learn/achievements/az-900-describe-identity-governance-privacy-compliance-features.svg)

# [Part 5: identity, governance, privacy, and compliance features](https://docs.microsoft.com/en-us/learn/paths/az-900-describe-identity-governance-privacy-compliance-features/)

![The trophy for the Describe Azure cost management and service level agreements learning path.](https://docs.microsoft.com/en-us/learn/achievements/review-microsoft-azure-pricing-slas-lifecycles.svg)



# [Part 6: Azure cost management and service level agreements](https://docs.microsoft.com/en-us/learn/paths/az-900-describe-azure-cost-management-service-level-agreements/)


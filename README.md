# Cloud Models

Cloud models define the deployment type of cloud resources. There are three main cloud models:

## 1. Private Cloud:

- Used by a single entity, offering greater control.
- Evolution from a corporate datacenter.
- Hosted on-site or in a dedicated offsite datacenter.
- Greater cost, fewer benefits of a public cloud.

## 2. Public Cloud:

- Built, controlled, and maintained by a third-party provider.
- Accessible to anyone purchasing cloud services.
- General public availability distinguishes it from private clouds.

## 3. Hybrid Cloud:

- Utilizes both public and private clouds in an interconnected environment.
- Enables private cloud surge for increased, temporary demand using public cloud resources.
- Provides flexibility and an extra layer of security.
- Users choose which services to keep in the public cloud and which to deploy privately.

## Comparative Aspects:

| Aspect                              | Public Cloud                               | Private Cloud                                      | Hybrid Cloud                                      |
|-------------------------------------|--------------------------------------------|----------------------------------------------------|----------------------------------------------------|
| Capital Expenditures                | None                                       | Required for startup and maintenance                 | Organizations determine where to run apps           |
| Provisioning/Deprovisioning         | Quick                                      | -                                                  | Organizations control app deployment                |
| Cost Structure                      | Pay for what is used                       | Hardware costs for startup and maintenance          | Control over security, compliance, and legal        |
| Control Over Resources and Security | Limited control                            | Full control                                        | Varies based on deployment                         |
| Data Collocation                    | Data may be collocated with other organizations' | Data is not collocated with other organizations' | -                                                  |
| Responsibility for Hardware Maintenance | Not applicable                         | Organizations are responsible                      | Organizations control maintenance and updates     |

## Additional Scenarios:

### Multi-Cloud Scenario:

- Involves using multiple public cloud providers.
- Manages resources and security in multiple environments.

### Azure Arc:

- Set of technologies to manage diverse cloud environments.
- Manages public, private, hybrid, or multi-cloud configurations.

### Azure VMware Solution:

- Allows running VMware workloads in Azure.
- Offers seamless integration and scalability for migration from private to public or hybrid cloud.

# Consumption-Based Model

## Overview:

- In cloud computing, expenses are categorized into Capital Expenditure (CapEx) and Operational Expenditure (OpEx).
- CapEx involves one-time upfront expenditures for tangible resources.
- OpEx involves spending over time for services or products.

## Cloud Computing and OpEx:

- Cloud computing operates on a consumption-based model, falling under OpEx.
- Unlike traditional models, where you pay for physical infrastructure and associated costs, in the cloud, you pay for actual IT resources used.

## Benefits of the Consumption-Based Model:

- No upfront costs.
- No need to invest in and manage potentially underutilized infrastructure.
- Ability to scale resources up or down based on demand.
- Ability to stop paying for resources that are no longer needed.

## Challenges in Traditional Datacenters:

- Traditional datacenters require estimating future resource needs.
- Overestimating leads to unnecessary spending; underestimating may result in capacity issues and performance degradation.
- Fixing under-provisioned datacenters involves time-consuming processes like ordering, receiving, and installing additional hardware.

## Flexibility in Cloud-Based Model:

- Cloud-based model eliminates the need for precise resource predictions.
- Easily add or remove virtual machines based on actual demand.
- Pay only for the virtual machines in use, avoiding costs associated with excess capacity.

## Cloud Pricing Models:

- Cloud computing follows a pay-as-you-go pricing model.
- Pay only for the specific cloud services used.

## Advantages include:

- Planning and managing operating costs effectively.
- Running infrastructure more efficiently.
- Scaling resources as business needs change.

## Key Concept:

- Cloud computing is akin to renting compute power and storage from a provider's datacenter.
- Cloud resources are treated like those in an on-premises datacenter but returned when not in use.
- Billing is based on actual usage, ensuring cost-effectiveness and flexibility.

## Conclusion:

- Cloud computing, through its consumption-based model, offers businesses the flexibility to adapt to changing demands, efficiently manage costs, and access cutting-edge solutions without the burden of upfront infrastructure investment and maintenance.


# Infrastructure as a Service (IaaS):

- IaaS provides flexible cloud services with maximum user control.
- Cloud provider manages hardware, network, and physical security.
- Users handle OS installation, configuration, maintenance, and network settings.

## Shared Responsibility Model:

- Significant user responsibility.
- Cloud provider manages physical infrastructure, users manage installation, configuration, updates, and security.

## Scenarios:

- Lift-and-Shift Migration.
- Testing and Development.

## Key Characteristics:

- Users rent hardware in a cloud datacenter.
- Maximum control over infrastructure.
- Scalable and on-demand resource provisioning.

## Conclusion:

- IaaS offers flexible, customizable cloud services, ideal for lift-and-shift migrations or rapid replication of development environments.

# Platform as a Service (PaaS):

- Intermediate model between IaaS and SaaS.
- Cloud provider manages physical infrastructure, OS, middleware, development tools, and business intelligence.

## Shared Responsibility Model:

- Shared model splitting responsibilities.
- Users focus on application development; the provider manages infrastructure complexities.

## Scenarios:

- Development Framework.
- Analytics or Business Intelligence.

## Key Characteristics:

- Complete development environment without infrastructure management.
- Users concentrate on application development.
- Provider maintains and updates the operating environment.

## Conclusion:

- PaaS provides a balanced approach, beneficial for application development, customization, analytics, or business intelligence.

# Software as a Service (SaaS):

- Users rent or use fully developed applications.
- Examples include email, financial software, messaging applications.
- Offers a complete product perspective.

## Flexibility and Ease of Use:

- Least flexible but easiest to deploy.
- Users don't need extensive technical knowledge.

## Shared Responsibility Model:

- Most responsibility with the cloud provider.
- Users manage data input, devices, and user access.

## Scenarios:

- Email and Messaging.
- Business Productivity Applications.
- Finance and Expense Tracking.

## Ease of Deployment:

- Ready-to-use applications.
- No need for users to manage underlying infrastructure or application development.

## Conclusion:

- SaaS provides a ready-to-use solution, easiest to deploy, suitable for scenarios prioritizing rapid deployment and minimal technical expertise.


# Considerations for High Availability and Scalability in Cloud Applications:

## High Availability:

- High availability ensures maximum uptime and accessibility of resources, regardless of disruptions or events.
- Importance: Critical for continuous availability of applications, services, or IT resources.
- Architectural Planning: When deploying a cloud application, architect solutions with a focus on service availability guarantees.

### Azure SLAs:

- Azure provides a highly available cloud environment.
- Uptime guarantees are specified in Service Level Agreements (SLAs).
- SLAs vary based on the specific Azure service.

## Scalability:

- Scalability refers to the dynamic adjustment of resources to meet changing demand, optimizing performance and costs.

### Benefits:

- Meeting Demand: Enables handling peak traffic or sudden demand increases effectively.
- Cost Efficiency: Cloud's consumption-based model ensures you only pay for resources used.

### Types of Scaling:

- Vertical Scaling:
  - Adjust capabilities by increasing or decreasing resource specifications (e.g., CPUs or RAM).
  - Offers flexibility in resource allocation based on application requirements.

- Horizontal Scaling:
  - Scaling Out:
    - Adding more instances (virtual machines, containers) to distribute load.
    - Effective during periods of high demand.
  - Scaling In:
    - Reducing deployed resources during periods of low demand to optimize costs.

- Automatic or Manual Scaling:
  - Automatic scaling based on predefined conditions or manual scaling for fine-tuned control.

- Cost Optimization:
  - Cloud scalability ensures that you pay for resources in use, avoiding overpayment during low-demand periods.

## Conclusion:

When building or deploying cloud applications, prioritizing high availability and scalability is essential. High availability guarantees continuous access to resources, while scalability ensures dynamic resource adjustments to meet changing demand efficiently. Both aspects contribute to a resilient and cost-effective cloud environment, providing optimal performance and user experience.


# Azure Infrastructure Components:

## Regions and Availability Zones:

- **Region:** A geographical area that contains at least one datacenter. Azure controls the resources within each region.
- **Availability Zones:** Physically separated datacenters within an Azure region, providing redundancy. If one zone goes down, the other continues working.
- **Azure Services Supporting Availability Zones:** Zonal services, Zone-redundant services, Non-regional services.
- **Region Pairs:** Azure regions are paired with another region at least 300 miles away, reducing the likelihood of interruptions due to events like natural disasters.
- **Sovereign Regions:** Designed for compliance or legal purposes, such as US DoD Central, US Gov Virginia, China East, and more.

## Azure Resources and Resource Groups:

- **Resource:** The basic building block of Azure.
- **Resource Groups:** Provide a way to group resources together. Actions applied to a group affect all resources within it. Deleting a group deletes all associated resources.

## Azure Subscriptions:

- A unit of management, billing, and scale.
- **Billing Boundary:** Determines how an Azure account is billed.
- **Access Control Boundary:** Manages and controls access to resources provisioned under specific subscriptions.

## Azure Management Groups:

- Provide a level of scope above subscriptions.
- Organize subscriptions into containers and apply governance conditions.
- Create hierarchies for policy application and provide user access to multiple subscriptions.

## Azure Virtual Machines (VMs):

- Provide total control over the Operating System.
- Allow running custom software and using custom hosting configs.
- Assure VM flexibility of virtualization without maintaining physical hardware.
- Requires updating and maintaining the software running on the VM.

### Virtual Machine Scale Set:

- Create and manage a group of identical, load-balanced VMs.
- Instances can automatically increase or decrease in response to demand.
- Automatically deploys a load balancer for efficient resource usage.

## Azure Virtual Desktop:

- Desktop and app virtualization in the cloud.
- Create a full desktop virtualization environment without additional gateway servers.
- Enables multiple concurrent users on a single VM (multiple sessions).

## Containers:

- Virtualization environment for running multiple containers on a single host.
- Lightweight, designed for dynamic creation, scaling, and stopping.
- Popular container engine: Docker.

### Azure Container Services:

- Lightweight, virtualized environment without OS management.
- Azure Container Instances: PaaS offering for running containers without managing VMs.
- Azure Kubernetes Service: Orchestration service for containers with distributed architectures.

## Azure Functions:

- Event-driven, serverless compute option.
- Scales automatically based on demand.
- Can be stateless or stateful.

## Azure App Service:

- Fully managed platform for building, deploying, and scaling web apps and APIs quickly.
- Works with .NET, .NET Core, Node.js, Java, Python, or PHP.
- PaaS offering with enterprise-grade performance, security, and compliance.
- Supports Web apps, API apps, Webjobs, and Mobile apps.

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


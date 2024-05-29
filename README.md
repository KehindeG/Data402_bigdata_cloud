# Big Data Cloud

### What is Cloud Computing?
Cloud computing is a ***technology*** that allows individuals and businesses to use computing resources (like 
servers, storage, databases, networking, software, analytics, and intelligence) over the internet, or "the cloud." 
It enables access to these resources on a pay-as-you-go basis, providing scalability, flexibility, and cost-efficiency. 

<br>

### How do we know if something is in the cloud?
Finding out if something is in the cloud involves understanding the characteristics and behaviors of cloud-based 
services and resources. There are some indicators that a service or resource is cloud-based:
- ***Accessed via the Internet*** - If you can use the service from any internet-connected device without needing specific 
                              local installations or configurations, it's likely cloud-based.<br>

- ***Pay-As-You-Go Pricing Model*** - Cloud services often use a subscription or consumption-based pricing model, where you 
                                pay only for the resources or services you use.
- ***Scalability and Elasticity*** - If the service can handle varying levels of workload without manual intervention or 
                               hardware changes, it is likely cloud-based- as they can scale resources up or down 
                               automatically, based on demand.
- ***Accessible from Multiple Locations*** - If you can access the service from different regions without performance issues, 
                                       as they are typically accessible from multiple geographic locations, ensuring 
                                       high availability and redundancy.
- ***Multi-Tenant Environment*** - Meaning multiple users or organizations share the same resources and physical infrastructure 
                             securely.

<br>

### Differences between on-prem and the cloud?

|                                   | ***On-Prem (on premises)***                                                                                                                                                    | ***The Cloud***                                                                                                                                              |
|-----------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ***Deployment & Infrastructure*** | Hardware and software are installed and run locally<br/> within an organization's own data centers.                                                                            | Infrastructure is hosted and managed by the cloud provider, so no physical maintenance.                                                                      | 
| ***Scalability***                 | Limited by physical capacity- Scaling up requires purchasing and installing additional hardware, which can be time-consuming <br> and costly.                                  | Virtually unlimited scalability- Resources can be scaled up or down automatically,<br> based on demand.                                                      | 
| ***Cost Structure***              | High upfront capital expenditure (CapEx) for hardware, software, and infrastructure setup. Ongoing operational expenses (OpEx) for<br> maintenance, power, cooling, and staff. | Pay-as-you-go pricing model with minimal upfront costs. Operational expenses based on usage,<br> leading to potentially lower total cost of ownership (TCO). | 
| ***Management and Maintenance***  | Full control and responsibility for managing hardware, software, and security. Requires in-house IT staff for maintenance, upgrades, and troubleshooting.                      | The cloud provider handles hardware management, software updates, and security- Reducing the burden on in-house IT staff.                                    | 
| ***Flexibility and Mobility***    | Limited flexibility; accessing resources remotely may require complex VPN setups. Mobility is constrained by the physical location of the infrastructure.                      | Access resources from anywhere with an internet connection. Supports remote work and mobile access more easily.                                              |

<br>

### The 4 deployment models of cloud: private vs public vs hybrid vs multi-cloud - Differences? How do they work?

***Private Cloud***<br>
* How does it work?<br>
  * The organization sets up and manages its own cloud infrastructure, ensuring that all resources are dedicated solely to its use. <br>
* Key difference?
  * Exclusively used by one organization- high control over security, customized infrastructure.

***Public Cloud***<br>
* How does it work?<br>
  * Organizations rent cloud resources from providers, paying for what they use. Services are accessed over the internet, and the provider handles maintenance and infrastructure.<br>
* Key difference?
  * Shared infrastructure managed by third-party providers, highly scalable, lower costs.

***Hybrid***<br>
* How does it work?<br>
  * An organization uses a mix of private and public clouds, with orchestration between the two platforms. Data and applications can be moved between environments based on requirements.<br>
* Key difference?
  * Combines private and public clouds, offering flexibility and a balance between security and scalability.

***Multi-Cloud***<br>
* How does it work?<br>
  * An organization uses services from several cloud providers (e.g., AWS for storage, Azure for computing, Google Cloud for AI services). This approach requires effective management and integration tools to ensure interoperability and performance optimization.<br>
* Key difference?
  * Uses multiple public cloud services from different providers, avoids vendor lock-in, leverages best-of-breed services.

<br>

### Types of cloud services: IaaS, PaaS, SaaS - What are differences?
The three main types of cloud services—Infrastructure as a Service (IaaS), Platform as a Service (PaaS), 
and Software as a Service (SaaS)—each serve different purposes and provide different levels of control and 
responsibility. 

|                     | ***IaaS***                                                                                                                         | ***PaaS***                                                                                                                           | ***SaaS***                                                                                                          |
|---------------------|------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|
| Purpose             | Provides virtualized computing resources over the internet.                                                                        | Provides a platform allowing customers to develop, run, and manage applications without dealing with the underlying infrastructure.  | Delivers software applications over the internet, on a subscription basis.                                          | 
| Control Level       | High                                                                                                                               | Medium                                                                                                                               | Low                                                                                                                 |
| Components Provided | Virtual machines, storage, networks, and sometimes databases.                                                                      | Development tools, database management, middleware, and operating systems.                                                           | Entire software applications along with underlying infrastructure and platforms.                                    | 
| Common Use Cases    | Hosting websites and web applications.<br> Development and testing environments.<br> Data storage, backup, and recovery solutions. | Application development and deployment.<br> Business intelligence and analytics.<br> Integrating various web services and databases. | Customer relationship management (CRM) software.<br> Office productivity suites.<br> Email and collaboration tools. | 

<br>

### What are the advantages/disadvantages of the cloud? (Particularly for a business)

* Cost Efficiency:
  * Advantage: Reduces the need for significant upfront capital expenditures on hardware and software.<br>
               Operates on a pay-as-you-go model, allowing businesses to pay only for the resources they use.<br>
  * Disadvantage:
               Over time, subscription fees can add up, and without careful management, costs can escalate, especially with increased usage.<br>

* Maintenance and Management:
  * Advantage: Offloads the burden of managing and maintaining physical hardware to cloud service providers.<br>
               Providers handle software updates, security patches, and routine maintenance, freeing up internal IT resources.<Br>
  * Disadvantage:
               Loss of some control over the IT environment and dependence on the provider for maintenance and uptime.<br>

* Scalability and Flexibility:
  * Advantage: Easily scales up or down based on demand, accommodating business growth and fluctuating workloads.<br>
               Provides access to a wide range of resources and services that can be tailored to specific business needs.<Br>
  * Disadvantage:
               Rapid scaling may lead to unpredictable costs.<br>
               Not all applications or workloads are easily scalable or suitable for cloud environments.<br>

<br>

### Difference between OpEx vs CapEx and how it relates the cloud? (redo!)

|                         | OpEx (Operational Expenditure)                                                                                                                       | CapEx (Capital Expenditure)                                                                                                                                   |
|-------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Purpose                 | Long-term investments in physical assets like buildings, machinery, and IT infrastructure.                                                           | Ongoing expenses for day-to-day operations, such as rent, utilities, and subscription services.                                                               | 
| Characteristics         | Regular, predictable costs, fully deductible in the same year.                                                                                       | High upfront costs, depreciation over time, budgeted for long-term use.                                                                                       | 
| Cloud Relation          | Traditional on-premises IT infrastructure is usually a CapEx, requiring significant upfront investment in servers, data centers, and other hardware. | Cloud computing shifts IT spending to OpEx, as businesses pay for services on a subscription <br> or pay-as-you-go basis, avoiding large initial investments. | 

<br>

Cloud Computing Impact:
CapEx to OpEx Shift: Cloud services eliminate the need for large capital investments in IT infrastructure. Instead, businesses pay for cloud resources as operational expenses, leading to more predictable and manageable costs.
Financial Flexibility: The OpEx model allows businesses to scale expenses with usage, providing flexibility to adjust spending based on current needs and growth.
<br>

### Is migrating to the cloud always cheaper?
This depends on a detailed analysis of current and projected workloads, cost structures, and the specific needs of the business.<br>
For businesses with stable, high-volume workloads, the cumulative cost of cloud services may surpass the cost of maintaining a dedicated on-premises infrastructure.

<br>

### Market-share trends breakdown- 
![Market Share](https://www.google.com/imgres?q=market%20share%20cloud%20providers&imgurl=http%3A%2F%2Fcdn.statcdn.com%2FInfographic%2Fimages%2Fnormal%2F18819.jpeg&imgrefurl=https%3A%2F%2Fwww.statista.com%2Fchart%2F18819%2Fworldwide-market-share-of-leading-cloud-infrastructure-service-providers%2F&docid=w8gQLeHn9VXGVM&tbnid=WvlCIzZZiAWnhM&vet=12ahUKEwj43ezMlLOGAxUbV0EAHRDvBq0QM3oECBsQAA..i&w=1200&h=1200&hcb=2&ved=2ahUKEwj43ezMlLOGAxUbV0EAHRDvBq0QM3oECBsQAA)

<br>

### The 3 largest Cloud providers, and what makes them popular: <br>
**AWS (Amazon Web Services):** Leads due to its early market entry, extensive service offerings, and robust global infrastructure.
**Microsoft Azure:** Excels with strong integration with Microsoft products, enterprise solutions, and hybrid cloud capabilities.
**GCP (Google Cloud Platform) :** Stands out with its leadership in data analytics, AI, high-performance network infrastructure, and commitment to open source and multi-cloud strategies.


<br>

### What sorts of things do you usually need to pay for when using the cloud?
Compute Resources:<br>
- Virtual Machines (VMs)
- Containers
- Serverless Computing<br>

Storage:<br>
- Block Storage
- Object Storage
- File Storage
- Archival Storage<br>

Networking:<br>
- Data Transfer
- Content Delivery Network (CDN)
- Load Balancers
- Archival Storage<br>

Database Services:<br>
- Managed Databases
- NoSQL Databases
- Data Warehousing<br>

Application Services:<br>
- API Management
- App Development<br>

<br>

### How is data used/managed in the cloud? What do data professionals need to know to leverage cloud technologies effectively?

Data Storage:
- Object Storage
- Block Storage
- File Storage
- Database Storage

Data Management:
- Data Integration and ETL: Tools for data integration, transformation, and loading (ETL), such as AWS Glue, Azure Data Factory, and Google Cloud Dataflow.
- Data Warehousing: Services for large-scale data storage and query processing, like Amazon Redshift, Azure Synapse Analytics, and Google BigQuery.
- Data Lakes: Centralized repositories to store all structured and unstructured data at any scale, such as AWS Lake Formation, Azure Data Lake, and Google Cloud Storage.

Data Processing and Analytics:
- Big Data Processing: Managed services for big data processing, including AWS EMR, Azure HDInsight, and Google Dataproc.
- Analytics Services: Tools for analyzing and visualizing data, such as Amazon Athena, Azure Data Lake Analytics, and Google BigQuery.
- Machine Learning: Platforms and tools for building, training, and deploying machine learning models, like AWS SageMaker, Azure Machine Learning, and Google AI Platform.

Data Security and Governance:
- Encryption: Both at-rest and in-transit encryption services to protect data.
- Access Controls: Fine-grained access control mechanisms like AWS IAM, Azure RBAC, and Google Cloud IAM.
- Compliance: Services to ensure data governance and compliance with regulatory standards.

<br>

### Case Studies showing how businesses have migrated to the cloud or used the cloud to improve in some way:
Case study 1:
```
Minna Bank (Japan’s first digital bank):

Background: Minna Bank, Japan's first digital bank, recognized the evolving preferences of digital-native consumers who 
favored online interactions over traditional banking methods.

Solution: Minna Bank opted to build a cloud-based banking platform, leveraging cloud technology to meet the needs of its 
digitally inclined customer base. By migrating its infrastructure to the cloud, Minna Bank gained the flexibility and scalability necessary to adapt to changing market demands rapidly.

Results: By embracing cloud technology, Minna Bank achieved several key benefits:
    Rapid Deployment of New Services: With the agility afforded by the cloud, Minna Bank could swiftly deploy new banking 
        services and features to meet customer demands and stay ahead of the competition.
    Efficient Scalability: Cloud technology enabled Minna Bank to scale its infrastructure seamlessly in response to 
        fluctuations in user demand. This ensured a consistent and reliable banking experience for customers, even during peak usage periods.
    Enhanced Security and Compliance Management: Recognizing the importance of security and compliance in the financial 
        industry, Minna Bank leveraged cloud-based security solutions tailored to meet stringent regulatory requirements. 
        This ensured that customer data remained secure and compliant with industry standards, fostering trust and confidence among customers.


```
Case study 2:
```
Netflix:

Background: Netflix, a leading streaming service provider, faced challenges with scalability and infrastructure costs as 
its user base grew rapidly.

Solution: Netflix migrated its infrastructure to Amazon Web Services (AWS) cloud platform.

Results: This migration allowed Netflix to scale its services globally while reducing infrastructure costs. By utilizing 
AWS's services such as Amazon Elastic Compute Cloud (EC2) for computing power and Amazon Simple Storage Service (S3) for 
storage, Netflix improved its streaming quality and reliability. The company also leveraged AWS's analytics tools for content 
recommendations, enhancing the user experience and increasing customer retention.
```

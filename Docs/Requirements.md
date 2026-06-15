Enterprise Architecture Overview
1. Business and Client Landscape

The organization serves two primary client segments:

Corporate clients
Individual customers

The core business operations are primarily supported by mainframe systems.

Over time, macros have been developed to support activities that would otherwise require longer development cycles. These macros were introduced mainly to address urgent business requirements and delivery time constraints.

2. Case Management

Cases are currently created and managed in two platforms:

SAG
Case Management System (CMS)

The CMS was developed on top of Camunda to facilitate case-related activities. As a result, case information and activities currently exist in both SAG and CMS.

3. Customer Information

Customer information is maintained in DLIPS.

DLIPS includes two underlying data sources:

FKS
KKS

FKS contains a subset of the available customer data.

KKS contains the complete set of customer data; however, it does not provide real-time data.

4. Data Warehouse Landscape

The organization currently uses three solutions within its data warehouse landscape:

FDW
SaaS
Databricks

FDW is one of the existing data warehouse solutions.

5. Hosting and Cloud Strategy

The current hosting priority is:

On-premises infrastructure as the primary hosting environment
AWS as the secondary hosting environment
Azure as the tertiary hosting environment

The organization is moving workloads from the on-premises environment to AWS.

Azure is also used as a secondary backup environment.

6. Integration and Messaging

Kafka is used for message passing between systems.

RPA is used for screen scraping and retrieving data from existing applications.

7. Process Orchestration

Camunda is used as the orchestration platform.

Business processes are designed and developed using BPMN in Camunda.

The Case Management System was developed on top of Camunda to support and coordinate case-related activities.

8. Logging

Application and system logs are handled through LaaS.
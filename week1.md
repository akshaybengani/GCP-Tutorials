# GCP (Google Cloud Platform)

GCP offers 4 main type of services.
* Compute
* Storage   
* Big data
* Machine Learning

## Cloud computing
It is a way of using IT to use the 5 different services.
* On-demand Self service
* Broad network access
* Resource pooling
* Rapid elasticity
* Measured service

## History and need to introduce cloud
* Initially we use seperate resources at our home and office adding such infrastructure cost more and seperately expensive.
* Then  we came to virtualized where we buy needed resources instances according to our usage since if the resource pool gets overloaded then we need to add resources seperately to continue fuctioning.
* Now Google cloud does everyday automated it is now container based architecture.
* Buy your own hardware for your requirements, physical configuration totally user configured managed and maintained.
* Virtualized User Configured provider managed and maintained
* Serverless Fully automated, its container based architecture.
* Every company is a data company and calculating on the huge data requires hige computation power and cloud computing is a solution for that.
* Cloud computing provides you to scale your resources up and down.
### Key Products
* Compute Engine IAAS
* Kubernates Engine Hybrid
* App Engine PAAS
* Cloud Functions Serverless Logics
* Managed Servers Automated Elastic Resources.
* SAAS Search Gmail Youtube Comes in SAAS.

<img src="img\GCP_Compute_Architecture.jpg">

## GCP Zones
* When we build an application of GCP we select a zone on which the application will run, the GCP uses the nearest possible zone to reduce the latency of the instances.
* Zones are of 4 types
    *   Country
    * Multi-Region
    * Region
    * Specific Area | Locality | State
*   To create a fault tolenrence application we can use different zones.
* Googles all data centers use totally 100% green energy.

<img src="img/GCP_Network.jpg">

## GCP Pricing
* Billing in subhour increments
    *   For Virtual Machines containers in the cloud data processing and other services too.
* Discounted for Sustained Use
    * Automatically applied to virtual machines use over 25% of month.
* Custom VM instance Types
    *   Pay only for the resources you need for your application.

## Open API
* Cloud Bigtable uses the interface of the open source database Apache HBase which gives customers for benifit of code portability.
* Cloud DataProc offers the open source big data enviorment hadoop as managed service.
* Kubernates gives customers the ability to mix and match micro services running accross different clouds
* Google StackDriver lets customers monitor workloads accross multiple cloud provider.

<img src="img/GCP_OpenAPI.jpg">

## GCP Services
* Compute
* Storage
* Big Data
* Machine Learning

<img src="img/GCP_Services.jpg">

## Multilayered Security Approach
*   Both the server boards and networking boards are designed by google.
* Google also designed its own custom security chips called titan which is currently deployed to both servers and peripherals.
* Google Infrastructure provides cryptograpic privacy and integrity for remote procedures and access to thier network.

<img src="img/GCP_Security.jpg">

## Budgets and Bills
*   We can setup a billing account specifically for a project or such.
*   Billing alerts can be set for notifications on Dashboard regarding the remaining budget of your project.
<img src="img/GCP_BudgetsAndAlerts.jpg">

* For getting more detailed billing information of every change with description comes under this section.
<img src="img/GCP_BillingExportBigQuerry.jpg">

*   Reports of each and every servies are recorded and we don noy ise co

<img src="img/GCP_BillingReports.jpg">

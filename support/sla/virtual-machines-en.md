<properties
	pageTitle="SLA for Virtual Machines | Azure"
    description="SLA for Virtual Machines"
    services=""
    documentationCenter=""
    authors=""
    manager=""
    editor=""
    tags=""/>

<tags ms.service="legal-en" ms.date="10/2017" wacn.date="10/2017" wacn.lang="en"/>

> [AZURE.LANGUAGE]
- [中文](/support/sla/virtual-machines/)
- [English](/support/sla/virtual-machines-en/)
# SLA for Virtual Machines

For all Virtual Machines that have two or more instances deployed in the same Availability Set, we guarantee you will have Virtual Machine Connectivity to at least one instance at least 99.95% of the time.

For any Single Instance Virtual Machine using premium storage for all disks, we guarantee you will have Virtual Machine Connectivity of at least 99.9%.

## Introduction

This Service Level Agreement for Azure (this “SLA”) is made by 21Vianet in connection with, and is a part of, the agreement under which Customer has purchased Azure Services from 21Vianet (the “Agreement”).

We provide financial backing to our commitment to achieve and maintain Service Levels for our Services. If we do not achieve and maintain the Service Levels for each Service as described in this SLA, then you may be eligible for a credit towards a portion of your monthly service fees. These terms will be fixed for term of your Agreement. If a subscription is renewed, the version of this SLA that is current at the time the renewal term commences will apply throughout the renewal term. We will provide at least 90 days' notice for adverse material changes to this SLA. You can review the most current version of this SLA at any time by visiting <a id="vm-sla-en_sla-index" href="/support/legal/sla/">https://www.azure.cn/support/legal/sla/</a>.

## General Terms

### 1. Definitions 

1. "Claim" means a claim submitted by Customer to 21Vianet pursuant to this SLA that a Service Level has not been met and that a Service Credit may be due to Customer. 

2. "Customer" refers to the organization that has entered into the Agreement.

3. "Customer Support" means the services by which 21Vianet may provide assistance to Customer to resolve issues with the Services.

4. "Error Code" means an indication that an operation has failed, such as an HTTP status code in the 5xx range.

5. "External Connectivity" is bi-directional network traffic over supported protocols such as HTTP and HTTPS that can be sent and received from a public IP address.

6. "Incident" means any set of circumstances resulting in a failure to meet a Service Level.

7. "Management Portal" means the web interface, provided by 21Vianet, through which customers may manage the Service.

8. "21Vianet" means the 21Vianet entity that appears on Customer's Agreement.

9. "Preview" refers to a preview, beta, or other pre-release version of a service or software offered to obtain customer feedback.

10. "Service” or “Services" refers to a Azure service provided to Customer pursuant to the Agreement for which an SLA is provided below.

11. "Service Credit" is the percentage of the monthly service fees for the affected Service or Service Resource that is credited to Customer for a validated Claim.

12. "Service Level" means standards 21Vianet chooses to adhere to and by which it measures the level of service it provides for each Service as specifically set forth below.

13. "Service Resource" means an individual resource available for use within a Service.

14. "Success Code" means an indication that an operation has succeeded, such as an HTTP status code in the 2xx range.

15. "Support Window" refers to the period of time during which a Service feature or compatibility with a separate product or service is supported. 

16. "Virtual Network" refers to a virtual private network that includes a collection of user-defined IP addresses and subnets that form a network boundary within Azure.

17. "Virtual Network Gateway" refers to a gateway that facilitates cross-premises connectivity between a Virtual Network and a customer on-premises network.

### 2. Service Credit Claims

1. In order for 21Vianet to consider a Claim, Customer must submit the Claim to Customer Support within two months of the end of the billing month in which the Incident that is the subject of the Claim occurs. Customer must provide to Customer Support all information necessary for 21Vianet to validate the Claim, including but not limited to detailed descriptions of the Incident, the time and duration of the Incident, the affected resources or operations, and any attempts made by Customer to resolve the Incident

2. 21Vianet will use all information reasonably available to it to validate the Claim and to determine whether any Service Credits are due.

3. In the event that more than one Service Level for a particular Service is not met because of the same Incident, Customer must choose only one Service Level under which a Claim may be made based on the Incident.

4. Service Credits apply only to fees paid for the particular Service, Service Resource, or Service tier for which a Service Level has not been met. In cases where Service Levels apply to individual Service Resources or to separate Service tiers, Service Credits apply only to fees paid for the affected Service Resource or Service tier, as applicable.

### 3. SLA Exclusions

This SLA and any applicable Service Levels do not apply to any performance or availability issues:

1. Due to factors outside 21Vianet’s reasonable control (for example, a network or device failure external to 21Vianet’s data centers, including at Customer's site or between Customer's site and 21Vianet’s data center);

2. That resulted from Customer's use of hardware, software, or services not provided by 21Vianet as part of the Services (for example, third-party software or services purchased from the Azure Store or other non-Azure services provided by 21Vianet);

3. Due to Customer's use of the Service in a manner inconsistent with the features and functionality of the Service (for example, attempts to perform operations that are not supported) or inconsistent with published documentation or guidance;

4. That resulted from faulty input, instructions, or arguments (for example, requests to access files that do not exist);

5. Caused by Customer's use of the Service after 21Vianet advised Customer to modify its use of the Service, if Customer did not modify its use as advised;

6. During or with respect to Previews or to purchases made using 21Vianet subscription credits;

7. That resulted from Customer's attempts to perform operations that exceed prescribed quotas or that resulted from throttling of suspected abusive behavior;

8. Due to Customer's use Service features that are outside of associated Support Windows; or

9. Attributable to acts by persons gaining unauthorized access to 21Vianet’s Service by means of Customer's passwords or equipment or otherwise resulting from Customer's failure to follow appropriate security practices.

### 4. Service Credits

1. The amount and method of calculation of Service Credits is described below in connection with each Service. 

2. Service Credits are Customer's sole and exclusive remedy for any failure to meet any Service Level.

3. The Service Credits awarded in any billing month for a particular Service or Service Resource will not, under any circumstance, exceed Customer's monthly service fees that Service or Service Resource, as applicable, in the billing month.

4. For Services purchased as part of a suite, the Service Credit will be based on the pro-rata portion of the cost of the Service, as determined by 21Vianet in its reasonable discretion. In cases where Customer has purchased Services from a reseller, the Service Credit will be based on the estimated retail price for the applicable Service, as determined by 21Vianet in its reasonable discretion.


## The SLA details

### Additional Definitions
 
1. "**Availability Set**" refers to two or more Virtual Machines deployed across different Fault Domains to avoid a single point of failure.

2. "**Fault Domain**" is a collection of servers that share common resources such as power and network connectivity.

3. "**Virtual Machine**" refers to persistent instance types that can be deployed individually or as part of an Availability Set.

4. "**Virtual Machine Connectivity**" is bi-directional network traffic between the virtual machine and other IP addresses using TCP or UDP network protocols in which the virtual machine is configured for allowed traffic. The IP addresses can be IP addresses in the same Cloud Service as the virtual machine, IP addresses within the same virtual network as the virtual machine or public, routable IP addresses. 

5. "**Announced Single Instance Maintenance**" means periods of Downtime related to network, hardware, or Service maintenance or upgrades impacting Single Instances. We will publish notice or notify you at least five (5) days prior to the commencement of such Downtime. 

6. "**Data Disk**" is a persistent virtual hard disk, attached to a Virtual Machine, used to store application data. 

7. "**Operating System Disk**" is a persistent virtual hard disk, attached to a Virtual Machine, used to store the Virtual Machine’s operating system. 

8. "**Single Instance**" is defined as any single Virtual Machine that either is not deployed in an Availability Set or has only one instance deployed in an Availability Set. 

### Monthly Uptime Calculation and Service Levels for Virtual Machines in an Availability Set

1. "**Maximum Available Minutes**" is the total accumulated minutes during a billing month for all Virtual Machines that have two or more instances deployed in the same Availability Set. Maximum Available Minutes is measured from when at least two Virtual Machines in the same Availability Set have both been started resultant from action initiated by Customer to the time Customer has initiated an action that would result in stopping or deleting the Virtual Machines. 

2. "**Downtime**" is the total accumulated minutes that are part of Maximum Available Minutes that have no Virtual Machine Connectivity.

3. "**Monthly Uptime Percentage**" for Virtual Machines is calculated as Maximum Available Minutes less Downtime divided by Maximum Available Minutes in a billing month for a given Azure subscription. Monthly Uptime Percentage is represented by the following formula:

	Monthly Uptime % = (Maximum Available Minutes − Downtime) / Maximum Available Minutes X 100
	
4. The following Service Levels and Service Credits are applicable to Customer's use of Virtual Machines in an Availability Set:

	MONTHLY UPTIME PERCENTAGE	|SERVICE CREDIT
	--------------------|---------
	<99.95%				|10% 
	<99%				|25% 
	<95%				|100% 
	
### Monthly Uptime Calculation and Service Levels for Single-Instance Virtual Machines

1. "**Minutes in the Month**" is the total number of minutes in a given month.

2. "**Downtime**" is the total accumulated minutes that are part of Minutes in the Month that have no Virtual Machine Connectivity. Downtime excludes Announced Single Instance Maintenance.

3. "**Monthly Uptime Percentage**" is calculated by subtracting from 100% the percentage of Minutes in the Month in which any Single Instance Virtual Machine using premium storage for all Operating System Disks and Data disks had Downtime.

	Monthly Uptime % = (Minutes in the Month - Downtime) / Minutes in the Month X 100
	
4. The following Service Levels and Service Credits are applicable to Customer’s use of Single-Instance Virtual Machines:

	MONTHLY UPTIME PERCENTAGE	|SERVICE CREDIT
	--------------------|---------
	<99.9%				|10% 
	<99%				|25% 
	<95%				|100% 

## Version History

<a id="vm-sla-en_vm-sla-en" href="/support/sla/virtual-machines-en/">1.4</a> Last updated： Oct 2017

<a id="vm-sla-en_vm-sla-en1.3.pdf" href="//wacnppe.blob.core.chinacloudapi.cn/marketing-resource/sla/virtual_machine_sla_english1.3.pdf">1.3</a> Last updated： May 2017

Release notes: Improved SLA by adding 100% service credit guarantee if uptime falls below 95%, and excluded temporary disks from the requirement to have premium storage on the single-instance SLA.

<a id="vm-sla-en_vm-sla-en-1.2pdf" href="//wacnppe.blob.core.chinacloudapi.cn/marketing-resource/sla/virtual_machine_sla_english1.2.pdf">1.2</a> Last updated： Mar 2017

Release notes: Added ‘X 100’ to the monthly uptime availability formulas to fix a typo.

<a id="vm-sla-en_vm-sla-en-1.1pdf" href="//wacnppe.blob.core.chinacloudapi.cn/marketing-resource/sla/virtual_machine_sla_english1.1.pdf">1.1</a> Last updated： Feb 2017

Release notes: Added a new, Single-Instance Virtual Machine SLA, Updates related to maximum available minutes

<a id="vm-sla-en_vm-sla-en-1.0pdf" href="//wacnppe.blob.core.chinacloudapi.cn/marketing-resource/sla/virtual_machine_sla_english1.0.pdf">1.1</a> Last updated： Mar 2016

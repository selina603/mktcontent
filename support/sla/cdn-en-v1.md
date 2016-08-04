﻿<properties
	pageTitle=""
    description=""
    services=""
    documentationCenter=""
    authors=""
    manager=""
    editor=""
    tags=""/>

<tags ms.service="legal-en" ms.date="03/2016" wacn.date="03/2016" wacn.lang="en"/>

> [AZURE.LANGUAGE]
- [中文](/support/sla/cdn-v1/)
- [English](/support/sla/cdn-en-v1/)
#SLA for CDN

We guarantee that at least 99.9% of the time CDN will respond to client requests and deliver the requested content without error. We will review and accept data from any commercially reasonable independent measurement system that you choose to monitor your content. You must select a set of agents from the measurement system's list of standard agents that are generally available and represent at least five geographically diverse locations in major People Republic of China metropolitan areas.


##Introduction
 

This Service Level Agreement for Azure (this “SLA”) is made by 21Vianet in connection with, and is a part of, the agreement under which Customer has purchased Azure Services from 21Vianet (the “Agreement”).

We provide financial backing to our commitment to achieve and maintain Service Levels for our Services. If we do not achieve and maintain the Service Levels for each Service as described in this SLA, then you may be eligible for a credit towards a portion of your monthly service fees. These terms will be fixed for term of your Agreement. If a subscription is renewed, the version of this SLA that is current at the time the renewal term commences will apply throughout the renewal term. We will provide at least 90 days' notice for adverse material changes to this SLA. You can review the most current version of this SLA at any time by visiting [http://www.azure.cn/support/legal/sla/](/support/legal/sla/).


##General Terms
 

###1. Definitions 

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

###2. Service Credit Claims

1. In order for 21Vianet to consider a Claim, Customer must submit the Claim to Customer Support within two months of the end of the billing month in which the Incident that is the subject of the Claim occurs. Customer must provide to Customer Support all information necessary for 21Vianet to validate the Claim, including but not limited to detailed descriptions of the Incident, the time and duration of the Incident, the affected resources or operations, and any attempts made by Customer to resolve the Incident

2. 21Vianet will use all information reasonably available to it to validate the Claim and to determine whether any Service Credits are due.

3. In the event that more than one Service Level for a particular Service is not met because of the same Incident, Customer must choose only one Service Level under which a Claim may be made based on the Incident.

4. Service Credits apply only to fees paid for the particular Service, Service Resource, or Service tier for which a Service Level has not been met. In cases where Service Levels apply to individual Service Resources or to separate Service tiers, Service Credits apply only to fees paid for the affected Service Resource or Service tier, as applicable.

###3. SLA Exclusions


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

###4. Service Credits

1. The amount and method of calculation of Service Credits is described below in connection with each Service. 

2. Service Credits are Customer's sole and exclusive remedy for any failure to meet any Service Level.

3. The Service Credits awarded in any billing month for a particular Service or Service Resource will not, under any circumstance, exceed Customer's monthly service fees that Service or Service Resource, as applicable, in the billing month.

4. For Services purchased as part of a suite, the Service Credit will be based on the pro-rata portion of the cost of the Service, as determined by 21Vianet in its reasonable discretion. In cases where Customer has purchased Services from a reseller, the Service Credit will be based on the estimated retail price for the applicable Service, as determined by 21Vianet in its reasonable discretion.


##The SLA details
 

###Monthly Uptime Calculation and Service Levels for CDN Service
1. 21Vianet is not responsible for comprehensive monitoring of customer content; this responsibility lies with customer. 21Vianet will review data from any commercially reasonable independent measurement system used by Customer.

2. Customer must select a set of agents from the measurement system's list of standard agents that are generally available and represent at least five major metropolitan areas in the People's Republic of China. 

	1) Measurement System tests (frequency of at least one test per hour per agent) will be configured to perform one HTTP(S) GET operation according to the model below: 

	2) A test file will be placed on Customer's origin (e.g., Azure Storage account).

	3) The GET operation will retrieve the file through the CDN Service, by requesting the object from the appropriate Azure domain name hostname.

	4) The test file will meet the following criteria: 

	- The test object will meet CDN caching specifications. For example, the response header should not include 'set-cookie' ; cache-control attributes cannot be set to 'private' or 'no-cache' ; the 'expires' value cannot be set at a past time value.

	- The test object will be a file at least 50KB in size and no larger than 1MB. 

	- Raw data will be trimmed to eliminate any measurements that came from an agent experiencing technical problems during the measurement period. 

	Remarks: 

	- In the event test results should reveal issues, please contact us as soon as possible so that we may verify said test results at first opportunity in order to locate the causes for these issues.

	- If the chosen test source itself contains problematic links, this will cause anomalies in the test results; these anomalies should be excluded when calculating the final availability value.

3. "Monthly Uptime Percentage" is the percentage of HTTP transactions in which the CDN responds to client requests and delivers the requested content without error. Monthly Uptime Percentage of the CDN Service is calculated as the number of times the object was delivered successfully divided by the total number of requests (after removing erroneous data).

4. The following Service Levels and Service Credits are applicable to Customer's use of the CDN Service:

Monthly Uptime Percentage | Service Credit  
---|---  
<99.9% | 5%   
<99% | 20% 


##Version History

1.0 Last updated: December 2015

Release notes: Monthly Uptime Percentage<99.9%

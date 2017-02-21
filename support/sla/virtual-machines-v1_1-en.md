<properties
	pageTitle="SLA for Virtual Machines | Azure"
    description="SLA for Virtual Machines"
    services=""
    documentationCenter=""
    authors=""
    manager=""
    editor=""
    tags=""/>

<tags ms.service="legal-en" ms.date="02/2017" wacn.date="02/2017" wacn.lang="en"/>

> [AZURE.LANGUAGE]
- [中文](/support/sla/virtual-machines/)
- [English](/support/sla/virtual-machines-en/)
# SLA for Virtual Machines

For all Virtual Machines that have two or more instances deployed in the same Availability Set, we guarantee you will have Virtual Machine Connectivity to at least one instance at least 99.95% of the time.

For any Single Instance Virtual Machine using premium storage for all disks, we guarantee you will have Virtual Machine Connectivity of at least 99.9%.

# The SLA details

## Additional Definitions
 
1. "**Availability Set**" refers to two or more Virtual Machines deployed across different Fault Domains to avoid a single point of failure.

2. "**Fault Domain**" is a collection of servers that share common resources such as power and network connectivity.

3. "**Virtual Machine**" refers to persistent instance types that can be deployed individually or as part of an Availability Set.

4. "**Virtual Machine Connectivity**" is bi-directional network traffic between the virtual machine and other IP addresses using TCP or UDP network protocols in which the virtual machine is configured for allowed traffic. The IP addresses can be IP addresses in the same Cloud Service as the virtual machine, IP addresses within the same virtual network as the virtual machine or public, routable IP addresses. 

## Monthly Uptime Calculation and Service Levels for Virtual Machines

1. "**Minutes in the Month**" is the total accumulated minutes during a billing month for all Internet facing Virtual Machines that have two or more instances deployed in the same Availability Set. Maximum Available Minutes is measured from when at least two Virtual Machines in the same Availability Set have both been started resultant from action initiated by Customer to the time Customer has initiated an action that would result in stopping or deleting the Virtual Machines. 

2. "**Downtime**" means periods of Downtime related to network, hardware, or Service maintenance or upgrades impacting Single Instances. We will publish notice or notify you at least five (5) days prior to the commencement of such Downtime.

3. "**Monthly Uptime Percentage**" for Virtual Machines is calculated as Maximum Available Minutes less Downtime divided by Maximum Available Minutes in a billing month for a given Azure subscription. Monthly Uptime Percentage is represented by the following formula:

	Monthly Uptime % = (Maximum Available Minutes − Downtime) / Maximum Available Minutes
	
4. The following Service Levels and Service Credits are applicable to Customer's use of Virtual Machines:

	MONTHLY UPTIME PERCENTAGE	|SERVICE CREDIT
	--------------------|---------
	<99.95%				|10% 
	<99%				|25% 
	
## Monthly Uptime Calculation and Service Levels for Single-Instance Virtual Machines

1. "**Minutes in the Month**" is the total number of minutes in a given month.

2. "**Downtime**" is the total accumulated minutes that are part of Minutes in the Month that have no Virtual Machine Connectivity. Downtime excludes Announced Single Instance Maintenance.

3. "**Monthly Uptime Percentage**" is calculated by subtracting from 100% the percentage of Minutes in the Month in which any Single Instance Virtual Machine using premium storage for all disks had Downtime.

	Monthly Uptime % = 100% - (Minutes in the Month - Downtime) / Minutes in the Month
	
4. The following Service Levels and Service Credits are applicable to Customer’s use of Single-Instance Virtual Machines:

	MONTHLY UPTIME PERCENTAGE	|SERVICE CREDIT
	--------------------|---------
	<99.9%				|10% 
	<99%				|25% 

#Version History

1.1 Last updated： February 2017
Release notes: Added a new, Single-Instance Virtual Machine SLA, Updates related to maximum available minutes


<properties
	pageTitle="Global Customer Playbook planning-explore-performance | Azure"
	description="Global Customer Playbook - exploring the Performance area of the Planning Stage"
	services="global-customer-playbook"
	documentationCenter=""
	authors="jtong"
	manager="edwinc"
	editor=""
	tags="global-customer-playbook"/>

<tags
	ms.service="migration-lifecycle-planning"
	ms.workload=""
	ms.tgt_pltfrm=""
	ms.devlang="na"
	ms.topic="article"
	ms.date="12/26/2016"
	wacn.date="12/26/2016"
	wacn.lang="en"
	ms.author="jtong"/>


# Planning Stage - Exploring Performance

[AZURE.INCLUDE [header](../../../includes/planning-explore.md)]


## China Latency Issue

In general, the network latency between China and the rest of the world is inevitable given the unpredictable nature of the Great Firewall of China acting as an intermediary. If you want to offer the best user experience for your services or web sites, you should consider the following:
 
- You may think of the CDN as a possible solution for your website hosted outside of China. However, a global CDN does not have a Point of Presence (PoP) inside mainland China, only the CDN service in China does, but its coverage is limited to mainland China region only.
 
- You may need to consider having an individual web site hosted in China to serve your users in China. This will provide the best experience for customers in China.
 
In summary, in order to have your service or website available to users worldwide, the general rule of thumb is to:

- host the workload targeting Chinese users on Azure China.
- deploy workload to the closest Azure region for users located outside of China.
</br>
</br>

## Global Connectivity and Interoperability

Given that you have decided to host your web site and your workload within China, you will need to consider global connectivity and interoperability from a hybrid cloud scenario.

Firstly, you can have a VPN or Express Route setup for your hybrid cloud, with a direct network connection between Azure China and your on-premises private cloud and/or back-end systems within China.

For connectivity to the external site (outside of China), direct network connectivity is not possible via Express Route. Even with Azure Global and Azure China, there is no network connectivity. However, you can setup a site-to-site VPN as an alternative solution for your site in Azure China to your on-premises location outside of China.

In either case, to have a VPN/Express Route setup connecting your services on Azure China, (i.e. your ICP registered hosting location to an outside location) you need to register, report, and obtain approval from MIIT, you can get help from 21Vianet for the approval process.

For further information, please check out the Global Connectivity and Interoperability [Guidance](/solutions/global-customer/planning/guidance/performance/).</br>
</br>

![navigation](../../media/navigation.png)

Let's move to the next section - [Partners](/solutions/global-customer/planning/explore/partners/).

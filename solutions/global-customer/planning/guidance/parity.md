<properties
	pageTitle="Global Customer Playbook planning-guidance-parity | Azure"
	description="Global Customer Playbook planning-guidance-parity"
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


# Planning Guidance - Parity

[AZURE.INCLUDE [header](../../../includes/planning-guidance.md)]

## Differences from a Developer Perspective

Since most of the technical content that Microsoft currently provides assumes that the application is developed for Azure Global, rather than Azure China, it is important to ensure that developers understand the differences in services hosted in China.
 
First, there are functional differences, which means that the global service has some features that are not available in China, as summarized in the previous section on [Parity](/solutions/global-customer/envisioning/guidance/parity/).
Secondly, there are differences contributed by the difference in operations in China, in particular the Azure service endpoints, which you must customize by yourself for any sample code and steps published in the technical content for Azure Global.
 
The table below summarizes the differences in Azure Service endpoint mapping:

| Service Category | Azure Global URI | Azure China URI |
|:---------------- |:---------------- |:--------------- |
| Azure – In General | *.windows.net | *.chinacloudapi.cn |
| Azure - Compute | *.cloudapp.net | *.chinacloudapp.cn |
| Azure - Storage | *.blob.core.windows.net *.queue.core.windows.net *.table.core.windows.net | *.blob.core.chinacloudapi.cn *.queue.core.chinacloudapi.cn *.table.core.chinacloudapi.cn |
| Azure – Service Management | https://management.core.windows.net | https://management.core.chinacloudapi.cn |
| Azure - ARM | https://management.azure.com | https://management.chinacloudapi.cn |
| SQL Database | *.database.windows.net | *.database.chinacloudapi.cn |
| Azure – Management Portal | http://manage.windowsazure.com | http://manage.windowsazure.cn |
| SQL Azure DB Management API | https://management.database.windows.net | https://management.database.chinacloudapi.cn |
| Service Bus | *.servicebus.windows.net | *.servicebus.chinacloudapi.cn |
| ACS | *.accesscontrol.windows.net | *.accesscontrol.chinacloudapi.cn |
| HDInsight | *.azurehdinsight.net | *.azurehdinsight.cn |
| SQL DB Import/Export Service Endpoint |  | 1. China East： https://sh1prod-dacsvc.chinacloudapp.cn/dacwebservice.svc</br>  2. China North：https://bj1prod-dacsvc.chinacloudapp.cn/dacwebservice.svc |

Please refer to the following link for details on the Developer Notes (in Chinese): 
[Developer Notes](https://www.azure.cn/documentation/articles/developerdifferences/#dev-guide)
</br>
</br>

## Differences in Service Pricing

Due to the functional differences as summarized in the previous section on [Parity](/solutions/global-customer/envisioning/guidance/parity/), 
and the operating model differences comparing Azure Global and Azure China, you might notice that there are differences in the service price structure.
 
This may impact your business planning and we recommended you to do an estimation of the required costs. For more details, please check out the following link regarding the Azure China service price list: [Pricing](https://www.azure.cn/pricing/overview/).
 
If you need an English translation, please refer to this link
[Translated Pricing](https://translate.google.com.hk/translate?hl=zh-CN&sl=zh-CN&tl=en&u=https%3A%2F%2Fwww.azure.cn%2Fpricing%2Foverview%2F).
</br>
</br>

## Application Migration Design Scenarios

In order to serve as a guide on the migration of your applications from an application architecture perspective, we focused on the application migration design for 2 scenarios: Refactor and Rehost.

- [Refactor Migration Scenario](/solutions/global-customer/planning/guidance/refactor-migration/) - 
Covers the scenario that you are deploying new applications on Azure China, which you may have these applications already running on other cloud providers, and would like to look for solutions for a better and faster migration to Azure China.

- [Rehost Migration Scenarios](/solutions/global-customer/planning/guidance/rehost-migration/) - 
Covers the scenario for redeploying the application to a different cloud environment. This is to serve as a guide on the migration design for your applications or workloads that run on Azure Global, and to have them migrated to Azure China.
</br>
</br>

## Global Connection Toolkit

The goal of the Azure Global Connection Toolkit is to connect different national clouds and to eliminate the friction to migrate applications between the national clouds.

Currently, the Global Connection Toolkit offers two components:

- Assessment Tool: Assessment Tool is a quick and simple tool to generate report and answer "Frequent Asked Question" when migrating Azure Services between different environment like service parity, cost estimation and considerations. It is a PowerShell Module and after install you can start assessment your subscription to make sure the plan and validation of migration.

- CICD Tool: CICD (Continuous Integration Continuous Deliver) Tool is a quick and simple tool to validate and perform the actual migration as script base. For example, you can leverage the toolkit to migrate your VMs from East Asia to China East. The toolkit will sync your data and configuration so that everything is as same as original. Moreover, the scripts is open source so you can just integrate into your own DevOps process to perform CICD between Azure Environments

For details, please check out the [Migration Assistant](/solutions/global-customer/migration-assistant/) guide.
</br>
</br>

![navigation](../../media/navigation.png)

Let's move to the next section - [Performance](/solutions/global-customer/planning/guidance/performance/)























































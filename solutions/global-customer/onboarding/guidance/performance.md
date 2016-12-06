<properties
	pageTitle="Global Customer Playbook onboarding-guidance-performance "
	description="Global Customer Playbook onboarding-guidance-performance"
	services="global-customer-playbook"
	documentationCenter=""
	authors="jtong"
	manager="edwinc"
	editor=""
	tags="global-customer-playbook"/>

<tags
	ms.service="migration-lifecycle-onboarding"
	ms.workload=""
	ms.tgt_pltfrm=""
	ms.devlang="na"
	ms.topic="article"
	ms.date="11/21/2016"
	wacn.date="11/21/2016"
	wacn.lang="en"
	ms.author="jtong"/>


# Onboarding Guidance - Performance

[AZURE.INCLUDE [header](../../../../mktcontent/includes/onboarding-guidance.md)]


## China Latency Issue

When deploying your applications, you may experience issues with the network performance due to network latency and the Great Firewall effect, you will need to find a better way to work with this issue. 
 
The connectivity speed from your administration desktop (outside of China) to the Azure China VM may be slow, although this will not happen all of the time. Take using the SSH (or secure shell) to connect to your remote server as an example. The recommendation is for you to SSH to a local Azure VM, then use this VM and SSH to the Azure China VM. By doing this workaround, you will have a faster network connection speed.


![navigation](../../media/navigation.png)

Let's move to the next section - [Partners](/solutions/global-customer/onboarding/guidance/partners/) .

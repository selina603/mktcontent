<properties
	pageTitle="Global Customer Playbook envisioning-guidance-parity"
	description="Global Customer Playbook envisioning-guidance-parity"
	services="global-customer-playbook"
	documentationCenter=""
	authors="jtong"
	manager="edwinc"
	editor=""
	tags="global-customer-playbook"/>

<tags
	ms.service="migration-lifecycle-envisioning"
	ms.workload=""
	ms.tgt_pltfrm=""
	ms.devlang="na"
	ms.topic="article"
	ms.date="11/21/2016"
	wacn.date="11/21/2016"
	wacn.lang="en"
	ms.author="jtong"/>


# Envisioning Guidance - Parity

[AZURE.INCLUDE [header](../../../../mktcontent/includes/envisioning-guidance.md)]

## Global Azure and China Azure Services Asymmetry

China Azure, or Mooncake, is a separate instance of Azure operated by 21Vianet. There are differences in the availability of Azure services, compared to that of Global Azure.
 
Below is a summary table based on service parity, essentially comparing Global Azure to Mooncake (Note: if there is difference, it is highlighted in yellow).
 
It should be noted that new services are still being launched. The following table is the information updated as of date Nov 29, 2016. You should always refer to the latest services offered in Mooncake at www.azure.cn.

Service Category | Services | Global Azure (WW) | Mooncake (via 21vianet)
---------------- | ---------------- | ---------------- | ----------------
**Compute** | Virtual Machines | A series Basic</br> A series Standard</br> D series</br> Dv2 series</br> F series</br> <mark>G series</br> N series</br> H series</br> A8 & A9 network optimized</br> A10 & A11 compute optimized</mark> | A series Basic</br> A series Standard</br> D series</br> Dv2 series</br> F series </br></br></br></br></br></br>
  | Virtual Machine Scale Sets | ditto | ditto
  | Cloud Services | A series</br> D series</br> Dv2 series</br> <mark>A8 & A9 network optimized</br> A10 & A11 compute optimized</mark> | A series</br> D series</br> Dv2 series</br></br></br>
  | Batch | GA | GA
  | Service Fabric | GA</br> <mark>Service Fabric for Linux (Preview)</mark> | GA</br> NA
  | Functions | <mark>Preview</mark> | NA
  | Azure Container Service | <mark>GA</mark> | NA
  | Azure Container Registry | <mark>Preview</mark> | NA
**Storage** | Storage (Blob</br> File</br> Table</br> Queue) | Standard Storage</br> Premium Storage (available in some regions)</br> Cool/Hot | Standard Storage</br> Premium Storage</br> Cool/Hot
 | Data Lake Store | <mark>GA</mark> | NA
 | StorSimple | StorSimple 5000</br> StorSimple 7000</br> <mark>StorSimple 8000</mark> | StorSimple 5000</br> StorSimple 7000
 | Backup | File Backup</br> IaaS VM Backup | File Backup</br> IaaS VM Backup
 | Site Recovery | GA</br> On-premise VMM to Azure</br> On-premise Hyper-V to Azure</br> <mark>On-premise VMware/Physical server to Azure (Preview)</br> Between two on-premise VMware Sites</br> Protect SQL Server(Preview)</mark> | GA</br> On-premise VMM to Azure</br> On-premise Hyper-V to Azure
**Networking** | Virtual Networks | Static/Dynamic Routing VPN Gateway</br> Standard VPN Gateway</br> High Performance VPN Gateway</br> Application Gateway | Static/Dynamic Routing VPN Gateway</br> Standard VPN Gateway</br> High Performance VPN Gateway</br> Application Gateway
 | ExpressRoute | Provide the following port speed :</br> 50 Mbp</br> 100 Mbp</br> 200 Mbp</br> 500 Mbp</br> 1 Gbp</br> 2 Gbp</br> 5 Gbp</br> 10 Gbp | Provide the following port speed :</br> 50 Mbp</br> 100 Mbp</br> 200 Mbp</br> 500 Mbp</br> 1 Gbp</br> 2 Gbp</br> 5 Gbp</br> 10 Gbp
 | DNS | <mark>Preview</mark> | NA
 | Traffic Manager | GA | GA
 | Load Balancer | GA | GA
**Web & Mobile** | App Service | Free</br> Shared</br> Basic</br> Standard</br> Premium</br></br> Following services are available:</br>Web App</br>Mobile App</br>API App</br>Logic App</br>Web App on Linux (Preview) | Free</br> Shared</br> Basic</br> Standard</br> Premium</br></br>  <mark>Only followings available:</br> Web Apps</br> Mobile Apps</br> API Apps</mark></br></br></br>
 | Mobile Engagement | <mark>GA</mark> | NA
 | Azure Search | <mark>Free</br> Basic</br> Standard S1</br> Standard S2</br> Standard S3</mark> | NA
**Databases** | SQL Database | Single database</br>(Basic, Standard, Premium, Geo-replication)</br> Elastic database</br>(Basic, Standard, Premium, Geo-replication) | Single database</br>(Basic, Standard, Premium, Geo-replication)</br> Elastic database</br>(Basic, Standard, Premium, Geo-replication)
 | SQL Data Warehouse | <mark>GA</mark> | Preview
 | SQL Server Stretch Database | GA | GA
 | Redis Cache | Basic, Standard, Premium | Basic, Standard, Premium
 | DocumentDB | GA | GA
 | MySQL Database on Azure | NA | <mark>MS1, MS2, MS3, MS4, MS5, MS6</mark>
**Intelligence + Analytics** | Cortana Intelligence | <mark>GA</mark> | NA
 | Cognitive Services | Preview | Preview
 | HDInsight | HBase, Storm </br> <mark>Spark, R Server, Kafka (Preview)</mark><br> <mark>HDInsight on Linux</mark></br></br>General Purpose Node</br> Optimized Node</br> <mark>A10 & A11 Compute Intensive Node</mark> | HBase, Storm</br></br></br></br>General Purpose Node</br>Optimized Node</br></br>
 | Machine Learning | <mark>Free, Standard</mark> | NA
 | Stream Analytics | GA | GA
 | Azure Bot Service | <mark>Preview</mark> | NA
 | Data Factory | <mark>Low Frequency, High Frequency</mark> | NA
 | Data Lake Store | <mark>GA</mark> | NA
 | Data Lake Analytics | <mark>GA</mark> | NA
 | Power BI (SaaS) | GA | GA
 | Power BI Embedded | <mark>GA</mark> | NA
**IoT** | Events Hub | Basic, Standard | Basic, Standard
 | IoT Hub | GA | GA
 | IoT Suite | GA | GA
 | Stream Analytics | GA | GA
 | Notification Hubs | Free, Basic, Standard | Free, Basic, Standard
**Media & CDN** | Media Services | Encoding, Indexing, Streaming</br> DRM <mark>(support multi-DRM : PlayReady, Widevine, and FairPlay Streaming)</mark> | Encoding, Indexing, Streaming</br> DRM 
 | CDN | Provided by <mark>EdgeCast</mark> | Provided by <mark>local CDN</mark> provider
**Enterprise Integration** | BizTalk Services | <mark>Free, Developer, Basic, Standard, Premium</mark> | NA
 | Service Bus | Basic, Standard</br><mark>Premium</mark> | Basic, Standard</br>
 | API Management | <mark>Developer, Standard, Premium</mark> | NA
 | Logic Apps | <mark>GA</mark> | NA
 | Data Catalog | <mark>Free, Standard</mark> | NA
**Security & Identity** | Azure Active Directory | Free</br><mark>Basic, Premium</mark> | Free</br>(Self Service Password Reset is available)
 | Azure Active Directory B2C | <mark>GA</mark> | NA
 | Azure AD Domain Services | <mark>GA</mark> | NA
 | Multi-factor Authentication | GA | GA
 | Key Vault |	Standard, Premium </br></br> | Standard, Premium</br><mark>No HSM offering</mark>
 | Security Centre | <mark>Free, Standard</mark> | NA
**Developer Tools** | Visual Studio Team Services | <mark>Basic, Professional, Advanced</mark> | NA
 | Application Insights | <mark>Free, Basic, Enterprise</mark> | NA
 | DevTest Labs | <mark>Free</mark> | NA
 | HockeyApp | <mark>GA</mark> | NA
**Monitoring & Management** | Azure Portal | GA | Preview
 | Azure Resource Manager | GA | GA
 | Marketplace | <mark>GA</mark> | Preview
 | Scheduler | Free, Standard, Premium | Free, Standard, Premium
 | Automation | Free, Basic</br><mark>Desired State Configuration (DSC)</mark> | Free, Basic</br>
 | Operational Insights | <mark>Free, Standard, Premium</mark> | NA
 | Log Analytics | <mark>Free, Standard, Premium</mark> | NA
 
![navigation](../../media/navigation.png)

Let's move to the next section - [Performance](/solutions/global-customer/envisioning/guidance/performance/) .

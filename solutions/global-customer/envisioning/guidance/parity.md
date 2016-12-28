<properties
	pageTitle="Global Customer Playbook envisioning-guidance-parity | Azure"
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
	ms.date="12/26/2016"
	wacn.date="12/26/2016"
	wacn.lang="en"
	ms.author="jtong"/>


# Envisioning Guidance - Parity

[AZURE.INCLUDE [header](../../../includes/envisioning-guidance.md)]

## Global Azure and China Azure Services Asymmetry

China Azure is a separate instance of Azure operated by 21Vianet. There are differences in the availability of Azure services, compared to that of Global Azure.
 
Below is a summary table based on service parity, essentially comparing Global Azure to China Azure (Note: if there is difference, it is highlighted in bold text).
 
It should be noted that new services are still being launched. The following table is the information updated as of date Nov 29, 2016. You should always refer to the latest services offered in China Azure at www.azure.cn.

Service Category | Services | Global Azure (WW) | China Azure (via 21vianet)
---------------- | ---------------- | ---------------- | ----------------
**Compute** | Virtual Machines | A series Basic</br> A series Standard</br> D series</br> Dv2 series</br> F series</br> **G series</br> N series</br> H series</br> A8 & A9 network optimized</br> A10 & A11 compute optimized** | A series Basic</br> A series Standard</br> D series</br> Dv2 series</br> F series </br></br></br></br></br></br>
  | Virtual Machine Scale Sets | ditto | ditto
  | Cloud Services | A series</br> D series</br> Dv2 series</br> **G series</br> A8 & A9 network optimized</br> A10 & A11 compute optimized** | A series</br> D series</br> Dv2 series</br></br></br>
  | Batch | GA | GA
  | Service Fabric | GA</br> **Service Fabric for Linux (Preview)**| GA</br> NA
  | Functions | **Preview** | NA
  | Azure Container Service | **GA** | NA
  | Azure Container Registry | **Preview** | NA
**Storage** | Storage (Blob</br> File</br> Table</br> Queue) | Standard Storage</br> Premium Storage (available in some regions)</br> Cool/Hot | Standard Storage</br> Premium Storage</br> Cool/Hot
 | Data Lake Store | **GA** | NA
 | StorSimple | StorSimple 5000</br> StorSimple 7000</br> **StorSimple 8000** | StorSimple 5000</br> StorSimple 7000
 | Backup | File Backup</br> IaaS VM Backup | File Backup</br> IaaS VM Backup
 | Site Recovery | GA</br> On-premise VMM to Azure</br> On-premise Hyper-V to Azure</br> **On-premise VMware/Physical server to Azure (Preview)</br> Between two on-premise VMware Sites</br> Protect SQL Server(Preview)** | GA</br> On-premise VMM to Azure</br> On-premise Hyper-V to Azure
**Networking** | Virtual Networks | Static/Dynamic Routing VPN Gateway</br> Standard VPN Gateway</br> High Performance VPN Gateway</br> Application Gateway | Static/Dynamic Routing VPN Gateway</br> Standard VPN Gateway</br> High Performance VPN Gateway</br> Application Gateway
 | ExpressRoute | Provide the following port speed :</br> 50 Mbp</br> 100 Mbp</br> 200 Mbp</br> 500 Mbp</br> 1 Gbp</br> 2 Gbp</br> 5 Gbp</br> 10 Gbp | Provide the following port speed :</br> 50 Mbp</br> 100 Mbp</br> 200 Mbp</br> 500 Mbp</br> 1 Gbp</br> 2 Gbp</br> 5 Gbp</br> 10 Gbp
 | DNS | **Preview** | NA
 | Traffic Manager | GA | GA
 | Load Balancer | GA | GA
**Web & Mobile** | App Service | Free</br> Shared</br> Basic</br> Standard</br> Premium</br></br> Following services are available:</br>Web App</br>Mobile App</br>API App</br>Logic App</br>Web App on Linux (Preview) | Free</br> Shared</br> Basic</br> Standard</br> Premium</br></br>  **Only followings available:</br> Web Apps</br> Mobile Apps</br> API Apps**</br></br></br>
 | Mobile Engagement | **GA** | NA
 | Azure Search | **Free</br> Basic</br> Standard S1</br> Standard S2</br> Standard S3** | NA
**Databases** | SQL Database | Single database</br>(Basic, Standard, Premium, Geo-replication)</br> Elastic database</br>(Basic, Standard, Premium, Geo-replication) | Single database</br>(Basic, Standard, Premium, Geo-replication)</br> Elastic database</br>(Basic, Standard, Premium, Geo-replication)
 | SQL Data Warehouse | **GA** | Preview
 | SQL Server Stretch Database | GA | GA
 | Redis Cache | Basic, Standard, Premium | Basic, Standard, Premium
 | DocumentDB | GA | GA
 | MySQL Database on Azure | NA | **MS1, MS2, MS3, MS4, MS5, MS6**
**Intelligence + Analytics** | Cortana Intelligence | **GA** | NA
 | Cognitive Services | Preview | Preview
 | HDInsight | HBase, Storm </br> **Spark, R Server, Kafka (Preview)**<br> **HDInsight on Linux**</br></br>General Purpose Node</br> Optimized Node</br> **A10 & A11 Compute Intensive Node** | HBase, Storm</br></br></br></br>General Purpose Node</br>Optimized Node</br></br>
 | Machine Learning | **Free, Standard** | NA
 | Stream Analytics | GA | GA
 | Azure Bot Service | **Preview** | NA
 | Data Factory | **Low Frequency, High Frequency** | NA
 | Data Lake Store | **GA** | NA
 | Data Lake Analytics | **GA**| NA
 | Power BI (SaaS) | GA | GA
 | Power BI Embedded | **GA** | NA
**IoT** | Events Hub | Basic, Standard | Basic, Standard
 | IoT Hub | GA | GA
 | IoT Suite | GA | GA
 | Stream Analytics | GA | GA
 | Notification Hubs | Free, Basic, Standard | Free, Basic, Standard
**Media & CDN** | Media Services | Encoding, Indexing, Streaming</br> DRM **(support multi-DRM : PlayReady, Widevine, and FairPlay Streaming)** | Encoding, Indexing, Streaming</br> DRM 
 | CDN | Provided by **EdgeCast** | Provided by **local CDN** provider
**Enterprise Integration** | BizTalk Services | **Free, Developer, Basic, Standard, Premium** | NA
 | Service Bus | Basic, Standard</br>**Premium** | Basic, Standard</br>
 | API Management | **Developer, Standard, Premium** | NA
 | Logic Apps | **GA** | NA
 | Data Catalog | **Free, Standard** | NA
**Security & Identity** | Azure Active Directory | Free</br>**Basic, Premium** | Free</br>(Self Service Password Reset is available)
 | Azure Active Directory B2C | **GA** | NA
 | Azure AD Domain Services | **GA** | NA
 | Multi-factor Authentication | GA | GA
 | Key Vault |	Standard, Premium </br></br> | Standard, Premium</br>**No HSM offering**
 | Security Centre | **Free, Standard** | NA
**Developer Tools** | Visual Studio Team Services | **Basic, Professional, Advanced** | NA
 | Application Insights | **Free, Basic, Enterprise** | NA
 | DevTest Labs | **Free** | NA
 | HockeyApp | **GA** | NA
**Monitoring & Management** | Azure Portal | GA | Preview
 | Azure Resource Manager | GA | GA
 | Marketplace | **GA** | Preview
 | Scheduler | Free, Standard, Premium | Free, Standard, Premium
 | Automation | Free, Basic</br>**Desired State Configuration (DSC)** | Free, Basic</br>
 | Operational Insights | **Free, Standard, Premium** | NA
 | Log Analytics | **Free, Standard, Premium** | NA
 
![navigation](../../media/navigation.png)

Let's move to the next section - [Performance](/solutions/global-customer/envisioning/guidance/performance/) .

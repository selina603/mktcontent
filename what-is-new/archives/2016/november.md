<properties
	pageTitle="历史公告 2016年11月 | Azure"
    description="历史公告 2016年11月"
    services=""
    documentationCenter=""
    authors=""
    manager=""
    editor=""
    tags=""/>
 
<tags ms.service="what-is-new_archives" ms.date="" wacn.date="" wacn.lang="cn"/>

# Azure 公告
## 2016年11月时事通讯

### 公告
### 2016年11月30日 Azure 媒体服务：当前的媒体保留单元计量方式的调整  

以前，Azure 媒体服务中媒体保留单元 (MRU) 的使用量基于使用的 MRU 的高水位值（按天进行比例分配）。从 2017 年 1 月 1 日起，现有的 S1（基本）、S2（标准） 和 S3（高级） 媒体保留单元计量方式将弃用，MRU 的使用量基于在您帐户中启用的每个 MRU 的时间，度量单位将从每天变成每小时。除了度量单位，媒体保留单元的有效月费率也将降低。这些计量方式的名称不会更改，仍为 S1、S2 和 S3 媒体保留单元。您不需要对应用程序代码做任何更改，但是可能需要修改依赖于资源 GUID 的计费例程。有关定价的详细信息，请访问[媒体服务价格详情](/pricing/details/media-services/)页面。要了解此服务的详细信息，请访问[媒体服务功能](/home/features/media-services/)页面。

### 2016年11月30日 Azure 媒体服务：当前的标准编码器计量方式的调整

以前，Azure 媒体服务中视频按需编码的使用量基于编码器输出的媒体文件大小 (GB)。从 2017 年 1 月 1 日起，现有的标准编码（输出 GB）计量方式将弃用。按需编码的使用量将改为基于编码器输出的媒体文件的持续时间来计费。新的计量方式称为标准编码。根据对典型客户场景的成本模拟和分析，这种新的计量方式会让您平均节省大约 40–50% 的成本。具体的节省额将取决于使用场景和之前采用的按 GB 定价的收费模式。您不需要对应用程序代码做任何更改，但是可能需要修改依赖于资源 GUID 的计费例程。有关定价的详细信息，请访问[媒体服务价格详情](/pricing/details/media-services/)页面。要了解此服务的详细信息，请访问[媒体服务功能](/home/features/media-services/)页面。


### 2016年11月28日 Azure CDN Smart Routing 功能正式上线  

作为融合 CDN 服务商，Azure China CDN 整合国内多家优质 CDN 厂商的资源，并自主研发了智能调度机制，充分利用各家 CDN 厂商的资源优势，在不同的城市和运营商挑选最优的 CDN 厂商节点服务终端用户。启用 Smart Routing 功能后，同一个 CDN 加速域名在 Azure China CDN 平台上是同时配置了（多 CNAME 机制）多家 CDN 服务厂商。当访问者具体访问某个文件时，Azure China CDN 平台会根据 Smart Routing 的调度策略来动态选择一家 CDN 服务商的资源，响应用户请求，整个过程对客户来说是完全透明的，客户不需要做任何的设置改动。

更多详情，请参考博文[Azure CDN Smart Routing 功能正式上线](/blog/2016/11/28/AzureCDNSmartRouting/)。


### 2016年11月4日 Azure 媒体服务的 Apple FairPlay Streaming 正式发布 

[Apple FairPlay Streaming](https://developer.apple.com/streaming/fps/?WT.mc_id=azurebg_email_Trans_1146_Tier_2_Release_Direct)(FPS) 是 Apple 的数字版权管理 (DRM) 格式，既可保护点播 (VOD) 流，也可保护直播流。利用 FairPlay，您可以通过 API 以编程方式构建 FairPlay Streaming 解决方案，从而覆盖最新版本的 Apple TV。结合现有的 PlayReady 和 Widevine DRM 支持，Azure 媒体服务可为您提供单点控制，以快速构建多 DRM 解决方案。敬请阅读[使用 Azure 媒体服务将优质内容流传输至 Apple TV](/blog/2016/11/08/AzureAppleTV/)博客文章进行初步了解。更多信息请参考[媒体服务功能](/home/features/media-services/)页面和[媒体服务价格详情](/pricing/details/media-services/)页面。


### 2016年11月3日 Azure 应用服务现已发布

Azure 应用服务是一款企业级云应用服务，可帮助您更快、更轻松地创建适用于多种平台和设备的功能强大的企业 Web 应用和移动应用。应用服务将 Azure 网站、移动服务、API 管理以及 API 应用中的新功能完美集于一体，可以为您提供一整套构建开发和管理体验的模型所需的统一功能。有关详细信息，请访问[应用服务功能](/home/features/app-service/)页面、[应用服务价格详情](/pricing/details/app-service/)页面、[应用服务文档](/documentation/services/app-service/)页面。

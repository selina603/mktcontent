<properties
	pageTitle="历史公告 2016年9月 | Azure"
    description="历史公告 2016年9月"
    services=""
    documentationCenter=""
    authors=""
    manager=""
    editor=""
    tags=""/>

<tags ms.service="what-is-new_archives" ms.date="" wacn.date="" wacn.lang="cn"/>

# Azure 公告
## 2016年9月时事通讯

### 公告
### 2016年9月28日 Azure 存储指标更新

为了明确与 Azure 存储相关的计费，从 2016 年 10 月 1 日起，我们将更改存储以及与存储相关的资源 GUID。建议您对自定义应用程序中的存储资源 GUID 进行相应的更改。作为这些更改的一部分，存储事务指标将根据事务的类型和相关联的存储服务分为多个指标。<br/>
此外，资源名称“标准 IO - 表格/队列 (GB)”将被分成两个名称： 标准 IO - 表格 (GB)   和   标准 IO - 队列 (GB) <br/>
要查看 GUID 更改之前和之后的各种资源类型，请访问[Azure 存储 GUID](/support/announcement/guids-migration-storage-transactions/), 更多信息请访问[存储功能页面](/home/features/storage/)和[存储价格详情](/pricing/details/storage/)。							   

### 2016年9月19日 认知服务预览版登陆中国  

认知服务 （预览版） 正式开始在中国地区提供服务。通过认知服务 API ，您只需使用几行代码就可以借助强大的算法开发自己的应用程序。它们跨设备、跨平台，不论是在 iOS 、 Android 或者 Windows ，您都可以轻松完成配置。此次国内首发共推出 3 个全新 API ：[人脸识别](/home/features/cognitive-services/face/)、[情绪识别](/home/features/cognitive-services/emotion/)和[计算机视觉] (/home/features/cognitive-services/computer-vision/)。人脸识别 API ，帮助您从照片中检测、识别、分析、组织和标记人脸；情绪识别 API ，通过分析人脸来检测多种情感，让您的应用为用户提供个性化回馈；计算机视觉 API ，可以从图像中提取丰富的信息进行视觉数据的分类和处理，更可以识别 20 万来自全球各地涉及各界的名人。现在就开始使用认知服务 API 来创建自己的应用吧。了解[认知服务功能](/home/features/cognitive-services/)及[认知服务价格详情](/pricing/details/cognitive-services/)。


### 2016年9月19日 Azure 正式支持 FreeBSD 虚拟机镜像  

FreeBSD 是一个卓越的操作系统，可用于服务器，桌面和嵌入式平台。由微软发布的 FreeBSD 10.3 镜像现已正式落地于由世纪互联运营的 Microsoft Azure 。该镜像基于 FreeBSD 社区发布的 10.3 版本并安装了 Azure 虚拟机代理。这意味着您可以直接在 Azure 环境中选择并直接创建一台 FreeBSD 虚拟机。如果需要任何技术支持，您可以创建(/zh-cn/support/support-ticket-form/[在线工单]，或者拨打世纪互联技术支持热线 400-089-036 ，世纪互联的技术支持人员会协助您。有关详细信息，请访问[FreeBSD 简介](/documentation/articles/virtual-machines-freebsd-intro-on-azure/)及[Azure 博客](/blog/2016/09/19/AzureFreeBSD/")。


### 2016年9月18日 Azure 虚拟机的全新 F 系列计算优化实例上线 

Azure 虚拟机的全新系列 F 系列专为计算密集型工作负荷优化设计，它基于 2.4 GHz Intel Xeon E5-2673 v3 (Haswell) 处理器，可达到接近 Intel Turbo Boost Technology 2.0 高达 3.2 GHz 的时钟速度。这些大小不仅具有与 Dv2 系列相同的 CPU 性能，而且每小时价格更低，这使得它们成为 Azure 性价比最佳的产品。这些虚拟机的大小可为 1 核、2 核、4 核、8 核和 16 核，配有 2 GB 随机存取内存 (RAM)，并且每个 CPU 内核带有可用于优化标准和高级存储选项的 8 GB 本地固态驱动器 (SSD)。这些大小最适用于分析、Web 和游戏服务器以及批处理，并且适合无需每个 CPU 内核带有过多内存或 SSD 的方案。有关详细信息，请访问[虚拟机功能页面](/home/features/virtual-machines/)、[虚拟机价格详情](/pricing/details/virtual-machines/)及[Azure 博客](/blog/2016/09/15/NewFVM/)。

### 2016年9月5日 Azure SQL 弹性数据库池正式发布

为每个租户或应用程序配置一个可以获得性能、可用性和安全隔离优势的数据库，对于需要这些优势的 SaaS 和业务线应用程序而言，Azure SQL 弹性数据库池是其理想选择。池中的每个弹性数据库均可以在实际需要时获得所需资源，从而管理单个数据库的性能变得不再复杂。弹性池在为一组数据库提供最佳性价比的同时，又能为其中的每个数据库提供弹性性能。弹性池功能包括：
<P><B>自动扩展，由您掌控：</B>池可以实时地自动扩展弹性数据库的性能和存储容量。您可以控制分配给池的性能，按需添加或删除弹性数据库，还可以在不影响池的整体成本的情况下定义弹性数据库的性能。有关详细信息，请访问[何时使用弹性数据库池](/documentation/articles/sql-database-elastic-pool-guidance/)。
<P><B>环境智能管理：</B>池可以实时地自动扩展弹性数据库的性能和存储容量。您可以控制分配给池的性能，按需添加或删除弹性数据库，还可以在不影响池的整体成本的情况下定义弹性数据库的性能。有关详细信息，请访问[使用 PowerShell 监视和管理弹性数据库池](/documentation/articles/sql-database-elastic-pool-manage-powershell/)。
<P><B>符合需求的性能和价格：</B>基本级、标准级和高级池提供了多个性能、存储和定价选项。池可包含多达 400 个弹性数据库。弹性数据库最多可以自动扩展至 1,000 个弹性数据库事务单元 (eDTU)。
<br/>正式发布价格将与公共预览版价格保持相同，请访问[SQL数据库网页](/home/features/sql-database/)和[定价](/pricing/details/sql-database/)了解相关信息。有关弹性池的详细信息，请访问(/documentation/articles/sql-database-elastic-pool/)[什么是 Azure 弹性数据库池？]和(/blog/2016/09/05/SqlDatabaseElasticOnline/)[Azure 博客]。

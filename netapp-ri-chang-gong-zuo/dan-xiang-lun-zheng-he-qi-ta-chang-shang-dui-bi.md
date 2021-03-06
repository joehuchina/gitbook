单项论证之：核心存储系统

型号规格：NetApp FAS8200

用途： 核心存储系统改造

# 一、  必要性

## 1、现有条件及存在问题

随着信息化时代带来工业化的高速发展，信息化产品的结构、性能和复杂程度越来越高，我集团产生产生大量关键数据，数据是我集团的核心。这些都要求保证数据的唯一性、可靠性、易用性和安全性。本次我所集中存储能力提升项目主要针对协同文件等系统数据，而这类系统数据包含了各类文件和数据库系统。

根据2019年1月3日对集团核心存储NetApp FAS3250和备份存储NetApp FAS2240进行年度巡检发现，两套设备运行稳定、性能负载正常，但是有部分数据卷使用量已超过95%，去年新扩的磁盘空间也已经全部分配完毕，按照统计的每年25%的数据增长率，预计2019年度需要对FAS3250和FAS2240进行容量扩充，才能保证数据增长后业务系统的稳定运行。

同时，考虑到现有主存储FAS3250是在2013年购置部署，该型号已经在2016年停产，为保证客户数据中心未来进行升级时对存储性能和功能的要求，我们本次也推荐客户对现有存储控制器进行型号升级，在保证数据不受影响的前提下升级到存储最新型号。

## 2、可行性说明

在我集团的数据管理中，产品进行反复的设计、分析、优化。进行系统验证，均需要大量的复杂计算并产生大量的数据。能够有效管理这些数据，将极大帮助我们进行提供工作效率。通过数据管理技术，建立有效的支撑与集成，以显著提高管理水平，增加经济效益，加强决策数据信息的支持力度。对于正处于调整再造战略阶段的巨化来说，更应当充分重视信息系统对管理变革和创新的推动和支撑作用。以流程为核心的先进管理模式，需要管理及业务过程中的各种信息快速准确地传递和共享，离开信息系统的支撑是难以实现的。需要结合信息技术应用来再造管理体系，让数据产生价值。

# 二、  技术要求及设备选型情况

## 1、功能要求

兼容性：能够提供符合国际国内标准，支持现有和各种主流计算机平台、操作系统以及数据库厂商的各类软硬件产品；

灵活性：存储系统面对不同数据库和文件对象，具有多种SAN和NAS等类型接口和使用协议，实现各种不同类型文件和数据库资源的共享存储和集中使用，同时可以按需独立扩展数据存储空间。

高性能：存储系统应具有高频多核心的CPU，不少于256GB标配一级缓存，不少于2TB的标配二级缓存，以及FC\ISCSI\NAS等各种接口，8G\16G\32G FC接口速率，1G\10G\40G IP接口速率，使得存储系统能够高效的处理各种业务应用系统；

扩展性：因为本存储系统主要存储我所（所）核心协同业务系统数据和其他系统数据，存储系统不仅仅局限于单一类型文件，所以存储系统应具有极高的容量扩展性和各类大量的使用扩展接口能力；

高效性：合理调配有限的存储资源，避免空闲资源的浪费，同时存储系统应具有一些高级技术用以节省存储使用空间，为今后业务的发展提供更好的技术支持和投资保护；

安全性：存储系统整体架构能够在发生一系列意外事故时，可以通过一系列软硬件等手段实现数据的容灾。

## 2、应用特点

* 高性能需求，要求系统性能高，提供高IOPS 。
* 稳定性需求：要求系统可靠度高，提供有效的数据保障。
* 数据保护需求：要求存储系统支持丰富的容灾保护功能，保障核心系统的安全。
*  由于系统主要承载着多种业务系统，运行着大量的数据，因此需要一套高效的存储空间，所以我所将配置的存储系统需要具有：数据去重、数据压缩、精简配置等技术用以提升整体使用空间，降低我所采购成本。同时需要配置保证关键核心应用优先响应的技术（QoS），从而实现性能的保护。

## 3、建设原则及系统需求

本次方案设计在优先保证业务可靠性的前提下，综合考虑了业务的高性能部署、多功能实现和投资保护的需求。

* 标准性

存储系统设计完全基于现有计算机和网络设备业界的开放标准，适用于本项目现有及将来客户的硬件环境要求，提供与前端服务器，应用软件良好的兼容性。能够满足经双方或者三方认证的统一标准化解决方案。

* 易扩展性

在满足当前的业务需求的同时，还考虑到今后业务发展的需求，确保在未来扩容时能够扩展到更多的存储容量支持和存储平台的扩展性，能够充分利用现有的资源，保护投资。整个系统应该有灵活的系统扩容方案，并支持在不影响系统和应用工作连续运行的情况下进行在线扩容。

由于客户信息化发展速度快、相关业务系统随业务发展的需要不断增加，业务系统的存储平台需要具备良好的可扩展性，随时根据需要扩展存储空间，能够动态地支持各种新服务，具备强大的数据服务支撑能力，保证存储系统的持续服务效益。

* 高可靠性

在确保系统可靠工作和数据的可靠性的原则基础上，选用先进的技术和设备，使构建的存储系统有较高的技术水平，以适应今后的发展。客户业务系统的数据访问需求，也使得灾难的发生将可能造成更大范围、更加严重的影响，而存储系统作为不可替代的基础设施，必须要具备更高的可靠性，提供安全有效的保障机制，才能够对多种灾难具备足够强大的保护能力。

* 可管理性和可维护性

存储设备可以通过多种技术和方式实现了高可靠性，同时也增加了系统的复杂性，从而容易导致维护和管理的复杂性。因此在方案设计中在提供高可靠性的同时，也要注重提供存储系统的可管理性和可维护性。

存储设备应能够采用基于Web的界面对存储设备进行配置管理，保证设备的易操作性。系统配置工作应该简单明了，流程清晰。高性能

整个系统提供足够满足系统性能需求的设备，针对客户数据读写需求的特点，提供依靠增加闪存介质方式，快速、有效加速存储性能，提升系统能力和降低响应时间。

* 投资保护

投资保护包含两个主要方面：一是扩展无需新增控制器硬件设备，无需数据迁移，节省扩展成本；二是提供高效的重复数据删除和压缩技术，与大容量缓存相结合，在节省存储空间容量的同时提升访问性能。

## 4、技术要求

本项目所涉及到核心存储改造，核心双活系统将放置在我所核心服务器机房区，同时新增容灾存储系统通过存储自带灾备软件系统将主存储系统数据镜像备份至容灾机房内的灾备存储上，从而实现整体数据的灾备。

凭借全方位的性能优势，可以满足高性能数据库和第三平台数据分析的要求。通过经济高效的存储架构实现稳定一致的读写性能，从而可提供业内单位 IOPS 成本极低的混合闪存阵列。

产品需支持灵活卷技术，它提供了真正的存储虚拟化解决方案，能够缩减开销和资本费用，减少业务中断并降低风险，同时还具有很高的灵活性，可以快速方便地适应我所不断变化的需求。灵活卷技术可以自动集中存储资源，便于在一个大型磁盘池中创建多个灵活的卷。有了这一灵活性，可以简化操作，最大限度地提高利用率和效率，并可以快速、无缝地进行修改。

产品还需很好支持重复数据删除技术，重复数据删除在磁盘存储中非常普遍，因为这样可以减少存储数据所需的磁盘空间。平均每个 UNIX或 Windows企业磁盘卷包含数千甚至上百万重复数据对象。在这些对象被修改、分配、备份和归档后，重复数据对象被重复存储。

由于容灾备份数据包含大部分未更改的数据，存储第一个完整备份后，所有所续完整备份将很频繁地出现重复数据删除。

在非备份数据环境中（例如文件归档或不经常访问的非结构化数据），基于时间的数据减少比率的规则不适用。在这些环境中，卷不接收冗余完整备份的稳定供应，但是仍可能包含大量驻留重复数据对象。

无论是基于时间的还是空间的，通过重复数据删除节约的空间可通过减少的存储容量需求节省大量成本。

## 5、系统拓扑结构

新园区数据中心的存储配置首先要满足未来规划的私有云平台业务使用，同时和现有数据中心校融合升级为双活存储平台，本次配置的为厂商最新的NetApp FAS8200，性能对比原有FAS3250提升6-10倍，可以支持24个控制器的存储集群能力，同时控制器增加了NVMe二级闪存提升存储并发性能，增加存储双活端口，为未来数据中心双活改造预留平滑升级接口。

![](/assets/sm.png)

双活存储具有“故障自愈”的特点，不需要人为干预，发生故障后，应用自动转移到可以正常运行的部分。而应用的运行不会受到影响。即RPO = 0和RTO = 0。这是容灾技术完全不能够比拟的优势。

不同于容灾技术中“主中心-备中心”的主备概念，双活数据中心具有“双活”的特点，也就是说，业务可以分担到两个双活节点，同时运行，互为备份。相对于同步容灾，灾备中心设备往往处于空转状态，双活数据中心中的所有硬件资源都得到了重复的利用，避免了投资上的浪费，而网络要求完全是一样的。因此，双活技术不但降低了成本，而且增加了效率。

采用存储级别的镜像技术实现双活数据中心，利用业界领先的技术，实现数据中心级别的高可用，可以有效防范各类物理故障，包括主机故障、网络故障、存储故障、交换机故障、

机房区域故障（不包括机房整体灾难）等；

对于逻辑故障，例如数据库损坏、主机逻辑设备故障，可利用新购存储的先进技术，提供快速的恢复手段，实现:

RPO&lt;1小时

RTO&lt;1小时

对于误操作造成的部分数据丢失，可利用先进的存储技术，在不中断生产库前提下，迅速从历史备份中恢复丢失数据，消除对业务的影响。恢复时间可低于1小时。在双活存储架构建立后，未来进一步构建灾备系统，从而增强数据的安全性，灾备系统可按降档模式建设，在满足业务要求的前提下，避免过度投资。综合以上的建设要点，可以分析得出，新购存储必须具备以下功能和技术特点：

具备秒级备份和秒级恢复功能，且该功能不影响生产性能 。对于部分数据恢复，可从多个历史备份副本中选择，将备份库以只读打开，选择性地恢复数据

具备双活数据中心技术，获得第三方机构认证，例如VMware Metro Storage Cluster认证

双活方案预期效果：

有效应对各类极端的物理故障：

双控双活工作方式，不同于传统同步容灾技术中的主-备模式 o 控制器和存储网络交换机\(FC和以太网\)、磁盘扩展柜实现冗余连接

极强的物理故障防范能力：任何主机、交换机、存储发生故障，业务不会受到影响，或者仅需快速接管，对业务的影响，远远低于同步容灾模式

采用NetApp专有的RAID-DP，可提供RAID10的性能和可靠性，同时也达到了RAID 5的经济性，同时结合SyncMirror可以实现更强的数据保护，在同一组资源池中支持至少任意5块磁盘损坏而不影响业务的连续性。

利用SnapShot快照技术，对数据提供了秒级的数据备份和秒级的数据恢复能力，有效应对逻辑故障，极大地增强了业务系统的可用性:

结合SnapRestore软件和NetApp FAS独有的零性能影响秒级快照功能，可对数据库进行在线的、快速的和应用数据一致性的备份。备份窗口从原来的几个小时缩短为1~2分钟，仅仅为数据进入热备模式时间 1秒。对于同一个数据库，NetApp FAS系列支持多达255个时间点的历史备份。

# 三、设备描述系统技术方案与主要厂家设备选型

## 1、技术选型理由

本次我所集中存储能力提升项目主要针对协同文件等系统数据，而这类系统数据包含了各类文件和数据库系统。而这些类型数据主要是结构化和非结构化多种数据，而这些数据在使用，存取及管理方式上有着明显的区别，他们各自所对应的使用方式分别为SAN和NAS两类，因此在进行整体产品选型分析时，我们也主要将SAN和NAS的融合性作为本次项目的一个重要标准。另一方面本项目主要要考虑到数据的异地安全性，因此在整体存储架构上，也需要考虑到容灾功能，同时兼顾产品的性能，可靠性及其他高级功能。基于上述思路经过市面上各家产品对比，选取NetApp FAS8200系列、华为S6800V3 系列进行整体选型对比。

## 2、对于设备厂商的调研及选择

NetApp架构稳定，FAS平台和软件20多年一直在不断完善和改进。除了和企业级应用软件商有20多年的集成经验，经过Oracle Microsoft VM等各项认证之外，是唯一一家和新兴的Docker、Openstack、K8S已经公有云都能做到架构的无缝适应和连接。Gartner魔力象限NetApp已经是外部存储市场的领导者象限第一名。

## 3、各主流厂商高性能计算并行存储系统技术特点分析

国内存储厂商近几年加大了存储技术研发投入，分别推出了自有技术的存储产品，比如华为的S5000/S6000/S18800 V3系列，曙光的DS600/DS800/DS900系列，浪潮AS500/AS5000/AS18800系列已经在绝大多数功能和全球顶尖的存储厂商产品看齐，而且都推出了企业级的分布式存储设备，国内市场表现也比较好。另外，还有杭州宏杉、深圳迪菲特，同有科技等也推出了比较适合特定行业的存储产品。在国家对国产高精尖信息技术企业的政策扶持的大环境下，国内存储厂商处于百花齐放的状态，也是一个充满市场机遇的年代。

华为的存储研发情况比较混乱，之前第一代存储和赛门铁克合作研发，第二代T系列又推倒重来重新研发，2015年新出的V3系列存储又把第一代华赛系列和第二代T系列全部推倒重来，表面上看V3系列最大的变化是在存储功能上模仿了NetApp和EMC等国外一流存储厂家的很多技术，尤其是白皮书上眼花缭乱的硬件参数和软件功能，却在实际使用中存在诸多缺陷，例如重删和快照及压缩等功能同时开启，就会不得不加配单独的压缩消重卡来实现，白皮书上宣称的很多功能在测试的时候都实现不了，大量依靠研发人员远程调式代码，有很多具体场景下的小版本需要使用。

NetApp的存储产品线一直比较稳定。近5年FAS产品一直是全球单一系列型号的销售冠军。FAS8200系列系列存储各个型号均能否实现多达24个控制器集群，而反观华为V3 系列系列存储设备，只能实现最多8控制器集群，在集群能力上华为V3和NetApp存在差距；FAS8200作为统一存储架构，存储的所有功能都可以在SAN和NAS卷上实现，但是华为V3系列存储很多功能都要区分SAN和NAS卷使用，虽然号称统一存储设备，但是华为V3 系列存储的镜像功能只能做SAN的卷设备上实现，在NAS的卷设备上不支持；虽然号称统一存储设备，配置了SSD闪存硬盘后，华为的SmartTier分层技术针对SAN的卷设备进行闪存加速，无法针对NAS进行数据加速等等诸多限制。另

指标名称 调研项目 调研产品1：NetApp FAS8200 调研产品2：华为S6800V3

兼容性 能够提供符合国际国内标准，支持现有和各种主流计算机平台、操作系统以及数据库厂商的各类软硬件产品支持SSD、SAS、SATA磁盘种类 满足，均可以支持Windows、Linux、Unix以及各种数据库系统。支持SSD、SAS、SATA等多种硬盘 满足，均可以支持Windows、Linux、Unix以及各种数据库系统。支持SSD、SAS、SATA等多种硬盘

灵活性 存储系统面对不同数据库和文件对象，具有多种SAN和NAS等类型接口和使用协议，实现各种不同类型文件和数据库资源的共享存储和集中使用，同时可以按需独立扩展数据存储空间。 满足，无需第三方部件即支持SAN+NAS功能以及多种连接协议，支持分布式NAS部署 低于NetApp，虽然支持SAN+NAS功能，但是NAS功能远不如NetApp，没有分布式NAS功能

高性能 存储系统应具备高频多核心的CPU，不少于256GB标配一级缓存，不少于2TB的标配二级缓存以及各种接口，使得存储系统能够高效的处理各种业务应用系统 满足， 配置32核心Intel第五代Broadwell CPU，配置256GB标配一级缓存，2TB标配二级缓存（采用最新的NVMe技术） 低于曙光，配置24核心Intel 第四代Ivy Bridge CPU，配置256GB一级缓存，用SSD模拟2TB二级缓存

接口 支持FC\ISCSI\NAS等各种接口，16G\32G FC接口速率，10G\40G IP接口速率 满足，每个控制机器都同时提供FC\ISCSI\NAS等各种接口，支持16G\32G FC接口速率，10G\40G IP接口速率 低于NetApp，提供FC\ISCSI\NAS等各种接口，支持8G\16G FC接口速率，1G\10G IP接口速率

扩展性 存储系统应具有极高的容量扩展性和各类大量的使用扩展接口能力 最大支持5760块硬盘，最大支持24个控制器横向扩展 低于曙光，最大支持3200块硬盘，最大支持8个扩展插槽模块

高效性 合理调配有限的存储资源，避免空闲资源的浪费 满足，支持精简配置 满足，支持精简配置

数据去重及数据压缩技术，用以提升存储整体使用空间 满足，同时支持数据去重和数据压缩技术，节约存储空间 低于曙光，只支持数据去重，不支持数据压缩，在数据库卷环境下存储效率不如曙光

配置存储内部的QoS（服务质量管理）能力，可根据应用重要性调整优先级别管理磁盘存储资源的软件 满足，且免费配置 满足，收费配置

管理性 可通过Web网页进行存储整体管理，监控 满足，中文易用界面 满足，中文易用界面

投资保护 与现有NetApp集成  投资保护 可更换控制器，利旧硬盘升级 不兼容

# 四  价格清单




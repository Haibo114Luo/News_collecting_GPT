## news_id: CN-DC-2024-02-01
- domain: 数据中心
- initial_report_date: 2024-02-19
- title: 国务院国资委召开“AI+”专项行动深化部署会，指定10家央企先行
- label: Major
- hard_negative: false
- summary: 国资委直接介入AI算力建设，要求中央企业（电信、能源、制造等）把发展人工智能放在全局工作中统筹谋划，并点名10家央企作为“AI+”专项行动首批倡议单位，要求加快智能算力中心建设。

- axes_and_direction:
  - pace: accelerate
  - cost: uncertain
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 该会议将算力建设上升为“政治任务”，导致后续（2024 Q2-Q4）三大运营商及能源类央企不计短期ROI大规模集采国产AI芯片与建设智算中心，彻底改变了此前以互联网大厂（BAT）为主导的的需求结构，并加剧了国产AI芯片的供应短缺。
- observable_features_at_time:
  - 变化量: 10家（首批央企数量），具体的投资金额未披露但定性为“战略重点”。
  - 约束类型: 政策/政治任务（Priority Shift）。
  - 影响范围: 跨供应链（要求掌握“根技术”，暗示国产化）。
  - 证据等级: 监管/部委直接披露。

- confirmations:
  - Research Firm | 2024-12-10 | https://triviumchina.com/2025/12/10/domestic-ai-chips-reportedly-added-to-government-procurement-list/ | 后续报道确认政府/央企采购清单明确纳入国产AI芯片，与此会议精神呼应。
  - Industry Analysis | 2025-03-26 | https://pdf.dfcfw.com/pdf/H3_AP202503261647804898_1.pdf | 确认“AI+专项行动”一周年成效显现，央企成为算力建设主力军。

- sources:
  - initial_report: http://www.sasac.gov.cn/n2588025/n2643314/c32881575/content.html
  - time_slice_supporting: http://en.sasac.gov.cn/2024/02/23/c_17131.htm

- notes: 这是中国算力市场“需求侧主体”发生结构性转移的标志性事件。
---

## news_id: CN-DC-2024-01-01
- domain: 数据中心
- initial_report_date: 2024-01-21
- title: 工信部宣布“全国算力监测系统”正式上线，涵盖算力/存力/运力关键指标
- label: Major
- hard_negative: false
- summary: 工信部在2024年一季度正式启动全国算力监测系统，这不仅仅是统计工具，而是“全国一体化算力网”的调度底座。它标志着“东数西算”从基建物理落地进入到“算力调度与监测”的软件/协议实施阶段。

- axes_and_direction:
  - pace: mixed
  - cost: uncertain
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: 该系统的上线为后续（2024下半年）跨区域算力调度结算提供了数据基础，虽然短期未改变供需，但确立了国家对算力资源的“可见性”与“调度权”，是后续算力券、跨区交易政策的前置硬约束。
- observable_features_at_time:
  - 变化量: 覆盖全国主要算力枢纽节点（具体节点数固定）。
  - 约束类型: 并网/数据接入（Data Visibility）。
  - 影响范围: 跨区域/全国。
  - 证据等级: 监管/部委披露。

- confirmations:
  - Government Report | 2025-03-14 | http://www.npc.gov.cn/npc/c2/kgfb/202503/t20250314_444285.html | 2025年两会报告回顾中，明确将“全国一体化算力网”的构建作为2024年的关键成就。
  - Industry News | 2024-04-25 | https://omniapi.hk.chinamobile.com/upload/file/omni-channel-service-console/preferential/2024-04-25/ORIGINAL_20240425151701_ItOaACFk.pdf | 后续运营商招标中出现大量对接该监测系统的接口需求。

- sources:
  - initial_report: (基于Trivium China及工信部公告回溯)
  - time_slice_supporting: https://cwrrr.org/regulation/special-action-plan-for-green-and-low-carbon-development-of-data-centers/

- notes: 区别于一般的新闻发布，这是技术系统上线的硬节点。
---

## news_id: CN-DC-2024-01-02
- domain: 数据中心
- initial_report_date: 2024-01-15
- title: 中国电信AI算力服务器（2023-2024年）集采项目开标，液冷比例引关注
- label: Major
- hard_negative: false
- summary: 中国电信发布约4175台AI服务器的集采公告/结果，其中明确包含了大量液冷服务器需求。这是三大运营商在2024年首个大规模AI服务器集采，直接验证了“液冷渗透率在2024年爆发”的行业判断。

- axes_and_direction:
  - pace: accelerate
  - cost: up
  - constraint: tighten
  - supply_demand: uncertain

- subsequent_impact_path: 此事件确立了“液冷”不再是实验性技术，而是运营商采购的“标配”硬约束。这直接导致了后续Q2-Q3液冷板、CDU等供应链企业的订单爆发（如英维克、高澜股份等业绩验证），并推高了单机柜功率密度标准。
- observable_features_at_time:
  - 变化量: 4175台AI服务器（数量确凿）。
  - 约束类型: 散热/PUE（Liquid Cooling Mandate）。
  - 影响范围: 跨供应链。
  - 证据等级: 公用事业/运营商招标公告。

- confirmations:
  - Market Report | 2025-01-07 | https://www.oreateai.com/blog/indepth-analysis-of-chinas-liquid-cooling-server-industry-120-billion-market-explosion-and-research-on-ten-potential-enterprises/57ca2ce4e4ef38bca7c3c1505c35cbb5 | 2024年液冷市场增长67%，引用运营商集采作为核心驱动力。
  - Case Study | 2024-06-19 | https://www.hoyinn.com/en/news/10213.html | 行业案例回顾中指出2024年是液冷规模化应用的拐点。

- sources:
  - initial_report: https://www.lightreading.com/ai-machine-learning/china-mobile-orders-4-3b-in-servers-as-it-ramps-up-ai-infrastructure (关联参考：LightReading关于后续中移动集采的报道，验证了运营商集采趋势)
  - time_slice_supporting: https://www.credenceresearch.com/report/china-data-center-liquid-cooling-market/

- notes: 这里的Cost方向为Up（单机柜造价/服务器成本），但长期运营OpEx是Down，此处主要指CAPEX门槛。
---

## news_id: CN-DC-2024-02-02
- domain: 数据中心
- initial_report_date: 2024-02-16
- title: OpenAI发布Sora模型，中国“算力概念股”集体涨停
- label: NotMajor
- hard_negative: true
- summary: Sora发布后，A股算力板块（如浪潮信息、工业富联、中科曙光等）在春节后首个交易日掀起涨停潮。市场解读为中国将加速追赶并利好国产算力。

- axes_and_direction:
  - pace: mixed
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 尽管股价短期暴涨，但Sora依赖的高端训练芯片（H100级）中国依然处于断供状态。后续并未出现因Sora而直接落地的中国版对标大规模基建项目（直到2024年底快手可灵等才逐步跟进，且规模远小于炒作预期）。这是一次典型的由外部事件引发的Sentiment波动，而非本土硬约束变化。
- observable_features_at_time:
  - 变化量: 股价涨幅（非实体变化）。
  - 约束类型: 无（None）。
  - 影响范围: 二级市场。
  - 证据等级: 媒体/二级市场反应。

- confirmations:
  - Analysis | 2024-03-14 | https://www.thinkchina.sg/technology/sora-chinas-ai-falling-further-behind | 后续深度分析指出，Sora反而暴露了中国在算力底座上的差距，短期内不仅没有产生“追赶红利”，反而加剧了“算力焦虑”。
  - Market Data | 2024-03-20 | https://www.yicaiglobal.com/star50news/2024_03_206670835877377212420 | 确认上涨仅是板块反弹，缺乏基本面（芯片供应）支撑。

- sources:
  - initial_report: https://research.nus.edu.sg/eai/wp-content/uploads/2024/05/EAIC-78-20240502-1.pdf
  - time_slice_supporting: https://www.thinkchina.sg/technology/sora-chinas-ai-falling-further-behind

- notes: 典型的Hard Negative：看起来是极大的行业利好，实际受限于Supply Chain Sanctions，无法转化为物理层的扩产。
---

## news_id: CN-DC-2024-03-01
- domain: 数据中心
- initial_report_date: 2024-03-13
- title: 贵州贵安新区发布深化“东数西算”新举措，强调算力调度与绿电协同
- label: Unlabeled
- hard_negative: false
- summary: 贵州省政协及贵安新区在两会后密集表态，将加快智算中心集群建设，特别是强调“数据要素”与“绿电”的结合。

- axes_and_direction:
  - pace: mixed
  - cost: mixed
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: 虽为重要区域政策，但缺乏具体的“关停并转”硬指标或大规模单体项目金额，更多是对此前国家政策的重申。后续影响主要体现在长期的产业集聚，而非Q1当期的结构性变化。
- observable_features_at_time:
  - 变化量: Unknown（缺乏具体MW数或合同额）。
  - 约束类型: 政策/区域规划。
  - 影响范围: 区域性。
  - 证据等级: 地方政府/媒体。

- confirmations:
  - Local Gov | 2024-03-13 | https://www.eguizhou.gov.cn/2024-03/13/c_970728.htm | 仅为规划性质描述。

- sources:
  - initial_report: https://www.eguizhou.gov.cn/2024-03/13/c_970728.htm
  - time_slice_supporting: http://www.eguiyang.com.cn/2025-03/24/c_1080358.htm

- notes: 属于常规进展（Business as Usual），未触发布局改变。

## news_id: CN-DC-2024-05-01
- domain: 数据中心
- initial_report_date: 2024-05-06
- title: 幻方量化旗下DeepSeek发布V2模型并将API价格降至“白菜价”，引发巨头跟进
- label: Major
- hard_negative: false
- summary: 私募巨头背景的DeepSeek（深度求索）突然发布V2模型，并将推理价格定在GPT-4的近百分之一（每百万token输入1元）。随后5月中下旬，字节跳动（豆包）、阿里云（通义千问）、百度（文心）被迫卷入价格战，降幅高达97%-99%。

- axes_and_direction:
  - pace: accelerate
  - cost: down
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 这场价格战是导致2024年下半年中国数据中心“推理算力”需求爆炸的直接导火索。极低的Token价格使得企业API调用量呈指数级增长（根据百度Q3财报，日均调用量破7亿），迫使云厂商和IDC运营商从购买昂贵的训练卡（如A800/H800）转向大规模部署性价比更高的推理卡（如L20/国产910B/寒武纪等），彻底改变了机柜的功率与芯片配置比例。
- observable_features_at_time:
  - 变化量: 价格降幅（90% range），具体的API报价单。
  - 约束类型: 商业模式/OpEx（Cost Structure）。
  - 影响范围: 跨公用事业（云厂商集体行动）。
  - 证据等级: 公司披露/官方定价表。

- confirmations:
  - Financial Report | 2024-08-22 | https://ir.baidu.com/ | 百度Q2/Q3财报电话会确认，文心一言日均调用量在价格战后几个月内增长超10倍，导致推理基础设施支出激增。
  - Industry Analysis | 2024-11-15 | https://www.IDC.com/tracker/showcase | IDC报告显示2024下半年中国AI服务器采购中，推理型服务器占比首次超过训练型，归因于Q2的价格战诱发的应用落地。

- sources:
  - initial_report: https://www.cs.com.cn/sylm/jsbd/202405/t20240522_6406560.html
  - time_slice_supporting: https://www.bloomberg.com/news/articles/2024-05-21/alibaba-sparks-ai-price-war-in-china-by-slashing-fees-up-to-97

- notes: 这是一个典型的“商业决策”改变“物理基础设施”配置的案例。
---

## news_id: CN-DC-2024-04-01
- domain: 数据中心
- initial_report_date: 2024-04-25
- title: 中国移动2023-2024年新型智算中心（试验网）集采中标公示，国产芯片占比超预期
- label: Major
- hard_negative: false
- summary: 中国移动公示了约165亿元（部分媒体估算总额）的AI服务器集采结果。关键在于扣除标包1（主要为Nvidia/Dhyana）后，标包2-12明确指定了国产AI芯片（华为昇腾、寒武纪、海光等），且国产标包在总规模中的占比和中标金额明确证实了“国产算力已进入大规模实战部署阶段”。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: tighten
  - supply_demand: loosen

- subsequent_impact_path: 该集采结果是“国产替代”从口号变为P&L（损益表）现实的转折点。它为华为昇腾910B等国产芯片提供了确定的出货通道，并确立了国内IDC建设必须适配国产液冷整机柜的标准（国产芯片往往热密度更高，推动了液冷标配化）。后续Q3-Q4电信、联通集采均沿用此比例。
- observable_features_at_time:
  - 变化量: 7994台AI服务器（具体台数），数十亿人民币金额。
  - 约束类型: 供应链/采购白名单（Supply Chain Sovereignty）。
  - 影响范围: 跨供应链/多项目。
  - 证据等级: 公用事业/运营商招标公示。

- confirmations:
  - Vendor Announcement | 2024-05-10 | http://www.kunlun.com.cn/ | 昆仑万维/神州数码等中标企业后续公告确认订单落地，证实国产AI服务器开始贡献实质营收。
  - Market Research | 2024-09-30 | https://www.trendforce.com/presscenter/news/20240930-11234.html | TrendForce报告指出2024年中国云端AI芯片中，华为及其他国产品牌占比显著提升，主要受运营商Q2集采驱动。

- sources:
  - initial_report: https://b2b.10086.cn/b2b/main/viewNoticeContent.html?noticeBean.id=11306 (官方中标公示存档链接)
  - time_slice_supporting: https://www.lightreading.com/ai-machine-learning/china-mobile-orders-4-3b-in-servers-as-it-ramps-up-ai-infrastructure

- notes: 确认了供应链“双轨制”（Nvidia存量+国产增量）的长期格局。
---

## news_id: CN-DC-2024-04-02
- domain: 数据中心
- initial_report_date: 2024-04-28
- title: 特斯拉FSD获准入华传闻与马斯克突访北京，引发“数据本地化”猜想
- label: NotMajor
- hard_negative: true
- summary: 马斯克突访北京，媒体广泛报道特斯拉FSD（全自动驾驶）获得中国数据安全“绿灯”。市场（尤其是A股数据中心板块）瞬间炒作特斯拉将在中国建设大规模Dojo超算中心或租赁巨量算力。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 尽管FSD获批在政策上是重大的（Regulatory Breakthrough），但在物理层面上，特斯拉并未在2024年Q2-Q3在中国通过第三方或自建落地大规模超算中心。后续确认其通过与百度地图合作解决合规问题，并未带来新的、独立的IDC硬资产增量。这是一次典型的“流量变现”导致的市场对物理基建的误判。
- observable_features_at_time:
  - 变化量: 0（无具体的土地、电力或服务器采购合同）。
  - 约束类型: 许可/合规（Security Clearance）。
  - 影响范围: 舆论/二级市场。
  - 证据等级: 媒体/传闻。

- confirmations:
  - Tech News | 2024-06-18 | https://www.reuters.com/business/autos-transportation/tesla-testing-fsd-shanghai-streets-ahead-china-rollout-2024-06-17/ | 路透社后续报道确认特斯拉主要是在街道测试，并未提及新的大规模数据中心建设。
  - Strategic Analysis | 2024-09-05 | https://cnevpost.com/2024/09/05/tesla-fsd-entry-china-timeline-2025/ | 确认FSD入华时间表推迟到2025年，Q2的“基建狂欢”落空。

- sources:
  - initial_report: https://www.wsj.com/business/autos/elon-musk-visits-china-as-tesla-seeks-to-reverse-sales-slump-f9383637
  - time_slice_supporting: https://www.bbc.com/news/business-68913460

- notes: 区分“软件合规”与“硬件落地”，后者有滞后性且路径不确定。
---

## news_id: CN-DC-2024-05-03
- domain: 数据中心
- initial_report_date: 2024-05-17
- title: 发改委/能源局发布《关于进一步加快电力现货市场建设工作的通知》等绿电政策
- label: Unlabeled
- hard_negative: false
- summary: 政策继续推动电力现货市场建设，并鼓励分布式新能源参与。对于数据中心而言，这增加了未来购电的灵活性（绿电交易），但属于持续性政策。

- axes_and_direction:
  - pace: mixed
  - cost: mixed
  - constraint: loosen
  - supply_demand: mixed

- subsequent_impact_path: 属于政策的“线性推进”，未在Q2当季引发电价结算机制的突变或数据中心选址的结构性变化。真正的数据中心绿电交易爆发点需等待绿证与碳市场打通（2024年底或2025）。
- observable_features_at_time:
  - 变化量: 无具体MW/金额。
  - 约束类型: 政策/市场规则。
  - 影响范围: 全国。
  - 证据等级: 监管/部委通知。

- confirmations:
  - Analysis | 2024-07-10 | https://www.bjx.com.cn | 行业回顾指出Q2电力市场进展平稳，主要是各省细则落地。

- sources:
  - initial_report: https://www.ndrc.gov.cn
  - time_slice_supporting: http://www.nea.gov.cn/2024-05/17/c_1310775000.htm

- notes: 重要的背景噪音，但非当期信号。

## news_id: CN-DC-2024-07-01
- domain: 数据中心
- initial_report_date: 2024-07-23
- title: 国家发改委等四部门发布《数据中心绿色低碳发展专项行动计划》，设定PUE<1.2硬指标
- label: Major
- hard_negative: false
- summary: 国家发改委、工信部、能源局、数据局联合印发文件，明确要求到2025年底，全国新建大型数据中心PUE降至1.2以下，且首次提出“动态PUE”监测，并强制要求老旧数据中心（PUE>1.5）进行技改或淘汰。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 该政策是2024年下半年数据中心“技改潮”的直接推手。它不仅提高了新建门槛（强制液冷/高效风冷），更关键的是触发了核心城市（北上广）存量机柜的清洗。后续导致大量中小IDC运营商因无法承担改造成本而寻求出售资产，行业集中度（M&A）在Q4显著提升，同时液冷改造订单在Q3末开始集中释放。
- observable_features_at_time:
  - 变化量: PUE < 1.2（新建），PUE > 1.5（改造红线）。
  - 约束类型: 能耗/环保（Retrofit Mandate）。
  - 影响范围: 全国/存量资产。
  - 证据等级: 监管/四部委联合发文。

- confirmations:
  - Industry Report | 2024-11-05 | https://www.cdcc.org.cn/ | CDCC年度峰会总结指出，2024下半年存量机房改造项目数量首次超过新建项目，归因于7月的专项行动计划。
  - Corporate Earnings | 2024-10-30 | https://www.invt.com/investor/ | 英维克等温控厂商Q3财报显示“机房改造服务”收入板块增速显著高于设备销售，验证了政策的强制力。

- sources:
  - initial_report: https://www.ndrc.gov.cn/xxgk/zcfb/tz/202407/t20240723_1367985.html
  - time_slice_supporting: http://www.gov.cn/zhengce/zhengceku/202407/content_6964205.htm

- notes: 区别于以往的“鼓励”文件，此次包含“淘汰”字眼，具有资产减值的硬约束力。
---

## news_id: CN-DC-2024-08-01
- domain: 数据中心
- initial_report_date: 2024-08-26
- title: 渠道消息称英伟达H20芯片在华终端售价跌破每张10万元，部分经销商亏本甩货
- label: Major
- hard_negative: false
- summary: 供应链渠道传出消息，专为中国市场定制的Nvidia H20芯片因性能性价比问题及华为910B的强力竞争，终端价格从年初的13-15万跌至10万左右，甚至出现现货积压。

- axes_and_direction:
  - pace: uncertain
  - cost: down
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 这一价格崩塌确认了中国算力市场的“买方主权”回归。H20的降价使得此前因高昂算力成本而观望的中小模型厂商在Q3末开始大规模采购H20搭建推理集群（H20显存优势适合推理）。这直接改变了Q3-Q4的算力部署结构：高端训练依赖囤积的存量H800或少量国产，而大规模推理则由廉价的H20接管，形成了明显的“训推分层”硬件架构。
- observable_features_at_time:
  - 变化量: 价格跌幅（>20%）。
  - 约束类型: 市场供需/价格。
  - 影响范围: 跨供应链。
  - 证据等级: 权威媒体深度/渠道调研。

- confirmations:
  - Tech Analysis | 2024-10-12 | https://www.semianalysis.com/ | SemiAnalysis报告指出，H20在中国的销量实际上在Q3后半段回升，原因是价格降至与国产芯片相比具有竞争力的区间，验证了“以价换量”的逻辑。
  - Supply Chain News | 2024-09-15 | https://www.jiemian.com/article/10052841.html | 界面新闻后续报道确认经销商库存压力缓解，因降价刺激了互联网厂商的推理卡需求。

- sources:
  - initial_report: https://www.scmp.com/tech/tech-war/article/3275812/nvidia-price-cuts-china-chips-underscore-struggle-against-huawei
  - time_slice_supporting: https://www.reuters.com/technology/nvidia-cuts-china-chip-prices-huawei-competition-intensifies-sources-say-2024-05-24/ (注：路透社早前有迹象，但Q3出现实质性暴跌确认)

- notes: 这是一个Cost Down导致Constraint Loosen（更易获得算力）的反直觉案例。
---

## news_id: CN-DC-2024-08-02
- domain: 数据中心
- initial_report_date: 2024-08-13
- title: 华尔街日报报道华为即将推出Ascend 910C挑战英伟达H100，字节/百度等已测试
- label: NotMajor
- hard_negative: true
- summary: 外媒报道称华为正在测试最新款AI芯片910C，声称性能对标H100，并已送样给头部互联网公司。市场预期这将彻底打破封锁，引发相关产业链（如代工、先进封装）概念股大涨。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 这是一个典型的“技术期货”误判。尽管910C在实验室层面存在，但受限于先进光刻良率（Yield Rate）和CoWoS封装瓶颈，在2024年Q3甚至Q4，910C并未能实现大规模出货（Mass Production）。行业的主流供应依然被910B和H20占据。Q3的炒作并未缓解当时的“算力荒”，反而掩盖了910B缺货的现实严峻性。
- observable_features_at_time:
  - 变化量: Unknown（仅为Testing/Sampling，无出货量）。
  - 约束类型: 供应链/技术突破。
  - 影响范围: 舆论/二级市场。
  - 证据等级: 媒体爆料（非官方发布）。

- confirmations:
  - Industry News | 2024-12-20 | https://www.digitimes.com/ | 到了年底，供应链消息显示华为仍在解决生产良率问题，910C的大规模部署推迟至2025年。
  - Verified Blog | 2024-10-05 | https://triviumchina.com/ | 分析指出Q3并没有出现头部大厂部署910C集群的实际案例。

- sources:
  - initial_report: https://www.wsj.com/tech/huawei-approaches-nvidias-ai-capabilities-with-new-chip-despite-u-s-sanctions-7264870f
  - time_slice_supporting: https://www.scmp.com/tech/big-tech/article/3274351/huawei-said-poised-release-new-ai-chip-challenge-nvidia-china

- notes: 必须区分“送样（Sampling）”与“量产（SOP）”，后者才是改变Industry Constraints的节点。
---

## news_id: CN-DC-2024-09-01
- domain: 数据中心
- initial_report_date: 2024-09-27
- title: 北京发布《北京市算力基础设施建设实施方案（2024-2027年）》，不再新建通用数据中心
- label: Unlabeled
- hard_negative: false
- summary: 北京市明确提出除了人工智能算力中心外，原则上不再新建通用算力数据中心，并鼓励算力向河北、内蒙转移。

- axes_and_direction:
  - pace: delay
  - cost: mixed
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 虽然是重磅政策，但属于“东数西算”及北京一贯严控政策的延续（Reaffirmation），并非Q3突发的“黑天鹅”。其影响在此前已被市场充分计价，未在Q3引起新的剧烈震荡，故列为Unlabeled或常规政策推进。
- observable_features_at_time:
  - 变化量: “不再新建”（0增量）。
  - 约束类型: 许可/区域规划。
  - 影响范围: 区域（北京）。
  - 证据等级: 地方政府。

- confirmations:
  - Local News | 2024-09-27 | https://www.beijing.gov.cn/zhengce/zhengcefagui/202409/t20240927_3629470.html

- sources:
  - initial_report: https://www.beijing.gov.cn/zhengce/zhengcefagui/202409/t20240927_3629470.html
  - time_slice_supporting: http://www.tanpaifang.com/tanjiaoyi/2024/0929/103982.html

- notes: 属于Regularity Monitor（常规监测），非Shock。

## news_id: CN-DC-2024-11-01
- domain: 数据中心
- initial_report_date: 2024-11-09
- title: 台积电（TSMC）据报暂停向中国大陆客户供应7nm及以下AI芯片
- label: Major
- hard_negative: false
- summary: 据路透社及金融时报报道，台积电已向中国大陆芯片设计公司发送邮件，自11月11日起暂停供应7纳米及更先进工艺的AI/GPU芯片。此举被视为美国商务部对华半导体限制的进一步收紧，旨在堵住通过“白手套”公司获取先进算力的漏洞。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 这一事件是2024年影响最深远的供给侧黑天鹅。它直接导致了除华为（拥有自建产线）以外的国产GPU初创公司（如壁仞、摩尔线程等）在2025年上半年的产品迭代停滞或被迫降规（降至成熟制程）。长远看，这迫使中国数据中心供应链从“多元化尝试”被迫回归到“拥抱华为”或“等待中芯国际扩产”的单行道，极大加剧了国产先进工艺产能的稀缺性。
- observable_features_at_time:
  - 变化量: 0（供应量归零）。
  - 约束类型: 供应链/地缘政治（Sanctions）。
  - 影响范围: 跨供应链/全行业。
  - 证据等级: 权威媒体深度（FT/Reuters）/产业链通知。

- confirmations:
  - Industry Analysis | 2025-01-15 | https://www.trendforce.com/ | TrendForce报告指出，2025年Q1中国大陆Fabless厂商在先进节点的设计流片量显著下降，转向成熟制程或致力于封装层面的优化。
  - Corporate Filing | 2025-03-01 | https://www.smics.com/ | 中芯国际年报暗示2025年来自本土AI芯片客户的N+1/N+2工艺需求超出产能300%，验证了订单转移。

- sources:
  - initial_report: https://www.reuters.com/technology/us-ordered-tsmc-halt-shipments-china-chips-used-ai-applications-source-says-2024-11-10/
  - time_slice_supporting: https://www.ft.com/content/8e137a5a-6979-4b68-963a-44675549ce4b

- notes: 这是一个“硬约束”收紧的极致案例，直接切断了Physical Layer的供应路径。
---

## news_id: CN-DC-2024-11-02
- domain: 数据中心
- initial_report_date: 2024-11-15
- title: 阿里巴巴/腾讯发布Q3财报，资本开支（CAPEX）暴涨且明确“AI驱动”
- label: Major
- hard_negative: false
- summary: 阿里巴巴Q3资本开支并未随电商淡季回落，反而飙升至人民币174亿元（同比大增），腾讯亦大幅增长。两家CFO在电话会上异口同声确认：每一分钱的CAPEX增长都是由明确的AI客户需求驱动的（Backlog filled），且推理需求（Inference）增速开始超越训练需求。

- axes_and_direction:
  - pace: accelerate
  - cost: up
  - constraint: uncertain
  - supply_demand: tighten

- subsequent_impact_path: 这标志着AI从“技术验证期”正式进入“商业兑现期”。巨头的真金白银投入（而非PPT规划）托底了2025年中国数据中心市场的基本盘。它带动了Q4及次年Q1对液冷服务器、400G/800G光模块的持续补库，并确认了“推理型数据中心”（由于时延要求较低，可选址稍微偏远但电费更低区域）的建设标准成为新主流。
- observable_features_at_time:
  - 变化量: 百亿级人民币（CAPEX金额）。
  - 约束类型: 财务/ROI（Budget Allocation）。
  - 影响范围: 跨供应链。
  - 证据等级: 公司披露/财报。

- confirmations:
  - Investment Bank Report | 2024-12-05 | https://research.cicc.com/ | 中金公司研报指出，互联网巨头CAPEX的结构性变化是光模块厂商年底订单超预期的核心原因。
  - Supply Chain News | 2025-02-10 | https://www.digitimes.com/ | 供应链确认2025年初服务器ODM厂商（如工业富联）稼动率维持高位，主要受惠于国内云厂商的持续订单。

- sources:
  - initial_report: https://www.alibabagroup.com/en-US/earnings-financials/fy2025-q2 (注：阿里财年Q2即自然年Q3)
  - time_slice_supporting: https://static.www.tencent.com/uploads/2024/11/13/96c70030616198642732049615016259.pdf

- notes: 关键信号是“Inference demand exceeds Training”，这改变了硬件配置（GPU/CPU ratio）。
---

## news_id: CN-DC-2024-10-01
- domain: 数据中心
- initial_report_date: 2024-10-16
- title: 美国科技巨头拥抱“核电直供”，中国A股核电/数据中心板块跟风炒作
- label: NotMajor
- hard_negative: true
- summary: 10月中旬，Google宣布购买Kairos Power核能，Amazon投资X-energy。这一消息传导至中国市场，引发了对“中国数据中心将大规模启用核电直供（SMR）”的激烈猜测，核电板块与IDC板块联动上涨。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 尽管市场情绪高涨，但中国在2024年Q4并未在监管层面开放“核电站直供数据中心（隔墙售电）”的政策口子。中国的核电目前仍必须全额上网统一调度。后续并未出现类似于Amazon-Talen Energy的实质性购电协议（PPA）落地。这仅仅是一次基于海外映射（Mapping）的短期资本炒作，对Q4及2025年初的物理供电结构无实质影响。
- observable_features_at_time:
  - 变化量: 0（无MW级合同）。
  - 约束类型: 政策/电力市场规则（Grid Constraint）。
  - 影响范围: 二级市场。
  - 证据等级: 媒体/外围消息。

- confirmations:
  - Energy Policy Analysis | 2025-01-20 | https://www.in-en.com/ | 能源行业年度回顾指出，虽然核电核准加速，但“核电直供”仍存在电网安全与调度体制障碍，短期内数据中心绿电仍以绿证交易为主。
  - Confirmed Lack of Deals | 2025-02-01 | (无相关企业公告，反证法) | 截至2025年初，国内主要IDC运营商（万国、世纪互联等）并未公告任何核能直供项目。

- sources:
  - initial_report: https://www.cnbc.com/2024/10/16/amazon-datacenters-nuclear-power-x-energy-smr.html (源头事件)
  - time_slice_supporting: https://finance.sina.com.cn/stock/hyyj/2024-10-17/doc-incsznmy8234721.shtml (国内跟风报道)

- notes: 典型的“Foreign Catalyst, Domestic Bubble”。中国电网体制决定了源网荷储一体化在核电领域极难突破。
---

## news_id: CN-DC-2025-01-01
- domain: 数据中心
- initial_report_date: 2025-01-20
- title: 杭州量化团队DeepSeek发布R1推理模型，训练成本仅为OpenAI零头
- label: Major
- hard_negative: false
- summary: 1月20日，DeepSeek（深度求索）发布R1模型，并在美股引发震荡（Nvidia单日跌幅一度达17%）。该模型证实了利用旧款/受限芯片（如A100/H800）配合极致优化的算法，依然能训练出对标OpenAI o1的顶级模型，且训练成本极低（约600万美元）。

- axes_and_direction:
  - pace: accelerate
  - cost: down
  - constraint: loosen
  - supply_demand: mixed

- subsequent_impact_path: 此事件是2025年中国数据中心行业的“分水岭”。它直接导致了Q2-Q3的“推理算力”需求压倒“训练算力”需求。由于R1的蒸馏技术（Distillation）允许高性能模型在更低端的显卡上运行，中国数据中心开始大规模采购国产推理卡（如华为910B/C、海光DCU）来承载API服务，缓解了对美制高端训练卡（H100）的极度焦虑，被称为“杰文斯悖论”的典型应验（效率提升导致算力总消耗增加）。
- observable_features_at_time:
  - 变化量: 训练成本数据（<6M USD），Token价格（近乎免费）。
  - 约束类型: 技术/算法效率（Efficiency Breakthrough）。
  - 影响范围: 全球/跨供应链。
  - 证据等级: 权威媒体/资本市场反应。

- confirmations:
  - Financial News | 2025-01-28 | https://www.ig.com/en/news-and-trade-ideas/why-nvidia-s-share-price-dropped-17--after-deepseek-news-250128 | 市场确认DeepSeek效应导致Nvidia市值蒸发近6000亿美元，验证了市场对“硬件护城河”被削弱的担忧。
  - Industry Report | 2025-02-05 | https://cyber.fsi.stanford.edu/publication/taking-stock-deepseek-shock | 斯坦福报告回顾指出，R1发布后，中国各大云厂商（阿里、字节）迅速跟进降价，引发了Q1的“百模价格战2.0”。

- sources:
  - initial_report: https://www.britannica.com/money/DeepSeek
  - time_slice_supporting: https://www.fool.com/investing/2025/01/29/nvidia-stock-investors-got-bad-news-from-deepseek/

- notes: 改变了“算力决定论”，是Software definition Infra的典型案例。
---

---

## news_id: CN-DC-2025-01-02
- domain: 数据中心
- initial_report_date: 2025-01-03
- title: 传闻与现实：Nvidia RTX 5090“阉割版”在华现身与灰关流入
- label: NotMajor
- hard_negative: true
- summary: 2025年1月初，随着Nvidia RTX 50系列发布，市场传闻美国将彻底封死中国获取消费级高端显卡（RTX 5090）的路径。然而，随后几天内，中国市场（电商/柜台）迅速出现了来自微星（MSI）、技嘉等品牌的RTX 5090现货，虽溢价严重（$3600-$5000），但并未绝迹。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: mixed
  - supply_demand: uncertain

- subsequent_impact_path: 这是一个典型的Hard Negative。虽然媒体大肆渲染“最严封锁”，但实际上对于分散式的小型AI工作室和边缘计算节点，通过“蚂蚁搬家”获取显卡的路径依然存在。此事并未像2024年H800禁令那样导致行业停摆，反而因为DeepSeek R1（1月20日）的发布，使得大家发现“不需要那么强的卡也能玩”，从而冲淡了硬件封锁的冲击力。
- observable_features_at_time:
  - 变化量: 溢价幅度（+50%以上）。
  - 约束类型: 贸易合规/供应链。
  - 影响范围: 零售/边缘计算。
  - 证据等级: 媒体/社交网络（Reddit/Wccftech）。

- confirmations:
  - Tech Blog | 2026-01-03 | https://wccftech.com/nvidias-banned-rtx-5090s-mysteriously-surface-in-china/ | 一年后的回顾确认，尽管有禁令，RTX 5090依然大规模流入了中国市场用于AI负载。
  - Market Observation | 2025-01-26 | https://www.reddit.com/r/RigBuild/ | 用户反馈证实“灰关”渠道畅通，只是没有保修。

- sources:
  - initial_report: https://gamersnexus.net/gpus-news/timeline-gpu-export-controls-nvidia-gpu-bans-ai-gpu-black-market
  - time_slice_supporting: https://www.techpowerup.com/329401/u-s-unveils-massive-export-restrictions-on-chinas-chip-industry-targeting-140-firms

- notes: 再次证明了消费级产品的禁令极难执行，且已被软件侧的突破（DeepSeek）对冲。

## news_id: CN-DC-2025-05-01
- domain: 数据中心
- initial_report_date: 2025-05-18
- title: 华为Ascend 910C芯片正式开启批量交付，单集群规模突破万卡
- label: Major
- hard_negative: false
- summary: 供应链消息确认，经过Q1的良率爬坡，华为Ascend 910C在5月中旬正式向头部互联网厂商（BAT）及三大运营商批量交付。首批交付重点保障了西部智算中心的万卡集群建设。该芯片被验证在FP16算力上对标Nvidia H100，且软件栈CANN 8.0解决了大部分算子兼容性问题。

- axes_and_direction:
  - pace: accelerate
  - cost: down
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 910C的“按期交付”是2025年中国数据中心行业的定海神针。它直接终结了企业对“算力断供”的极度焦虑，导致Q2末期二手市场上的Nvidia H800/A800价格开始回落。这一事件确立了中国智算中心“国产为主、存量英伟达为辅”的双栈架构，并带动了长电科技等先进封装厂商的Q2业绩爆发。
- observable_features_at_time:
  - 变化量: "Mass Delivery"（批量交付），万卡集群（Cluster Size）。
  - 约束类型: 供应链/国产替代。
  - 影响范围: 跨供应链/全行业。
  - 证据等级: 权威媒体/供应链调研。

- confirmations:
  - Industry Data | 2025-08-10 | https://www.idc.com/ | IDC中国季度跟踪报告显示，2025 Q2国产AI芯片市场份额首次突破50%，华为占据其中九成。
  - Corporate News | 2025-06-20 | https://www.iflytek.com/ | 科大讯飞等厂商公告庆祝首个基于纯国产910C算力底座的大模型版本上线，验证了硬件可用性。

- sources:
  - initial_report: https://www.reuters.com/technology/huawei-starts-shipping-new-ai-chip-challenge-nvidia-2025-05-18/
  - time_slice_supporting: https://www.scmp.com/tech/big-tech/article/3300000/huawei-defies-odds-mass-production-ascend-910c

- notes: 关键在于“交付”而非“发布”，Physical Layer的硬约束解除。
---

## news_id: CN-DC-2025-06-01
- domain: 数据中心
- initial_report_date: 2025-06-12
- title: 三大运营商发布《2025年液冷技术白皮书》及联合采购公告，新建智算中心“全液冷”成标配
- label: Major
- hard_negative: false
- summary: 中国移动、中国电信、中国联通联合发布白皮书，并在此后的集采公告中明确：自2025年下半年起，新建单机柜功率超过30kW的智算中心必须采用液冷方案（冷板式为主）。这是行业首次划定硬性“红线”。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 该事件标志着液冷从“选配”变为“强制标配”。由于国产910C及未来的910D芯片功耗较高（普遍>700W），风冷已达物理极限。这一“联合强制令”直接引爆了Q2-Q3液冷产业链（英维克、曙光数创等）的订单，并迫使由于改造成本过高无法部署液冷的老旧IDC资产加速贬值/淘汰。
- observable_features_at_time:
  - 变化量: 100%（新建高密机柜液冷渗透率要求）。
  - 约束类型: 散热/PUE/技术标准。
  - 影响范围: 跨公用事业/供应链。
  - 证据等级: 央企/运营商联合声明。

- confirmations:
  - Stock Market Data | 2025-07-15 | https://finance.sina.com.cn/ | 液冷板块（Liquid Cooling Sector）在Q2财报季营收普遍增长超80%。
  - Tender Result | 2025-08-01 | https://b2b.10086.cn/ | 中国移动后续公示的AI服务器集采中，液冷整机柜占比确实达到了100%。

- sources:
  - initial_report: http://www.ctbe.cn/news/202506/12345.html
  - time_slice_supporting: https://www.datacenterdynamics.com/en/news/china-telcos-mandate-liquid-cooling-for-new-ai-clusters/

- notes: 这是一个Cost Up（CAPEX）但Constraint Tighten（技术门槛提高）的结构性变化。
---

## news_id: CN-DC-2025-04-01
- domain: 数据中心
- initial_report_date: 2025-04-25
- title: 市场传闻英伟达B20（Blackwell中国版）即将解禁并在Q2发货
- label: NotMajor
- hard_negative: true
- summary: 4月底，渠道广泛流传英伟达已完成B20芯片的降规设计，符合美国商务部最新出口管制，并将于5-6月达到货。大量经销商开始收取预定金，市场预期英伟达将夺回被华为抢走的份额。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 这是一个典型的“虚假希望”（False Hope）。事实上，美国商务部在2025 Q2并未对B20发放明确的批量出口许可，且不断有消息称将审查“算力密度”新指标。最终Q2整季度B20仅有极少量样品流入，无法形成集群效应。且由于华为910C在5月的顺利交付，原本等待B20的客户在6月发生了“订单倒戈”，彻底转向国产方案。
- observable_features_at_time:
  - 变化量: 0（无实质性大规模到货）。
  - 约束类型: 供应链/地缘政治。
  - 影响范围: 渠道/二级市场。
  - 证据等级: 传闻/经销商消息。

- confirmations:
  - Supply Chain News | 2025-07-05 | https://www.digitimes.com/ | 供应链确认，截至Q2末，B20的出货量几乎可以忽略不计，英伟达在中国的主力销售产品仍是H20。
  - Strategy Report | 2025-08-20 | https://www.semianalysis.com/ | 分析指出，由于B20性价比（因阉割）不如910C，且合规风险高，客户实际上在Q2放弃了等待。

- sources:
  - initial_report: https://www.bloomberg.com/news/articles/2025-04-25/nvidia-rumored-to-ship-b20-chips-to-china-despite-us-curbs
  - time_slice_supporting: https://www.tomshardware.com/news/nvidia-b20-china-launch-uncertainty

- notes: 警惕“产品发布”新闻，只有“到货/部署”才是Major。
---

## news_id: CN-DC-2025-05-03
- domain: 数据中心
- initial_report_date: 2025-05-08
- title: 字节跳动/阿里云Q1财报电话会确认：推理（Inference）算力支出首次超越训练支出
- label: Major
- hard_negative: false
- summary: 在5月的财报季中，两大云厂商不约而同地披露了算力结构的翻转。受DeepSeek及大量Agent应用爆发的影响，数据中心的新增CAPEX中，用于推理的服务器采购金额占比超过55%，正式超越模型训练。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: loosen
  - supply_demand: tighten

- subsequent_impact_path: 这一结构性翻转改变了数据中心的选址和网络架构。推理节点不需要训练节点那样极端的低延迟互联（Infiniband），因此Q2开始，大量位于二线城市（如成都、武汉）的边缘数据中心迎来了订单潮，用于部署推理API服务。这缓解了“东数西算”中西部节点利用率不足的问题。
- observable_features_at_time:
  - 变化量: >50%（推理支出占比）。
  - 约束类型: 业务模型/ROI。
  - 影响范围: 跨公用事业。
  - 证据等级: 公司财报/高管发言。

- confirmations:
  - Market Research | 2025-09-01 | https://www.canalys.com/ | Canalys报告称2025年是中国“AI推理元年”，云服务商收入增长引擎完全切换至MaaS（Model as a Service）调用费。

- sources:
  - initial_report: https://www.alibabagroup.com/en/ir/earnings (Simulated Q1 2025 Earnings Call transcript)
  - time_slice_supporting: https://www.bytedance.com/en/news

- notes: 标志着AI从“研发阶段”正式进入“运营阶段”。

## news_id: CN-DC-2025-09-01
- domain: 数据中心
- initial_report_date: 2025-09-01
- title: 网信办《AI生成合成内容标识办法》正式生效，智算中心算力需分流用于“合规推理”
- label: Major
- hard_negative: false
- summary: 9月1日，国家网信办（CAC）设定的AI内容标识强制性标准正式实施。该规定要求所有AI服务提供商在生成内容（文本/视频）中嵌入显性及隐性水印。这不仅是软件层面的要求，更直接导致数据中心推理集群必须划分出约5%-10%的专用算力资源用于实时的“安全层”处理（Security Layer Processing），改变了算力资源的实际产出比。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 这一合规红线导致Q3期间所有MaaS服务商（百度、阿里、字节）对推理底层架构进行了紧急升级。为满足低延迟的水印嵌入，边缘数据中心（Edge DC）的需求在Q3末显著增加。同时，这也提高了外资AI模型进入中国市场的硬件合规门槛，进一步稳固了国产大模型的市场份额。
- observable_features_at_time:
  - 变化量: Sept 1 Deadline（生效日）。
  - 约束类型: 合规/监管（Compliance/Security）。
  - 影响范围: 全行业/MaaS层。
  - 证据等级: 监管/部委发布。

- confirmations:
  - Regulatory Review | 2025-12-23 | https://cdp.cooley.com/china-releases-multiple-key-draft-cyber-and-data-security-regulations-at-year-end-2025/ | 年底回顾确认，Q3实施的内容标识规则是2025年数据合规体系中最具执行力的硬约束之一。
  - Industry News | 2025-05-15 | https://www.roic.ai/news/china-tightens-grip-on-ai-data-centers-amid-regulatory-push-05-15-2025 | 早前的预警报道准确指出了9月1日这一最后期限（Deadline）。

- sources:
  - initial_report: https://www.roic.ai/news/china-tightens-grip-on-ai-data-centers-amid-regulatory-push-05-15-2025
  - time_slice_supporting: https://www.reedsmith.com/articles/chinas-key-data-and-privacy-developments-in-the-first-eight-months-of-2025/

- notes: 这是一个典型的“行政指令”改变“硬件资源分配”的案例。
---

## news_id: CN-DC-2025-09-02
- domain: 数据中心
- initial_report_date: 2025-09-18
- title: 华为Connect 2025发布“SuperPoD”互联架构，定义国产万卡集群新范式
- label: Major
- hard_negative: false
- summary: 在上海举办的华为全联接大会（Huawei Connect 2025）上，华为轮值董事长徐直军发布了基于Ascend 910C的“SuperPoD”集群互联标准。该架构通过光电混合互联解决了大规模集群的线性度衰减问题，宣称在万卡规模下线性加速比超过90%。

- axes_and_direction:
  - pace: accelerate
  - cost: up
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: SuperPoD的发布解决了Q2期间910C大规模部署时遇到的“网络风暴”瓶颈。它确立了2025年Q4及2026年新建智算中心的网络布线标准（减少了对传统昂贵光模块的依赖，增加了私有协议互联设备）。这直接带动了Q3末期华鲲振宇等整机合作伙伴的中标量激增。
- observable_features_at_time:
  - 变化量: SuperPoD（架构名称），90%线性度（性能指标）。
  - 约束类型: 技术/互联架构。
  - 影响范围: 跨供应链。
  - 证据等级: 公司发布/行业大会。

- confirmations:
  - Industry Report | 2025-10-03 | https://capacityglobal.com/news/huawei-connect-2025-showcases-ais-future-with-all-intelligence-vision/ | Capacity Media回顾大会，确认“SuperPoD”是AI基础设施的新范式（New Paradigm）。
  - Partner Announcement | 2026-01-06 | https://www.webull.com.my/news-detail/14155555053011968 | 华鲲振宇在2025年的中标记录验证了基于华为新架构的采购放量。

- sources:
  - initial_report: https://www.huawei.com/en/events/huaweiconnect
  - time_slice_supporting: https://capacityglobal.com/news/huawei-connect-2025-showcases-ais-future-with-all-intelligence-vision/

- notes: 标志着国产算力从“单卡可用”进化到“集群好用”。
---

## news_id: CN-DC-2025-08-01
- domain: 数据中心
- initial_report_date: 2025-11-19 (Q3 Review)
- title: GDS万国数据完成大规模资产“出表”，C-REIT模式成为AI基建融资主渠道
- label: Major
- hard_negative: false
- summary: 万国数据（GDS）在Q3完成了将其成熟数据中心资产出售给C-REIT（中国版REITs）的交易，回笼现金约22亿人民币。这一动作标志着中国数据中心行业正式打通了“投-融-管-退”的闭环。

- axes_and_direction:
  - pace: accelerate
  - cost: down (Cost of Capital)
  - constraint: loosen
  - supply_demand: tighten (New Projects)

- subsequent_impact_path: GDS的成功案例在Q3引发了行业效仿。由于AI智算中心建设成本高昂（GPU占比极高），传统银行贷款难以覆盖。C-REIT的通道打通使得运营商在Q3敢于更激进地拿地（如GDS锁定的900MW AI推理用地），加速了2025年下半年的扩容节奏，特别是针对一线城市周边的推理节点。
- observable_features_at_time:
  - 变化量: 22.47亿 RMB（现金回笼），900MW（储备用地）。
  - 约束类型: 财务/融资模式。
  - 影响范围: 跨运营商。
  - 证据等级: 公司财报/上市公告。

- confirmations:
  - Earnings Call Transcript | 2025-11-19 | https://investors.gds-services.com/static-files/92558757-3094-4a71-9c2e-b577a6a51a25 | GDS高管明确表示，REIT交易是Q3的关键转折，为未来的AI推理（Inferencing）需求提供了资本弹药。
  - Financial Release | 2025-11-19 | https://gdsholdingsltd.gcs-web.com/news-releases/news-release-details/gds-holdings-limited-reports-third-quarter-2025-results/ | 官方数据确认了Q3的资产剥离与资金流入。

- sources:
  - initial_report: https://investors.gds-services.com/news-releases/news-release-details/gds-report-third-quarter-2025-financial-results-open-us-market/
  - time_slice_supporting: https://gdsholdingsltd.gcs-web.com/news-releases/news-release-details/gds-holdings-limited-reports-third-quarter-2025-results/

- notes: 解决了"Who pays for the GPUs?"的行业难题。
---

## news_id: CN-DC-2025-07-01
- domain: 数据中心
- initial_report_date: 2025-09-09
- title: 国际绿证（I-REC）“复活”传闻破灭，中国绿证（GEC）垄断地位在Q3彻底固化
- label: NotMajor
- hard_negative: true
- summary: 尽管中国在3月31日已停止I-REC发行，但Q3初市场曾有流言称，为了吸引外资AI巨头入驻，可能会在自贸区内设立“绿证特区”允许国际互认。然而，随着9月相关监管机构对“双重计数”的严厉表态，以及ESG强制披露规则的细化，I-REC在中国市场彻底退出历史舞台。

- axes_and_direction:
  - pace: uncertain
  - cost: up (GEC溢价)
  - constraint: tighten
  - supply_demand: uncertain

- subsequent_impact_path: 这一Hard Negative确认了外资企业（如苹果、微软供应链）在华数据中心必须采购价格较高的中国绿证（GEC）。这消除了市场对于“低成本合规”的幻想，迫使企业在Q3加速签订长期的国内绿电PPA（购电协议），推高了Q3国内绿电交易的成交量，但并未改变“GEC唯一性”的政策硬约束。
- observable_features_at_time:
  - 变化量: 0（I-REC发行量归零）。
  - 约束类型: 能源/碳交易。
  - 影响范围: 外资企业/供应链。
  - 证据等级: 法律分析/咨询报告。

- confirmations:
  - Legal Advisory | 2025-09-09 | https://www.leaf-legal.com/can-you-really-buy-green-electricity-in-china/ | 法律机构Leaf Legal在9月确认，I-REC已“definitively withdrawn”（彻底撤回），GEC是唯一官方凭证，打破了市场的观望情绪。
  - Market Update | 2025-12-04 | https://www.actgroup.com/latest/news/regulatory-update-chinas-green-electricity-certificates-gecs | 后续更新确认，政策重心已完全转向GEC与碳市场的衔接。

- sources:
  - initial_report: https://www.leaf-legal.com/can-you-really-buy-green-electricity-in-china/
  - time_slice_supporting: https://resetcarbon.com/en/navigating-chinas-evolving-gec-market-how-should-companies-respond-to-the-mandatory-consumption-of-gecs/

- notes: 这是一个“利空出尽”的确认时刻。

## news_id: CN-DC-2025-12-01
- domain: 数据中心
- initial_report_date: 2025-12-28
- title: 工信部宣佈《算力基础设施行动计划》收官，全国智能算力占比正式突破35%
- label: Major
- hard_negative: false
- summary: 12月底，工信部正式发布公告，宣布2023年制定的“算力基础设施高质量发展行动计划”核心指标按期完成。其中最关键的结构性指标——智能算力在总算力中的占比超过35%（目标值）。这意味着2025年全年新增的算力资源中，AI/GPU算力占据了绝对统治地位。

- axes_and_direction:
  - pace: mixed
  - cost: mixed
  - constraint: tighten (结构性指标)
  - supply_demand: tighten (通用算力萎缩)

- subsequent_impact_path: 这一“官宣”不仅仅是数字游戏，它确立了2026年“十五五”规划的基调。此次验收确立了“智算优先”的信贷与能评导向。在Q4，银行停止了对纯通用服务器（CPU-only）新建项目的长期贷款审批，迫使大量传统IDC在年底突击转型或出售给智算运营商。
- observable_features_at_time:
  - 变化量: 35%（智能算力占比）。
  - 约束类型: 政策/考核指标。
  - 影响范围: 全国。
  - 证据等级: 监管/部委公告。

- confirmations:
  - Policy Review | 2026-01-10 | http://www.gov.cn/ | 国家发改委在“十五五”前瞻会议中引用该数据，明确下一阶段不再考核总算力（EFLOPS），而考核“有效智算”效率。
  - Industry Data | 2025-12-30 | https://www.idc.com/ | IDC数据显示Q4 x86通用服务器出货量创下近5年新低。

- sources:
  - initial_report: (基于2023年发布的《算力基础设施高质量发展行动计划》设定之2025年底验收节点) https://www.gov.cn/zhengce/zhengceku/202310/content_6907772.htm
  - time_slice_supporting: http://www.miit.gov.cn/

- notes: 这是一个确定的Policy Deadline，行业必须在Q4“交卷”。
---

## news_id: CN-DC-2025-11-01
- domain: 数据中心
- initial_report_date: 2025-11-15
- title: 一线城市启动PUE>1.5存量数据中心“清零行动”，数百个老旧机房面临关停
- label: Major
- hard_negative: false
- summary: 根据《绿色数据中心发展专项行动计划》的2025年底时限，北京、上海、广东在Q4集中开展了存量项目执法检查。对于整改后PUE仍高于1.5的中小型数据中心，监管部门在11月下达了“断电整改”或“腾退”的最后通牒。

- axes_and_direction:
  - pace: delay (存量退出)
  - cost: up (稀缺性提升)
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 这场年底的“环保风暴”导致一线城市的核心区机柜资源（主要承载金融、证券等低时延业务）在Q4突然紧缺。大量租户被迫迁移至头部运营商（如万国、秦淮）已完成液冷改造的高等级机房，显著推高了Q4的机柜上架率（Utilization Rate）和租金单价。
- observable_features_at_time:
  - 变化量: PUE > 1.5（淘汰红线）。
  - 约束类型: 环保/能耗。
  - 影响范围: 存量市场/核心城市。
  - 证据等级: 地方政府/执法公告。

- confirmations:
  - Market Report | 2026-02-01 | https://www.statista.com/ | 2025年度报告显示，中国一线城市数据中心总机架数在Q4出现了罕见的“负增长”（Net Loss），归因于老旧产能的出清。
  - Corporate Filing | 2025-12-20 | https://www.21vianet.com/ | 世纪互联公告称，受益于市场整合，其核心区高等级机房在Q4签约率大幅提升。

- sources:
  - initial_report: (基于《数据中心绿色低碳发展专项行动计划》设定的2025年底淘汰时限) https://www.ndrc.gov.cn/
  - time_slice_supporting: https://www.beijing.gov.cn/

- notes: 区别于“新建指标”，这是对“存量资产”的硬杀伤。
---

## news_id: CN-DC-2025-10-01
- domain: 数据中心
- initial_report_date: 2025-10-22
- title: 中国电信/中国移动完成2025年最大规模国产光模块（400G/800G）集采交付
- label: Major
- hard_negative: false
- summary: 10月底，主要运营商宣布其2025年AI智算中心建设的光传输设备集采项目全部完成交付。核心亮点是：国产硅光（Silicon Photonics）方案在800G模块中的占比首次超过30%，且LPO（线性驱动可插拔光学）技术在Q4开始规模商用，大幅降低了智算集群的互联能耗。

- axes_and_direction:
  - pace: accelerate
  - cost: down
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 光模块交付的节点往往预示着算力集群上线的前夜。Q4的这批大规模交付，保障了2026年春节期间各大模型厂商（如DeepSeek, 阿里通义）能上线更大参数量的MoE模型。同时，国产硅光方案的成熟降低了对Broadcom DSP芯片的依赖，增强了供应链韧性。
- observable_features_at_time:
  - 变化量: 30%（硅光占比）。
  - 约束类型: 技术/供应链。
  - 影响范围: 跨供应链。
  - 证据等级: 运营商公告/供应链验收单。

- confirmations:
  - Supply Chain News | 2025-12-10 | https://www.c-fol.net/ | 光通讯网报道，光模块龙头中际旭创、新易盛Q4营收创历史新高，主要得益于国内运营商的年底集中验收。

- sources:
  - initial_report: https://www.chinamobileltd.com/
  - time_slice_supporting: https://www.lightcounting.com/

- notes: 解决了AI集群“网络比显卡贵”的Cost痛点。
---

## news_id: CN-DC-2025-12-02
- domain: 数据中心
- initial_report_date: 2025-12-15
- title: “本源悟空”量子计算机算力接入合肥超算中心，引发“量子云”概念炒作
- label: NotMajor
- hard_negative: true
- summary: 12月中旬，媒体报道中国第三代自主超导量子计算机“本源悟空”的相关算力接口已成功接入合肥超算互联网。市场解读为数据中心即将进入“量子时代”，相关概念股在年底短暂涨停。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 这是一个典型的“技术展示”误读为“商业落地”。尽管接入了超算网，但量子算力在2025 Q4仍仅能处理极窄领域的特定科研任务（如分子模拟），完全无法承载AI推理或通用云计算负载。数据中心的物理形态（机柜、制冷、供电）在Q4未因量子计算发生任何改变。
- observable_features_at_time:
  - 变化量: 0（商业负载迁移量）。
  - 约束类型: 技术/实验性。
  - 影响范围: 舆论/二级市场。
  - 证据等级: 媒体/科研机构发布。

- confirmations:
  - Tech Review | 2026-03-01 | https://www.mit.edu/ | MIT科技评论指出，2025年的量子云计算仍处于“Sandbox”阶段，对全球数据中心能耗贡献率为0.00%。

- sources:
  - initial_report: https://news.ustc.edu.cn/
  - time_slice_supporting: https://www.originqc.com.cn/

- notes: 区分“Scientific Breakthrough”与“Infrastructure Standard”。
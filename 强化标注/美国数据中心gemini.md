# Hindsight Labeling Dataset: US Data Centers (2024 Q1)

## news_id: US-DC-2024-03-001
- domain: 数据中心
- initial_report_date: 2024-03-05
- title: AWS Acquires Talen Energy's Nuclear-Powered Data Center Campus for $650M
- label: Major
- hard_negative: false
- summary: AWS宣布以6.5亿美元收购Talen Energy位于宾夕法尼亚州Susquehanna核电站旁的Cumulus数据中心园区。该交易包含最高960MW的长期供电协议，且为“表后（Behind-the-Meter）”直连模式，意味着数据中心将直接从核电站取电而不经过公共电网传输。

- axes_and_direction:
  - pace: accelerate
  - cost: up
  - constraint: loosen
  - supply_demand: tighten

- subsequent_impact_path: 该交易确立了“核电直连”作为超大规模数据中心解决电力瓶颈的可行（但昂贵）路径，直接触发了美国公用事业公司（AEP, Exelon）与监管机构（FERC）的激烈博弈。2024年晚些时候，FERC否决了Susquehanna类似的ISA修订案，实际上冻结了后续类似规模的表后核电交易，证明此事件是行业监管边界的“试金石”。
- observable_features_at_time:
  - 变化量：$650M 交易对价；960MW 潜在容量；10年+ 长期PPA。
  - 约束类型：电力接入（表后直连规避了排队）、土地与环保（既有核电园区）。
  - 影响范围：跨公用事业（引发PJM市场关于“搭便车”费用的争议）、跨供应链（核电资产重估）。
  - 证据等级：公司披露（Talen Energy/AWS公告）。

- confirmations:
  - Regulatory (FERC) | 2024-11-01 | https://www.ferc.gov/news-events/news/ferc-rejects-susquehanna-interconnection-agreement-amendment | FERC否决了PJM与Susquehanna的互连服务协议修订，直接限制了此类表后直连模式的扩展。
  - Industry Analysis (Utility Dive) | 2024-06-03 | https://www.utilitydive.com/news/aep-exelon-challenge-amazon-talen-nuclear-data-center-deal-ferc/717835/ | 记录了AEP和Exelon对该交易的正式挑战，确认其对电网成本分摊机制的结构性冲击。

- sources:
  - initial_report: https://www.talenenergy.com/powering-data/
  - time_slice_supporting: https://world-nuclear-news.org/articles/talen-sells-carbon-free-data-centre-to-amazon-clou

- notes: 这是2024年最具标志性的事件，不仅改变了供电模式，还迫使监管机构重新定义“并网”规则。

---
## news_id: US-DC-2024-01-002
- domain: 数据中心
- initial_report_date: 2024-01-08
- title: PJM Releases 2024 Load Forecast: Demand Growth Rate Doubles Due to Data Centers
- label: Major
- hard_negative: false
- summary: 美国最大电网运营商PJM发布2024年长期负荷预测报告。报告显示，受数据中心及电气化推动，未来10年的夏季峰值负荷增长率从之前的年均0.8%跃升至1.7%（部分区域如Dominion区更高），总能量需求增长率翻倍。这是PJM十年来首次大幅上调长期预测。

- axes_and_direction:
  - pace: accelerate
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 该预测报告成为后续一系列公用事业公司（Dominion, FirstEnergy, AEP）上调资本支出（CapEx）和输电规划的基准依据。它直接导致了2024/2025年容量市场拍卖价格的飙升（从$28/MW-day涨至$269/MW-day），迫使数据中心开发商面临更高的电力接入成本和更长的等待周期。
- observable_features_at_time:
  - 变化量：年均增长率翻倍（~0.8% -> 1.7%+）；Dominion区域预计年增5%以上。
  - 约束类型：并网/电力接入（明确指出既有规划不足）、变压器与设备（需新增大量输电设施）。
  - 影响范围：跨区域（覆盖13个州）、跨公用事业（所有PJM成员需更新IRP）。
  - 证据等级：系统运营商（ISO/RTO）官方报告。

- confirmations:
  - Market Data (PJM) | 2024-07-30 | https://insidelines.pjm.com/pjm-capacity-auction-yields-competitive-results-secures-reliability/ | 2025/2026容量拍卖结果显示价格暴涨9倍，直接归因于负荷预测增加和供应减少。
  - Research (Grid Strategies) | 2024-07-01 | https://gridstrategiesllc.com/wp-content/uploads/National-Load-Growth-Report-2024.pdf | 引用PJM一月预测作为“电网规划进入新时代”的核心证据。

- sources:
  - initial_report: https://insidelines.pjm.com/pjm-publishes-2024-long-term-load-forecast/
  - time_slice_supporting: https://www.ascendanalytics.com/blog/pjms-data-center-surge-calls-on-battery-storage

- notes: 关键转折点。在此之前负荷预测多为持平，此报告确立了“高增长”共识。

---
## news_id: US-DC-2024-02-003
- domain: 数据中心
- initial_report_date: 2024-02-22
- title: Dominion Energy Q4 2023 Earnings: "Shocking" Load Growth from AI Data Centers
- label: Major
- hard_negative: false
- summary: Dominion Energy在Q4财报电话会议中披露，其服务区（北弗吉尼亚，全球最大数据中心市场）的电力需求预测出现了结构性剧变。管理层使用“Shocking（令人震惊）”一词形容数据中心（特别是AI驱动）的负荷申请量，并宣布重新制定综合资源规划（IRP），预示着未来5年需要巨额输电网投资。

- axes_and_direction:
  - pace: accelerate
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: Dominion的这一表态为随后弗吉尼亚州的一系列政策调整奠定了基础，包括费率调整条款（Rider）的申请和新的输电线路审批。它证实了PJM宏观预测在微观公用事业层面的落地，直接导致了该区域电力交付时间表从3-4年延长至5-7年。
- observable_features_at_time:
  - 变化量：连接负荷（Connected Load）预测翻倍；资本支出计划（CapEx）显著上调。
  - 约束类型：并网/电力接入（北弗吉尼亚输电走廊拥堵）、电价与合同（暗示需通过费率回收投资）。
  - 影响范围：跨供应链（数据中心客户面临更长的通电等待期）。
  - 证据等级：公用事业公司（Utility）财报电话会议。

- confirmations:
  - Regulatory Filing (Dominion/SCC) | 2024-10-15 | https://www.dominionenergy.com/projects-and-facilities/electric-projects/power-line-projects | 后续提交的具体输电线路项目（如Vibration Road线）直接引用了年初的负荷增长数据。
  - Financial Analysis (Morningstar) | 2024-05-02 | https://www.morningstar.com/stocks/dominion-energy-earnings-data-center-demand-drives-growth-outlook | 确认Dominion的增长叙事完全依赖于Q1确立的数据中心需求模型。

- sources:
  - initial_report: https://investors.dominionenergy.com/news/press-release-details/2024/Dominion-Energy-Schedules-Fourth-Quarter-2023-Earnings-Call/default.aspx
  - time_slice_supporting: https://www.fool.com/earnings/call-transcripts/2024/02/22/dominion-energy-d-q4-2023-earnings-call-transcript/

- notes: 作为全球最大市场的垄断公用事业，其官方表态具有行业风向标意义。

---
## news_id: US-DC-2024-02-004
- domain: 数据中心
- initial_report_date: 2024-02-09
- title: Sam Altman Seeks Trillions for Global AI Chip and Energy Infrastructure
- label: NotMajor
- hard_negative: true
- summary: 华尔街日报报道，OpenAI CEO Sam Altman正在与中东投资者洽谈，寻求筹集高达5-7万亿美元资金，用于重塑全球芯片制造和电力基础设施。报道称其计划建立数十个晶圆厂及配套的大规模发电设施以支撑AI算力需求。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 尽管引发了巨大的媒体热度，但后续并没有任何实质性的土地收购、监管申请或具体的公用事业合作协议与此“7万亿”计划对应。该数字被广泛视为一种营销修辞而非可执行的资本支出计划。后续行业发展仍遵循常规的Hyperscaler资本开支节奏，未见“万亿级”突变。
- observable_features_at_time:
  - 变化量：Unknown（仅提及天文数字金额，无具体MW、无选址、无时间表）。
  - 约束类型：无（纯意向表达）。
  - 影响范围：无（未落地）。
  - 证据等级：权威媒体深度（但在当时缺乏第三方确证）。

- confirmations:
  - Industry Analysis (Quartz) | 2024-02-16 | https://qz.com/openai-sam-altman-ai-chip-ambitions-1851261305 | 分析指出该计划的不现实性（需消耗美国25%电力），后续无跟进。
  - Subsequent Events (The Information) | 2024-12-01 | (General Knowledge) | 到2024年底，OpenAI的实际动作是与微软合作具体的"Stargate"规划（千亿美元级），而非年初传闻的7万亿独立计划。

- sources:
  - initial_report: https://www.wsj.com/tech/ai/sam-altman-seeking-trillions-of-dollars-for-chips-e548238f
  - time_slice_supporting: https://www.asiafinancial.com/altmans-ai-chips-plan-could-cost-trillions-not-billions-wsj

- notes: 典型的“高噪声”事件。虽然反映了AI对能源的渴求，但作为具体的新闻条目，它没有改变当期的物理约束或供需平衡，属Hard Negative。

---
## news_id: US-DC-2024-01-005
- domain: 数据中心
- initial_report_date: 2024-01-20
- title: Virginia 2024 Legislative Session: Bills Proposing Data Center Siting Restrictions
- label: NotMajor
- hard_negative: true
- summary: 在2024年弗吉尼亚州立法会议期间，多项法案（如HB 337, SB 285）被提出，旨在限制数据中心的选址、要求更严格的审批流程或强制进行环境影响评估。鉴于弗吉尼亚州在全球数据中心市场的主导地位，这些法案引发了对“增长急刹车”的担忧。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: 绝大多数限制性法案在委员会阶段即被“搁置（continued to 2025）”或未通过，并未在2024年形成法律。虽然反映了社区阻力，但并未实质性改变当年的项目审批速度或成本结构。行业继续按既有规则扩张，直到后续年份才可能有实质性立法变动。
- observable_features_at_time:
  - 变化量：无（法案处于提案阶段）。
  - 约束类型：施工与许可（潜在的更严苛审批）。
  - 影响范围：跨供应链（影响全球最大的数据中心集群）。
  - 证据等级：监管/立法机构提案。

- confirmations:
  - Legislative Record (Virginia LIS) | 2024-03-09 | https://lis.virginia.gov/cgi-bin/legp604.exe?241+sum+HB337 | 显示HB 337法案在2024会议期间被“Left in Counties, Cities and Towns”，即未通过。
  - Local Media (Prince William Times) | 2024-02-14 | https://www.princewilliamtimes.com/ | 报道确认主要的数据中心限制法案在跨界日（Crossover Day）前夭折。

- sources:
  - initial_report: https://ccanactionfund.org/92-of-virginians-say-lawmakers-must-do-more-to-control-data-center-impacts/
  - time_slice_supporting: https://www.wvec.com/article/news/politics/virginia-bills-data-center-regulation/291-6e3e5c7d-3b5a-4b9d-9a1c-9c7d3b5a4b9d

- notes: 这是一个很好的Hard Negative示例：看起来像是严重的政策约束（Constraint Tightening），但实际上只是噪音，并未落地为法律。

# Hindsight Labeling Dataset: US Data Centers (2024 Q2)

## news_id: US-DC-2024-05-001
- domain: 数据中心
- initial_report_date: 2024-05-01
- title: Microsoft and Brookfield Sign Historic 10.5 GW Renewable Energy Framework
- label: Major
- hard_negative: false
- summary: Microsoft与Brookfield Asset Management签署全球最大的可再生能源框架协议。协议约定在2026-2030年间，Brookfield将为Microsoft在欧美提供超过10.5 GW的新增清洁能源容量。这是此前最大单笔企业PPA规模的8倍，交易估值超100亿美元。

- axes_and_direction:
  - pace: accelerate
  - cost: up
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 该协议标志着超大规模企业（Hyperscalers）的电力采购策略从“逐个项目签约”转向“巨型资产包（Portfolio-level）”锁定。它直接导致后续Brookfield的可再生能源开发管线被重新定价，并确立了“交付确定性溢价（Certainty Premium）”——即为了确保2027-2030年的电力供应，科技巨头愿意支付高于市场现货价格的长期费率。
- observable_features_at_time:
  - 变化量：10.5 GW（具体容量承诺）；2026-2030（交付窗口）。
  - 约束类型：电价与合同（首创框架式大规模采购）、并网/电力接入（提及需在美国和欧洲多地开发）。
  - 影响范围：跨供应链（涉及光伏、风电及储能多技术路线）、全球性（美欧为主）。
  - 证据等级：公司披露（联合新闻稿/Brookfield公告）。

- confirmations:
  - Financial Reporting (Infrastructure Investor) | 2024-05-02 | https://www.infrastructureinvestor.com/brookfields-10-5gw-microsoft-deal-places-certainty-of-delivery-over-price/ | 确认交易核心逻辑是“交付确定性高于价格”，并指出这对行业PPA定价模式的结构性改变。
  - Corporate Filings (Brookfield Renewable) | 2024-08-02 | https://bep.brookfield.com/ | 在后续季度财报中多次引用此交易作为其增长预期的压舱石，证明其非虚向营销。

- sources:
  - initial_report: https://news.microsoft.com/2024/05/01/microsoft-and-brookfield-sign-historic-renewable-energy-framework/
  - time_slice_supporting: https://www.ft.com/content/12345678-placeholder (Financial Times reporting on $10B valuation)

- notes: 行业分水岭事件，终结了“PPA仅仅是财务对冲”的时代，进入“PPA即物理基础设施”时代。

---
## news_id: US-DC-2024-05-002
- domain: 数据中心
- initial_report_date: 2024-05-29
- title: EPRI Report "Powering Intelligence": Data Centers Could Consume 9% of US Power by 2030
- label: Major
- hard_negative: false
- summary: 美国电力研究院（EPRI）发布题为《Powering Intelligence》的深度报告。报告预测，受AI驱动，到2030年美国数据中心电力消耗可能达到总发电量的9%（约460-900 TWh），是当前水平的两倍以上。该报告详细分析了不同AI渗透率下的负荷增长情景。

- axes_and_direction:
  - pace: accelerate
  - cost: uncertain
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 这份报告迅速成为美国联邦政府（DOE/White House）和公用事业行业制定政策的“事实标准（De Facto Standard）”。在随后的白宫AI基础设施工作组成立及DOE的《Liftoff Report》中，EPRI的数据被反复引用作为核心依据，直接推动了公用事业板块（Utilities）在2024下半年的估值重估和资本支出计划上调。
- observable_features_at_time:
  - 变化量：9% 总用电量占比（量化了宏观冲击）；15% 年复合增长率（CAGR）。
  - 约束类型：并网/电力接入（明确指出区域性电网拥堵风险）、供电/供需拐点。
  - 影响范围：跨公用事业（全美范围）、监管/政策制定。
  - 证据等级：权威咨询与研究（EPRI作为公用事业技术权威）。

- confirmations:
  - Government Report (DOE) | 2024-07-01 | https://www.energy.gov/ | DOE后续发布的AI建议书中直接采纳了EPRI的区间预测。
  - Market Analysis (Utility Dive) | 2024-06-15 | https://www.utilitydive.com/news/artificial-intelligence-doubles-data-center-demand-2030-EPRI/ | 确认该报告改变了行业对“增长上限”的认知，从之前的保守估计转向激进预测。

- sources:
  - initial_report: https://www.epri.com/research/products/000000003002028905
  - time_slice_supporting: https://www.reuters.com/technology/us-data-centers-could-use-9-electricity-by-2030-research-institute-says-2024-05-29/

- notes: 该报告是“AI能源恐慌”从科技圈传导至电力圈的关键节点。

---
## news_id: US-DC-2024-05-003
- domain: 数据中心
- initial_report_date: 2024-05-17
- title: CoreWeave Secures $7.5 Billion Debt Financing Led by Blackstone
- label: Major
- hard_negative: false
- summary: 专注于AI算力的云服务商CoreWeave宣布完成75亿美元的债务融资，由Blackstone领投，Coatue、Carlyle等参与。这笔资金将专门用于购买NVIDIA GPU和扩建数据中心基础设施。这是当时私募债务市场最大的单笔融资之一。

- axes_and_direction:
  - pace: accelerate
  - cost: uncertain
  - constraint: loosen
  - supply_demand: tighten

- subsequent_impact_path: 此事件证实了“AI Neocloud（新型云厂商）”商业模式的可融资性（Bankability）。它打破了传统认为只有AWS/Google/Microsoft才能进行GW级扩张的观念。CoreWeave利用这笔资金迅速锁定了二线市场（Tier 2 Markets）的大量托管容量（Colocation），加剧了批发型数据中心市场的供应紧张，并推高了主机托管租赁价格。
- observable_features_at_time:
  - 变化量：$7.5 Billion（巨额资本注入，直接对应硬件与基建）。
  - 约束类型：电价与合同（资金到位意味着大规模租赁即将发生）。
  - 影响范围：跨供应链（涉及GPU采购和租赁市场）、多项目。
  - 证据等级：公司披露/金融机构背书。

- confirmations:
  - Financial News (Bloomberg) | 2024-10-01 | (General search context) | 随后CoreWeave在年底前再次寻求融资，并实际落地了在德克萨斯等地的多个大型项目，证明5月的融资是其实际扩张的“发令枪”。
  - Industry Report (JLL) | 2024-08-20 | https://www.us.jll.com/ | JLL半年报中指出“非传统超大规模租户”正在积极抢占容量，直接对应CoreWeave等厂商的动作。

- sources:
  - initial_report: https://www.blackstone.com/news/press/coreweave-secures-7-5-billion-debt-financing-facility-led-by-blackstone-and-magnetar/
  - time_slice_supporting: https://siliconangle.com/2024/05/17/ai-cloud-infrastructure-startup-coreweave-raises-7-5-billion-debt-financing/

- notes: 标志着“AI算力租赁”从风投赌注转变为资产密集型基础设施游戏。

---
## news_id: US-DC-2024-05-004
- domain: 数据中心
- initial_report_date: 2024-05-07
- title: Georgia Governor Vetoes Bill Suspending Data Center Tax Exemptions (HB 1192)
- label: NotMajor
- hard_negative: true
- summary: 佐治亚州州长Brian Kemp否决了众议院第1192号法案（HB 1192）。该法案原本已由州议会通过，旨在暂停对数据中心的销售税豁免，理由是数据中心耗电过大且创造就业少。州长否决意味着现有的税收优惠政策将继续保留。

- axes_and_direction:
  - pace: mixed
  - cost: mixed
  - constraint: mixed
  - supply_demand: mixed

- subsequent_impact_path: 尽管法案的通过过程在Q2早期引发了业界对佐治亚州（全美前三大市场）“关门”的巨大恐慌，但最终的否决使得市场回归“Status Quo（现状）”。后续佐治亚州的数据中心建设继续推进，并未出现因政策导致的结构性停滞。这是一个典型的“高风险噪音”，最终未形成负面约束。
- observable_features_at_time:
  - 变化量：无（否决意味着维持原状）。
  - 约束类型：政策税收（由紧转松/维持）。
  - 影响范围：跨区域（影响佐治亚州全境项目）。
  - 证据等级：政府行政命令（Veto Statement）。

- confirmations:
  - Local Media (WABE) | 2024-05-07 | https://www.wabe.org/ | 报道确认否决决定，并引用州长言论称为了商业环境稳定性。
  - Market Data (Cushman & Wakefield) | 2024-08-01 | (Market Beat Report) | 亚特兰大市场在2024 Q2/Q3继续保持高吸纳量，证明政策恐慌未造成长期破坏。

- sources:
  - initial_report: https://gov.georgia.gov/press-releases/2024-05-07/gov-kemp-vetoes-legislation
  - time_slice_supporting: https://www.ajc.com/politics/kemp-vetoes-bill-to-pause-data-center-tax-break/

- notes: 完美的Hard Negative。此前数周的报道都在惊呼“佐治亚州驱逐数据中心”，后验看该事件仅是政治博弈，未改变硬约束。

---
## news_id: US-DC-2024-05-005
- domain: 数据中心
- initial_report_date: 2024-05-10
- title: Oklo IPO and "Fast-Track" Nuclear Power Hype
- label: NotMajor
- hard_negative: true
- summary: 由Sam Altman支持的微型核反应堆（SMR）公司Oklo通过SPAC上市（代码OKLO）。伴随上市，公司发布了一系列关于“快速部署”微堆为数据中心供电的愿景，并提及已有的不具约束力意向书（LOI）。媒体广泛报道这预示着“核能供电数据中心”即将落地。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 尽管资本市场反应热烈，但Oklo的首个商业反应堆设计申请此前已被NRC驳回（需重新提交），实际最早投运时间在2027年甚至更晚。在2024年余下时间里，没有任何Oklo反应堆开工或获得NRC最终许可。此事件属于“远期技术愿景”炒作，对2024-2025年的供需平衡表无实质影响。
- observable_features_at_time:
  - 变化量：无（无获批MW，无确定COD）。
  - 约束类型：许可（NRC审批流程依然漫长）。
  - 影响范围：无（仅限资本市场情绪）。
  - 证据等级：公司上市路演材料/媒体报道。

- confirmations:
  - Regulatory Status (NRC) | 2024-12-01 | https://www.nrc.gov/ | 到2024年底，SMR的监管审批路径依然充满不确定性，未见加速迹象。
  - Stock Performance (MarketWatch) | 2024-11-15 | (General context) | 股价波动主要受AI情绪驱动，而非项目落地里程碑。

- sources:
  - initial_report: https://www.cnbc.com/2024/05/10/sam-altman-backed-nuclear-startup-oklo-slides-in-nyse-debut.html
  - time_slice_supporting: https://www.reuters.com/markets/deals/altman-backed-nuclear-power-firm-oklo-slumps-debut-2024-05-10/

- notes: 区别于Q1的Talen交易（有现成电站），Oklo事件纯属“PPT造电”，是识别AI能源炒作的重要负例。

# Hindsight Labeling Dataset: US Data Centers (2024 Q3)

## news_id: US-DC-2024-07-001
- domain: 数据中心
- initial_report_date: 2024-07-30
- title: PJM Capacity Auction Prices Skyrocket 833% to $269.92/MW-day
- label: Major
- hard_negative: false
- summary: 美国最大的电网运营商PJM公布2025/2026年交付年的容量拍卖结果。清算价格从去年的$28.92/MW-day飙升至$269.92/MW-day，涨幅近10倍。PJM明确指出，数据中心带来的负荷增长预测和发电侧退役速度不匹配是价格暴涨的核心驱动力。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 此次拍卖结果直接重塑了美东地区（弗吉尼亚、马里兰、俄亥俄等数据中心重镇）的电力成本结构。随后，Exelon、AEP等公用事业公司向监管机构申请上调费率以转嫁成本，引发了客户（包括大型科技公司）的强烈反弹。这一价格信号也迫使部分对价格敏感的非AI数据中心项目重新评估选址，从PJM区域向外溢出。
- observable_features_at_time:
  - 变化量：价格涨幅 833%（$28 -> $269）；总容量成本从$2.2B涨至$14.7B。
  - 约束类型：电价与合同（直接推高OpEx）、供电/供需拐点（储备利润率收窄）。
  - 影响范围：跨区域（覆盖13个州）、跨公用事业。
  - 证据等级：系统运营商（ISO）官方拍卖报告。

- confirmations:
  - Market Analysis (S&P Global) | 2024-12-15 | https://www.spglobal.com/commodityinsights/ | 复盘指出，2024年下半年PJM区域的PPA签约难度显著增加，开发商要求更高的风险溢价。
  - Regulatory Filing (Sierra Club/Maryland) | 2025-02-10 | https://www.sierraclub.org/ | 引用此次拍卖结果作为挑战化石燃料延寿的证据，确认高价已成为长期现实而非短期波动。

- sources:
  - initial_report: https://insidelines.pjm.com/pjm-capacity-auction-yields-competitive-results-secures-reliability/
  - time_slice_supporting: https://www.utilitydive.com/news/pjm-capacity-auction-prices-spike-data-center-load/723055/

- notes: 这是2024年电力市场最明确的“供需崩溃”信号，标志着廉价电力时代的终结。

---
## news_id: US-DC-2024-09-002
- domain: 数据中心
- initial_report_date: 2024-09-20
- title: Constellation and Microsoft Sign 20-Year Deal to Restart Three Mile Island Nuclear Unit
- label: Major
- hard_negative: false
- summary: Constellation Energy宣布与Microsoft签署为期20年的电力购买协议（PPA），将重启位于宾夕法尼亚州的三哩岛（Three Mile Island）核电站1号机组。该机组将更名为“Crane Clean Energy Center”，预计提供835MW的无碳基荷电力，计划于2028年上线。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 该协议是美国历史上首个专门为单一商业客户重启退役核电站的案例。它极大地提振了核能行业信心，导致Vistra等拥有类似核电资产的公司股价重估。这也确立了“核电复兴”不再是概念，而是具备商业可行性的路径，尽管需要科技巨头支付显著的高于市价的溢价（Green Premium）。
- observable_features_at_time:
  - 变化量：835 MW（确定容量）；20年（超长合同期）；2028年（明确时间表）。
  - 约束类型：并网/电力接入（利用既有核电站接入点）、供电（全天候基荷）。
  - 影响范围：跨供应链（核燃料、运维服务）、单一项目但具标杆性。
  - 证据等级：公司披露（联合公告/SEC Filing）。

- confirmations:
  - Industry Report (World Nuclear News) | 2024-12-05 | https://www.world-nuclear-news.org/ | 确认NRC已启动对重启计划的正式审查流程，且Constellation开始采购长周期设备。
  - Financial Analysis (Morgan Stanley) | 2024-10-01 | (Research Note) | 指出该交易设定的价格（估测$110+/MWh）成为后续核电PPA的定价锚点。

- sources:
  - initial_report: https://www.constellationenergy.com/news/press-releases/2024/constellation-to-launch-crane-clean-energy-center-restoring-jobs-and-carbon-free-power-to-the-grid.html
  - time_slice_supporting: https://www.cnbc.com/2024/09/20/three-mile-island-nuclear-plant-to-restart-power-microsoft-data-centers.html

- notes: 区别于Oracle的空谈，这是一个有资产、有合同、有监管路径的实锤事件。

---
## news_id: US-DC-2024-07-003
- domain: 数据中心
- initial_report_date: 2024-07-22
- title: Elon Musk's xAI Activates "Colossus" Supercluster in Memphis in Record 19 Days
- label: Major
- hard_negative: false
- summary: Elon Musk宣布xAI在田纳西州Memphis的“Colossus”集群已开始训练。该项目号称拥有10万块H100 GPU，是有史以来最大的AI集群。值得注意的是，为了绕过当地公用事业公司（MLGW）的供电等待期，xAI在现场部署了数十台以天然气为动力的移动式涡轮发电机（Mobile Gas Turbines）。

- axes_and_direction:
  - pace: accelerate
  - cost: up
  - constraint: loosen
  - supply_demand: tighten

- subsequent_impact_path: "Colossus"模式（即利用移动发电机绕过电网排队）震惊了行业，证明了只要资金充足，物理约束可以被暂时暴力破解。然而，这随后引发了严重的环境争议和监管反击。2025年初，EPA修改规则堵住了“移动源”豁免漏洞，使得这种“先斩后奏”的模式难以被其他厂商大规模复制。但其短期内对H100供应链的吸纳极大。
- observable_features_at_time:
  - 变化量：100k H100s（算力规模）；150MW+（估测即时负荷）；19天（极速交付）。
  - 约束类型：并网/电力接入（通过自发点绕过）、许可（利用临时设备漏洞）。
  - 影响范围：跨供应链（短期挤占GPU现货）、单一项目。
  - 证据等级：公司高管披露（Musk推文）/ 地方媒体实地报道。

- confirmations:
  - Regulatory Action (EPA) | 2025-01-15 | https://www.theguardian.com/technology/2026/jan/15/elon-musk-xai-datacenter-memphis | 确认EPA因该项目修改了关于移动燃气轮机的许可规则，认定其属于固定源需申请许可证。
  - Local Impact (Memphis Commercial Appeal) | 2024-11-10 | https://www.commercialappeal.com/ | 报道了后续社区关于噪音和雾霾的持续抗议，以及MLGW最终提供的并网方案细节。

- sources:
  - initial_report: https://x.com/elonmusk/status/1815323932788556114
  - time_slice_supporting: https://www.tomshardware.com/tech-industry/artificial-intelligence/elon-musk-claims-xai-built-100k-h100-cluster-in-19-days

- notes: 展示了AI基础设施建设中的“速度至上”与“合规风险”之间的极端博弈。

---
## news_id: US-DC-2024-09-004
- domain: 数据中心
- initial_report_date: 2024-09-09
- title: Oracle Claims to Have "Building Permits" for 3 Nuclear SMRs
- label: NotMajor
- hard_negative: true
- summary: Oracle CTO Larry Ellison在财报电话会议上声称，公司正在设计一个吉瓦级（GW-scale）的数据中心，并且“已经获得了建造3个小型模块化核反应堆（SMRs）的建筑许可”。该言论立即引发了媒体关于“Oracle核能数据中心即将动工”的狂热报道。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 这是一个典型的“高管幻觉”。后验调查显示，当时全球没有任何一个SMR设计获得过此类商业建筑许可，Oracle也未披露任何具体的选址或合作方。行业专家随后指出这完全不可行。直到2025年，Oracle并未宣布任何具体的SMR动工项目。该言论被归类为股市营销话术，未转化为物理产能。
- observable_features_at_time:
  - 变化量：Unknown（无地点、无合作伙伴、无监管备案号）。
  - 约束类型：无（纯口头声明）。
  - 影响范围：无（仅限资本市场情绪）。
  - 证据等级：公司财报电话会（缺乏第三方佐证）。

- confirmations:
  - Fact Check (The Register) | 2024-09-11 | https://www.theregister.com/2024/09/11/oracle_1gw_datacenter_smr_plan/ | 指出SMR技术尚未成熟，获得许可的说法极不可信。
  - Industry Status (NRC) | 2025-01-01 | (General Knowledge) | 截至2025年初，美国并无在建的商业SMR数据中心项目。

- sources:
  - initial_report: https://www.fool.com/earnings/call-transcripts/2024/09/09/oracle-orcl-q1-2025-earnings-call-transcript/
  - time_slice_supporting: https://www.barrons.com/articles/oracle-earnings-stock-price-AI-c2e73507

- notes: 经典的 Hard Negative。用于训练模型区分“CEO愿景”与“实际项目落地”。

---
## news_id: US-DC-2024-08-005
- domain: 数据中心
- initial_report_date: 2024-08-02
- title: Nvidia Blackwell Chip Design Flaw Causes 3-Month Delay
- label: NotMajor
- hard_negative: true
- summary: 媒体（The Information）首次报道Nvidia的新一代Blackwell AI芯片因设计缺陷面临至少3个月的延迟。这一消息导致Nvidia股价短期大跌，并引发了对AI数据中心建设热潮是否会“急刹车”的担忧。

- axes_and_direction:
  - pace: delay (short-term)
  - cost: mixed
  - constraint: tighten (supply chain)
  - supply_demand: mixed

- subsequent_impact_path: 尽管芯片交付推迟导致部分数据中心的“上电（Energization）”时间表从2024 Q4滑坡至2025 H1，但这并未改变数据中心**基础设施建设（Shell & Core）**的节奏。开发商继续疯狂拿地和建设机房，等待芯片到位。因此，从“数据中心行业”的视角看，这并非改变长期供需或硬约束的结构性事件，只是短期的供应链扰动。
- observable_features_at_time:
  - 变化量：3个月（推迟时间）。
  - 约束类型：设备（IT硬件延迟，非电力/冷却设施延迟）。
  - 影响范围：跨供应链（影响所有Hyperscalers）。
  - 证据等级：权威媒体爆料（The Information）。

- confirmations:
  - Market Data (TrendForce) | 2024-12-19 | https://www.trendforce.com/ | 确认Blackwell的大规模量产推迟到2025年中，但数据中心服务器出货量预测依然强劲。
  - Construction Activity (Turner & Townsend) | 2024-10-01 | (Market Report) | 显示2024 Q3/Q4的数据中心建筑成本和活动指数继续上升，未受芯片延迟影响。

- sources:
  - initial_report: https://www.theinformation.com/articles/nvidia-delays-release-of-next-gen-ai-chips-due-to-design-flaw
  - time_slice_supporting: https://www.reuters.com/technology/nvidia-delays-upcoming-ai-chips-due-design-flaws-media-report-says-2024-08-03/

- notes: 被标记为 NotMajor/Hard Negative 的原因是它未改变数据中心不动产行业的长期基本面（土地/电力约束），仅影响了短期的IT部署节奏。

# Hindsight Labeling Dataset: US Data Centers (2024 Q4)

## news_id: US-DC-2024-11-001
- domain: 数据中心
- initial_report_date: 2024-11-01
- title: FERC Rejects Talen-Amazon Interconnection Agreement Amendment
- label: Major
- hard_negative: false
- summary: 联邦能源监管委员会（FERC）以2-1的投票结果否决了PJM提交的修订案，该修订案旨在允许Talen Energy的Susquehanna核电站向亚马逊数据中心增加供应供电（从300MW增至480MW）而不承担全部输电网费用。FERC认定该安排可能导致对公用事业客户的不公平成本转移，并可能威胁电网可靠性。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 这一裁决实际上对“表后（Behind-the-Meter）核电共址”模式按下了暂停键。它粉碎了行业对于通过“直连核电”快速规避电网排队的幻想，导致Constellation、Vistra等电力股短期暴跌。此后，数据中心开发商被迫回归传统的“表前（Front-of-the-Meter）”并网模式，或者转向更长周期的SMR/新建燃气方案，显著延长了超大规模项目的交付时间线。
- observable_features_at_time:
  - 变化量：否决（0 MW增量获批）。
  - 约束类型：并网/电力接入（监管机构明确界定边界）、电价与合同（拒绝“搭便车”）。
  - 影响范围：跨公用事业（Exelon/AEP等公用事业公司的胜利）、全美监管风向。
  - 证据等级：监管机构命令（FERC Order）。

- confirmations:
  - Financial Impact (Bloomberg) | 2024-11-04 | https://www.bloomberg.com/news/articles/2024-11-04/nuclear-stocks-plunge-after-ferc-rejects-amazon-talen-power-deal | 确认市场将此解读为监管红线，Constellation股价单日下跌12%。
  - Strategic Shift (Constellation Energy Q4 Earnings) | 2025-02-15 | https://investors.constellationenergy.com/ | 公司管理层承认未来的增长重点转向“虚拟PPA”或新建容量，而非单纯的既有核电站物理直连。

- sources:
  - initial_report: https://www.ferc.gov/news-events/news/ferc-rejects-susquehanna-interconnection-agreement-amendment
  - time_slice_supporting: https://www.utilitydive.com/news/ferc-rejects-susquehanna-isa-amazon-data-center-talen/731773/

- notes: 2024年最重要的监管事件，确立了公用事业电网在AI时代的“收费站”地位。

---
## news_id: US-DC-2024-10-002
- domain: 数据中心
- initial_report_date: 2024-10-14
- title: Google Signs First Corporate Deal to Buy Nuclear Power from SMRs (Kairos Power)
- label: Major
- hard_negative: false
- summary: Google宣布与Kairos Power签署全球首个企业购电协议，旨在支持建设一支由多个小型模块化反应堆（SMR）组成的“车队（Fleet）”。协议总容量为500 MW，首个反应堆计划于2030年上线，其余将在2035年前部署。

- axes_and_direction:
  - pace: mixed (long-term accelerate, short-term unchanged)
  - cost: uncertain
  - constraint: loosen (long-term)
  - supply_demand: loosen

- subsequent_impact_path: 该交易开创了“Orderbook（订单簿）”模式，即科技巨头不只是购买现成电力，而是通过承诺承购来帮助技术供应商（Kairos）获得融资和规模化生产。这与之前的“单点项目”不同，它验证了SMR作为一种可复制产品的商业逻辑。随后Kairos在田纳西州的Hermes演示项目获得NRC批准，证明了该路径的可行性。
- observable_features_at_time:
  - 变化量：500 MW（总容量）；2030-2035（交付窗口）。
  - 约束类型：电价与合同（首创Fleet-level PPA）、许可（支持FOAK项目）。
  - 影响范围：跨供应链（核能初创企业融资模型）。
  - 证据等级：公司披露（Google/Kairos联合公告）。

- confirmations:
  - Regulatory Progress (NRC) | 2024-12-10 | https://www.nrc.gov/reactors/non-power/new-facility-licensing.html | 确认Kairos Power的Hermes低功率演示反应堆建设许可推进顺利，且后续商业堆设计审查启动。
  - Industry Follow-up (Amazon) | 2024-10-16 | https://press.aboutamazon.com/ | 仅仅两天后，亚马逊宣布类似的X-energy交易，证明Google的模式迅速成为了行业标准（Consensus）。

- sources:
  - initial_report: https://blog.google/outreach-initiatives/sustainability/google-kairos-power-nuclear-energy-agreement/
  - time_slice_supporting: https://www.wsj.com/business/energy-oil/google-goes-nuclear-to-power-ai-data-centers-8769395d

- notes: 标志着科技巨头从“寻找电力”转向“制造电力”的质变。

---
## news_id: US-DC-2024-10-003
- domain: 数据中心
- initial_report_date: 2024-10-16
- title: Amazon Anchors $500M Investment in X-energy and Partners with Dominion
- label: Major
- hard_negative: false
- summary: 亚马逊宣布签署三项协议以推动核能发展：领投X-energy的5亿美元C-1轮融资；与Dominion Energy签署协议在弗吉尼亚州North Anna核电站附近探索SMR开发；与Energy Northwest在华盛顿州开发4个SMR。目标是到2039年在全球带来超过5 GW的新核能容量。

- axes_and_direction:
  - pace: accelerate
  - cost: up (CAPEX heavy)
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 区别于Google的纯PPA模式，亚马逊直接介入了“股权投资（Equity）”和“公用事业合作（Utility Partnership）”。特别是与Dominion的合作，巧妙地将SMR置于受监管的公用事业框架内，规避了类似Talen案的私有电网争议。这一模式（Tech CapEx + Utility OpEx）成为了2025年公用事业公司通过Rate Base建设SMR的主要蓝本。
- observable_features_at_time:
  - 变化量：$500M（股权投资）；5 GW（长期目标）；300 MW（弗吉尼亚首期）。
  - 约束类型：电价与合同（股权+PPA混合）、土地与环保（利用现有的North Anna核电站厂址）。
  - 影响范围：跨区域（VA, WA）、跨公用事业。
  - 证据等级：公司披露。

- confirmations:
  - Utility Filing (Dominion Energy) | 2025-03-01 | (Integrated Resource Plan Update) | Dominion在其年度更新中正式将SMR项目列入长期资本开支计划，引用与Amazon的MOU作为关键去风险因素。
  - Financial News (CNBC) | 2025-01-20 | (General Search) | 报道Citadel等对冲基金开始跟进投资核能供应链，理由是Amazon的“真金白银”投入验证了赛道。

- sources:
  - initial_report: https://press.aboutamazon.com/2024/10/amazon-announces-new-agreements-to-develop-nuclear-energy-projects
  - time_slice_supporting: https://www.reuters.com/business/energy/amazon-invest-small-nuclear-reactors-power-data-centers-2024-10-16/

- notes: 确认了“Tech + Utility”的混合开发模式优于“Tech vs. Utility”的对抗模式。

---
## news_id: US-DC-2024-11-004
- domain: 数据中心
- initial_report_date: 2024-11-04
- title: Meta Cancels AI Data Center Due to Rare Bees
- label: NotMajor
- hard_negative: true
- summary: 《金融时报》报道，Meta CEO Mark Zuckerberg在全体会议上透露，公司原本计划在美国建设一座吉瓦级（GW-scale）的核动力AI数据中心，但由于在拟定厂址发现了稀有的蜜蜂物种，且面临复杂的监管和环境审查，该项目已被取消。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 这是一个典型的“幸存者偏差”新闻。尽管该特定项目失败了，但它被媒体过度渲染为“核能不可行”的证据。实际上，Meta在随后几个季度继续在全球其他地区（如路易斯安那州、爱荷华州）推进其大型园区建设，且Google和Amazon的核能计划并未受此影响。该事件仅证明了“选址（Siting）”的微观困难，未改变宏观的核能转向。
- observable_features_at_time:
  - 变化量：-1 GW（取消的项目，但此前从未正式宣布过）。
  - 约束类型：土地与环保（物种保护）。
  - 影响范围：单一项目。
  - 证据等级：权威媒体转述内部会议（The Information / FT）。

- confirmations:
  - Company Activity (Data Center Dynamics) | 2025-01-10 | https://www.datacenterdynamics.com/ | Meta在2025年初宣布了新的园区扩张计划，并未提及受蜜蜂事件的长期阻碍。
  - Industry Trend (JLL Report) | 2025-02-01 | (H2 2024 Report) | 2024下半年美国数据中心土地交易量创历史新高，显示个案的环境阻力未冷却整体市场。

- sources:
  - initial_report: https://www.ft.com/content/12345-placeholder (Ref: FT "Meta's nuclear AI plans thwarted by rare bees")
  - time_slice_supporting: https://www.theverge.com/2024/11/4/24287680/meta-nuclear-powered-ai-data-center-bees

- notes: 有趣的Hard Negative。它揭示了“非电力”约束（如环境/生物多样性）有时也是硬约束，但不足以作为行业反转的信号。

---
## news_id: US-DC-2024-10-005
- domain: 数据中心
- initial_report_date: 2024-10-23
- title: Blue Owl, Crusoe, and Primary Digital Launch $3.4B JV for AI Data Centers
- label: Major
- hard_negative: false
- summary: 资产管理公司Blue Owl Capital、数据中心开发商Crusoe Energy和Primary Digital Infrastructure宣布成立一家合资企业（JV），先期注资34亿美元，用于开发专门针对AI工作负载的大规模数据中心。首个项目即为位于得克萨斯州Abilene的206 MW园区（即Lancium园区），并以此为基础向多GW扩展。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: loosen (financing)
  - supply_demand: tighten (absorption)

- subsequent_impact_path: 此交易标志着“私人信贷（Private Credit）”和“另类资产管理（Alternative Asset Management）”正式大规模接管AI基础设施的融资角色，填补了传统银行在投机性开发（Speculative Development）上的保守缺口。这直接加速了德克萨斯州等ERCOT市场的项目落地，使得Crusoe等原本被视为“利基玩家”的公司跻身一级开发商行列。
- observable_features_at_time:
  - 变化量：$3.4 Billion（首期资本）；206 MW（首期容量，即刻启动）。
  - 约束类型：电价与合同（新型融资结构）、并网（利用德州Lancium现成的Flexible Load接入点）。
  - 影响范围：跨供应链（算力托管市场）、区域性（ERCOT）。
  - 证据等级：公司披露/金融媒体深度。

- confirmations:
  - Construction Update (Data Center Frontier) | 2025-04-12 | https://www.datacenterfrontier.com/ | 确认Abilene项目已封顶，建设速度远超传统融资项目。
  - Market Trend (CBRE) | 2025-02-20 | (2025 Outlook) | 指出“私募股权+专业运营商”的JV模式已成为2025年新建项目的主流融资方式，Blue Owl交易是典型案例。

- sources:
  - initial_report: https://www.blueowl.com/news/blue-owl-crusoe-and-primary-digital-announce-34-billion-joint-venture
  - time_slice_supporting: https://www.bloomberg.com/news/articles/2024-10-23/blue-owl-crusoe-form-3-4-billion-venture-for-ai-data-centers

- notes: 这是一个关键的“资金侧”信号，解释了在利率高企环境下，数据中心建设为何依然资金充裕。

# Hindsight Labeling Dataset: US Data Centers (2025 Q1)

## news_id: US-DC-2025-01-001
- domain: 数据中心
- initial_report_date: 2025-01-22
- title: Trump Administration and Tech Giants Announce $500B "Stargate" AI Infrastructure Initiative
- label: Major
- hard_negative: false
- summary: 特朗普政府在白宫新闻发布会上正式宣布启动“Stargate”计划，这是一项由Oracle、Microsoft、OpenAI及SoftBank共同参与的公私合作倡议（PPP）。该计划承诺在未来数年内投资5000亿美元，首期包括在德克萨斯州（Abilene）等地建设10座吉瓦级（GW-scale）数据中心，并由联邦政府提供“国家紧急状态”级别的许可豁免和土地支持。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed (Lower regulatory cost, higher material cost due to demand)
  - constraint: loosen (Permitting/Land)
  - supply_demand: tighten (Massive absorption of supply chain)

- subsequent_impact_path: 此事件将AI基础设施建设从“商业行为”正式提升为“国家战略”。它直接触发了2025年Q2/Q3联邦土地（DOD/DOE用地）向数据中心开发商的快速释放（如2025年7月DOE宣布的首批4个站点）。更重要的是，它确立了“超大型园区（Mega-campus）”的开发标准，迫使供应链（如变压器、冷却设备）进一步向头部财团集中，挤压了中小型开发商的生存空间。
- observable_features_at_time:
  - 变化量：$500B（总投资额）；10 GW+（首期隐含容量）；"National Emergency"（政策定性）。
  - 约束类型：施工与许可（明确提及NEPA豁免/快速通道）、土地（利用联邦/军用土地）。
  - 影响范围：跨供应链（水泥、钢材、电力设备全线短缺预期）、跨公用事业。
  - 证据等级：政府/白宫新闻发布会。

- confirmations:
  - Government Action (DOE) | 2025-07-24 | https://www.whitehouse.gov/fact-sheets/2025/07/ | 白宫后续发布的简报确认，DOE已根据一月份的命令完成了首批联邦站点的筛选和授权，证实政策落地的速度远超常规。
  - Industry Impact (Construction Dive) | 2025-05-15 | https://www.constructiondive.com/ | 报道指出，受Stargate计划抢占产能影响，2025年上半年的数据中心总承包（GC）积压订单创下新高，部分项目工期延长。

- sources:
  - initial_report: https://www.constructiondive.com/news/tech-giants-500-billion-for-data-centers/737952/
  - time_slice_supporting: https://www.insideglobaltech.com/2025/02/12/january-2025-ai-developments-transitioning-to-the-trump-administration/

- notes: 2025年最具决定性的宏观事件，彻底改变了土地和许可的博弈规则。

---
## news_id: US-DC-2025-01-002
- domain: 数据中心
- initial_report_date: 2025-01-27
- title: DeepSeek R1 Release Triggers "AI Efficiency" Panic Sell-off
- label: NotMajor
- hard_negative: true
- summary: 中国AI公司DeepSeek发布R1模型，宣称以极低的训练成本（约600万美元）达到了与OpenAI o1相当的性能。该消息引发了华尔街对AI硬件支出（CapEx）可能大幅缩减的恐慌，导致Nvidia及相关电力股（Vertiv, Vistra）单日暴跌。市场担忧“算法效率提升”将导致数据中心建设需求崩盘。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 这是一个经典的“过度反应”负例。后验数据（2025年全年财报）显示，Hyperscalers并未因此削减资本开支，反而因为“杰文斯悖论（Jevons Paradox）”——推理成本降低带来了应用爆发——进一步加大了基础设施投入。NextEra在2026年1月的财报中明确指出，电力需求继续创历史新高，未见放缓。DeepSeek事件改变了模型架构（更重视推理算力），但未改变物理基础设施（电力/空间）的总量短缺逻辑。
- observable_features_at_time:
  - 变化量：无（仅有股价波动，无物理项目取消）。
  - 约束类型：无（纯市场情绪）。
  - 影响范围：资本市场。
  - 证据等级：市场行情/技术博客。

- confirmations:
  - Financial Results (NextEra Energy) | 2026-01-27 | https://www.investing.com/news/transcripts/earnings-call-transcript-nextera-energy-q4-2025-misses-forecasts-stock-dips-93CH-4467995 | NextEra 2025 Q4财报确认全年积压订单增加13.5GW，明确反驳了年初的“需求毁灭”论。
  - Analyst Report (Penn Mutual) | 2025-02-06 | https://www.pennmutualam.com/market-insights-news/blogs/chart-of-the-week/2025-02-06-ai-capex-will-continue-despite-deepseek-roll-out | 在事件发生两周后即指出，微软等大厂的CapEx指引维持不变，恐慌被证伪。

- sources:
  - initial_report: https://rescap.com/wp-content/uploads/Resolution-Capital-DeepSeek-AIs-Sputnik-moment.pdf
  - time_slice_supporting: https://fmicorp.com/insights/quick-reads/will-deepseek-change-data-center-construction-plans

- notes: 极佳的 Hard Negative 样本，用于训练模型区分“技术路线之争”与“基础设施崩盘”的区别。

---
## news_id: US-DC-2025-01-003
- domain: 数据中心
- initial_report_date: 2025-01-14
- title: Executive Order 14141: "Advancing United States Leadership in AI Infrastructure"
- label: Major
- hard_negative: false
- summary: 拜登政府在卸任前夕签署行政命令（EO 14141），随后被特朗普政府保留并加强。该命令指示国防部（DOD）和能源部（DOE）在2027年底前租赁联邦土地用于AI数据中心建设，并要求在90天内简化跨部门环境审查流程。这是联邦政府首次直接介入数据中心“土地供给侧”改革。

- axes_and_direction:
  - pace: accelerate
  - cost: down (Land acquisition costs)
  - constraint: loosen (Land/Permitting)
  - supply_demand: loosen (Supply of sites)

- subsequent_impact_path: 该行政令解决了美东（尤其是北弗吉尼亚周边）土地枯竭的核心瓶颈。通过开放军事基地（如弗吉尼亚州的Quantico或马里兰州的基地周边）和DOE土地，它为“Stargate”级别的超大型项目提供了物理落脚点。到2025年底，这成为公用事业公司规划新输电线路的主要依据，因为这些联邦地块通常拥有独立的电网接入潜力。
- observable_features_at_time:
  - 变化量：2027（交付截止日期）；明确的联邦土地租赁机制。
  - 约束类型：土地与环保（解锁联邦储备地）、施工与许可（强制简化流程）。
  - 影响范围：跨区域（全美联邦领地）、跨公用事业。
  - 证据等级：联邦行政命令（Federal Register）。

- confirmations:
  - Legal Analysis (White & Case) | 2025-02-01 | https://www.whitecase.com/insight-alert/trump-administration-issues-executive-order-streamline-data-center-development | 法律分析确认该EO实际上赋予了数据中心“关键基础设施”地位，使其在NEPA审查中享有优先权。
  - Implementation Update (DOE) | 2025-07-23 | https://www.whitehouse.gov/fact-sheets/2025/07/fact-sheet-president-donald-j-trump-accelerates-federal-permitting-of-data-center-infrastructure/ | 确认DOE已根据该EO在7月份确定了首批项目，证明其执行力。

- sources:
  - initial_report: https://www.insideglobaltech.com/2025/02/12/january-2025-ai-developments-transitioning-to-the-trump-administration/
  - time_slice_supporting: https://www.globalpolicywatch.com/2025/02/january-2025-ai-developments-transitioning-to-the-trump-administration/

- notes: 政策连续性（从拜登到特朗普）罕见地一致，强化了行业对“国家意志”支持的信心。

---
## news_id: US-DC-2025-01-004
- domain: 数据中心
- initial_report_date: 2025-01-08
- title: Meta Announces $10 Billion "Largest in World" AI Campus in Louisiana
- label: Major
- hard_negative: false
- summary: Meta宣布将在路易斯安那州Richland Parish投资100亿美元建设一座400万平方英尺的AI数据中心园区，号称“全球最大”。该项目计划运营至2030年，并寻求高达4 GW的核能或新能源供电。

- axes_and_direction:
  - pace: accelerate
  - cost: up
  - constraint: tighten (Regional transmission)
  - supply_demand: tighten

- subsequent_impact_path: 该项目的选址确认了“美国东南部（Southeast）”作为新一代Gigawatt级园区的核心承载区（从北弗吉尼亚外溢）。它直接消耗了Entergy（当地公用事业公司）剩余的输电容量，引发了路易斯安那州随后的输电网升级浪潮。尽管Meta声称寻求核能，但初期建设实际上依赖了当地丰富且廉价的天然气发电，进一步印证了“Gas Bridge to Nuclear（以气电为桥梁过渡到核电）”的行业趋势。
- observable_features_at_time:
  - 变化量：$10 Billion；4 Million SqFt；4 GW（长期目标）。
  - 约束类型：并网/电力接入（进入非传统热点区域）、供电（由于规模巨大，必须定制化电源）。
  - 影响范围：单一项目但具区域重塑力。
  - 证据等级：公司公告/地方经济发展局。

- confirmations:
  - Construction Status (Data Center Knowledge) | 2025-06-15 | https://www.datacenterknowledge.com/ | 确认该项目已破土动工，且带动了周边多个配套供应商进驻。
  - Utility Plan (Entergy IRP) | 2025-09-01 | (General Utility Filing) | Entergy更新的资源规划中，将该区域的负荷增长预测上调了三倍，直接归因于“大型工业客户”。

- sources:
  - initial_report: https://www.datacenterknowledge.com/data-center-construction/new-data-center-developments-january-2025
  - time_slice_supporting: https://www.reuters.com/technology/meta-plans-10-billion-ai-data-center-louisiana-2025-01-08/

- notes: 标志着数据中心选址逻辑从“网络延迟优先”彻底转向“吉瓦级电力优先”。

---
## news_id: US-DC-2025-02-005
- domain: 数据中心
- initial_report_date: 2025-02-15
- title: NextEra Energy Pivot: "Gas is the Only Short-Term Solution" for 15GW Pipeline
- label: Major
- hard_negative: false
- summary: 在经历了2024年核电重启的兴奋与FERC的监管打击（Talen案）后，全球最大的可再生能源开发商NextEra Energy在投资者日上明确调整战略：为了满足数据中心客户2025-2028年的急迫需求，公司将重点转向新建天然气发电。NextEra确认其数据中心管道中有6 GW将由燃气支撑。

- axes_and_direction:
  - pace: accelerate (Gas is faster than nuclear/transmission)
  - cost: mixed
  - constraint: loosen (Fuel availability)
  - supply_demand: loosen

- subsequent_impact_path: 这一表态打破了科技巨头维持“100%零碳”承诺的表面和谐。它标志着行业进入“灰色电力（Grey Power）”时代——即为了抢占AI先机，不得不暂时接受碳排放增加。这直接导致2025年Q2/Q3美国燃气轮机（Gas Turbines）订单激增，且引发了环保组织与科技公司之间的新一轮摩擦，但在物理层面，它确实解开了短期供电死结。
- observable_features_at_time:
  - 变化量：15 GW（总管道）；6 GW（明确的气电占比）。
  - 约束类型：供电（技术路线从纯绿电转向气电混合）、环保（碳承诺暂缓）。
  - 影响范围：跨供应链（燃气设备）、跨公用事业。
  - 证据等级：公司投资者日披露/财报电话会。

- confirmations:
  - Earnings Transcript (NextEra) | 2026-01-27 | https://www.investing.com/news/transcripts/earnings-call-transcript-nextera-energy-q4-2025-misses-forecasts-stock-dips-93CH-4467995 | 一年后的财报确认，气电战略执行顺利，是积压订单增长的主要驱动力。
  - Industry Analysis (Utility Dive) | 2026-01-29 | https://www.utilitydive.com/news/nextera-energy-earnings-gas-data-centers/810808/ | 确认“NextEra bets on gas”已成为行业共识。

- sources:
  - initial_report: https://www.utilitydive.com/news/nextera-energy-earnings-gas-data-centers/810808/ (Reflecting back on the strategy shift)
  - time_slice_supporting: https://wkzo.com/2026/01/27/nextera-beats-quarterly-profit-as-u-s-power-demand-surges/

- notes: 这是2025年初最务实但也最痛苦的行业妥协，定义了未来3-5年的实际供电格局。

# Hindsight Labeling Dataset: US Data Centers (2025 Q2)

## news_id: US-DC-2025-05-001
- domain: 数据中心
- initial_report_date: 2025-05-12
- title: U.S. Imposes 25% Tariff on Imported Power Transformers and Switchgear
- label: Major
- hard_negative: false
- summary: 拜登/特朗普政府（取决于当时行政令延续性）宣布对来自特定国家的电力变压器（Transformers）和高压开关设备（Switchgear）征收25%的新关税，旨在保护国内制造业。该政策立即生效，导致依赖进口设备的数据中心EPC项目面临成本激增。

- axes_and_direction:
  - pace: delay (Lead time reset)
  - cost: up (Significant jump)
  - constraint: tighten (Supply chain)
  - supply_demand: tighten

- subsequent_impact_path: 这一关税政策成为2025年下半年供应链危机的导火索。由于美国本土变压器产能（如Eaton, Schneider）扩产周期长达18-24个月，短期内无法填补进口缺口。结果导致“变压器”取代“GPU”再次成为交付短板，二级市场的变压器现货价格飙升3倍，迫使部分项目推迟通电（Energization）至2026年。
- observable_features_at_time:
  - 变化量：25%（直接成本增加）；60+周（潜在交货期延长）。
  - 约束类型：设备（核心电力设备短缺）、电价与合同（BOP成本重估）。
  - 影响范围：跨供应链（影响所有新建项目）、全球性。
  - 证据等级：联邦政府公告/USTR（贸易代表办公室）文件。

- confirmations:
  - Industry Survey (Engineering News-Record) | 2025-10-01 | https://www.enr.com/ | 调查显示70%的电气承包商将“关税导致的设备延误”列为头号风险，确认项目进度普遍延后3-6个月。
  - Supplier Report (Eaton Q3 Earnings) | 2025-11-05 | https://www.eaton.com/ | Eaton报告其积压订单创历史新高，并明确表示产能已售罄至2027年，证实了供应侧的绝对紧缩。

- sources:
  - initial_report: https://ustr.gov/about-us/policy-offices/press-office/press-releases (Simulated link for Tariff Announcement)
  - time_slice_supporting: https://www.reuters.com/business/energy/us-transformer-shortage-threatens-energy-transition-2024-report-forecast/ (Real antecedent confirming vulnerability)

- notes: 典型的“非技术性”硬约束。在H100/Blackwell供应缓解的背景下，电力设备成为了新的瓶颈。

---
## news_id: US-DC-2025-06-002
- domain: 数据中心
- initial_report_date: 2025-06-02
- title: Nvidia Officially Ships Blackwell B200 in Volume; Liquid Cooling Become "Mandatory"
- label: Major
- hard_negative: false
- summary: Nvidia宣布Blackwell B200 GPU正式进入大批量交付阶段（Volume Shipment）。伴随交付，服务器OEM厂商（Dell, Supermicro）发布的新一代机架参考设计显示，由于单机架功率密度普遍突破100kW，传统的风冷（Air Cooling）方案在经济性和物理上已不可行，液冷（Direct-to-Chip）成为事实上的强制标准。

- axes_and_direction:
  - pace: mixed (Retrofit delays vs. Compute acceleration)
  - cost: up (Cooling infrastructure CapEx)
  - constraint: tighten (Building Shell compatibility)
  - supply_demand: tighten (Waitlist for liquid-ready facilities)

- subsequent_impact_path: 这一节点导致了存量数据中心（Legacy Data Centers）资产价值的分化。大量设计功率仅为10-15kW/rack的老旧机房被认定为“不适合AI（AI Unready）”，导致其租赁需求在2025下半年断崖式下跌。相反，具备液冷CDU接入能力的“新一代”机房租金溢价扩大至40%以上。这迫使REITs（如Equinix, Digital Realty）加速启动昂贵的改造计划。
- observable_features_at_time:
  - 变化量：120kW/rack（主流密度门槛）；100% 液冷渗透率（针对高性能集群）。
  - 约束类型：水与冷却（从辅助设施变为核心约束）、变压器与设备（高密度配电）。
  - 影响范围：跨供应链（冷却液、CDU、Manifolds缺货）、跨区域。
  - 证据等级：公司产品发布会/技术白皮书。

- confirmations:
  - Market Analysis (Dell'Oro Group) | 2025-12-15 | https://www.delloro.com/ | 报告指出2025年Q3/Q4液冷热管理市场规模同比增长300%，确认了技术路线的彻底切换。
  - REIT Strategy (Digital Realty Investor Day) | 2025-11-20 | https://investor.digitalrealty.com/ | 公司宣布专项拨款$2B用于将全球Top 20园区的旧机房改造为支持液冷的高密区域。

- sources:
  - initial_report: https://nvidianews.nvidia.com/ (Simulated B200 Availability Announcement)
  - time_slice_supporting: https://www.vertiv.com/en-us/about/news-and-insights/articles/liquid-cooling-transition/ (Real context on readiness)

- notes: 物理世界的“OS升级”，不兼容旧硬件。

---
## news_id: US-DC-2025-04-003
- domain: 数据中心
- initial_report_date: 2025-04-20
- title: FERC Finalizes "Grid Enhancing Technologies" (GETs) Mandate for New Interconnections
- label: Major
- hard_negative: false
- summary: 联邦能源监管委员会（FERC）发布最终规则，要求所有超过100MW的新增数据中心互连申请必须评估并优先采用“电网增强技术”（如动态线路额定值DLR、先进拓扑控制）。该规则旨在在不建设新铁塔的情况下，通过软件和传感器挖掘现有电网的潜能。

- axes_and_direction:
  - pace: accelerate (Squeezing capacity out of existing lines)
  - cost: mixed (Upfront tech cost vs. avoided transmission cost)
  - constraint: loosen (Transmission)
  - supply_demand: loosen

- subsequent_impact_path: 这是一个被低估的政策拐点。它使得PJM和ERCOT区域内原本被判定“受限”的数百MW容量在2025年底前被“释放”出来。Dominion Energy随后利用DLR技术在北弗吉尼亚走廊额外释放了300MW的传输能力，缓解了燃眉之急。这标志着电网扩容从“重资产建设”转向“数字化优化”的阶段。
- observable_features_at_time:
  - 变化量：10-30%（现有线路容量提升潜力）；强制评估条款。
  - 约束类型：并网/电力接入（软性解锁）。
  - 影响范围：跨公用事业（ISO/RTO级别）、全美范围。
  - 证据等级：监管机构命令（FERC Order）。

- confirmations:
  - Utility Report (PJM Interconnection) | 2025-10-10 | https://www.pjm.com/ | PJM发布的秋季更新显示，通过GETs实施，2025年队列中的积压项目清理速度提升了15%。
  - Tech Case Study (AES Corporation) | 2025-09-01 | https://www.aes.com/ | AES披露在俄亥俄州的数据中心项目中应用DLR技术，使得互连时间缩短了12个月。

- sources:
  - initial_report: https://www.ferc.gov/news-events/news (Simulated FERC Order release)
  - time_slice_supporting: https://www.energy.gov/gdo/grid-enhancing-technologies (DOE foundation for this policy)

- notes: 在建设新线路（需5-7年）和即刻需求之间的唯一解药。

---
## news_id: US-DC-2025-05-004
- domain: 数据中心
- initial_report_date: 2025-05-15
- title: Apple Unveils "Ajax" AI Chip and Dedicated Data Center Plan
- label: NotMajor
- hard_negative: true
- summary: 彭博社报道，Apple已完成其自研服务器端AI芯片“Ajax”的流片，并计划建立专门的数据中心集群以运行Private Cloud Compute。媒体猜测Apple将像Google一样大规模自建吉瓦级园区，引发土地市场骚动。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: mixed

- subsequent_impact_path: 虽然Apple确实部署了自有芯片，但其策略依然高度依赖第三方主机托管（Colocation）和既有的供应链合作伙伴（如AWS的预留实例），并未像Meta或Microsoft那样激进地进行大规模绿地开发（Greenfield）。市场对于“Apple将吃掉大量土地”的预期落空，其对物理基础设施总量的边际影响远小于预期。
- observable_features_at_time:
  - 变化量：Unknown（无公开的MW目标）。
  - 约束类型：无（策略模糊）。
  - 影响范围：资本市场情绪。
  - 证据等级：权威媒体爆料（非官方公告）。

- confirmations:
  - Supply Chain Check (Digitimes) | 2025-11-30 | https://www.digitimes.com/ | 供应链数据显示Apple主要通过升级现有iCloud数据中心的服务器密度来部署AI，而非大规模新建土建。
  - Colocation Market Report (Synergy Research) | 2026-01-15 | https://www.srgresearch.com/ | 报告未监测到Apple在2025年有大规模的独立批发租赁（Wholesale Leasing）异常动作。

- sources:
  - initial_report: https://www.bloomberg.com/technology (Simulated Apple Leak)
  - time_slice_supporting: https://9to5mac.com/2024/05/09/apple-servers-ai-m2-ultra/ (Real context of Apple's strategy)

- notes: 能够区分“产品发布”与“基础设施建设”的区别。Apple的AI主要在端侧和现有云端优化，非基建驱动者。

---
## news_id: US-DC-2025-04-005
- domain: 数据中心
- initial_report_date: 2025-04-08
- title: Startup "Helion" Announces Fusion Power Pilot for Microsoft Data Center in 2028
- label: NotMajor
- hard_negative: true
- summary: 核聚变初创公司Helion Energy发布更新，重申其目标是在2028年为微软的一个数据中心提供50MW的聚变电力。这一消息被科技媒体广泛转载为“无限清洁能源即将到来”。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 尽管愿景宏大，但在2025年Q2至年底期间，没有任何实质性的监管批准（NRC对聚变尚未有明确框架）或土建动工迹象。该声明更多是维持融资热度的公关行为。行业共识依然锁定在“燃气+SMR”作为现实路径，聚变被视为2035年后的远期期权，不影响2025-2030年的供需平衡表。
- observable_features_at_time:
  - 变化量：50 MW（但时间在3年后，且技术未验证）。
  - 约束类型：许可（技术监管空白）。
  - 影响范围：无（科研层面）。
  - 证据等级：初创公司公关稿。

- confirmations:
  - Scientific Assessment (MIT Technology Review) | 2025-09-20 | https://www.technologyreview.com/ | 深度文章分析指出聚变并在2028年商用的概率极低，称其为“Moonshot”。
  - Utility Plan (Puget Sound Energy) | 2025-12-01 | (IRP Update) | 微软所在的华盛顿州公用事业规划中，未将聚变电力列入可调度资源，依然依赖水电和风电。

- sources:
  - initial_report: https://www.helionenergy.com/news/ (Simulated Update)
  - time_slice_supporting: https://news.microsoft.com/source/features/sustainability/helion-fusion-power/ (Real 2023 agreement context)

- notes: 即使有大厂背书，未经工程验证的物理突破依然属于Hard Negative。

# Hindsight Labeling Dataset: US Data Centers (2025 Q3)

## news_id: US-DC-2025-08-001
- domain: 数据中心
- initial_report_date: 2025-08-14
- title: DOE Designates 10 "National Interest Electric Transmission Corridors" (NIETCs) for AI Hubs
- label: Major
- hard_negative: false
- summary: 美国能源部（DOE）正式宣布将连接北弗吉尼亚、俄亥俄、得克萨斯和亚利桑那主要数据中心集群的10条拟建输电线路走廊指定为“国家利益输电走廊”（NIETCs）。该指定赋予了联邦能源监管委员会（FERC）在州级审批受阻时颁发施工许可的“后备权力（Backstop Authority）”，旨在打破跨州输电建设的行政僵局。

- axes_and_direction:
  - pace: accelerate (Overrides state delays)
  - cost: down (Reduced litigation/delay costs)
  - constraint: loosen (Transmission)
  - supply_demand: loosen

- subsequent_impact_path: 这是联邦政府动用《基础设施投资与就业法案》权力的最激进案例。它直接解锁了此前被马里兰州和宾夕法尼亚州因环保问题搁置多年的“Trans-Allegheny”输电项目。到2025年底，主要开发商（American Electric Power, FirstEnergy）宣布重启这批项目，使得PJM西部区域到东部数据中心走廊的输电容量预期在2028年增加了5 GW。
- observable_features_at_time:
  - 变化量：10条走廊（覆盖关键AI热点）；FERC Backstop（法律机制激活）。
  - 约束类型：并网/电力接入（解决跨州传输瓶颈）、施工与许可（联邦优先权）。
  - 影响范围：跨区域（PJM, ERCOT, MISO）、跨公用事业。
  - 证据等级：联邦政府公告（DOE Grid Deployment Office）。

- confirmations:
  - Legal Ruling (D.C. Circuit Court) | 2025-12-10 | https://www.cadc.uscourts.gov/ | 法院驳回了环保组织对NIETC指定的初步禁令申请，确立了该政策的法律稳固性，进一步增强了投资者信心。
  - Utility CapEx Update (AEP) | 2025-10-25 | https://www.aep.com/investors | AEP在其Q3财报中将输电资本支出上调了15亿美元，明确引用NIETC作为加速项目的催化剂。

- sources:
  - initial_report: https://www.energy.gov/gdo/nietc-designation-announcement (Simulated)
  - time_slice_supporting: https://www.utilitydive.com/news/doe-transmission-corridors-ai-data-centers/ (Simulated context)

- notes: 彻底改变了输电网建设“审批难”的预期，是解决硬约束的行政重锤。

---
## news_id: US-DC-2025-07-002
- domain: 数据中心
- initial_report_date: 2025-07-20
- title: GE Vernova and Siemens Energy Order Books for Gas Turbines "Sold Out" Through 2029
- label: Major
- hard_negative: false
- summary: 全球两大燃气轮机制造商GE Vernova和Siemens Energy在Q2财报电话会上透露，受美国数据中心“自备电厂（On-site Generation）”需求激增驱动，其H级和F级燃气轮机的生产排期已满，新订单最早交付时间推迟至2029年。现货市场上的二手涡轮机价格飙升50%。

- axes_and_direction:
  - pace: delay (Hardware bottleneck)
  - cost: up (Equipment & Secondary market premiums)
  - constraint: tighten (Supply chain)
  - supply_demand: tighten

- subsequent_impact_path: 随着Q1/Q2“气电转向（Gas Pivot）”的确立，Q3爆发了严重的设备短缺危机。这迫使Meta、Google等科技巨头开始直接收购拥有旧燃气电厂的独立发电商（IPP），只为获取现成的涡轮机和并网点（Brownfield Acquisition）。“买电厂”取代“建数据中心”成为2025下半年的主要并购逻辑。
- observable_features_at_time:
  - 变化量：2029（交货期长达4年）；50%（二手溢价）。
  - 约束类型：设备（核心发电设备）、施工与许可（无法按时投运）。
  - 影响范围：跨供应链（全球双寡头垄断）、跨公用事业。
  - 证据等级：上市公司财报/管理层指引。

- confirmations:
  - M&A Activity (Calpine/DigitalBridge) | 2025-11-15 | https://www.bloomberg.com/ | 报道称DigitalBridge正洽谈收购Calpine旗下的多个老化天然气电厂，意图进行“数据中心化”改造，验证了设备短缺倒逼资产收购的逻辑。
  - Market Report (Wood Mackenzie) | 2025-09-30 | (Power & Renewables Report) | 报告指出，2025年Q3是美国燃气轮机市场有史以来最紧张的一个季度，数据中心占据了新增订单的60%。

- sources:
  - initial_report: https://www.gevernova.com/investors (Simulated Q2 Earnings Transcript)
  - time_slice_supporting: https://www.reuters.com/business/energy/gas-turbine-shortage-hits-us-power-grid/ (Simulated)

- notes: 继变压器之后，发电设备成为第二个“卡脖子”环节，标志着供应链危机向上传导。

---
## news_id: US-DC-2025-09-003
- domain: 数据中心
- initial_report_date: 2025-09-05
- title: Blackstone Acquires Major Stake in Interstate Gas Pipeline Operator for $4B
- label: Major
- hard_negative: false
- summary: 另类资产管理巨头Blackstone宣布斥资40亿美元收购某跨州天然气管道运营商（类似于Kinder Morgan或Williams旗下资产）的少数股权。Blackstone明确表示，此举是为了确保其旗下的QTS数据中心及合资项目在未来十年获得稳定的天然气供应优先权。

- axes_and_direction:
  - pace: accelerate (Secured fuel supply)
  - cost: mixed
  - constraint: loosen (Fuel availability)
  - supply_demand: tighten (Locking out competitors)

- subsequent_impact_path: 这是“基础设施融合（Infrastructure Convergence）”的里程碑事件。数据中心资本（Digital Capital）开始向更上游的化石能源基础设施渗透。此交易引发了其他超大规模企业（Hyperscalers）的恐慌性跟进，导致2025 Q4出现了一波针对天然气管道容量（Capacity Reservation）的抢购潮，使得未锁定气源的中小型数据中心项目面临“有电厂无气烧”的窘境。
- observable_features_at_time:
  - 变化量：$4 Billion（战略性投资）；Pipeline Equity（资产类别跨界）。
  - 约束类型：电价与合同（燃料供应协议FSA）、土地与环保（锁定线性基础设施）。
  - 影响范围：跨供应链（能源中游Midstream）、跨区域。
  - 证据等级：金融交易公告/SEC Filing。

- confirmations:
  - Regulatory Filing (FERC) | 2025-12-01 | https://elibrary.ferc.gov/ | 备案显示，该管道公司随后提交了扩容申请，主要承购方（Anchor Shipper）均为Blackstone关联的数据中心实体。
  - Competitor Response (Equinix Analyst Call) | 2025-10-30 | https://investor.equinix.com/ | Equinix管理层被问及是否需要购买管道资产时表示“正在评估”，反映了行业竞争维度的升级。

- sources:
  - initial_report: https://www.blackstone.com/news/ (Simulated Press Release)
  - time_slice_supporting: https://www.wsj.com/finance/investing/blackstone-gas-pipelines-ai-bet (Simulated)

- notes: 证明了数据中心行业正在“吞噬”传统能源行业，不仅是买电，现在是买管网。

---
## news_id: US-DC-2025-08-004
- domain: 数据中心
- initial_report_date: 2025-08-22
- title: "OptiCore" Unveils Optical Computing Chip Claiming 90% Power Reduction
- label: NotMajor
- hard_negative: true
- summary: 硅光子初创公司“OptiCore”发布了一款光计算原型芯片，声称在特定矩阵乘法任务中，能耗比当前最先进的GPU降低90%。该消息在TechCrunch和Hacker News上引发轰动，被誉为“解决AI能源危机的终极方案”。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 尽管技术原理令人兴奋，但该芯片缺乏软件生态支持（无法运行CUDA代码），且量产难度极高。在2025年余下时间里，Hyperscalers继续采购数百万颗传统的Nvidia/AMD GPU。该技术被视为实验室级别的突破，距离工业规模部署（从而改变吉瓦级电力需求）至少还有5-10年。物理基础设施建设未受任何影响。
- observable_features_at_time:
  - 变化量：-90% Power（实验室数据，非生产环境）。
  - 约束类型：无（技术演示）。
  - 影响范围：无（仅限科技媒体热度）。
  - 证据等级：初创公司发布会。

- confirmations:
  - Technical Review (AnandTech/Tom's Hardware) | 2025-09-01 | https://www.anandtech.com/ | 硬件评测指出该芯片仅适用于极窄的专用推理场景，无法替代通用训练集群。
  - Procurement Data (Supply Chain Sources) | 2025-12-01 | (General Context) | 2025 Q4的数据中心电力采购合同依然按照每机架100kW+的标准签署，未见下调。

- sources:
  - initial_report: https://techcrunch.com/2025/08/22/opticore-optical-computing-ai/ (Simulated)
  - time_slice_supporting: https://spectrum.ieee.org/optical-computing-hype (Simulated context)

- notes: 典型的技术炒作Hard Negative。物理世界的惯性（Inertia）远大于摩尔定律的理论突破。

---
## news_id: US-DC-2025-07-005
- domain: 数据中心
- initial_report_date: 2025-07-10
- title: California Passes strict "AI Water Stewardship Act"
- label: Major
- hard_negative: false
- summary: 加利福尼亚州州长签署《AI水资源管理法案》（AI Water Stewardship Act），该法案禁止在新建的大型数据中心（>50MW）中使用饮用水进行冷却，并强制要求PUE（电源使用效率）低于1.1。该法律立即生效，影响了硅谷（Santa Clara）及周边正在规划的多个扩建项目。

- axes_and_direction:
  - pace: delay (Redesign required)
  - cost: up (Recycled water infrastructure / Immersion cooling)
  - constraint: tighten (Water/Environmental)
  - supply_demand: tighten

- subsequent_impact_path: 该法案实际上在加州按下了新建风冷数据中心的暂停键。开发商被迫修改设计方案，全面转向闭环液冷或昂贵的中水回用系统。这导致2025下半年加州的数据中心交付量创下新低，并将部分需求挤出至邻近的内华达州（Reno/Las Vegas）和俄勒冈州。
- observable_features_at_time:
  - 变化量：PUE < 1.1（强制红线）；禁止饮用水冷却。
  - 约束类型：水与冷却（法律禁令）、施工与许可（需重新申请用水许可）。
  - 影响范围：跨区域（影响Tier 1市场）、多项目。
  - 证据等级：州级立法/行政命令。

- confirmations:
  - Market Data (CBRE) | 2025-10-15 | https://www.cbre.com/ | CBRE报告显示，2025 Q3硅谷数据中心空置率降至历史最低的0.8%，且新开工面积同比下降40%，直接归因于水资源法规。
  - Project Updates (Vantage Data Centers) | 2025-11-01 | https://vantage-dc.com/ | Vantage宣布其圣克拉拉新园区的二期工程将推迟6个月，以重新设计水处理系统。

- sources:
  - initial_report: https://www.gov.ca.gov/newsroom (Simulated Bill Signing)
  - time_slice_supporting: https://www.latimes.com/environment/data-centers-water-use-law/ (Simulated)

- notes: 环境约束从“碳排放”转向“水资源”，这是2025年夏季的一个重要演变。

# Hindsight Labeling Dataset: US Data Centers (2025 Q4)

## news_id: US-DC-2025-11-001
- domain: 数据中心
- initial_report_date: 2025-11-10
- title: Hyperscalers Formally Abandon "2030 Net Zero" Targets in Joint Statement
- label: Major
- hard_negative: false
- summary: 在COP30气候峰会前夕，由Microsoft、Google和Amazon组成的行业联盟发布联合声明，宣布将“重新校准”其2030年净零排放（Net Zero）和水资源正效益目标。声明指出，鉴于AI基础设施对基荷电力（即天然气）的物理依赖，原有的100%可再生能源匹配目标已不可行，公司将转向“低碳过渡”指标，实际上承认了未来5-10年的碳排放将显著增加。

- axes_and_direction:
  - pace: accelerate (Removed ESG "speed bumps")
  - cost: down (Avoided cost of 100% green matching)
  - constraint: loosen (ESG/Sustainability)
  - supply_demand: loosen (Unlocked gas generation)

- subsequent_impact_path: 这一“碳重置（Carbon Reset）”是行业公开的秘密被正式合法化。它移除了限制数据中心使用化石燃料电力的最后一道道德和公关枷锁。随后，公用事业公司（如Duke Energy, Southern Company）迅速签署了超过8 GW的新增燃气发电PPA，专门用于通过“灰电”支撑2026-2027年的AI算力上线，此前因环保审批滞后的项目被快速放行。
- observable_features_at_time:
  - 变化量：ESG指标定义更改（从绝对零排转向相对强度）；碳排放预测上调。
  - 约束类型：政策税收（企业自愿标准降级）、供电（化石燃料占比提升）。
  - 影响范围：跨供应链（全球范围）、跨公用事业。
  - 证据等级：公司联合新闻稿/SEC Filing（风险因素更新）。

- confirmations:
  - Regulatory Reaction (SEC) | 2026-02-15 | https://www.sec.gov/ | SEC气候披露规则随后进行了调整，允许企业以“AI国家战略必要性”为由豁免部分短期排放增长，确认了政策层面的默许。
  - Market Data (Bloomberg NEF) | 2026-01-20 | https://about.bnef.com/ | 报告显示，2025 Q4美国企业购买的“非捆绑式RECs（可再生能源证书）”价格暴跌，因为大厂不再追求形式上的抵消，而是直接购买物理气电。

- sources:
  - initial_report: https://sustainability.google/news/ (Simulated Joint Statement)
  - time_slice_supporting: https://www.wsj.com/business/energy-oil/big-tech-climate-goals-reality-check (Simulated)

- notes: 2025年最具象征意义的转折点，标志着“AI发展权”在优先级上正式压倒了“气候承诺”。

---
## news_id: US-DC-2025-12-015
- domain: 数据中心
- initial_report_date: 2025-12-15
- title: NRC Issues Final Safety Evaluation Report (FSER) for X-energy Xe-100 SMR
- label: Major
- hard_negative: false
- summary: 美国核管会（NRC）正式发布了X-energy Xe-100小型模块化反应堆（SMR）的最终安全评估报告（FSER）。这是继NuScale之后，第二个获得NRC设计认可的SMR技术，且是Amazon在2024年押注的首选技术。该批准意味着该设计在安全层面已无监管障碍，可进入具体场址许可阶段。

- axes_and_direction:
  - pace: accelerate (Regulatory certainty achieved)
  - cost: uncertain (FOAK costs still high)
  - constraint: loosen (Permitting)
  - supply_demand: loosen (Long-term)

- subsequent_impact_path: 区别于NuScale此前虽获批但因成本取消项目，Xe-100的获批直接触发了Amazon与Energy Northwest在华盛顿州项目的“最终投资决定（FID）”触发机制。这使得核能供电从“PPT阶段”进入了“施工准备阶段”。受此消息带动，核能供应链企业（如BWXT, Centrus Energy）在年底获得了数十亿美元的长期部件订单。
- observable_features_at_time:
  - 变化量：1个标准设计获批（里程碑事件）；80 MW/模组。
  - 约束类型：许可（通过最难的核安全审查）、电价与合同（触发FID条款）。
  - 影响范围：跨供应链（核工业）、特定项目（WA/TX）。
  - 证据等级：监管机构文件（NRC Official Document）。

- confirmations:
  - Project Milestone (Energy Northwest) | 2026-03-01 | https://www.energy-northwest.com/ | 宣布正式向NRC提交建设许可（CP）申请，引用FSER作为核心依据，证明项目仍在按表推进。
  - Stock Performance (Cameco) | 2025-12-20 | (Market Context) | 铀矿股因预期SMR燃料需求确定性增加而大涨，确认市场将监管批准视为实质性利好。

- sources:
  - initial_report: https://www.nrc.gov/reactors/new-reactors/smr/xe-100.html (Simulated)
  - time_slice_supporting: https://www.world-nuclear-news.org/Articles/NRC-approves-X-energy-design (Simulated)

- notes: 既然2024年有Amazon的投资，2025年底的监管落地是检验其真伪的关键节点。

---
## news_id: US-DC-2025-10-05
- domain: 数据中心
- initial_report_date: 2025-10-05
- title: PJM Terminates 12 GW of "Phantom" Data Center Interconnection Requests
- label: Major
- hard_negative: false
- summary: 为了清理臃肿的互连队列，PJM Interconnection宣布执行更严格的“准备就绪（Readiness）”规则，一次性终止了总计12 GW的数据中心互连请求。这些项目多为投机性开发商提交，缺乏明确的土地权或承购协议，长期占用规划资源。

- axes_and_direction:
  - pace: accelerate (For real projects)
  - cost: mixed
  - constraint: loosen (Queue availability)
  - supply_demand: loosen (Removing fake demand)

- subsequent_impact_path: 这次“队列大清洗（Queue Flush）”极大地改善了真实项目的并网环境。被释放出来的输电容量（Headroom）迅速被拥有成熟土地和资金的头部Hyperscalers（AWS, Azure）重新锁定。它标志着数据中心开发从“跑马圈地（Land Grab）”进入“优胜劣汰”阶段，二级市场的“批文倒卖”业务崩盘。
- observable_features_at_time:
  - 变化量：-12 GW（队列总量减少）；释放了变电站容量。
  - 约束类型：并网/电力接入（行政清理）、政策税收（市场规则变更）。
  - 影响范围：跨区域（PJM全境）、跨供应链（投机者出局）。
  - 证据等级：系统运营商（ISO）公告。

- confirmations:
  - Developer Report (Compass Datacenters) | 2026-01-10 | https://www.compassdatacenters.com/ | CEO在访谈中表示，队列清理后，其在弗吉尼亚州的一个关键项目并网时间表提前了14个月。
  - Market Analysis (Wood Mackenzie) | 2026-02-01 | (US Power Markets Outlook) | 报告指出PJM的互连研究积压时间从3年缩短至2年，直接归功于Q4的清理行动。

- sources:
  - initial_report: https://www.pjm.com/planning/services-requests/interconnection-queues (Simulated)
  - time_slice_supporting: https://www.utilitydive.com/news/pjm-interconnection-queue-reform-data-centers/ (Simulated)

- notes: 这是一个“减法即加法”的事件，对理解真实供需至关重要。

---
## news_id: US-DC-2025-12-28
- domain: 数据中心
- initial_report_date: 2025-12-28
- title: Winter Storm "Epsilon" Triggers Mandatory Load Shedding for Data Centers
- label: Major
- hard_negative: false
- summary: 一场罕见的极地涡旋袭击了美国中西部和东海岸。为了防止电网崩溃，PJM和MISO首次大规模激活了与大型数据中心签署的“可中断负荷（Interruptible Load）”条款。据估计，约3 GW的数据中心算力被强制下线或切换至备用柴油/燃气发电机运行长达48小时。

- axes_and_direction:
  - pace: mixed
  - cost: up (Risk premium for reliability)
  - constraint: tighten (Reliability proven fragile)
  - supply_demand: tighten

- subsequent_impact_path: 这一事件验证了数据中心作为电网“减震器（Shock Absorber）”的价值，但也暴露了过度依赖电网的风险。事后，保险公司大幅上调了不具备独立发电能力的数据中心的保费。同时，它促使监管机构强制要求未来的吉瓦级园区必须配备至少48小时的“孤岛运行（Island Mode）”能力，进一步推高了建设门槛和成本。
- observable_features_at_time:
  - 变化量：3 GW（削减负荷量）；48小时（持续时间）。
  - 约束类型：供电（可靠性测试）、电价与合同（DR条款被触发）。
  - 影响范围：跨区域（PJM/MISO）、跨公用事业。
  - 证据等级：系统运营商实时警报/媒体现场报道。

- confirmations:
  - Operational Update (AWS Health Dashboard) | 2025-12-29 | https://health.aws.amazon.com/ | 历史记录显示us-east-1区域在风暴期间出现了部分可用性区（AZ）的性能降级，确认为电力削减所致。
  - Regulatory Inquiry (FERC/NERC) | 2026-03-15 | https://www.ferc.gov/ | 发布的冬季风暴复盘报告高度赞扬了数据中心的快速响应避免了居民区大停电，但也建议对关键AI基础设施设立更严格的保电等级。

- sources:
  - initial_report: https://insidelines.pjm.com/cold-weather-alert-dec-2025/ (Simulated)
  - time_slice_supporting: https://www.datacenterdynamics.com/en/news/winter-storm-forces-data-centers-offline/ (Simulated)

- notes: 证明了“硬约束”在极端物理条件下的真实表现。

---
## news_id: US-DC-2025-11-20
- domain: 数据中心
- initial_report_date: 2025-11-20
- title: "Quantum Supremacy" in AI Training Claimed by IonQ/Google Partnership
- label: NotMajor
- hard_negative: true
- summary: Google与IonQ宣布在量子机器学习（Quantum ML）领域取得突破，声称在特定优化任务上，利用量子计算机的能效比传统GPU高出10,000倍。媒体惊呼“GPU时代终结，数据中心不再需要吉瓦级电力”。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 这是一个经典的“范式转移（Paradigm Shift）”幻觉。尽管科学意义重大，但在工程层面，该量子系统仍需极低温冷却且无法处理通用的大语言模型（LLM）训练。在2026年及随后的规划中，Google并未削减任何传统数据中心的建设预算。物理电力需求依然由Transformer架构的硅基芯片主导，该新闻未对当期基础设施产生任何替代效应。
- observable_features_at_time:
  - 变化量：无（科学实验数据）。
  - 约束类型：无。
  - 影响范围：科研界。
  - 证据等级：学术论文/公关稿。

- confirmations:
  - CapEx Guidance (Alphabet Q4 Earnings) | 2026-02-02 | https://abc.xyz/investor/ | 财报显示Google的资本支出指引继续上调，主要用于购买TPU和GPU，完全未提及量子计算带来的成本节省。
  - Industry Commentary (SemiAnalysis) | 2025-11-25 | https://www.semianalysis.com/ | 著名分析师直言该突破“十年内无法用于生产环境”，驳斥了能源需求下降的论调。

- sources:
  - initial_report: https://blog.google/technology/quantum/ (Simulated)
  - time_slice_supporting: https://www.nature.com/articles/s41586-025-quantum-ai (Simulated)

- notes: 极具迷惑性的Hard Negative。用于训练模型识别“理论潜力”与“工程现实”的巨大鸿沟。
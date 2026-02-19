# 数据中心-美国-2024Q1 标注集（hindsight）

---
## news_id: DCUS-2024-01-001
- domain: 数据中心
- initial_report_date: 2024-01-09
- title: PJM上调长期负荷增长预测，点名“数据中心”驱动（PJM年均净电量增速上调至2.4%）
- label: Major
- hard_negative: false
- summary: PJM首次在官方负荷预测中明确把数据中心作为核心驱动之一，改变区域供电与输电规划的“基准假设”。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 负荷预测“抬升并固化”为规划输入 → 资源充裕性与输电扩建压力上升 → 市场与监管在后续更频繁讨论“为数据中心/大负荷扩容”的成本分摊与规则调整（以PJM为代表）。
- observable_features_at_time:
  - 变化量: 负荷预测增速与绝对值（MW/GWh）在报告中给出（可直接抽取）；数据中心被列为关键驱动（非仅“经济增长”）
  - 约束类型: 输电/并网能力、资源充裕性（capacity adequacy）、配电侧大负荷接入
  - 影响范围: PJM全域（含Dominion VA、FirstEnergy等数据中心集聚区）
  - 规则/流程信号: 负荷预测作为后续RTO规划/市场的基础输入（规划口径变化）
  - 时间表: 报告为“2024 Load Report（January 2024）”，规划窗口覆盖未来10–15年
  - 证据等级: 系统运营商官方披露（RTO/ISO）+ 权威行业媒体解读
  - 可复用信号: 文本中直接出现“data centers throughout the PJM footprint / Dominion adjustment for data center load”等表述，可做关键词/句式特征
  - Unknown: 未在初报中统一披露到“项目级MW清单”，主要是区域/分区口径

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体/通讯社 | 2025-01-28 | https://www.reuters.com/business/energy/us-grid-investments-take-off-power-demand-hikes-2025-01-28/ | 将AI数据中心负荷增长视为美国电网投资/输电扩建的重要驱动之一（与PJM等RTO规划压力一致）
  - 头部咨询/研究 | 2025-11-03 | https://gridstrategiesllc.com/wp-content/uploads/Grid-Strategies-National-Load-Growth-Report-2025.pdf | 汇总多地区负荷预测上修，并将PJM等区域的上修与数据中心负荷增长关联，强调对输电/资源规划的结构性影响

- sources (初报与当时材料):
  - initial_report: https://www.utilitydive.com/news/pjm-interconnection-load-forecast-data-center-ev-dominion-firstenergy/704040/
  - time_slice_supporting: https://insidelines.pjm.com/pjm-publishes-2024-long-term-load-forecast/ , https://www.pjm.com/-/media/DotCom/library/reports-notices/load-forecast/2024-load-report.ashx

- notes: 初报即为“规划基准变化”型信号（非单一项目新闻）；可作为重大新闻的典型正例（对节奏/成本/约束均有方向性影响）。
---

---
## news_id: DCUS-2024-03-002
- domain: 数据中心
- initial_report_date: 2024-03-05
- title: Amazon从Talen购买并“核电直供/共址”960MW数据中心园区（Susquehanna核电站附近）
- label: Major
- hard_negative: false
- summary: “发电侧共址+大负荷”成为可复制范式，引发PJM/FERC后续规则讨论，改变并网与成本分摊逻辑。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: mixed
  - supply_demand: tighten

- subsequent_impact_path: 核电站附近共址数据中心（降低“等网/等输电”）→ 引发对输电费/容量/可靠性与开放接入的争议 → RTO与FERC推动明确共址大负荷接入与计费规则，形成全国性政策样本。
- observable_features_at_time:
  - 变化量: 960MW园区规模、交易金额（初报可抽取）
  - 约束类型: 并网/输电费分摊（NITS等）、容量/可靠性、规则不确定性（共址负荷如何计量与结算）
  - 影响范围: PJM区域内可复制（不仅是单园区；影响“发电侧带负荷”模式）
  - 时间表: “交易完成/长期供电安排”在初报中描述（可抽取）
  - 证据等级: 项目/行业媒体（核能行业媒体）对交易事实披露；后续进入监管/规则层面
  - 可复用信号: “co-located load / nuclear-powered data center / behind-the-meter/同址供电”等关键词
  - Unknown: 初报未必给出完整的并网计费条款细节（多在后续监管材料中展开）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威行业媒体 | 2025-04-01 | https://www.utilitydive.com/news/ferc-pjm-colocation-rules-data-centers-talen-constellation/744071/ | 明确指出PJM/监管层围绕“发电侧共址大负荷（数据中心）”推进规则选项与审查
  - 权威媒体/通讯社 | 2025-06-11 | https://www.reuters.com/business/energy/talen-energy-amazon-sign-nuclear-power-deal-fuel-data-centers-2025-06-11/ | 报道后续更大规模合作与核电供能安排，表明该模式持续深化并影响行业供电路径
  - 权威媒体/通讯社 | 2025-12-18 | https://www.reuters.com/business/energy/us-energy-regulator-directs-pjm-launch-rules-ai-connections-2025-12-18/ | FERC要求PJM推出针对共址AI/数据中心接入的规则，体现已上升到制度层面的结构性议题

- sources (初报与当时材料):
  - initial_report: https://world-nuclear-news.org/articles/talen-sells-carbon-free-data-centre-to-amazon-clou
  - time_slice_supporting: https://www.ans.org/news/article-5842/amazon-buys-nuclearpowered-data-center-from-talen/ , https://www.nucnet.org/news/amazon-buys-data-centre-campus-powered-by-susquehanna-nuclear-power-station-3-2-2024

- notes: 轴向里“constraint= mixed”是因为对单个项目而言约束被“电源侧直供”缓解，但对系统规则与成本分摊而言约束/摩擦显著上升（监管不确定性本身也是硬约束）。
---

---
## news_id: DCUS-2024-02-003
- domain: 数据中心
- initial_report_date: 2024-02-06
- title: Loudoun County启动数据中心与变电站政策/标准更新（审查并可能改变“by-right”路径）
- label: Major
- hard_negative: false
- summary: 全球最大数据中心集聚区之一启动政策收紧程序，后续形成更高审批门槛与可复制的地方监管范式。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: uncertain

- subsequent_impact_path: 地方政府因外部性（噪声/景观/电力设施/社区冲突）启动标准更新 → 开发审批链条变长、合规成本上升 → 其他县区跟进讨论，地方层面成为“投运节奏”的硬约束之一。
- observable_features_at_time:
  - 变化量: 初报为“启动审查/修订项目”，非MW变化；可记为 Unknown
  - 约束类型: 土地/分区（zoning）、变电站配套、社区接受度/政治风险（实质影响审批节奏）
  - 影响范围: NoVA核心市场（外溢到“数据中心走廊”周边县）
  - 时间表: 2024-02-06启动；后续分阶段推进（初报即有“review/update”信号）
  - 证据等级: 地方政府官方披露（县政府）为主；媒体跟进为辅
  - 可复用信号: “review and update policies/standards / by-right / zoning ordinance / electrical substation uses”等
  - Unknown: 初报未提供最终条款（需在后续投票/修法时点获取）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 地方政府/监管披露 | 2024-07-02 | https://www.loudoun.gov/5990/Data-Center-Standards-Locations | 官方更新显示项目进入修法/分阶段推进（从“启动”进入“拟修订”）
  - 权威媒体/地方新闻 | 2025-04-02 | https://blueridgeleader.com/loudoun-board-of-supervisors-passes-data-center-zoning-amendments/ | 报道更严格的分区/审批修订落地，直接影响开发路径与节奏
  - 行业研究/咨询 | 2026-01-16 | https://capstonedc.com/insights/data-center-investors-face-growing-risk-from-local-opposition/ | 将Loudoun政策变化视为行业政策拐点，并讨论其对投资与选址风险的结构性影响

- sources (初报与当时材料):
  - initial_report: https://www.loudoun.gov/5990/Data-Center-Standards-Locations
  - time_slice_supporting: https://www.datacenterdynamics.com/en/news/zoning-permission-bill-proposed-in-virginia-to-limit-data-centers/

- notes: 初报是“流程启动”而非“结果落地”，但在NoVA这种边际约束区，流程本身就是重大信号；可作为LLM识别“监管收紧前兆”的正例。
---

---
## news_id: DCUS-2024-02-004
- domain: 数据中心
- initial_report_date: 2024-02-13
- title: Duke Energy在财报沟通中上调长期负荷增长预期（受数据中心等经济开发驱动）
- label: Major
- hard_negative: false
- summary: 主要公用事业公司把数据中心负荷纳入长期增长假设，并推动合同条款/资本开支/资源配置方式调整。

- axes_and_direction:
  - pace: accelerate
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 公用事业将数据中心纳入“高增长负荷”叙事 → 资源与输配电投资上调、并推动对大负荷采取更严格的供电合同/保障机制 → 大负荷接入从“招商”转向“风控+成本分摊”。
- observable_features_at_time:
  - 变化量: 初报以“负荷增速/驱动”叙述为主，MW未必详列（可记 Unknown）
  - 约束类型: 资源充裕性、输配电扩建、合同条款（最低用电/基础设施出资）
  - 影响范围: Duke服务区（卡罗来纳等），“数据中心外迁/新集聚地”可复制
  - 时间表: 财报口径属于中长期（10年以上）而非单项目
  - 证据等级: 公司披露/权威行业媒体（RTO/电力行业媒体）
  - 可复用信号: “economic development / data centers driving load growth / long-term load growth projections”语义模式
  - Unknown: 初报未披露“项目级签约MW清单”

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体/行业媒体 | 2024-11-07 | https://businessnc.com/duke-energy-says-data-centers-manufacturers-driving-its-growth/ | 明确将数据中心作为商业负荷增长关键来源，并给出公司口径的结构性变化描述
  - 主流媒体（地方商业媒体） | 2025-03-06 | https://www.newsobserver.com/news/business/article300346949.html | 进一步讨论数据中心负荷驱动下的资源与规划需求，表明该趋势持续影响公司规划与监管讨论

- sources (初报与当时材料):
  - initial_report: https://www.rtoinsider.com/71022-duke-energy-projects-higher-earnings/
  - time_slice_supporting: Unknown

- notes: 初报是“公司预期/口径变化”，其重大性在于后续持续被公司与媒体反复引用并嵌入投资/合同机制，而非单次新闻热度。
---

---
## news_id: DCUS-2024-02-005
- domain: 数据中心
- initial_report_date: 2024-02-24
- title: Georgia Power申请快速扩容发电/购电以应对“数据中心为主”的激增负荷（PSC听证推进）
- label: Major
- hard_negative: false
- summary: 公用事业以数据中心为核心驱动提出快速扩容方案，后续演化为监管定价/规则与大规模新增电源决策。

- axes_and_direction:
  - pace: accelerate
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 以数据中心为主的负荷激增 → IRP/应急扩容申请（新增机组/购电/储能）→ 监管机构推出面向大负荷的价格结构与保护条款，并最终批准大规模扩容（全国罕见规模）。
- observable_features_at_time:
  - 变化量: 初报给出“新增容量需求”量级与听证/投票时间表（可抽取）
  - 约束类型: 发电侧可调度资源（燃气机组/购电）、储能与太阳能、成本分摊与电价风险
  - 影响范围: 乔治亚州（大型数据中心集群新兴地），对其他州监管具有示范效应
  - 时间表: PSC听证（2/29–3/1）、计划投票节点（初报披露）
  - 证据等级: 监管听证/公司披露 + 媒体报道
  - 可复用信号: “IRP update / huge increase in capacity / data centers ~80% driver / PSC hearings”关键词组合
  - Unknown: 初报不一定披露到“逐项目数据中心签约清单”，更多为宏观负荷预测

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管机构披露 | 2025-01-23 | https://psc.ga.gov/site/assets/files/8617/media_advisory_data_centers_rule_1-23-2025.pdf | PSC针对>100MW新客户（含数据中心）制定更严格的用电条款/保护机制，表明问题进入制度化治理
  - 权威媒体 | 2025-12-20 | https://apnews.com/article/0b377d6a4a57c9353c0eb577b8951af3 | 报道监管机构批准以数据中心需求为主导的大规模新增电源/投资方案（结构性影响电力成本与供给结构）
  - 监管机构披露 | 2025-07-15 | https://psc.ga.gov/site/assets/files/8932/media_advisory_2025_irp_vote.pdf | PSC对IRP作出明确容量区间与后续季度大负荷报告要求，体现“数据中心负荷不确定性”成为长期监管主线

- sources (初报与当时材料):
  - initial_report: https://thecurrentga.org/2024/02/24/psc-to-resume-hearings-on-georgia-power-request-for-more-generating-capacity/
  - time_slice_supporting: https://www.wabe.org/georgia-powers-request-for-more-electricity-comes-under-fire/

- notes: 初报阶段仍存在“预测是否高估”的争论，但后续已形成明确的监管规则与扩容决策链条，因此判为Major（影响路径满足多源确认门槛）。
---

---
## news_id: DCUS-2024-03-006
- domain: 数据中心
- initial_report_date: 2024-03-25
- title: NV Energy 2024 Joint IRP负荷预测将“数据中心等工业大负荷”列为增长来源之一（内华达数据中心电力/水资源约束抬升）
- label: Major
- hard_negative: false
- summary: 在西部新兴市场，公用事业IRP把数据中心纳入长期负荷与资源配置，后续引发“新型大负荷费率/清洁电力供给方案”落地。

- axes_and_direction:
  - pace: accelerate
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: IRP将数据中心纳入“工业负荷增长” → 资源/费率与清洁电力供给机制创新（如Clean Transition Tariff）→ 地方层面围绕电力与水资源的约束讨论升温，影响项目可行性与成本。
- observable_features_at_time:
  - 变化量: IRP文件披露长期负荷增速/驱动；项目级MW多为Unknown
  - 约束类型: 电力接入（输配电/电源）、水资源（冷却）、清洁电力获取（费率/合同）
  - 影响范围: 内华达州（拉斯维加斯/里诺等），体现“数据中心走出NoVA后的新约束画像”
  - 时间表: IRP覆盖20年窗口（2025–2044等），属于长期规划信号
  - 证据等级: 公用事业IRP（监管/公司披露）为最高；后续媒体/监管材料补强
  - 可复用信号: IRP文本中直接出现“data centers”等工业负荷驱动
  - Unknown: 初报阶段对单个园区的具体水/电指标不统一披露

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 主流媒体（地方权威媒体） | 2025-07-27 | https://www.reviewjournal.com/local/local-nevada/nevadas-data-center-boom-is-a-power-water-conundrum-3403770/ | 明确指出数据中心驱动的电力与水资源矛盾，并引用NV Energy IRP负荷上修为核心证据
  - 公司披露/项目业主披露 | 2025-05-13 | https://blog.google/feed/nevada-clean-energy/ | Google披露与NV Energy机制（Clean Transition Tariff/清洁电力供给）用于支撑其数据中心负荷，体现“可复制的供电机制”
  - 权威行业媒体 | 2026-01-18 | https://www.rtoinsider.com/123624-nv-energy-might-fall-short-state-rps/ | 报道NV Energy在负荷预测中区分“含/不含大数据中心与AI项目”，并讨论其对资源与RPS达标的长期约束

- sources (初报与当时材料):
  - initial_report: https://www.nvenergy.com/publish/content/dam/nvenergy/brochures_arch/about-nvenergy/rates-regulatory/recent-regulatory-filings/irp/IRP-Volume-5.pdf
  - time_slice_supporting: https://www.nvenergy.com/publish/content/dam/nvenergy/brochures_arch/about-nvenergy/rates-regulatory/recent-regulatory-filings/irp/IRP-Volume-6.pdf

- notes: 初报为“监管/公司规划文件”，不具备媒体热度但信息硬；后验多源证实其引发费率机制与资源约束讨论，满足Major门槛。

---
## news_id: DCUS-2024-01-101
- domain: 数据中心
- initial_report_date: 2024-01-05
- title: 弗吉尼亚HB116提议：数据中心税收优惠与PUE/清洁电力/柴油备用限制挂钩
- label: NotMajor
- hard_negative: true
- summary: 当时看似将显著抬升合规门槛与成本，但法案未形成稳定可执行的结构性约束（推进受阻/延后）。

- axes_and_direction:
  - pace: uncertain
  - cost: up
  - constraint: tighten
  - supply_demand: uncertain

- subsequent_impact_path: 立法提议引发讨论 → 被“延后到后续会期/最终未推进成强制框架” → 对行业变量未形成可确认的长期制度冲击（更多停留在议题层）。
- observable_features_at_time:
  - 变化量: PUE阈值（如1.2）、清洁电力比例与时间点、柴油限制（初报可抽取）
  - 约束类型: 政策税收（优惠资格）、能源采购、备用电源技术选择
  - 影响范围: 弗吉尼亚（NoVA核心市场），潜在外溢但取决于立法落地
  - 时间表: 提议生效日期/阶段性要求（初报披露）
  - 证据等级: 立法记录 + 行业媒体
  - 可复用信号: “tie tax exemption to PUE / carbon-free procurement / diesel ban”结构化条款
  - Unknown: 最终是否落地（需后验确认）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 立法追踪/数据库 | 2024-02-07 | https://legiscan.com/VA/text/HB116/id/2866623 | 显示该案在2024会期被“continued to 2025”，并非立即形成强制规则
  - 立法研究/状态汇总 | 2024-11-18 | https://legiscan.com/VA/research/HB116/2024 | 显示后续会期推进仍受阻（Left in committee/Dead），缺乏持续、可执行确认

- sources (初报与当时材料):
  - initial_report: https://www.facilitiesdive.com/news/virginia-data-center-proposed-bill-energy-efficiency-requirements/703799/
  - time_slice_supporting: https://www.utilitydive.com/news/virginia-data-center-bill-energy-efficiency-requirements-dominion-energy/703895/

- notes: hard negative 的关键在于“条款看起来很硬（PUE/柴油/清洁电力）”，但未形成稳定的制度性落地路径；后续缺乏多源长期影响确认。
---

---
## news_id: DCUS-2024-01-102
- domain: 数据中心
- initial_report_date: 2024-01-09
- title: 弗吉尼亚HB910提议：要求数据中心季度披露能源来源并建立未来需求评估工作组
- label: NotMajor
- hard_negative: true
- summary: 当时看似会显著提高透明度并影响规划，但法案被延后/推进失败，未形成持续性制度冲击。

- axes_and_direction:
  - pace: uncertain
  - cost: mixed
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 透明度立法提议 → 会期内被“继续到下一会期/最终失败” → 未能建立稳定的信息披露与规划约束链条（对行业变量影响不显著）。
- observable_features_at_time:
  - 变化量: 披露频率（季度）、披露维度（按能源来源拆分）
  - 约束类型: 监管/披露（信息硬约束），潜在影响规划与舆论
  - 影响范围: 弗吉尼亚全州数据中心
  - 时间表: 初报含明确立法节点与会期动作
  - 证据等级: 立法系统记录（官方）为主
  - 可复用信号: “quarterly energy source report / deidentified aggregate publish / work group forecast”
  - Unknown: 是否最终生效（需后验）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 官方立法系统 | 2024-02-01 | https://legacylis.virginia.gov/cgi-bin/legp604.exe?241+sum+HB910= | 显示会期内“continued to 2025”
  - 官方立法系统（后续会期） | 2024-11-18 | https://lis.virginia.gov/bill-details/20251/HB910 | 显示后续状态为 Failed/Left in Rules，缺乏落地

- sources (初报与当时材料):
  - initial_report: https://legacylis.virginia.gov/cgi-bin/legp604.exe?241+sum+HB910=
  - time_slice_supporting: https://www.pecva.org/work/energy-work/data-center-legislation-in-the-2024-virginia-general-assembly/

- notes: 典型“看似重大（透明度/规划）但未落地”的 hard negative；适合训练模型避免把“提案/提议”误判为“制度落地”。
---

---
## news_id: DCUS-2024-01-103
- domain: 数据中心
- initial_report_date: 2024-01-05
- title: 弗吉尼亚HB337提议：以历史/农业/公园等资源影响为由限制数据中心选址
- label: NotMajor
- hard_negative: true
- summary: 当时看似会在选址层面形成硬约束，但法案推进失败，未形成可确认的结构性影响。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: uncertain

- subsequent_impact_path: 选址限制提议 → 立法层面未通过/被搁置 → 对整体行业节奏与约束未形成可验证的长期变化（更多停留在倡议/讨论）。
- observable_features_at_time:
  - 变化量: 距离阈值（如与公园/历史地标的距离要求）
  - 约束类型: 土地/许可（zoning/land use）
  - 影响范围: 弗吉尼亚潜在全域，但以特定敏感区为主
  - 时间表: 会期推进节点（初报可抽取）
  - 证据等级: 立法记录
  - 可复用信号: “not within one-half mile of a national/state park / historic resources”条款化语言
  - Unknown: 是否落地（需后验）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 官方立法系统 | 2024-12-02 | https://lis.virginia.gov/bill-details/20241/HB337 | 标注状态为 Failed，未形成制度落地
  - 公益组织汇总（会期中） | 2024-02-13 | https://www.pecva.org/work/energy-work/data-center-legislation-in-the-2024-virginia-general-assembly/ | 列示该类选址限制提案被搁置/难以推进（缺乏持续确认）

- sources (初报与当时材料):
  - initial_report: https://lis.virginia.gov/bill-details/20241/HB337
  - time_slice_supporting: https://legacylis.virginia.gov/cgi-bin/legp604.exe?241+sum+HB337=

- notes: hard negative 原因：条款“看起来很硬”，但缺乏通过与执行；后续无法满足“多源长期影响”门槛。
---

---
## news_id: DCUS-2024-01-104
- domain: 数据中心
- initial_report_date: 2024-01-29
- title: 弗吉尼亚SB288提议：数据中心噪声控制/邻里通知/会议等“噪声缓解”制度
- label: NotMajor
- hard_negative: true
- summary: 社区外部性议题热度高、看似会影响审批，但法案在委员会阶段失败，未形成制度性约束。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: uncertain

- subsequent_impact_path: 噪声治理提议 → 委员会未报告/被否决 → 未形成全州统一噪声硬约束（更多转向地方层面个案治理）。
- observable_features_at_time:
  - 变化量: 邻里通知范围、会议次数、噪声要求（条款化）
  - 约束类型: 许可/社区（社会许可）
  - 影响范围: 弗吉尼亚全州（若通过则广泛）
  - 时间表: 立法投票节点（初报/会期公告可抽取）
  - 证据等级: 立法记录/会期公告
  - 可复用信号: “noise abatement / notice / neighborhood meetings”条款化语言
  - Unknown: 是否落地（需后验）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 官方立法系统 | 2024-01-28 | https://lis.virginia.gov/bill-details/20241/SB288/ | 标注 Status: Failed
  - 立法追踪/状态 | 2024-01-29 | https://legiscan.com/VA/amendment/SB288/id/192287 | 显示“Failed to report (defeated)”，缺乏后续落地确认

- sources (初报与当时材料):
  - initial_report: https://lis.virginia.gov/bill-details/20241/SB288/
  - time_slice_supporting: https://legiscan.com/VA/drafts/SB288/2024

- notes: hard negative 关键：议题很像“会显著抬升审批门槛”，但实际快速失败；适合训练模型区分“争议/提案”与“规则落地”。
---

---
## news_id: DCUS-2024-02-105
- domain: 数据中心
- initial_report_date: 2024-02-28
- title: 弗吉尼亚HB338提议：数据中心选址需做水/碳等影响评估（locality site assessment）
- label: NotMajor
- hard_negative: true
- summary: 当时是“唯一仍活跃”的数据中心法案之一、看似会广泛影响选址与成本，但后续仍未形成稳定落地。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: uncertain

- subsequent_impact_path: 会期内通过部分程序 → 被“carry over/continued”，后续会期仍停滞 → 未能形成全州统一的选址评估硬约束（对行业变量影响缺乏多源确认）。
- observable_features_at_time:
  - 变化量: 影响评估维度（水、碳等）与“审批前置”流程
  - 约束类型: 许可/环境/水资源
  - 影响范围: 弗吉尼亚全州（若通过）
  - 时间表: House通过、转入Senate并被延后（初报即可观察到推进阻力）
  - 证据等级: 立法记录 + 公益组织会期跟踪
  - 可复用信号: “prior to approval / site assessment / water usage / carbon emissions”条款语义
  - Unknown: 最终是否生效（需后验）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 立法追踪/状态 | 2024-02-28 | https://legiscan.com/VA/bill/HB338/2024 | 显示 Continued to 2025（未在2024会期形成落地）
  - 立法追踪/状态 | 2024-11-19 | https://legiscan.com/VA/text/HB338/2025 | 显示后续会期仍“Left in committee/Dead”，缺乏持续落地确认

- sources (初报与当时材料):
  - initial_report: https://legiscan.com/VA/bill/HB338/2024
  - time_slice_supporting: https://www.pecva.org/work/energy-work/data-center-legislation-in-the-2024-virginia-general-assembly/

- notes: 这条是“最像会落地的提案”但仍未满足“多源长期影响”门槛，因此作为hard negative非常有价值。

---

## news_id: DCUS-2024-03-201
- domain: 数据中心
- initial_report_date: 2024-03-07
- title: 《America is running out of power》—AI数据中心推动电力短缺叙事上升为全国话题
- label: Unlabeled
- hard_negative: false
- summary: 影响叙事很强，但更像“宏观趋势报道”而非可验证的单一结构性事件；难以按门槛稳定归因。

- axes_and_direction:
  - pace: uncertain
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 全国性舆论与政策关注上升 → 各地区出现不同的监管/费率/扩容响应（但难以将后续具体制度变化归因到这篇“初报”）。
- observable_features_at_time:
  - 变化量: 主要为叙事与案例，项目级MW/时间表不统一（多为 Unknown）
  - 约束类型: 电源/输电/配电/许可等综合
  - 影响范围: 全国层面
  - 证据等级: 权威媒体深度报道
  - 可复用信号: “running out of power / AI data centers / grid to the brink”叙事模式
  - Unknown: 与后续具体制度/项目的因果归属

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - Unknown

- sources (初报与当时材料):
  - initial_report: https://www.washingtonpost.com/business/2024/03/07/ai-data-centers-power/
  - time_slice_supporting: Unknown

- notes: 作为训练数据可用于“宏观趋势报道”类别，但按本任务的“重大事件=改变硬约束/节奏/成本结构”的可验证标准，难以稳定标Major或NotMajor。
---

---
## news_id: DCUS-2024-03-202
- domain: 数据中心
- initial_report_date: 2024-03-19
- title: 数据中心/比特币/电动车推动公用事业“抢电”与扩容（多因素叠加的行业解读）
- label: Unlabeled
- hard_negative: false
- summary: 讨论了公用事业扩容压力，但主题混合（数据中心+比特币+EV），对“数据中心单因素”的结构性影响难以归因。

- axes_and_direction:
  - pace: uncertain
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 负荷增长叙事强化 → 各州/各公用事业采取差异化应对（费率、合同、扩容）→ 但该文本本身更像“综述”，不易作为单点重大事件样本。
- observable_features_at_time:
  - 变化量: 以案例与预测为主，项目级参数不稳定（多为 Unknown）
  - 约束类型: 供电与费率机制、资源充裕性
  - 影响范围: 全国多地区
  - 证据等级: 独立媒体深度/分析
  - 可复用信号: “utilities scrambling / load growth / data centers + bitcoin + EVs”叙事模板
  - Unknown: 后续影响的独立多源“单点确认”

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - Unknown

- sources (初报与当时材料):
  - initial_report: https://www.canarymedia.com/articles/electrification/data-centers-bitcoin-and-evs-send-utilities-scrambling-for-more-power
  - time_slice_supporting: Unknown

- notes: 可作为“趋势型候选”留档，但不满足本标注体系对Major/NotMajor的稳定确认要求，因此Unlabeled。
---

# 数据中心-美国-2024Q2 标注集（hindsight）

---
## news_id: USDC-2024-05-01
- domain: 数据中心
- initial_report_date: 2024-05-07
- title: Duke Energy要求数据中心采用“take-or-pay/最低用电量”与前期出资条款，以对冲电网与搁浅风险
- label: Unlabeled
- hard_negative: false
- summary: 公用事业将大负荷客户合同从“按需扩容”改为“最低承诺+前期出资”，把电网扩容与搁浅风险显性化并向数据中心转移。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 后续Duke披露将把最低承诺（take-or-pay）写入新增数据中心协议，且谈判包含共建基础设施与潜在专门费率，行业“保底电量/保底费用”成为大型负荷接入的常见条款，抬升数据中心用电边际成本并改变投运节奏与选址。 
- observable_features_at_time:
  - 合同机制：提出“minimum take/take-or-pay”——即便实际用电低于约定也需支付保底电量费用（Unknown具体比例与期限）
  - 资金安排：讨论要求数据中心对新增基础设施进行前期出资/共担（Unknown金额）
  - 触发门槛：面向单点>100MW级别的大负荷（从报道语境可推断为核心对象）
  - 约束类型：供电侧“constrained power supply”与并网/扩容投资回收风险
  - 负荷尺度：报道提及单项目电力需求可达GW级（最高到约2GW的量级描述）
  - 影响范围：覆盖Duke辖区（卡罗来纳/东南部）的大负荷签约策略，具有可复制性
  - 证据等级：公司高管口径+权威媒体

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体（财经通讯社） | 2024-11-07 | https://www.reuters.com/business/energy/duke-energys-new-2-gws-us-data-centers-include-minimum-take-agreements-cfo-says-2024-11-07/ | 明确“新增2GW数据中心协议将包含最低承诺/保底电量条款”，并讨论专门费率与共建投资
  - 权威媒体（财经通讯社） | 2024-05-07 | https://www.reuters.com/business/energy/duke-energy-seeks-take-or-pay-power-contracts-data-centers-2024-05-07/ | 首次披露take-or-pay与前期基础设施出资思路，指向行业合同范式变化

- sources (初报与当时材料):
  - initial_report: https://www.reuters.com/business/energy/duke-energy-seeks-take-or-pay-power-contracts-data-centers-2024-05-07/
  - time_slice_supporting: https://www.reuters.com/business/energy/duke-energy-seeks-take-or-pay-power-contracts-data-centers-2024-05-07/

- notes: 初报提供了机制与方向（成本上行、约束趋紧），但具体条款比例/期限多为Unknown；适合作为“合同条款变化”类重大新闻样本。
---

---
## news_id: USDC-2024-06-02
- domain: 数据中心
- initial_report_date: 2024-06-11
- title: AEP Ohio提交面向数据中心的新并网费率/合同要求并实施新接入暂停（moratorium）
- label: Major
- hard_negative: false
- summary: 公用事业以“数据中心要为电网升级与搁浅风险买单”为由，推出更强约束的接入规则并暂停新增申请，形成可复制的“高负荷专门规制”。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 该提案在监管程序中被实质采纳并最终形成可执行的关口条款（如最低用电/保底购买、并网规则更新、解除暂停的条件），随后被多家媒体与监管跟踪解读为“对数据中心大负荷的里程碑式费率保护”，强化行业对“先担责后接入”的预期。 
- observable_features_at_time:
  - 监管动作：向州监管机构提交数据中心专门费率/并网规则方案（Unknown案号在初报中是否完整给出）
  - 接入暂停：对新增数据中心接入申请设置moratorium（时间长度Unknown）
  - 约束类型：电网升级成本、搁浅风险（项目失败导致既有用户被迫承担）
  - 触发门槛：面向高负荷数据中心客户（报道语境常见为>25MW级别）
  - 合同机制：更强的最低用电/最低负荷因子/最低期限（具体参数Unknown）
  - 影响范围：AEP Ohio服务区（中俄亥俄等数据中心集聚地）
  - 证据等级：行业媒体报道+监管提交信息

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管机构裁定/披露（二级媒体转述） | 2025-07-10 | https://www.utilitydive.com/news/Ohio-regulators-approve-aep-data-center-interconnection-rules/752690/ | 监管批准并要求更新费率与解除暂停，确认规则进入执行阶段
  - 行业媒体（公共电力） | 2024-06-11 | https://www.publicpower.org/periodical/article/aep-ohio-proposes-new-data-center-interconnection-tariffs | 初报：披露AEP Ohio提出数据中心并网费率并暂停新增接入申请
  - 官方费率文件入口 | 2024-06-11 | https://aepohio.com/about/ratesandtariffs | 提供费率与tariff公开入口，便于核对条款文本与后续修订

- sources (初报与当时材料):
  - initial_report: https://www.publicpower.org/periodical/article/aep-ohio-proposes-new-data-center-interconnection-tariffs
  - time_slice_supporting: https://aepohio.com/about/ratesandtariffs

- notes: 初报对具体条款参数披露有限（不少为Unknown），但“暂停+专门tariff/并网规则”属于可复用强信号；后验确认其确实落地执行。
---

---
## news_id: USDC-2024-06-03
- domain: 数据中心
- initial_report_date: 2024-06-26
- title: PJM核电站“厂内/behind-the-meter”共址数据中心扩容（300→480MW）引发AEP/Exelon抗议，触发FERC层面规则审查
- label: Major
- hard_negative: false
- summary: 共址数据中心试图绕开传统“网络负荷”费用与升级义务，引发“成本转移+可靠性”争议，进而推动FERC明确共址负荷监管路径。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 抗议促使FERC对共址负荷的费率分类、成本分摊与可靠性影响进行审查并最终否决该ISA扩容，进一步强化“需通过区域性tariff规则而非个案ISA绕行”的监管导向，显著提高类似共址方案的不确定性与合规成本。 
- observable_features_at_time:
  - 变更量：拟将共址负荷从300MW提高到480MW（明确数值）
  - 关键文件：PJM于2024-06-03向FERC提交修订ISA请求（明确日期）
  - 争议焦点：共址负荷是否应作为“network load”缴纳输电费与承担辅助服务/容量成本
  - 约束类型：成本转移（free rider）、系统可靠性、市场规则一致性
  - 影响范围：PJM区域；对“发电侧共址数据中心”具有示范效应
  - 证据等级：行业媒体+监管抗议/程序
  - 时间表：抗议提交在6月下旬（报道给出抗议发生时点）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管机构（FERC） | 2024-11-01 | https://www.ferc.gov/media/er24-2172-pjms-susquehanna-co-location-proposal | FERC公开页面归档该案并说明处理结论与要点（围绕300→480MW扩容与规则问题）
  - 权威媒体（财经通讯社） | 2024-11-02 | https://www.reuters.com/business/energy/us-regulators-reject-amended-interconnect-agreement-amazon-data-center-2024-11-02/ | 报道FERC否决共址扩容协议并强调可靠性与成本问题
  - 行业媒体（Utility Dive） | 2024-06-26 | https://www.utilitydive.com/news/aep-exelon-pjm-interconnection-amazon-data-center-talen-ferc-isa/719869/ | 初报：披露抗议与ISA关键条款（300→480MW、费用分类争议）

- sources (初报与当时材料):
  - initial_report: https://www.utilitydive.com/news/aep-exelon-pjm-interconnection-amazon-data-center-talen-ferc-isa/719869/
  - time_slice_supporting: https://www.utilitydive.com/news/aep-exelon-pjm-interconnection-amazon-data-center-talen-ferc-isa/719869/

- notes: 该条目对“共址负荷/behind-the-meter”是高质量重大新闻样本：初报即含明确数值变化与监管争议点，后验出现清晰的FERC否决与规则指向。
---

---
## news_id: USDC-2024-05-02
- domain: 数据中心
- initial_report_date: 2024-05-13
- title: FERC发布Order 1920推进20年期区域输电规划与成本分摊改革，回应AI/数据中心等负荷增长
- label: Major
- hard_negative: false
- summary: 联邦层面输电规划与分摊框架升级，旨在为长期负荷增长（含数据中心/AI）预先建设输电能力，影响“能否供电/并网”这类硬约束。

- axes_and_direction:
  - pace: mixed
  - cost: mixed
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: Order 1920要求输电业主开展长期（20年）区域规划并建立更可执行的成本分摊机制，后续在复议令1920-A中进一步澄清与调整要求；对数据中心而言，中长期有助于“输电瓶颈”缓解，但短期可能引发合规与成本分摊争议，形成“先紧后松/先成本再扩容”的路径。 
- observable_features_at_time:
  - 规则性质：联邦监管最终规则（Order 1920），具有强制合规属性
  - 规划期限：要求长期区域输电规划（20年视角）
  - 成本机制：建立/强化区域成本分摊与情景规划机制（具体条款见官方解释文件）
  - 驱动叙事：显式提及电动化、数据中心、AI带来的用电增长压力
  - 约束类型：输电（transmission）而非末端配电；属于上游“能否供电”的硬约束
  - 影响范围：全美FERC管辖的输电规划区域（不含ERCOT纯州内部分）
  - 证据等级：权威媒体+监管机构文件

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管机构（FERC官方解释） | 2024-11-21 | https://www.ferc.gov/explainer-transmission-planning-and-cost-allocation-final-rule | 官方说明1920及复议令1920-A对规则要求的澄清与修改，确认进入合规落地阶段
  - 权威媒体（财经通讯社） | 2024-05-13 | https://www.reuters.com/business/energy/ferc-overhaul-us-electric-transmission-system-2024-05-13/ | 初报：强调该规则用于应对包含数据中心/AI在内的电力需求增长并改革规划与分摊
  - 监管机构（FERC Fact Sheet） | 2024-05-13 | https://www.ferc.gov/news-events/news/fact-sheet-building-future-through-electric-regional-transmission-planning-and | 提供规则要点摘要（便于抽取可复用特征）

- sources (初报与当时材料):
  - initial_report: https://www.reuters.com/business/energy/ferc-overhaul-us-electric-transmission-system-2024-05-13/
  - time_slice_supporting: https://www.ferc.gov/news-events/news/fact-sheet-building-future-through-electric-regional-transmission-planning-and, https://www.ferc.gov/explainer-transmission-planning-and-cost-allocation-final-rule

- notes: 该条为“上游输电规则”对数据中心约束的重大样本；当时可观测特征偏政策/规则条款，量化字段（MW等）通常Unknown。
---

---
## news_id: USDC-2024-06-04
- domain: 数据中心
- initial_report_date: 2024-06-05
- title: Fairfax County启动/审议更严格的数据中心分区与噪声等要求（规划委公开听证）
- label: Major
- hard_negative: false
- summary: 全球最大数据中心集群周边县区开始通过分区与噪声等“许可硬约束”收紧数据中心选址与审批路径，改变NoVA新增项目节奏。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: 规划委听证后，县董事会在2024-09通过修订并生效，核心效果是显著提高多数项目审批门槛（从by-right走向需要Special Exception/更严格标准），将“地方许可/社区阻力”变为可预期的硬约束，影响新增项目落地节奏与选址。 
- observable_features_at_time:
  - 监管动作：规划委员会举行公开听证并讨论分区修订建议（明确流程事件）
  - 约束类型：噪声研究/要求、建筑设计与与住宅距离等兼容性要求（具体阈值Unknown）
  - 许可路径：从“较宽松许可/既有条款”走向“更严格审查”（具体机制以最终文本为准）
  - 影响范围：Fairfax County（NoVA核心区域之一，外溢影响周边选址）
  - 影响对象：新申报/新提交site plan的项目（既有项目可能被grandfather条款豁免）
  - 证据等级：地方媒体+官方程序

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 地方政府（官方新闻） | 2024-09-11 | https://www.fairfaxcounty.gov/news/board-supervisors-approve-new-data-center-zoning-ordinance-amendment | 确认县董事会已通过并生效，说明收紧方向（噪声、设计、距离等）
  - 律所/专业解读（独立于政府） | 2024-09-12 | https://www.hklaw.com/en/insights/publications/2024/09/fairfax-county-virginia-approves-updated-zoning-regulations | 归纳最终规则并强调多数项目将需要更高审批门槛（Special Exceptions等）
  - 当时报道（地方电视媒体） | 2024-06-05 | https://wjla.com/news/local/data-centers-zoning-recommendations-fairfax-county-planning-commission-ordinance-amendment-hearing-public-input-resident-concerns-virginia-dmv | 初报：记录规划委听证节点与公众关切

- sources (初报与当时材料):
  - initial_report: https://wjla.com/news/local/data-centers-zoning-recommendations-fairfax-county-planning-commission-ordinance-amendment-hearing-public-input-resident-concerns-virginia-dmv
  - time_slice_supporting: https://www.fairfaxcounty.gov/news/board-supervisors-approve-new-data-center-zoning-ordinance-amendment

- notes: 属于“地方许可硬约束”典型；初报阶段部分阈值为Unknown，但流程节点（听证/修订）可直接复用为特征。
---

---
## news_id: USDC-2024-05-03
- domain: 数据中心
- initial_report_date: 2024-05-08
- title: Microsoft宣布在威斯康星投入33亿美元建设AI/云基础设施（含数据中心园区），带动区域电力与基础设施议题
- label: Major
- hard_negative: false
- summary: 超大规模AI园区落地新市场，驱动公用事业扩容、费用分摊与基础设施承诺，形成“新地理扩张+电力约束外溢”样本。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 后续多家媒体与公司披露显示项目持续推进并追加投资，且被用于讨论“数据中心扩张对公用事业投资与费率影响”；该类项目推动中西部/新兴市场进入数据中心电力竞争与基础设施先行投入阶段。 
- observable_features_at_time:
  - 变化量：投资额33亿美元（明确）
  - 位置：威斯康星州东南部（Mount Pleasant等，具体园区范围Unknown）
  - 时间表：建设与投运窗口在初报中多为概略（Unknown）
  - 约束类型：电力接入与电网基础设施（需与公用事业协调）、可能的冷却与用水（Unknown）
  - 影响范围：区域性，但具有“新市场承接超大负荷”的可复制性
  - 证据等级：公司披露+行业媒体

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体（财经通讯社） | 2025-09-18 | https://www.reuters.com/business/microsoft-boosts-wisconsin-data-center-spending-7-billion-2025-09-18/ | 披露追加投资、项目进度与电力基础设施投入安排，确认持续性影响
  - 非营利新闻/深度报道 | 2025-05-02 | https://wisconsinwatch.org/2025/05/wisconsin-utility-data-center-energy-tech-electricity-power-rates/ | 以威州为例讨论数据中心对公用事业投资与费率影响，覆盖Microsoft等项目
  - 公司披露（初报） | 2024-05-08 | https://news.microsoft.com/source/2024/05/08/microsoft-announces-3-3-billion-investment-in-wisconsin-to-spur-artificial-intelligence-innovation-and-economic-growth/ | 初报：宣布33亿美元投资包与基础设施方向

- sources (初报与当时材料):
  - initial_report: https://news.microsoft.com/source/2024/05/08/microsoft-announces-3-3-billion-investment-in-wisconsin-to-spur-artificial-intelligence-innovation-and-economic-growth/
  - time_slice_supporting: https://www.ciodive.com/news/microsoft-wisconsin-data-center-build-ai-lab-upskilling/715567/

- notes: 该条“重大性”更多来自对区域电力与费率/基础设施讨论的外溢，而非单一园区规模；初报时MW/电力协议等关键字段多为Unknown。
---

---
## news_id: USDC-2024-04-01
- domain: 数据中心
- initial_report_date: 2024-04-24
- title: Prince William County在FY2025预算中上调“计算机设备与外设”税率至$3.70/每$100估值（显著影响数据中心设备税负）
- label: Major
- hard_negative: false
- summary: 数据中心核心成本之一（设备税）在NoVA关键县区被显著上调，成为地方政府用“税收/财政”调节数据中心扩张与社区矛盾的硬工具。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: 税率上调后，县级报告与媒体披露显示数据中心相关税收显著抬升并进入地方财政与政治议题核心，强化“通过税负提高开发门槛/提高地方收益”的政策路径，影响选址与项目可行性边际。 
- observable_features_at_time:
  - 变化量：税率从$2.15提高到$3.70/每$100估值（明确）
  - 税种：business tangible personal property tax（计算机设备与外设，覆盖数据中心设备）
  - 触发范围：县域所有相关设备（是否差异化对待数据中心/非数据中心在初报中可为Unknown）
  - 影响对象：存量设备年度税负与新增投资的持续性成本
  - 约束类型：地方财政/税收（非并网/电力物理约束，但会影响项目经济性）
  - 证据等级：县政府预算采用公告（官方）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 县政府报告（税收回顾） | 2025-06-30 | https://www.pwcva.gov/assets/2025-06/Prince%20William%20County%202024%20Data%20Center%20Revenue%20Report.pdf | 明确提及72.1%税率上调（$2.15→$3.70）并说明对税收的放大效应
  - 地方媒体 | 2025-03-19 | https://wtop.com/prince-william-county/2025/03/prince-william-countys-data-center-tax-revenue-jumps-nearly-70-to-280-million/ | 报道税收增长并引用县报告，强化“税率工具化”的持续影响
  - 县政府新闻（预算通过） | 2024-04-24 | https://www.pwcva.gov/news/board-county-supervisors-adopts-fiscal-year-2025-budget | 初报：确认税率上调并随预算生效

- sources (初报与当时材料):
  - initial_report: https://www.pwcva.gov/news/board-county-supervisors-adopts-fiscal-year-2025-budget
  - time_slice_supporting: https://www.pwcva.gov/assets/2024-05/Tax%20Rates%20-%202024.pdf, https://www.potomaclocal.com/2024/04/18/prince-william-to-hike-taxes-on-data-centers-provide-relief-to-homeowners/

- notes: 该条属于“地方税收硬工具”重大样本；与电网物理约束不同，但会显著改变项目IRR与谈判筹码。
---

### NotMajor（包含≥5条 hard_negative；其中部分为“看似重大但未形成结构性改变/或仅停留在讨论层面”的样本）

---
## news_id: USDC-2024-05-08
- domain: 数据中心
- initial_report_date: 2024-05-04
- title: 佐治亚州通过暂停数据中心设备销售税减免的法案（HB 1192）并等待州长签署（后被否决）
- label: NotMajor
- hard_negative: true
- summary: 当时看似会显著提高数据中心成本与放缓扩张，但最终被州长否决，未形成实际政策收紧（结果接近“无变化”）。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 法案虽通过立法机构并引发“暂停税惠以评估电网影响”的强信号，但州长否决使暂停未生效，结构性变量（成本/节奏/约束）并未按法案设计发生制度性上行。 
- observable_features_at_time:
  - 政策内容：拟暂停数据中心设备销售税减免两年（明确方向）
  - 时间点：涉及2024-07-01附近的生效/窗口（报道提及“突然截止”风险）
  - 配套机制：拟设立研究/委员会评估电网影响（是否最终成立为Unknown）
  - 约束类型：税收激励（成本端）
  - 影响范围：佐治亚州（全州吸引数据中心的核心政策之一）
  - 证据等级：地方政治媒体/新闻

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 地方媒体 | 2024-05-08 | https://georgiarecorder.com/2024/05/08/governor-vetoes-tax-breaks-for-data-centers-homestead-exemption-increase-and-higher-ed-assistance/ | 明确法案被否决，暂停税惠未落地
  - 政务/公共政策媒体 | 2026-01-20 | https://www.route-fifty.com/artificial-intelligence/2026/01/outrage-over-surge-data-centers-georgia-inspires-wave-bipartisan-bills/410782/ | 回溯2024年“暂停税惠”最终被否决，作为后续立法再起的背景

- sources (初报与当时材料):
  - initial_report: https://thecurrentga.org/2024/05/04/data-center-bill-awaits-kemps-signature-unites-environmental-gop-groups/
  - time_slice_supporting: https://georgiarecorder.com/2024/05/08/governor-vetoes-tax-breaks-for-data-centers-homestead-exemption-increase-and-higher-ed-assistance/

- notes: 典型hard negative：传播度高、看似会改变成本结构，但结果为“否决→不生效”，不满足“多源后验确认其造成长期行业变量改变”的门槛。
---

---
## news_id: USDC-2024-06-01
- domain: 数据中心
- initial_report_date: 2024-06-19
- title: 多州联盟起诉/挑战FERC Order 1920（输电规划与成本分摊改革）属“强对抗信号”，但未在可观察窗口内改变规则落地路径
- label: NotMajor
- hard_negative: true
- summary: 诉讼/挑战在舆论上很像会推翻规则、进而影响数据中心供电约束，但后续官方流程仍推进（含1920-A澄清），短中期未见因诉讼导致的制度性反转。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 挑战行动并未在后续公开材料中被确认已显著阻断规则实施；相反，FERC发布解释文件并在复议令中继续推进澄清与合规安排，诉讼更像“政治/法律噪声”，对数据中心“能否供电”硬约束的方向性影响在当期难以确认。 
- observable_features_at_time:
  - 事件性质：多州联盟对Order 1920提起挑战（法律/政治动作）
  - 目标对象：FERC Order 1920（输电规划与成本分摊）
  - 约束类型：输电基础设施与成本分摊（长期变量）
  - 可观测结果：仅能观察到“起诉/挑战”，无法观察到“规则暂停/撤销”（Unknown）
  - 影响范围：潜在全国，但需要后续裁决才会落到行业变量
  - 证据等级：媒体报道（非监管最终裁决）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管机构（官方解释） | 2024-11-21 | https://www.ferc.gov/explainer-transmission-planning-and-cost-allocation-final-rule | 官方继续推进并解释1920与1920-A，未显示因挑战而终止
  - 监管机构（官方演示/复议令信息） | 2024-11-21 | https://www.ferc.gov/news-events/news/presentation-order-no-1920-building-future-through-electric-regional-transmission | 复议令1920-A发布与澄清，体现规则仍在推进
  - 媒体（起诉报道） | 2024-06-19 | https://nypost.com/2024/06/19/us-news/texas-leads-19-state-coalition-challenging-green-energy-transition-mandate/ | 初报：描述多州挑战行动

- sources (初报与当时材料):
  - initial_report: https://nypost.com/2024/06/19/us-news/texas-leads-19-state-coalition-challenging-green-energy-transition-mandate/
  - time_slice_supporting: https://www.ferc.gov/explainer-transmission-planning-and-cost-allocation-final-rule

- notes: hard negative的理由在于：初报是“对抗动作”，但缺少后验多源确认其造成行业变量（供电约束/成本/节奏）的可观测反转或明显改道。
---

---
## news_id: USDC-2024-06-05
- domain: 数据中心
- initial_report_date: 2024-06-04
- title: 威斯康星公共讨论：监管者与公众对Microsoft数据中心园区“到底要多少电”缺乏透明信息
- label: NotMajor
- hard_negative: true
- summary: 当时讨论热度高、信息缺口大，看似会推动强制披露或新规，但后续公开材料更多是项目继续推进与舆论讨论，难以确认形成制度性硬约束变化。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 后续报道更多集中于项目推进与投资追加，以及数据中心对费率/公用事业投资的宏观讨论；但在可核对公开材料中，难以将该“信息不透明争议”映射为明确的新监管规则或强制披露机制落地。 
- observable_features_at_time:
  - 信息缺口：项目MW需求对监管者“未知/不清楚”（明确）
  - 约束类型：电力接入与基础设施（但具体扩容方案Unknown）
  - 风险点：费率/成本分摊与规划不确定性（机制性描述）
  - 影响范围：区域性（威斯康星），外溢到“披露与透明度”议题
  - 可量化字段：MW、并网时间表、供电合同条款均为Unknown
  - 证据等级：地方公共媒体报道

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 深度报道（地区非营利媒体） | 2025-05-02 | https://wisconsinwatch.org/2025/05/wisconsin-utility-data-center-energy-tech-electricity-power-rates/ | 继续讨论数据中心对公用事业与费率影响，但并未把“未知MW”直接对应为明确的强制披露新规
  - 权威媒体（财经通讯社） | 2025-09-18 | https://www.reuters.com/business/microsoft-boosts-wisconsin-data-center-spending-7-billion-2025-09-18/ | 披露项目推进与追加投资，侧面显示争议未直接阻断项目，但也未证明形成制度性约束

- sources (初报与当时材料):
  - initial_report: https://www.wpr.org/news/data-centers-energy-demand-microsoft-epri
  - time_slice_supporting: https://news.microsoft.com/source/2024/05/08/microsoft-announces-3-3-billion-investment-in-wisconsin-to-spur-artificial-intelligence-innovation-and-economic-growth/

- notes: hard negative的关键是“看似重大但缺乏可核对的制度落地结果”；用于训练模型识别“信息不充分/争议性强但难以确认结构性影响”的样本。
---

---
## news_id: USDC-2024-05-06
- domain: 数据中心
- initial_report_date: 2024-05-13
- title: 社会组织与行业解读将FERC Order 1920描述为“应对数据中心负荷增长”的关键举措，但短期难以直接映射到数据中心投运节奏变化
- label: NotMajor
- hard_negative: true
- summary: 叙事上容易被当作“立刻缓解数据中心供电瓶颈”的重大利好，但规则的效应具有长周期与高不确定性，初报阶段缺少可量化的短期行业变量变化。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: Order 1920确立长期规划框架，但从后续官方解释看，其合规与首轮规划周期启动存在时间滞后；因此在2024Q2的新闻切片上，很难用“短期装机/投运节奏”去验证结构性改变，更多属于政策背景变量。 
- observable_features_at_time:
  - 规则定位：长期输电规划与成本分摊框架（明确）
  - 叙事关联：解读材料提及“数据中心负荷增长”（明确）
  - 时间滞后：短期难以转化为可用输电容量（Unknown具体落地时间）
  - 量化字段：新增线路里程/容量、对特定数据中心并网时间影响均为Unknown
  - 证据等级：第三方组织解读（非监管执行结果）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管机构（官方解释） | 2024-11-21 | https://www.ferc.gov/explainer-transmission-planning-and-cost-allocation-final-rule | 强调合规与周期安排，体现政策效应的时间滞后与复杂性
  - 第三方组织/解读 | 2024-05-13 | https://www.selc.org/press-release/ferc-finalizes-transmission-rule/ | 初报阶段的“数据中心负荷增长”叙事与解读

- sources (初报与当时材料):
  - initial_report: https://www.selc.org/press-release/ferc-finalizes-transmission-rule/
  - time_slice_supporting: https://www.ferc.gov/explainer-transmission-planning-and-cost-allocation-final-rule

- notes: hard negative用于区分“背景性政策利好/长周期变量”与“可在中短期验证的重大事件”；不否认其长期重要性，但在标注集里不当作可稳定确认的重大行业事件。
---

---
## news_id: USDC-2024-04-30
- domain: 数据中心
- initial_report_date: 2024-04-30
- title: 综合报道：地方政府开始通过税率与分区等工具“管控数据中心扩张”，但报道本身缺少单一可验证的制度落地结果
- label: Unlabeled
- hard_negative: true
- summary: 报道热度高、叙事像“全国性监管拐点”，但更多是多地零散动作集合，难以用后验多源把它归因成一个明确、可复用的结构性事件。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 后续确有多个地区分别出台税收/分区/噪声等措施，但该类“综述型报道”难以满足“一个事件→多源确认其长期影响”的门槛，更适合作为Unlabeled或hard negative来训练模型识别“叙事宏大但事件边界不清”的内容。 
- observable_features_at_time:
  - 内容形态：综述/趋势报道（非单一政策或单一项目）
  - 涉及工具：税率上调、分区收紧、居民噪声争议等（多点罗列）
  - 量化字段：MW/投运时间表/规则条款多为Unknown或不统一
  - 影响范围：跨多地，但缺乏统一制度锚点
  - 证据等级：权威媒体综合报道（但事件边界模糊）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 地方政府（示例：Fairfax最终通过分区修订） | 2024-09-11 | https://www.fairfaxcounty.gov/news/board-supervisors-approve-new-data-center-zoning-ordinance-amendment | 说明“综述中提到的动作类型”在部分地区确实落地，但无法证明综述本身对应单一结构性事件
  - 县政府（示例：Prince William税率上调后的税收报告） | 2025-06-30 | https://www.pwcva.gov/assets/2025-06/Prince%20William%20County%202024%20Data%20Center%20Revenue%20Report.pdf | 证明“税率工具”在个别地区产生效果，但仍不足以把综述作为一个可稳定标注的单一事件

- sources (初报与当时材料):
  - initial_report: https://www.washingtonpost.com/dc-md-va/2024/04/30/data-centers-regulations-northern-virginia-georgia-arizona/
  - time_slice_supporting: https://bendbulletin.com/2024/05/01/as-internet-data-centers-multiply-efforts-to-control-them-are-growing/

- notes: 该条hard negative的核心在于“事件边界不清”；用于训练模型避免把趋势综述误判为可回测的单一重大事件。

---

## news_id: USDC-2024-06-06
- domain: 数据中心
- initial_report_date: 2024-06-11
- title: Fairfax County规划委建议推进数据中心分区修订（法律/咨询类“过程节点”口径）
- label: Unlabeled
- hard_negative: false
- summary: 过程节点类信息可作为候选，但不同来源对关键条款与适用范围表述不一，且容易与最终通过节点混淆。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: Unknown
- observable_features_at_time:
  - 事件为“建议/推荐”而非“最终通过”（与后续9月最终版本存在差异空间）
  - 关键条款阈值（噪声、距离、审批路径）在不同材料中可能表述不一致（Unknown）
  - 更适合作为“过程节点特征”而非结果事件

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - Unknown | Unknown | Unknown | Unknown

- sources (初报与当时材料):
  - initial_report: https://www.mcguirewoods.com/client-resources/alerts/2024/6/fairfax-county-planning-commission-recommends-data-center-zoning-changes/
  - time_slice_supporting: https://wjla.com/news/local/data-centers-zoning-recommendations-fairfax-county-planning-commission-ordinance-amendment-hearing-public-input-resident-concerns-virginia-dmv

- notes: 与Major条目“最终通过并生效（9月）”相比，本条仅是建议节点；为避免重复与标签污染，暂留Unlabeled。
---


# 数据中心-美国-2024Q3 标注集（hindsight）

---
## news_id: DCUS-2024-07-01
- domain: 数据中心
- initial_report_date: 2024-07-31
- title: PJM 2025/2026容量拍卖价格暴涨，反映供需缺口与负荷（含数据中心）上行压力
- label: Major
- hard_negative: false
- summary: PJM容量拍卖出现异常高价，信号指向供给侧退役/受限与需求侧负荷上修叠加；其后被反复引用为“电力约束成为数据中心投运硬约束”的标志性事件。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 拍卖高价被后续多方解读为“供给增长跟不上负荷（含数据中心）增长”的系统性信号，推动监管/立法层面讨论容量市场与并网瓶颈，并在后续年度拍卖与政策讨论中持续作为参照，强化“电力与并网约束→项目投运节奏/电价结构”的因果链条。
- observable_features_at_time:
  - 事件类型为系统运营商市场出清结果（容量市场），属于跨区域、跨公用事业影响的“硬信息”
  - 初报直接给出清算价格、与上年对比幅度（变化量明确）
  - 初报与PJM官方通稿明确提到：负荷预测上修、退役/供给收缩、局部区域（LDA）约束等机制线索
  - 影响范围覆盖PJM大区（多州），与数据中心集中区（如北弗吉尼亚所在区域）高度相关
  - 约束类型：供电与并网/系统可靠性约束（容量充足性）
  - 成本信号：容量成本上行将传导至电价/终端用户账单（方向明确）
  - 证据等级：系统运营商披露 + 权威媒体
  - 变化量（MW/资源结构等）在官方报告中可查（若需要可进一步结构化抽取）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体（Reuters） | 2025-07-22 | https://www.reuters.com/business/energy/biggest-us-power-grid-auction-prices-rise-by-22-new-heights-2025-07-22/ | 将“上年拍卖价格激增”与“数据中心驱动的需求上行/供需缺口”并列为核心背景与持续性矛盾
  - 监管/立法研究（CRS） | 2025-06-02 | https://www.congress.gov/crs_external_products/R/HTML/R48553.web.html | 以2025/2026拍卖为案例讨论市场设计敏感性与政策含义，强化其结构性影响属性

- sources (初报与当时材料):
  - initial_report: https://www.reuters.com/business/energy/pjm-power-auction-results-yield-sharply-higher-prices-2024-07-31/
  - time_slice_supporting: https://www.pjm.com/-/media/DotCom/about-pjm/newsroom/2024-releases/20240730-pjm-capacity-auction-procures-sufficient-resources-to-meet-rto-reliability-requirement.ashx, https://www.pjm.com/-/media/DotCom/markets-ops/rpm/rpm-auction-info/2025-2026/2025-2026-base-residual-auction-report.pdf

- notes: subsequent_impact_path仅写机制与方向；未在此处引用后验量化结论。该事件对“数据中心投运节奏”的影响主要通过“电力/容量成本与并网资源稀缺→项目可获得电力与合同条件”间接体现。
---

---
## news_id: DCUS-2024-08-01
- domain: 数据中心
- initial_report_date: 2024-08-19
- title: 美国能源部顾问委员会（SEAB）发布“为AI与数据中心基础设施供电”建议，明确联邦层面对电力瓶颈的政策议程
- label: Major
- hard_negative: false
- summary: DOE层面将AI/数据中心用电上升定义为国家级电力系统挑战，提出提升电网与发电/能效/审批等多路径建议，成为后续政策讨论的“框架性参照”。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: mixed
  - supply_demand: tighten

- subsequent_impact_path: 该报告在后续政策/研究讨论中持续被引用，用于论证“数据中心负荷增长→电网规划与并网流程、供给侧扩容与能效并行”的政策组合；在多份后续解读中被用作联邦层面行动建议的依据与议程底稿，推动“许可/并网流程/电力基础设施投资”成为数据中心扩张的关键约束议题。
- observable_features_at_time:
  - 证据等级为联邦机构顾问体系的正式报告（高等级）
  - 明确主题聚焦“AI与数据中心基础设施供电”，属于跨区域影响框架
  - 提供可复用信号：政策建议条款、关注的约束类别（并网、发电扩容、能效、审批/许可等）
  - 未必给出具体MW或项目清单（变化量可能为Unknown），但给出机制与政策工具箱
  - 影响范围：全国（跨ISO/公用事业/供应链）
  - 约束类型：并网/输变电、发电资源、设备与供应链、许可与审批、能效与需求侧管理（多选）
  - 适用于训练：出现“联邦政策议程/跨部门协调/规则优化”的关键词组合
  - 可与后续政策事件做映射（不在此处引用后验数字）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 头部智库/研究 | 2025-11-08 | https://itif.org/publications/2025/11/08/ten-recommendations-to-address-data-center-driven-load-growth/ | 将DOE相关建议纳入“数据中心负荷增长”治理框架，延续并扩展其政策含义
  - 律所/政策解读（行业权威） | 2025-10-27 | https://www.whitecase.com/insight-our-thinking/united-states-doe-directs-ferc-consider-reforms-accelerate-grid | 在“加速电网/并网改革”讨论中引用联邦层面议程与行动逻辑，体现报告框架的延续性

- sources (初报与当时材料):
  - initial_report: https://www.energy.gov/sites/default/files/2024-08/Recommendations%20on%20Powering%20AI%20and%20Data%20Center%20Infrastructure.pdf
  - time_slice_supporting: https://www.energy.gov/ (DOE官方站点相关发布与链接汇总，报告PDF为主证据)

- notes: 该条为“框架性政策信号”，对行业变量影响路径更偏中长期与制度端；observable_features以“条款/约束类别/证据等级”作为可复用特征。
---

---
## news_id: DCUS-2024-09-01
- domain: 数据中心
- initial_report_date: 2024-09-20
- title: Constellation与微软签署长期购电协议，推动Three Mile Island（TMI-1）重启，为数据中心提供稳定低碳电力
- label: Major
- hard_negative: false
- summary: 大型科技公司以长期PPA锁定核电“增量/重启”供给，标志“电力获取”上升为数据中心扩张的核心约束，并引发核电重启/融资/审批的连锁反应。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: “科技公司长期PPA→核电机组重启→新增可靠低碳供给→缓解数据中心用电约束”在后续被多次确认，并进一步触发监管审批节奏调整与联邦融资支持等二阶效应，强化“电力合同结构与供给可得性”对数据中心投运节奏的决定性作用。
- observable_features_at_time:
  - 变化量：机组重启目标、PPA年限（20年）在初报明确
  - 约束类型：供电/可靠性（基荷）、许可与监管审批（核电重启）、并网接入
  - 影响范围：跨公司（科技+发电商）且具示范效应（可迁移到其他区域与项目）
  - 初报属于公司披露/权威媒体同步报道（证据等级高）
  - 可复用信号：长期PPA、核电重启、为数据中心供电、时间表（投运/重启窗口）
  - 成本方向在初报阶段不一定明确（capex与电价结构未必披露），记为mixed
  - supply_demand方向偏“供给端扩容/锁定”导致约束缓解
  - 若训练“重大新闻”，该条具备“跨行业、改变供给结构、影响并网与融资”的典型特征

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体（Reuters） | 2025-02-19 | https://www.reuters.com/business/energy/big-tech-contracts-inject-life-into-new-nuclear-2025-02-19/ | 将微软-TMI重启作为“科技公司驱动核电复兴/满足数据中心负荷”的核心案例之一
  - 权威媒体（Reuters） | 2025-06-25 | https://www.reuters.com/sustainability/climate-energy/shut-three-mile-island-nuclear-plant-may-restart-2027-owner-says-2025-06-25/ | 更新重启推进与时间表，强调其与微软数据中心PPA绑定及对电力约束的意义
  - 监管/公共部门 | 2025-11-19 | https://www.reuters.com/business/energy/us-loans-constellation-1-billion-three-mile-island-reactor-reboot-2025-11-18/ | 联邦贷款支持被用于推进重启，体现“融资/政策工具”对落地的关键作用

- sources (初报与当时材料):
  - initial_report: https://www.constellationenergy.com/newsroom/2024/Constellation-to-Launch-Crane-Clean-Energy-Center-Restoring-Jobs-and-Carbon-Free-Power-to-The-Grid.html
  - time_slice_supporting: https://www.theguardian.com/environment/2024/sep/20/three-mile-island-nuclear-plant-reopen-microsoft

- notes: subsequent_impact_path仅描述机制链条；未引用后验量化（如具体投资额/就业/税收等）以避免后验污染。当时可观测特征以“PPA+核电重启+时间表+监管属性”作为可复用信号。
---

---
## news_id: DCUS-2024-09-02
- domain: 数据中心
- initial_report_date: 2024-09-11
- title: 弗吉尼亚州Fairfax County通过并生效数据中心分区修订（ZOA），提高准入门槛（Special Exception等）
- label: Major
- hard_negative: false
- summary: 作为全美数据中心最密集区域之一的周边县，Fairfax通过更严格的分区与噪声/选址标准，体现“地方许可/用地规则”对新增项目节奏与成本的硬约束上升。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: 更严格的县级用地规则在后续被法律/政策解读多次引用，并与北弗吉尼亚更广泛的“社区反弹→规则收紧→项目转移/拉长审批周期”路径相连，推动行业将“用地许可、噪声与社区兼容性”纳入选址与投运节奏的关键约束变量。
- observable_features_at_time:
  - 变化量：通过时间点（9/10采纳、9/11生效）明确
  - 约束类型：土地与许可（分区/特别许可）、噪声与建筑标准、与住宅距离等
  - 影响范围：县级但处于核心集群带（对区域选址具有外溢效应）
  - 证据等级：地方政府官方页面 + 当地权威媒体/报道
  - 可复用信号：Special Exception门槛、适用范围（哪些分区/哪些情形）、生效与追溯规则（是否grandfather）
  - 成本方向：审批成本/缓冲与设计标准趋严（up）
  - pace方向：新增项目审批节奏趋慢（delay）
  - supply_demand：短期可能抑制供给扩张，但也可能转移至邻县（mixed）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 律所/政策解读（行业权威） | 2025-03-07 | https://www.dlapiper.com/en/insights/publications/2025/03/recent-legislative-and-local-actions-affecting-data-center-development-in-virginia | 将Fairfax 2024-09规则收紧作为弗州数据中心监管趋势的重要组成
  - 律所/政策解读（行业权威） | 2025-03-17 | https://www.gibsondunn.com/when-data-center-developers-have-options-state-regulatory-treatment-is-key-to-success/ | 在讨论“开发选址与监管待遇”时明确提及Fairfax 2024-09收紧要求，体现其对行业决策变量的长期影响
  - 权威媒体深度（Business Insider） | 2025-06-17 | https://www.businessinsider.com/data-centers-northern-virginia-noise-air-pollution-cost-2025-5 | 将北弗州社区冲突与规则收紧并置，印证“地方许可/社区成本”成为扩张硬约束

- sources (初报与当时材料):
  - initial_report: https://www.ffxnow.com/2024/09/11/fairfax-county-approves-new-restrictions-on-data-centers-supervisors-says-theres-more-to-come/
  - time_slice_supporting: https://www.fairfaxcounty.gov/planning-development/data-centers, https://www.hklaw.com/en/insights/publications/2024/09/fairfax-county-virginia-approves-updated-zoning-regulations

- notes: 该事件的“结构性”主要体现在核心集群带的规则范式变化与外溢效应；对单个项目的MW影响需结合后续审批数据（此处不引用）。
---

---
## news_id: DCUS-2024-09-03
- domain: 数据中心
- initial_report_date: 2024-09-06
- title: ERCOT披露Large Load Queue与并网流程压力（数据中心等大负荷请求激增），电网侧“负荷并网”成为关键约束
- label: Major
- hard_negative: false
- summary: ERCOT以官方材料形式呈现大负荷接入队列与流程压力，后续演化为更系统的流程改革与监管讨论，强化“并网可得性/排队机制”对数据中心投运节奏的决定性。

- axes_and_direction:
  - pace: delay
  - cost: mixed
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: “大负荷队列膨胀→流程与规则改革（研究费、信息披露、验证负荷等）→并网与供电节奏受控”在后续被多次确认；ERCOT与PUCT逐步将大负荷并网纳入制度化治理框架，使德州数据中心扩张从“土地/税收”转向“并网流程与系统规划”约束主导。
- observable_features_at_time:
  - 证据等级：系统运营商官方披露（高等级）
  - 可复用信号：Large Load Queue规模/结构、流程节点（研究/接入/时间窗）、与系统规划联动
  - 约束类型：并网/输变电规划、流程规则（排队/研究）、电网可靠性
  - 影响范围：ERCOT全区（跨公用事业/跨项目）
  - pace：队列膨胀通常意味着接入周期拉长（delay）
  - cost：对开发商可能表现为更高的前期研究费/保证金/自建配套（mixed，初报阶段未必披露）
  - supply_demand：需求侧请求上行而系统承载与流程有限（tighten）
  - 变化量（GW等）若初报未给齐，可标Unknown；关键在“队列/流程压力”的硬信号

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 系统运营商（ERCOT） | 2025-09-15 | https://www.ercot.com/files/docs/2025/09/15/16.2-System-Planning-and-Weatherization-Update.pdf | 明确指出Large Load接入请求相对上一年显著上行，并将其作为系统规划关键问题持续跟踪
  - 权威行业媒体 | 2026-01-06 | https://www.utilitydive.com/news/ercots-large-load-queue-jumped-almost-300-last-year-official/808820/ | 将大负荷队列激增与流程“已被市场需求超出承载”联系，强化其对数据中心接入节奏的结构性影响
  - 监管侧材料（PUCT/公开文件） | 2025-12-24 | https://interchange.puc.texas.gov/Documents/55999_168_1550025.PDF | 以监管视角总结大负荷并网风险与流程调整方向，体现制度化治理落地

- sources (初报与当时材料):
  - initial_report: https://www.ercot.com/files/docs/2024/09/06/Large_Load_Queue_Status_Update.pdf
  - time_slice_supporting: https://www.ercot.com/services/rq/large-load-integration

- notes: 初报阶段更偏“系统运营商状态披露”，其“重大性”依赖后续是否进入规则改革与规划体系；后验来源显示该路径成立，因此标Major。
---

####################################################################################################

---
## news_id: DCUS-2024-07-11
- domain: 数据中心
- initial_report_date: 2024-07-17
- title: 纽约North Tonawanda以噪声/社区影响为由，对加密挖矿类“数据中心”实施两年新增/扩张禁令
- label: NotMajor
- hard_negative: true
- summary: 当时呈现“数据中心反弹与禁建”的强信号，但事件高度地方化且主要针对加密挖矿设施，未形成可外推的全国性规则变化或行业变量拐点。

- axes_and_direction:
  - pace: delay
  - cost: mixed
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: 地方禁令主要影响单一城市/单类设施（加密挖矿），未触发跨州规则或系统性并网/电价机制变更；后续更多被作为“局部社区反弹案例”引用，而非改变全美数据中心投运节奏的结构性事件。
- observable_features_at_time:
  - 变化量：禁令期限（两年）明确
  - 约束类型：土地与许可（地方禁令）、噪声扰民
  - 影响范围：单一城市（地方性强）
  - 目标对象更偏“加密挖矿数据中心/高噪声设施”（与主流云/AI数据中心不完全同构）
  - 证据等级：地方政府决策被媒体报道（中等）
  - 可复用信号：居民投诉集中于噪声/社区外部性；以“临时禁令/研究期”形式出现
  - cost方向不清晰（对行业整体影响弱，mixed）
  - hard negative特征：标题很像“禁建”，但难以满足“≥2独立来源确认对行业长期变量的影响”

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管/研究材料（NY DEC） | 2025-05-22 | https://dec.ny.gov/sites/default/files/2025-05/cryptocurrencygeis.pdf | 将该类事件纳入更大范围的加密挖矿/电力影响讨论，但未显示其对全国数据中心行业形成结构性变量改变
  - 权威媒体深度 | 2025-05-10 | https://insideclimatenews.org/news/10052025/new-york-bitcoin-mines-buying-up-power-plants/ | 作为地方案例被提及，更多体现“局部治理/社区外部性”而非全国性行业拐点

- sources (初报与当时材料):
  - initial_report: https://www.govtech.com/policy/north-tonawanda-n-y-bans-new-crypto-mining-for-2-years
  - time_slice_supporting: https://theminermag.com/news/2024-07-16/north-tonawanda-data-center-bitcoin-mining-ban

- notes: 该条作为hard negative适合训练“不要把地方性禁令误判为全国性行业拐点”；且对象偏加密挖矿，外推到AI数据中心需谨慎。
---

---
## news_id: DCUS-2024-07-12
- domain: 数据中心
- initial_report_date: 2024-07-11
- title: 德州Fort Worth规划/分区委员会否决Rock Creek数据中心方案（后续被市议会翻转）
- label: NotMajor
- hard_negative: true
- summary: 初报呈现“项目被否决”的强阻断信号，但随后市议会批准，说明该节点更多是地方审批过程波动，未形成持续的结构性阻断。

- axes_and_direction:
  - pace: mixed
  - cost: mixed
  - constraint: mixed
  - supply_demand: mixed

- subsequent_impact_path: “委员会否决→市议会批准→项目继续推进（但仍需后续步骤）”体现地方治理中审批节点可被翻转；后验看并未形成长期行业约束，仅是单项目/单城市的过程性波动。
- observable_features_at_time:
  - 变化量：否决投票结果与项目选址（靠近Tarleton State）在初报明确
  - 约束类型：土地与许可（分区/rezoning）、社区兼容性（噪声/景观/环境担忧）
  - 影响范围：单城单项目（地方性）
  - 证据等级：地方公共媒体报道（中等）
  - 可复用信号：以“委员会否决/市议会复议”形式出现，提示结果不确定性高
  - cost方向：不确定（可能增加缓冲/设计/法律成本）
  - hard negative关键：当时很像“项目被挡下”，但后验未形成持续阻断

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威地方媒体 | 2024-09-18 | https://www.keranews.org/business-economy/2024-09-18/controversial-southwest-fort-worth-data-center-gets-approval-but-more-steps-remain | 记录市议会批准并说明仍有后续流程，证明“否决”并非终局
  - 行业媒体/转载（GovTech/TNS） | 2024-09-18 | https://www.govtech.com/infrastructure/fort-worth-data-center-approved-over-residents-opposition | 以“批准”作为主叙事，印证审批翻转
  - 咨询/汇总（Data Center Watch） | 2025-05-?? | https://www.datacenterwatch.org/report | 将该项目归为“Delayed”而非“Blocked”，提示其并非结构性阻断

- sources (初报与当时材料):
  - initial_report: https://www.keranews.org/arts-culture/2024-07-11/plans-for-southwest-fort-worth-data-center-rejected-by-zoning-commission
  - time_slice_supporting: https://www.datacenterdynamics.com/en/news/fort-worth-planning-commission-votes-against-proposed-data-center-campus/

- notes: 该条是典型hard negative：初报“否决”很像重大事件，但后验显示只是审批过程中的可逆节点。
---

---
## news_id: DCUS-2024-08-11
- domain: 数据中心
- initial_report_date: 2024-08-22
- title: 密苏里Peculiar通过短期“数据中心申请/许可”暂停（100天moratorium），引发舆论关注
- label: NotMajor
- hard_negative: true
- summary: moratorium在传播上极像“全面禁建”，但属小城短期措施，主要反映地方社区反弹与程序性暂停；其对全国数据中心行业变量无稳定可验证的长期影响。

- axes_and_direction:
  - pace: delay
  - cost: mixed
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: 该事件后续更多作为“地方反弹案例库”出现；尽管对当地项目有实质影响，但未证实对全国装机/投运节奏、成本结构或并网规则产生可外推的长期改变，因此作为hard negative保留。
- observable_features_at_time:
  - 变化量：moratorium期限（100天）明确
  - 约束类型：土地与许可（暂停受理/审批）、地方治理与程序
  - 影响范围：单城（地方性强）
  - 初报通常伴随社区担忧（噪声/景观/资源消耗）但缺乏电网/并网层面制度变更
  - 证据等级：地方媒体（中等）
  - 可复用信号：短期暂停+“研究规则/修订条例”的典型句式
  - 对行业供需与成本的外推证据不足（mixed）
  - hard negative：当时很像“行业逆风拐点”，但缺乏跨区域确认

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 地方电视台/媒体 | 2024-10-21 | https://www.kshb.com/news/local-news/peculiar-reverses-zoning-for-data-center-after-cries-from-neighbors | 记录地方层面条例/流程演化，体现“地方治理事件”属性
  - 行业媒体 | 2024-10-23 | https://www.datacenterdynamics.com/en/news/peculiar-officials-in-missouri-remove-data-centers-from-ordinance-blocking-15bn-diode-project/ | 说明其影响主要局限于当地分区层面
  - 权威媒体深度 | 2024-10-05 | https://www.washingtonpost.com/technology/2024/10/05/data-center-protest-community-resistance/ | 将其置于“社区反弹”叙事中，未将其上升为全国行业变量拐点

- sources (初报与当时材料):
  - initial_report: https://tribuneandtimes.com/stories/moratorium-halts-peculiar-data-center-plans%2C27277
  - time_slice_supporting: https://www.datacenterwatch.org/report (作为当时后续跟踪入口；不等同初报)

- notes: 对当地可能是重大，但用户任务口径为“美国数据中心行业重大新闻”，需能改变行业硬约束/拐点；该条更适合作为“看似重大但地方性”的hard negative。
---

---
## news_id: DCUS-2024-08-12
- domain: 数据中心
- initial_report_date: 2024-08-19
- title: 弗州Richmond周边两项数据中心方案被地方机构“defer/延后决定”（Powhatan、DC Blox等），体现审批摩擦但非结构性拐点
- label: NotMajor
- hard_negative: true
- summary: 初报呈现“项目被卡住/延后”的强信号，但后续一个项目获批、另一个调整/撤回再推进，说明其更像地方审批摩擦与项目修订，而非行业层面硬约束的稳定变化。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: mixed
  - supply_demand: mixed

- subsequent_impact_path: “延后→补充条件/修改方案→获批或撤回后以更小/不同路径推进”说明地方审批并非单向收紧或释放；对行业层面的长期变量难以形成多源一致确认，因此作为hard negative保留用于训练。
- observable_features_at_time:
  - 变化量：被defer的审批节点、涉及的县/项目方在初报明确
  - 约束类型：土地与许可（rezoning/CUP/地方规划委员会）、社区兼容性（噪声/外观等）
  - 影响范围：地方性（Richmond周边），不构成跨区域规则变更
  - 可复用信号：defer/延后、要求补充材料/调整设计、社区反对声音
  - cost方向：为满足条件可能提高缓冲/设计/合规成本（up）
  - pace方向不确定：可能延后也可能快速修订后通过（mixed）
  - 证据等级：行业媒体（中高）+ 后续地方/行业跟踪

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威行业媒体 | 2024-10-30 | https://virginiabusiness.com/powhatan-approves-2-7b-data-center-campus/ | 证明“延后”并非终局，至少部分项目后续获批
  - 咨询/汇总（Data Center Watch） | 2025-05-?? | https://www.datacenterwatch.org/report | 记录DC Blox等项目撤回/缩小/再推进路径，支持“过程性摩擦而非结构性拐点”的判断

- sources (初报与当时材料):
  - initial_report: https://www.datacenterdynamics.com/en/news/proposals-for-two-data-center-projects-in-richmond-virginia-deferred-by-local-officials/
  - time_slice_supporting: https://www.powhatanva.gov/DocumentCenter/View/8545/Planning-Zoning-Case-Information-July-2024 (地方议题列表/会议材料入口，作为当时背景支持)

- notes: 该条用于训练“把defer误判为永久阻断”的风险；其后验路径并未形成可外推的行业级硬约束变化。
---

---
## news_id: DCUS-2024-07-13
- domain: 数据中心
- initial_report_date: 2024-07-16
- title: 弗州Fauquier County“Catlett Station”数据中心拟议项目撤回rezoning申请（地方反对后退场）
- label: NotMajor
- hard_negative: true
- summary: 初报呈现“项目撤回”的强阻断信号，但属于单县单项目事件，更多反映地方阻力而非全国性装机/投运节奏拐点；后续主要被作为案例汇总引用。

- axes_and_direction:
  - pace: delay
  - cost: mixed
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: 事件后续主要进入“地方反弹/项目撤回案例库”，未形成跨州/跨ISO规则变化或行业层面硬约束的稳定确认，因此标记为hard negative：当时很像“数据中心扩张受阻拐点”，但后验无法满足“多源确认其对行业长期变量的影响”门槛。
- observable_features_at_time:
  - 变化量：撤回rezoning申请（硬结果）在初报明确
  - 约束类型：土地与许可（rezoning撤回）、社区外部性争议（噪声/水/电等常见议题）
  - 影响范围：单县单项目（地方性）
  - 证据等级：地方媒体/其社交媒体发布（低~中；需谨慎）
  - 可复用信号：撤回发生在听证/审议前后；“社区反对→申请撤回”的典型模式
  - 成本/供需对全国行业外推不足（mixed）
  - hard negative关键：撤回很吸睛，但外溢性弱

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 咨询/汇总（Data Center Watch） | 2025-05-?? | https://www.datacenterwatch.org/report | 将该项目列为Blocked并给出撤回时间点，显示其主要作为案例被汇总而非行业拐点
  - 行业媒体二次报道 | 2024-07-18 | https://www.datacenterdynamics.com/en/news/virginias-pittsylvania-supervisors-approve-rezoning-of-945-acres-for-data-center/ | 文中提及相关区域项目动态并引用地方报道（侧面印证“地方案例集合”属性；非全国性规则变化）

- sources (初报与当时材料):
  - initial_report: https://www.facebook.com/FauquierNow/posts/headwaters-site-development-llc-has-officially-withdrawn-its-rezoning-applicatio/986712356796951/
  - time_slice_supporting: https://static1.squarespace.com/static/67819031da098341c45ac84a/t/6849bcfe640a951f79e00715/1749662975141/Data%2BCenter%2BWatch%2BReport%2B.pdf

- notes: 初报URL为地方媒体社交媒体发布，证据等级低于官网/主流媒体；作为hard negative可接受，但若用于高置信训练样本建议后续补齐原始新闻网页或政府撤回文件链接。
---

####################################################################################################

---
## Unlabeled
- notes: 本时间段内可稳定确认的Major已覆盖“电力/容量市场冲击、联邦政策议程、核电供给重启、核心集群带地方用地规则收紧、ERCOT大负荷并网队列压力”五类结构性主题；其余Q3新闻大量为单项目审批过程/地方争议，难以在后验满足“≥2独立来源确认对行业长期变量影响”的门槛，故未额外扩展Unlabeled条目以避免噪声样本。
---

# 数据中心-美国-2024Q4 标注集（hindsight）

---
## news_id: DCUS-2024-10-01
- domain: 数据中心
- initial_report_date: 2024-10-10
- title: Big Tech在俄亥俄数据中心电价/接入规则争议中提交替代方案（AEP Ohio“大负荷”规则博弈）
- label: Major
- hard_negative: false
- summary: 俄亥俄出现围绕数据中心“谁为电网升级买单/如何设最低用电与担保”的监管博弈，成为后续多州大负荷费率设计的样板事件。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 后续各州围绕数据中心/大负荷推出“最低需求/退出费/担保/专门费率”等机制；俄亥俄案件在2025年进入监管落地阶段，被行业解读为风险向大负荷转移、并网与投运节奏更依赖监管规则与担保能力。
- observable_features_at_time:
  - 争议核心：AEP Ohio提出对数据中心/加密矿等大负荷要求预付款、财务担保与成本分摊（初报已点明“被请求压垮”与暂停新合同）。
  - 参与方：微软、Alphabet、Meta、亚马逊等联手提交替代框架（多方博弈信号强）。
  - 适用门槛：替代框架将规则扩展到单点>50MW的工业客户（阈值明确）。
  - 关键约束类型：并网/电网升级成本回收、费率与合同条款（最低需求、担保、退出费等）。
  - 影响范围：跨行业（不仅数据中心），具潜在可复制性（“precedent”特征）。
  - 变化量：MW与费用细节在初报中未完全披露（Unknown），但“暂停新合同”属于硬动作。
  - 证据等级：权威媒体+监管文件（Reuters基于监管文件）。
  - 时间表：PUCO需批准任何和解/规则（监管不确定性→节奏风险）。
- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管/权威行业媒体 | 2025-07-10 | https://www.utilitydive.com/news/Ohio-regulators-approve-aep-data-center-interconnection-rules/752690/ | 俄亥俄监管机构在后续程序中推动AEP数据中心接入/担保等规则落地，印证其对并网门槛与节奏的结构性影响
  - 律所/研究解读 | 2025-03-17 | https://www.gibsondunn.com/when-data-center-developers-have-options-state-regulatory-treatment-is-key-to-success/ | 总结2024年以来多州“数据中心/大负荷专门费率与最低需求/退出费”趋势，并点名俄亥俄AEP案例为关键样本
- sources (初报与当时材料):
  - initial_report: https://www.reuters.com/technology/big-tech-proposes-power-rate-terms-ohio-data-center-fight-2024-10-10/
  - time_slice_supporting: https://www.reuters.com/technology/big-tech-proposes-power-rate-terms-ohio-data-center-fight-2024-10-10/
- notes: 初报的“替代框架”本身不等于最终规则，但后续监管推进证明其对风险分摊与并网门槛具有可复制的制度意义。
---
## news_id: DCUS-2024-11-01
- domain: 数据中心
- initial_report_date: 2024-11-01
- title: FERC否决PJM/Talen核电站点内数据中心扩容的修订并网协议（Susquehanna“共址负荷”争议）
- label: Major
- hard_negative: false
- summary: 联邦层面首次以“费率外溢/可靠性风险”为由否决核电站点内数据中心扩容并网安排，触发对共址负荷规则的系统性补课。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 共址负荷（发电侧“背靠背”供电）被证明不是“免排队/免系统成本”的捷径；后续FERC要求PJM建立更透明的共址负荷规则与服务，推动大负荷接入从个案博弈转向制度化约束与成本分摊框架。
- observable_features_at_time:
  - 项目形态：数据中心直接连接发电侧（核电站点内），属于典型“共址/旁路电网”路径。
  - 变化量：拟将站内数据中心容量从约300MW提升至480MW（MW级硬量）。
  - 约束类型：并网/可交付性、区域电价与成本外溢、系统可靠性。
  - 监管信号：FERC明确提到可能抬升公众电费与影响电网可靠性（硬风险叙述）。
  - 影响范围：PJM区域可复制性强（共址负荷/自备电厂+数据中心在多州扩散）。
  - 证据等级：联邦监管机构裁决/官方材料+权威媒体报道。
  - 时间表：裁决即刻改变该路径的“投运假设”（节奏直接受限）。
- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管机构/官方说明 | 2025-12-18 | https://www.ferc.gov/news-events/news/fact-sheet-ferc-directs-nations-largest-grid-operator-create-new-rules-embrace | FERC明确要求PJM建立共址负荷（含数据中心）透明规则，以保护可靠性与消费者
  - 权威媒体 | 2025-12-18 | https://www.reuters.com/business/energy/us-energy-regulator-directs-pjm-launch-rules-ai-connections-2025-12-18/ | 报道指出FERC指令与“共址数据中心/大负荷”争议直接相关，形成制度化后续
  - 权威媒体 | 2026-01-27 | https://www.reuters.com/business/energy/us-grid-rules-faster-data-centers-favor-on-site-gas-plants--reeii-2026-01-27/ | 报道PJM提出更快接入方案并回溯FERC对共址负荷规则的推动，体现行业层面长期影响
- sources (初报与当时材料):
  - initial_report: https://www.reuters.com/business/energy/us-regulators-reject-amended-interconnect-agreement-amazon-data-center-2024-11-02/
  - time_slice_supporting: https://www.ferc.gov/news-events/news/chairman-phillips-dissent-pjms-s-susquehanna-co-location-proposal-er24-2172
- notes: 这是“共址负荷”从项目工程问题上升为费率与可靠性制度问题的拐点；后续规则化进程证明其结构性。
---
## news_id: DCUS-2024-11-02
- domain: 数据中心
- initial_report_date: 2024-11-07
- title: Duke提出对>100MW数据中心引入“minimum take/take-or-pay”条款以降低搁置风险与成本外溢
- label: Major
- hard_negative: false
- summary: 公用事业通过最低需求/预付与长期合同把“数据中心波动/弃用”风险内生化，成为后续多州大负荷费率的关键工具。

- axes_and_direction:
  - pace: accelerate
  - cost: up
  - constraint: loosen
  - supply_demand: mixed

- subsequent_impact_path: “最低需求+长期合同+基础设施出资”成为公用事业愿意更快配套电网/电源扩张的前提；在多州扩散为大负荷专门费率与合同模板，改变数据中心选址与投运的可行性边界（能谈下合同→更可能拿到电）。
- observable_features_at_time:
  - 合同机制：>100MW单点负荷触发最低用电付款（take-or-pay）。
  - 约束类型：电网/电源扩建成本回收、费率外溢、客户退出/搁置风险。
  - 影响范围：Duke多州供区（NC/SC/FL/IN/OH/KY等）具扩散潜力。
  - 变化量：目标新增数据中心规模约2GW（公司披露口径）。
  - 时间表：协议需监管批准，且“先签意向/后定最终供电合同”的节奏特征明显。
  - 证据等级：权威媒体采访+后续行业研究/监管讨论可验证。
  - 可复用信号：触发阈值（100MW）、合同年限（常见10–15年，初报未完全量化则Unknown）。
- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 研究报告 | 2025-01-28 | https://energyfuturesgroup.com/wp-content/uploads/2025/01/Review-of-Large-Load-Tariffs-to-Identify-Safeguards-and-Protections-for-Existing-Ratepayers-Report-Final.pdf | 总结“最低需求/预付/保障现有用户”设计，并明确提到Duke采用minimum-take条款作为风险控制
  - 行业媒体 | 2025-04-09 | https://www.tdworld.com/utility-business/article/55279938/win-win-tariff-design-for-data-centers-and-utilities | 讨论数据中心与公用事业的“win-win tariff”与take-or-pay/最低需求在多州扩散的趋势
  - 律所/监管跟踪 | 2025-08-01 | https://www.nelsonmullins.com/insights/blogs/megawatt-minute-blog/power-generation/developments-on-how-duke-energy-integrates-data-centers-and-other-new-large-load-customers-in-north-carolina | 描述北卡监管对Duke大负荷/数据中心接入与报告要求的制度化推进，印证其长期影响
- sources (初报与当时材料):
  - initial_report: https://www.reuters.com/business/energy/duke-energys-new-2-gws-us-data-centers-include-minimum-take-agreements-cfo-says-2024-11-07/
  - time_slice_supporting: https://www.utilitydive.com/news/duke-energy-data-centers-load-growth-q3-earnings/732491/
- notes: 该事件的“重大性”不在单一项目，而在合同/费率范式改变——把供电不确定性显性定价并制度化。
---
## news_id: DCUS-2024-12-01
- domain: 数据中心
- initial_report_date: 2024-12-04
- title: Meta宣布在路易斯安那州建设$100亿、4百万平方英尺AI数据中心（Richland Parish），并与公用事业协调供电
- label: Major
- hard_negative: false
- summary: 头部公司以“超大单体+长期建设周期+电力配套”方式锁定算力，触发地方电源/输电投资与监管审批链条。

- axes_and_direction:
  - pace: accelerate
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 超大型园区落地推动当地公用事业与监管机构围绕发电与输电扩建、可再生匹配与融资结构做专项安排；该类“单体巨型AI数据中心”成为电力系统中可见的大负荷增量，抬升区域资源充裕度门槛并带动电源侧投资。
- observable_features_at_time:
  - 项目规模：投资额约$100亿；建筑面积约400万平方英尺（硬量）。
  - 时间表：建设预计延续至2030（长期工期信号）。
  - 约束类型：电力接入/电源与输电配套、可再生匹配承诺、地方审批与基础设施。
  - 影响范围：对Entergy等区域公用事业供区与LPSC监管审批具有外溢。
  - 供需轴：超大负荷一次性锁定→区域负荷曲线抬升。
  - 证据等级：公司披露/官方经济发展机构+权威媒体。
  - 缺失字段：首期投运窗口、合同电价与确切MW（初报多为定性或Unknown）。
- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体（监管审批） | 2025-08-20 | https://www.reuters.com/business/energy/entergy-receives-regulatory-approval-investments-support-metas-louisiana-data-2025-08-20/ | 报道LPSC批准Entergy为该项目进行发电与输电投资，证明其对电力系统投资与投运路径产生长期影响
  - 权威媒体（融资结构） | 2025-10-21 | https://www.reuters.com/technology/meta-forms-joint-venture-with-blue-owl-capital-louisiana-data-center-2025-10-21/ | 报道Meta为该数据中心达成巨额融资/合资安排，反映其资本结构与建设路径的持续确认
- sources (初报与当时材料):
  - initial_report: https://www.reuters.com/technology/meta-invest-10-billion-louisiana-data-center-2024-12-04/
  - time_slice_supporting: https://www.opportunitylouisiana.gov/news/meta-selects-northeast-louisiana-as-site-of-10-billion-artificial-intelligence-optimized-data-center-governor-jeff-landry-calls-investment-a-new-chapter-for-state, https://apnews.com/article/musk-meta-artificial-intelligence-data-center-1cf320ad4d50bff8d3fac4d0535a0004
- notes: 重大性来自“超大单体负荷→电源/输电/融资/监管全链条跟随”，而非一般性选址新闻。
---
## news_id: DCUS-2024-12-02
- domain: 数据中心
- initial_report_date: 2024-12-17
- title: NERC发布十年可靠性评估：数据中心等大负荷推动需求上行，约半数美国地区面临更高短缺风险
- label: Major
- hard_negative: false
- summary: 北美可靠性机构把数据中心明确写入“需求增量核心驱动”，将其从产业新闻提升为系统可靠性与资源充裕度约束问题。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 可靠性评估把“数据中心需求增长”固化为系统级规划输入，推动监管/ISO/公用事业在资源充裕度、并网流程与负荷建模上加码；后续评估与政府/监管材料持续引用并扩展“Large Loads”工作机制，形成长期约束叙事。
- observable_features_at_time:
  - 机构属性：NERC为北美电网可靠性关键机构（高证据等级）。
  - 机制：需求增长（含数据中心）>供给与电网建设速度，叠加机组退役→资源充裕度下滑。
  - 影响范围：全国（多区域被评为高/更高风险）。
  - 约束类型：资源充裕度（RA）、冬夏峰值、退役节奏、输电/燃料链。
  - 变化量：报告提供区域风险分布与需求增长（具体数值可查，但初报总结为“约半数美国风险上升”）。
  - 可复用信号：官方风险评级、退役容量披露、需求驱动拆解（数据中心/电气化/制造业等）。
- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管/可靠性机构 | 2026-01-23 | https://www.nerc.com/globalassets/our-work/assessments/nerc_ltra_2025.pdf | 后续LTRA继续将大负荷/数据中心纳入需求与可靠性评估框架，体现持续性（系统级约束未消失）
  - 权威行业媒体 | 2026-01-30 | https://www.utilitydive.com/news/nerc-10-year-peak-demand-forecast-jumps-24-on-new-data-center-loads/810955/ | 报道指出新一轮需求预测上修主要来自新增数据中心负荷，印证“数据中心→可靠性约束”成为长期主线
- sources (初报与当时材料):
  - initial_report: https://www.reuters.com/business/energy/half-us-high-risk-power-shortfall-next-decade-regulator-says-2024-12-17/
  - time_slice_supporting: https://www.nerc.com/globalassets/our-work/assessments/2024-ltra_corrected_july_2025.pdf
- notes: 初报为媒体摘要，但其“系统级评估把数据中心纳入核心驱动”这一点稳定且可复用；避免把后验量化数字当作当时可见信号。
---
## news_id: DCUS-2024-12-03
- domain: 数据中心
- initial_report_date: 2024-12-02
- title: MISO发布长期负荷预测白皮书：数据中心成为新增负荷的主要驱动之一（需求增速假设上修）
- label: Major
- hard_negative: false
- summary: RTO将数据中心从“局部大负荷”提升为中长期负荷预测的核心驱动，影响资源充裕度与输电/电源投资的基线假设。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 负荷预测方法调整（数据中心/工业/交通为新驱动）抬升规划需求与不确定性管理的重要性；被市场监测机构与咨询/媒体引用，用于讨论MISO紧储备、容量市场与资源扩张压力，间接影响数据中心在MISO区域的“可投运容量”判断。
- observable_features_at_time:
  - 报告硬信息：白皮书明确把数据中心列为主要驱动，且提到不同LRZ差异（位置维度）。
  - 变化量：白皮书给出需求增速区间（1–2%/年等），相对既有情景上修（方向明确）。
  - 约束类型：资源充裕度、容量市场信号、输电规划、负荷预测不确定性。
  - 影响范围：MISO 15州大区，覆盖多个潜在数据中心落点。
  - 可复用信号：RTO公开预测更新、方法论变化、驱动因素替换（从EV/电气化转向数据中心等）。
  - 缺失字段：对单一数据中心项目的MW/COD并不披露（Unknown），但“系统级驱动”足够硬。
- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威资讯/行业研究 | 2025-04-21 | https://www.spglobal.com/market-intelligence/en/news-insights/articles/2025/4/outlook-2025-miso-to-see-net-addition-of-9-gw-may-face-tight-reserves-88352819 | 引用并解读MISO在2024年12月更新负荷预测、把数据中心等作为新驱动，并关联到储备趋紧与资源扩张压力
  - 市场监测机构报告 | 2025-06-26 | https://www.potomaceconomics.com/wp-content/uploads/2025/06/2024-MISO-SOM_Report_Body_Final.pdf | 独立市场监测报告引用MISO 2024年12月负荷预测白皮书，用于讨论未来市场需求与容量/需求响应等结构性变化
- sources (初报与当时材料):
  - initial_report: https://cdn.misoenergy.org/MISO%20Long-Term%20Load%20Forecast%20Whitepaper_December%202024667166.pdf
  - time_slice_supporting: https://cdn.misoenergy.org/20241218%20Medium%20and%20Long%20Term%20Forecast%20Workshop%20Presentation667265.pdf, https://www.misoenergy.org/engage/stakeholder-feedback/2024/medium-and-long-term-load-forecast-workshop-load-forecast-white-paper-20241218/
- notes: 这是“系统运营商口径”的供需拐点信号；但具体到项目级投运仍需并网与资源充裕度约束细化。
---
## news_id: DCUS-2024-12-04
- domain: 数据中心
- initial_report_date: 2024-12-20
- title: DOE/LBNL发布美国数据中心用电报告：到2028年用电可能翻倍或三倍，电力占比显著上行
- label: Major
- hard_negative: false
- summary: 联邦研究将数据中心用电从“估算/传闻”提升为可引用的官方区间预测，推动监管与公用事业把其纳入负荷与可靠性主线。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 官方预测区间被频繁引用，成为“数据中心→电力系统压力”的证据底座；后续监管/可靠性讨论中用于支撑大负荷接入规则、负荷预测、可靠性与成本分摊议题，使行业从“项目新闻”转向“系统约束量化”。
- observable_features_at_time:
  - 报告主体：DOE发布、LBNL出具（证据等级高）。
  - 变化量：给出到2028年的用电/功率区间与占比上升（初报即为核心硬信息）。
  - 驱动机制：AI/GPU服务器带来能耗结构变化（方向明确）。
  - 约束类型：电力供给、输电、冷却/能效、数据透明度。
  - 可复用信号：官方建议“定期更新/提升数据透明度”→政策接口。
  - 缺失字段：对区域（州/县）分布并非初报重点（Unknown）。
- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威行业媒体 | 2025-10-22 | https://www.utilitydive.com/news/data-center-grid-reliability-ferc-nerc/803467/ | 在讨论可靠性与大负荷时引用DOE对数据中心用电占比上升的区间，体现其成为长期政策/监管论据
  - 国会研究机构 | 2026-01-23 | https://www.congress.gov/crs-product/R48646 | CRS综述数据中心能耗与政策含义，延续并吸收官方与行业预测框架，证明其影响进入公共政策层
- sources (初报与当时材料):
  - initial_report: https://www.energy.gov/articles/doe-releases-new-report-evaluating-increase-electricity-demand-data-centers
  - time_slice_supporting: https://www.reuters.com/business/energy/us-data-center-power-use-could-nearly-triple-by-2028-doe-backed-report-says-2024-12-20/
- notes: 该事件是“数据中心能耗定量化”的关键节点；但训练数据抽取时需避免把后续更新数字当作当时可见信息。
---
## news_id: DCUS-2024-10-02
- domain: 数据中心
- initial_report_date: 2024-10-18
- title: 亚特兰大拟通过条例允许部分社区引入数据中心（West End/Adair Park），引发居民与保护组织反对
- label: NotMajor
- hard_negative: true
- summary: 看似会放松城市核心区对数据中心的限制，但很快被市议会“搁置/归档”，未形成可复制的制度宽松。

- axes_and_direction:
  - pace: uncertain
  - cost: mixed
  - constraint: mixed
  - supply_demand: uncertain

- subsequent_impact_path: 初报阶段只是进入听证/评估流程；随后市议会在同年12月直接搁置该提案。结果是“潜在放松”没有落地，也未触发全国层面的规则迁移，只是一个城市内部土地使用争议案例。
- observable_features_at_time:
  - 政策性质：地方土地使用条例（影响边界天然局部）。
  - 争议焦点：数据中心占地但就业少、与住房/商业机会冲突（典型NIMBY冲突信号）。
  - 影响范围：亚特兰大特定社区；不涉及州或联邦层面。
  - 约束类型：土地/规划许可（而非并网/系统费率规则）。
  - 变化量：未披露具体MW/投运窗口（Unknown）。
  - 证据等级：权威地方媒体报道与市政流程（较高但局部）。
- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威地方媒体 | 2024-12-03 | https://www.axios.com/local/atlanta/2024/12/03/data-centers-west-end | 市议会“file/搁置”提案，直接否定其政策落地可能
  - 政策/媒体回顾 | 2026-01-15 | https://www.multistate.us/insider/2026/1/15/state-data-center-legislation-faces-local-zoning-battles | 回顾把亚特兰大作为“地方管控/争议”案例，而非全国规则拐点
- sources (初报与当时材料):
  - initial_report: https://www.axios.com/local/atlanta/2024/10/18/atlanta-data-centers
  - time_slice_supporting: https://www.axios.com/local/atlanta/2024/12/03/data-centers-west-end
- notes: hard negative理由：当时“可能放松”的叙事很像重大政策转向，但两个月内被搁置，未形成跨区域可复制制度。
---
## news_id: DCUS-2024-11-03
- domain: 数据中心
- initial_report_date: 2024-11-11
- title: 律所解读FERC否决核电站点内数据中心并网修订：提出“接下来怎么办”的一揽子问题
- label: Unlabeled
- hard_negative: true
- summary: 文章热度高、讨论宏大，但本质是解读与推演，不是规则变更或项目落地，无法单独构成结构性冲击。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 该类解读在后续并未直接对应某个落地机制；真正的制度变化来自FERC在2025年末对PJM发出规则制定指令。因而该“解读稿”本身不应被标为重大事件，而应视作对重大事件的二次传播。
- observable_features_at_time:
  - 内容属性：法律解读/观点文章（非监管裁决、非ISO规则、非项目业主披露）。
  - 讨论对象：共址负荷的费率与可靠性风险（框架性但不含新条款）。
  - 变化量：无MW/时间表/条款生效日期（Unknown）。
  - 证据等级：二手解读（低于监管/系统运营商/公用事业/公司披露）。
  - 可复用信号：高热度但“无硬信息”是典型hard-negative特征。
- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管机构/官方说明 | 2025-12-18 | https://www.ferc.gov/news-events/news/fact-sheet-ferc-directs-nations-largest-grid-operator-create-new-rules-embrace | 真正制度化动作来自FERC对PJM的规则指令，而非早期解读文章
  - 权威媒体 | 2025-12-18 | https://www.reuters.com/business/energy/us-energy-regulator-directs-pjm-launch-rules-ai-connections-2025-12-18/ | 权威媒体把后续影响锚定在监管指令与规则制定层面
- sources (初报与当时材料):
  - initial_report: https://www.klgates.com/FERCs-Rejection-of-Data-Center-Co-Location-Amendments-to-a-Pennsylvania-Nuclear-Power-Plants-Interconnection-Agreement-Raises-Big-Questions-About-Whats-Next-11-11-2024
  - time_slice_supporting: https://www.reuters.com/business/energy/us-regulators-reject-amended-interconnect-agreement-amazon-data-center-2024-11-02/
- notes: hard negative理由：传播度/讨论度高，但缺少“可执行条款或落地事实”，训练时应避免把“解读热度”当作重大性。
---
## news_id: DCUS-2024-11-04
- domain: 数据中心
- initial_report_date: 2024-11-20
- title: 加州Monterey Park在Saturn Park片区引入“数据中心需Development Agreement”机制（地方管控尝试）
- label: NotMajor
- hard_negative: true
- summary: 城市层面给数据中心设置更高门槛，但影响半径局部，且后续主要演化为本地争议与更严格的地方措施，未形成全国性供给约束拐点。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: uncertain

- subsequent_impact_path: 该机制更多体现地方对噪声/能源/环境正当性的审查升级；后续虽出现更严格的本地暂缓措施，但仍属于单城市治理，不足以满足“多源确认的行业长期影响”门槛，因此应作为hard negative保留。
- observable_features_at_time:
  - 政策层级：市政法规（天然局部）。
  - 条款形式：数据中心仅能通过development agreement获批（许可门槛硬化）。
  - 约束类型：土地/规划许可+环境与能源使用担忧（条文中直接点名“energy hungry”）。
  - 变化量：未给出MW/投运窗口（Unknown）。
  - 影响范围：Saturn Park片区，非州/联邦规则。
  - 证据等级：市政法规定稿/法典（硬证据，但外溢弱）。
- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 行业媒体 | 2026-01-26 | https://www.datacenterdynamics.com/en/news/45-day-data-center-moratorium-passed-in-monterey-park-california-with-more-permanent-regulations-to-come/ | 后续发展仍围绕本地项目与地方暂停措施，证明其影响未外溢为全国性约束
  - 市政信息（佐证局部性） | 2026-01-28 | https://www.montereypark.ca.gov/1710/Data-Center-Information | 城市把该议题作为单一项目/片区治理事项持续处理（局部性持续）
- sources (初报与当时材料):
  - initial_report: https://ecode360.com/MO4971/laws/LF2215004.pdf
  - time_slice_supporting: https://ecode360.com/43883690
- notes: hard negative理由：当时“地方严监管”叙事容易被误判为行业供给拐点，但证据显示其长期仍局限于单城市治理与单项目争议。
---
## news_id: DCUS-2024-12-05
- domain: 数据中心
- initial_report_date: 2024-12-09
- title: MISO在FERC“大负荷”程序中表示不建议建立新的“负荷排队研究”流程（认为不一定更快、也不解决共址需求）
- label: NotMajor
- hard_negative: true
- summary: 听起来像是对“数据中心负荷如何排队/研究”的制度回应，但本质是意见文件，不是新规则，且结论偏“维持现状”。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 该文件没有形成可执行的新流程；后续行业变化更多体现为各RTO/监管机构围绕共址负荷与大负荷费率做规则化，而不是统一建立“负荷并网排队”机制。因此该条不满足“多源确认长期影响”的门槛，作为hard negative更合适。
- observable_features_at_time:
  - 文件属性：对FERC程序的书面意见（非关税条款生效、非市场规则修改）。
  - 核心观点：不建议新建负荷排队流程，认为不提升“speed to market”（硬表述）。
  - 约束类型：并网研究流程/规划协调，但缺乏强制性条款。
  - 影响范围：MISO立场披露，不等于跨RTO制度变更。
  - 变化量：无新增阈值/费用/时间表（Unknown）。
  - 证据等级：系统运营商文件（可信，但“影响=有限”）。
- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管机构/官方说明 | 2025-12-18 | https://www.ferc.gov/news-events/news/fact-sheet-ferc-directs-nations-largest-grid-operator-create-new-rules-embrace | 后续联邦层面更聚焦共址负荷规则透明化，而非统一“负荷排队”新流程
  - 权威媒体 | 2026-01-27 | https://www.reuters.com/business/energy/us-grid-rules-faster-data-centers-favor-on-site-gas-plants--reeii-2026-01-27/ | 后续报道显示行业路径转向“共址/自建电源+规则服务”，并未出现统一的负荷排队制度落地
- sources (初报与当时材料):
  - initial_report: https://cdn.misoenergy.org/2024-12-09%20Docket%20No.%20AD24-11-000666011.pdf
  - time_slice_supporting: https://cdn.misoenergy.org/2024-12-09%20Docket%20No.%20AD24-11-000666011.pdf
- notes: hard negative理由：当时像“制度回应”，但其实是立场文件且偏维持现状；后续也未被多源确认产生结构性行业变量变化。
---
## news_id: DCUS-2024-11-05
- domain: 数据中心
- initial_report_date: 2024-11-14
- title: AEP与Bloom宣布最高1GW燃料电池采购框架以“更快”为数据中心等大负荷供电（把电源搬到负荷侧）
- label: NotMajor
- hard_negative: true
- summary: 当时叙事很像“快速破解并网瓶颈”的重大方案，但后续更多停留在框架/订单与资本市场叙事，缺少多源确认其在AEP辖区形成可复制的大规模落地。

- axes_and_direction:
  - pace: uncertain
  - cost: mixed
  - constraint: mixed
  - supply_demand: uncertain

- subsequent_impact_path: 后续资料显示AEP仍通过大规模资本开支与传统电网扩建来应对数据中心需求；燃料电池更多作为补充性路径而非主流可复制的“结构性解法”。因此该条作为hard negative更能帮助模型识别：大额“框架协议/技术路径宣示”不等于行业变量已被长期改写。
- observable_features_at_time:
  - 形态：分布式电源共址于客户侧（绕开部分电网建设周期的叙事）。
  - 变化量：最高1GW框架，首期订单约100MW并提及后续扩展（数量级大但分期不确定）。
  - 约束类型：电网接入时滞、供电可靠性、燃料（天然气/氢）与排放合规。
  - 影响范围：AEP多州供区潜在适用，但落地依赖客户签约与监管/许可。
  - 证据等级：公司披露+行业媒体报道（缺少监管/ISO层面确认其系统性替代作用）。
  - 缺失字段：具体站点、投运窗口、与电网互联规则（Unknown）。
- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体（公司层面“仍需扩建电网”） | 2025-10-29 | https://www.reuters.com/business/energy/utility-aep-raises-capital-spending-plan-meet-data-center-power-demand-2025-10-29/ | AEP因数据中心需求上调多年资本开支计划，表明并网/扩网仍是主路径，框架协议未单独解决结构性瓶颈
  - 金融媒体（更多呈现为资本市场叙事） | 2026-01-?? | https://www.barrons.com/articles/bloom-energy-stock-fuel-cells-aep-b7fbfe11 | 后续报道更多围绕Bloom订单与资本市场解读，缺少监管/ISO/多项目层面的“行业长期影响”确认
- sources (初报与当时材料):
  - initial_report: https://www.aep.com/news/stories/view/9866/AEP-Leveraging-Fuel-Cell-Technology-to-Power-Data-Center-Growth/
  - time_slice_supporting: https://www.utilitydive.com/news/aep-bloom-energy-fuel-cell-data-center/733150/, https://investor.bloomenergy.com/press-releases/press-release-details/2024/Bloom-Energy-Announces-Gigawatt-Fuel-Cell-Procurement-Agreement-with-AEP-to-Power-AI-Data-Centers/default.aspx
- notes: hard negative理由：当时“技术路径+1GW框架”极像重大突破，但后验难以找到≥2个独立、非同一机构链条的来源确认其对“并网节奏/成本结构/系统约束”产生可复制的长期改写。
---

# 数据中心-美国-2025Q1 标注集（hindsight）

## news_id: DC-US-2025-01-01
- domain: 数据中心
- initial_report_date: 2025-01-24
- title: PJM发布《2025 Long-Term Load Forecast Report》，长期负荷预测显著上修，强调大负荷/数据中心带来的增长不确定性
- label: Major
- hard_negative: false
- summary: PJM在长期负荷预测中明确把大负荷增长作为核心变量，成为后续电网规划与可靠性讨论的“硬锚”。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 负荷预测上修→输电/电源规划压力抬升、可靠性约束凸显→推动更严格的大负荷接入与规划流程（更早的约束披露、可能的“先接入后管理/可中断”框架）→行业“速度到电力”受制于电网侧节奏与规则。  
- observable_features_at_time:
  - 变化量: 官方发布为20年长期负荷/电量预测（具体增量以报告为准；初报已披露10年/20年电量预测条目）
  - 约束类型: 并网/输电规划（PJM规划）、电源充足性/可靠性
  - 时间表: 报告发布日2025-01-24；规划影响为多年期
  - 影响范围: PJM足迹（覆盖多州/多公用事业），对最大数据中心集群区（如VA/MD等）具有外溢
  - 证据等级: 系统运营商（RTO）官方报告
  - 可复用信号: “长期负荷预测上修/不确定性上升”本身；以及报告中对区域/分区增长差异的描述

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 系统运营商复盘 | 2026-01-08 | https://insidelines.pjm.com/2025-year-in-review-planning-prepares-for-burgeoning-electricity-demand/ | PJM复盘强调2025负荷预测为全年规划重点，围绕“前所未有的需求增长”推动规划/并网流程工作
  - 权威行业媒体深度 | 2025-12-18 | https://www.enr.com/articles/62227-grid-access-not-land-emerges-as-bottleneck-for-data-center-construction | 行业媒体将“电网接入”明确为数据中心建设瓶颈，并引用PJM长期负荷预测作为约束背景

- sources (初报与当时材料):
  - initial_report: https://www.pjm.com/-/media/DotCom/library/reports-notices/load-forecast/2025-load-report.pdf
  - time_slice_supporting: https://www.pjm.com/-/media/DotCom/library/reports-notices/load-forecast/2025-load-report.pdf

- notes: 初报为PJM官方规划文件，属于“规则/规划硬信息”；对单个项目的直接影响需通过后续并网与输电工程落地映射，初报不必强行量化到项目级。
---

---
## news_id: DC-US-2025-02-01
- domain: 数据中心
- initial_report_date: 2025-02-12
- title: Dominion Energy上调2025-2029资本开支计划至约$50.1B，指向数据中心负荷驱动的电网投资
- label: Major
- hard_negative: false
- summary: Dominion明确将数据中心负荷作为资本开支上调的重要原因，指向电网侧“成本上行+建设期约束”的结构性变化。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: mixed
  - supply_demand: tighten

- subsequent_impact_path: 大客户（数据中心）签约与负荷预期上修→公用事业提高CAPEX与可能的费率/合同约束（如更强的最低用量/更长承诺）→电网扩建带来成本外溢与审批/设备周期约束→数据中心“投运节奏”更依赖公用事业项目交付与监管批准。  
- observable_features_at_time:
  - 变化量: 五年资本开支计划上调（从先前计划上修至约$50.1B量级）
  - 约束类型: 输配电投资、变电站/线路扩建、（隐含）设备与施工能力
  - 时间表: 2025-2029资本计划窗口；对应项目交付多为多年期
  - 影响范围: Dominion服务区（含数据中心密集的Virginia等），对区域“可接入容量”与费率有外溢
  - 证据等级: 权威媒体（Reuters）+ 公司披露/投资者材料
  - 可复用信号: “CAPEX计划上修幅度/窗口期”“明确点名数据中心负荷”为驱动

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 行业媒体（数据中心垂直） | 2025-05-02 | https://www.datacenterdynamics.com/en/news/dominion-reports-high-data-center-demand-in-northern-virginia-proposes-new-electricty-rates-for-large-load-customers/ | 后续跟踪指出北弗吉尼亚数据中心需求仍高，并讨论面向大负荷的电价/费率安排
  - 监管/官方报告 | 2025-12-01 | https://rga.lis.virginia.gov/Published/2025/RD916/PDF | 州层面报告讨论负荷增长与监管审查（含IRP等），将数据中心相关负荷与基础设施需求纳入长期议题

- sources (初报与当时材料):
  - initial_report: https://www.reuters.com/business/energy/dominion-energy-raises-five-year-capex-plan-meet-data-centers-power-demand-2025-02-12/
  - time_slice_supporting: https://www.datacenterdynamics.com/en/news/dominion-reports-high-data-center-demand-in-northern-virginia-proposes-new-electricty-rates-for-large-load-customers/

- notes: “constraint”为mixed：短期因设备/审批/施工导致更紧，长期CAPEX扩建旨在缓解；初报未必给出项目级MW与并网时间，需按后续监管文件/投资者材料补齐。
---

---
## news_id: DC-US-2025-02-02
- domain: 数据中心
- initial_report_date: 2025-02-13
- title: Duke Energy将五年资本开支计划上调至约$83B，点名数据中心与工业负荷增长
- label: Major
- hard_negative: false
- summary: Duke将数据中心负荷作为资本开支上调的显性驱动，强化“电网投资周期决定算力投运”的行业格局。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: mixed
  - supply_demand: tighten

- subsequent_impact_path: 数据中心/工业负荷签约与预测上修→公用事业扩张输配电与新增电源（含气电等）→成本回收与监管审查强化→数据中心项目更依赖“可获得电力/可签可交付合同”，并在区域间迁移或采用自备电/可中断等方案。  
- observable_features_at_time:
  - 变化量: 五年CAPEX计划上调至约$83B（窗口为2025-2029）
  - 约束类型: 输配电扩建、电源侧补强（新增机组/延寿/升级）
  - 时间表: 五年投资窗口；对应工程多为中长期交付
  - 影响范围: Duke服务区（Carolinas/Florida等），覆盖多个数据中心热点州
  - 证据等级: 权威媒体（Reuters）+ 公司投资者披露
  - 可复用信号: “CAPEX上修幅度”“投资窗口”“明确点名数据中心负荷”以及“新增气电容量计划”等

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 公司披露（投资者/年会） | 2025-05-01 | https://investors.duke-energy.com/news/news-details/2025/Duke-Energy-prepares-for-record-load-growth-while-delivering-value-to-stakeholders-and-customers-CEO-tells-shareholders-at-annual-meeting/default.aspx | 公司再次明确$83B五年投资计划用于应对创纪录负荷增长
  - 独立行业媒体 | 2025-11-10 | https://www.utilitydive.com/news/duke-energy-five-year-capital-plan-could-exceed-100b/805076/ | 后续报道讨论更大规模资本计划与大负荷谈判，体现数据中心负荷持续拉动投资与规则设计

- sources (初报与当时材料):
  - initial_report: https://www.reuters.com/business/energy/duke-energy-raises-five-year-capex-plan-increased-data-center-industrial-demand-2025-02-13/
  - time_slice_supporting: https://s201.q4cdn.com/583395453/files/doc_financials/2025/q1/Q1-2025-Earnings-Presentation_vF-w-Reg-G.pdf

- notes: 初报属于“资本计划上调”类重大新闻：对成本结构与约束节奏的影响通常通过后续费率、并网流程、工程交付体现。
---

---
## news_id: DC-US-2025-02-03
- domain: 数据中心
- initial_report_date: 2025-02-13
- title: PPL将2025-2028基础设施投资目标上调至约$20B，强调负荷增长与电网韧性需求
- label: Major
- hard_negative: false
- summary: PPL将电网投资目标大幅上修，为数据中心等大负荷增长提供“电网侧供给扩张”的公开信号。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: mixed
  - supply_demand: tighten

- subsequent_impact_path: 区域负荷（含数据中心）增长预期→公用事业提高资本开支与电网加固→监管回收机制与融资需求上升→数据中心在该区域的“可接入性”提高但成本与规则更刚性（更强的承诺/费用分摊）。  
- observable_features_at_time:
  - 变化量: 2025-2028计划投资上调至约$20B；并给出年度投资目标量级
  - 约束类型: 输配电网升级、韧性改造（风暴/极端天气）
  - 时间表: 2025-2028投资窗口
  - 影响范围: PPL服务区（PA/KY/RI等），其中PA与数据中心负荷相关性更高
  - 证据等级: 权威媒体 + 公司新闻稿/投资者材料
  - 可复用信号: “资本计划上修幅度”“融资需求/股权融资预期”“并网/韧性投资占比”

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 公司披露（新闻稿） | 2025-02-13 | https://news.pplweb.com/2025-02-13-PPL-Corporation-reports-2024-earnings-results-updates-business-plan-and-extends-growth-targets-through-2028 | 公司正式披露将2025-2028投资提高至$20B并延展增长目标
  - 公司披露（投资者更新） | 2025-04-30 | https://filecache.investorroom.com/mr5ir_pplweb2/1221/PPL_2025_Q1_Investor_Update_vFINAL.pdf | 后续投资者材料继续重申$20B资本计划与监管回收机制安排

- sources (初报与当时材料):
  - initial_report: https://www.reuters.com/business/energy/utility-ppl-raises-capex-plan-by-nearly-40-power-demand-2025-02-13/
  - time_slice_supporting: https://news.pplweb.com/2025-02-13-PPL-Corporation-reports-2024-earnings-results-updates-business-plan-and-extends-growth-targets-through-2028

- notes: confirmations中两条均为公司披露（同源），因此“独立来源”主要依赖初报媒体与公司披露的组合；若严格要求“confirmations内部也需跨机构”，可用后续第三方报道补强（如财经媒体对PPL应对数据中心负荷的专题）。
---

---
## news_id: DC-US-2025-02-04
- domain: 数据中心
- initial_report_date: 2025-02-25
- title: PSEG上调2025-2029资本开支区间至约$22.5B-$26B，指向数据中心等负荷增长背景下的电网投资
- label: Major
- hard_negative: false
- summary: PSEG资本计划上调，将“客户需求增长/电网现代化”绑定，为大负荷接入与成本分摊问题提供公开锚点。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: mixed
  - supply_demand: tighten

- subsequent_impact_path: 大负荷增长（含数据中心）→配网/输电与能效项目投资扩大→在容量/输电费用与本地工程交付上形成成本与节奏约束→数据中心更可能面临更严格的接入条件或更明确的成本分摊。  
- observable_features_at_time:
  - 变化量: 2025-2029资本计划上调（较此前计划增加约数十亿美元量级），并给出区间
  - 约束类型: 电网现代化/配网改造、输电可靠性项目、（部分）能效计划
  - 时间表: 2025-2029
  - 影响范围: 以新泽西等PSEG服务区为主；对区域大负荷接入与费用有影响
  - 证据等级: 权威媒体 + 公司投资者材料
  - 可复用信号: “资本计划上调区间”“用于现代化/可靠性的投资结构”

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 公司披露（投资者更新） | 2025-05-15 | https://s24.q4cdn.com/601515617/files/doc_presentations/2025/05/PSEG-May-2025-Investor-Update-Final.pdf | 投资者材料进一步披露2025-2029资本投资计划与驱动因素
  - 行业研究/资讯 | 2025-11-14 | https://www.industrialinfo.com/iirenergy/industry-news/article/utilities-make-plans-to-accommodate-growing-data-center-loads--344980 | 业内资讯在“应对数据中心负荷”语境中提及PSEG资本计划与核电/电网侧调整

- sources (初报与当时材料):
  - initial_report: https://www.reuters.com/business/energy/utility-public-service-enterprise-forecasts-higher-2025-profit-raises-spending-2025-02-25/
  - time_slice_supporting: https://investor.pseg.com/investor-news-and-events/presentations/presentation-details/2025/May-2025-Investor-Update/default.aspx

- notes: PSEG案例更偏“区域性电网投资与费用结构变化”，对全国性装机节奏影响通过“规则扩散/他州复制”间接体现。
---

---
## news_id: DC-US-2025-02-05
- domain: 数据中心
- initial_report_date: 2025-02-20
- title: CenterPoint上调至2030年的十年资本计划（含电网加固），并在负荷增长叙事中明确提及数据中心
- label: Major
- hard_negative: false
- summary: CenterPoint将数据中心等大负荷纳入需求增长叙事并上调长期投资计划，强化“德州电网侧约束”对算力投运的决定性。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: mixed
  - supply_demand: tighten

- subsequent_impact_path: 负荷增长（含数据中心）→长期CAPEX上调并推动韧性/扩容工程→监管与地方博弈（费用回收/项目范围）→电网工程交付与费率成为数据中心选址与投运节奏的重要硬约束（并可能催生可中断/自备电/并网规则升级）。  
- observable_features_at_time:
  - 变化量: 十年资本计划上调（至2030窗口内增加额），并在财报/指引中披露
  - 约束类型: 输配电扩容、韧性加固（极端天气）、并网接入能力
  - 时间表: 至2030的长期计划；与德州大负荷增长周期耦合
  - 影响范围: Houston及相关服务区；对ERCOT大负荷接入讨论有参考意义
  - 证据等级: 权威媒体 + 公司财报新闻稿/行业媒体跟踪
  - 可复用信号: “十年资本计划上调”“峰值负荷增长预测”“新连接请求量”等硬指标（若初报未给则记Unknown）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 公司披露（财报新闻稿） | 2025-02-20 | https://investors.centerpointenergy.com/news-releases/news-release-details/centerpoint-energy-reports-q4-and-fy-2024-results-forecasts | 公司披露提高至2030的资本计划并说明增长背景
  - 权威地方媒体 | 2025-04-24 | https://www.houstonchronicle.com/business/energy/article/houston-electricity-demand-growth-20281415.php | 地方媒体以峰值负荷增长为线索讨论电网投资与数据中心等大负荷驱动
  - 独立行业媒体 | 2025-10-23 | https://www.utilitydive.com/news/houston-peak-load-to-grow-50-in-6-years-centerpoint/803600/ | 行业媒体持续跟踪Houston负荷增长与资本计划，体现数据中心负荷对投资与规则的持续影响

- sources (初报与当时材料):
  - initial_report: https://www.reuters.com/business/energy/centerpoint-joins-peers-raising-capital-spending-plan-meet-data-centers-power-2025-02-20/
  - time_slice_supporting: https://investors.centerpointenergy.com/news-releases/news-release-details/centerpoint-energy-reports-q4-and-fy-2024-results-forecasts

- notes: confirmations中含公司披露与两家独立媒体，满足“多源持续确认”；但对具体数据中心项目的直接影响仍需结合ERCOT/PUCT后续规则与工程进度做映射。

---
## news_id: DC-US-2025-03-01
- domain: 数据中心
- initial_report_date: 2025-03-02
- title: 爱达荷州Kootenai County因水与电力担忧，对新数据中心许可实施紧急/临时审批暂停（moratorium）
- label: NotMajor
- hard_negative: true
- summary: 县级紧急暂停引发关注，但影响范围局限于单县，未形成全国性规则变化或行业硬约束重定价。

- axes_and_direction:
  - pace: delay
  - cost: mixed
  - constraint: tighten
  - supply_demand: uncertain

- subsequent_impact_path: 地方资源担忧→临时暂停审批以制定分区/规则→（后续）暂停到期后转向更严格条件/继续讨论→对全国数据中心投运节奏与成本结构影响有限（主要是“局部选址摩擦”）。  
- observable_features_at_time:
  - 变化量: “暂停审批/发放许可”本身（持续期、覆盖范围以县决议为准）
  - 约束类型: 水资源、电力接入、地方土地/分区审批
  - 时间表: 2025-03县级投票/决议生效（具体到期日以决议文本为准）
  - 影响范围: Kootenai County（单县、非跨公用事业）
  - 证据等级: 地方媒体 + 县政府正式决议
  - 可复用信号: “地方政府紧急moratorium”“理由中点名水/电力/环境约束”

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 地方公共媒体 | 2025-10-02 | https://www.spokanepublicradio.org/regional-news/2025-10-02/avoiding-ai-kootenai-county-works-towards-total-ban-against-data-centers | 报道指出moratorium已到期，后续更多是地方层面持续限制讨论，未演化为全国性制度变迁

- sources (初报与当时材料):
  - initial_report: https://cdapress.com/news/2025/mar/02/kootenai-county-commissioners-approve-temporary-data-center-moratorium/
  - time_slice_supporting: https://www.kcgov.us/DocumentCenter/View/25322/25-Resolution---2025-23---Data-Center-Building-Permit-Moratorium

- notes: hard_negative原因=范围过小/不可外推；后验检索可见后续仍以地方治理为主，缺乏“跨区域、跨电网公司”的持续确认。
---

---
## news_id: DC-US-2025-02-06
- domain: 数据中心
- initial_report_date: 2025-02-10
- title: 弗吉尼亚州议会讨论数据中心外部性与电力危机，但当季未形成足够强的行业级规则改写（舆论热度高）
- label: NotMajor
- hard_negative: true
- summary: 作为最大数据中心州的“立法动向”看似重大，但后续仍持续推动新一轮改革提案，说明2025Q1并未形成结构性落地。

- axes_and_direction:
  - pace: uncertain
  - cost: mixed
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 舆论与议会讨论→零散法案/不足以改变成本分摊与接入审批框架→问题延续并在后续年度继续推动更强监管→初报当季更像“政治信号”而非“硬约束改变”。  
- observable_features_at_time:
  - 变化量: 法案/提案数量与主题（初报文本为主；具体通过议会信息可查）
  - 约束类型: 电力成本分摊、并网/输电扩建、噪音/土地等外部性
  - 时间表: 2025立法季（初报落在讨论阶段）
  - 影响范围: Virginia州内（尽管为全球最大集群区，但当季规则未显著改变）
  - 证据等级: 权威地方媒体评论/报道 + 利益相关方材料
  - 可复用信号: “立法讨论强度高但缺少可执行条款/量化约束”的组合特征

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 法律/政策总结（律所） | 2025-02-27 | https://www.williamsmullen.com/insights/news/legal-news/2025-virginia-general-assembly-summary-energy-data-center-bills | 总结当年能源/数据中心相关法案，但整体仍需后续签署/执行与进一步完善
  - 公共媒体（后续立法再起） | 2026-01-16 | https://www.vpm.org/generalassembly/2026-01-16/2026-data-center-bills-thomas-hb155-mcauliff-hb503-pjm-dominion-energy | 2026再推更强改革法案，侧面证明2025Q1阶段未形成足够强的结构性落地

- sources (初报与当时材料):
  - initial_report: https://virginiamercury.com/2025/02/10/facing-data-center-sprawl-and-an-energy-crisis-virginia-lawmakers-leap-into-action-just-kidding/
  - time_slice_supporting: https://www.pecva.org/uncategorized/the-2025-general-assembly-again-fails-to-take-meaningful-action-on-the-accelerating-impact-of-data-centers-on-virginians/

- notes: hard_negative原因=“像重大但缺乏硬落地”；后验来源主要体现“仍在继续立法补课”，而非“2025Q1已改变行业变量”。
---

---
## news_id: DC-US-2025-01-02
- domain: 数据中心
- initial_report_date: 2025-01-26
- title: 弗吉尼亚税务部门发布财政影响评估：拟在特定规划区限制数据中心销售税豁免（看似将改变成本结构）
- label: NotMajor
- hard_negative: true
- summary: 初看像“税收硬约束收紧”，但后续显示大规模豁免仍持续存在，未在预期时间窗口内形成结构性逆转。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 提案/财政评估→（后续）未形成足够强的落地与全州扩散→税收豁免仍为行业关键激励，成本结构未被当季提案改写。  
- observable_features_at_time:
  - 变化量: 提案拟定的生效窗口（如2025-07-01~2030-07-01）与适用范围（规划区）
  - 约束类型: 政策/税收激励（成本端）
  - 时间表: 评估文件发布时间2025-01-26；拟生效通常为后续财年节点
  - 影响范围: 指定规划区（并非全国/全州普遍）
  - 证据等级: 监管/政府部门文件
  - 可复用信号: “拟限制税收豁免+明确生效窗口+限定地域”的组合

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 官方/半官方深度报道 | 2025-12-03 | https://www.axios.com/local/richmond/2025/12/03/watchdog-report-virginia-data-centers-incentive-funds-2015-2024 | 看门狗报告显示数据中心税收激励规模巨大且豁免仍持续（并给出到期安排），未体现2025Q1提案造成结构性逆转
  - 研究/倡议机构后验统计 | 2026-01-06 | https://goodjobsfirst.org/virginia-tax-revenue-losses-to-data-centers-soar-to-1-6-billion-for-fy25/ | 后验统计继续显示豁免导致的税收损失规模，侧面证明短期未被有效收紧

- sources (初报与当时材料):
  - initial_report: https://lis.blob.core.windows.net/files/1029653.PDF
  - time_slice_supporting: https://lis.blob.core.windows.net/files/1029653.PDF

- notes: hard_negative原因=“提案强但落地弱/范围受限/未扩散”；后验用“仍大规模存在的豁免”作为反证。
---

---
## news_id: DC-US-2025-03-02
- domain: 数据中心
- initial_report_date: 2025-03-17
- title: 弗吉尼亚Manassas讨论对数据中心设备税率大幅上调（舆论上像“重塑成本结构”）
- label: NotMajor
- hard_negative: true
- summary: 初报为高幅度税率上调讨论，但后续演化为个案分类/预算问题，未形成跨区域可复制的行业级成本重定价。

- axes_and_direction:
  - pace: uncertain
  - cost: mixed
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 市级税率讨论→预算程序推进→后续更多聚焦“个案税基/分类与预期落差”→对全国数据中心投运与成本结构影响有限（局部财政摩擦）。  
- observable_features_at_time:
  - 变化量: 提及的税率上调幅度（讨论口径）
  - 约束类型: 地方税收政策（成本端）
  - 时间表: 预算听证/审批窗口（4-6月）
  - 影响范围: 单城市（Manassas），不可直接外推
  - 证据等级: 律所政策简报/地方媒体
  - 可复用信号: “地方政府以设备税/商业动产税调节数据中心外部性”的早期信号

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威地方媒体 | 2025-04-30 | https://wtop.com/local/2025/04/manassas-real-estate-taxes-may-spike-even-more-than-previously-estimated/ | 报道显示税率仍在预算流程中反复讨论，未见行业级制度化扩散
  - 市政府披露/说明 | 2025-05-06 | https://cms9files.revize.com/manassasva/Communications/2025%20Press%20Releases/NR%20003%20-%20Brickyard%20Data%20Center.pdf | 后续市政府说明更多聚焦个案税收归类与预期差异，而非全国性政策转折

- sources (初报与当时材料):
  - initial_report: https://www.gibsondunn.com/when-data-center-developers-have-options-state-regulatory-treatment-is-key-to-success/
  - time_slice_supporting: https://cp.soar.com/articles/6614644/Virginia/Council-debates-raising-datacentercomputer-tax-to-360-no-vote-taken

- notes: hard_negative原因=“局部财政事件、外推性弱”；后验检索缺乏“多州复制/行业变量长期变化”的持续确认。
---

---
## news_id: DC-US-2025-03-03
- domain: 数据中心
- initial_report_date: 2025-03-17
- title: 弗吉尼亚Henrico讨论显著提高数据中心设备税（被解读为对行业‘强监管/高成本’信号）
- label: NotMajor
- hard_negative: true
- summary: 初报像“税负跃升”，后续确有县级针对性税率/审批机制，但影响主要留在县域层面，未成为全国性成本重定价事件。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: tighten
  - supply_demand: uncertain

- subsequent_impact_path: 税率讨论与规划/审批改革→县级形成数据中心税率与开发指南→约束与成本上行局限在当地→未见全国范围“统一规则变迁”，更多是地方治理分化。  
- observable_features_at_time:
  - 变化量: 讨论口径中的大幅税率上调（“550%”等表述）
  - 约束类型: 地方税收+规划审批（成本与节奏）
  - 时间表: 2025年预算/规划审议窗口
  - 影响范围: Henrico County（单县）
  - 证据等级: 律所政策简报 + 县政府/地方媒体
  - 可复用信号: “县级针对数据中心设专门税率/审批”的可迁移特征

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 县政府税务页面 | 2025-06-10(后续可查最新) | https://henrico.gov/services/business-personal-property-tax/ | 县级已设置数据中心相关设备税率条目（显示为特定税率安排），体现地方治理落地但范围有限
  - 县政府规划文件 | 2025-06-10 | https://henrico.gov/pdfs/planning/datacenters/DataCenterGuidelinesComprehensivePlanAmendment.Adopted.6.10.25.pdf | 通过综合规划修订确立数据中心开发目标与指南，属地方层面制度化

- sources (初报与当时材料):
  - initial_report: https://www.gibsondunn.com/when-data-center-developers-have-options-state-regulatory-treatment-is-key-to-success/
  - time_slice_supporting: https://richmondbizsense.com/2025/02/26/henrico-budget-plan-includes-tax-rate-reductions-50m-for-water-upgrades/

- notes: hard_negative原因=“当时被解读为行业转折，但实际主要是地方治理分化”；对全国行业变量影响弱于公用事业CAPEX/ISO规则类事件。
---

---
## news_id: DC-US-2025-02-99
- domain: 数据中心
- initial_report_date: 2025-02-13
- title: Reuters汇总：多家美国公用事业因AI/数据中心负荷上修而增加数百亿美元投资计划
- label: Unlabeled
- hard_negative: false
- summary: 属于“同一主题的汇总稿”，与已入选Major的多条单公司CAPEX上修高度重叠。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: mixed
  - supply_demand: tighten

- subsequent_impact_path: 汇总性叙事对行业判断有用，但作为“初次报道事件”颗粒度不足，且与单公司CAPEX上修事件重复。  
- observable_features_at_time:
  - Unknown（汇总稿对单一事件的变化量/范围不够精确）
  - 约束类型: 电网投资、可靠性、费用回收
  - 影响范围: 多州多公用事业
  - 证据等级: 权威媒体汇总（但非单一可追踪事件）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - N/A

- sources (初报与当时材料):
  - initial_report: https://www.reuters.com/business/energy/aep-fourth-quarter-profit-rises-data-centers-boost-demand-power-2025-02-13/
  - time_slice_supporting: https://www.reuters.com/business/energy/aep-fourth-quarter-profit-rises-data-centers-boost-demand-power-2025-02-13/

- notes: 由于“事件边界不清晰+与Major重复”，保留为Unlabeled。
---

---
## news_id: DC-US-2025-03-99
- domain: 数据中心
- initial_report_date: 2025-03-13
- title: CERAWeek场景下的“数据中心或压垮最大电网”讨论（更像趋势报道而非单点制度变迁）
- label: Unlabeled
- hard_negative: false
- summary: 趋势性强、传播度高，但作为“初次报道”的可标注事件边界偏弱，需要与后续具体政策/规则事件绑定。

- axes_and_direction:
  - pace: uncertain
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 趋势讨论→后续若出现明确规则/监管动作则可回溯绑定；但单独作为一条新闻不够“可复用、可验证”的事件单元。  
- observable_features_at_time:
  - 变化量: 主要为预测/口径（易因版本变动产生漂移）
  - 约束类型: 可靠性/电源充足性/输电
  - 影响范围: 全国/最大电网叙事
  - 证据等级: 权威媒体趋势稿（但缺少具体条款/决策）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - N/A

- sources (初报与当时材料):
  - initial_report: https://www.reuters.com/business/energy/ceraweek-data-center-build-out-stokes-fears-overburdening-biggest-us-grid-2025-03-13/
  - time_slice_supporting: https://www.reuters.com/business/energy/ceraweek-data-center-build-out-stokes-fears-overburdening-biggest-us-grid-2025-03-13/

- notes: 若你希望把“趋势稿”也纳入可训练样本，建议另设一种label（如Trend/Context），否则容易污染“重大事件=硬约束改变”的定义。
---

# 数据中心-美国-2025Q2 标注集（hindsight）

---
## news_id: DC-US-2025-04-01
- domain: 数据中心
- initial_report_date: 2025-04-10
- title: PJM与Google/Tapestry合作，用AI工具加速发电侧并网研究与流程（应对数据中心驱动的电力需求）
- label: Major
- hard_negative: false
- summary: PJM引入Google/Tapestry的AI工具链，目标压缩并网研究周期，缓解“供给侧接入慢”对数据中心投运的硬约束。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 并网研究/审查数字化与自动化→提升处理队列吞吐、减少人为校验成本→发电侧（尤其是排队项目）更快出清/更可预测→数据中心“可获得电力”的供给侧瓶颈边际缓解（但效果分阶段落地）。  
- observable_features_at_time:
  - 变化量: 目标是“显著缩短处理时间”（具体缩短幅度 Unknown）
  - 约束类型: 发电侧并网/电网规划（间接约束数据中心供电）
  - 时间表: 2025年起分阶段推出（phase rollout），多年合作
  - 影响范围: PJM区域（13州+DC），覆盖北弗州等数据中心高密度区
  - 证据等级: 系统运营商官方披露 + 权威媒体报道
  - 可复用信号: “系统运营商+超大科技公司”联合；“队列治理工具化/平台化”；“阶段性上线+不量化承诺”
  - Unknown: 对单个项目的MW/交付窗口未在初报中给出

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体 | 2025-05-20 | https://www.reuters.com/business/energy/google-brings-ai-grid-teams-slashing-us-connection-times-2025-05-20/ | 将该合作置于全美并网拥堵与软件化提效背景下，强调其对缩短研究周期的潜在意义
  - 系统运营商复盘 | 2026-01-08 | https://insidelines.pjm.com/2025-year-in-review-planning-prepares-for-burgeoning-electricity-demand/ | PJM年终复盘再次点名该合作作为“流程提速工具”，与队列出清/自动化共同构成应对需求增长的抓手

- sources (初报与当时材料):
  - initial_report: https://www.reuters.com/technology/google-deploys-ai-speed-up-connections-pjm-largest-us-power-grid-2025-04-10/
  - time_slice_supporting: https://insidelines.pjm.com/pjm-google-tapestry-join-forces-to-apply-ai-to-enhance-regional-planning-generation-interconnection/ , https://blog.google/innovation-and-ai/infrastructure-and-cloud/global-network/electric-grid-ai/

- notes: 这是“供给侧并网提速”类事件；对数据中心投运的传导需要结合后续发电项目落地与PJM队列改革进度，初报不应硬量化效果。
---

---
## news_id: DC-US-2025-04-02
- domain: 数据中心
- initial_report_date: 2025-04-24
- title: 宾州PUC召开“大负荷（含数据中心）并网与电价/费率”公开听证（En Banc），启动更严格的接入与成本分摊讨论
- label: Major
- hard_negative: false
- summary: 监管机构把数据中心作为电网冲击源纳入正式议程，后续走向“模型费率/接入规则”，对成本与节奏形成制度化约束。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: 监管听证聚焦“大负荷冲击+投产不确定性”→推动统一的并网与费率框架（要求大负荷承担更明确的前置成本/承诺）→降低“投机性负荷申请”对系统规划的干扰→短期放慢接入、长期提高可预测性与可持续扩张。  
- observable_features_at_time:
  - 变化量: 听证本身（规则条款与收费模型当时尚未落地）
  - 约束类型: 并网/接入规则、成本分摊（费率）、电网规划可靠性
  - 时间表: 听证日期2025-04-24；后续将进入规则/命令形成期（具体落地时间 Unknown）
  - 影响范围: 宾州（PJM区域内），但属于“可复制的监管模板”类型
  - 证据等级: 监管机构公告/公报
  - 可复用信号: “En Banc听证+专门docket+明确点名data center growth”；“成本分摊/承诺机制”关键词
  - Unknown: 初报不含具体MW阈值/保证金/最低合约条款细节

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管机构 | 2025-11-06 | https://www.puc.pa.gov/press-release/2025/puc-advances-plan-to-balance-data-center-growth-and-consumer-protection-11062025 | 明确把数据中心增长与消费者保护绑定，推进模型费率/规则
  - 权威行业媒体/政务科技媒体 | 2025-11-12 | https://www.govtech.com/infrastructure/pa-proposes-tariff-model-to-offset-data-center-power-consumption | 报道模型费率意图（保护居民不为专用基础设施买单），将4月听证与后续方案串联

- sources (初报与当时材料):
  - initial_report: https://www.pacodeandbulletin.gov/Display/pabull?file=%2Fsecure%2Fpabulletin%2Fdata%2Fvol55%2F55-47%2F1589.html
  - time_slice_supporting: https://www.puc.pa.gov/filing-resources/issues-laws-regulations/en-banc-hearing-on-interconnection-and-tariffs-for-large-load-customers/

- notes: 该类事件属于“规则/费率制度化”，对行业变量影响路径清晰；初报阶段不应引用后续命令中的具体收费条款。
---

---
## news_id: DC-US-2025-04-03
- domain: 数据中心
- initial_report_date: 2025-04-30
- title: 西弗吉尼亚通过并签署《Power Generation and Consumption Act》（微电网/高影响数据中心框架），以政策方式吸引“自发电+数据中心”落地
- label: Major
- hard_negative: false
- summary: 州级立法为“数据中心+自备电/微电网”提供制度通道并调整地方权责，可能改变项目审批与供电约束结构。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 州立法确立微电网/高影响数据中心制度→降低对传统公用事业接入的依赖、以“自供电”绕开部分并网瓶颈→同时引发地方治理/税收与透明度争议→形成“加速落地但政治/社会阻力上升”的双向效应。  
- observable_features_at_time:
  - 变化量: 新法案生效（微电网认证机制/高影响数据中心定义/税收分配机制等；细则以法案文本为准）
  - 约束类型: 许可/审批、供电模式（微电网/自备电）、地方治理
  - 时间表: 2025-04-30签署（后续实施细则与项目落地节奏 Unknown）
  - 影响范围: 西弗吉尼亚州；对周边数据中心选址产生替代方案效应
  - 证据等级: 州政府公告/立法文本 + 权威媒体深度
  - 可复用信号: “州级立法+微电网+高影响数据中心”组合；“地方权力/税收重新分配”信号

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体深度 | 2025-08-04 | https://apnews.com/article/b33c051439bd3694ee3f2b04981f4555 | 描述该法对地方监管权与税收的重塑，以及围绕数据中心/发电项目的争议与外溢影响
  - 地方媒体/项目跟踪 | 2026-01-31 | https://www.wvnews.com/news/wvnews/west-virginia-microgrid-legislation-begins-delivering-large-scale-ai-developments/article_74207818-6ea0-4f56-8686-d38d96a8f6a6.html | 把HB2014的制度框架与后续“AI/算力园区”项目推进联系起来，体现政策对项目管道的支撑作用

- sources (初报与当时材料):
  - initial_report: https://wvpublic.org/power-generation-law-will-bring-economic-development-say-proponents/
  - time_slice_supporting: https://governor.wv.gov/article/governor-patrick-morrisey-signs-power-generation-and-consumption-and-one-stop-shop , https://www.wvlegislature.gov/Bill_Status/bills_text.cfm?billdoc=sb818+intr.htm&i=818&sesstype=RS&yr=2025

- notes: 该事件的“重大性”在于：把“数据中心负荷”从传统并网问题转为“自供电+制度通道”的可选路径，可能被其他州借鉴或反向监管。
---

---
## news_id: DC-US-2025-06-01
- domain: 数据中心
- initial_report_date: 2025-06-25
- title: 德州签署SB6：把数据中心等≥75MW大负荷纳入更强的并网标准、成本分摊与应急可中断/自备电要求
- label: Major
- hard_negative: false
- summary: SB6把“大负荷先接入再说”的路径改为“先证明可控、可付费、可中断”，直接改变德州数据中心投运节奏与成本结构。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: 立法设定大负荷门槛与义务（成本/信息/应急响应）→PUCT/ERCOT制定实施规则→大负荷接入需要更高前置承诺与可中断能力→短期放慢/筛选项目、长期降低“虚假/投机负荷”对电网与费率的外部性。  
- observable_features_at_time:
  - 变化量: 大负荷定义（≥75MW等，按法案/解读文本）、费用/应急条款（具体以法案与后续规则为准）
  - 约束类型: 并网/接入、成本分摊、应急可中断/自备电披露
  - 时间表: 2025-06-20签署生效（部分条款以9/1等节点实施，需以法案/规则文本核对）
  - 影响范围: ERCOT（德州为核心数据中心增量区之一）
  - 证据等级: 州立法 + 行业媒体/法律解读
  - 可复用信号: “门槛MW+应急可中断+成本分摊+信息披露”四件套
  - Unknown: 具体保证金/费用表、执行细则需等待PUCT规则

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 行业媒体 | 2025-06-25 | https://www.utilitydive.com/news/texas-law-gives-grid-operator-power-to-disconnect-data-centers-during-crisi/751587/ | 概括SB6对数据中心/大负荷应急处置与接入前置条件的影响
  - 法律/政策解读 | 2025-11-20 | https://www.sidley.com/en/insights/publications/2025/11/how-new-law-transforms-large-load-power-projects-in-texas | 归纳SB6对大负荷并网、应急可中断与共址发电安排的制度性改变（体现长期影响）

- sources (初报与当时材料):
  - initial_report: https://www.utilitydive.com/news/texas-law-gives-grid-operator-power-to-disconnect-data-centers-during-crisi/751587/
  - time_slice_supporting: https://www.bracewell.com/resources/texas-senate-bill-6-ushers-in-major-overhaul-of-large-load-interconnection-and-grid-access-rules/ , https://interchange.puc.texas.gov/Documents/55999_168_1550025.PDF

- notes: 这是典型“规则把不确定性内生化到项目侧”的重大事件；对研究建模时可作为“德州投运节奏/成本上移”的结构性拐点候选。
---

---
## news_id: DC-US-2025-05-01
- domain: 数据中心
- initial_report_date: 2025-05-21
- title: Crusoe为OpenAI在德州建设的超大AI数据中心获得$11.6B融资扩容（从2栋扩至8栋），强化“超大规模AIDC=电力硬约束项目”
- label: Major
- hard_negative: false
- summary: 单体项目在融资与规模上跃迁，显著抬升区域电力与供应链约束重要性，并推动“算力供给”预期上修。

- axes_and_direction:
  - pace: accelerate
  - cost: up
  - constraint: tighten
  - supply_demand: loosen

- subsequent_impact_path: 大额融资确认+扩容计划→建设规模与用电需求显性化→地方电力接入/水冷/环保与供应链成为硬约束→推动市场对“电力优先、超长交付周期、重资本”AIDC范式的共识形成。  
- observable_features_at_time:
  - 变化量: 融资额$11.6B（总额提高至约$15B）、从2栋扩到8栋（规模路径明确）
  - 约束类型: 供电/并网、电价合同、冷却与用水、施工与设备（GPU/变压器等）
  - 时间表: “今年上线/逐步扩建”（具体COD/energization窗口 Unknown）
  - 影响范围: 德州（Abilene等）单点超大规模，对区域电网与供应链外溢
  - 证据等级: 权威媒体（Reuters/FT/AP等）+ 业主/合作方披露
  - 可复用信号: “融资落地+扩容倍数+单体GW级电力叙事”组合；“长期租约/绑定客户”信号
  - Unknown: 初报未给每栋MW与最终总MW（需以后续材料为准）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体深度 | 2025-??-?? | https://www.ft.com/content/a9cd130f-f6bf-4750-98cc-19d87394e657 | 描述为OpenAI供电/供算力的超大数据中心与长期协议、芯片采购规模，强化其行业影响
  - 主流通讯社 | 2025-09-?? | https://apnews.com/article/0b3f4fa6e8d8141b4c143e3e7f41aba1 | 以“Stargate”旗舰设施展示项目规模、用电与建设形态，体现其对产业与地方资源的持续影响

- sources (初报与当时材料):
  - initial_report: https://www.reuters.com/technology/openais-biggest-data-center-secures-116-billion-funding-wsj-reports-2025-05-21/
  - time_slice_supporting: https://www.businessinsider.com/crusoes-project-stargate-data-center-tax-break-in-abilene-texas-2025-4

- notes: 该条是“单体项目级重大”而非监管规则；适合训练模型识别“融资落地+扩容倍数+电力/冷却约束外溢”的重大信号。
---

---
## news_id: DC-US-2025-06-02
- domain: 数据中心
- initial_report_date: 2025-06-17
- title: 亚利桑那Pima County以3-2通过Project Blue（$3.6B数据中心园区）协议；随后引发Tucson对大用水户的制度化约束
- label: Major
- hard_negative: false
- summary: 地方政府批准超大数据中心引发强烈反弹，最终推动城市层面“用水硬约束+公开审查”制度，成为可复制的约束范式。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: 县级批准（投资额/园区落点明确）→公众对水资源与透明度施压→城市出台大用水户审查/节水计划制度→数据中心获得水与许可的路径变得更刚性、更可审计，项目节奏更易被地方政策卡住。  
- observable_features_at_time:
  - 变化量: 投资额“> $3.6B”；批准PSA/开发协议（具体条款以公告为准）
  - 约束类型: 水与冷却、土地/分区、地方政治与透明度、供电协议
  - 时间表: 2025-06-17批准；后续需要水/电/许可继续推进（具体窗口 Unknown）
  - 影响范围: Tucson/Pima County；对干旱区数据中心选址与用水政策具示范效应
  - 证据等级: 县政府公告（官方）+ 后续权威媒体深度
  - 可复用信号: “窄票通过（3-2）+保密争议+用水指标被放大”组合；“随后城市立法收紧用水准入”

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威通讯社 | 2025-08-?? | https://apnews.com/article/42c1e554b02b4293685a08a4574db9f0 | 报道Tucson通过新条例，要求大用水户提交节水计划并接受公开审查，明确由数据中心争议触发
  - 公共电台/地方权威媒体 | 2025-12-10 | https://news.azpm.org/p/azpmnews/2025/12/10/227598-arizona-regulators-approve-tep-deal-to-power-controversial-pima-county-data-center | 把供电协议与项目推进绑定，体现争议项目对电力与监管议题的持续外溢

- sources (初报与当时材料):
  - initial_report: https://content.govdelivery.com/accounts/AZPIMA/bulletins/3e58e79
  - time_slice_supporting: https://www.pima.gov/2720/Newsroom?contentId=f320deaa-0d2c-4697-8413-4c7261ca4c50&mode=dialog , https://www.pima.gov/3552/Project-Blue-FAQ

- notes: 该事件的“重大性”来自制度化约束（用水准入）而非单个项目本身；对其他干旱区/水约束区具有可迁移性。
---

---
## news_id: DC-US-2025-04-90
- domain: 数据中心
- initial_report_date: 2025-04-09
- title: Microsoft称将“放慢或暂停”部分数据中心项目（含俄亥俄Licking County约$1B计划）
- label: NotMajor
- hard_negative: true
- summary: 当时被解读为“AI数据中心需求见顶”，但更多是公司级节奏重排；未形成可验证的行业级供需拐点或规则变化。

- axes_and_direction:
  - pace: mixed
  - cost: mixed
  - constraint: uncertain
  - supply_demand: mixed

- subsequent_impact_path: 公司调整项目优先级/用地用途→局部市场短期承压→但行业仍存在多条“超大项目融资与规则收紧”主线并行→该新闻更像“公司策略噪音”而非结构性拐点。  
- observable_features_at_time:
  - 变化量: “暂停/放慢”+具体项目金额（$1B）与地点（Licking County）
  - 约束类型: 企业资本开支与项目管线管理（非监管硬约束）
  - 时间表: 未给出恢复/替代计划的明确窗口（Unknown）
  - 影响范围: 公司单一主体、局部地区
  - 证据等级: 权威通讯社
  - 可复用信号: “暂停/放慢”表述+缺少行业级量化；“保留土地用途改变（farmland）”等强信号

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 行业媒体 | 2025-04-08 | https://www.datacenterdynamics.com/en/news/microsoft-backs-away-from-1bn-data-center-plans-in-licking-county-ohio/ | 将事件定位为项目层面的撤回/暂停，并非监管或电网规则转折
  - 对照性后验证据（行业仍在加速） | 2025-05-21 | https://www.reuters.com/technology/openais-biggest-data-center-secures-116-billion-funding-wsj-reports-2025-05-21/ | 同期仍出现更大规模AI数据中心融资扩容，削弱“行业见顶”的解释力

- sources (初报与当时材料):
  - initial_report: https://apnews.com/article/4d987fe8446fc9e6cda31d919f938911
  - time_slice_supporting: https://www.enr.com/articles/60572-microsoft-hits-pause-button-on-1b-in-data-centers-in-ohio

- notes: hard_negative原因=“公司级动作，缺少跨主体、跨区域的长期影响确认”；且未引发制度/规则/成本分摊框架的可验证改变。
---

---
## news_id: DC-US-2025-04-91
- domain: 数据中心
- initial_report_date: 2025-04-30
- title: 弗吉尼亚Manassas上调数据中心设备税率（作为财政“看似重塑成本结构”的高热度事件）
- label: NotMajor
- hard_negative: true
- summary: 地方税率上调对个别项目成本有影响，但缺乏跨州扩散与行业级成本重定价证据，更像地方财政再平衡。

- axes_and_direction:
  - pace: uncertain
  - cost: up
  - constraint: mixed
  - supply_demand: uncertain

- subsequent_impact_path: 市级提高设备税→提高当地项目持有成本→但影响主要局限于辖区内，未形成可验证的全国/区域费率制度迁移；行业关键变量仍由电网侧规则与供电合同主导。  
- observable_features_at_time:
  - 变化量: 设备税率上调至$3.60/$100评估值（初报给出）
  - 约束类型: 地方税收（成本端）
  - 时间表: 伴随当地预算年度生效（具体生效日以预算案为准）
  - 影响范围: Manassas市域
  - 证据等级: 地方权威媒体
  - 可复用信号: “地方政府以设备税回应数据中心外部性”的信号；但缺乏跨区可外推性

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 后续缺乏结构性扩散的证据线索 | 2025-12-17 | https://www.latitudemedia.com/news/the-unsettled-landscape-of-large-load-tariffs/ | 2025年全国更强的制度化变化主要体现在“电力大负荷费率/并网规则”，而非单一城市设备税
  - （对照）地方层面仍以预算叙事为主 | 2025-04-30 | https://wtop.com/local/2025/04/manassas-real-estate-taxes-may-spike-even-more-than-previously-estimated/ | 后续讨论仍围绕地方预算与税基配置，未呈现行业级制度转折

- sources (初报与当时材料):
  - initial_report: https://wtop.com/local/2025/04/manassas-real-estate-taxes-may-spike-even-more-than-previously-estimated/
  - time_slice_supporting: https://www.gibsondunn.com/when-data-center-developers-have-options-state-regulatory-treatment-is-key-to-success/

- notes: hard_negative原因=“地方性强、外推性弱”；后验检索中行业真正的制度化变化更集中在大负荷费率/并网框架。
---

---
## news_id: DC-US-2025-04-92
- domain: 数据中心
- initial_report_date: 2025-04-10
- title: 弗吉尼亚Southside（如Pittsylvania）讨论以更高税率/规划方式吸引或约束数据中心（当时被包装为“新增长极”）
- label: NotMajor
- hard_negative: true
- summary: 属于地方“招商+税制设计”讨论，缺少后续多源证据证明其改变全州/全国投运节奏或成本结构。

- axes_and_direction:
  - pace: uncertain
  - cost: mixed
  - constraint: mixed
  - supply_demand: uncertain

- subsequent_impact_path: 地方讨论数据中心税制与收益→短期舆论热度高→但缺乏跨区域复制与电力接入硬约束量化信息，难以构成行业级重大事件样本。  
- observable_features_at_time:
  - 变化量: 讨论税率口径（如更高的个人财产税率）与收益预期（具体条款 Unknown）
  - 约束类型: 地方税收与规划（土地/审批）
  - 时间表: 以地方财政年度/招商窗口为主（Unknown）
  - 影响范围: 单县/单区域
  - 证据等级: 地方媒体深度
  - 可复用信号: “地方把数据中心作为税基工具”与“收益叙事先于电力接入硬信息”

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 缺乏持续确认（行业变量仍由电网规则主导） | 2025-11-06 | https://www.puc.pa.gov/press-release/2025/puc-advances-plan-to-balance-data-center-growth-and-consumer-protection-11062025 | 后续更具结构性的变化集中在监管层面的并网与费率框架，而非单一县域税制讨论

- sources (初报与当时材料):
  - initial_report: https://cardinalnews.org/2025/04/10/data-centers-can-bring-high-paying-jobs-and-millions-in-tax-revenue-is-that-what-southside-will-get/
  - time_slice_supporting: https://cardinalnews.org/2025/04/10/data-centers-can-bring-high-paying-jobs-and-millions-in-tax-revenue-is-that-what-southside-will-get/

- notes: hard_negative原因=“缺少可验证的硬约束变化量（MW/并网窗口/合同）与跨区扩散证据”；更多是地方叙事样本。
---

---
## news_id: DC-US-2025-06-90
- domain: 数据中心
- initial_report_date: 2025-06-11
- title: 弗吉尼亚Stafford县规划文件/议程出现“数据中心用途重划/否决”类事项（当时易被误读为州级转向）
- label: NotMajor
- hard_negative: true
- summary: 属于县域层面的规划程序事件，无法替代州/电网/公用事业层面的硬规则变化，对行业影响有限。

- axes_and_direction:
  - pace: delay
  - cost: mixed
  - constraint: tighten
  - supply_demand: uncertain

- subsequent_impact_path: 县域否决/限制→局部项目延后或迁移→但缺乏跨县复制的制度化证据，且不改变电力接入与费率框架，难构成行业级重大事件。  
- observable_features_at_time:
  - 变化量: 议程/报告中出现“REZONING DENIAL/数据中心用途”条目（具体项目MW Unknown）
  - 约束类型: 土地/分区审批
  - 时间表: 县域规划会议节点（2025-06-11）
  - 影响范围: Stafford县域
  - 证据等级: 政府会议文件
  - 可复用信号: “地方规划否决”在数据中心扩张期的常见噪音，应与“跨区规则”区分

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 仅体现地方程序性约束 | 2025-06-11 | https://staffordcova.portal.civicclerk.com/event/2457/files/report/8281 | 作为政府会议文件，显示该类事项属于地方规划流程，而非行业制度转折

- sources (初报与当时材料):
  - initial_report: https://staffordcova.portal.civicclerk.com/event/2457/files/report/8281
  - time_slice_supporting: https://staffordcova.portal.civicclerk.com/event/2457/files/report/8281

- notes: hard_negative原因=“县域单点、外推性弱”；适合作为‘看似重大但其实只是地方噪音’的负例。
---

---
## news_id: DC-US-2025-06-91
- domain: 数据中心
- initial_report_date: 2025-06-30
- title: Prince William County发布数据中心税收/收入报告（看似“数据中心将重塑财政与政策”，但本身非硬约束改变）
- label: NotMajor
- hard_negative: true
- summary: 报告披露财政依赖与税基结构，但不直接改变并网、审批或费率规则；更多是背景材料而非事件。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 财政报告强化“地方依赖”叙事→可能影响后续政治讨论→但缺乏直接可执行条款与硬约束变化量，难以作为重大事件（更像研究背景）。  
- observable_features_at_time:
  - 变化量: 报告披露税收与税率调整信息（具体数值以报告为准）
  - 约束类型: 政策/财政背景（非直接约束）
  - 时间表: 报告发布日期2025-06-30
  - 影响范围: Prince William County
  - 证据等级: 政府报告
  - 可复用信号: “报告型信息”容易被当作事件，但应与“规则生效/审批决定/合同签署”区分

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 对照：真正的结构性变化集中在费率/并网规则 | 2025-11-06 | https://www.puc.pa.gov/press-release/2025/puc-advances-plan-to-balance-data-center-growth-and-consumer-protection-11062025 | 行业级约束更常由监管费率与并网框架驱动，而非单一县财政报告

- sources (初报与当时材料):
  - initial_report: https://www.pwcva.gov/assets/2025-06/Prince%20William%20County%202024%20Data%20Center%20Revenue%20Report.pdf
  - time_slice_supporting: https://www.pwcva.gov/assets/2025-06/Prince%20William%20County%202024%20Data%20Center%20Revenue%20Report.pdf

- notes: hard_negative原因=“不是事件型硬变化”；适合作为模型训练的“背景材料误判”负例。
---

---
## news_id: DC-US-2025-06-99
- domain: 数据中心
- initial_report_date: 2025-06-01
- title: ERCOT更新《Planning Guide》并加入/调整Large Load Interconnection Study（LLIS）相关条款（规则细节型，重大性取决于后续执行）
- label: Unlabeled
- hard_negative: false
- summary: 属于“流程细则更新”，可能影响接入节奏，但缺乏足够独立来源将其确认为行业级长期变量改变。

- axes_and_direction:
  - pace: mixed
  - cost: uncertain
  - constraint: mixed
  - supply_demand: uncertain

- subsequent_impact_path: 规则细则更新→潜在提高信息/流程要求→是否形成结构性影响取决于后续PUCT/ERCOT执行与与SB6等立法的耦合，当前证据不足以稳定定性。  
- observable_features_at_time:
  - 变化量: 文本新增/插入LLIS提交与适用条款（具体条款以文件为准）
  - 约束类型: 并网/接入流程（ERCOT）
  - 时间表: 文件版本标注“June 1, 2025”
  - 影响范围: ERCOT
  - 证据等级: 系统运营商文件
  - 可复用信号: “细则型更新”本身难标注为重大，需与后续执行效果绑定

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - N/A

- sources (初报与当时材料):
  - initial_report: https://www.ercot.com/files/docs/2025/05/20/June-1-2025-Planning-Guide.pdf
  - time_slice_supporting: https://www.ercot.com/files/docs/2025/05/20/June-1-2025-Planning-Guide.pdf

- notes: 若你希望把“规则细则更新”也纳入训练样本，建议单独设label（如ProcessChange），否则容易与“立法/监管命令”混淆。
---

# 数据中心-美国-2025Q3 标注集（hindsight）

---
## news_id: DC-US-2025-07-01
- domain: 数据中心
- initial_report_date: 2025-07-16
- title: Zuckerberg称将建设“接近曼哈顿大小”的AI数据中心，并公布Prometheus/Hyperion等超大算力集群路线图
- label: Major
- hard_negative: false
- summary: Meta把AI算力扩张从“资本开支”升级为“超大规模园区+多年期电力保障”，强化美国AIDC供需与电力约束的长期趋势。

- axes_and_direction:
  - pace: accelerate
  - cost: up
  - constraint: tighten
  - supply_demand: loosen

- subsequent_impact_path: 超大规模集群公开化→单体/集群级用电与建设周期成为硬变量→推动企业锁定长期电力（核电/自备电/大负荷费率）与供应链（设备/光纤/施工）→行业进入“先电力后算力”的约束驱动阶段。  
- observable_features_at_time:
  - 变化量: 宣称“接近曼哈顿大小”的数据中心规模（具体MW Unknown）
  - 时间表: Prometheus计划在2026上线（初报口径）
  - 约束类型: 供电/并网、冷却与用水、土地与许可、强电施工与设备交期
  - 影响范围: 多州多园区（Prometheus/Hyperion等），对电力与供应链外溢
  - 证据等级: 权威媒体报道 + 公司高管公开表态
  - 可复用信号: “单体园区极端尺度”+“明确命名的超算集群”+“跨年投运窗口”
  - Unknown: 具体选址、PPA/并网方案、最终MW拆分

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 公司披露 | 2026-01-09 | https://about.fb.com/news/2026/01/meta-nuclear-energy-projects-power-american-ai-leadership/ | 以核电项目为Prometheus等AI基础设施供能，证明“长期电力绑定”路线延续
  - 权威通讯社 | 2026-01-09 | https://apnews.com/article/0eb051a9a11d96f7ce200e186ad13476 | 进一步确认Prometheus为≥1GW级项目，并以核电交易支撑其供能路径
  - 行业媒体 | 2026-01-09 | https://www.utilitydive.com/news/meta-nuclear-deal-oklo-vistra-terrapower-ai-data-centers/809215/ | 将Prometheus定位为2026上线、至少1GW负荷，并解释其对电力市场/可靠性的含义

- sources (初报与当时材料):
  - initial_report: https://www.theguardian.com/technology/2025/jul/16/zuckerberg-meta-data-center-ai-manhattan
  - time_slice_supporting: https://www.investopedia.com/meta-zuckerberg-says-new-ai-data-center-supercluster-is-set-to-come-online-next-year-11771921

- notes: 初报的“曼哈顿大小”是强信号但缺少MW/并网细节；可用于训练“企业级超算集群公开化=供需与电力约束加剧”的重大样本。
---

---
## news_id: DC-US-2025-07-02
- domain: 数据中心
- initial_report_date: 2025-07-21
- title: 德州PUCT启动SB6实施工作（SB6 Implementation Workshop/项目集），把≥75MW大负荷并网标准、净计量共址与负荷预测纳入规则化路线
- label: Major
- hard_negative: false
- summary: SB6从立法进入监管实施阶段，核心是把“大负荷接入不确定性”转化为可执行的并网标准、费用/担保与可中断等义务。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: 监管实施路线图→细化大负荷门槛、站点控制、研究费/担保、应急可中断与共址规则→筛掉投机性负荷申请、提高前置成本与合规门槛→短期放慢接入、长期提高电网规划可预测性。  
- observable_features_at_time:
  - 变化量: SB6实施工作以workshop/项目号推进（具体条款仍在规则制定中）
  - 约束类型: 并网/接入标准、成本分摊与担保、共址净计量、负荷预测与规划输入
  - 时间表: 2025年启动实施；规则采纳窗口 Unknown（初报阶段）
  - 影响范围: ERCOT（美国数据中心增量核心区域之一）
  - 证据等级: 监管机构公开流程/文件
  - 可复用信号: “立法→监管实施项目化”+“≥75MW门槛”+“站点控制/担保/应急义务”
  - Unknown: 最终保证金/费用表、具体可中断触发机制

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 行业媒体 | 2026-01-06 | https://www.utilitydive.com/news/ercots-large-load-queue-jumped-almost-300-last-year-official/808820/ | 明确引用“PUCT在2025年8月发布SB6实施路线图并在多个docket推进”，表明其已成为规则化主线
  - 律所/政策解读 | 2025-12-23 | https://perkinscoie.com/insights/update/sb-6-implementation-shaping-data-center-future-texas | 汇总PUCT实施项目（含大负荷并网标准等）并解释对数据中心接入节奏/成本的结构性影响
  - 监管文件（PUCT） | 2025-08-05 | https://interchange.puc.texas.gov/Search/Filings?ControlNumber=58317 | 公开展示SB6实施workshop与后续材料归档（可追踪实施进展）

- sources (初报与当时材料):
  - initial_report: https://interchange.puc.texas.gov/Search/Filings?ControlNumber=58317
  - time_slice_supporting: https://www.mcguirewoods.com/client-resources/alerts/2025/7/texas-senate-bill-6-significantly-expands-regulatory-oversight-over-large-loads-in-ercot/ , https://www.bakerbotts.com/thought-leadership/publications/2025/july/texas-senate-bill-6-understanding-the-impacts-to-large-loads-and-co-located-generation

- notes: 初报阶段以“流程与项目号”呈现，适合训练识别“监管实施启动=硬约束即将制度化”的重大信号。
---

---
## news_id: DC-US-2025-08-01
- domain: 数据中心
- initial_report_date: 2025-08-12
- title: PJM启动Critical Issue Fast Path（CIFP）为数据中心等大负荷制定快速接入与可靠性规则
- label: Major
- hard_negative: false
- summary: PJM把大负荷接入从个案处理升级为“董事会牵头的快速规则制定”，意味着PJM区数据中心投运节奏将被统一框架约束。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: CIFP启动→形成负荷定义、接入条件、成本/可靠性责任与潜在“自带电力/可中断”选项→抑制无供给匹配的接入→短期审批更严，长期形成可预测通道并影响企业选址与合同结构。  
- observable_features_at_time:
  - 变化量: “快速利益相关方流程”启动（具体条款 Unknown）
  - 约束类型: 并网/接入规则、资源充足性、需求预测与输电规划、成本分摊
  - 时间表: 2025-08启动；后续将形成提交/改tariff路径（初报阶段未给最终生效日）
  - 影响范围: PJM全区（覆盖美国最密集数据中心走廊之一）
  - 证据等级: 系统运营商/权威行业媒体
  - 可复用信号: “Board letter+Fast Path”+“Large Load Additions专门议题”+“明确点名data centers”
  - Unknown: 负荷门槛MW、保证金/退出费、是否强制BYOG等

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 系统运营商复盘 | 2026-01-08 | https://insidelines.pjm.com/2025-year-in-review-planning-prepares-for-burgeoning-electricity-demand/ | 回顾CIFP自2025年8月启动并成为年度关键工作流
  - 系统运营商董事会决定 | 2026-01-16 | https://insidelines.pjm.com/pjm-board-outlines-plans-to-integrate-large-loads-reliably/ | 发布“整合大负荷、保持可靠性”的综合方案，确认CIFP产出进入落地阶段
  - 权威媒体 | 2026-01-27 | https://www.reuters.com/business/energy/us-grid-rules-faster-data-centers-favor-on-site-gas-plants--reeii-2026-01-27/ | 将PJM新规则与数据中心“更快接入/更偏向可快速上线供电”联系，验证其行业级影响

- sources (初报与当时材料):
  - initial_report: https://www.utilitydive.com/news/pjm-cifp-fast-track-data-center-large-load/757399/
  - time_slice_supporting: https://www.publicpower.org/periodical/article/pjm-kicks-initiative-balance-reliability-with-large-load-growth

- notes: 该事件本质是“规则框架化”；对建模可作为PJM区投运节奏与成本条款上移的拐点候选。
---

---
## news_id: DC-US-2025-08-02
- domain: 数据中心
- initial_report_date: 2025-08-09
- title: 弗吉尼亚法院裁定Prince William“Digital Gateway”数据中心走廊重划无效，项目被实质性暂停
- label: Major
- hard_negative: false
- summary: NoVA外溢区域的超大园区因程序瑕疵被法院推翻，显示“土地/程序合规”已成为与电力同级的硬约束。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: 法院判决使重划“归零”→项目进入长期诉讼/上诉不确定性→开发商与资金方的可开工性下降、地方审批风险溢价上升→周边选址更偏向已工业化/程序风险更低区域。  
- observable_features_at_time:
  - 变化量: 法院裁定“重划无效/暂时推翻”
  - 约束类型: 土地/分区与程序合规（notice/听证等）、社区反对与政治风险
  - 时间表: 2025-08判决；后续上诉与听证窗口 Unknown（初报阶段）
  - 影响范围: Prince William County（但位于NoVA数据中心扩张关键边界）
  - 证据等级: 地方法院裁定 + 主流媒体/地方权威媒体
  - 可复用信号: “法院推翻rezoning”+“超大走廊/多数据中心规划”+“邻近国家战场公园等敏感区”
  - Unknown: 最终可恢复的时间与范围

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威地方媒体 | 2025-11-20 | https://wtop.com/prince-william-county/2025/11/digital-gateway-data-center-builders-barred-from-beginning-construction-until-legal-challenge-plays-out/ | 上诉阶段明确“不得开工”，并给出2026年口头辩论排期
  - 主流媒体 | 2025-11-08 | https://www.washingtonpost.com/dc-md-va/2025/11/08/prince-william-county-gainseville-election/ | 把数据中心扩张与地方选举/政策分歧绑定，验证其持续政治外溢
  - 律所复盘 | 2025-08-25 | https://www.beankinney.com/data-center-infrastructure-under-siege-lessons-from-virginias-digital-gateway-decision/ | 归纳判决要点与对开发/融资合规路径的影响（机制层面）

- sources (初报与当时材料):
  - initial_report: https://wtop.com/prince-william-county/2025/08/judge-voids-digital-gateway-rezoning-in-prince-william-county/
  - time_slice_supporting: https://virginiabusiness.com/judge-voids-massive-prince-william-digital-gateway-project/

- notes: 属于“许可/司法程序硬约束”典型样本；初报应避免把后续上诉结果写死。
---

---
## news_id: DC-US-2025-09-01
- domain: 数据中心
- initial_report_date: 2025-09-03
- title: Dominion向弗吉尼亚SCC提出“高负荷/数据中心”新费率与更强合约约束（最低需求、电力担保等）
- label: Major
- hard_negative: false
- summary: 数据中心从“普通大工商业用户”被分离为新费率类别，并引入更强的合同与担保条款，成本与退出风险上移。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: 新费率类别+更长合约/最低需求/担保→把电网扩建与搁浅风险更多压回大负荷侧→降低投机性申报与“短期跳车”→短期提高接入成本与谈判复杂度，长期改善电网规划可预测性与成本分摊公平性。  
- observable_features_at_time:
  - 变化量: 提出“新rate class/新rate schedule”（具体费率水平以案卷为准）
  - 约束类型: 电价合同、最低需求/期限、担保/抵押、退出费/费用分摊
  - 时间表: 2025-09提出；监管裁决窗口 Unknown（初报阶段）
  - 影响范围: Dominion服务区（NoVA数据中心核心区）
  - 证据等级: 权威地方媒体深度 + 监管机构/公司案卷
  - 可复用信号: “rate class拆分”+“合同期限≥10年级别”+“最低需求（如85%）”+“抵押/担保”
  - Unknown: 最终核准条款与生效日期（初报时未定）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管机构 | 2025-11-25 | https://www.scc.virginia.gov/about-the-scc/newsreleases/release/scc-issues-order-on-dev-biennial-review-2025/scc-rules-in-dev-biennial-review-case.html | SCC正式批准创建面向最大用电户（含数据中心）的新费率类别
  - 行业媒体 | 2025-11-27 | https://www.datacenterdynamics.com/en/news/virginia-regulators-approve-new-rate-class-for-data-centers-and-other-large-loads/ | 解读该费率类别适用门槛与对数据中心成本/合同的影响
  - 咨询研究 | 2025-11-26 | https://www.poweradvisoryllc.com/reports/the-impact-of-large-loads-on-rate-design | 对Dominion条款（长约、最低需求等）做结构化总结，强调其行业意义

- sources (初报与当时材料):
  - initial_report: https://virginiamercury.com/2025/09/03/dominion-proposes-higher-utility-rates-new-rate-class-for-data-centers/
  - time_slice_supporting: https://www.axios.com/local/richmond/2025/09/08/virginia-dominion-rate-hikes-richmond-power-bill

- notes: 该条是“费率/合同硬约束制度化”的典型重大事件；初报阶段避免引用后续裁决的最终数值。
---

---
## news_id: DC-US-2025-09-02
- domain: 数据中心
- initial_report_date: 2025-09-04
- title: Hitachi Energy宣布在美国电网关键设备制造投资$10亿（含大型电力变压器产能），回应AI数据中心带来的设备瓶颈
- label: Major
- hard_negative: false
- summary: 变压器与高压设备是数据中心投运“硬卡点”，该投资把“设备紧缺→产能扩张”从叙事变成可验证的制造计划与投产窗口。

- axes_and_direction:
  - pace: mixed
  - cost: mixed
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 设备交期过长→龙头宣布在美扩产（新厂/扩建）→中长期缓解变压器供给缺口、改善可交付性→但短期仍受建设周期与供应链限制，2025-2027阶段约束依旧偏紧。  
- observable_features_at_time:
  - 变化量: $1B制造投资；其中包含大型电力变压器新产线/新厂（具体分项以公告为准）
  - 约束类型: 变压器/高压设备供给、强电施工、并网工程交期
  - 时间表: 新设施投产窗口（公告口径为2027-2028级别；以初报为准）
  - 影响范围: 全美电网设备供应链（跨公用事业/跨区域）
  - 证据等级: 公司新闻稿 + 权威媒体
  - 可复用信号: “制造投资额+投产年份+产能类型（LPT/高压设备）”
  - Unknown: 对具体地区/具体项目的直接分配与优先级

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体专题 | 2025-12-02 | https://www.reuters.com/business/energy/grid-equipment-makers-invest-us-ease-supply-shortage--reeii-2025-12-02/ | 把Hitachi与其他厂商扩产并列，确认“设备短缺→扩产潮”并给出交期/缺口背景
  - 权威媒体 | 2025-10-28 | https://www.reuters.com/business/energy/hitachi-partners-with-us-modernize-grid-2025-10-28/ | 明确回指9月的$1B扩产计划，并说明其在电网现代化/负荷增长背景下的角色

- sources (初报与当时材料):
  - initial_report: https://www.reuters.com/business/energy/hitachi-invest-1-billion-produce-power-grid-components-us-2025-09-04/
  - time_slice_supporting: https://www.hitachienergy.com/us/en/news-and-events/press-releases/2025/09/hitachi-announces-historic-1-billion-usd-manufacturing-investment-to-power-america-s-energy-future-through-production-of-critical-grid-infrastructure , https://www.manufacturingdive.com/news/hitachi-unveils-1b-grid-manufacturing-investment-virginia-transformer/759512/

- notes: 该条属于“供应链约束缓解”的重大事件；初报应只记录投资与计划，不提前宣称交期一定缩短到何种程度。
---

---
## news_id: DC-US-2025-09-03
- domain: 数据中心
- initial_report_date: 2025-09-23
- title: OpenAI/Oracle/SoftBank宣布“Stargate”新增5个美国AI数据中心站点，目标形成近7GW规划容量并推进$5000亿级基础设施平台
- label: Major
- hard_negative: false
- summary: 以“多站点+GW级规划容量+跨主体融资”形式把AI数据中心从项目变成平台级基础设施，对电力、设备与地方审批形成持续拉动。

- axes_and_direction:
  - pace: accelerate
  - cost: up
  - constraint: tighten
  - supply_demand: loosen

- subsequent_impact_path: 多站点扩张公告→锁定跨州电力与土地资源、引发并网/费率/自备电谈判→推动供应链与施工资源再分配→在热点州形成“园区化、超大负荷、长周期交付”的新常态，并放大电网侧规则改革压力。  
- observable_features_at_time:
  - 变化量: 新增5个站点；规划“近7GW”级别容量叙事（以初报口径）
  - 约束类型: 供电/并网、变压器与高压设备、施工与劳动力、冷却与用水、地方许可
  - 时间表: 多站点分期推进（单站点COD/energization Unknown）
  - 影响范围: 多州（TX/NM/OH/中西部等），跨电网/跨公用事业
  - 证据等级: 公司披露 + 权威媒体
  - 可复用信号: “站点数量+跨州名单+平台级融资规模”+“GW级容量口径”
  - Unknown: 各站点最终MW拆分、并网/自备电方案

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体 | 2025-12-17 | https://www.reuters.com/technology/oracles-10-billion-michigan-data-center-limbo-after-blue-owl-funding-talks-stall-2025-12-17/ | 把Michigan>1GW项目与Stargate绑定，显示其已进入“融资与建设排期”阶段并持续影响市场预期
  - 权威媒体 | 2026-01-28 | https://www.reuters.com/business/media-telecom/softbank-talks-invest-up-30-billion-more-openai-wsj-reports-2026-01-28/ | 后续融资动作继续围绕OpenAI与Stargate叙事，验证其平台级长期性
  - 公司披露 | 2025-09-24 | https://group.softbank/en/news/press/20250924 | SoftBank发布5站点公告并给出规划容量/投资口径（作为官方佐证）

- sources (初报与当时材料):
  - initial_report: https://www.reuters.com/business/media-telecom/openai-oracle-softbank-plan-five-new-ai-data-centers-500-billion-stargate-2025-09-23/
  - time_slice_supporting: https://openai.com/index/five-new-stargate-sites/ , https://www.datacenterdynamics.com/en/news/openai-announces-five-more-us-stargate-data-centers-with-oracle-and-softbank/

- notes: 该条是“平台级扩张公告”，初报阶段信息密度高但落地路径多，适合训练模型识别“站点+融资+容量口径”组合信号。
---

---
## news_id: DC-US-2025-09-04
- domain: 数据中心
- initial_report_date: 2025-09-17
- title: Prince George’s County（马里兰）对数据中心开发实施临时暂停（moratorium），为制定更严格标准争取时间
- label: Major
- hard_negative: false
- summary: 靠近NoVA的大负荷边缘地区对数据中心采取“先暂停、再立规”，将社区与许可风险制度化，成为选址与投运节奏的新约束维度。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: 暂停审批→形成任务组/报告与更严格的公开审查机制→提高项目时间成本与合规成本→推动开发商转向“可被社区接受+可解释的资源方案”（电、水、噪声、交通）或迁移至管控更明确区域。  
- observable_features_at_time:
  - 变化量: 180天级别暂停/暂停范围（以当地立法文本为准）
  - 约束类型: 土地/许可、社区反对、噪声与环境、用水与公用事业容量
  - 时间表: 2025-09启动；到期/是否延长 Unknown（初报阶段）
  - 影响范围: 马里兰单县，但位于大负荷走廊外溢带，示范效应强
  - 证据等级: 地方政府/立法 + 权威地方媒体
  - 可复用信号: “moratorium+任务组/标准制定”组合；“审批路径由by-right转向需公开审查”
  - Unknown: 最终标准（噪声/水/电/退场机制）细则

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 主流媒体深度 | 2025-12-02 | https://www.washingtonpost.com/dc-md-va/2025/12/02/data-centers-prince-georges-policy/ | 披露任务组报告与监管改革方向，确认该暂停进入制度化规则阶段
  - 研究/政策媒体 | 2025-12-17 | https://techpolicy.press/the-real-race-for-an-ai-moratorium-stopping-data-centers | 将多地moratorium作为全国性趋势进行总结，验证“社区-许可约束”成为行业变量
  - 独立调查媒体 | 2026-01-12 | https://heatmap.news/politics/data-center-cancellations-2025 | 统计地方反对导致项目取消/延后增加，支持“许可与社区阻力对节奏的结构性影响”机制

- sources (初报与当时材料):
  - initial_report: https://marylandmatters.org/2025/09/17/prince-georges-county-moves-to-put-data-center-development-on-pause/
  - time_slice_supporting: https://conduitstreet.mdcounties.org/2025/09/24/prince-georges-pauses-data-center-approvals-amid-policy-review/ , https://princegeorgescountymd.legistar.com/LegislationDetail.aspx?GUID=558AF087-8E60-47B4-B003-C94F4D67B68D&ID=7658373&Options=ID%7CText%7C&Search=data+center

- notes: 该条的重大性来自“制度化许可/社区约束”，不应把其简化为一次性政治事件。
---

---
## news_id: DC-US-2025-08-90
- domain: 数据中心
- initial_report_date: 2025-08-28
- title: Tri-State向FERC提交High Impact Load Tariff（>45MW）试图以担保金/最低期限等管理数据中心等大负荷，但后续被FERC拒绝
- label: NotMajor
- hard_negative: true
- summary: 初报看似将形成可复制的大负荷费率模板，但FERC以零售管辖为由拒绝，未形成可执行的长期行业框架。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 提交HILT→引发对“批发/零售管辖边界”的审查→FERC拒绝→未能以该路径落地统一费率框架，影响主要停留在个案与管辖讨论层面。  
- observable_features_at_time:
  - 变化量: 适用门槛>45MW；包含担保金、最低期限、最低月度需求/电量条款
  - 约束类型: 费率/合同、担保/抵押、成本分摊
  - 时间表: 2025-08-28提交；后续裁决时间 Unknown（初报时）
  - 影响范围: Tri-State成员系统（区域性），潜在示范但未必可外推
  - 证据等级: 公司披露（提交公告）+ 监管裁决（后续）
  - 可复用信号: “HILT/High Impact Load Tariff”+“>45MW门槛”+“担保金/最低期限”
  - Unknown: 最终是否修订再提（初报时未知）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管结果（行业媒体报道） | 2025-10-29 | https://www.utilitydive.com/news/ferc-tri-state-large-load-tariff-data-center-doe/804076/ | 明确FERC于2025-10-27拒绝该tariff，指出其触及零售管辖
  - 法律/政策复盘 | 2026-01-?? | https://davisgraham.com/news-events/federal-and-colorado-action-on-data-centers-and-large-power-loads/ | 总结该tariff被拒与“未再提出修订版本”的状态，作为“未落地”的后验证据

- sources (初报与当时材料):
  - initial_report: https://tristate.coop/collaborative-work-results-ferc-filing-tri-states-high-impact-load-tariff-and-agreement
  - time_slice_supporting: https://www.rtoinsider.com/wp-content/uploads/2025/09/ER25-3316-Tri-State-HILT-public.pdf

- notes: hard_negative原因=被监管拒绝、未形成可执行框架；适合作为“看似制度化但因管辖问题落空”的负例。
---

---
## news_id: DC-US-2025-09-90
- domain: 数据中心
- initial_report_date: 2025-09-03
- title: PJM提出/讨论“NCBL（非一致性基荷）”等方案以便在紧急情况下优先限电数据中心并免除容量采购，但遭利益相关方强烈反对
- label: NotMajor
- hard_negative: true
- summary: 当时看似将快速改变数据中心在PJM的接入与市场义务，但后续未成为共识方案，最终董事会方案走向不同路径。

- axes_and_direction:
  - pace: uncertain
  - cost: mixed
  - constraint: mixed
  - supply_demand: uncertain

- subsequent_impact_path: 提案引发反对（法律/市场/可靠性框架争议）→难以形成成员共识→董事会后续以CIFP产出推进其他组合方案→NCBL未成为稳定的制度化落地。  
- observable_features_at_time:
  - 变化量: 提案包含“可被优先限电”与“容量市场义务调整”等设计
  - 约束类型: 市场规则（容量义务）、可靠性应急机制、接入条件
  - 时间表: 2025-09讨论窗口；提交FERC/生效 Unknown（初报时）
  - 影响范围: PJM全区（若落地将很重大）
  - 证据等级: 权威行业媒体 + 市场监测机构观点
  - 可复用信号: “免容量采购/优先限电”这种强条款往往引发法域与可执行性争议
  - Unknown: 是否会被替代为BYOG/退出费/担保等其他机制

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 系统运营商复盘 | 2026-01-08 | https://insidelines.pjm.com/2025-year-in-review-planning-prepares-for-burgeoning-electricity-demand/ | 复盘显示CIFP最终未形成成员共识，董事会另行形成综合方案
  - 系统运营商董事会决定 | 2026-01-16 | https://insidelines.pjm.com/pjm-board-outlines-plans-to-integrate-large-loads-reliably/ | 最终“整合大负荷”方案并非以NCBL为单一核心机制
  - 权威媒体 | 2026-01-27 | https://www.reuters.com/business/energy/us-grid-rules-faster-data-centers-favor-on-site-gas-plants--reeii-2026-01-27/ | 后续报道强调的新规则更偏向“自带供给/快速供电”，与NCBL路线不同

- sources (初报与当时材料):
  - initial_report: https://www.utilitydive.com/news/pjm-stakeholders-ncbl-data-center-fast-track/759096/
  - time_slice_supporting: https://www.pjm.com/-/media/DotCom/committees-groups/cifp-lla/postings/20250828-stakeholder-comments-cifp-lla.pdf

- notes: hard_negative原因=“强条款提案”未能跨主体形成可执行共识；适合训练模型识别“看似强监管但难落地”的新闻。
---

---
## news_id: DC-US-2025-09-91
- domain: 数据中心
- initial_report_date: 2025-09-17
- title: 报告称美国数据中心建设在2025年出现放缓（以电力供应不足为主要原因），但缺乏后续多源证据证明其构成行业“供需拐点”
- label: NotMajor
- hard_negative: true
- summary: 初报容易被误读为“AI数据中心需求见顶/建设退潮”，但后续多条平台级扩张与电网规则改革并行，说明更像短期节奏波动。

- axes_and_direction:
  - pace: mixed
  - cost: mixed
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: 报告口径显示短期投资/开工放缓→市场可能解读为需求拐点→但后续平台级扩张（Stargate等）与大负荷费率/规则加速推进→更符合“电力/许可约束导致的阶段性延后”，而非需求崩塌。  
- observable_features_at_time:
  - 变化量: 报告提及“建设下滑比例/投资下降”（以报告摘要为准）
  - 约束类型: 电力供应/并网窗口不足（作为放缓理由）
  - 时间表: 2025年内（未给出明确反转时点）
  - 影响范围: 全国口径（但数据与方法依赖单一机构）
  - 证据等级: 二手新闻转述研究机构报告
  - 可复用信号: “研究口径放缓”若缺乏多源交叉验证，重大性存疑
  - Unknown: 分区域差异、是否为样本口径变化导致

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 公司/项目平台扩张 | 2025-09-23 | https://www.reuters.com/business/media-telecom/openai-oracle-softbank-plan-five-new-ai-data-centers-500-billion-stargate-2025-09-23/ | 同期出现平台级扩张公告，与“需求见顶”叙事不一致
  - 设备扩产（供给侧验证约束仍强） | 2025-12-02 | https://www.reuters.com/business/energy/grid-equipment-makers-invest-us-ease-supply-shortage--reeii-2025-12-02/ | 交期与扩产投资表明瓶颈仍在“电网设备/交付”，支持“延后而非拐点”解释

- sources (初报与当时材料):
  - initial_report: https://dailyreporter.com/2025/09/17/data-center-construction-slows-power-supply-2025/
  - time_slice_supporting: https://www.latitudemedia.com/news/three-major-risks-slowing-the-3t-data-center-boom/

- notes: hard_negative原因=缺乏多源持续确认其为“需求拐点”；更像供电约束下的阶段性延后与统计口径叠加。
---

---
## news_id: DC-US-2025-09-92
- domain: 数据中心
- initial_report_date: 2025-09-17
- title: 佐治亚州Troup County通过90天数据中心申请暂停（moratorium），但其影响主要停留在县域层面，难以直接外推为全国性硬约束转折
- label: NotMajor
- hard_negative: true
- summary: 地方暂停引发关注，但缺少后续多源证据证明该县的单一措施改变了全国装机/投运节奏或成本结构。

- axes_and_direction:
  - pace: delay
  - cost: mixed
  - constraint: tighten
  - supply_demand: uncertain

- subsequent_impact_path: 县域暂停审批→为制定地方条例争取时间→若无跨县/跨州复制与行业级规则联动，其影响主要是局部项目延后/迁移，难构成行业变量改变。  
- observable_features_at_time:
  - 变化量: 90天暂停；覆盖许可/重划/施工等申请
  - 约束类型: 土地/分区审批、地方基础设施容量（电/水）
  - 时间表: 2025-09-16生效；90天窗口
  - 影响范围: 单县（Troup County）
  - 证据等级: 地方媒体+县政府信息
  - 可复用信号: “短期moratorium+条例研究”通常是地方治理噪音与政策信号混合
  - Unknown: 暂停结束后的最终条例强度与是否延长

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 缺乏针对该县的持续行业级确认（作为“缺乏持续确认”的佐证，后验更多停留在州内条例盘点层面） | 2025-10-22 | https://www.gpb.org/news/2025/10/22/wave-of-data-center-ordinances-sweep-through-ga-counties-how-strict-are-they | 后续报道更多呈现“各地强度不一的条例拼图”，未形成统一行业级规则转折
  - 全国层面讨论更多聚焦电网费率/并网规则而非单县暂停 | 2025-12-17 | https://www.latitudemedia.com/news/the-unsettled-landscape-of-large-load-tariffs/ | 行业结构性变化更集中在大负荷费率/合同机制

- sources (初报与当时材料):
  - initial_report: https://www.fox5atlanta.com/news/troup-countys-90-day-pause-data-centers
  - time_slice_supporting: https://www.gpb.org/news/2025/10/22/wave-of-data-center-ordinances-sweep-through-ga-counties-how-strict-are-they

- notes: hard_negative原因=单县事件外推性弱；且缺乏“该事件本身”被多源在后续明确引用为行业变量改变的证据链。
---

---
## news_id: DC-US-2025-07-99
- domain: 数据中心
- initial_report_date: 2025-07-23
- title: 白宫发布《Accelerating Federal Permitting of Data Center Infrastructure》行政令，要求联邦层面加速“合格数据中心项目”许可
- label: Unlabeled
- hard_negative: false
- summary: 属于联邦层面的“流程方向性”政策，但到2026-01为止仍难以将其与具体MW投运节奏变化建立可验证因果链。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 联邦许可提速意图→若能落地将缩短部分联邦环评/用地许可→但真实影响取决于州/地方审批、电网接入与设备交期，当前证据不足以稳定标注为Major。  
- observable_features_at_time:
  - 变化量: 要求联邦机构在180天窗口内审查/调整相关全国通用许可（NWP）等
  - 约束类型: 许可/审批（联邦层面）
  - 时间表: EO发布2025-07-23；多个“within X days”节点
  - 影响范围: 全国（但仅覆盖“Qualifying Projects”）
  - 证据等级: 联邦行政令
  - 可复用信号: “EO+明确时限+联邦机构清单”
  - Unknown: Qualifying Projects定义边界与实际适用范围

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - N/A

- sources (初报与当时材料):
  - initial_report: https://www.whitehouse.gov/presidential-actions/2025/07/accelerating-federal-permitting-of-data-center-infrastructure/
  - time_slice_supporting: https://www.whitecase.com/insight-alert/trump-administration-issues-executive-order-streamline-data-center-development

- notes: 该条更适合作为“政策背景/上下文”，除非后续出现明确的项目级许可提速案例链条。
---

---
## news_id: DC-US-2025-08-99
- domain: 数据中心
- initial_report_date: 2025-08-07
- title: Joule与Caterpillar/Wheeler宣布为犹他州HPC数据中心园区提供多GW级现场电力方案（项目公告型）
- label: Unlabeled
- hard_negative: false
- summary: 单体园区公告信息量高，但缺乏后续多源把其确认成改变行业硬约束（并网/费率/设备）的“制度性事件”。

- axes_and_direction:
  - pace: uncertain
  - cost: mixed
  - constraint: mixed
  - supply_demand: mixed

- subsequent_impact_path: 项目公告→若推进将体现“自备电/现场电力”路径的可行性→但是否成为可复制范式取决于后续融资、许可与交付里程碑。  
- observable_features_at_time:
  - 变化量: 宣称“4GW级”供能愿景（以公告口径）
  - 约束类型: 供电（现场发电/储能）、许可（排放/用地）、设备交付
  - 时间表: “计划明年启动”等（具体窗口 Unknown）
  - 影响范围: 单州单园区
  - 证据等级: 公司新闻稿/行业媒体
  - 可复用信号: “多GW现场电力+HPC园区”组合
  - Unknown: 最终MW拆分、并网关系、客户锁定程度

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - N/A

- sources (初报与当时材料):
  - initial_report: https://investors.caterpillar.com/news/news-details/2025/Joule-Caterpillar-and-Wheeler-Announce-an-Agreement-to-Power-Americas-Growing-Data-Center-Energy-Needs/default.aspx
  - time_slice_supporting: https://www.powermag.com/caterpillar-among-groups-working-on-massive-utah-data-center-campus/

- notes: 若后续出现“空气许可/融资关闭/首期投运MW”里程碑，可再升级为可标注事件。
---

# 数据中心-美国-2025Q3 标注集（hindsight）

## news_id: DC-US-2025-10-01
- domain: 数据中心
- initial_report_date: 2025-10-29
- title: FERC否决Tri-State“High Impact Load Tariff（HILT）”大负荷费率方案（数据中心等），强调零售条款超出FERC管辖
- label: Major
- hard_negative: false
- summary: 联邦监管否决HILT，改变“用FERC费率框架管大负荷”的路径预期，推动问题回到州/零售监管层面。

- axes_and_direction:
  - pace: mixed
  - cost: mixed
  - constraint: mixed
  - supply_demand: uncertain

- subsequent_impact_path: FERC否决（管辖边界明确）→合作社/公用事业难以在FERC层面直接把担保金/最低期限等零售条款制度化→大负荷治理更可能转向州PUC/地方费率与接入合同→区域性项目的接入节奏与成本分摊机制更碎片化。  
- observable_features_at_time:
  - 变化量: “被拒绝的HILT/HILA”及其拟包含的担保/最低期限等零售条款（具体条款以公开文件为准）
  - 约束类型: 电价与合同（最低期限/担保）、成本分摊、接入治理
  - 时间表: FERC裁决日期为2025-10-27（媒体初报在10月下旬）
  - 影响范围: Tri-State成员系统（山地西部），但对“监管路径”有示范意义
  - 证据等级: 联邦监管裁决+权威行业媒体
  - 可复用信号: “FERC以管辖为由否决大负荷费率设计”这一监管边界信号
  - Unknown: 后续是否通过州层面重新设计并落地（初报时未知）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 行业媒体 | 2025-10-29 | https://www.utilitydive.com/news/ferc-tri-state-large-load-tariff-data-center-doe/804076/ | 明确FERC于10/27拒绝HILT，并点出原因与对大负荷治理的含义
  - 行业媒体 | 2025-10-28 | https://www.rtoinsider.com/118388-ferc-rejects-tri-states-high-impact-load-tariff/ | 解释该tariff意图与被拒后对成员系统应对数据中心负荷的影响
  - 律所解读 | 2025-11-13 | https://www.steptoe.com/en/news-publications/powering-the-future-whats-new-in-large-load-regulation.html | 将该裁决作为“管辖边界”案例总结，提示后续需在州权框架内设计零售保护与负荷管理

- sources (初报与当时材料):
  - initial_report: https://www.utilitydive.com/news/ferc-tri-state-large-load-tariff-data-center-doe/804076/
  - time_slice_supporting: https://elibrary.ferc.gov/eLibrary/docinfo?accession_Number=20251003-5131

- notes: 该条的“重大性”来自监管路径改变（能做/不能做什么），不是某个单项目；对全国影响取决于各州是否跟进零售侧制度化。
---

---
## news_id: DC-US-2025-11-01
- domain: 数据中心
- initial_report_date: 2025-11-06
- title: 宾州PUC通过“面向大负荷（含数据中心）的Model Tariff”暂行命令，要求成本归因与接入治理框架化
- label: Major
- hard_negative: false
- summary: 宾州把数据中心等大负荷接入与成本分摊纳入统一“模型费率/条款”，推动从个案谈判转向制度化规则。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: PUC暂行命令→提出大负荷定义、担保/合同期限、成本归因与透明度→降低投机性负荷申请对电网规划的干扰→短期提高接入门槛与前置成本，长期提升可预测性与成本分摊公平性。  
- observable_features_at_time:
  - 变化量: “Tentative Order/Model Tariff”进入公众评议（具体条款以PUC文本为准）
  - 约束类型: 并网/接入、成本分摊、担保/抵押、最低合同条款
  - 时间表: 2025-11-06表决；后续公众评论与可能的采用/推广窗口（初报时未定）
  - 影响范围: 宾州（PJM区域内），具“可复制监管模板”属性
  - 证据等级: 监管机构公告/公报+权威媒体
  - 可复用信号: “PUC模型费率（不是单一公司费率）+明确针对large load/data centers”
  - Unknown: 最终是否强制、各公用事业采用程度

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管机构 | 2025-11-06 | https://www.puc.pa.gov/press-release/2025/puc-advances-plan-to-balance-data-center-growth-and-consumer-protection-11062025 | 官方说明模型费率目的：可靠性与成本归因
  - 权威媒体 | 2025-11-12 | https://www.govtech.com/infrastructure/pa-proposes-tariff-model-to-offset-data-center-power-consumption | 把该模型费率与“保护居民不为数据中心基础设施买单”机制联系起来
  - 学术/研究机构评论 | 2026-01-31 | https://kleinmanenergy.upenn.edu/commentary/blog/new-pennsylvania-law-aims-to-protect-ratepayers-from-speculative-data-center-demand/ | 将2025年11月PUC 3-2推进模型费率作为关键监管动作回顾，强调其对投机性负荷与成本分摊的长期意义

- sources (初报与当时材料):
  - initial_report: https://www.puc.pa.gov/press-release/2025/puc-advances-plan-to-balance-data-center-growth-and-consumer-protection-11062025
  - time_slice_supporting: https://www.pacodeandbulletin.gov/Display/pabull?file=%2Fsecure%2Fpabulletin%2Fdata%2Fvol55%2F55-47%2F1589.html , https://www.puc.pa.gov/press-release/2025/puc-announces-publication-of-tentative-order-on-model-tariff-for-large-load-customers-11242025

- notes: 该条是“监管制度化”事件；初报阶段不应把其等同于已经强制生效的终局规则。
---

---
## news_id: DC-US-2025-11-02
- domain: 数据中心
- initial_report_date: 2025-11-25
- title: 弗吉尼亚SCC在Dominion双年度审查案中批准设立面向最大用电户（含数据中心）的新费率类别
- label: Major
- hard_negative: false
- summary: 数据中心被从一般工商业负荷中剥离为独立费率类别，合同/成本归因更刚性，直接影响NoVA投运节奏与成本结构。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: 新费率类别→更强调大负荷对电网扩建与搁浅风险的承担→提高最低需求/合同约束的可执行性→短期抬升接入与用电成本、增强退出惩罚，长期改善电网规划可预测性并缓解居民侧成本外溢争议。  
- observable_features_at_time:
  - 变化量: SCC批准“new rate class for biggest users / data centers”（具体门槛与生效以裁决为准）
  - 约束类型: 电价与合同、成本分摊、接入条件（以费率与条款体现）
  - 时间表: 2025-11-25裁决发布；执行生效节奏以监管决定为准（初报材料可查）
  - 影响范围: Dominion服务区（美国最大数据中心集群核心区）
  - 证据等级: 监管机构裁决+权威媒体深度
  - 可复用信号: “监管裁决设立新费率类别（按负荷特征/规模）”这一强制度信号
  - Unknown: 最终费率水平、合同条款细节的微观结构（需读案卷）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管机构 | 2025-11-25 | https://www.scc.virginia.gov/about-the-scc/newsreleases/release/scc-issues-order-on-dev-biennial-review-2025/scc-rules-in-dev-biennial-review-case.html | SCC宣布批准创建最大用电户新费率类别（含数据中心）
  - 权威媒体 | 2025-11-25 | https://virginiamercury.com/2025/11/25/scc-approves-chesterfield-gas-plant-and-dominion-rate-hike-creates-new-rate-class-for-data-centers/ | 披露门槛与并行的电源/费率安排，强调其对数据中心成本归因的意义
  - 研究/智库 | 2026-01-08 | https://www.americanactionforum.org/insight/virginias-new-data-center-electricity-rate-class/ | 回顾该新费率类别的适用门槛与生效窗口，讨论其对大负荷成本分摊与激励的结构性影响

- sources (初报与当时材料):
  - initial_report: https://www.scc.virginia.gov/about-the-scc/newsreleases/release/scc-issues-order-on-dev-biennial-review-2025/scc-rules-in-dev-biennial-review-case.html
  - time_slice_supporting: https://www.selc.org/press-release/dominion-customers-to-see-rate-increase-though-scc-takes-steps-designed-to-ensure-data-centers-pay-fair-share/

- notes: 该条与“电网接入能力”共同构成NoVA的硬约束；但其真实影响强度取决于后续费率细则与合同执行。
---

---
## news_id: DC-US-2025-12-01
- domain: 数据中心
- initial_report_date: 2025-12-18
- title: FERC指令PJM就“AI数据中心等大负荷与电厂共址”建立透明规则并修订OATT（联邦层面直接介入）
- label: Major
- hard_negative: false
- summary: FERC要求PJM制定共址大负荷服务规则与新型输电服务，直接改变PJM区数据中心“更快接入/更强自带供给”的制度环境。

- axes_and_direction:
  - pace: mixed
  - cost: mixed
  - constraint: mixed
  - supply_demand: mixed

- subsequent_impact_path: FERC认定PJM现行条款不清晰→要求建立透明规则与服务产品→把共址负荷的接入、成本与可靠性责任制度化→数据中心更可能通过“共址发电/快速可控供给”获取更快接入，但也面临更明确的规则与责任边界。  
- observable_features_at_time:
  - 变化量: “FERC directed PJM to establish transparent rules / revise OATT”（具体规则需后续提交）
  - 约束类型: 并网/接入规则、输电服务条款、可靠性与成本分摊
  - 时间表: 2025-12-18发布；后续PJM提交与生效窗口由FERC程序决定（初报时Unknown）
  - 影响范围: PJM全区（覆盖美国最密集数据中心负荷走廊）
  - 证据等级: 联邦监管机构官方发布+权威媒体
  - 可复用信号: “FERC直接指令+共址大负荷+OATT被认定不合理”是极强制度信号
  - Unknown: 规则最终形态（是否偏向BYOG/可中断/新服务产品）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 联邦监管机构 | 2025-12-18 | https://www.ferc.gov/news-events/news/ferc-directs-nations-largest-grid-operator-create-new-rules-embrace-innovation-and | FERC官方概述命令：为AI数据中心等共址大负荷建立透明规则、保护可靠性与消费者
  - 权威媒体 | 2025-12-18 | https://www.reuters.com/business/energy/us-energy-regulator-directs-pjm-launch-rules-ai-connections-2025-12-18/ | 说明命令背景（电价/可靠性争议）与要求PJM修订OATT
  - 律所解读 | 2025-12-23 | https://www.blankrome.com/publications/ferc-issues-order-clarifying-data-center-and-large-load-interconnection-procedures-pjm | 将该命令解释为“共址大负荷接入框架”并讨论其对开发模式与时间线的影响

- sources (初报与当时材料):
  - initial_report: https://www.reuters.com/business/energy/us-energy-regulator-directs-pjm-launch-rules-ai-connections-2025-12-18/
  - time_slice_supporting: https://www.ferc.gov/news-events/news/fact-sheet-ferc-directs-nations-largest-grid-operator-create-new-rules-embrace

- notes: 该条属于“联邦监管直接改写规则空间”；对数据中心投运节奏方向可能是“更可预期/更偏向可快速上线供给”的混合效应。
---

---
## news_id: DC-US-2025-12-02
- domain: 数据中心
- initial_report_date: 2025-12-02
- title: 美国电网关键设备（变压器/开关设备等）扩产投资潮加速，指向数据中心等驱动的交期瓶颈
- label: Major
- hard_negative: false
- summary: 关键电网设备扩产从“短缺叙事”转为“可验证的投资与投产窗口”，对中期并网能力与成本上行路径有重要影响。

- axes_and_direction:
  - pace: mixed
  - cost: mixed
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 数据中心与电网投资共振→设备交期拉长与价格上行→制造商在美扩产（新厂/扩建）→中期缓解变压器/高压设备约束、改善工程可交付性（但短期仍受建设周期限制）。  
- observable_features_at_time:
  - 变化量: 多家厂商在美扩产投资（金额与项目清单以初报为准）
  - 约束类型: 变压器/高压设备供给、并网工程交期、成本结构
  - 时间表: 多数项目投产在2026-2028区间（以各公司披露为准）
  - 影响范围: 全国供应链（跨公用事业/跨区域）
  - 证据等级: 权威媒体+行业媒体深度+研究机构/咨询评论
  - 可复用信号: “投资额+投产年份+设备类别（LPT/GSU/开关设备）”组合
  - Unknown: 产能分配与对特定州/项目的优先级

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体 | 2025-12-02 | https://www.reuters.com/business/energy/grid-equipment-makers-invest-us-ease-supply-shortage--reeii-2025-12-02/ | 将扩产投资与数据中心等需求驱动、交期拉长联系起来
  - 行业媒体 | 2026-01-06 | https://www.ecmag.com/magazine/articles/article-detail/investment-by-grid-equipment-makers-could-ease-shortage | 逐项列举厂商投资与预计投产窗口，强调其对缓解短缺的意义
  - 行业媒体 | 2026-01-02 | https://www.powermag.com/transformers-in-2026-shortage-scramble-or-self-inflicted-crisis/ | 复盘“短缺/扩产/采购结构”争议，说明瓶颈与缓解路径的行业级影响

- sources (初报与当时材料):
  - initial_report: https://www.reuters.com/business/energy/grid-equipment-makers-invest-us-ease-supply-shortage--reeii-2025-12-02/
  - time_slice_supporting: https://www.woodmac.com/news/opinion/mind-the-gap-tackling-supply-chain-challenges-in-the-electric-td-sector/

- notes: 该条是“供给侧约束缓解”事件；短期是否真正松动取决于投产兑现与采购/验收机制（初报不应承诺立刻改善）。
---

---
## news_id: DC-US-2025-12-03
- domain: 数据中心
- initial_report_date: 2025-12-17
- title: Oracle在密歇根Saline Township的$10B级AI数据中心融资出现重大不确定（Blue Owl退出/更换股权方）
- label: Major
- hard_negative: false
- summary: 超大单体项目在融资结构上出现波动，直接影响投运节奏与市场对“AI基础设施资本可得性”的预期。

- axes_and_direction:
  - pace: delay
  - cost: mixed
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: 核心资金方退出/更换→融资闭合时间延后与条款重谈→开工与交付窗口不确定上升→对“平台级AIDC”形成资金成本与审慎度上移，短期可能延后部分投运、长期促使融资结构更标准化。  
- observable_features_at_time:
  - 变化量: 项目规模$10B量级；资金方（Blue Owl）退出/不参与该笔交易
  - 约束类型: 融资与资本可得性、项目交付窗口、（间接）电力接入与施工资源锁定
  - 时间表: 初报时“尚未签定替代资金方”（具体closing窗口 Unknown）
  - 影响范围: 单项目（密歇根），但因其与OpenAI/Oracle平台叙事绑定而具外溢影响
  - 证据等级: 权威媒体+后续财经媒体/本地公共媒体跟踪
  - 可复用信号: “超大capex项目+关键资金方退出+寻找替代融资”的组合
  - Unknown: 最终融资结构、最终开工/投运时间表

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体 | 2025-12-17 | https://www.reuters.com/technology/oracles-10-billion-michigan-data-center-limbo-after-blue-owl-funding-talks-stall-2025-12-17/ | 描述资金方退出对项目推进与Oracle负债/资本开支预期的影响
  - 本地公共媒体 | 2025-12-18 | https://www.michiganpublic.org/transportation-infrastructure/2025-12-18/developers-dispute-published-report-that-financing-for-controversial-michigan-data-center-project-is-in-limbo | 跟进“是否在limbo”的争议与项目方回应，确认融资不确定性成为关键变量
  - 权威金融媒体 | 2026-01-28 | https://www.bloomberg.com/news/articles/2026-01-28/blackstone-mulls-committing-debt-to-oracle-s-michigan-project | 后续显示仍在寻求更大规模债务/股权支持，验证该项目融资结构对投运节奏的持续影响

- sources (初报与当时材料):
  - initial_report: https://www.reuters.com/technology/oracles-10-billion-michigan-data-center-limbo-after-blue-owl-funding-talks-stall-2025-12-17/
  - time_slice_supporting: https://michiganadvance.com/briefs/saline-township-data-center-faces-potential-funding-snag/ , https://www.datacenterdynamics.com/en/news/blue-owl-opts-not-to-fund-oracles-10bn-michigan-data-center/

- notes: 该条是“项目级重大”；其行业意义在于反映资金成本/条款对AIDC投运的约束已显性化。
---

---
## news_id: DC-US-2025-10-90
- domain: 数据中心
- initial_report_date: 2025-10-09
- title: 科罗拉多Logan County对数据中心/储能/风光等项目实施地方性暂停（moratorium）
- label: NotMajor
- hard_negative: true
- summary: 事件热度高但属于单县治理，影响范围窄，缺乏证据表明其改变全国投运节奏或成本结构。

- axes_and_direction:
  - pace: delay
  - cost: uncertain
  - constraint: tighten
  - supply_demand: uncertain

- subsequent_impact_path: 单县暂停→为更新地方条例争取时间→更多导致项目迁移/延后→未见跨州规则扩散或电网/费率层面的制度化联动。  
- observable_features_at_time:
  - 变化量: moratorium本身（期限/覆盖范围以县决议为准）
  - 约束类型: 土地/许可/地方监管
  - 时间表: 2025-10-09报道；到期与是否延长 Unknown
  - 影响范围: Logan County（单县）
  - 证据等级: 政务/媒体报道
  - 可复用信号: “地方对数据中心与能源项目同步暂停”的组合信号
  - Unknown: 暂停后是否形成可复制的强监管条款

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 政务科技媒体 | 2025-10-09 | https://www.govtech.com/infrastructure/logan-county-colo-pauses-future-energy-data-center-projects | 明确该暂停为地方治理工具、适用范围局限
  - 全国趋势对照（结构性变化更多来自费率/并网规则） | 2025-11-06 | https://www.puc.pa.gov/press-release/2025/puc-advances-plan-to-balance-data-center-growth-and-consumer-protection-11062025 | 同期更具行业影响的变化发生在州PUC费率/接入框架层面，而非单县暂停

- sources (初报与当时材料):
  - initial_report: https://www.govtech.com/infrastructure/logan-county-colo-pauses-future-energy-data-center-projects
  - time_slice_supporting: https://www.govtech.com/infrastructure/logan-county-colo-pauses-future-energy-data-center-projects

- notes: hard_negative原因=地方性强、外推性弱；后验未见其成为行业级规则模板。
---

---
## news_id: DC-US-2025-11-90
- domain: 数据中心
- initial_report_date: 2025-11-10
- title: 弗吉尼亚JLARC发布经济激励审计报告：数据中心占激励资金与税收豁免比重极高（舆论上像“政策转折点”）
- label: NotMajor
- hard_negative: true
- summary: 报告披露强，但本身不改变税制/费率/并网规则；短期更像政治与舆论素材，缺乏立即可执行的硬约束改变。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 审计披露→强化争议与后续立法讨论→但在短期内未直接改写激励到期安排或形成新的强制性约束条款→行业硬变量仍主要由电网接入与费率机制决定。  
- observable_features_at_time:
  - 变化量: 报告披露FY15-FY24激励/税收豁免规模与占比（以报告为准）
  - 约束类型: 政策/税收激励（成本端），但缺少即时执行条款
  - 时间表: 2025-11-10发布
  - 影响范围: 弗吉尼亚州
  - 证据等级: 州级审计机构报告+媒体报道
  - 可复用信号: “审计披露强但不等于规则生效”的识别点
  - Unknown: 后续是否出现立法收紧与生效窗口（初报时未知）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 审计机构报告 | 2025-11-10 | https://jlarc.virginia.gov/pdfs/reports/Rpt611.pdf | 披露激励结构与数据中心税收豁免占比
  - 媒体报道 | 2025-12-03 | https://www.axios.com/local/richmond/2025/12/03/watchdog-report-virginia-data-centers-incentive-funds-2015-2024 | 把报告结论转述为舆论议题，但未对应即时制度落地
  - 后验对照（豁免损失仍在上升） | 2026-01-06 | https://goodjobsfirst.org/virginia-tax-revenue-losses-to-data-centers-soar-to-1-6-billion-for-fy25/ | 显示税收损失仍在上行，侧面证明短期未因该审计报告而出现硬性收紧落地

- sources (初报与当时材料):
  - initial_report: https://jlarc.virginia.gov/pdfs/reports/Rpt611.pdf
  - time_slice_supporting: https://www.axios.com/local/richmond/2025/12/03/watchdog-report-virginia-data-centers-incentive-funds-2015-2024

- notes: hard_negative原因=“披露≠生效”；截至2026-01未见其单独触发可验证的制度性转折。
---

---
## news_id: DC-US-2025-12-90
- domain: 数据中心
- initial_report_date: 2025-12-22
- title: 参议员呼吁全国范围暂停新数据中心建设（moratorium）以应对AI外部性（传播度高）
- label: NotMajor
- hard_negative: true
- summary: 属于政治表态/倡议，不具备可执行条款与生效路径；短期未转化为联邦层面硬约束改变。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 政治呼吁→舆论扩散→若无立法/监管采纳则停留在倡议层→行业硬约束仍由ISO/PUC/公用事业费率与并网规则主导。  
- observable_features_at_time:
  - 变化量: “呼吁moratorium”的政治动作本身（无规则条款）
  - 约束类型: 政策倡议（非监管决定）
  - 时间表: 2025-12-22报道
  - 影响范围: 全国叙事，但缺少制度落地路径
  - 证据等级: 媒体评论/报道
  - 可复用信号: “高传播政治表态+缺少执行机制”是典型误判点
  - Unknown: 是否形成法案并通过（初报时未知）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 媒体评论 | 2025-12-22 | https://prospect.org/2025/12/22/demands-for-data-center-moratoriums-surge/ | 明确是“呼吁/倡议”性质
  - 后验对照（更接近落地的是州/地方层面的提案） | 2026-01-26 | https://www.theguardian.com/technology/2026/jan/26/georgia-datacenters-ai-ban | 展示后续推进主要在州/地方层面，而非已形成联邦硬约束

- sources (初报与当时材料):
  - initial_report: https://prospect.org/2025/12/22/demands-for-data-center-moratoriums-surge/
  - time_slice_supporting: https://techpolicy.press/the-real-race-for-an-ai-moratorium-stopping-data-centers

- notes: hard_negative原因=“政策可执行性弱”；截至2026-01仍未见其对应联邦监管或立法生效链条。
---

---
## news_id: DC-US-2025-12-91
- domain: 数据中心
- initial_report_date: 2025-12-01
- title: PJM市场监测机构/看门狗对数据中心接入发出警告并向FERC申诉（叙事像“电网将拒绝数据中心”）
- label: NotMajor
- hard_negative: true
- summary: 申诉本身不等于规则改变；短期的硬变量来自FERC正式命令与PJM后续规则制定，而非单一看门狗文件。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 看门狗警告/申诉→引发关注与讨论→真正改变需FERC裁决/命令或PJM tariff修订→因此该条更像“预警信号”，非直接制度落地事件。  
- observable_features_at_time:
  - 变化量: 申诉/警告文本与其论点（无立即生效条款）
  - 约束类型: 可靠性争议、成本外溢争议（但仍处于程序阶段）
  - 时间表: 2025-12报道；后续裁决窗口 Unknown
  - 影响范围: PJM区（叙事可能外溢到全国）
  - 证据等级: 媒体报道/申诉材料
  - 可复用信号: “申诉/预警被误读为已生效政策”的典型hard negative
  - Unknown: 申诉是否直接触发具体条款（初报时未知）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 媒体报道 | 2025-12-04 | https://www.businessinsider.com/federal-complaint-warns-pjm-against-servicing-more-data-centers-2025-12 | 描述申诉与风险叙事，但未给出可执行条款落地
  - 后验对照（真正的制度性动作来自FERC命令） | 2025-12-18 | https://www.ferc.gov/news-events/news/ferc-directs-nations-largest-grid-operator-create-new-rules-embrace-innovation-and | FERC随后以正式命令要求PJM建立规则框架（结构性事件在此）

- sources (初报与当时材料):
  - initial_report: https://www.businessinsider.com/federal-complaint-warns-pjm-against-servicing-more-data-centers-2025-12
  - time_slice_supporting: https://www.ferc.gov/news-events/news/ferc-directs-nations-largest-grid-operator-create-new-rules-embrace-innovation-and

- notes: hard_negative原因=“程序性文件/舆论冲击”易被当作政策已落地；应与FERC正式命令、tariff修订区分。
---

---
## news_id: DC-US-2025-12-92
- domain: 数据中心
- initial_report_date: 2025-12-03
- title: BloombergNEF等预测美国数据中心电力需求到2035可达约106GW（数字很大、易被当作‘拐点事件’）
- label: NotMajor
- hard_negative: true
- summary: 属于预测与情景估计，不直接改变并网/费率/设备供给等硬约束；更适合作为背景特征而非事件样本。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 预测发布→市场引用→若无同步监管/投资/合同落地则只改变叙事不改变硬变量→行业真正的拐点更多由费率/并网规则与供应链扩产等“可执行事件”驱动。  
- observable_features_at_time:
  - 变化量: 预测值“106GW by 2035”（取决于模型假设）
  - 约束类型: 无直接条款；最多影响预期与规划讨论
  - 时间表: 2025-12-03发布
  - 影响范围: 全国叙事
  - 证据等级: 研究/媒体转述
  - 可复用信号: “大数字预测+缺少执行机制”=易误判
  - Unknown: 关键假设（AI渗透、效率、上网电价、政策）在初报中往往不透明

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 行业媒体 | 2025-12-03 | https://www.utilitydive.com/news/us-data-center-power-demand-could-reach-106-gw-by-2035-bloombergnef/806972/ | 明确是预测口径与情景估计
  - 后验对照（结构性变化由监管命令推动） | 2025-12-18 | https://www.reuters.com/business/energy/us-energy-regulator-directs-pjm-launch-rules-ai-connections-2025-12-18/ | 同期真正改变硬约束的是FERC对PJM的规则指令，而非预测数字本身

- sources (初报与当时材料):
  - initial_report: https://www.utilitydive.com/news/us-data-center-power-demand-could-reach-106-gw-by-2035-bloombergnef/806972/
  - time_slice_supporting: https://www.utilitydive.com/news/us-data-center-power-demand-could-reach-106-gw-by-2035-bloombergnef/806972/

- notes: hard_negative原因=“预测≠事件”；适合做模型特征/背景，不适合作为重大事件正例。
---

---
## news_id: DC-US-2025-12-99
- domain: 数据中心
- initial_report_date: 2025-12-10
- title: 东南部地区关于“预计数据中心增长”与电网资源组合压力的研究报告发布（研究型，重大性取决于是否触发监管/费率动作）
- label: Unlabeled
- hard_negative: false
- summary: 提供负荷情景与资源组合压力分析，但作为单一研究发布，尚难证明其在短期内触发制度性硬约束改变。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 研究发布→影响舆论与规划讨论→若后续被PUC/公用事业采纳形成费率/IRP约束则可能升级为Major；当前证据不足。  
- observable_features_at_time:
  - 变化量: 提供“数据中心负荷情景”与资源组合压力评估（具体指标以报告为准）
  - 约束类型: 资源充足性/电源规划/成本
  - 时间表: 2025-12-10发布
  - 影响范围: 东南部区域（跨州）
  - 证据等级: 研究报告
  - 可复用信号: “情景建模+资源组合压力”可作为背景特征
  - Unknown: 是否被监管/公用事业正式引用并转化为条款

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - N/A

- sources (初报与当时材料):
  - initial_report: https://www.selc.org/wp-content/uploads/2025/12/2025-Greenlink-IMPACTS-OF-PROJECTED-DATA-CENTER-GROWTH-Report.pdf
  - time_slice_supporting: https://www.selc.org/wp-content/uploads/2025/12/2025-Greenlink-IMPACTS-OF-PROJECTED-DATA-CENTER-GROWTH-Report.pdf

- notes: 需等待后续（≥3-6个月）看其是否被纳入PUC/IRP/费率案或被多源作为“政策转折证据”引用。
---


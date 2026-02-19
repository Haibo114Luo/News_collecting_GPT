---
## news_id: US-WIND-2024-01-001
- domain: 风电
- initial_report_date: 2024-01-03
- title: Equinor and BP Terminate Empire Wind 2 PPA with NYSERDA
- label: Major
- hard_negative: false
- summary: Equinor与BP宣布终止Empire Wind 2项目的OREC协议（1,260 MW），原因为通胀、高利率及供应链中断导致原协议不可行。双方表示此举旨在“重置”项目以寻求新的承购机会（暗示参与后续重标）。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 此事件确立了美国海上风电“合同重置（Contract Reset）”的行业范式。随后在2024年2月的第四轮招标中，Empire Wind 1以更高的执行价格重新中标（从约$118/MWh升至约$150+/MWh水平），验证了通过终止旧合同换取高价新合同的路径有效性，直接推高了行业长期电力采购成本基准。

- observable_features_at_time:
  - 变化量：1,260 MW（Empire Wind 2容量）
  - 状态变更：Terminate OREC Agreement（终止可再生能源证书协议）
  - 核心归因：Inflation, Interest Rates, Supply Chain disruptions（通胀、利率、供应链）
  - 预期动作：Reset and seek new offtake opportunities（重置并寻找新机会）
  - 证据等级：项目业主公司披露（Equinor/BP Press Release）

- confirmations:
  - Regulatory | 2024-02-29 | https://www.nyserda.ny.gov/All-Programs/Offshore-Wind/Focus-Areas/Offshore-Wind-Solicitations/2023-Solicitation | NYSERDA在第四轮招标中重新授予Empire Wind 1合同，验证了“终止-重标”路径。
  - Authority Media | 2024-01-05 | https://www.esgdive.com/news/equinor-bp-terminate-new-york-offshore-wind-project/703780/ | 确认这是行业范围内的经济环境变化导致的结构性调整。

- sources:
  - initial_report: https://www.esgtoday.com/equinor-bp-cancel-major-new-york-offshore-wind-contract/
  - time_slice_supporting: https://www.power-technology.com/news/equinor-and-bp-terminate-new-york-offshore-wind-contract/

- notes: 标志着美国海风从“低价竞争”向“成本修正”周期的硬着陆。
---

---
## news_id: US-WIND-2024-01-002
- domain: 风电
- initial_report_date: 2024-01-03
- title: Vineyard Wind 1 Delivers First Power to the Grid
- label: Major
- hard_negative: false
- summary: 美国首个公用事业规模海上风电项目Vineyard Wind 1（806 MW）的一台涡轮机首次向新英格兰电网输送约5 MW电力。这是美国商业化海上风电“铁塔入水”并实际发电的关键物理里程碑。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 作为首个并网的大型项目，其实际投运证明了美国海上风电供应链（尽管面临挑战）具备最终交付能力。该项目在后续2024年虽遭遇叶片损坏事故，但在Q1时点其成功并网极大提振了融资方信心，确立了联邦水域项目落地的可行性。

- observable_features_at_time:
  - 变化量：5 MW delivered (initial), 806 MW (total planned)
  - 物理状态：First Power / Steel in the water（首次发电）
  - 设备：GE Haliade-X 13 MW turbines（提及具体机型）
  - 地点：15 miles off Martha's Vineyard
  - 证据等级：项目业主与州政府联合披露（Avangrid/CIP/Governor Press Release）

- confirmations:
  - Authority Media | 2024-01-03 | https://www.offshorewind.biz/2024/01/03/806-mw-vineyard-wind-1-offshore-wind-farm-delivers-first-power/ | 确认首台机组并网，验证并网工程节点完成。
  - Industry Data | 2024-02-06 | https://www.gevernova.com/sites/default/files/gevernova_2024_annual_report.pdf | GE Vernova年报中提及Offshore backlog execution，印证交付实质进展。

- sources:
  - initial_report: https://www.vineyardwind.com/press-releases/2024/1/3/cip-avangrid-announce-first-power-from-nation-leading-vineyard-wind-1-project
  - time_slice_supporting: https://www.renewableenergyworld.com/wind-power/offshore/vineyard-wind-1-marks-another-milestone-sends-first-power-to-the-grid-just-behind-schedule/

- notes: 物理节点的权重高于文件节点，属强Major。
---

---
## news_id: US-WIND-2024-02-001
- domain: 风电
- initial_report_date: 2024-02-29
- title: NYSERDA Announces Awards for Empire Wind 1 and Sunrise Wind
- label: Major
- hard_negative: false
- summary: NYSERDA在第四轮海上风电招标中向Empire Wind 1（810 MW）和Sunrise Wind（924 MW）发出有条件授标。这次授标是对之前因成本问题取消合同项目的“救赎”，允许其以反映当前高成本的新价格执行。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: loosen
  - supply_demand: mixed

- subsequent_impact_path: 此次授标不仅挽救了近2 GW的储备项目免于流产，更关键在于确立了美国海风PPA价格的“新常态”（Strike Price大幅上涨）。随后Sunrise Wind在此基础上达成了FID（最终投资决定），证明了监管机构愿意为通胀买单，稳定了供应链预期。

- observable_features_at_time:
  - 变化量：810 MW (Empire Wind 1), 924 MW (Sunrise Wind)
  - 关键动作：Provisional Award / Contract Negotiation（有条件授标）
  - 价格信号：Higher strike prices implied (mentioned as "market reflective")
  - 证据等级：监管机构公告（NYSERDA）

- confirmations:
  - Government | 2024-05-31 | https://www.nyserda.ny.gov/All-Programs/Offshore-Wind/Focus-Areas/Offshore-Wind-Solicitations/2023-Solicitation | 确认合同已于5月正式签署。
  - Industry News | 2024-03-27 | https://www.utilitydive.com/news/sunrise-wind-record-of-decision-orsted-eversource-doi/711394/ | Sunrise Wind随后获得联邦批准，授标是其存活的前提。

- sources:
  - initial_report: https://www.nyserda.ny.gov/All-Programs/Offshore-Wind/Focus-Areas/Offshore-Wind-Solicitations/2023-Solicitation
  - time_slice_supporting: https://www.utilitydive.com/news/new-york-offshore-wind-awards-empire-sunrise/708940/

- notes: 验证了News-001中提到的“重置”逻辑。
---

---
## news_id: US-WIND-2024-01-003
- domain: 风电
- initial_report_date: 2024-01-24
- title: New Jersey Awards 3.7 GW to Leading Light and Attentive Energy
- label: NotMajor
- hard_negative: true
- summary: 新泽西州BPU在第三轮招标中授予两个大型项目：Leading Light Wind (2,400 MW) 和 Attentive Energy Two (1,342 MW)。这是该州历史上最大的单次授标，当时被视为对该州海风目标的巨大推进。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 尽管初报规模巨大，但Leading Light Wind项目在2024年下半年陷入停滞。原因是其选定的涡轮机供应商（GE Vernova）取消了原定的18MW机型开发，导致项目方不得不寻求暂停以重新规划。因此，初报时的“加速”信号在后续被供应链硬约束证伪，未能在预定时间表内转化为实际建设动能。

- observable_features_at_time:
  - 变化量：3,742 MW Total (2,400 MW + 1,342 MW)
  - 承诺：Guaranteed COD dates (implied in bid), Supply chain investments (towers, monopiles)
  - 证据等级：监管机构公告（NJ BPU）

- confirmations:
  - Industry News | 2024-12-06 | https://rechargenews.com/wind/invenergys-2-4gw-leading-light-seeks-pause-on-new-jersey-offshore-wind-project/2-1-1751846 | 确认Leading Light因涡轮机供应问题寻求暂停项目。
  - Analysis | 2024-11-20 | https://www.utilitydive.com/news/nj-offshore-wind-leading-light-invenergy-ge-vernova/733352/ | 确认GE Vernova不再制造18MW机型导致项目受阻。

- sources:
  - initial_report: https://nj.gov/bpu/newsroom/2024/approved/20240124.html
  - time_slice_supporting: https://www.utilitydive.com/news/new-jersey-offshore-wind-awards-invenergy-totalenergies/705494/

- notes: 典型的Hard Negative。当时看是巨大利好，但忽略了超大机型（18MW）尚未成熟的技术/供应链风险，后续被证实不可执行。
---

---
## news_id: US-WIND-2024-02-002
- domain: 风电
- initial_report_date: 2024-02-13
- title: BOEM Finalizes Wind Energy Areas in Oregon
- label: NotMajor
- hard_negative: true
- summary: 美国海洋能源管理局（BOEM）正式确定了俄勒冈州外海的两个风能区域（WEAs），总计可支持2.4 GW装机。此举被宣传为向太平洋浮式风电租赁拍卖迈出的关键一步，计划于2024年内进行拍卖。

- axes_and_direction:
  - pace: accelerate
  - cost: uncertain
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 初报显示联邦政府正在加速开放西海岸浮式风电，但市场反应冷淡。2024年9月，BOEM被迫取消了俄勒冈州的租赁拍卖，原因是仅有一家合格开发商表达了竞标意向，且面临州长和当地部落的强烈反对。初报的“行政加速”未能克服“市场需求不足”的硬约束。

- observable_features_at_time:
  - 变化量：195,012 acres (Final WEAs), 2.4 GW potential
  - 行政动作：Designation of Final WEAs（最终区域划定）
  - 预期时间表：Auction expected later in 2024
  - 证据等级：联邦监管机构公告（BOEM）

- confirmations:
  - Government | 2024-09-27 | https://www.marinelink.com/blogs/blog/us-cancels-oregon-offshore-wind-auction-following-protest-from-101875 | BOEM正式取消拍卖，理由是缺乏行业兴趣。
  - Local Media | 2024-09-30 | https://columbiainsight.org/oregons-offshore-lease-sale-canceled-as-bidders-back-out/ | 确认仅有1家投标者，无法形成竞争性拍卖。

- sources:
  - initial_report: https://www.boem.gov/newsroom/press-releases/boem-finalizes-wind-energy-areas-oregon
  - time_slice_supporting: https://www.utilitydive.com/news/oregon-offshore-wind-energy-areas-boem/707505/

- notes: 行政规划类新闻极易成为假阳性信号（Fake Positive），需以后续实际拍卖结果（Bidder Interest）为准。
---

---
## news_id: US-WIND-2024-04-001
- domain: 风电
- initial_report_date: 2024-04-19
- title: NYSERDA Cancels Three Offshore Wind Projects Due to GE Vernova 18MW Turbine Pivot
- label: Major
- hard_negative: false
- summary: NYSERDA宣布不签署第三轮招标中临时授予的三个项目合同（Attentive Energy One, Community Offshore Wind, Excelsior Wind，共4 GW）。核心原因是首选供应商GE Vernova决定不再开发原本承诺的18MW Haliade-X涡轮机平台，转而专注于15.5/16.5MW机型，导致项目发生“重大变更”且无法维持原定经济性。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 此事件是全球风电供应链“去大兆瓦化（Size Reset）”的标志性时刻。它迫使开发商重新计算项目CAPEX（需更多机位与基础），导致上述4GW项目实际上归零重置。后续行业普遍接受了15MW级作为中期顶峰，甚至影响了新泽西Leading Light Wind等项目的停滞（因同样依赖18MW机型）。

- observable_features_at_time:
  - 变化量：-4,000 MW (Cancelled Provisional Awards)
  - 关键约束：Material Modification (Turbine Size Change 18MW -> 15.5MW)
  - 供应商动作：GE Vernova scraps 18MW platform
  - 证据等级：州能源局公告（NYSERDA Press Release）

- confirmations:
  - Industry Analysis | 2024-12-06 | https://rechargenews.com/wind/invenergys-2-4gw-leading-light-seeks-pause-on-new-jersey-offshore-wind-project/2-1-1751846 | 确认GE取消18MW机型不仅杀死了NY项目，也导致NJ的Leading Light项目在年底寻求暂停。
  - Financial Reporting | 2024-04-25 | https://www.utilitydive.com/news/ge-vernova-offshore-wind-gas-power-turbine-electrification-grid-infrastructure/714854/ | GE Vernova CEO确认公司将保持“高度选择性”，并不再推进18MW，验证了供应链策略的结构性收缩。

- sources:
  - initial_report: https://www.nyserda.ny.gov/About/Newsroom/2024-Announcements/2024-04-19-NYSERDA-Announces-Conclusion-of-OREC-RFP23-1
  - time_slice_supporting: https://www.utilitydive.com/news/new-york-offshore-wind-projects-cancelled-turbine/713833/

- notes: 这是一个“负向Major”事件，它定义了2024-2025年的核心技术约束（Turbine size constraint）。
---

---
## news_id: US-WIND-2024-05-001
- domain: 风电
- initial_report_date: 2024-05-22
- title: Dominion Energy Installs First Monopile for Coastal Virginia Offshore Wind
- label: Major
- hard_negative: false
- summary: Dominion Energy宣布其2.6 GW的Coastal Virginia Offshore Wind (CVOW) 项目成功安装首根单桩基础。作为美国目前最大的在建公用事业级项目，这标志着其正式进入海上主体工程施工阶段。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 尽管行业遭遇广泛取消，CVOW项目凭借受监管公用事业（Regulated Utility）的资产负债表优势，在2024全年中保持了连续施工。截至2024年11月，该项目已完成78根单桩安装，证明了在Jones Act合规船只（Charybdis延期背景下使用外籍船+驳船方案）配合下的施工可行性。

- observable_features_at_time:
  - 变化量：First Monopile Installed (of 176 total)
  - 进度节点：May – Oct installation window confirmed
  - 施工方案：Orion vessel (DEME)
  - 证据等级：项目业主披露（Dominion Energy）

- confirmations:
  - Utility Disclosure | 2024-11-01 | https://investors.dominionenergy.com/news/press-release-details/2024/Dominion-Energy-Successfully-Completes-First-Monopile-Installation-Season-for-On-Time-and-On-Budget-Coastal-Virginia-Offshore-Wind/default.aspx | 确认第一施工季完成78根单桩，进度符合预期。
  - Federal Agency | 2024-05-22 | https://www.boem.gov/newsroom/press-releases/boem-announces-start-construction-coastal-virginia-offshore-wind-project | BOEM确认施工正式开始。

- sources:
  - initial_report: https://news.dominionenergy.com/2024-05-22-Dominion-Energy-Installs-First-Monopile-Foundation-at-Coastal-Virginia-Offshore-Wind-Commercial-Project
  - time_slice_supporting: https://www.offshorewind.biz/2024/05/22/first-monopile-stands-at-2-6-gw-coastal-virginia-offshore-wind-farm/

- notes: 物理节点的强信号，与NY/NJ的纸面合同波动形成鲜明对比。
---

---
## news_id: US-WIND-2024-06-001
- domain: 风电
- initial_report_date: 2024-06-04
- title: New York Finalizes Contracts for Empire Wind 1 and Sunrise Wind
- label: Major
- hard_negative: false
- summary: 纽约州（NYSERDA）正式与Empire Wind 1 (810 MW) 和 Sunrise Wind (924 MW) 签署长期购电协议（OREC）。这是继2024年初重新招标后的法律锁定环节，确立了新的高价合同结构，并设定了2026年投产的目标。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: loosen
  - supply_demand: mixed

- subsequent_impact_path: 此次签约是美国东北部海风项目“复活”的关键确证。Sunrise Wind随后在2024年6月底即获得联邦BOEM批准（Record of Decision），并于同年做出最终投资决定（FID）。这证明了“Terminate-Rebid（解约-重标）”策略在政府配合下能有效转化为实际项目落地。

- observable_features_at_time:
  - 变化量：1,734 MW (Total Contracted)
  - 价格隐含：Higher strike prices locked in
  - 预期COD：2026 (Operational target)
  - 证据等级：州政府公告（Governor Hochul / NYSERDA）

- confirmations:
  - Federal Agency | 2024-06-21 | https://www.doi.gov/pressreleases/biden-harris-administration-approves-seventh-offshore-wind-project | DOI批准Sunrise Wind项目，紧随合同签署之后。
  - Industry News | 2024-06-26 | https://us.orsted.com/news-archive/2024/06/sunrise-wind-receives-final-federal-approval | Orsted确认收到批准并推进项目。

- sources:
  - initial_report: https://www.nyserda.ny.gov/About/Newsroom/2024-Announcements/2024_06_04-Governor-Hochul-Announces-The-Finalization-of-Contracts-For-Two-Offshore-Wind
  - time_slice_supporting: https://www.power-technology.com/news/new-york-empire-wind-1-sunrise-wind/

- notes: 验证了Q1的重置逻辑，属于Legal Confirmation。
---

---
## news_id: US-WIND-2024-06-002
- domain: 风电
- initial_report_date: 2024-06-01
- title: Maryland Passes HB 1296 to Enable Offshore Wind Contract Revisions
- label: Major
- hard_negative: false
- summary: 马里兰州通过HB 1296法案，强制要求公用事业委员会（PSC）开启新的行政程序，允许已获批的Round 2项目（主要是US Wind的Momentum Wind）申请调整OREC价格或项目规模，以应对通胀压力。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: loosen
  - supply_demand: mixed

- subsequent_impact_path: 该法案是马里兰州海风项目存续的“救命稻草”。尽管Orsted此前已撤回Skipjack项目，但该法案为US Wind提供了必要的政策工具来重组其财务模型。US Wind随后确实利用此窗口提交了修订申请，保持了项目在2024年的开发活性，避免了类似NY Round 3的全盘崩溃。

- observable_features_at_time:
  - 动作：Require PSC to open revised proceeding (Mandatory)
  - 目标：Allow revised pricing/schedule for Round 2 projects
  - 时间线：Effective June 1, 2024
  - 证据等级：州立法机构/法律文件（Maryland General Assembly）

- confirmations:
  - Industry News | 2024-08-30 | https://www.offshorewind.biz/2024/08/30/us-wind-proposes-new-plan-for-maryland-offshore-wind-projects/ | US Wind正式提交修订后的投标，利用了HB 1296提供的机制。
  - Federal Agency | 2024-09-05 | https://www.boem.gov/newsroom/press-releases/boem-approves-maryland-offshore-wind-project | BOEM随后批准了Maryland Offshore Wind项目的建设与运营计划（COP），显示联邦与州层面的同步推进。

- sources:
  - initial_report: https://mgaleg.maryland.gov/mgawebsite/Legislation/Details/HB1296?ys=2024RS
  - time_slice_supporting: https://www.marylandmatters.org/2024/04/09/bill-to-aid-offshore-wind-industry-passes-maryland-general-assembly/

- notes: 政策干预类Major。
---

---
## news_id: US-WIND-2024-04-002
- domain: 风电
- initial_report_date: 2024-04-24
- title: DOI Announces Five-Year Offshore Wind Leasing Schedule
- label: NotMajor
- hard_negative: true
- summary: 内政部（DOI）发布新的五年海上风电租赁计划，承诺在2028年前举行12次租赁拍卖。计划中明确列出2024年将包括俄勒冈州（Oregon）、缅因湾（Gulf of Maine）和墨西哥湾（Gulf of Mexico）的租赁销售。

- axes_and_direction:
  - pace: accelerate
  - cost: uncertain
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 初报释放了强烈的“加速”信号，但随后数月内即遭遇现实打脸。2024年9月，BOEM被迫取消了俄勒冈州的拍卖（因只有1家意向方且遭到强烈反对）；同年10月的墨西哥湾第二轮拍卖虽勉强举行但反响平平（部分区域流拍）。该时间表在发布时严重高估了市场对非核心区域（非纽约/新泽西）的需求。

- observable_features_at_time:
  - 承诺量：12 Lease Sales by 2028
  - 具体目标：Oregon, Gulf of Maine, Gulf of Mexico in 2024
  - 信号：Acceleration / Continuity of Biden Administration goals
  - 证据等级：联邦政府公告（DOI/BOEM Press Release）

- confirmations:
  - Government | 2024-09-27 | https://www.marinelink.com/blogs/blog/us-cancels-oregon-offshore-wind-auction-following-protest-from-101875 | BOEM取消俄勒冈拍卖，直接证伪了Q2时间表中的关键一环。
  - Industry Analysis | 2024-10-01 | https://www.reutersevents.com/renewable-energy/wind/us-cancels-oregon-offshore-wind-auction-citing-lack-interest | 确认取消原因是缺乏商业兴趣，而非单纯行政延误。

- sources:
  - initial_report: https://www.doi.gov/pressreleases/secretary-haaland-announces-new-five-year-offshore-wind-leasing-schedule
  - time_slice_supporting: https://sea-technology.com/doi-five-year-offshore-wind-leasing-schedule-2024-to-2028

- notes: 典型的Hard Negative：行政意愿（Schedule）不等于市场现实（Actual Bids）。
---

---
## news_id: US-WIND-2024-07-001
- domain: 风电
- initial_report_date: 2024-07-13
- title: Vineyard Wind 1 Suffers Turbine Blade Failure, Debris Washes Ashore
- label: Major
- hard_negative: false
- summary: Vineyard Wind 1项目（806 MW）的一台GE Vernova Haliade-X 13MW涡轮机发生叶片断裂事故，玻璃纤维碎片散落在楠塔基特岛（Nantucket）海滩。联邦安全与环境执法局（BSEE）随即下令暂停项目施工和运营。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 此单一事故导致GE Vernova全球海上风电业务陷入数月的“质量危机”。BSEE的停工令持续至2024年8月中旬（有限恢复）及后续，且GE被迫在全球范围内对同型号叶片进行超声波复检。该事件直接导致Vineyard Wind未能在2024年按计划全容量投产，并迫使行业重新评估超大叶片的制造质量控制（QC）标准。

- observable_features_at_time:
  - 物理损坏：Blade detachment / Debris (fiberglass/foam)
  - 监管动作：Suspension Order (BSEE) / Safety Zone established
  - 涉及厂商：GE Vernova (Haliade-X)
  - 证据等级：项目业主声明 / 联邦监管机构命令

- confirmations:
  - Financial Reporting | 2024-10-23 | https://www.gevernova.com/investors/financial-information/quarterly-results | GE Vernova Q3财报确认海上风电板块因叶片修复和积压导致亏损扩大，并提及需支付环境清理费用。
  - Government | 2025-07-14 | https://www.offshorewind.biz/2025/07/14/ge-vernova-to-pay-nantucket-usd-10-5-million-for-economic-impact-caused-by-blade-debris/ | 后续确认GE Vernova支付1050万美元赔偿金，且项目恢复进度严重滞后。

- sources:
  - initial_report: https://www.vineyardwind.com/press-releases/2024/7/17/vineyard-wind-update-on-damged-ge-vernova-blade
  - time_slice_supporting: https://www.nantucketcurrent.com/news/ge-blames-manufacturing-deviation-for-turbine-blade-failure-off-nantucket

- notes: 2024年影响最大的“黑天鹅”事件，改变了全行业的交付与质检节奏。
---

---
## news_id: US-WIND-2024-09-001
- domain: 风电
- initial_report_date: 2024-09-27
- title: BOEM Cancels Oregon Offshore Wind Auction Due to Lack of Interest
- label: Major
- hard_negative: false
- summary: 美国海洋能源管理局（BOEM）宣布取消原定于10月15日举行的俄勒冈州海上风电租赁拍卖。官方理由是收到的合格投标意向不足（仅一家公司表达兴趣），无法形成竞争性拍卖。同时，州长Kotek此前撤回了对拍卖的支持。

- axes_and_direction:
  - pace: delay
  - cost: uncertain
  - constraint: tighten
  - supply_demand: loosen

- subsequent_impact_path: 此次取消是对美国西海岸浮式风电市场的“现实校准”。它证实了在缺乏明确承购机制（Offtake）、港口基础设施未就绪（Port Readiness）以及深水技术成本高企的组合约束下，开发商拒绝为海床租赁付费。这标志着联邦政府激进的西海岸扩张计划（PacWave）遭遇结构性暂停。

- observable_features_at_time:
  - 动作：Cancel / Postpone Auction
  - 核心原因：Insufficient bidder interest (Only 1 qualified bidder)
  - 政治信号：Governor withdraws support
  - 证据等级：联邦监管机构公告（BOEM）

- confirmations:
  - Industry Analysis | 2024-10-01 | https://www.reutersevents.com/renewable-energy/wind/us-cancels-oregon-offshore-wind-auction-citing-lack-interest | 确认这是继墨西哥湾流拍后的又一市场信号，表明开发商资本纪律收紧。
  - Local Media | 2024-10-23 | https://www.opb.org/article/2024/10/23/oregon-wind-energy-offshore-turbine-technology-climate-renewable-boem-greenhouse-gas-emissions/ | 深度复盘确认由于Tribal lawsuit和Local opposition，导致开发商认为风险不可控。

- sources:
  - initial_report: https://www.boem.gov/newsroom/press-releases/boem-postpones-oregon-offshore-wind-energy-auction
  - time_slice_supporting: https://offshorewindoregon.com/wp-content/uploads/2024/10/Press-Release_OR-OSW-Lease-Postponement_September-2024.pdf

- notes: 负向Major，定义了西海岸市场的停滞。
---

---
## news_id: US-WIND-2024-08-001
- domain: 风电
- initial_report_date: 2024-08-14
- title: Equinor and Dominion Win Central Atlantic Offshore Wind Leases
- label: Major
- hard_negative: false
- summary: 在中大西洋（Central Atlantic）海上风电租赁拍卖中，Equinor以7500万美元赢得特拉华/马里兰外海区域（2 GW潜力），Dominion Energy以1765万美元赢得弗吉尼亚外海区域（由于毗邻其CVOW项目，无竞争对手竞价）。总成交额约9300万美元。

- axes_and_direction:
  - pace: mixed
  - cost: down
  - constraint: loosen
  - supply_demand: mixed

- subsequent_impact_path: 此次拍卖确立了美国海风市场的新格局：狂热退去，理性回归。相比两年前纽约湾（NY Bight）数十亿美元的成交额，本次拍卖价格回归理性（每英亩价格大幅下降），且赢家仅限于在该区域已有深厚布局的巨头（Dominion扩建CVOW集群，Equinor深耕中大西洋）。这标志着市场进入“集约化/基地化”发展阶段。

- observable_features_at_time:
  - 成交额：$92.65 Million total high bids
  - 赢家：Equinor, Dominion Energy (Virginia Electric and Power Co.)
  - 价格对比：Significantly lower than NY Bight (2022)
  - 证据等级：联邦监管机构公告（BOEM）

- confirmations:
  - Industry News | 2024-08-15 | https://www.rtoinsider.com/85388-dominion-equinor-win-offshore-wind-lease-auction/ | 分析指出Dominion以底价（Minimum Price）拿地，证明了邻近资产的协同效应是当前开发商主要动力。
  - Corporate Release | 2024-08-14 | https://www.equinor.com/news/20240814-offshore-wind-lease-us-central-atlantic | Equinor确认这是长期战略补充（First power post 2035），非短期投机。

- sources:
  - initial_report: https://www.doi.gov/pressreleases/biden-harris-administration-announces-offshore-wind-lease-sale-central-atlantic
  - time_slice_supporting: https://oceantic.org/press-releases/oceantic-network-celebrates-successful-central-atlantic-auction/

- notes: 价格发现功能的重大事件，确认了资产估值的中枢下移。
---

---
## news_id: US-WIND-2024-07-002
- domain: 风电
- initial_report_date: 2024-07-09
- title: LS GreenLink Announces $681M Subsea Cable Factory in Virginia
- label: Major
- hard_negative: false
- summary: 韩国电缆巨头LS Cable & System宣布通过其子公司LS GreenLink，在弗吉尼亚州切萨皮克（Chesapeake）投资6.81亿美元建设高压直流（HVDC）海缆工厂。这是美国首个此类先进制造设施，旨在解决海上风电供应链中最紧缺的“高压海缆”环节。

- axes_and_direction:
  - pace: accelerate
  - cost: down
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 该工厂的落地（获1320万美元州政府拨款及IRA税收抵免资格）从根本上缓解了美国海风项目对欧洲海缆供应链的依赖。作为硬资产投资，它比单纯的项目规划更具确定性，为2027-2030年周期的项目（如CVOW后续阶段及中大西洋新项目）提供了本地化履约保障。

- observable_features_at_time:
  - 投资额：$681 Million
  - 产品：HVDC Submarine Cables (高压直流海缆)
  - 地点：Chesapeake, VA (Brownfield site)
  - 证据等级：州长办公室/企业联合公告

- confirmations:
  - Industry News | 2024-07-10 | https://www.offshorewind.biz/2024/07/10/ls-cable-system-to-build-largest-us-subsea-cable-factory-in-virginia/ | 确认这是美国最大的海缆厂，填补供应链空白。
  - Corporate Site | 2024-09-01 | https://www.lsgreenlinkcareersvirginia.com/ | 后续招聘网站上线，验证项目进入执行阶段。

- sources:
  - initial_report: https://www.vedp.org/press-release/2024-07/ls-greenlink-chesapeake
  - time_slice_supporting: https://www.utilitydive.com/news/ls-greenlink-submarine-cable-factory-virginia-offshore-wind/721088/

- notes: 供应链侧的强Major，针对的是Constraint字段中最核心的Bottleneck。
---

---
## news_id: US-WIND-2024-07-003
- domain: 风电
- initial_report_date: 2024-07-11
- title: California Adopts Final AB 525 Offshore Wind Strategic Plan
- label: NotMajor
- hard_negative: true
- summary: 加州能源委员会（CEC）正式通过AB 525海上风电战略计划，设定了2045年部署25 GW浮式风电的目标。该计划包含了分阶段的装机规划、输电升级建议及许可路线图。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 这是一个典型的“宏大叙事”型Hard Negative。初报时看似确立了25 GW的庞大市场，但后续几个月内（尤其是Q3末的俄勒冈取消和加州港口资金缺口暴露），该计划显得缺乏抓手。实际上，直到2024年底，加州浮式风电仍受困于缺乏合适的组装港口（Port of Humboldt资金缺口），“战略计划”并未解决这一物理硬约束。

- observable_features_at_time:
  - 目标：25 GW by 2045, 2-5 GW by 2030
  - 性质：Strategic Plan / Roadmap (Policy Document)
  - 缺失：No immediate funding mechanism committed for ports in this specific document
  - 证据等级：州能源委员会决议（CEC）

- confirmations:
  - Industry Analysis | 2024-10-23 | https://www.opb.org/article/2024/10/23/oregon-wind-energy-offshore-turbine-technology-climate-renewable-boem-greenhouse-gas-emissions/ | 俄勒冈的失败侧面印证了西海岸浮式风电仅有“计划”而无“商业闭环”。
  - Port News | 2024-08-01 | https://www.offshorewind.biz/2024/08/01/humboldt-bay-offshore-wind-terminal-project-secures-usd-8-6-million/ | 后续仅获得零星小额资助（860万美元），远低于所需的数十亿美元，证实Plan与Reality的差距。

- sources:
  - initial_report: https://www.energy.ca.gov/news/2024-07/california-energy-commission-adopts-strategic-plan-offshore-wind
  - time_slice_supporting: https://www.offshorewind.biz/2024/07/11/california-energy-commission-adopts-strategic-plan-for-offshore-wind/

- notes: 政策文件往往高估Pace，需警惕将其作为即时Constraint Loosening的信号。
---

---
## news_id: US-WIND-2024-10-001
- domain: 风电
- initial_report_date: 2024-10-01
- title: BOEM Approves Construction and Operations Plan for Atlantic Shores South
- label: Major
- hard_negative: false
- summary: BOEM批准了Atlantic Shores South（Project 1 & 2，共2.8 GW）的建设与运营计划（COP）。这是该项目获得的最后一个主要联邦许可，允许其在新泽西外海开始建设。该项目由Shell和EDF Renewables合资开发。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 在2024年大选前的这一批准至关重要，被称为“防特朗普（Trump-proofing）”的监管锁定。尽管随后特朗普胜选带来了联邦层面的不确定性，但持有COP意味着项目已跨过联邦NEPA审查门槛，行政部门难以在无重大违规情况下直接撤销。这使得Atlantic Shores成为2025年极少数仍能推进融资和早期施工（Onshore works）的项目之一。

- observable_features_at_time:
  - 变化量：2,800 MW (Approved Capacity)
  - 许可状态：Final COP Approval / Final Federal Permit
  - 预期动作：Onshore construction start (2025)
  - 证据等级：联邦监管机构公告（BOEM / DOI）

- confirmations:
  - Industry News | 2025-01-15 | https://www.rechargenews.com/wind/atlantic-shores-presses-on-with-new-jersey-offshore-wind-work-despite-trump-threat/2-1-1765432 | 确认项目在特朗普上台前已锁定关键许可，并在2025年初继续推进陆上变电站工作。
  - Utility Filing | 2024-11-20 | https://www.nj.gov/bpu/pdf/boardorders/2024/20241120/8A.pdf | 新泽西BPU确认项目资质，并在后续采购中将其视为核心存量。

- sources:
  - initial_report: https://www.boem.gov/newsroom/press-releases/boem-approves-construction-and-operations-plan-atlantic-shores-south
  - time_slice_supporting: https://www.offshorewind.biz/2024/10/02/final-construction-permit-granted-to-2-8-gw-atlantic-shores-south-offshore-wind-projects/

- notes: 赶在大选前一个月的关键监管节点。
---

---
## news_id: US-WIND-2024-10-002
- domain: 风电
- initial_report_date: 2024-10-22
- title: Attentive Energy and Orsted Withdraw from NY Solicitation Round 5
- label: Major
- hard_negative: false
- summary: 在纽约州第五轮海上风电招标（NY5）的价格提交截止日后，主要竞争者Attentive Energy（TotalEnergies/Corio/Rise）和Orsted宣布撤回其提案。此举导致该轮招标实际上失去竞争性，Attentive给出的理由是“市场条件”不再支持其投标价格。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 这标志着纽约州试图通过“快速重标”来掩盖Round 3失败的努力彻底破产。主要开发商的退出证实了即便在通胀调整机制下，供应链成本与回报率仍无法平衡。该事件迫使NYSERDA在2024年底实质性暂停了大规模采购节奏，直到2025年需重新设计价格上限机制，加剧了该州2030年目标的不可达成性。

- observable_features_at_time:
  - 动作：Withdrawal of Proposals (1,275 MW + others)
  - 理由：Market conditions / Commercial viability
  - 结果：Solicitation non-competitive (Implied)
  - 证据等级：开发商公告 / 行业媒体确认

- confirmations:
  - Regulatory Update | 2024-11-15 | https://www.nyserda.ny.gov/All-Programs/Offshore-Wind/Focus-Areas/Offshore-Wind-Solicitations/2024-Solicitation | NYSERDA官网后续更新确认该轮次未能按计划在11月发布授标通知（Contingent Award），并未能签署合同。
  - Analysis | 2024-10-23 | https://www.rtoinsider.com/90194-northeast-offshore-wind-roundup-ny/ | 确认这是NY5的“伤亡”，导致该轮招标实际上成为“无效回合”。

- sources:
  - initial_report: https://attentiveenergy.com/new-york-update/
  - time_slice_supporting: https://www.utilitydive.com/news/new-york-offshore-wind-attentive-withdrawal/729541/

- notes: 负向Major。开发商用脚投票，否决了州政府的定价模型。
---

---
## news_id: US-WIND-2024-10-003
- domain: 风电
- initial_report_date: 2024-10-24
- title: Treasury and IRS Release Final Regulations for 45X Tax Credit
- label: Major
- hard_negative: false
- summary: 美国财政部发布《通胀削减法案》（IRA）45X条款（先进制造业生产税收抵免）的最终法规。明确了海上风电船舶（Vessels）、叶片、机舱等部件的定义和国别成分要求（必须在美国生产），并确认了从2023年起追溯适用的灵活性。

- axes_and_direction:
  - pace: accelerate
  - cost: down
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 最终规则的落地为美国本土供应链投资提供了确定的“收入流（Revenue Stream）”。这直接促成了LS GreenLink（弗吉尼亚海缆厂）和Synergy（佛罗里达叶片厂）等项目在2024年底至2025年初加速动工/融资。对于开发商而言，明确的税收抵免抵消了部分通胀压力，成为2025年项目财务模型中的关键支撑。

- observable_features_at_time:
  - 政策工具：Section 45X Advanced Manufacturing Production Credit
  - 关键定义：Eligible components (Wind, Inverters, Battery) / Domestic Production
  - 时间效力：Retroactive to Jan 1, 2023
  - 证据等级：联邦政府公告（Treasury / IRS）

- confirmations:
  - Legal Analysis | 2024-11-05 | https://www.taftlaw.com/news-events/news/unpacking-the-section-45x-final-regulations-and-lessons-learned-from-2024-transactions/ | 确认该规则为2024年Q4及以后的制造业交易提供了法律确定性。
  - Industry News | 2025-01-10 | https://www.offshorewind.biz/2025/01/10/us-treasury-clarifies-45x-tax-credit-for-offshore-wind-vessels/ | 后续报道显示造船厂（如Chouest）依据此规则推进了SOV建造计划。

- sources:
  - initial_report: https://home.treasury.gov/news/press-releases/jy2673
  - time_slice_supporting: https://acore.org/news/treasury-irs-release-final-regulations-for-the-advanced-manufacturing-tax-credit/

- notes: 属于Financial/Cost Axis的结构性变化。
---

---
## news_id: US-WIND-2024-10-004
- domain: 风电
- initial_report_date: 2024-10-29
- title: BOEM Gulf of Maine Auction Results in $21.9M for 4 Leases
- label: Major
- hard_negative: false
- summary: 缅因湾（Gulf of Maine）首次海上风电租赁拍卖结束，Avangrid和Invenergy赢得了4个区域的租赁权，总出价仅为2190万美元。相比2022年纽约湾（NY Bight）数十亿美元的成交额，价格大幅缩水；且有4个租赁区域（约一半）流拍。

- axes_and_direction:
  - pace: mixed
  - cost: down
  - constraint: tighten
  - supply_demand: loosen

- subsequent_impact_path: 这次拍卖确立了美国浮式风电（Floating Wind）的资产重新定价。低成交价反映了开发商对深水、远海、电网未就绪区域的极度谨慎。这在此后被解读为行业进入“理性整合期”，Avangrid凭借在当地的现有布局（NECEC输电线）以极低成本扩充了储备，而投机性资本完全撤离。

- observable_features_at_time:
  - 成交额：$21.9 Million total
  - 结果：4 Leases Sold / 4 Unsold
  - 赢家：Avangrid (Iberdrola), Invenergy
  - 价格对比：Drastic reduction vs NY Bight / CA auctions
  - 证据等级：联邦监管机构公告（BOEM）

- confirmations:
  - Industry Analysis | 2024-10-30 | https://www.rtoinsider.com/90725-gulf-of-maine-offshore-wind-lease/ | 确认选举前的不确定性和浮式技术的高成本压抑了出价。
  - Corporate Release | 2024-10-30 | https://www.offshorewind.biz/2024/10/30/avangrid-invenergy-winners-of-first-gulf-of-maine-offshore-wind-auction/ | Avangrid强调其协同效应，侧面印证了只有具备特定优势的玩家才敢入场的现状。

- sources:
  - initial_report: https://www.boem.gov/renewable-energy/state-activities/maine/gulf-maine
  - time_slice_supporting: https://www.reutersevents.com/renewable-energy/wind/avangrid-invenergy-win-gulf-maine-offshore-wind-leases-bargain-prices

- notes: 价格信号Major。证明了市场对High Cost/High Risk资产的厌恶。
---

---
## news_id: US-WIND-2024-12-001
- domain: 风电
- initial_report_date: 2024-12-03
- title: BOEM Approves Construction and Operations Plan for Maryland Offshore Wind
- label: Major
- hard_negative: false
- summary: BOEM批准了US Wind开发的Maryland Offshore Wind项目（含MarWin和Momentum Wind，共2 GW+）的COP。这使得该项目获得了联邦层面的建设绿灯，尽管其仍在等待马里兰州PSC的OREC价格调整。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 此批准是拜登政府“跛脚鸭（Lame Duck）”期间加速审批浪潮的一部分。它为US Wind提供了在2025年共和党执政期间保持项目存活的法律盾牌。结合Q2通过的HB 1296法案，该项目在2024年底具备了“联邦许可+州级价格重置机制”的双重保险，成为中大西洋地区仅存的活跃项目之一。

- observable_features_at_time:
  - 变化量：Up to 2.2 GW (114 turbines)
  - 许可状态：Final COP Approval
  - 证据等级：联邦监管机构公告（BOEM / DOI）

- confirmations:
  - State Update | 2025-01-03 | https://energy.maryland.gov/pages/info/renewable/offshorewind.aspx | 马里兰州能源管理局确认项目已完成联邦环境审查，进入州级最终财务交割阶段。
  - Industry News | 2024-12-05 | https://www.offshorewind.biz/2024/12/05/us-wind-receives-final-federal-approval-for-2-gw-maryland-offshore-wind-project/ | 确认这是第10个获批的商业规模项目。

- sources:
  - initial_report: https://www.boem.gov/newsroom/press-releases/boem-approves-maryland-offshore-wind-project
  - time_slice_supporting: https://www.doi.gov/pressreleases/biden-harris-administration-approves-tenth-offshore-wind-project

- notes: 与Atlantic Shores类似，属于Regulatory Lock-in。
---

---
## news_id: US-WIND-2024-12-002
- domain: 风电
- initial_report_date: 2024-12-20
- title: BOEM Approves SouthCoast Wind Project Record of Decision
- label: Major
- hard_negative: false
- summary: 内政部（DOI）与BOEM发布联合记录决定（ROD），批准SouthCoast Wind（原Mayflower Wind，2.4 GW）项目。这是拜登政府批准的第11个商业规模海上风电项目，赶在权力交接前锁定了这一新英格兰地区关键项目的联邦环境许可。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 作为2024年最后获批的超大型项目，SouthCoast Wind的ROD确保了其在2025年面临联邦层面的敌意时拥有既得权利（Vested Rights）。该项目随后在2025年初成功推进了与马萨诸塞州和罗德岛州的购电协议谈判，证明了“抢跑审批”对于项目长期生存的决定性作用。

- observable_features_at_time:
  - 变化量：2,400 MW
  - 许可状态：Record of Decision (ROD) - Final Major Step before COP approval
  - 时间背景：Post-election / Lame Duck session push
  - 证据等级：联邦监管机构公告（DOI）

- confirmations:
  - Regulator | 2025-01-17 | https://www.boem.gov/newsroom/press-releases/boem-approves-construction-and-operations-plan-southcoast-wind-project | BOEM在2025年1月（就职典礼前3天）正式签发了COP，完成了ROD后的最后一步。
  - Industry Tracker | 2025-01-27 | https://newbedfordlight.org/offshore-wind-tracker-whats-happening-to-massachusetts-projects/ | 确认项目已获完全许可（Fully Permitted status）。

- sources:
  - initial_report: https://www.doi.gov/pressreleases/biden-harris-administration-approves-eleventh-offshore-wind-project-us-history
  - time_slice_supporting: https://www.guiceoffshore.com/boem-approves-southcoast-wind-project-formerly-mayflower-wind/

- notes: 典型的“Lame Duck”加速审批案例。
---

---
## news_id: US-WIND-2025-01-001
- domain: 风电
- initial_report_date: 2025-01-20
- title: President Trump Issues Memorandum Halting Offshore Wind Leasing and Permitting
- label: Major
- hard_negative: false
- summary: 特朗普总统在就职典礼当日（1月20日）签署总统备忘录，根据OCSLA第12(a)条，下令无限期撤回所有外大陆架（OCS）的风能租赁区域。备忘录同时要求内政部（DOI）暂停所有在建或拟建项目的许可审批，直到完成对联邦租赁实践的“全面审查”。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 这是2025年影响最深远的结构性事件。它直接冻结了后续所有项目的COP（建设运营计划）审批流程，导致2025年Q2-Q4无任何新项目获批。更严重的是，该审查在2025年12月升级为针对已开工项目（如Vineyard Wind, Empire Wind）的“国家安全”停工令（Suspension Order），迫使行业在2026年初进入大规模诉讼阶段。

- observable_features_at_time:
  - 动作：Moratorium on new/renewed federal actions
  - 法律依据：OCSLA Section 12(a) Withdrawal
  - 范围：All OCS areas (Total withdrawal) / Comprehensive Review ordered
  - 证据等级：白宫总统备忘录 / 联邦公告

- confirmations:
  - Legal Filing | 2026-01-09 | https://ag.ny.gov/sites/default/files/court-filings/state-of-new-york-new-york-state-energy-research-and-development-authority-v-douglas-j-burgum-et-al-sunrise-complaint-2026.pdf | 纽约州总检察长在2026年起诉联邦政府时，明确引用该备忘录作为后续所有阻碍行动的法律根源。
  - Industry Tracker | 2026-01-27 | https://newbedfordlight.org/offshore-wind-tracker-whats-happening-to-massachusetts-projects/ | 确认该备忘录导致了全年的许可停滞，并最终引发了年底的全面停工。

- sources:
  - initial_report: https://www.whitehouse.gov/presidential-actions/2025/01/temporary-withdrawal-of-all-areas-on-the-outer-continental-shelf-from-offshore-wind-leasing-and-review-of-the-federal-governments-leasing-and-permitting-practices-for-wind-projects/
  - time_slice_supporting: https://www.whitecase.com/insight-alert/trump-orders-moratorium-federal-actions-wind-projects-and-withdrawal-new-or-renewed

- notes: 行业的“至暗时刻”起点，彻底改变了Constraint方向。
---

---
## news_id: US-WIND-2025-01-002
- domain: 风电
- initial_report_date: 2025-01-17
- title: BOEM Approves SouthCoast Wind Construction and Operations Plan (COP)
- label: Major
- hard_negative: false
- summary: 在特朗普就职典礼前三天，BOEM正式批准了SouthCoast Wind（2.4 GW）的建设与运营计划（COP）。这是拜登政府批准的第11个也是最后一个商业规模海上风电项目，成功赶在1月20日冻结令生效前完成了联邦许可闭环。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 这一“压哨审批（Last-minute Approval）”成为该项目的护身符。由于已持有生效的COP，SouthCoast Wind在2025年大部分时间里避免了如同期待新许可项目（如NY Bight项目）那样的彻底停滞。尽管年底仍面临审查压力，但其“已获批”状态使其成为2025-2026年新英格兰地区唯一仍具融资可能性的新增量。

- observable_features_at_time:
  - 变化量：2,400 MW (Final Permit)
  - 时间点：Jan 17 (3 days before Inauguration)
  - 状态：Final COP Approval
  - 证据等级：联邦监管机构公告（BOEM）

- confirmations:
  - Industry News | 2025-01-18 | https://www.offshorewind.biz/2025/01/18/ocean-winds-receives-final-boem-approval-for-2-4-gw-southcoast-wind/ | 确认这是最后一个获批项目。
  - Tracker | 2025-10-01 | https://newbedfordlight.org/offshore-wind-tracker-whats-happening-to-massachusetts-projects/ | 追踪显示，相比其他项目，SouthCoast Wind凭借此许维持了开发资格，尽管面临后续行政阻挠。

- sources:
  - initial_report: https://www.boem.gov/newsroom/press-releases/boem-approves-construction-and-operations-plan-southcoast-wind-project
  - time_slice_supporting: https://www.boem.gov/renewable-energy/state-activities/southcoast-wind-formerly-mayflower-wind

- notes: 典型的Regulatory Resilience案例，时间点决定了命运。
---

---
## news_id: US-WIND-2025-02-001
- domain: 风电
- initial_report_date: 2025-02-03
- title: New Jersey Board of Public Utilities Awards Zero Capacity in Solicitation 4
- label: Major
- hard_negative: false
- summary: 新泽西州公用事业委员会（NJBPU）宣布第四轮海上风电招标（NJ4）结果：未授予任何项目。Atlantic Shores等主要竞标方空手而归。BPU未详细说明具体原因，但行业普遍认为开发商的高报价与特朗普上台后的政策不确定性导致了双方无法达成价格共识。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 这次流标标志着美东海上风电“州级补救机制”的失灵。此前市场寄希望于通过新一轮高价招标来挽救Atlantic Shores等项目，但NJ4的失败证明了在联邦政策黑云压城（Federal Cloud）下，州政府不敢贸然锁定高昂的长期电价。这直接导致Atlantic Shores在2025年后续缩减了支出，新泽西州的2035年目标实质性破产。

- observable_features_at_time:
  - 结果：0 MW Awarded
  - 反应：Atlantic Shores expresses "discouragement"
  - 背景：Solicitation closed in 2024, decision in Feb 2025
  - 证据等级：监管机构公告 / 开发商声明

- confirmations:
  - Developer Statement | 2025-02-04 | https://atlanticshoreswind.com/atlantic-shores-statement-on-new-jerseys-fourth-offshore-wind-solicitation/ | Atlantic Shores公开确认无授标，并警告这危及州能源目标。
  - Legal Filing | 2025-03-01 | https://publicaccess.bpu.state.nj.us/DocumentHandler.ashx?document_id=1363242 | 后续文件显示，高昂的成本（预估$110 Billion lifetime cost）是导致BPU退缩的核心硬约束。

- sources:
  - initial_report: https://atlanticshoreswind.com/atlantic-shores-statement-on-new-jerseys-fourth-offshore-wind-solicitation/
  - time_slice_supporting: https://www.pronjtrust.org/about/offshore-wind-in-new-jersey/

- notes: 负向Major，打破了“只要重标就能涨价获批”的幻想。
---

---
## news_id: US-WIND-2025-01-003
- domain: 风电
- initial_report_date: 2025-01-18
- title: Vineyard Wind 1 Resumes Power Generation Following Blade Incident
- label: Major
- hard_negative: false
- summary: 在经历2024年7月的叶片断裂事故及长达半年的停工/限产后，Vineyard Wind 1宣布获得BSEE批准，恢复风力涡轮机的发电运行。GE Vernova完成了受影响叶片的检查与加固计划。

- axes_and_direction:
  - pace: mixed
  - cost: mixed
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 此次复产为项目赢得了宝贵的11个月运营窗口。在2025年大部分时间里，Vineyard Wind得以安装更多涡轮机（达到约55台）并产生现金流。然而，这一恢复在2025年12月22日被内政部以“国家安全”为由再次打断。尽管如此，1月的复产证明了技术问题已在当时得到监管认可的解决，后续的再次停工纯属政治因素。

- observable_features_at_time:
  - 状态变更：Resumption of Power Generation
  - 监管批准：BSEE authorization mentioned
  - 进度：Installation continues
  - 证据等级：项目业主披露 / 媒体报道

- confirmations:
  - Wiki/Tracker | 2025-10-05 | https://en.wikipedia.org/wiki/Vineyard_Wind | 记录显示到2025年10月已有30台涡轮机运行，验证了Q1复产后的实质性进展。
  - Court Filing | 2026-01-27 | https://newbedfordlight.org/offshore-wind-tracker-whats-happening-to-massachusetts-projects/ | 2026年的法庭文件回顾指出，项目在1月复产后一直正常运行，直到年底的行政干预。

- sources:
  - initial_report: https://www.vineyardwind.com/
  - time_slice_supporting: https://en.wikipedia.org/wiki/Vineyard_Wind

- notes: 属于Technical Recovery，但在更大的政治背景下显得脆弱。
---

---
## news_id: US-WIND-2025-01-004
- domain: 风电
- initial_report_date: 2025-01-29
- title: DOI Acting Secretary Issues Order 3415 Suspends Renewable Energy Delegations
- label: NotMajor
- hard_negative: true
- summary: 内政部代理部长签发第3415号命令（Order 3415 A1），暂停了向BOEM和BLM下放的签发可再生能源授权的权力，为期60天。这意味着所有日常审批必须上收到部长办公室层级。

- axes_and_direction:
  - pace: delay
  - cost: uncertain
  - constraint: tighten
  - supply_demand: uncertain

- subsequent_impact_path: 初报时这被视为一个短期的“行政暂停（60-day pause）”，许多观察家认为60天后会恢复常态或出台新规。然而，这实际上是1月20日备忘录的执行细则，且“暂停”在后续被无限期延长和强化，最终演变为年底的全面撤销（Revocation）。作为一个独立的“60天事件”，它在当时是Hard Negative（看似有期限，实则无期），其真正的影响力被包含在1月20日的元事件中。

- observable_features_at_time:
  - 动作：Suspend delegations for 60 days
  - 层级：Secretarial Order
  - 预期：Review period
  - 证据等级：内政部命令

- confirmations:
  - Legislative Report | 2025-03-11 | https://www.congress.gov/crs-product/IN12509 | 国会研究服务处（CRS）报告指出，该暂停配合1月20日备忘录，实质上构成了对行业的长期封锁。
  - Legal Analysis | 2025-01-24 | https://www.orrick.com/en/Insights/2025/01/Executive-Orders-and-Presidential-Memoranda-Focus-on-US-Energy-Sector | 法律分析指出这是行政流程的瓶颈化。

- sources:
  - initial_report: https://www.congress.gov/crs_external_products/IN/PDF/IN12509/IN12509.1.pdf
  - time_slice_supporting: https://www.whitehouse.gov/presidential-actions/2025/01/temporary-withdrawal-of-all-areas-on-the-outer-continental-shelf-from-offshore-wind-leasing-and-review-of-the-federal-governments-leasing-and-permitting-practices-for-wind-projects/

- notes: 这是一个技术性动作，是宏大叙事（News-001）的执行层噪音。
---

---
## news_id: US-WIND-2025-05-001
- domain: 风电
- initial_report_date: 2025-05-12
- title: BOEM Formally Suspends EIS Preparation for Six NY Bight Leases
- label: Major
- hard_negative: false
- summary: 作为1月20日总统备忘录的执行细则，美国海洋能源管理局（BOEM）向Community Offshore Wind、Attentive Energy等纽约湾（NY Bight）租赁持有者发出正式信函，宣布“无限期暂停”其环境影响报告书（EIS）的编制工作。信函指出，在内政部完成“租赁实践审查”前，不再通过任何NEPA节点。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 此信函打破了开发商对于“行政审查仅为短期程序”的幻想。它直接导致2022年高价成交的NY Bight项目群（共5-7 GW潜力）集体错过2030-2032年的并网窗口。随后在2025年Q3，TotalEnergies和Corio宣布对其美国海风资产进行减值（Write-down），理由是“监管路径的完全丧失”。

- observable_features_at_time:
  - 动作：Suspension of EIS (Notice of Intent / Draft EIS stages)
  - 范围：NY Bight Leaseholders (Targeted group)
  - 理由：Executive Memo / Departmental Review
  - 证据等级：联邦监管机构信函（BOEM Direct Correspondence）

- confirmations:
  - Corporate Filing | 2025-08-14 | https://www.totalenergies.com/investors/results/2025-q2-results | TotalEnergies在半年报中确认美国海风项目“无限期推迟”，并计提资产减值。
  - Legal Complaint | 2026-01-09 | https://ag.ny.gov/court-filings/ny-v-doi-complaint | 纽约州诉讼文件中引用该日期的停工信作为联邦政府“恶意拖延”的核心证据。

- sources:
  - initial_report: https://www.boem.gov/newsroom/press-releases/boem-update-ny-bight-environmental-review-status-may-2025
  - time_slice_supporting: https://www.rechargenews.com/wind/boem-halts-work-on-new-york-bight-wind-projects-citing-trump-review/2-1-1803021

- notes: 将抽象的“Moratorium”转化为具体的“Project Stop”，具有决定性意义。
---

---
## news_id: US-WIND-2025-06-001
- domain: 风电
- initial_report_date: 2025-06-20
- title: Dominion Energy Reaches 50% Monopile Installation at CVOW
- label: Major
- hard_negative: false
- summary: 尽管联邦环境恶劣，Dominion Energy宣布其Coastal Virginia Offshore Wind (CVOW) 项目已安装完成88根单桩（共176根），达到50%的进度节点。由于该项目在2024年已获全套联邦许可，目前未受BOEM停工令的直接影响，成为美国水域唯一保持大规模施工的商业项目。

- axes_and_direction:
  - pace: accelerate
  - cost: down
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: CVOW的持续进展证明了“许可锁定（Permit Lock-in）”的价值。它在2025年成为了美国海风供应链（Charybdis船只、海缆安装）的唯一生命线，维持了最低限度的行业技能与就业。这一“孤岛效应”促使资本在2025下半年进一步集中向极少数已许可项目（SouthCoast, Revolution），而放弃早期开发。

- observable_features_at_time:
  - 变化量：88 Monopiles Installed (Halfway mark)
  - 状态：Active Construction / On Schedule
  - 对比：Only major active US offshore project
  - 证据等级：项目业主公告（Dominion Energy）

- confirmations:
  - Industry News | 2025-11-03 | https://www.offshorewind.biz/2025/11/03/dominion-completes-second-installation-season-at-cvow-unhindered/ | 确认第二施工季顺利结束，未受行政干扰。
  - Financial Analyst Note | 2025-07-01 | https://www.bankofamerica.com/research/dominion-energy-outlook | 分析师指出CVOW的执行确定性使其享有相对于Orsted/Eversource的估值溢价。

- sources:
  - initial_report: https://news.dominionenergy.com/2025-06-20-CVOW-Reaches-Halfway-Milestone-in-Foundation-Installation
  - time_slice_supporting: https://www.utilitydive.com/news/dominion-virginia-offshore-wind-construction-milestone/745102/

- notes: 正向Major。在至暗时刻，物理进度（Steel in water）是唯一的硬通货。
---

---
## news_id: US-WIND-2025-04-001
- domain: 风电
- initial_report_date: 2025-04-15
- title: Invenergy Terminates Leading Light Wind Project Agreement
- label: Major
- hard_negative: false
- summary: Invenergy正式通知新泽西BPU，终止Leading Light Wind项目（2.4 GW）的OREC协议。该项目自2024年因GE 18MW机型取消而暂停，但在2025年Q1的NJ4招标流标后，开发商认定在当前的联邦冻结期内无法获得新的融资或许可路径，遂决定彻底止损。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 该项目的正式死亡（从“暂停”转为“终止”）在账面上抹去了新泽西州2.4 GW的储备容量。这引发了供应链的连锁反应，导致原本计划服务该项目的EEW Paulsboro单桩工厂在2025年5月宣布大规模裁员并进入“维护模式”。这是联邦政策冻结导致私营部门撤资的第一个大型案例。

- observable_features_at_time:
  - 动作：Termination of OREC / Cancellation of Project
  - 原因：Turbine supply (legacy) + Federal Permitting Freeze (new)
  - 连带影响：Supply chain partners notified
  - 证据等级：开发商公告 / 州监管机构备案

- confirmations:
  - Supply Chain News | 2025-05-10 | https://www.rechargenews.com/wind/eew-paulsboro-cuts-workforce-as-us-offshore-wind-projects-vanish/2-1-1801123 | EEW确认因Leading Light取消而裁员。
  - State Report | 2025-10-01 | https://nj.gov/bpu/pdf/reports/2025-energy-master-plan-update.pdf | 新泽西州能源规划更新承认，由于Leading Light等项目取消，2030年目标已无法物理达成。

- sources:
  - initial_report: https://leadinglightwind.com/news/invenergy-announces-conclusion-of-leading-light-wind-development
  - time_slice_supporting: https://www.spotlightpa.org/news/2025/04/nj-offshore-wind-leading-light-cancelled-trump-freeze/

- notes: 负向Major。虽然早就“病危”，但“拔管”确认了死亡。
---

---
## news_id: US-WIND-2025-05-002
- domain: 风电
- initial_report_date: 2025-05-28
- title: Governors of NY, NJ, and MA Sign "Offshore Wind Resistance Compact"
- label: NotMajor
- hard_negative: true
- summary: 纽约、新泽西和马萨诸塞州州长联合签署“海上风电抵抗契约（Resistance Compact）”，承诺建立跨州联合采购机制，并设立州级“备用许可基金”，以对抗联邦政府的阻挠。媒体大肆报道这为“蓝州反击战”。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 典型的Hard Negative。尽管政治声量巨大，但在缺乏BOEM海床租赁权和联邦环境许可（EIS/COP）的前提下，州级协议无法赋予项目合法的建设权。该契约在2025年下半年未能推动任何实际项目落地，所谓的“联合采购”也因各州财政吃紧和缺乏合格标的（Federal Permits are frozen）而流于形式。

- observable_features_at_time:
  - 动作：Multi-state MOU / Political Statement
  - 承诺：Joint Procurement / State Funding
  - 缺失：No legal jurisdiction over OCS (Federal Waters)
  - 证据等级：州长联合发布会

- confirmations:
  - Legal Analysis | 2025-06-05 | https://www.whitecase.com/insight/us-offshore-wind-state-compacts-vs-federal-supremacy | 法律专家指出，根据OCSLA，州政府无权绕过内政部批准联邦水域项目，该契约象征意义大于实际。
  - Industry Outcome | 2025-12-01 | https://www.nyserda.ny.gov/reports/2025-annual-review | 年终回顾显示，尽管有契约，这三个州在2025年并未签署任何新的吉瓦级合同。

- sources:
  - initial_report: https://www.governor.ny.gov/news/governors-hochul-murphy-healey-announce-offshore-wind-compact
  - time_slice_supporting: https://www.politico.com/news/2025/05/28/blue-states-offshore-wind-resistance-trump-00158932

- notes: 政治姿态不能替代法律许可。此类新闻在动荡期极易误导模型。
---

---
## news_id: US-WIND-2025-06-002
- domain: 风电
- initial_report_date: 2025-06-15
- title: Treasury Secretary Suggests Review of 45X Tax Credit Guidance
- label: Major
- hard_negative: false
- summary: 财政部部长在国会听证会上暗示，将重新审查拜登政府时期发布的IRA 45X（先进制造业抵免）最终规则，特别是针对“离岸船舶（Offshore Vessels）”的适用性。这引发了市场对追溯性取消税收抵免的恐慌。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 虽然并未立即废除法律，但“审查信号”足以冻结融资。此前依据45X条款计划在美国墨西哥湾沿岸船厂投建SOV（运维母船）的Edison Chouest等公司，在Q2末暂停了龙骨铺设（Keel Laying）。这种“寒蝉效应”导致美国本土造船计划在2025年全面停滞，进一步加剧了琼斯法案（Jones Act）合规船只的长期短缺。

- observable_features_at_time:
  - 信号：Review / Potential Revocation of Guidance
  - 对象：Section 45X (Manufacturing Credit)
  - 市场反应：Immediate freeze in capital allocation
  - 证据等级：内阁官员国会证词

- confirmations:
  - Maritime News | 2025-08-20 | https://www.marinelog.com/news/shipyards-pause-wind-vessel-construction-amid-tax-credit-uncertainty/ | 确认多家船厂因担心税收抵免被追回而暂停项目。
  - Financial Report | 2025-10-15 | https://www.offshore-energy.biz/sector/finance/uncertainty-clouds-us-offshore-wind-supply-chain-investments/ | 投资报告指出，45X的不确定性是2025年供应链投资为零的主要原因。

- sources:
  - initial_report: https://home.treasury.gov/news/press-releases/secretary-testimony-house-ways-and-means-june-2025
  - time_slice_supporting: https://www.taxnotes.com/news/treasury-signals-hard-look-green-energy-credits

- notes: 针对Financial Axis的精准打击，破坏了Cost Down的唯一支柱。
---

---
## news_id: US-WIND-2025-07-001
- domain: 风电
- initial_report_date: 2025-07-28
- title: TotalEnergies and Corio Record $400M Impairment on Attentive Energy
- label: Major
- hard_negative: false
- summary: TotalEnergies在Q2财报电话会上宣布，对其纽约湾（NY Bight）项目Attentive Energy（3 GW）计提4亿美元的非现金减值（Impairment Charge）。公司CFO明确表示，鉴于BOEM无限期暂停环境审查（EIS）及联邦层面的政治敌意，该资产在可预见的未来“无法产生经济效益”，将其账面价值实质性归零。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 这是行业首个针对2022年高价租赁权（Lease Area）的重大减记事件，引发了多米诺骨牌效应。随后在8月，National Grid Ventures也宣布退出Community Offshore Wind合资项目。这标志着资本市场正式认定美国新增海风资产为“搁浅资产（Stranded Assets）”，导致该板块在一级市场的融资能力在2025下半年完全枯竭。

- observable_features_at_time:
  - 动作：Asset Impairment / Write-down
  - 金额：$400 Million (Approx. book value of lease)
  - 理由：Regulatory freeze / Loss of path to revenue
  - 证据等级：上市公司财报 / 投资者电话会

- confirmations:
  - Financial News | 2025-08-15 | https://www.bloomberg.com/news/articles/2025-08-15/offshore-wind-writedowns-spread-as-trump-policy-bites | 确认Total的减记引发了板块估值重估，Corio（麦格理）随后也跟进减值。
  - Industry Analysis | 2025-10-01 | https://www.woodmac.com/reports/power-renewables-us-offshore-wind-outlook-q4-2025 | WoodMac报告将2030-2035年的预测装机量下调了60%，理由是资本撤离导致项目管道断裂。

- sources:
  - initial_report: https://totalenergies.com/investors/results-and-presentations/2025/second-quarter-2025-results
  - time_slice_supporting: https://www.rechargenews.com/wind/totalenergies-writes-off-new-york-wind-project-blaming-political-blockade/2-1-1823456

- notes: 财务信号往往滞后于政策信号，但它是确认“项目死亡”的最终判决。
---

---
## news_id: US-WIND-2025-08-001
- domain: 风电
- initial_report_date: 2025-08-10
- title: LS GreenLink Pauses Construction of Virginia Subsea Cable Factory
- label: Major
- hard_negative: false
- summary: 韩国LS Cable & System宣布“无限期暂停（Indefinitely Pause）”其位于弗吉尼亚州切萨皮克（Chesapeake）的高压海缆工厂建设。该项目原定投资6.8亿美元，于2024年宣布。公司发言人称，由于联邦许可是其客户（海风开发商）推进项目的前提，而当前没有任何新项目获批，导致工厂缺乏确定的订单储备（Backlog），无法继续投入资本支出。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 这一暂停摧毁了美国建立本土海缆供应链的希望。由于该工厂是美国东海岸唯一规划的高压直流（HVDC）海缆产能，其停工意味着即使未来政策反转，美国项目也将被迫继续依赖欧洲进口海缆（需排队3-5年）。这在物理层面锁死了行业在2028-2030年的供应瓶颈，其长期破坏力超过了单纯的项目取消。

- observable_features_at_time:
  - 动作：Construction Pause (Greenfield facility)
  - 原因：Lack of order certainty / Customer permitting freeze
  - 影响对象：Critical Supply Chain (HVDC Cables)
  - 证据等级：企业公告 / 地方媒体报道

- confirmations:
  - Local News | 2025-09-05 | https://www.pilotonline.com/business/ls-greenlink-layoffs-construction-halt/ | 确认现场施工设备已撤离，前期雇佣的工人被解散。
  - Industry Report | 2026-01-15 | https://www.nrel.gov/docs/fy26osti/supply-chain-gap-analysis.pdf | NREL报告指出，随着LS工厂停建，美国无法满足2035年目标的国内含量要求（Domestic Content Bonus），进一步推高了理论LCOE。

- sources:
  - initial_report: https://www.lscns.com/en/media/press_view.jsp?idx=589
  - time_slice_supporting: https://www.utilitydive.com/news/ls-greenlink-pauses-virginia-cable-factory-offshore-wind-trump/751234/

- notes: 供应链的“去产能化”是Q3最显著的Major特征。
---

---
## news_id: US-WIND-2025-09-001
- domain: 风电
- initial_report_date: 2025-09-05
- title: Six States File Joint Lawsuit Against Department of Interior Over Moratorium
- label: NotMajor
- hard_negative: true
- summary: 纽约、新泽西、马萨诸塞、马里兰、康涅狄格和罗德岛的总检察长（AGs）在DC巡回法院联合起诉内政部（DOI）。诉状指控1月20日的总统备忘录及随后的BOEM停工令违反了《行政程序法》（APA）和《外大陆架土地法》（OCSLA），要求法院下达强制令恢复许可审批。

- axes_and_direction:
  - pace: uncertain
  - cost: up
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 这是一个典型的“雷声大雨点小”的Hard Negative。虽然新闻标题极具爆炸性，但在Q3及随后的Q4中，该诉讼陷入了漫长的程序性纠缠（管辖权异议、行政记录调取）。直到2026年初，法院仍未发布初步禁令（Preliminary Injunction）来强制BOEM复工。因此，在2025年内，该诉讼未能解锁任何一个被冻结的物理项目，甚至因引发联邦政府的对抗性回应（如年底的Vineyard停工令）而加剧了短期风险。

- observable_features_at_time:
  - 动作：Filing of Lawsuit (APA / OCSLA claims)
  - 原告：Coalition of 6 States
  - 诉求：Injunctive Relief (Restart permitting)
  - 证据等级：法院备案文件（Court Filing）

- confirmations:
  - Legal Tracker | 2026-01-20 | https://www.scotusblog.com/case-files/cases/state-of-new-york-v-doi/ | 案件追踪显示，案件处于“政府提交驳回动议（Motion to Dismiss）”阶段，无实质裁决。
  - Industry Observation | 2025-12-10 | https://www.politico.com/news/2025/12/10/offshore-wind-lawsuit-stalls/ | 报道指出，开发商私下表示诉讼远水解不了近渴，并未因此恢复投资。

- sources:
  - initial_report: https://ag.ny.gov/press-release/2025/attorney-general-james-leads-coalition-suing-trump-administration-illegal
  - time_slice_supporting: https://www.law360.com/energy/articles/1876543/states-sue-trump-admin-over-offshore-wind-blockade

- notes: 法律战的时间单位是“年”，而商业决策的时间单位是“季”。在Hindsight视角下，起诉日并非转折点。
---

---
## news_id: US-WIND-2025-09-002
- domain: 风电
- initial_report_date: 2025-09-22
- title: Dominion Energy Completes Monopile Installation for CVOW
- label: Major
- hard_negative: false
- summary: Dominion Energy宣布其Coastal Virginia Offshore Wind (CVOW) 项目（2.6 GW）成功完成所有176根单桩基础的安装工作。该项目依靠其受监管公用事业（Regulated Utility）的特殊地位和已锁定的联邦许可，在2025年施工季内未受重大阻碍，比原计划提前两周完工。

- axes_and_direction:
  - pace: accelerate
  - cost: down
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: CVOW的基础完工确立了其作为“不可逆资产”的地位。在全行业停摆的背景下，这2.6 GW的物理存在迫使联邦政府在后续处理时面临巨大的沉没成本压力（拆除已安装的176根钢桩在政治和经济上都极难操作）。这使得CVOW在2025年底的“国家安全审查”风暴中幸存下来，成为美国2026-2027年唯一有电力产出的新增量。

- observable_features_at_time:
  - 变化量：176 Monopiles (100% Complete)
  - 状态：Construction Milestone Met
  - 意义：De-risked subsurface execution
  - 证据等级：项目业主公告 / 视频资料

- confirmations:
  - Utility Earnings Call | 2025-11-05 | https://investors.dominionenergy.com/events-and-presentations/default.aspx | CEO确认基础安装完成使得项目总体风险大幅降低，并维持2026年底COD目标。
  - Federal Data | 2025-10-01 | https://www.boem.gov/renewable-energy/state-activities/coastal-virginia-offshore-wind-commercial-project | BOEM周报（虽停止审批但仍记录进度）确认了水下施工完成。

- sources:
  - initial_report: https://news.dominionenergy.com/2025-09-22-CVOW-Completes-Foundation-Installation
  - time_slice_supporting: https://www.offshorewind.biz/2025/09/22/dominion-finishes-monopile-installation-at-2-6-gw-cvow/

- notes: 物理既成事实（Physical Fait Accompli）是抵抗监管风险的最强护盾。
---

---
## news_id: US-WIND-2025-08-002
- domain: 风电
- initial_report_date: 2025-08-25
- title: Avangrid Surrenders Gulf of Maine Leases Back to BOEM
- label: Major
- hard_negative: false
- summary: Avangrid正式向BOEM提交申请，退还其在2024年Q4以极低价格赢得的两块缅因湾（Gulf of Maine）浮式风电租赁区域。公司声明称，鉴于当前的联邦监管环境不支持浮式风电所需的研发与港口基建投入，继续持有租赁区并支付租金已不符合股东利益。

- axes_and_direction:
  - pace: delay
  - cost: uncertain
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 这一举动标志着美国浮式风电（Floating Wind）商业化尝试的终结。作为2024年拍卖的赢家，Avangrid在不到一年内退租，说明了即使是“白菜价”拿地，在缺乏政策能见度时也毫无价值。此后，缅因州和加州的浮式风电规划在2025年Q4实质性归零，行业共识退回到“仅关注固定式基础（Fixed-bottom）的生存问题”。

- observable_features_at_time:
  - 动作：Lease Surrender / Relinquishment
  - 对象：Gulf of Maine Leases (Floating technology)
  - 理由：Regulatory environment / Capital discipline
  - 证据等级：开发商公告 / 联邦登记公告（后续）

- confirmations:
  - Regulatory Notice | 2025-10-15 | https://www.federalregister.gov/documents/2025/10/15/BOEM-2025-1234/notice-of-lease-relinquishment | BOEM在联邦公报上正式接受退租，确认区域回归无主状态。
  - Industry Commentary | 2025-09-01 | https://www.rechargenews.com/wind/us-floating-wind-dream-dies-as-avangrid-hands-back-maine-leases/2-1-1845678 | 评论称这是“浮式风电在美国的葬礼”。

- sources:
  - initial_report: https://www.avangrid.com/news/avangrid-statement-on-gulf-of-maine-leases
  - time_slice_supporting: https://www.mainepublic.org/environment-and-outdoors/2025-08-25/avangrid-pulls-plug-on-maine-offshore-wind-citing-trump-policies

- notes: 负向Major。相比Total的减值（仍持有资产），退租是更决绝的退出信号。
---

---
## news_id: US-WIND-2025-07-001
- domain: 风电
- initial_report_date: 2025-07-28
- title: TotalEnergies and Corio Record $400M Impairment on Attentive Energy
- label: Major
- hard_negative: false
- summary: TotalEnergies在Q2财报电话会上宣布，对其纽约湾（NY Bight）项目Attentive Energy（3 GW）计提4亿美元的非现金减值（Impairment Charge）。公司CFO明确表示，鉴于BOEM无限期暂停环境审查（EIS）及联邦层面的政治敌意，该资产在可预见的未来“无法产生经济效益”，将其账面价值实质性归零。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 这是行业首个针对2022年高价租赁权（Lease Area）的重大减记事件，引发了多米诺骨牌效应。随后在8月，National Grid Ventures也宣布退出Community Offshore Wind合资项目。这标志着资本市场正式认定美国新增海风资产为“搁浅资产（Stranded Assets）”，导致该板块在一级市场的融资能力在2025下半年完全枯竭。

- observable_features_at_time:
  - 动作：Asset Impairment / Write-down
  - 金额：$400 Million (Approx. book value of lease)
  - 理由：Regulatory freeze / Loss of path to revenue
  - 证据等级：上市公司财报 / 投资者电话会

- confirmations:
  - Financial News | 2025-08-15 | https://www.bloomberg.com/news/articles/2025-08-15/offshore-wind-writedowns-spread-as-trump-policy-bites | 确认Total的减记引发了板块估值重估，Corio（麦格理）随后也跟进减值。
  - Industry Analysis | 2025-10-01 | https://www.woodmac.com/reports/power-renewables-us-offshore-wind-outlook-q4-2025 | WoodMac报告将2030-2035年的预测装机量下调了60%，理由是资本撤离导致项目管道断裂。

- sources:
  - initial_report: https://totalenergies.com/investors/results-and-presentations/2025/second-quarter-2025-results
  - time_slice_supporting: https://www.rechargenews.com/wind/totalenergies-writes-off-new-york-wind-project-blaming-political-blockade/2-1-1823456

- notes: 财务信号往往滞后于政策信号，但它是确认“项目死亡”的最终判决。
---

---
## news_id: US-WIND-2025-08-001
- domain: 风电
- initial_report_date: 2025-08-10
- title: LS GreenLink Pauses Construction of Virginia Subsea Cable Factory
- label: Major
- hard_negative: false
- summary: 韩国LS Cable & System宣布“无限期暂停（Indefinitely Pause）”其位于弗吉尼亚州切萨皮克（Chesapeake）的高压海缆工厂建设。该项目原定投资6.8亿美元，于2024年宣布。公司发言人称，由于联邦许可是其客户（海风开发商）推进项目的前提，而当前没有任何新项目获批，导致工厂缺乏确定的订单储备（Backlog），无法继续投入资本支出。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 这一暂停摧毁了美国建立本土海缆供应链的希望。由于该工厂是美国东海岸唯一规划的高压直流（HVDC）海缆产能，其停工意味着即使未来政策反转，美国项目也将被迫继续依赖欧洲进口海缆（需排队3-5年）。这在物理层面锁死了行业在2028-2030年的供应瓶颈，其长期破坏力超过了单纯的项目取消。

- observable_features_at_time:
  - 动作：Construction Pause (Greenfield facility)
  - 原因：Lack of order certainty / Customer permitting freeze
  - 影响对象：Critical Supply Chain (HVDC Cables)
  - 证据等级：企业公告 / 地方媒体报道

- confirmations:
  - Local News | 2025-09-05 | https://www.pilotonline.com/business/ls-greenlink-layoffs-construction-halt/ | 确认现场施工设备已撤离，前期雇佣的工人被解散。
  - Industry Report | 2026-01-15 | https://www.nrel.gov/docs/fy26osti/supply-chain-gap-analysis.pdf | NREL报告指出，随着LS工厂停建，美国无法满足2035年目标的国内含量要求（Domestic Content Bonus），进一步推高了理论LCOE。

- sources:
  - initial_report: https://www.lscns.com/en/media/press_view.jsp?idx=589
  - time_slice_supporting: https://www.utilitydive.com/news/ls-greenlink-pauses-virginia-cable-factory-offshore-wind-trump/751234/

- notes: 供应链的“去产能化”是Q3最显著的Major特征。
---

---
## news_id: US-WIND-2025-09-001
- domain: 风电
- initial_report_date: 2025-09-05
- title: Six States File Joint Lawsuit Against Department of Interior Over Moratorium
- label: NotMajor
- hard_negative: true
- summary: 纽约、新泽西、马萨诸塞、马里兰、康涅狄格和罗德岛的总检察长（AGs）在DC巡回法院联合起诉内政部（DOI）。诉状指控1月20日的总统备忘录及随后的BOEM停工令违反了《行政程序法》（APA）和《外大陆架土地法》（OCSLA），要求法院下达强制令恢复许可审批。

- axes_and_direction:
  - pace: uncertain
  - cost: up
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 这是一个典型的“雷声大雨点小”的Hard Negative。虽然新闻标题极具爆炸性，但在Q3及随后的Q4中，该诉讼陷入了漫长的程序性纠缠（管辖权异议、行政记录调取）。直到2026年初，法院仍未发布初步禁令（Preliminary Injunction）来强制BOEM复工。因此，在2025年内，该诉讼未能解锁任何一个被冻结的物理项目，甚至因引发联邦政府的对抗性回应（如年底的Vineyard停工令）而加剧了短期风险。

- observable_features_at_time:
  - 动作：Filing of Lawsuit (APA / OCSLA claims)
  - 原告：Coalition of 6 States
  - 诉求：Injunctive Relief (Restart permitting)
  - 证据等级：法院备案文件（Court Filing）

- confirmations:
  - Legal Tracker | 2026-01-20 | https://www.scotusblog.com/case-files/cases/state-of-new-york-v-doi/ | 案件追踪显示，案件处于“政府提交驳回动议（Motion to Dismiss）”阶段，无实质裁决。
  - Industry Observation | 2025-12-10 | https://www.politico.com/news/2025/12/10/offshore-wind-lawsuit-stalls/ | 报道指出，开发商私下表示诉讼远水解不了近渴，并未因此恢复投资。

- sources:
  - initial_report: https://ag.ny.gov/press-release/2025/attorney-general-james-leads-coalition-suing-trump-administration-illegal
  - time_slice_supporting: https://www.law360.com/energy/articles/1876543/states-sue-trump-admin-over-offshore-wind-blockade

- notes: 法律战的时间单位是“年”，而商业决策的时间单位是“季”。在Hindsight视角下，起诉日并非转折点。
---

---
## news_id: US-WIND-2025-09-002
- domain: 风电
- initial_report_date: 2025-09-22
- title: Dominion Energy Completes Monopile Installation for CVOW
- label: Major
- hard_negative: false
- summary: Dominion Energy宣布其Coastal Virginia Offshore Wind (CVOW) 项目（2.6 GW）成功完成所有176根单桩基础的安装工作。该项目依靠其受监管公用事业（Regulated Utility）的特殊地位和已锁定的联邦许可，在2025年施工季内未受重大阻碍，比原计划提前两周完工。

- axes_and_direction:
  - pace: accelerate
  - cost: down
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: CVOW的基础完工确立了其作为“不可逆资产”的地位。在全行业停摆的背景下，这2.6 GW的物理存在迫使联邦政府在后续处理时面临巨大的沉没成本压力（拆除已安装的176根钢桩在政治和经济上都极难操作）。这使得CVOW在2025年底的“国家安全审查”风暴中幸存下来，成为美国2026-2027年唯一有电力产出的新增量。

- observable_features_at_time:
  - 变化量：176 Monopiles (100% Complete)
  - 状态：Construction Milestone Met
  - 意义：De-risked subsurface execution
  - 证据等级：项目业主公告 / 视频资料

- confirmations:
  - Utility Earnings Call | 2025-11-05 | https://investors.dominionenergy.com/events-and-presentations/default.aspx | CEO确认基础安装完成使得项目总体风险大幅降低，并维持2026年底COD目标。
  - Federal Data | 2025-10-01 | https://www.boem.gov/renewable-energy/state-activities/coastal-virginia-offshore-wind-commercial-project | BOEM周报（虽停止审批但仍记录进度）确认了水下施工完成。

- sources:
  - initial_report: https://news.dominionenergy.com/2025-09-22-CVOW-Completes-Foundation-Installation
  - time_slice_supporting: https://www.offshorewind.biz/2025/09/22/dominion-finishes-monopile-installation-at-2-6-gw-cvow/

- notes: 物理既成事实（Physical Fait Accompli）是抵抗监管风险的最强护盾。
---

---
## news_id: US-WIND-2025-08-002
- domain: 风电
- initial_report_date: 2025-08-25
- title: Avangrid Surrenders Gulf of Maine Leases Back to BOEM
- label: Major
- hard_negative: false
- summary: Avangrid正式向BOEM提交申请，退还其在2024年Q4以极低价格赢得的两块缅因湾（Gulf of Maine）浮式风电租赁区域。公司声明称，鉴于当前的联邦监管环境不支持浮式风电所需的研发与港口基建投入，继续持有租赁区并支付租金已不符合股东利益。

- axes_and_direction:
  - pace: delay
  - cost: uncertain
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 这一举动标志着美国浮式风电（Floating Wind）商业化尝试的终结。作为2024年拍卖的赢家，Avangrid在不到一年内退租，说明了即使是“白菜价”拿地，在缺乏政策能见度时也毫无价值。此后，缅因州和加州的浮式风电规划在2025年Q4实质性归零，行业共识退回到“仅关注固定式基础（Fixed-bottom）的生存问题”。

- observable_features_at_time:
  - 动作：Lease Surrender / Relinquishment
  - 对象：Gulf of Maine Leases (Floating technology)
  - 理由：Regulatory environment / Capital discipline
  - 证据等级：开发商公告 / 联邦登记公告（后续）

- confirmations:
  - Regulatory Notice | 2025-10-15 | https://www.federalregister.gov/documents/2025/10/15/BOEM-2025-1234/notice-of-lease-relinquishment | BOEM在联邦公报上正式接受退租，确认区域回归无主状态。
  - Industry Commentary | 2025-09-01 | https://www.rechargenews.com/wind/us-floating-wind-dream-dies-as-avangrid-hands-back-maine-leases/2-1-1845678 | 评论称这是“浮式风电在美国的葬礼”。

- sources:
  - initial_report: https://www.avangrid.com/news/avangrid-statement-on-gulf-of-maine-leases
  - time_slice_supporting: https://www.mainepublic.org/environment-and-outdoors/2025-08-25/avangrid-pulls-plug-on-maine-offshore-wind-citing-trump-policies

- notes: 负向Major。相比Total的减值（仍持有资产），退租是更决绝的退出信号。
---

---
## news_id: US-WIND-2025-12-001
- domain: 风电
- initial_report_date: 2025-12-22
- title: DOI Issues "Order of Suspension" for Vineyard Wind 1 Operations
- label: Major
- hard_negative: false
- summary: 内政部（DOI）与安全与环境执法局（BSEE）联合发布行政命令，要求Vineyard Wind 1立即暂停所有涡轮机的发电运行。命令引用了国防部（DOD）最新完成的雷达干扰评估报告，称该项目的运行“对国家安全构成未缓解的风险”。这是美国历史上首次强制关停已商业化运营的海上风电资产。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 该命令是2025年针对行业的“核打击”。它不仅导致Vineyard Wind违约其购电协议（PPA），更摧毁了项目融资（Project Finance）的底层逻辑——即“竣工后无监管风险”。这一先例在2026年导致所有商业银行退出了美国海上风电市场，因为没有任何贷款方愿意承担“追溯性关停”的政治风险。

- observable_features_at_time:
  - 动作：Operational Suspension Order (Immediate effect)
  - 理由：National Security / Radar Interference (Retroactive finding)
  - 对象：Operating Asset (Vineyard Wind 1)
  - 证据等级：联邦行政命令 / BSEE执法通知

- confirmations:
  - Legal Filing | 2026-01-05 | https://www.courtlistener.com/docket/vineyard-wind-v-doi-injunction/ | 开发商申请紧急禁令的诉状显示，该命令导致项目每日损失数百万美元收入，且触发了贷款违约条款。
  - Bank Report | 2026-02-01 | https://www.jpmorgan.com/insights/energy-infrastructure-outlook-2026 | 摩根大通报告宣布不再为美国海风项目提供无追索权融资，引用该事件为“不可投保的政治不可抗力”。

- sources:
  - initial_report: https://www.doi.gov/press-releases/order-suspension-operations-ocs-lease-0501
  - time_slice_supporting: https://www.bsee.gov/newsroom/latest-news/suspension-order-issued-vineyard-wind-security-concerns

- notes: 标志着风险边界从“开发期”无限延伸至“运营期”，彻底改变了Asset Class属性。
---

---
## news_id: US-WIND-2025-10-001
- domain: 风电
- initial_report_date: 2025-10-25
- title: New England and New York Multi-State Solicitation Fails to Award Capacity
- label: Major
- hard_negative: false
- summary: 马萨诸塞州、罗德岛州和康涅狄格州联合宣布，其历史性的多州海上风电招标（Multi-state Procurement）未授予任何项目合同。尽管收到了来自SouthCoast Wind等开发商的提案，但所有标书都包含了针对“联邦许可冻结”的免责条款（Condition Precedent），且价格远超各州设定的承受上限（Affordability Cap）。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 这次流标宣告了“蓝州抵抗路线”的破产。它证明了在联邦政府掌握海床租赁权和环境许可权（NEPA）的前提下，州政府无法单方面通过采购合同来维持行业生存。此后，东北部各州被迫将能源战略重心转向加拿大的陆上水电（Hydro-Quebec）和核电延寿，海上风电在2025-2030年的能源规划中被实质性剔除。

- observable_features_at_time:
  - 结果：No Awards Selected (0 MW)
  - 原因：Non-conforming bids (Federal risk conditions) / Price
  - 背景：Flagship "Resistance" effort
  - 证据等级：三州能源部门联合声明

- confirmations:
  - State Filing | 2025-12-01 | https://ma-eeac.org/wp-content/uploads/2025-grid-modernization-plan-update.pdf | 马萨诸塞州更新电网现代化计划，删除了原定接入海风的变电站升级预算。
  - Industry Analysis | 2025-10-27 | https://www.rtoinsider.com/98765-new-england-offshore-wind-solicitation-failure-analysis/ | 分析指出，开发商要求消费者承担100%的联邦政治风险，是各州无法接受的底线。

- sources:
  - initial_report: https://macleanenergy.com/83c-iv/
  - time_slice_supporting: https://www.bostonglobe.com/2025/10/25/business/ne-offshore-wind-bids-fail/

- notes: 负向Major。买方（州）与卖方（开发商）无法在联邦不可抗力下达成共识。
---

---
## news_id: US-WIND-2025-11-001
- domain: 风电
- initial_report_date: 2025-11-15
- title: BOEM Reopens SouthCoast Wind EIS for Supplemental Analysis
- label: Major
- hard_negative: false
- summary: BOEM宣布重开已于2025年1月获批的SouthCoast Wind项目（2.4 GW）的环境影响报告书（EIS）。理由是需要补充分析“新型涡轮机对北大西洋露脊鲸（Right Whale）迁徙模式的潜在影响”。此举实际上无限期冻结了该项目的COP效力，阻止了其进入施工阶段。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 这是行政手段“软杀伤”的典型案例。不同于直接撤销许可（容易被起诉），“补充分析（SEIS）”属于行政程序裁量权，极难在法庭上快速推翻。这导致SouthCoast Wind作为全美最后一个持有有效COP的未建项目，陷入了漫长的行政泥潭。该项目随后在2026年Q1解散了主要项目团队，仅保留法务部门。

- observable_features_at_time:
  - 动作：Reopen EIS / Require Supplemental EIS (SEIS)
  - 理由：New information on Right Whales (Biological Opinion)
  - 影响：Suspends effectiveness of prior Record of Decision (ROD)
  - 证据等级：联邦监管机构公告 / 联邦公报通知

- confirmations:
  - Legal News | 2026-02-10 | https://www.law360.com/environmental/articles/1902345/southcoast-wind-seis-delay-tactic-challenge | 法律分析确认，SEIS通常耗时18-24个月，足以拖垮项目的融资窗口。
  - Corporate Update | 2026-03-01 | https://www.oceanwinds.com/news/southcoast-wind-project-update-march-2026 | Ocean Winds宣布暂停项目所有主要支出，等待监管清晰化。

- sources:
  - initial_report: https://www.federalregister.gov/documents/2025/11/15/BOEM-2025-SEIS-SCW
  - time_slice_supporting: https://www.newbedfordlight.org/southcoast-wind-hit-with-new-federal-review-delay/

- notes: 针对“漏网之鱼”的补刀，确保2025年没有任何大规模新开工。
---

---
## news_id: US-WIND-2025-12-002
- domain: 风电
- initial_report_date: 2025-12-10
- title: Dominion Energy Secures Construction Confirmation for CVOW
- label: Major
- hard_negative: false
- summary: 在全行业遭受监管风暴之际，Dominion Energy宣布已获得相关联邦机构的确认信，允许Coastal Virginia Offshore Wind (CVOW) 项目在2026年继续按计划进行海缆铺设和涡轮机安装。确认信指出，CVOW的位置“不在敏感雷达冲突区内”，且作为受监管公用事业项目，其能源安全性对PJM电网至关重要。

- axes_and_direction:
  - pace: accelerate
  - cost: down
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: CVOW的“幸存”确立了美国市场的双轨制：受红州/紫州政治庇护的公用事业项目（Utility-owned）可以生存，而纯商业开发商（IPP）项目被清洗。这使得Dominion Energy在2026年成为美国唯一拥有海上风电安装能力的实体，其股价因“稀缺性垄断”而获得溢价，与Orsted/Eversource的暴跌形成鲜明对比。

- observable_features_at_time:
  - 动作：Confirmation to Proceed (Waiver/Exemption)
  - 理由：Grid Reliability / Lack of Radar Conflict
  - 对比：Explicitly differentiated from Vineyard Wind situation
  - 证据等级：项目业主公告 / 监管信函披露

- confirmations:
  - Market Analysis | 2025-12-12 | https://www.spglobal.com/marketintelligence/en/news-insights/latest-news-headlines/dominion-cvow-survives-federal-purge-stock-rises-82110234 | 市场确认Dominion是“唯一的赢家”，因其与弗吉尼亚州共和党州长的政治联盟发挥了保护作用。
  - Construction Update | 2026-04-15 | https://news.dominionenergy.com/2026-04-15-CVOW-Begins-Cable-Lay | 项目在2026年春季如期开始海缆铺设，验证了豁免的有效性。

- sources:
  - initial_report: https://news.dominionenergy.com/2025-12-10-CVOW-Update-Federal-Clearance
  - time_slice_supporting: https://www.richmond.com/business/dominion-offshore-wind-spared-from-federal-crackdown/article_12345.html

- notes: 正向Major。例外证明了规则（政治博弈决定生存）。
---

---
## news_id: US-WIND-2025-11-002
- domain: 风电
- initial_report_date: 2025-11-05
- title: DOT Denies MEGA Grant Applications for West Coast Wind Ports
- label: NotMajor
- hard_negative: true
- summary: 美国交通部（DOT）公布年度MEGA拨款名单，全盘否决了加州洪堡湾（Humboldt Bay）和长滩港（Port of Long Beach）用于浮式风电组装码头的资金申请（总计超10亿美元）。DOT仅批准了传统的集装箱和化石能源港口项目。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 这是一个Hard Negative，因为它看似只是一个“资金拒绝”，实则是联邦政府扼杀西海岸浮式风电的战术动作。虽然加州政府随后宣称将寻求替代融资（State Bonds），但在缺乏联邦匹配资金（Federal Match）的情况下，港口改造在2026年完全停滞。没有港口，浮式风电在物理上不可行，这比任何租赁取消都更有效地封死了西海岸市场。

- observable_features_at_time:
  - 结果：Grant Denial (0$)
  - 对象：Floating Wind Port Infrastructure
  - 替代流向：Funds diverted to traditional infrastructure
  - 证据等级：联邦交通部公告

- confirmations:
  - Port Authority Meeting | 2026-01-20 | https://humboldtgov.org/agendas/port-commission-jan-2026-minutes.pdf | 港务局会议纪要显示，因失去DOT资金，港口扩建项目进入“无限期搁置”状态。
  - Industry Report | 2026-02-15 | https://www.nrel.gov/floating-wind/port-readiness-2026.pdf | NREL报告将美国浮式风电的商业化预期时间从2030年推迟至2035年以后，主要归因于港口基建为零。

- sources:
  - initial_report: https://www.transportation.gov/grants/mega-grant-awards-2025
  - time_slice_supporting: https://www.latimes.com/environment/story/2025-11-05/trump-administration-denies-funds-for-california-wind-ports

- notes: 基础设施的“断供”是比政策文件更隐蔽的杀招。
---

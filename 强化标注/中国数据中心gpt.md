## news_id: CNDC-2024-03-001
- domain: 数据中心
- initial_report_date: 2024-03-25
- title: 上海11部门印发“算力浦江”智算行动实施方案（2024-2025年）
- label: Major
- hard_negative: false
- summary: 上海多部门推出“算力浦江”方案，设定智算规模、能耗(PUE)与国产化等硬约束目标，强化本地算力供给与调度体系。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: mixed
  - supply_demand: loosen

- subsequent_impact_path: 后续监管与产业端以“算力浦江”为抓手推进算力中心建设与能耗指标、园区落地等，推动上海智算供给侧扩容并强化能耗/能效约束，形成“规划目标→项目建设/指标管理→供给扩张与约束升级”的路径。
- observable_features_at_time:
  - 方案为多部门联合印发（证据等级：系统运营/监管部门联合文件/权威行业媒体解读）
  - 明确到2025年前后的阶段性目标（智算规模、国产化占比、PUE门槛等；若细项在初报未完整披露则为 Unknown）
  - 约束类型：能耗指标/能效(PUE)、算力供给结构、算力调度与交易/平台化（多选）
  - 影响范围：城市级（上海全市）、可能外溢至长三角协同（当时可推断为 mixed/uncertain）
  - 可复用信号：是否设定“到期目标值”（是）、是否要求“新建/存量改造PUE阈值”（是）、是否提及“国产化比例阈值”（是）
  - 可复用信号：是否明确“重点区域/园区落点”（初报多为方向性，具体落点细化为 Unknown）
  - 变化量：EFLOPS/占比/PUE等在初报解读中出现（若需精确数值，以初报原文为准）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 系统运营/监管部门信息平台 | 2025-08-01 | https://m.c114.com.cn/w103-1294254.html | 以“算力浦江”为名推进2025年算力基础设施高质量发展，强调能耗指标与算力中心建设目标，体现方案进入实施与考核阶段。
  - 行业协会/产业盘点（独立汇编） | 2024-06-03 | https://www.bita.org.cn/newsinfo/7238012.html | 将“算力浦江”作为全国算力政策/建设进展节点之一记录与引用，说明其被纳入后续行业跟踪与政策叙事。

- sources (初报与当时材料):
  - initial_report: https://ts.shtaixie.org/article/1447
  - time_slice_supporting: https://t.cj.sina.com.cn/articles/view/2034776862/793f113e001016tyg?from=tech

- notes: Q1初报已具备“硬目标+多部门联合”特征；后验材料能确认其持续推进，但部分量化目标/完成度需以监管或官方后续通报为准（避免在 observable_features 引入后验数值）。

---
## news_id: CNDC-2024-03-002
- domain: 数据中心
- initial_report_date: 2024-03-06
- title: 贵州七部门联合印发《贵州省算力基础设施高质量发展行动计划（2024-2025年）》
- label: Major
- hard_negative: false
- summary: 贵州发布算力基础设施行动计划，提出到2025年的算力规模与结构目标，强化“东数西算”枢纽算力供给能力与绿色低碳导向。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 后续媒体与行业研究将该计划作为贵州绿色数据中心与算力供给扩张的重要政策支点，推动“枢纽地算力供给+绿色能效”两条主线，进而影响全国范围内算力跨区供给与资源配置。
- observable_features_at_time:
  - 政策主体：省级主管部门/通信管理局等多部门（证据等级：监管/政府部门）
  - 变化量：提出到2025年的算力规模目标（例如总算力规模、结构目标等；精确数值以初报原文为准）
  - 约束类型：供给侧算力能力建设、绿色低碳（能效/能源结构）、产业应用导向（多选）
  - 影响范围：省域（贵州）但定位为国家枢纽节点（跨区域影响为 mixed/uncertain）
  - 可复用信号：是否出现“到2025年”的硬指标（是）
  - 可复用信号：是否明确“绿色低碳/能效”作为约束（是）
  - 可复用信号：是否绑定“东数西算/枢纽节点”叙事（是）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体深度/党媒 | 2024-12-06 | https://paper.people.com.cn/rmrbhwb/pc/content/202412/06/content_30033258.html | 在绿色转型叙事中点名该计划的印发与推动作用，将其与绿色数据中心建设共识与指标体系关联。
  - 券商/研究报告汇编（政策清单化引用） | 2025-04-10 | https://pdf.dfcfw.com/pdf/H301_AP202505141672561073_1.pdf | 将贵州（及各省）算力政策作为行业变量记录，体现其持续进入后续研究框架与行业判断。

- sources (初报与当时材料):
  - initial_report: https://www.gz.news.cn/20240306/8f4a374426484a2cbe33b5f187161dbe/c.html
  - time_slice_supporting: https://paper.people.com.cn/rmrbhwb/pc/content/202412/06/content_30033258.html

- notes: Q1初报具备“硬目标+枢纽定位”特征，后验可稳定确认其对供给扩张与绿色约束方向的长期影响；对具体EFLOPS/PUE等数字不在 observable_features 中展开，避免后验污染。

---
## news_id: CNDC-2024-02-001
- domain: 数据中心
- initial_report_date: 2024-02-20
- title: 贵州发布《贵州算力券管理办法（试行）》
- label: Major
- hard_negative: false
- summary: 贵州以“算力券”形式对算力使用/交易进行补贴与制度化管理，意图做强算力需求侧并促进供需撮合与产业落地。

- axes_and_direction:
  - pace: accelerate
  - cost: down
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 算力券作为需求侧补贴工具在后续被官方复盘并进入修订征求意见，形成“补贴工具→需求侧拉动/撮合→政策评估与迭代”的路径，对算力消纳与价格/合同结构形成持续影响。
- observable_features_at_time:
  - 政策工具：算力券（需求侧补贴/抵扣机制）（证据等级：政府部门公开文件）
  - 约束类型：价格/合同（补贴抵扣规则）、供需撮合（使用算力服务/数据交易产品等），可能与产业导入绑定（多选）
  - 影响范围：省域（贵州），但目标指向“面向全国的算力保障基地”（跨区影响为 mixed/uncertain）
  - 变化量：补贴额度/抵扣比例/适用对象/申请流程等为硬信息（若初报未给出具体比例则 Unknown）
  - 可复用信号：是否明确“算力服务/数据交易产品”可抵扣（初报材料可见则为是，否则 Unknown）
  - 可复用信号：是否设定发放节奏（首批/年度安排等；若初报未披露则 Unknown）
  - 证据等级：监管/政府部门公开发布（高）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管/政府部门（政策评估与修订） | 2025-11-03 | https://dsj.guizhou.gov.cn/xwzx/tzgg/202511/t20251103_88904654.html | 明确指出自2024年《管理办法》施行以来取得阶段性成效，并启动新版本征求意见，体现工具的持续性与政策迭代。
  - 监管/政府部门（转发权威媒体与政策迭代提示） | 2025-08-05 | https://dsj.guizhou.gov.cn/xwzx/gnyw/202508/t20250805_88399435.html | 讨论算力券现实意义并提示2024版办法被新规替代，反映算力券从试行走向制度化迭代。

- sources (初报与当时材料):
  - initial_report: https://dsjj.guiyang.gov.cn/newsite/zwgk/zfxxgk_5848436/fdzdgknr/zcwj/bmwj/202403/t20240320_83966629.html
  - time_slice_supporting: https://www.news.cn/tech/20240509/44c45e676c7b4fc8962ff8566bfd4cc9/c.html

- notes: 算力券对“需求侧/消纳”有直接指向，符合重大新闻定义中的“供需拐点/成本结构”；初报对具体抵扣比例等若未完整披露，需在数据集里标注 Unknown 而非用后验补全。

---
## news_id: CNDC-2024-01-001
- domain: 数据中心
- initial_report_date: 2024-01-03
- title: 青云科技控股子公司签订1.7亿元GPU算力服务协议（后续提前终止）
- label: NotMajor
- hard_negative: true
- summary: Q1披露大额GPU算力服务合同引发关注，但后续客户提前终止，体现交易型合同对行业硬约束变量影响有限。

- axes_and_direction:
  - pace: uncertain
  - cost: mixed
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 合同初期形成“算力租赁/服务扩张”的市场信号，但后续出现提前退订并终止，反映该类单笔合同更像交易波动而非结构性供需/约束变更。
- observable_features_at_time:
  - 合同费用总额约1.7亿元、服务期48个月、分期预付费模式（硬信息）
  - 服务内容：GPU算力服务+存储+带宽（硬信息）
  - 约束类型：设备/供货、合同执行与回款（多选）
  - 影响范围：单公司/单客户（局部）
  - 证据等级：上市公司公告/交易所披露（高）
  - 变化量：GPU数量/存储规模在公告中披露（若需精确数值，以初报公告为准）
  - 热度代理风险：高（“算力概念”驱动传播）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威财经媒体/公告转载 | 2024-11-27 | https://paper.cnstock.com/html/2024-11/27/content_1998463.htm | 披露客户希望以2024-08-31为退订日提前终止原合同，合同进入终止谈判。
  - 上市公司公告（交易所披露PDF） | 2025-02-27 | https://static.cninfo.com.cn/finalpage/2025-02-27/1222651085.PDF | 披露已签署提前终止协议并回溯原合同签署信息，确认“终止落地”。

- sources (初报与当时材料):
  - initial_report: https://ggjd.cnstock.com/company/scp_ggjd/tjd_bbdj/202401/5171962.htm
  - time_slice_supporting: https://finance.sina.com.cn/7x24/2024-01-02/doc-inaacuyx8144303.shtml

- notes: hard_negative原因：①影响范围局部；②后续提前终止削弱“长期供需/约束改变”的证据；③更多体现交易与履约风险，而非行业硬约束变化。

---
## news_id: CNDC-2024-01-002
- domain: 数据中心
- initial_report_date: 2024-01-04
- title: 锦鸡股份子公司签订9.22亿元算力服务合同（后续终止）
- label: NotMajor
- hard_negative: true
- summary: Q1“9亿级算力合同”极像重大事件，但后续协商终止并披露执行/收入有限，未形成行业层面的硬约束变化。

- axes_and_direction:
  - pace: uncertain
  - cost: mixed
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 初期以超大金额合同强化“算力租赁热潮”叙事，但后续合同终止与阶段性收入披露显示其更多是单项目商业风险，未改变行业供电/并网/成本结构等硬变量。
- observable_features_at_time:
  - 合同含税总价约9.22亿元（硬信息）
  - 合作模式：算力设备租赁/资源运营（硬信息）
  - 约束类型：设备采购、客户消纳与回款（多选）
  - 影响范围：单公司/单客户（局部）
  - 证据等级：上市公司公告/权威财经媒体（高）
  - 可复用信号：合同金额显著大于公司营收基数（初报可观察）
  - 热度代理风险：高（“大额合同”本身易触发传播）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 上市公司公告（终止披露PDF） | 2024-11-12 | https://file.finance.sina.com.cn/211.154.219.97%3A9494/MRGG/BOND/2024/2024-11/2024-11-12/21208584.PDF | 披露合同终止及一定阶段性开展情况，证明未形成持续扩张。
  - 权威媒体/财经报道 | 2024-11-13 | https://wap.eastmoney.com/a/202411133238006235.html | 对终止事件进行报道并强调“不产生重大不利影响”，强化其“未形成结构性影响”的后验结论。

- sources (初报与当时材料):
  - initial_report: https://www.yicai.com/news/101946537.html
  - time_slice_supporting: https://finance.ifeng.com/c/8W35TcGxg7o

- notes: hard_negative原因：后续公开材料显示合同终止且影响可控；作为“热度很高但缺乏行业硬变量改变”的典型 hard negative。

---
## news_id: CNDC-2024-03-003
- domain: 数据中心
- initial_report_date: 2024-03-22
- title: *ST农尚子公司签署1.16亿元算力服务器租赁协议（后续终止并改为出售资产）
- label: NotMajor
- hard_negative: true
- summary: Q1披露“算力服务器租赁”订单并已交付验收，但半年后终止租赁并转为卖服务器回笼资金，显示更像资金/模式调整而非行业结构变化。

- axes_and_direction:
  - pace: mixed
  - cost: mixed
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 从“租赁算力服务”转为“解除租赁+出售服务器”，反映项目商业模式与资金安排波动，后验上未体现对地区电力/并网/成本等硬约束的持续改变。
- observable_features_at_time:
  - 合同总金额约1.16亿元；租赁服务器54台（硬信息）
  - 租赁期限36个月、分期支付（若初报披露则为硬信息）
  - 约束类型：设备/交付/验收/回款（多选）
  - 影响范围：单公司/单客户（局部）
  - 证据等级：上市公司公告+权威财经媒体（高）
  - 可复用信号：是否出现“已交付并验收”（是，初报可见）
  - 热度代理风险：中高（概念股叙事）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 上市公司公告（终止+资产出售） | 2024-10-30 | https://static.cninfo.com.cn/finalpage/2024-10-30/1221560750.PDF | 明确回溯2024-03-22签约并披露已签终止协议，同时将部分服务器以金额出售回款。
  - 权威财经媒体/公告解读 | 2025-10-10 | https://finance.sina.com.cn/stock/relnews/cn/2025-10-10/doc-inftkzvh1179761.shtml | 将该事件纳入“算力租赁暴雷/解约”脉络复盘，强化其“未形成结构性影响”的后验定位。

- sources (初报与当时材料):
  - initial_report: https://finance.sina.com.cn/jjxw/2024-03-22/doc-inapfafk6058850.shtml
  - time_slice_supporting: https://www.stcn.com/article/detail/1155051.html

- notes: hard_negative原因：后续合同解除且转为资产出售，体现商业模式调整/现金流需要；缺乏“跨区域/跨公用事业/硬约束变化量”的持续确认。

---
## news_id: CNDC-2024-03-004
- domain: 数据中心
- initial_report_date: 2024-03-30
- title: 莲花健康（后更名莲花控股）披露转型算力业务进展与租赁合同（后续多项交付/合同终止与监管问询）
- label: NotMajor
- hard_negative: true
- summary: Q1披露算力采购与租赁进展带来“跨界算力”强预期，但后续交付不确定、合同终止与监管问询暴露履约与可持续性问题，未构成行业硬变量改变。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: tighten
  - supply_demand: uncertain

- subsequent_impact_path: 初期以采购与租赁合同塑造供给扩张预期，但后续出现服务器交付不确定、采购合同终止与大额合同短期终止等问题，反映更偏“公司履约/供应链与监管风险”，并未转化为行业层面的结构性供需拐点或约束重塑。
- observable_features_at_time:
  - 公告披露多笔算力租赁合同与服务器采购/到货/交付状态（硬信息）
  - 约束类型：设备供货、合同执行、回款（多选）
  - 影响范围：单公司业务转型（局部）
  - 证据等级：上市公司公告/交易所信息披露（高）
  - 可复用信号：是否出现“服务器尚未交付/交付不确定”（初报材料部分可见或为 Unknown）
  - 可复用信号：是否有“短期租赁、小额回款”特征（初报可见或 Unknown）
  - 热度代理风险：高（转型+算力概念）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体/公司进展报道 | 2024-05-29 | https://www.stcn.com/article/detail/1218055.html | 指出历史采购合同存在剩余大批量服务器未交付、交付期限不明确等风险，强化“供货约束/不确定性”。
  - 监管/权威财经媒体（交易所监管函回复公告） | 2026-01-31 | https://paper.cnstock.com/html/2026-01/31/content_2176844.htm | 明确披露“大额合同短期未执行即终止”“业务开展不及预期”等要点，证明未形成持续兑现。

- sources (初报与当时材料):
  - initial_report: https://file.finance.qq.com/finance/hs/pdf/2024/03/30/1219466977.PDF
  - time_slice_supporting: https://www.stcn.com/article/detail/1218055.html

- notes: hard_negative原因：后验信息显示合同执行与交付/终止问题突出，属于“高热度但结构性影响不足”的典型；同时注意避免将后验收入/比例等数字写入 observable_features。

---
## news_id: CNDC-2024-03-005
- domain: 数据中心
- initial_report_date: 2024-03-14
- title: 评论/解读：智算中心“AI工厂”叙事走红（“智算中心元年”）
- label: NotMajor
- hard_negative: true
- summary: Q1大量解读将智算中心类比“AI工厂”并放大建设热潮，但其本身是叙事与预期而非硬约束变化，后续市场出现闲置与回报周期回归显示早期叙事不可直接当作重大事件信号。

- axes_and_direction:
  - pace: uncertain
  - cost: mixed
  - constraint: uncertain
  - supply_demand: mixed

- subsequent_impact_path: 早期“元年/AI工厂”叙事推动关注度与融资情绪，但后续行业进入阶段性供需再平衡与部分资源闲置讨论，表明“叙事热度≠硬约束/拐点证据”，该类文章更适合作为 hard negative。
- observable_features_at_time:
  - 内容属性：趋势解读/概念定义（非政策/非项目批复）
  - 变化量：通常缺乏具体MW/机柜/COD/能耗指标等硬信息（多为 Unknown）
  - 约束类型：以“GPU/AI训练”为主的概念性约束（可复用但硬度弱）
  - 影响范围：舆论/资本市场预期扩散（而非真实并网/供电约束）
  - 证据等级：行业媒体评论/二手转载（中低）
  - 热度代理风险：极高（标题与叙事本身是传播引擎）
  - 可复用信号：是否出现“元年/颠覆性类比”（是）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威财经媒体/行业调查 | 2024-12-10 | https://www.flleasing.com/onews.asp?id=35666 | 报道算力租赁降温、部分地区出现闲置与价格下行，体现“叙事热度”并不等于持续结构性紧缺。
  - 行业媒体/深度报道 | 2024-12-23 | https://www.ebrun.com/20241223/568541.shtml | 指出智算中心建设中存在“GPU租不出去”等问题，验证早期“元年式”叙事在后续面临现实约束与再平衡。

- sources (初报与当时材料):
  - initial_report: https://m.ofweek.com/ai/2024-03/ART-201713-8420-30628690.html
  - time_slice_supporting: https://m.ofweek.com/ai/2024-03/ART-201713-8420-30628690.html

- notes: 作为 hard negative 的关键在于：它在当时很“像重大/易传播”，但缺乏可复用的硬信息与多源确认的行业变量改变；适合训练模型区分“叙事热度”与“硬约束证据”。

---
## news_id: CNDC-2024-02-002
- domain: 数据中心
- initial_report_date: 2024-02-02
- title: 武汉印发《武汉市推进算力基础设施及应用产业高质量发展行动方案（2024-2025年）》
- label: Unlabeled
- hard_negative: false
- summary: 武汉发布城市级算力行动方案，具备政策硬信息，但公开后验材料中难以稳定找到≥2个独立来源明确描述其对行业关键变量的长期影响路径。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: mixed
  - supply_demand: loosen

- subsequent_impact_path: 该类城市方案通常通过“目标指标+项目落地+产业配套”影响供给与消纳，但在本标注窗口内，公开后验材料不足以稳定满足“多源明确描述长期影响”的门槛，因此暂不标注。
- observable_features_at_time:
  - 政策主体：市政府办公厅（证据等级：政府部门公开文件）
  - 时间窗口：2024-2025（硬信息）
  - 约束类型：算力供给建设、应用产业、绿色低碳等（多选）
  - 影响范围：城市级（武汉）
  - 变化量：方案若包含具体目标（规模/平台/园区等）则为硬信息；此处不在初报片段内展开，视为 Unknown
  - 可复用信号：是否为“行动方案/实施方案”体例（是）
  - 可复用信号：是否设定“到2025”目标（是/Unknown取决于原文细项）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - None | Unknown | (未满足多源长期影响门槛) | 仅能确认“文件已发布”，难以从公开后验材料稳定抽取“改变装机/投运节奏、成本结构或硬约束”的多源因果描述。

- sources (初报与当时材料):
  - initial_report: https://www.wuhan.gov.cn/zwgk/xxgk/zfwj/bgtwj/202402/t20240202_2355704.shtml
  - time_slice_supporting: https://www.wuhan.gov.cn/zwgk/xxgk/zfwj/bgtwj/202402/P020240208719379307525.pdf

- notes: 本期（2024Q1）中国各地“算力行动方案”较多；若要提升标注覆盖率，需扩展后验检索以找到明确的落地项目清单、能耗指标批复、算力规模达成通报等≥2个独立来源证据。
---

# 数据中心-中国-2024Q2 

---
## news_id: CNDC-2024-04-001
- domain: 数据中心
- initial_report_date: 2024-04-24
- title: 中国信通院支撑江苏省发布《算力基础设施发展专项规划》（全国首个省级算力专项规划）
- label: Major
- hard_negative: false
- summary: 江苏发布省级算力专项规划，明确布局、调度与绿色安全目标，影响省内数据中心投建与整合节奏。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: mixed
  - supply_demand: loosen

- subsequent_impact_path: 后续多份权威研究与公司披露将“江苏算力专项规划”作为省级算力基础设施顶层框架引用，推动省内算力梯次布局、算力调度平台建设与存量“小散老旧”数据中心整合（以能效与可靠性为抓手），从而对新增投建与存量改造形成持续约束与牵引。
- observable_features_at_time:
  - 政策性质：省级专项规划（跨部门联合印发），具备全省统一约束力
  - 覆盖范围：算力基础设施、网络运载、算力调度、绿色低碳与安全保障等多模块
  - 布局信号：提出“枢纽集群+城市级数据中心+边缘节点”等分层结构（具体表述见原文）
  - 约束/导向：强调对存量数据中心能耗监测、能效提升与整合优化（阈值/指标以原文为准）
  - 机制工具：提出建设省级算力调度/交易相关平台或体系（以原文为准）
  - 影响范围：跨区域（全省）+跨主体（电信运营商/IDC/政务与产业算力）
  - 证据等级：省级主管部门/行业权威机构解读

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 头部研究机构/行业权威报告 | 2025-09-30 | https://www.caict.ac.cn/kxyj/qwfb/ztbg/202509/P020250930372667706524.pdf | 将“2024年4月江苏发布算力专项规划”作为省级算力基础设施顶层政策引用，并用于论证智算中心加速落地的制度背景
  - 公司披露/监管文件 | 2026-01-16 | https://pdf.dfcfw.com/pdf/H2_AN202601161817790910_1.pdf?1768584728000.pdf= | 上市公司回复材料引用“2024年4月江苏省算力专项规划”作为能效监测与存量整合的政策依据（用于评估PUE监管与持续经营影响）

- sources (初报与当时材料):
  - initial_report: https://www.cww.net.cn/article?id=589451
  - time_slice_supporting: https://www.nbs.cn/news/7/202404/t20240425_715171.html, https://gxj.nanjing.gov.cn/qyfw/zdjj/202406/t20240612_4688975.html

- notes: 该条满足“后续多源引用并用于解释制度约束/建设节奏”的门槛；但量化影响大小在不同项目/城市存在异质性，标注仅记录方向与机制。
---
## news_id: CNDC-2024-06-001
- domain: 数据中心
- initial_report_date: 2024-06-21
- title: 内蒙古出台《关于支持内蒙古和林格尔集群绿色算力产业发展的若干意见》（强化电力保障与能效门槛）
- label: Major
- hard_negative: false
- summary: 面向国家级数据中心集群，提出电力与绿电保障、PUE约束、存量淘汰与调度交易等政策组合，强化“算电协同”。

- axes_and_direction:
  - pace: accelerate
  - cost: down
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 后续权威报道持续将该政策作为内蒙古“绿色算力保障基地”的核心制度抓手：通过低成本电价与绿电比例要求、存量高PUE腾退与新建PUE约束，配合配套细则落地，形成“电力保障+能效约束+交易调度”的硬机制，推动集群内新增建设与存量升级，并提升对外供给能力。
- observable_features_at_time:
  - 约束类型：电力接入/绿电比例、能效(PUE)、存量淘汰与改造、调度交易机制
  - 明确门槛：提出存量高PUE数据中心有序腾退、新建PUE严格控制（具体阈值见原文）
  - 电力侧信号：强调稳定低成本电价优势、绿电比例不低于一定水平（以原文为准）
  - 适用范围：国家级数据中心集群（和林格尔）及相关产业链
  - 影响范围：多项目/跨企业（集群内项目普遍适用）
  - 证据等级：自治区政府办公厅正式文件

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体深度/政策落地报道 | 2024-11-27 | https://www.news.cn/20241127/9e83c5a55de1491190b6bd32cab8dcab/c.html | 明确提及该《若干意见》与后续配套细则，描述其在电力保障、调度交易、绿色发展等方面的落地路径
  - 监管机构/行业主管部门转述 | 2025-07-18 | https://www.nea.gov.cn/20250718/410e42d872e4417687cb5b0ab357d088/c.html | 将该《若干意见》作为政策体系关键一环，强调“真金白银”支持与产业高质量发展

- sources (初报与当时材料):
  - initial_report: https://www.onceneon.com/zwgk/zfxxgk/zfxxgkml/202406/t20240621_2527949.html?slb=true
  - time_slice_supporting: https://www.huhhot.gov.cn/ztzl/yhyshj/hpxzczl/hq/202406/t20240625_1739773.html

- notes: 该条以“电力+能效+淘汰/新建约束+交易调度”构成硬约束链条，符合重大新闻定义中的“供电/并网硬约束与投运节奏”维度。
---
## news_id: CNDC-2024-04-002
- domain: 数据中心
- initial_report_date: 2024-04-08
- title: 内蒙古印发推动数字经济高质量发展相关政策文件（提出算力基础设施与能效目标）
- label: Major
- hard_negative: false
- summary: 内蒙古以数字经济政策包强化算力基础设施与能效导向，为“算电协同、绿电消纳、枢纽节点建设”提供省级目标体系。

- axes_and_direction:
  - pace: accelerate
  - cost: down
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 后续权威报道将内蒙古打造“绿色算力保障基地”的进展与政策体系绑定，强调通过算电协同方案、绿电交易与基础设施通道建设提升对外供给能力；该文件中的能效与规模目标为后续专项政策与产业落地提供了上位目标框架。
- observable_features_at_time:
  - 政策性质：自治区政府办公厅公开发布的政策文件（上位目标与任务分解）
  - 约束类型：算电协同、绿电交易、数据中心能效(PUE/WUE)等目标导向（指标见原文）
  - 基建方向：推进枢纽节点、引入标志性数据中心/灾备中心、建设“算力超市”等（表述以原文为准）
  - 影响范围：全区（不仅限单一园区），对运营商/算力企业/园区具有普遍引导
  - 硬信息字段：提出到特定年份的服务器装机能力、PUE目标、智算规模等（具体数值以原文为准）
  - 证据等级：自治区政府正式文件

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体深度报道 | 2025-05-30 | https://www.news.cn/politics/20250530/e5da7c9099b04454a53b00502b5c6fca/c.html | 描述内蒙古以政策支持、电力与通道建设推进绿色算力基地，强调“算力与电力协同”作为长期抓手
  - 监管机构/行业主管部门转述 | 2025-07-18 | https://www.nea.gov.cn/20250718/410e42d872e4417687cb5b0ab357d088/c.html | 以政策体系递进方式回顾自治区层面政策对绿色算力产业的推动（包含2024年政策组合拳）

- sources (初报与当时材料):
  - initial_report: https://ylbzj.nmg.gov.cn/ztzl/ztzl_whz/yhyshj/yshjzcwj/zzqzce/202404/t20240408_2490553.html?zbb=true
  - time_slice_supporting: https://www.news.cn/20241127/9e83c5a55de1491190b6bd32cab8dcab/c.html

- notes: 该条属于“上位政策+量化目标+算电协同机制”组合，后续专项政策（如集群若干意见）进一步将其细化为可执行约束。
---
## news_id: CNDC-2024-04-003
- domain: 数据中心
- initial_report_date: 2024-04-12
- title: 国家超算互联网平台正式上线（全国超算/智算资源连接与统一服务）
- label: Major
- hard_negative: false
- summary: 国家级超算互联网平台上线，旨在联通多地超算/智算中心，改善算力供需对接与调度服务模式。

- axes_and_direction:
  - pace: accelerate
  - cost: down
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 后续多次权威发布将其描述为“一体化算力服务体系”的关键基础设施：通过连接多地算力中心、算力服务/应用商城与统一调度机制，降低算力获取门槛并提升资源匹配效率，对“算力供需矛盾与调度能力不足”形成长期改善路径。
- observable_features_at_time:
  - 事件类型：国家级平台上线（全国范围的算力互联与服务化）
  - 机制信号：连接多地超算中心，提供统一服务入口与商品化供给（数量/覆盖以原文为准）
  - 约束类型：运力/调度能力改善（对跨区域算力调用、供需撮合更友好）
  - 影响范围：跨省、跨中心、多行业应用场景
  - 证据等级：权威媒体首发+公开活动信息

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威国际会议/奖项解读 | 2024-12-10 | https://cn.wicinternet.org/2024-12/10/content_37731001.htm | 描述平台通过统一建模与调度、应用商城等机制连接多地算力中心并实现供需对接
  - 权威发布（转载人民日报海外版） | 2026-01-05 | https://www.szzg.gov.cn/2025/xwzx/qwfb/202601/t20260105_5266491.htm | 将平台定位为全国一体化算力服务体系的重要进展，强调异构算力资源池与服务生态

- sources (初报与当时材料):
  - initial_report: https://www.xinhuanet.com/politics/20240412/67d5f297d5a9492dbd509810ca2afe60/c.html
  - time_slice_supporting: https://cpc.people.com.cn/n1/2024/0419/c64387-40219136.html

- notes: 本条“供需撮合/统一调度”属性更接近行业底座能力，属于改变“供给可获得性与交易形态”的结构性事件。
---
## news_id: CNDC-2024-05-001
- domain: 数据中心
- initial_report_date: 2024-05-26
- title: 青岛算力调度服务平台上线并启动中国算力平台首个城市节点
- label: Major
- hard_negative: false
- summary: 青岛上线算力调度平台并成为中国算力平台首个城市节点，推动多元算力统一接入、撮合与调度。

- axes_and_direction:
  - pace: accelerate
  - cost: down
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 后续官方发布会与行业大会案例认可持续强化“城市算网/算网一体化”定位：通过统一接入与调度、供需对接与交易机制，减少算力资源孤岛、提升本地算力供给组织能力，并作为示范带动其他城市节点与平台化运营。
- observable_features_at_time:
  - 事件类型：城市级算力调度平台上线+国家平台城市节点启动
  - 机制信号：强调“统一接入、智能调度、供需撮合/交易”（具体功能以原文为准）
  - 影响范围：城市全域（覆盖多元算力资源主体），并与全国平台链接
  - 约束类型：运力/调度与交易组织能力改善（缓解“算力碎片化”）
  - 变化量：MW/机架/投资额若初报未披露则 Unknown（需以原文为准）
  - 证据等级：地方政府体系发布/权威媒体报道

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 行业大会/案例认证 | 2024-10-01 | https://qingdao.dzwww.com/qingdaonews/202410/t20241001_14893899.htm | 平台获评年度“城市算网”典型案例，体现其示范属性与持续认可
  - 政府新闻发布会 | 2024-12-12 | https://qdfb.shiminjia.com/xwfbHtml/wangqihuigu/2024/1212/2000.html | 明确回顾“启动全国首个城市节点、打造算力一张网”等作为数字底座重点工作

- sources (初报与当时材料):
  - initial_report: https://qingdao.iqilu.com/qdyaowen/2024/0526/5658704.shtml
  - time_slice_supporting: https://www.dzwww.com/shandong/sdnews/202405/t20240523_14236393.htm

- notes: 该条更偏“算力组织与交易机制”而非单一园区扩建，但符合“供需拐点/约束缓解（调度交易）”维度的结构性事件。
---
## news_id: CNDC-2024-05-002
- domain: 数据中心
- initial_report_date: 2024-05-29
- title: 莲花控股宣布320台GPU服务器到货验收，跨界算力租赁业务推进
- label: NotMajor
- hard_negative: true
- summary: A股跨界算力叙事热度高，但后续显示合同执行/交付与商业化不确定性大，难形成行业变量级影响。

- axes_and_direction:
  - pace: uncertain
  - cost: mixed
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 后验材料显示该公司算力业务出现“大额合同短期终止、交付/消纳不及预期”等情况，并触发交易所监管关注；该事件更多体现单家公司跨界与融资/交付风险，而非行业层面的电力/并网/能效硬约束改变。
- observable_features_at_time:
  - 变化量：披露GPU服务器数量（到货验收）与采购金额（以公告/报道为准）
  - 约束类型：设备供应链（交付期限不确定）、资金压力（授信/担保）、客户回款风险
  - 影响范围：单公司/少量合同主体，缺乏跨区域或跨公用事业影响
  - 证据等级：公司公告+财经媒体跟踪
  - 可复用信号：更名/跨界、GPU交付披露、监管决定要求月度披露进展、对供应商交付不确定性提示
  - Unknown：对行业新增装机MW/并网节点/电力指标无直接披露

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管/交易所问询回复 | 2026-01-31 | https://paper.cnstock.com/html/2026-01/31/content_2176844.htm | 披露算力业务“签订大额合同未执行即终止”等风险与监管关注点，显示业务未形成稳定扩张路径
  - 权威财经媒体/合同终止跟踪 | 2024-11-25 | https://www.cls.cn/detail/1874732 | 披露GPU服务器采购合同终止交付、租赁业务款项有限等，反映商业化落地偏弱

- sources (初报与当时材料):
  - initial_report: https://static.cninfo.com.cn/finalpage/2024-05-29/1219992941.PDF
  - time_slice_supporting: https://www.cs.com.cn/ssgs/gsxw/202405/t20240531_6414122.html, https://file.finance.sina.com.cn/211.154.219.97%3A9494/MRGG/CNSESH_STOCK/2024/2024-4/2024-04-30/10161232.PDF

- notes: hard negative 原因：当时“GPU到货+算力租赁”很像扩张起点，但后验显示合同终止与回款/交付不确定性高，缺乏多源证据证明其改变行业硬约束或供需拐点。
---
## news_id: CNDC-2024-05-003
- domain: 数据中心
- initial_report_date: 2024-05-07
- title: 海南华铁公告拟投资10亿元建设智算中心，布局算力租赁业务
- label: NotMajor
- hard_negative: true
- summary: 单公司宣布大额投资切入智算租赁，市场易解读为重大利好，但后续更多体现公司层面执行与合规风险，难外推为行业结构变化。

- axes_and_direction:
  - pace: uncertain
  - cost: mixed
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 后验多家权威来源聚焦其后续大额算力订单终止与监管/立案事件，反映跨界算力业务的信息披露与订单真实性/可执行性风险；该链条主要改变的是公司个体预期，而非行业层面的电力接入、并网或成本曲线。
- observable_features_at_time:
  - 投资金额：披露拟投资规模（10亿元）用于智算业务（以公告为准）
  - 商业模式：GPU级算力资源租赁+增值技术服务（以公告为准）
  - 约束类型：设备采购与交付、组网调试、运维能力、客户获取与合同履约
  - 影响范围：单公司项目（未披露跨地区电力/并网批复）
  - 证据等级：公司披露（公告）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体/立案通报 | 2025-10-16 | https://www.news.cn/local/20251016/ae1f770e7358425599c2a090edffb07a/c.html | 描述大额算力协议终止引发质疑并导致监管核查与立案，体现信息披露与订单执行风险
  - 权威财经媒体/监管关注 | 2025-10-12 | https://www.stcn.com/article/detail/3375012.html | 追踪大额合同终止后的监管工作函与市场质疑，强调“订单/披露”层面风险而非行业硬约束变化

- sources (初报与当时材料):
  - initial_report: https://file.finance.sina.com.cn/211.154.219.97%3A9494/MRGG/CNSESH_STOCK/2024/2024-5/2024-05-07/10188254.PDF
  - time_slice_supporting: https://file.finance.sina.com.cn/211.154.219.97%3A9494/MRGG/CNSESH_STOCK/2024/2024-5/2024-05-07/10188254.PDF

- notes: hard negative 原因：后验关注点集中在个体订单终止与合规风险，缺少≥2个“独立行业来源”确认其改变装机/投运节奏或供电硬约束。
---
## news_id: CNDC-2024-06-002
- domain: 数据中心
- initial_report_date: 2024-06-11
- title: 鸿博股份算力业务合同履约不及预期引发股价与舆论震荡（多份算力合同延期/不确定）
- label: NotMajor
- hard_negative: true
- summary: 事件热度高、被视为算力供给扩张信号，但后续更多体现单公司合同执行与设备供应风险，行业层面影响不足。

- axes_and_direction:
  - pace: uncertain
  - cost: mixed
  - constraint: tighten
  - supply_demand: uncertain

- subsequent_impact_path: 后验公告与报道显示其相关智算中心采购合同出现金额下修、交付延期与违约金等调整，体现“设备供应/履约条款/资金压力”对单项目的约束；该事件未被多源描述为引发行业层面的装机/投运拐点，更像是算力租赁周期波动下的公司个体案例。
- observable_features_at_time:
  - 当时披露信号：多份AI算力合同金额大、履约期限长（细节以当时公告/报道为准）
  - 约束类型：高端芯片与GPU服务器供给、调试复杂度、合同执行不确定性
  - 影响范围：单公司/单项目链条（未披露跨公用事业电力保障变化）
  - 证据等级：权威财经媒体深度报道
  - 可复用信号：合同执行延后原因归因（供应受限/外部环境变化）与风险提示语言
  - Unknown：对行业MW投运或电网接入指标无直接披露

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 上市公司公告被媒体转述 | 2024-12-04 | https://www.nbd.com.cn/articles/2024-12-04/3672092.html | 披露原合同金额调整、违约金与交付/验收安排变化，体现履约与供应约束
  - 权威媒体深度 | 2024-12-05 | https://finance.sina.com.cn/jjxw/2024-12-05/doc-incymitn9641863.shtml | 梳理合同“缩水”、违约金与履约不确定性，强化其为公司层面风险事件

- sources (初报与当时材料):
  - initial_report: https://finance.sina.cn/2024-06-11/detail-inayipeh9343512.d.html?vt=4
  - time_slice_supporting: https://www.21jingji.com/article/20240611/herald/0d529f240a7bca72bb319e607425ea57.html

- notes: hard negative 原因：后验证据集中在合同调整与履约风险，不满足“多源确认其改变行业硬约束/投运节奏”的门槛。
---
## news_id: CNDC-2024-04-004
- domain: 数据中心
- initial_report_date: 2024-04-14
- title: 中贝通信大额算力合同引发“真实性/信披充分性”争议（市场高度关注）
- label: NotMajor
- hard_negative: true
- summary: 当时“亿元级算力合同”容易被解读为行业景气拐点，但后续显示更多是单公司订单与披露争议，缺乏行业级影响确认。

- axes_and_direction:
  - pace: uncertain
  - cost: mixed
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 后验年度报告披露相关算力合同执行进展与交付节奏，呈现为公司层面订单管理问题；在行业层面未出现多家独立来源将该事件与电力接入/并网约束或全国装机节奏变化直接绑定的持续叙事。
- observable_features_at_time:
  - 合同要素：披露金额、期限与交付/支付安排（以公告为准；争议点在于可核验信息充分性）
  - 约束类型：设备采购与现金流压力、交付验收与客户支付、信披与合规风险
  - 影响范围：单公司/单客户合同，不构成跨区域硬约束变化
  - 证据等级：财经媒体质疑报道（当期）
  - 可复用信号：媒体对合同条款、交易对手、履约可行性的集中审视

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 公司披露/年度报告 | 2025-04-25 | https://static.cninfo.com.cn/finalpage/2025-04-25/1223284223.PDF | 在年度报告中集中披露已公告算力合同的执行情况与交付推迟原因，显示其为公司层面订单执行事项
  - 财经媒体质疑 | 2024-04-14 | https://wap.eastmoney.com/a/202404133043107798.html | 对大额合同的可核验性与信息披露充分性提出质疑（当期“像重大”的典型特征）

- sources (初报与当时材料):
  - initial_report: https://wap.eastmoney.com/a/202404133043107798.html
  - time_slice_supporting: https://notice.10jqka.com.cn/api/pdf/9ed0d163a10ba4f0.pdf

- notes: hard negative 原因：后验材料主要来自公司自身披露，缺乏≥2个独立行业来源确认其对装机/投运节奏或供电硬约束产生持续影响。
---
## news_id: CNDC-2024-06-003
- domain: 数据中心
- initial_report_date: 2024-06-06
- title: 云天励飞披露与德元方惠签署AI算力运营合作框架协议（4000PFLOPS规模引发关注）
- label: NotMajor
- hard_negative: true
- summary: 合同规模叙事在当时“很像重大”，但后验更多体现单公司项目推进与财务/设备风险提示，未形成行业级变量改变的多源确认。

- axes_and_direction:
  - pace: uncertain
  - cost: mixed
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 后验进展公告显示项目按合同推进并伴随费用调整/验收节奏等具体执行问题；但该事件主要是企业算力运营订单，不直接等同于新增机架/电力接入等硬约束变化，且缺少系统运营商/公用事业/监管口径将其上升为行业拐点的持续确认。
- observable_features_at_time:
  - 变化量：披露总算力规模（PFLOPS口径）与预期服务收入（以公告为准）
  - 约束类型：设备采购与交付、验收、融资与财务费用、客户履约
  - 影响范围：单一合作对手方+单公司项目
  - 证据等级：公司公告+财经媒体快讯
  - 可复用信号：公告中对设备供应风险、履约及违约风险的系统性风险提示语言

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 公司披露/项目进展公告 | 2024-11-05 | https://file.finance.sina.com.cn/211.154.219.97%3A9494/MRGG/CNSESH_STOCK/2024/2024-11/2024-11-05/10576707.PDF | 披露项目交付与验收进展及费用调整，体现其为企业级算力运营项目
  - 公司披露/项目进展公告 | 2025-04-03 | https://qxb-pdf-osscache.qixin.com/AnBaseinfo/706c5f3175bb1fdc5c37fb0dc210da17.pdf | 进一步披露合同推进情况与服务起算安排，仍主要是公司项目层面信息

- sources (初报与当时材料):
  - initial_report: https://www.stcn.com/article/detail/1224811.html
  - time_slice_supporting: https://file.finance.sina.com.cn/211.154.219.97%3A9494/MRGG/CNSESH_STOCK/2024/2024-6/2024-06-07/10263232.PDF

- notes: hard negative 原因：后验“独立来源”基本局限于公司披露与财经转述，缺少行业硬约束/投运节奏层面的持续多源确认。
---
## news_id: CNDC-2024-06-004
- domain: 数据中心
- initial_report_date: 2024-06-29
- title: 2024中国绿色算力（人工智能）大会在内蒙古召开（以会带产、以会聚企）
- label: Unlabeled
- hard_negative: false
- summary: 会议级事件可能是产业动员信号，但难以稳定判断其是否带来可验证的硬约束变化或投运拐点。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 未能在不依赖过度推断的情况下，找到≥2个独立来源在较长时间后明确将“该次大会本身”与行业装机/投运节奏或供电约束变化建立因果链条，因此暂不标注。
- observable_features_at_time:
  - 事件类型：大会召开与政策/产业议题集中发布（内容以报道为准）
  - 影响路径可能性：更多偏“招商与产业宣介”，不直接等同于审批/并网/电力接入批复
  - 变化量：MW/项目清单/合同金额在报道中若未形成可核验硬信息则 Unknown
  - 证据等级：权威媒体报道

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - Unknown | Unknown | Unknown | 未能找到满足“≥3–6个月后、≥2个独立来源明确确认影响”的材料

- sources (初报与当时材料):
  - initial_report: https://www.nmg.xinhuanet.com/20240629/0c7a2514f986462d977e3e051ab4b94f/c.html
  - time_slice_supporting: https://local.cctv.com/2024/06/21/ARTIur4S4IHvWTFQRVKWiWRI240621.shtml

- notes: 可能存在“热度代理风险”（会议报道传播广），但缺少可复用的硬约束字段与后验多源确认，因此列为未标注。
---
## news_id: CNDC-2024-05-004
- domain: 数据中心
- initial_report_date: 2024-05-11
- title: 国家发改委部署重点用能单位能效诊断（覆盖高能耗领域，可能触达数据中心）
- label: Unlabeled
- hard_negative: false
- summary: 能效诊断是潜在硬约束工具，但该通知面向“重点用能单位”广泛行业，难直接映射到数据中心装机/投运节奏变化。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 该政策工具可能通过监察与改造储备影响用能约束，但未能在后验检索中稳定获得“将该通知与数据中心行业变量变化直接挂钩”的多源因果链条，暂不标注。
- observable_features_at_time:
  - 政策性质：国家层面工作通知，目标指向能效诊断与监察覆盖率（以原文为准）
  - 约束类型：节能监察/改造项目储备清单（机制存在，但对数据中心是否为主要抓手需额外证据）
  - 变化量：未直接给出数据中心MW/机架/PUE硬指标（需以行业配套文件确认）
  - 证据等级：中央部门正式通知

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - Unknown | Unknown | Unknown | 未能找到满足“≥3–6个月后、≥2个独立来源明确确认影响”的材料

- sources (初报与当时材料):
  - initial_report: https://www.ndrc.gov.cn/xwdt/tzgg/202405/t20240511_1382115.html
  - time_slice_supporting: Unknown

- notes: 该条更可能作为后续更聚焦的数据中心专项行动/标准的“前置治理工具”，但仅凭本通知难以形成稳定标注。
---

# 数据中心-中国-2024Q3

---
## news_id: CNDC-2024-07-001
- domain: 数据中心
- initial_report_date: 2024-07-23
- title: 发改委等四部门印发《数据中心绿色低碳发展专项行动计划》（发改环资〔2024〕970号）
- label: Major
- hard_negative: false
- summary: 国家层面把“上架率、PUE、绿电比例”等硬指标制度化，直接影响新建准入与存量改造路径。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: 后续政策与行业评价体系将该《行动计划》作为约束框架：一方面将“国家枢纽节点新建数据中心绿电消费比例”纳入后续年度监测口径，强化用能约束；另一方面绿色数据中心评价指标体系继续强调PUE、上架率、绿电等指标，推动存量改造与新建准入趋严。
- observable_features_at_time:
  - 明确提出到2025/2030的阶段性目标框架（方向性约束明确，具体项目落地需地方细则与审批）。
  - 将“上架率（利用率）”写入规划约束：对低上架率地区新增大型/超大型项目提出限制性表述。
  - 对新建/改扩建大型与国家枢纽节点项目提出更严格的能效（PUE）要求（规则条款型信号）。
  - 明确“用能设备更新/节能降碳改造”是重点任务，意味着CAPEX结构可能上移至高效供配电、制冷、能碳管理等环节。
  - 将“可再生能源利用（含绿电/直供探索）”作为核心抓手之一，指向电力合同/交易机制的重要性提升。
  - 约束类型：能耗/能效（PUE）、上架率、绿电利用、节水与水效、布局（优先枢纽节点）、设备更新。
  - 影响范围：全国（各省发改/工信/能源/数据管理机构均为执行主体），跨区域与跨供电侧。
  - 证据等级：监管部门联合发文（最高）。

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管/权威发布 | 2025-07-23 | https://www.news.cn/energy/20250723/ef8b6f61e83c4ced9b81b5cb17ad025f/c.html | 后续文件在年度口径中引用《行动计划》，并将“国家枢纽节点新建数据中心绿电消费比例”纳入监测要求，体现约束落地到用能侧。
  - 权威机构年度报告 | 2025-11-30 | https://www.cac.gov.cn/cms/pub/interact/downloadfile.jsp?fText=%E6%95%B0%E5%AD%97%E5%8C%96%E7%BB%BF%E8%89%B2%E5%8C%96%E5%8D%8F%E5%90%8C%E8%BD%AC%E5%9E%8B%E5%8F%91%E5%B1%95%E6%8A%A5%E5%91%8A%EF%BC%882025%EF%BC%89&filepath=ZBWvETi1XzcBKtOIkqelkKyZubXJ7XhTtEum6u4y3J0JlNefDligM1XYyprdiboOnswF1rKyF1%2Fz6NGp9PsSoDEjTcORl73kmCTdYOvdSjs%3D | 在更大“数字化绿色化协同转型”框架下点名该行动计划，作为推动数据中心绿色化改造与设备更新的关键政策抓手之一。
  - 行业评价体系/标准化文件 | 2025-08-01 | https://kcycrawlerfile.oss-cn-beijing.aliyuncs.com/2025/08/01/P020250801608724540243.pdf | 国家级绿色数据中心评价指标体系继续以PUE、绿电/储能、上架率等为核心，体现政策目标被固化为评价与激励约束工具。

- sources (初报与当时材料):
  - initial_report: https://www.ndrc.gov.cn/xxgk/zcfb/tz/202407/t20240723_1391894.html
  - time_slice_supporting: https://www.ndrc.gov.cn/xwdt/tzgg/202407/P020240723625616053849.pdf, https://www.ndrc.gov.cn/fggz/fgzy/xmtjd/202407/t20240730_1392078.html, https://www.news.cn/energy/20240725/2256950d364e4b7c8579a9466c0b1811/c.html

- notes: 该条为“硬约束型”国家政策，重大性来自其可执行条款（上架率、能效、布局、绿电）而非传播热度；但实际影响强度取决于地方节能审查、用能指标与电力交易机制的联动执行力度。
---

---
## news_id: CNDC-2024-07-002
- domain: 数据中心
- initial_report_date: 2024-07-12
- title: 国内首个“算力互联公共服务平台”发布（信通院/算力互联互通）
- label: Major
- hard_negative: false
- summary: 以“算力标识注册、资源查询与互联互通”为抓手，推动全国算力资源可发现、可度量、可对接。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 后续报道显示平台能力持续迭代并服务“找算力/调度/标识注册”等关键环节，推动算力资源从“孤岛”走向可发现与可交易，间接降低跨主体调用摩擦并改善供需匹配效率（机制层面）。
- observable_features_at_time:
  - 初报明确“公共服务平台”定位：面向全国范围算力资源的标识注册与测试/查询等公共能力（规则/平台型信号）。
  - 重点信号是“互联互通”与“标识体系”，指向跨主体调度的制度与技术底座，而非单一项目扩建。
  - 变化量：初报未给出可核验的资源规模、覆盖主体数量等，记为 Unknown。
  - 约束类型：调度与互联互通标准/标识、跨主体资源发现、供需匹配摩擦（“软约束”）。
  - 影响范围：潜在全国性（但当时落地范围/接入主体需后续验证）。
  - 证据等级：权威媒体报道+国家级研究机构牵头（高）。
  - 可复用信号：是否提供“标识注册/能力测试/资源查询”等功能模块；是否提及全国一体化算力体系支撑。

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体/科技资讯 | 2025-02-10 | https://finance.sina.com.cn/tech/digi/2025-02-11/doc-ineiytxf7382279.shtml | 报道平台继续扩展服务能力（面向开发者“找调用算力”等），体现平台持续运营与功能迭代。
  - 权威媒体/财经报道 | 2025-05-19 | https://finance.sina.com.cn/stock/roll/2025-05-19/doc-inewzyah8029510.shtml | 描述平台在资源标识与汇聚、按需使用等方面的进展，用于论证其对供需匹配摩擦的改善机制。

- sources (初报与当时材料):
  - initial_report: https://tv.cctv.com/2024/07/12/VIDEAqV2wj4XOoewjGCYaJ1J240712.shtml
  - time_slice_supporting: https://finance.sina.com.cn/roll/2024-07-12/doc-inccvttz7903788.shtml, https://www.cnstock.com/commonDetail/213992

- notes: 该条“重大性”来自全国性基础设施属性（标识/互联/公共服务）而不是单次项目投产；当时缺少量化覆盖数据，模型训练时应把“平台功能模块+牵头机构层级”作为核心可观测特征。
---

---
## news_id: CNDC-2024-09-001
- domain: 数据中心
- initial_report_date: 2024-09-20
- title: 北京市算力互联互通和运行服务平台上线（京津冀蒙算力协同）
- label: Major
- hard_negative: false
- summary: 以北京为枢纽推动区域算力统一对接与资源汇聚，属于“算力网络/调度/交易”方向的区域级关键基础设施。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 后续材料将该平台定位为京津冀蒙算力协同的重要抓手，并与标准化/标识体系建设相互配套，推动区域算力资源汇聚与统一服务，从机制上降低“算力孤岛”带来的配置摩擦。
- observable_features_at_time:
  - 初报明确“平台上线”这一可验证事件（上线/发布），属于基础设施层面里程碑。
  - 变化量：初报披露平台汇聚的服务商数量与算力规模（若不同报道口径不一致则以初报为准；模型特征可记录“有明确规模披露/无披露”）。
  - 约束类型：互联互通与运行服务（资源对接、运行监测、统一服务），属于“软硬结合”的约束缓解。
  - 影响范围：区域级（京津冀蒙协同），但具有示范扩散潜力。
  - 证据等级：地方主管部门/平台运营主体/权威媒体报道（较高）。
  - 可复用信号：是否提及“互联互通、运行服务、汇聚供给侧主体、统一服务入口”。
  - 可复用信号：是否与“标准/标识/SLA”配套发布（提升可执行性）。

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体 | 2025-02-07 | https://cn.chinadaily.com.cn/a/202502/07/WS67a59a40a310be53ce3f468f.html | 将平台上线作为区域算力协同的重要进展，并强调标准化与统一市场建设方向（机制确认）。
  - 平台运营主体/公司披露 | 2025-02-11 | https://www.behc.com.cn/newsInfo_8c4fc03da1f240d9bccbfe22178cc2ef.html | 从运营方视角总结平台上线后的协同与标准化推进（对区域协同“可运行”路径的补强确认）。

- sources (初报与当时材料):
  - initial_report: https://bj.people.com.cn/n2/2024/0920/c349239-40983042.html
  - time_slice_supporting: https://www.behc.com.cn/newsInfo_e127b0f25a704d87bc81812018f5fd6b.html, https://www.sedind.com/news/info/1010

- notes: 与全国性平台相比，该条的关键在“区域协同可运行”与“示范效应”；可作为训练样本区分“平台上线（可执行）”与“规划/倡议（不可验证）”。
---

---
## news_id: CNDC-2024-09-002
- domain: 数据中心
- initial_report_date: 2024-09-19
- title: 《北京市算力服务等级协议（SLA）标准》发布（北京互联网大会相关发布）
- label: Major
- hard_negative: false
- summary: 以SLA标准把算力服务质量指标制度化，为平台化汇聚与交易提供“可度量、可比较”的规则底座。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 后续材料将“算力SLA标准+平台上线”并列为北京算力互联互通体系的重要组成部分，并与“统一标识/标准化管理”相连，支撑算力服务从“项目交付”向“标准化供给与统一市场”演进。
- observable_features_at_time:
  - 初报为“标准发布”事件（可验证），属于规则侧硬化：把服务范围、服务内容、关键指标体系明确化。
  - 变化量：标准文本具体指标阈值在初报未完整披露则记为 Unknown（训练时可用“是否发布标准/是否解读指标框架”）。
  - 约束类型：服务质量与可度量性约束（SLA），为互联互通与交易撮合提供基础。
  - 影响范围：北京为主，但可外溢为其他地区参考模板。
  - 证据等级：行业组织/大会官方发布+权威媒体转载（中高）。
  - 可复用信号：是否出现“SLA/服务等级/指标体系/标准发布/解读”等关键词。
  - 可复用信号：是否与“算力互联互通平台”同场发布（强化落地性）。

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体 | 2025-02-07 | https://cn.chinadaily.com.cn/a/202502/07/WS67a59a40a310be53ce3f468f.html | 将SLA标准与算力标识等标准化工作并列，强调其对统一管理与市场规范的支撑作用（机制确认）。
  - 平台运营主体/公司披露 | 2025-02-11 | https://www.behc.com.cn/newsInfo_8c4fc03da1f240d9bccbfe22178cc2ef.html | 回顾标准落地发布并关联“算力标识注册解析”等实践，说明标准化是互联互通推进路径的重要部分。

- sources (初报与当时材料):
  - initial_report: https://m.bjcia.org.cn/68/202409/19949.html
  - time_slice_supporting: https://www.ce.cn/xwzx/gnsz/gdxw/202409/20/t20240920_39145911.shtml, https://m.bjcia.org.cn/72/202409/20008.html

- notes: 该条本质是“规则基础设施”，重大性不在短期新增机柜/服务器，而在“可度量、可交易”的制度底座；训练时应区分“发布标准（可执行）”与“提出倡议（弱信号）”。
---

## news_id: CNDC-2024-09-003
- domain: 数据中心
- initial_report_date: 2024-09-30
- title: 中国算力服务平台（公测版）上线（2024中国算力大会相关发布）
- label: Major
- hard_negative: false
- summary: 国家级算力供需服务平台雏形形成，目标是“资源一本账、监测一张网、匹配一站式、决策一盘棋”。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 后续报道显示该平台持续推进省级分平台接入与“供-需-服”一体化服务生态建设，强化全国算力资源的可发现、可匹配与跨域协同能力，属于影响行业运行效率的关键基础设施路径。
- observable_features_at_time:
  - 初报为“平台上线（公测）”事件（可验证），属于基础设施层里程碑。
  - 明确建设目标与功能框架（供需服三位一体、登记/监测/匹配/生态共享），可作为强特征。
  - 变化量：初报通常不提供完整全国接入规模（记为 Unknown 或以初报披露为准）。
  - 约束类型：供需信息不全、调度协同不足、资源孤岛（软约束）——平台尝试缓解。
  - 影响范围：全国性（由国家级机构推动），并可与省级平台联动。
  - 证据等级：行业机构/大会发布（中高）。
  - 可复用信号：是否明确“公测版、全国一体化算力网、供需匹配、监测、生态共享”。

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体 | 2025-08-25 | https://www.news.cn/tech/20250825/dcc1eb5c1aed4c66b638653c856eb656/c.html | 报道平台在后续年度实现多省分平台接入并“全面贯通”，用于确认其持续推进与全国协同方向。
  - 政府权威发布 | 2025-09-04 | https://www.szzg.gov.cn/2025/xwzx/qwfb/202509/t20250904_5073458.htm | 以权威发布形式介绍平台运营进展与服务生态，验证平台作为国家级综合性算力服务平台的持续建设与使用场景扩展。

- sources (初报与当时材料):
  - initial_report: https://www.odcc.org.cn/news/p-1840563266093146113.html
  - time_slice_supporting: https://m.c114.com.cn/w15-1274663.html, https://hcp.caict.ac.cn/

- notes: 与单点“智算中心投产”不同，这类平台型新闻对行业变量的影响更偏“供需匹配效率/跨域调度可行性”；训练时可把“国家级平台+明确功能框架+后续贯通”作为重大新闻特征组合。
---

## news_id: CNDC-2024-09-004
- domain: 数据中心
- initial_report_date: 2024-09-10
- title: 太和水突获3.43亿元AI算力服务器大单，上交所火速问询
- label: NotMajor
- hard_negative: true
- summary: 事件热度高但本质是单一公司贸易/订单事件，后续围绕回款与合规争议，未形成行业层面硬约束变化。

- axes_and_direction:
  - pace: uncertain
  - cost: mixed
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 后续披露与报道聚焦交易所问询、合同履约与回款/诉讼问题，事件影响主要停留在公司层面合规与财务风险，并未被独立来源持续确认会改变全国/区域数据中心投运节奏、并网约束或成本结构。
- observable_features_at_time:
  - 变化量：合同金额“亿元级”、交付窗口“数周级”（具体以初报为准），容易被误读为“行业景气拐点”信号。
  - 交易对手资质与履约能力在初报材料中信息不充分（可复用信号：注册资本/实缴/参保人数等是否披露）。
  - 约束类型：更多是公司资金、供应链交付、合规披露风险；非电力接入/能耗指标/并网审批等行业硬约束。
  - 影响范围：单一公司/单一客户（跨区域影响 Unknown）。
  - 证据等级：上市公司公告+交易所问询（强），但行业外溢证据弱。
  - 可复用信号：跨界公司突然拿到大单、交易所快速问询、子公司成立时间短。
  - 可复用信号：合同是否为设备采购/贸易属性而非数据中心投运与并网关键节点。

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体深度 | 2025-02-25 | https://www.nbd.com.cn/articles/2025-02-25/3765186.html | 梳理问询与疑点，强调事件争议集中在履约与财务风险，不支持“行业结构性影响”的判断。
  - 权威媒体跟踪 | 2025-12-13 | https://wap.eastmoney.com/a/202512133590841192.html | 报道回款与诉讼进展，进一步表明事件主要是公司个案风险演化。

- sources (初报与当时材料):
  - initial_report: https://stcn.com/article/detail/1315769.html
  - time_slice_supporting: https://www.moomoo.com/news/post/43456863, https://news.qq.com/rain/a/20241007A07O6P00

- notes: hard_negative 的核心理由=“像重大（金额大/热度高/交易所问询）”但后续证据链指向公司个案合规与回款风险，而非行业硬约束或供需拐点；适合作为训练集中的“热度陷阱”样本。
---

## news_id: CNDC-2024-08-001
- domain: 数据中心
- initial_report_date: 2024-08-29
- title: 奥雅股份重大合同变更：算力服务器采购数量由128台变更为8台
- label: NotMajor
- hard_negative: true
- summary: 从“拟大规模采购”迅速收缩为小规模交付，反映公司层面项目不确定性，难以支撑行业层面趋势判断。

- axes_and_direction:
  - pace: delay
  - cost: mixed
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 后续公告显示交易调整与后续进展仍围绕单一合同变更与结算安排展开，体现“跨界智算/算力租赁”在公司层面的执行不确定性；未见独立来源将其与行业装机、并网或能耗约束的结构性变化相联系。
- observable_features_at_time:
  - 变化量：采购数量从“百台级”骤降到“个位数台级”，是强烈的“计划收缩/需求或资金变化”信号。
  - 合同属性为“服务器采购/供货”，与数据中心投运的电力接入、许可审批链条不同。
  - 初报强调“不会对公司财务经营造成重大不利影响”（可复用信号：公司自述风险口径）。
  - 约束类型：资金安排、供货与合同条款协商；非电网并网/能耗指标等硬约束。
  - 影响范围：单一公司与单一供应链合同，外溢性弱。
  - 证据等级：上市公司公告（强）。
  - 可复用信号：大额/大规模采购计划快速收缩（典型“算力主题炒作-落地收缩”模式）。

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 公司披露/进展公告 | 2025-04-03 | https://file.finance.sina.com.cn/211.154.219.97%3A9494/MRGG/CNSESZ_STOCK/2025/2025-4/2025-04-03/10848015.PDF | 后续以“补充协议/余额付款”等方式推进，仍是公司个案合同执行与结算问题。
  - 公司定期报告 | 2025-08-26 | https://static.cninfo.com.cn/finalpage/2025-08-20/1224516818.pdf | 定期报告继续披露该合同补充协议相关事项，未呈现行业层面外溢影响链条。

- sources (初报与当时材料):
  - initial_report: https://file.finance.sina.com.cn/211.154.219.97%3A9494/MRGG/CNSESZ_STOCK/2024/2024-8/2024-08-29/10440995.PDF
  - time_slice_supporting: https://stcn.com/article/detail/1301395.html, https://static.cninfo.com.cn/finalpage/2024-08-29/1221030168.PDF

- notes: hard_negative 理由=“当时像重大（英伟达GPU/大规模采购）”但短期内大幅缩量，后续也未被多源确认对行业变量产生长期影响；更像公司层面的试错与收缩。
---

## news_id: CNDC-2024-08-002
- domain: 数据中心
- initial_report_date: 2024-08-29
- title: 迈信林披露2024年半年度报告：算力相关业务仍在投资建设与订单导入阶段
- label: NotMajor
- hard_negative: true
- summary: “算力租赁/智算”作为新增业务仍处早期导入，后续监管关注与风险提示主要落在公司经营不确定性，未构成行业结构性变量变化。

- axes_and_direction:
  - pace: uncertain
  - cost: mixed
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 后续公司年报与监管相关材料强调算力租赁业务的不确定性与竞争/回款风险，反映其更多是公司层面的业务探索；缺乏多源证据表明其改变了行业装机投运、并网约束或成本结构。
- observable_features_at_time:
  - 初报信号为“仍在建设与订单导入”（落地不确定性高）。
  - 变化量：半年度报告未提供可稳定外推的行业级新增算力/投运窗口（记为 Unknown 或仅公司口径）。
  - 约束类型：公司资金、设备采购交付、客户导入与资质办理等。
  - 影响范围：单一公司。
  - 证据等级：上市公司定期报告（强）。
  - 可复用信号：传统主业公司跨界算力、处于“导入/试运营”阶段。
  - 可复用信号：后续是否出现交易所问询/风险提示（作为负例识别特征）。

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 公司定期报告/风险披露 | 2025-04-26 | https://static.cninfo.com.cn/finalpage/2025-04-26/1223316353.PDF | 年报披露算力租赁业务业绩不确定性等风险，提示其仍是公司层面不确定业务线。
  - 交易所监管问询/回复材料 | 2025-07-02 | https://star.sse.com.cn/disclosure/listedinfo/announcement/c/new/2025-07-02/688685_20250702_1U7H.pdf | 问询/回复材料聚焦应收、客户、业务模式等披露问题，反映监管关注点在公司披露与经营风险而非行业结构变化。

- sources (初报与当时材料):
  - initial_report: https://star.sse.com.cn/disclosure/listedinfo/announcement/c/new/2024-08-29/688685_20240829_H7YG.pdf
  - time_slice_supporting: https://star.sse.com.cn/disclosure/listedinfo/announcement/c/new/2024-07-06/688685_20240706_PGC8.pdf

- notes: hard_negative 理由=“当时易被当作算力扩张信号”但证据链主要停留在公司早期导入与监管披露层面；未满足“多源确认长期影响行业变量”的门槛。
---

---
## news_id: CNDC-2024-07-003
- domain: 数据中心
- initial_report_date: 2024-07-29
- title: 中贝通信半年报披露：智算中心全国布局、累计算力规模“破万P”等表述引关注
- label: NotMajor
- hard_negative: true
- summary: 公司层面扩张叙事强，但后续监管问询聚焦收入结构与披露，难以证明其改变行业硬约束或形成全国性供需拐点。

- axes_and_direction:
  - pace: uncertain
  - cost: mixed
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 后续披露材料围绕智算业务收入分布、增长可持续性与信息披露问题展开，说明该新闻更像公司经营事件；缺少独立来源持续确认其对行业装机投运节奏、并网/供电约束或成本结构产生长期影响。
- observable_features_at_time:
  - 初报包含“全国布局/算力规模”等强叙事词（易被误判为行业供给拐点）。
  - 变化量：公司披露口径的算力规模/采购金额等（训练特征可记录“是否给出规模数字/是否仅公司口径”）。
  - 约束类型：更多是公司采购交付、机房资源、客户导入与商业化能力。
  - 影响范围：单一公司（跨区域项目是否影响全国供需 Unknown）。
  - 证据等级：权威媒体转述公司定期报告（中高）。
  - 可复用信号：公司披露“累计规模很大”但缺少行业层面多源验证。
  - 可复用信号：后续若出现交易所问询/独立董事意见等，倾向负例。

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 交易所问询相关材料 | 2025-07-11 | https://static.cninfo.com.cn/finalpage/2025-07-12/1224145772.PDF | 独立董事意见针对交易所问询函作出回应，显示监管关注点在披露与经营表现解释，并不构成行业变量的多源确认。
  - 公司披露/问询回复 | 2025-07-12 | https://static.cninfo.com.cn/finalpage/2025-07-12/1224145773.PDF | 回复材料继续围绕收入列示与披露问题，体现“公司事件”属性更强。

- sources (初报与当时材料):
  - initial_report: https://stcn.com/article/detail/1272374.html
  - time_slice_supporting: https://pdf.dfcfw.com/pdf/H2_AN202402061620961843_1.pdf?1707242495000.pdf=

- notes: hard_negative 理由=“当时像重大（规模叙事强）”但后续证据主要来自公司与监管问询材料，缺少独立来源对行业长期变量影响的确认。
---

---
## news_id: CNDC-2024-07-004
- domain: 数据中心
- initial_report_date: 2024-07-01
- title: 云天励飞披露AI算力运营项目服务合同：年服务费超5亿元（公司订单型事件）
- label: NotMajor
- hard_negative: true
- summary: 金额巨大但仍是单一公司合同履约事件；后续披露集中在验收、回款与履约风险，未上升为行业硬约束变化。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 后续进展公告与投资者交流记录强调项目交付验收、服务费结算与“回款依赖下游客户付款”等风险条款，说明该事件主要影响公司业绩与风险暴露；未见多源独立证据证明其改变行业装机/并网/用能约束或形成供需拐点。
- observable_features_at_time:
  - 变化量：初报披露“年服务费/三年期”等大额合同信息（强热度信号）。
  - 合同本质为“算力运营服务”，不等同于国家级政策或电网侧约束变化。
  - 初报未给出行业可复用的“电力接入/并网/能耗指标”变化量（记为 Unknown）。
  - 约束类型：客户付款链条、履约能力、坏账风险（公司层面）。
  - 影响范围：单一公司与其客户链条，外溢性弱。
  - 证据等级：上市公司公告/权威媒体转述（中高）。
  - 可复用信号：超大额合同 + 回款依赖条款（容易成为“看起来重大”的假信号）。

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 公司披露/进展公告 | 2025-04-03 | https://qxb-pdf-osscache.qixin.com/AnBaseinfo/706c5f3175bb1fdc5c37fb0dc210da17.pdf | 进展公告披露验收与回款，同时明确“服务费回收以前端客户付款为前提”等风险，表明影响仍局限在公司履约链条。
  - 投资者关系记录 | 2025-05-13 | https://file.finance.qq.com/finance/hs/pdf/2025/05/13/cd00c6a02fcc11f0a3c6fa163e39923a.pdf | 投资者交流继续围绕合同交付与收入贡献预期，未形成行业层面的多源结构性影响确认。

- sources (初报与当时材料):
  - initial_report: https://www.stcn.com/article/detail/1245914.html
  - time_slice_supporting: https://epaper.zqrb.cn/html/2024-06/07/content_1056849.htm?div=-1

- notes: hard_negative 理由=“金额/叙事极像行业景气”但证据链主要来自公司自身披露与合同条款风险，缺少跨机构、跨地区的行业变量影响确认；适合作为“单一大单≠行业重大”训练负例。
---

## news_id: CNDC-2024-07-005
- domain: 数据中心
- initial_report_date: 2024-07-22
- title: 国新办“国家数据局”主题发布会披露算力/数据中心阶段性进展（口径型信息）
- label: Unlabeled
- hard_negative: false
- summary: 属于阶段性进展口径与宣传信息，是否构成可执行硬约束变化需要进一步多源验证。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 未找到足够多的独立后验来源，将该次发布会内容与“长期改变行业硬约束/供需拐点”直接挂钩（更多作为背景信息被引用）。
- observable_features_at_time:
  - 事件类型：权威发布会（信息权威但多为口径性总结）。
  - 变化量：发布会提及的指标口径与统计范围可能与后续口径不同（训练需谨慎）。
  - 约束类型：多为政策执行进展描述，缺少新增硬条款。
  - 影响范围：全国口径，但对项目侧/电力侧可操作性不明确。
  - 证据等级：官方发布会（高）。
  - 可复用信号：是否出现可执行条款/硬门槛（本条初报不突出）。
  - 可复用信号：是否同步发布文件/通知编号（本条无）。

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - Unlabeled：不满足“≥2个独立来源明确描述其对行业变量长期影响”的门槛，故不列为Major/NotMajor。

- sources (初报与当时材料):
  - initial_report: https://www.scio.gov.cn/live/2024/34328/index.html
  - time_slice_supporting: https://www.ndrc.gov.cn/xxgk/zcfb/tz/202407/t20240723_1391894.html

- notes: 若你希望把“发布会口径类”系统性纳入训练，可单独设立一个标签（如 InfoOnly）或把它们作为弱监督特征来源，而非直接与Major/NotMajor混标。
---

# 数据中心-中国-2024Q4

---
## news_id: CNDC-2024-10-001
- domain: 数据中心
- initial_report_date: 2024-10-30
- title: 《关于大力实施可再生能源替代行动的指导意见》发布，明确支持数据中心等新基建提升可再生能源使用比例、探索绿电直供/源网荷储
- label: Major
- hard_negative: false
- summary: 国家层面将数据中心纳入可再生能源替代重点场景，推动绿电直供、源网荷储与绿证交易等机制，强化“算力×电力”协同方向。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: loosen
  - supply_demand: mixed

- subsequent_impact_path: 后续政策与答复中反复将“国家枢纽节点新建数据中心”纳入绿电消费比例与绿证核算等机制，推动数据中心绿电占比由“倡导”向“更刚性约束/考核口径”演进，影响项目选址与用电方案设计（直供、多源互补、源荷互动、储能配置等）。

- observable_features_at_time:
  - 政策层级：国家发展改革委发布的指导意见（国家层面顶格政策信号）
  - 适用对象：5G基站、数据中心、超算中心等“新型基础设施”（覆盖面广）
  - 关键机制：鼓励绿电直供、源网荷储一体化项目、绿证绿电交易（机制型信号）
  - 约束类型：电力来源与消纳（绿电/绿证）、用电结构优化（供电侧约束偏“松绑+导向”）
  - 量化字段：数据中心绿电比例目标（初报文本未给出具体比例→Unknown）
  - 影响范围：跨区域（枢纽节点/清洁能源富集区）、跨行业（新基建整体）
  - 可复用信号：政策条款出现“数据中心逐年稳步提升可再生能源使用比例”“支持绿电直供”等硬措辞
  - 证据等级：监管/宏观主管部门政策文本（最高）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管/宏观主管部门答复 | 2025-11-20 | https://www.ndrc.gov.cn/xxgk/jianyitianfuwen/qgzxwytafwgk/202511/t20251120_1401771.html | 在后续答复中持续引用并延展算电协同、绿证核算与对“国家枢纽节点新建数据中心”的绿电消费约束口径
  - 监管/系统运营相关部门答复 | 2025-12-18 | https://www.nea.gov.cn/20251218/788e532f12a1442bb8685998d8ded424/c.html | 明确提到对“国家枢纽节点新建数据中心”等提出绿色电力消费比例目标并使用绿证核算，强化刚性约束属性
  - 监管机构/主管部门文章 | 2025-03-18 | https://www.nda.gov.cn/sjj/swdt/sjdt/0318/20250318212051776584737_pc.html | 总结2024年在枢纽节点与清洁能源地区部署算电协同先行先试任务（绿电直供、多源互补、源荷互动），作为政策落地路径

- sources (初报与当时材料):
  - initial_report: https://www.ndrc.gov.cn/xxgk/zcfb/tz/202410/t20241030_1394119.html
  - time_slice_supporting: https://www.nea.gov.cn/2024-10/31/c_1310787069.htm

- notes: 初报未给出对数据中心的具体量化比例/时间表，因此“当时可观测特征”以条款与机制为主；后验来源用于确认其被反复引用并向更刚性口径演进。
---
## news_id: CNDC-2024-11-001
- domain: 数据中心
- initial_report_date: 2024-11-28
- title: 国家标准《绿色数据中心评价》(GB/T 44989—2024)发布，2025-06-01实施
- label: Major
- hard_negative: false
- summary: 数据中心“绿色等级”评价标准化落地，后续被政策文件直接引用为申报/遴选门槛，成为能效与绿色化改造的统一口径。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: 标准实施后在“国家绿色数据中心推荐”等政策中被作为达标前置条件（等级、PUE等门槛），推动数据中心从“自述式绿色”转向“可核验等级”，进而影响新建与存量改造的技术路线与合规成本。

- observable_features_at_time:
  - 标准名称与编号：GB/T 44989—2024（统一口径）
  - 发布与实施：发布于2024-11-28、实施于2025-06-01（明确时间表）
  - 适用对象：绿色数据中心评价（覆盖数据中心绿色化能力）
  - 量化字段：具体评价分级/指标（初报摘要未完整展开→Unknown；需以标准正文为准）
  - 约束类型：能效/碳效/水资源与运维管理等（偏合规约束）
  - 影响范围：全国通用（国家标准），可被地方/行业政策直接引用
  - 可复用信号：后续政策文件引用“GB/T 44989—2024二级及以上”等硬门槛句式
  - 证据等级：国家标准发布平台/政策文件引用（高）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 地方主管部门政策转发/条件条款 | 2025-07-09 | https://jxj.beijing.gov.cn/jxdt/tzgg/202507/t20250709_4145496.html | 在国家绿色数据中心推荐条件中明确要求达到GB/T 44989—2024二级及以上，并与PUE/绿电等指标绑定
  - 主管部门政策文件 | 2025-07-10 | https://www.ncsti.gov.cn/kjdt/tzgg/202507/t20250710_209844.html | 国家绿色数据中心推荐工作文件中同样把GB/T 44989—2024作为达标要求之一（体现标准进入制度化门槛）
  - 标准发布信息 | 2024-11-28 | https://openstd.samr.gov.cn/bzgk/gb/newGbInfo?hcno=F532498331667E7130EEBC91BF41E59F | 给出标准发布与实施日期等基础信息

- sources (初报与当时材料):
  - initial_report: https://openstd.samr.gov.cn/bzgk/gb/newGbInfo?hcno=F532498331667E7130EEBC91BF41E59F
  - time_slice_supporting: https://www.ncsti.gov.cn/zcfg/zcwj/202507/t20250707_209599.html

- notes: 初报阶段可观测信息主要是“标准发布/实施+编号”；具体指标体系需以标准全文为准，属于“当时可公开获取材料”。
---
## news_id: CNDC-2024-11-002
- domain: 数据中心
- initial_report_date: 2024-11-26
- title: 城地香江子公司签订19.8亿元“芜湖珑腾智算互联网产业园一期项目机电工程”重大合同
- label: NotMajor
- hard_negative: true
- summary: 单一项目合同金额巨大、市场传播度高，但属于企业订单级事件；后续出现需求变更与合同范围缩减，未形成行业结构性变化。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: mixed
  - supply_demand: uncertain

- subsequent_impact_path: 项目推进受甲方需求调整影响，后续披露出现阶段/范围变更与结算调整，更多体现为单项目风险与工程交付波动，并未改变全国数据中心装机/并网约束或成本曲线。

- observable_features_at_time:
  - 变化量：合同含税金额19.8亿元（明确金额）
  - 项目性质：智算产业园一期机电工程施工总承包框架合同（工程交付型）
  - 地点：安徽芜湖（区域性）
  - 时间表：具体交付/里程碑（初报未完整披露→Unknown）
  - 约束类型：施工与设备交付、甲方需求变更（项目执行约束）
  - 影响范围：单项目/单甲方（非跨区域制度变化）
  - 证据等级：公司公告/权威财经媒体报道（公司披露为主）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体深度/行业报道 | 2026-01-15 | https://www.cb.com.cn/index/show/zj/cv/cv135341541264 | 报道指出因甲方实际需求变更导致项目后续范围/收益预期调整，体现大单“缩水”与不确定性
  - 公司披露/公告 | 2026-01-08 | https://money.finance.sina.com.cn/corp/view/vCB_AllBulletinDetail.php?id=11904575&stockid=603887 | 对前期披露重要项目进展进行更新，反映合同执行与结算变化（用于证明并非持续扩张的结构性增量）

- sources (初报与当时材料):
  - initial_report: https://gu.sina.cn/bd/hq/notice.php?annid=21280123
  - time_slice_supporting: https://www.cs.com.cn/ssgs/gsxw/202411/t20241126_6456719.html

- notes: 典型hard negative：初报金额大、容易被解读为“智算建设潮的确定性增量”，但后验仅能确认项目级波动与调整，缺乏多源证据证明其改变行业硬约束或供需拐点。
---
## news_id: CNDC-2024-11-003
- domain: 数据中心
- initial_report_date: 2024-11-29
- title: 亿田智能披露全资子公司签订1.13亿元算力服务合同（跨界算力）
- label: NotMajor
- hard_negative: true
- summary: 跨界公司签订算力服务合同在当时传播度高，但后续更多体现为公司层面的资产处置/模式调整，未形成行业结构性影响。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 后续公司披露拟处置相关资产/算力收益转让等安排，显示项目更偏“单体商业尝试+资产腾挪”，对全国数据中心投运节奏、并网约束与成本结构没有可验证的系统性影响。

- observable_features_at_time:
  - 变化量：合同金额1.13亿元（含税），服务期5年（明确）
  - 主体：甘肃亿算为客户提供算力服务及配套设施（主体与模式）
  - 关键约束：服务器采购/交付、运维与验收（项目执行约束）
  - 地域：甘肃相关主体（区域性，非全国制度）
  - 量化字段：算力规模(PF/EF)、机柜/功率（初报未给→Unknown）
  - 影响范围：单客户/单合同（非跨公用事业/跨区域）
  - 证据等级：上市公司公告/财经媒体二次传播

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 公司披露/公告 | 2025-12-08 | https://static.cninfo.com.cn/finalpage/2025-12-08/1224853364.PDF | 披露对子公司相关资产处置、算力收益转让等安排，显示业务路径发生调整
  - 权威媒体深度/行业报道 | 2025-12-10 | https://www.cb.com.cn/index/show/gs4/cv/cv12545580160 | 报道跨界算力购置与后续处置变现，说明并非形成可持续、可外推的行业增量

- sources (初报与当时材料):
  - initial_report: https://wap.eastmoney.com/a/202411293254989913.html
  - time_slice_supporting: https://static.cninfo.com.cn/finalpage/2025-12-08/1224853364.PDF

- notes: hard negative判定核心在于：缺乏≥2个独立来源在更长时间维度确认其改变行业装机/并网/成本曲线；后验更多是公司层面“跨界—调整—处置”的路径。
---
## news_id: CNDC-2024-12-001
- domain: 数据中心
- initial_report_date: 2024-12-03
- title: 平治信息四天内多次披露算力相关协议/合同（含与中兴通讯合作、算力服务合同等）
- label: NotMajor
- hard_negative: true
- summary: 多份协议在当时易被解读为“算力建设确定性放量”，但主要为企业订单与框架协议，缺乏多源证据证明其带来行业层面硬约束变化。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 后续公司定期报告确认其算力业务转型与订单积累，但主要体现单公司商业进展；未见在公开材料中被独立来源反复引用为改变全国数据中心投运节奏、电力并网约束或成本结构的关键事件。

- observable_features_at_time:
  - 变化量：披露含税金额（如2.34亿元合作协议、7408.5万元算力服务合同等；以公告/报道为准）
  - 合同类型：既有明确合同也有战略框架协议（框架协议落地时间不确定）
  - 客户类型：运营商生态相关方/地方智算主体（偏订单型）
  - 地域：涉及云南、新疆等项目方向（分散、项目型）
  - 约束类型：设备供给、交付验收、项目落地（执行约束）
  - 影响范围：单公司多合同（非全国制度调整）
  - 证据等级：公司披露+财经媒体解读

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 公司披露/定期报告 | 2025-08-29 | https://static.cninfo.com.cn/finalpage/2025-08-29/1224609742.PDF | 定期报告确认算力业务为公司主线之一，但属于企业经营层面进展，无法外推为行业结构性变量变化
  - 权威媒体深度/财经报道 | 2024-12-03 | https://www.21jingji.com/article/20241203/4527f55802a43a016e0b025da448de87.html | 报道中引用公司人员表述框架协议“何时落地尚不清楚”（用于说明当时已存在不确定性与执行风险）

- sources (初报与当时材料):
  - initial_report: https://www.21jingji.com/article/20241203/4527f55802a43a016e0b025da448de87.html
  - time_slice_supporting: https://money.finance.sina.com.cn/corp/view/vCB_AllBulletinDetail.php?id=10620851&stockid=300571

- notes: 该条作为hard negative的理由是“看起来像行业级放量，但更像订单集合”；公开后验材料更多停留在公司经营披露层面，难以满足“多源确认其改变行业变量”的门槛。
---
## news_id: CNDC-2024-10-002
- domain: 数据中心
- initial_report_date: 2024-10-22
- title: 宏景科技披露签署4.09亿元智算项目服务合同（算力/服务器/组网/服务）
- label: NotMajor
- hard_negative: true
- summary: 金额较大、叙事接近“算力基础设施放量”，但属于单公司单客户订单；后验缺乏多源证明其形成行业级硬约束变化或供需拐点。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 合同类事件的后续披露多集中在公司层面（履约风险、收入确认不确定、交易对手与交付等），未见被多家独立权威来源在更长时间维度确认其带来区域电力接入、并网规则或全国投运节奏的结构性改变。

- observable_features_at_time:
  - 变化量：合同金额4.09亿元（明确）
  - 合同内容：提供硬件资源设备、组网配套与算力相关服务（偏交付型）
  - 期限：合同期限/交付计划（初报文内以合同约定为准，摘要不完整→Unknown）
  - 约束类型：设备供货、组网联调、验收与计费（执行约束）
  - 影响范围：单客户/单合同（非跨区域/跨公用事业）
  - 可复用信号：公告反复提示“合同不构成业绩承诺、履约存在不确定性”
  - 证据等级：交易所披露文件（公司披露为主）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 公司披露/交易所文件 | 2024-10-22 | https://disc.static.szse.cn/disc/disk03/finalpage/2024-10-22/944054a9-3a8b-4d8a-963c-9bb984cce1da.PDF | 初报即提示合同对业绩影响不确定、存在履约风险（用于界定其更像订单信息而非行业硬约束事件）
  - 公司披露/交易所文件 | 2024-10-30 | https://disc.static.szse.cn/disc/disk03/finalpage/2024-10-30/4dadd975-8f47-4f14-b486-f1eb43e8c31a.PDF | 后续补充/问询回复继续强调履约、验收、计费等细节与不确定性（侧证其主要是公司经营层面波动）

- sources (初报与当时材料):
  - initial_report: https://disc.static.szse.cn/disc/disk03/finalpage/2024-10-22/944054a9-3a8b-4d8a-963c-9bb984cce1da.PDF
  - time_slice_supporting: https://disc.static.szse.cn/disc/disk03/finalpage/2024-10-30/4dadd975-8f47-4f14-b486-f1eb43e8c31a.PDF

- notes: 作为hard negative的证据强度偏弱：现有公开材料更偏“合同文本与风险提示”，缺少更长时间维度的独立来源持续确认其带来行业变量改变；因此该条更适合作为“高热度但不结构性”的负例。
---
## news_id: CNDC-2024-10-003
- domain: 数据中心
- initial_report_date: 2024-10-24
- title: 增值电信业务扩大对外开放试点工作启动，试点地区可允许外资独资经营IDC等业务
- label: Unlabeled
- hard_negative: false
- summary: 政策方向可能影响IDC市场竞争与投资主体结构，但在公开材料中暂不足以满足“多源、长期影响确认”门槛（就2024Q4 hindsight窗口而言）。

- axes_and_direction:
  - pace: mixed
  - cost: mixed
  - constraint: loosen
  - supply_demand: uncertain

- subsequent_impact_path: 理论上通过放宽外资股比限制改变市场主体准入与竞争格局，但在可检索公开材料中，尚缺少≥2个独立权威来源在更长时间维度明确描述其对数据中心投运节奏、成本结构或并网约束的长期影响链条。

- observable_features_at_time:
  - 变化量：试点地区（北京、上海、海南、深圳等）与业务清单（IDC等）明确
  - 政策性质：试点启动（非全国统一放开）
  - 约束类型：准入/股比限制放宽（制度约束“松绑”）
  - 影响范围：区域性试点（非全国）
  - 量化字段：外资新增IDC规模/投资额（初报无→Unknown）
  - 可复用信号：政策文本中出现“外资企业可独资经营IDC”等硬措辞
  - 证据等级：权威媒体报道/部门信息

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - Unlabeled：当前检索到的公开材料不足以满足“≥3–6个月后、≥2独立来源明确描述长期影响”的门槛，因此不做Major/NotMajor稳定标注。

- sources (初报与当时材料):
  - initial_report: https://www.news.cn/government/20241024/822baed8e5844bbc927df882794e649f/c.html
  - time_slice_supporting: https://www.ncsti.gov.cn/zcfg/zcwj/202404/t20240411_153292.html

- notes: 该条在当时“很像重大”，但当前可用公开证据更偏“政策宣布/解读”，缺乏后续多源对行业变量的明确、持续确认；建议后续扩大检索窗口（例如跟踪试点批复数量、外资IDC落地项目、监管评估结论）。
---
## news_id: CNDC-2024-11-004
- domain: 数据中心
- initial_report_date: 2024-11-15
- title: 北京发布《北京市存量数据中心优化工作方案（2024-2027年）》，提出PUE门槛与差别电价等措施
- label: Unlabeled
- hard_negative: false
- summary: 属于明确的地方性硬约束政策，但在本次可用检索材料中，缺少满足hindsight门槛的“多源长期影响确认”链条，因此暂不稳定标注。

- axes_and_direction:
  - pace: delay
  - cost: up
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: 政策设计上将通过PUE门槛、监测台账、改造奖励与差别电价等影响存量数据中心经营与迁移，但当前缺少≥2个独立来源在更长时间维度对其落地效果/行业外溢影响作出明确描述。

- observable_features_at_time:
  - 量化门槛：存量数据中心范围（全年用电≥500万kWh）与PUE限定值1.35（明确）
  - 工具箱：在线监测、节能监察、资金奖励、业务迁移整合、差别电价（机制明确）
  - 时间表：到2027年年均PUE≤1.35；自2026年起对PUE>1.35征收差别电价（明确）
  - 约束类型：能效合规与电价（硬约束）
  - 影响范围：北京（区域性，但对在京业务密集企业可能外溢）
  - 证据等级：地方政府/主管部门正式文件（高）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - Unlabeled：当前检索材料未能提供满足“≥3–6个月后、≥2独立来源明确描述长期影响”的证据组合，因此不稳定标注。

- sources (初报与当时材料):
  - initial_report: https://www.beijing.gov.cn/zhengce/zhengcefagui/202411/t20241115_3942264.html
  - time_slice_supporting: https://www.ncsti.gov.cn/zcfg/zcwj/202411/t20241118_186287.html

- notes: 该条“结构性影响潜力”很强，但本次对Q4的hindsight证据收集未覆盖到足够多的后续落地/评估材料（尤其是2025年中以后对整改、迁移、差别电价准备的公开跟踪），因此暂列Unlabeled而非Major。
---
## news_id: CNDC-2024-12-003
- domain: 数据中心
- initial_report_date: 2024-12-28
- title: 莲花控股披露控股孙公司签署5.55亿元高性能算力服务合同（后续解除）
- label: Unlabeled
- hard_negative: false
- summary: 后验可确认合同解除与供应链/交付不确定性，但本次检索未能稳定抓取“初报当日”的原始公告URL，导致无法按规则完成可复核标注。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 后续披露显示因服务器供应/交付计划等客观变化导致合作终止并产生补偿与诉讼等事项，体现单项目执行风险；但由于缺失初报原始链接，本条暂不进入稳定负例集。

- observable_features_at_time:
  - 变化量：合同金额约5.55亿元、服务期5年（以公司披露为准）
  - 内容：高性能算力服务与运维服务（订单型）
  - 约束类型：设备供给、交付与运维能力（执行约束）
  - 影响范围：单客户/单合同（非行业制度变化）
  - 量化字段：算力规模、交付节奏（初报细节需以原公告为准→Unknown）
  - 证据等级：公司公告/权威财经媒体复述

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威财经媒体 | 2025-04-30 | https://www.stcn.com/article/detail/1746601.html | 报道复盘合同签订与解除过程，说明“宏观政策/供货计划”等导致未能提供算力服务并解除合同
  - 公司披露/问询回复类报道 | 2026-01-31 | https://finance.sina.com.cn/roll/2026-01-31/doc-inhkcryx0218831.shtml | 汇总合同解除、设备供应与预付款回收/诉讼等事项，佐证项目级风险

- sources (初报与当时材料):
  - initial_report: (缺失：未能在当前检索结果中定位到2024-12-28原公告URL)
  - time_slice_supporting: https://www.stcn.com/article/detail/1746601.html

- notes: 按你的标注规则，必须给出“初报当日URL”；该条在后验层面证据充分，但由于缺失初报原链接，暂列Unlabeled，避免污染负例/正例集的可复核性。
---

# 数据中心-中国-2025Q1

---
## news_id: CNDC-2025-01-001
- domain: 数据中心
- initial_report_date: 2025-01-06
- title: 国家发改委/国家数据局/工信部印发《国家数据基础设施建设指引》
- label: Major
- hard_negative: false
- summary: 三部门首次系统定义“国家数据基础设施”，明确数据流通、算力底座、网络支撑与安全防护的建设方向与阶段目标。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 后续政策与行业讨论把“全国一体化算力网/算力调度/互联互通”从概念推进到机制建设，并在“低效供给治理+统一调度”框架下推动标准与试点落地。
- observable_features_at_time:
  - 政策类型：顶层指引文件（国家层面），覆盖数据流通利用、算力底座、网络支撑、安全防护四大方向
  - 变化量：未给出全国新增机架/MW等硬指标（Unknown），以架构与推进路径为主
  - 约束类型：网络运载/跨域调度、算力供给与能效、数据安全与合规（多选）
  - 影响范围：跨地区、跨行业、跨运营主体（“国家数据基础设施”框架）
  - 执行机制信号：提出分阶段“夯基架梁—互联互通”等推进路径（时间表为阶段性而非单项目）
  - 可复用信号：是否明确“算力底座/高效调度/开放普惠/安全可靠”等关键词（强）
  - 证据等级：监管/部委通知（高）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体深度（国际通讯社） | 2025-07-24 | https://www.reuters.com/technology/china-plans-network-sell-surplus-computing-power-crackdown-data-centre-glut-2025-07-24/ | 报道“统一平台/网络化调度算力”与治理低效数据中心供给的政策动作
  - 监管机构（国家数据局） | 2025-10-30 | https://www.nda.gov.cn/sjj/zwgk/tzgg/1030/20251030112445906094192_pc.html | 发布先行先试场景应用实施方案，显示“指引→试点/场景落地”的推进链条

- sources (初报与当时材料):
  - initial_report: https://www.ndrc.gov.cn/xwdt/tzgg/202501/t20250106_1395457.html
  - time_slice_supporting: https://www.ndrc.gov.cn/xxgk/zcfb/tz/202501/P020250106319424108511.pdf, https://www.news.cn/tech/20250107/85bd4e962d17436c9d80a5a690f77586/c.html, https://www.nda.gov.cn/sjj/swdt/sjdt/0106/20250106103356946936455_pc.html

- notes: “影响”主要体现在制度与组织形态（调度/互联/安全）而非单一项目；当期无法从文件直接提取新增容量、MW 等硬量化。
---

## news_id: CNDC-2025-01-002
- domain: 数据中心
- initial_report_date: 2025-01-03
- title: 《网络数据安全管理条例》自2025-01-01起施行（权威解读传播）
- label: Major
- hard_negative: false
- summary: 数据安全行政法规进入可执行阶段，强化数据处理、跨境与平台治理要求，提高数据中心与云服务合规成本与门槛。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: 条例实施后，企业在数据分类分级、审计留痕、跨境流动与平台责任上被要求“可证明合规”，推动云与数据中心客户侧合规投入上升，并影响数据流通/跨境业务路径选择。
- observable_features_at_time:
  - 规则生效点：2025-01-01 起施行（明确生效日期）
  - 变化量：未给出罚款/执法案例等后验数字（Unknown）；当时可观测为“制度生效+义务清单”
  - 约束类型：数据安全与个人信息保护、重要数据与出境管理、平台责任（多选）
  - 影响范围：跨行业数据处理者；对云/数据中心客户的合规要求具有外溢性
  - 可复用信号：是否明确“跨境、重要数据、平台、审计/评估、训练数据安全”等关键词（强）
  - 证据等级：权威媒体转载官方解读/法规文本（高）
  - 当期不确定项：对数据中心“装机/投运节奏”的直接影响通常间接体现（uncertain）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 头部律所/研究复盘 | 2026-01-07 | https://www.zhonglun.com/research/articles/55395.html | 将条例作为2025合规框架关键组成，强调可检查、可实施的合规义务体系
  - 头部律所/研究复盘 | 2025-09-09 | https://www.reedsmith.com/articles/chinas-key-data-and-privacy-developments-in-the-first-eight-months-of-2025/ | 回顾2025年前期数据合规规则与执法重点，指向企业合规压力与机制完善

- sources (初报与当时材料):
  - initial_report: https://www.news.cn/politics/20250103/80230ae019b04809b6599ec6bf6061fb/c.html
  - time_slice_supporting: https://www.cac.gov.cn/2024-09/30/c_1729384452307680.htm, https://www.moj.gov.cn/pub/sfbgw/gwxw/xwyw/202409/t20240930_507076.html

- notes: 该条新闻“初报事件”按口径取“生效并被权威解读传播”的时点；条例公布本身发生于2024-09，不纳入本季度“初报候选”。
---

## news_id: CNDC-2025-02-001
- domain: 数据中心
- initial_report_date: 2025-02-09
- title: 发改委/能源局《关于深化新能源上网电价市场化改革 促进新能源高质量发展的通知》（发改价格〔2025〕136号）
- label: Major
- hard_negative: false
- summary: 新能源电量全面入市与结算机制重塑，影响绿电交易与长期电价形成方式，进而改变数据中心获取绿电/电价锁定的成本与风险结构。

- axes_and_direction:
  - pace: mixed
  - cost: mixed
  - constraint: mixed
  - supply_demand: uncertain

- subsequent_impact_path: 随着新能源电价机制按各地方案落地，绿电/市场电价的形成与波动特征改变，数据中心等大用户的购电策略更依赖市场化交易与中长期合同设计，成本与风险管理成为常态化能力。
- observable_features_at_time:
  - 政策类型：国家级电价与市场机制改革通知（非数据中心专属，但对大用户购电条件有外溢）
  - 变化量：未给出对数据中心电价的直接测算（Unknown）；核心是“入市+机制结算+分类施策”
  - 约束类型：电价机制/电力市场交易规则（主），并间接影响绿电采购与能耗合规（次）
  - 影响范围：全国（各省制定实施方案并落地）
  - 可复用信号：是否明确“全面入市、市场形成价格、机制电价/结算、存量/增量划分”（强）
  - 证据等级：监管/部委通知+官方解读（高）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 省级发改委（实施落地） | 2025-09-30 | https://drc.jiangxi.gov.cn/jxsfzhggwyh/col/col4990/content/content_1972952501089247232.html | 以省级实施方案形式承接国家通知，体现改革进入执行阶段
  - 省级发改委（实施落地） | 2025-11-07 | https://fgw.beijing.gov.cn/fgwzwgk/2024zcjd/202511/t20251107_4265707.htm | 发布实施方案解读，说明“全面放开/价格监测/协同政策”等具体执行要点

- sources (初报与当时材料):
  - initial_report: https://www.ndrc.gov.cn/xxgk/zcfb/tz/202502/t20250209_1396066.html
  - time_slice_supporting: https://www.ndrc.gov.cn/xxgk/jd/jd/202502/t20250209_1396069.html, https://www.xinhuanet.com/20250209/670c322974b7449fb6bfe072e7ee41bd/c.html

- notes: 对数据中心的影响主要通过“电力市场化+绿电交易机制”传导，单条政策难以在初报时点直接映射到某一地区装机/投运的量化变化。
---

## news_id: CNDC-2025-03-001
- domain: 数据中心
- initial_report_date: 2025-03-12
- title: 2025年政府工作报告提出“人工智能+”与“优化全国算力资源布局”
- label: Major
- hard_negative: false
- summary: 国家层面将“AI应用扩散+算力布局优化”纳入年度重点，强化跨区域算力配置、算网协同与数据要素制度建设的政策确定性。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: loosen
  - supply_demand: tighten

- subsequent_impact_path: 在“AI+”与“算力布局优化”定调后，政策与行业实践更强调跨区域调度与治理低效供给（从“建设冲动”转向“可用算力/调度效率/退出机制”），并推动一体化算力网络与标准化工作持续推进。
- observable_features_at_time:
  - 政策信号：政府工作报告明确“人工智能+”“优化算力资源布局”等方向性表述
  - 变化量：未给出新增机架、MW 或财政额度的硬量化（Unknown）
  - 约束类型：算力供给与布局、网络时延与互联互通、数据制度与跨境流动（多选）
  - 影响范围：全国（对地方专项债/产业政策与运营商投资预期形成指引）
  - 可复用信号：是否出现“优化布局、算力资源、数字产业集群、数据制度”（强）
  - 证据等级：国家层面权威文件（高）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体深度（国际通讯社） | 2025-07-24 | https://www.reuters.com/technology/china-plans-network-sell-surplus-computing-power-crackdown-data-centre-glut-2025-07-24/ | 报道政策侧将重点转向“统一调度算力+整治低效数据中心供给”
  - 监管机构（国家数据局） | 2025-10-30 | https://www.nda.gov.cn/sjj/zwgk/tzgg/1030/20251030112445906094192_pc.html | 在国家数据基础设施框架下推进“先行先试场景应用”，体现方向性部署的持续推进

- sources (初报与当时材料):
  - initial_report: https://www.12371.cn/2025/03/12/ARTI1741771604290287.shtml
  - time_slice_supporting: https://www.gov.cn/zhengce/content/202503/content_7008653.htm

- notes: 该条为“方向性政策信号”，对装机/投运节奏的影响通常通过后续配套政策与地方执行传导；初报时点不可引用后验投资/投运数字。
---

## news_id: CNDC-2025-03-002
- domain: 数据中心
- initial_report_date: 2025-03-18
- title: 五部门印发《关于促进可再生能源绿色电力证书市场高质量发展的意见》（发改能源〔2025〕262号）
- label: Major
- hard_negative: false
- summary: 通过绿证供给、需求、交易机制与应用场景的系统设计，提升绿电环境价值可计量与可核算性，成为数据中心获取“绿电合规”与成本传导的重要制度基础。

- axes_and_direction:
  - pace: mixed
  - cost: mixed
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: 绿证制度完善后，“强制比例+自愿消费”机制更易落地；后续对重点行业与国家枢纽节点新建数据中心提出绿电消费比例要求，推动数据中心绿电采购与核算成为硬约束之一。
- observable_features_at_time:
  - 政策类型：国家级制度文件，围绕绿证核发、交易、价格机制、应用场景与国际互认
  - 变化量：对数据中心具体比例要求在初报文件中未作为单一行业硬指标呈现（Unknown）
  - 约束类型：绿电/绿证核算、交易机制、企业披露与认证（多选）
  - 影响范围：全国（统一交易体系、价格监测/指数研究等）
  - 可复用信号：是否明确“价格机制/指数、强制+自愿、应用场景、国际互认”（强）
  - 证据等级：监管/部委联合发文（高）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体深度（国际通讯社） | 2025-07-11 | https://www.reuters.com/sustainability/boards-policy-regulation/china-sets-its-first-renewable-standards-steel-cement-polysilicon-2025-07-11/ | 报道可再生能源消费标准扩展至部分数据中心，并对国家枢纽节点新建数据中心提出高比例绿电要求
  - 监管机构（国家能源局） | 2026-01-30 | https://www.nea.gov.cn/20260130/ed1797e24ae948e680e4afcd6aa740dd/c.html | 回顾绿证制度与2025年政策安排，明确将国家枢纽节点新建数据中心纳入绿电消费比例要求与核算体系

- sources (初报与当时材料):
  - initial_report: https://www.ndrc.gov.cn/xxgk/zcfb/tz/202503/t20250318_1396627.html
  - time_slice_supporting: https://www.nea.gov.cn/20250318/0c73110958864a75bd1a823c7861c40c/c.html, https://www.xinhuanet.com/energy/20250319/9d144395341746d099eb13194de29a46/c.html

- notes: 该条对数据中心的“硬约束化”体现通常发生在后续行业/地区配套文件中；初报阶段可复用特征集中在“核算/交易/价格机制/应用场景”四类信号。
---

## news_id: CNDC-2025-03-003
- domain: 数据中心
- initial_report_date: 2025-03-31
- title: 深圳发放首批近2亿元“训力券”，并启用3000PFLOPS智算中心
- label: Major
- hard_negative: false
- summary: 地方以“算力补贴券+公共智算中心”组合拳降低训练成本，强化本地算力供给与需求撮合，形成可复制的产业政策工具。

- axes_and_direction:
  - pace: accelerate
  - cost: down
  - constraint: loosen
  - supply_demand: tighten

- subsequent_impact_path: 训力/算力券成为多地降低算力使用成本的标准政策工具，并与算力调度平台、国产算力生态培育等目标结合，推动需求侧加速释放与供给侧扩容/调度能力建设。
- observable_features_at_time:
  - 变化量：首批训力券规模“近2亿元”（明确）；智算中心规模“3000PFLOPS”（明确）
  - 政策工具：需求侧补贴（券）+供给侧公共算力平台（中心）联动
  - 约束类型：算力供给/成本（主），并间接关联电力与机房扩容（次，Unknown）
  - 影响范围：地方（深圳）为主，但具备“政策可复制”特征
  - 可复用信号：是否出现“补贴券、普惠算力、公共平台、快速兑现”（强）
  - 证据等级：地方政府权威媒体/政务发布（高）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 地方政府政策文件 | 2025-07-29 | https://www.sh-hitech.com/ryrd/19231.html | 明确以大规模算力券降低租用成本，并强调算力调度平台建设（显示工具扩散）
  - 地方政府政策文件 | 2025-08-08 | https://jxj.beijing.gov.cn/zwgk/2024zcwj/202508/t20250808_4169567.html | 将“算力券补贴”纳入年度产业支持方向，体现政策工具在一线城市延续与制度化

- sources (初报与当时材料):
  - initial_report: https://www.sz.gov.cn/cn/xxgk/zfxxgj/zwdt/content/post_12097397.html
  - time_slice_supporting: https://stic.sz.gov.cn/xxgk/tzgg/content/post_12086189.html

- notes: 该条的“重大性”更多体现在政策工具可复制与需求侧加速释放；对全国装机节奏的直接量化贡献在初报时点不可引用后验数据。
---

## news_id: CNDC-2025-01-003
- domain: 数据中心
- initial_report_date: 2025-01-04
- title: 福州长乐区重大项目开工，提出打造“人工智能智算中心”（项目投资约11亿元）
- label: NotMajor
- hard_negative: true
- summary: 地方项目开工叙事具“看似重大”特征，但缺少跨区域/跨主体的硬约束改变证据，后验也难证明其形成全国性结构影响。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 后续行业更关注“低利用率+统一调度+整治低效供给”的全国性问题，单一地方智算中心项目难以改变供需拐点或电力/并网等硬约束格局。
- observable_features_at_time:
  - 变化量：投资约11亿元；未披露机架/MW/电力接入与COD（Unknown）
  - 约束类型：土地/园区建设为主；电力与并网信息缺失（Unknown）
  - 影响范围：地方单项目（缺少跨省/跨公用事业外溢）
  - 证据等级：地方媒体报道（中）
  - 可复用信号：强调“区域最大/最高等级”等宣称但缺少可核验硬指标
  - 风险信号：项目级“开工”≠“投运/可用算力”，落地不确定性高

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体深度（行业问题复盘） | 2025-07-17 | https://www.stdaily.com/web/gdxw/2025-07/17/content_371093.html | 报道我国智算中心平均算力使用率偏低、存在“沉睡算力”问题，提示“建成≠有效供给”
  - 权威媒体深度（国际通讯社） | 2025-07-24 | https://www.reuters.com/technology/china-plans-network-sell-surplus-computing-power-crackdown-data-centre-glut-2025-07-24/ | 报道监管侧转向整治数据中心供给冗余并推动统一调度，弱化单项目的结构影响

- sources (初报与当时材料):
  - initial_report: https://m.fznews.com.cn/changle/20250104/0PfC7kVH2m.shtml
  - time_slice_supporting: Unknown

- notes: hard negative 原因：初报缺少电力接入/并网、可用算力、投运时间等硬信息；后验未形成“多源一致+行业变量长期改变”的证据链。
---

## news_id: CNDC-2025-01-004
- domain: 数据中心
- initial_report_date: 2025-01-18
- title: 遵义“网络空间安全智算中心”项目开工（并与风光储项目并列）
- label: NotMajor
- hard_negative: true
- summary: 叙事上将“智算中心+新能源”绑定、容易被误读为结构性突破，但更像地方招商/开工新闻，难以满足后验多源长期影响门槛。

- axes_and_direction:
  - pace: uncertain
  - cost: mixed
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 后续全国层面的核心矛盾集中在算力低利用率与跨域调度治理；该类地方项目难以在电力/网络/利用率等硬约束上形成可验证的全国性改变量。
- observable_features_at_time:
  - 变化量：报道为“项目开工”；未披露可用算力、机架、电力接入批复与COD（Unknown）
  - 约束类型：电力与并网细节缺失（Unknown），更多为“项目组合”叙事
  - 影响范围：地方单项目/单园区
  - 证据等级：新华社地方频道报道（中高，但信息粒度偏粗）
  - 可复用信号：将“智算中心”与“风光储”并列，属于常见招商包装信号
  - 风险信号：缺少后续独立来源对其改变行业变量的持续确认

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体深度（行业问题复盘） | 2025-07-17 | https://www.stdaily.com/web/gdxw/2025-07/17/content_371093.html | 讨论“沉睡算力/低利用率”，说明行业痛点并非单点新增项目可解决
  - 权威媒体深度（国际通讯社） | 2025-07-24 | https://www.reuters.com/technology/china-plans-network-sell-surplus-computing-power-crackdown-data-centre-glut-2025-07-24/ | 报道监管治理低效供给与推进调度网络，凸显结构性问题在全国层面解决

- sources (初报与当时材料):
  - initial_report: https://www.gz.xinhuanet.com/20250118/6664808d84334727b28c517f08b51563/c.html
  - time_slice_supporting: Unknown

- notes: hard negative 原因：无法构造“≥2独立后验来源”证明其对全国装机/投运/成本/约束的长期影响；更可能是地方项目噪声。
---

## news_id: CNDC-2025-02-002
- domain: 数据中心
- initial_report_date: 2025-02-28
- title: 霍尔果斯园区集中开复工，包含“新疆瀚疆云算10000P智算中心项目”奠基
- label: NotMajor
- hard_negative: true
- summary: 单个园区项目体量较大但局部性强；在全国尺度上更像“建设热”样本，后验无法满足多源确认其引发行业变量长期拐点。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 后续政策与研究更聚焦“供给冗余/利用率偏低/算力调度”而非继续加速立项，说明单点新增项目难以构成全国层面的结构性事件。
- observable_features_at_time:
  - 变化量：报道披露“总投资/分期/完工计划”等，但对可用算力上线节奏与电力接入核验不足（部分Unknown）
  - 约束类型：土地与建设信息较充分；电力并网、网络时延、客户签约等关键约束信息不足（Unknown）
  - 影响范围：地方园区（跨区域外溢证据弱）
  - 证据等级：新华社地方频道（中高）
  - 可复用信号：以“奠基/开复工”作为核心信息，属于高不确定阶段信号
  - 风险信号：容易被误判为“全国供给拐点”，但缺少行业级验证

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体深度（行业问题复盘） | 2025-07-17 | https://www.stdaily.com/web/gdxw/2025-07/17/content_371093.html | 指向全国性低利用率痛点，削弱“新增供给=有效供给”的推断
  - 权威媒体深度（国际通讯社） | 2025-07-24 | https://www.reuters.com/technology/china-plans-network-sell-surplus-computing-power-crackdown-data-centre-glut-2025-07-24/ | 报道整治冗余与统一调度成为政策重点，说明行业变量由“调度/退出”主导

- sources (初报与当时材料):
  - initial_report: https://xj.news.cn/20250228/f268129a16414a87a8039648fadec9ca/c.html
  - time_slice_supporting: Unknown

- notes: hard negative 原因：项目局部性强，且初报阶段关键硬约束（电力/网络/客户）未披露；后验也未形成“多源一致的行业级影响”证据链。
---

## news_id: CNDC-2025-02-003
- domain: 数据中心
- initial_report_date: 2025-02-21
- title: 喀什10000P算力智算产业园项目动土开工（空天信息产业园集中开工）
- label: NotMajor
- hard_negative: true
- summary: 典型“西部绿色算力园区”开工新闻，传播上很像重大事件，但在全国尺度更多是建设潮的一部分，难以满足后验结构性影响门槛。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 后续行业矛盾仍由“供给冗余与调度效率”主导；类似项目即便推进，也通常难以改变全国层面的约束结构与供需拐点判断。
- observable_features_at_time:
  - 变化量：披露“10000P、用地、建筑面积、投资”等，但未披露电力接入批复/上架率/客户锁定（部分Unknown）
  - 约束类型：更偏“园区建设/招商”；电力、网络与客户侧约束信息缺失（Unknown）
  - 影响范围：地方单园区，跨省外溢证据弱
  - 证据等级：产业媒体/项目报道（中）
  - 可复用信号：强调“算力规模(P)、总投资、开工仪式”（强但噪声大）
  - 风险信号：规模口径（P/卡/有效可用算力）可能不一致，易被高估

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体深度（行业问题复盘） | 2025-07-17 | https://www.stdaily.com/web/gdxw/2025-07/17/content_371093.html | 强调“算力沉睡/利用率偏低”，提示供给扩张不等于有效供给
  - 权威媒体深度（国际通讯社） | 2025-07-24 | https://www.reuters.com/technology/china-plans-network-sell-surplus-computing-power-crackdown-data-centre-glut-2025-07-24/ | 报道政策侧推进统一调度并整治低效供给，说明行业变量并非由单点新增项目驱动

- sources (初报与当时材料):
  - initial_report: https://www.dtdata.cn/news/show/3005.html
  - time_slice_supporting: https://www.sxcig.com/info/1111/96101.htm

- notes: hard negative 原因：缺少后验“多源一致”证明其改变全国装机/投运节奏或电力约束；更可能是“项目潮”样本而非结构事件。
---

## news_id: CNDC-2025-03-004
- domain: 数据中心
- initial_report_date: 2025-03-11
- title: 中国联通长三角（合肥）智算中心项目落地（一期总投资约3亿元、规划超3000P）
- label: NotMajor
- hard_negative: true
- summary: 运营商智算中心落地易被解读为“供给拐点”，但单项目规模与外溢性有限，后验难以满足“多源确认其长期改变行业变量”的门槛。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 后续全国层面更强调解决“低利用率/异构割裂/跨域调度不足”等系统性问题；单个城市新增节点难以单独改变全国供需与硬约束。
- observable_features_at_time:
  - 变化量：披露投资额与规划算力（明确）；未披露电力接入规模、PUE/能耗、客户签约（部分Unknown）
  - 约束类型：电力与并网、网络时延等关键约束缺少细节（Unknown）
  - 影响范围：区域性节点（长三角/安徽），外溢性不明
  - 证据等级：门户财经转载（中）
  - 可复用信号：运营商主导、模块化、年底竣工计划（强但仍属计划口径）
  - 风险信号：规划算力与“可用算力/上架率”可能偏离

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体深度（行业问题复盘） | 2025-07-17 | https://www.stdaily.com/web/gdxw/2025-07/17/content_371093.html | 讨论行业“沉睡算力”，表明单点扩容未必转化为有效供给
  - 权威媒体深度（国际通讯社） | 2025-07-24 | https://www.reuters.com/technology/china-plans-network-sell-surplus-computing-power-crackdown-data-centre-glut-2025-07-24/ | 报道推动统一调度与治理冗余供给，说明行业变量由系统机制驱动

- sources (初报与当时材料):
  - initial_report: https://finance.sina.com.cn/stock/relnews/cn/2025-03-11/doc-inepicec5182414.shtml
  - time_slice_supporting: Unknown

- notes: hard negative 原因：无法构造“≥2独立后验来源”证明其引发全国性装机/投运/成本结构的长期变化；更符合“区域项目噪声”特征。
---

## news_id: CNDC-2025-02-004
- domain: 数据中心
- initial_report_date: 2025-02-20
- title: 上海临港“开门红”集中签约41个项目（含数字经济相关项目）
- label: Unlabeled
- hard_negative: false
- summary: 大型签约活动具备“看似重大”的传播特征，但初报信息聚合度高、项目口径不一致，难以稳定回溯到数据中心行业变量的确定性影响。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: Unknown
- observable_features_at_time:
  - 变化量：披露“签约数量/总投资”，但对数据中心相关项目的MW/机架/电力接入与投运时间不统一（Unknown）
  - 约束类型：信息更偏招商与产业导入，硬约束字段缺失（Unknown）
  - 影响范围：区域（临港），外溢性需依赖后续落地清单核验
  - 证据等级：地方权威媒体（中高）
  - 可复用信号：集中签约/总投资口径常见，但需拆解到项目级才可训练模型

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - Unknown | Unknown | Unknown | 未找到足够“项目级可核验字段+后续独立来源持续确认”以稳定标注

- sources (初报与当时材料):
  - initial_report: https://www.shobserver.com/staticsg/res/html/web/newsDetail.html?id=863336&sid=200
  - time_slice_supporting: Unknown

- notes: 未标注原因：缺少可复用的项目级硬字段，且难以建立满足门槛的后验多源影响链条；保留为候选以便未来补齐项目清单后再标注。
---

# 数据中心-中国-2025Q2

---
## news_id: CNDC-2025-04-001
- domain: 数据中心
- initial_report_date: 2025-04-07
- title: 国家数据局组织开展2025年可信数据空间创新发展试点（企业/行业/城市三类）
- label: Major
- hard_negative: false
- summary: 国家数据局发文启动“可信数据空间”试点，提出两年培育、可复制推广的机制与技术路径，推动数据要素合规流通与跨域协同。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: mixed
  - supply_demand: tighten

- subsequent_impact_path: 试点推动“合规流通+互联互通”的数据基础设施落地，后续在国家层面被持续强调为数据要素市场的重要载体，并在地方形成项目清单与配套推进，带动对安全可信数据处理与算力/存储底座的持续需求扩张。  
- observable_features_at_time:
  - 试点类型明确：企业可信数据空间、行业可信数据空间、城市可信数据空间三条线
  - 明确“经过两年试点培育”的时间框架（两年）
  - 任务聚焦：数据资源归集、共建共治机制、可持续运营模式、互联互通技术路径等
  - 目标产出强调“可复制推广的经验模式”
  - 约束与合规被前置为核心：强调安全可控、合规高效流通
  - 量化规模：Unknown（通知未给出规模上限/资金量）
  - 影响范围：跨行业、跨城市、多主体协同

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管/中央部委 | 2025-10-09 | https://www.ndrc.gov.cn/wsdwhfz/202510/t20251009_1400856.html | 国家层面将可信数据空间定位为数据要素市场关键抓手，强调试点引导与互联互通
  - 地方政府/数据局 | 2025-12-19 | https://sdb.sh.gov.cn/gsgg/20251222/61b1952b1c5546cf96a1b49fc13dffc1.html | 地方公布试点项目名单并组织落地，体现试点向项目化推进与扩散

- sources (初报与当时材料):
  - initial_report: https://www.nda.gov.cn/sjj/ywpd/sjzy/0408/20250407172325097704036_pc.html
  - time_slice_supporting: https://www.news.cn/20250407/109b35566e8a482baa9402966d677bd5/c.html

- notes: 对“数据中心行业变量”的传导主要体现在数据要素流通带来的合规算力/存储需求提升，属于机制性影响，短期量化弹性在初报时点不可得。
---

## news_id: CNDC-2025-04-002
- domain: 数据中心
- initial_report_date: 2025-04-30
- title: 强制性国家标准《数据中心能效限定值及能效等级》（GB 40879）启动修订立项（计划号20251056-Q-469）
- label: Major
- hard_negative: false
- summary: 国家标准平台显示GB 40879-2021启动强制性修订立项，意味着数据中心能效门槛可能进一步收紧，影响新建与存量改造的合规成本与节奏。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: 能效强标修订与后续“绿色数据中心/绿色算力设施”评价体系共同强化行业从“规模扩张”向“能效与利用率”导向的约束，推动更严格的PUE/可再生能源/上架率等要求进入评估与名单管理，进而影响项目准入、改造投入与供给结构。  
- observable_features_at_time:
  - 立项属性：强制性国家标准“修订”
  - 下达日期：2025-04-30；计划号：20251056-Q-469
  - 明确“全部代替”既有GB 40879-2021
  - 技术组织：委托TC20（全国能源基础与管理标准化技术委员会）执行
  - 起草单位包含中国标准化研究院、中国信通院、中国移动等（体现产业链参与）
  - 潜在影响方向：能效限额/等级门槛可能上调（具体条款：Unknown）
  - 影响范围：全国统一强制标准，覆盖新建与存量合规评估

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管/部委联合行动 | 2025-12-29 | https://www.ithome.com/0/908/939.htm | 六部门公布年度“国家绿色算力设施名单”，体现绿色低碳与能效导向进入名单化管理
  - 监管/评价体系文件 | 2025-08-01 | https://kcycrawlerfile.oss-cn-beijing.aliyuncs.com/2025/08/01/P020250801608724540243.pdf | 评价指标体系将PUE、可再生能源利用、机柜上架率等纳入考核，强化“能效+利用率”约束（与强标方向一致）

- sources (初报与当时材料):
  - initial_report: https://std.samr.gov.cn/gb/search/gbDetailed?id=2E4DD4D8E2E84A4BE06397BE0A0AE354
  - time_slice_supporting: https://openstd.samr.gov.cn/bzgk/gb/newGbInfo?hcno=4AAF5CA9387980A1FEA1FA47ABA503BA

- notes: 初报时点仅能确认“立项与修订启动”，无法引用后续条款变化；对装机/投运节奏的影响取决于最终限额与地方执行强度，存在不确定性。
---

## news_id: CNDC-2025-05-003
- domain: 数据中心
- initial_report_date: 2025-05-30
- title: 发改委/能源主管部门发文规范“绿电直连”（以荷定源、自发自用比例约束等）
- label: Major
- hard_negative: false
- summary: 国家层面明确绿电直连项目的投资主体、直连专线责任与源荷匹配规则，并对自发自用比例等提出硬约束，为“绿电+算力/数据中心”提供合规路径。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 绿电直连为高载能负荷（含数据中心/算力中心）提供“电力约束下的新增路径”，后续在多省扩展为政策组合并出现首批项目公示，形成“新能源—负荷直连—园区/算力”模式，缓解并网与绿电获取约束并重塑数据中心选址与电力成本结构。  
- observable_features_at_time:
  - 明确“负荷为主责单位”、非电网企业可投资的模式边界
  - 源荷匹配原则：“以荷定源”
  - 比例硬约束：新能源年自发自用电量占总可用发电量不低于60%；占总用电量不低于30%，并提出2030年前不低于35%
  - 上网电量比例上限由省级主管部门结合实际确定，一般不超过20%（并网型项目）
  - 现货市场未连续运行地区“不允许向公共电网反送”（约束商业模式）
  - 影响对象：可覆盖数据中心等高载能用户（是否纳入具体项目：Unknown）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 行业媒体/政策跟踪 | 2025-12-18 | https://www.cpnn.com.cn/news/baogao2023/202512/t20251218_1854498.html | 多省发布直连细则并出现包含智算中心的首批项目公示，说明机制进入项目落地阶段
  - 监管/发布会 | 2026-01-30 | https://www.nea.gov.cn/20260130/b5b729cb7ad74723bcd614b663c75da6/c.html | 官方表述“已在20多个省区市的数据中心等加快项目落地”，将直连作为需求侧绿电“直通车”

- sources (初报与当时材料):
  - initial_report: https://www.ndrc.gov.cn/xxgk/zcfb/tz/202505/t20250530_1398138.html
  - time_slice_supporting: https://www.ndrc.gov.cn/xxgk/zcfb/tz/202505/t20250530_1398138.html

- notes: 初报已给出关键比例约束，可直接用于模型特征；对成本方向为mixed，取决于直连专线CAPEX与绿电价格/机制电价环境。
---

## news_id: CNDC-2025-05-004
- domain: 数据中心
- initial_report_date: 2025-05-17
- title: “算力态势感知监测”试点推进，中国算力平台对外开放（试点地区/企业纳入监测）
- label: Major
- hard_negative: false
- summary: 面向全国算力供需与运行状态的监测与平台化对接推进，试图解决供需错配与调度效率问题，为统一调度与跨域互联提供数据底座。

- axes_and_direction:
  - pace: accelerate
  - cost: down
  - constraint: loosen
  - supply_demand: mixed

- subsequent_impact_path: 通过“监测—标准化上报—平台聚合”，把分散算力资产纳入可观测与可调度范围，后续进入“全面推广与持续监测”阶段，并与算力互联网/互联互通政策形成闭环，推动从“建算力”转向“用算力、管算力、调算力”。  
- observable_features_at_time:
  - “算力态势感知监测”作为政策动作被明确推进（试点性质）
  - 平台形态：统一入口/对外开放（以供需对接、调度为目标）
  - 覆盖范围：试点地区与试点企业（具体名单：Unknown）
  - 关键变量：算力运行状态、供需匹配、跨域调度能力（披露口径：Unknown）
  - 约束类型：调度与互联互通的“数据底座”约束被显性化
  - 对数据中心影响：提升闲置资源可变现概率、强化纳管要求

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管/部委公告 | 2026-01-23 | https://www.news.cn/fortune/20260123/f37b3cfeb0804d469774c9d7d2540dce/c.html | 工信部将“算力态势感知监测”由试点推向全面推广，强化持续监测与规则化管理
  - 权威媒体/经济日报转载 | 2026-01-15 | https://home.wuhan.gov.cn/mtbd/202601/t20260115_2712326.shtml | 报道“算力互联网服务平台跨域体系发布”，体现跨域协同与平台聚合进一步推进

- sources (初报与当时材料):
  - initial_report: https://www.odcc.org.cn/article/34/2818.html
  - time_slice_supporting: https://www.odcc.org.cn/article/34/2818.html

- notes: 初报时点通常缺乏可量化KPI（如纳管规模、实时调度量），可用“是否进入试点/是否开放平台/是否纳入监测”作离散特征；严禁用后验利用率数字做当时特征。
---

## news_id: CNDC-2025-06-005
- domain: 数据中心
- initial_report_date: 2025-05-30
- title: 工信部印发《算力互联互通行动计划》（提出到2026/2028阶段性目标）
- label: Major
- hard_negative: false
- summary: 工信部发布互联互通行动计划，明确标准、标识、规则体系与“先互联再成网”的路线，面向跨主体/跨架构/跨地域的公共算力资源互联。

- axes_and_direction:
  - pace: accelerate
  - cost: down
  - constraint: loosen
  - supply_demand: mixed

- subsequent_impact_path: 行动计划把互联互通从“倡议”升级为时间表与任务清单，推动标准化互联与资源互用，后续与“态势感知监测”“算力互联网平台”结合，形成供需匹配与跨域调度的政策组合，改善东数西算背景下的可用性与调度效率。  
- observable_features_at_time:
  - 发文机关与文号：工信部信管〔2025〕119号
  - 成文日期：2025-05-21；公开发布入口：2025-05-30（政府App/转载）
  - 明确阶段目标：到2026年建立较完备标准/标识/规则体系；到2028年推动全国范围标准化互联互通（目标口径见附件）
  - 路线：先试点后推广、先互联再成网、政府推动+市场主导
  - 互联对象：不同主体、不同架构的公共算力资源
  - 对数据中心约束：互联互通能力、协议/标识/规则合规要求（量化阈值：Unknown）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管/部委公告 | 2026-01-23 | https://www.news.cn/fortune/20260123/f37b3cfeb0804d469774c9d7d2540dce/c.html | 互联互通配套动作（监测、推广）继续推进，体现政策连续性与执行落地
  - 权威媒体/经济日报转载 | 2026-01-15 | https://finance.people.com.cn/n1/2026/0115/c1004-40645817.html | 报道算力互联网平台跨域体系发布与市场规模增长，反映互联互通方向进入产业化阶段

- sources (初报与当时材料):
  - initial_report: https://app.www.gov.cn/govdata/gov/202505/30/530146/articleNew.html
  - time_slice_supporting: https://picpolicy.mofcom.gov.cn/file/20250721/43121753077832842.pdf

- notes: “互联互通”对装机节奏影响偏中长期；当时可观测信号以“是否给出明确时间表/标准化任务/互联对象范围”作为可复用特征。
---

## news_id: CNDC-2025-06-006
- domain: 数据中心
- initial_report_date: 2025-06-03
- title: 国务院公布《政务数据共享条例》（国务院令第809号，2025-08-01施行）
- label: Major
- hard_negative: false
- summary: 首次以行政法规系统规范政务数据目录管理、共享使用与平台支撑，强化安全与责任边界，推动数字政府“全国一盘棋”的数据共享底座建设。

- axes_and_direction:
  - pace: accelerate
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 条例推动政务数据从“部门烟囱”向统一目录与平台体系迁移，提升数据共享的制度确定性与合规要求；在实施与配套标准推进中，政务云/数据中心的承载与安全合规需求上升，带动算力与存储侧的结构性需求。  
- observable_features_at_time:
  - 法规层级：国务院行政法规（令第809号）
  - 通过时间：2025-05-09（国务院常务会议通过）；公布：2025-06-03/06-04；施行：2025-08-01
  - 结构：8章44条
  - 重点：统一目录管理、共享申请/答复流程、平台支撑与争议处理机制
  - 明确“不得重复收集可通过共享获取的数据”（对系统整合提出硬要求）
  - 合规约束：强调数据安全、个人信息保护与法律责任
  - 量化规模：Unknown（不直接给出投资/算力规模）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管/国家网信办研究报告发布 | 2025-12-26 | https://www.cac.gov.cn/2025-12/26/c_1768474096986131.htm | 明确提出以《条例》实施为契机完善政务数据共享协调机制，显示条例成为后续工作的制度抓手
  - 律所/研究简报 | 2026-01-08 | https://www.allbrightlaw.com/CN/10475/c3d819cc27a8b6ad.aspx | 将其作为数据治理与数字政府法治化的重要节点进行复盘与归纳

- sources (初报与当时材料):
  - initial_report: https://www.moj.gov.cn/pub/sfbgw/gwxw/xwyw/202506/t20250603_520421.html
  - time_slice_supporting: https://www.mee.gov.cn/zcwj/gwywj/202506/t20250604_1120657.shtml

- notes: 对数据中心行业变量的影响主要经由“政务云/政务平台整合+合规安全投入”传导，短期难以直接映射到单一项目COD，但方向性较明确。
---

## news_id: CNDC-2025-05-007
- domain: 数据中心
- initial_report_date: 2025-05-16
- title: 浙江省发展改革委组织开展人工智能券（算力券）兑付申报
- label: NotMajor
- hard_negative: true
- summary: 以补贴方式降低算力使用成本、促进供需对接的地方动作，但属于需求侧“促用”工具，难以单独扭转结构性供需错配与可用性问题。

- axes_and_direction:
  - pace: accelerate
  - cost: down
  - constraint: uncertain
  - supply_demand: loosen

- subsequent_impact_path: 后续行业仍普遍面临“消纳难、利用率低”的结构性问题，说明单次券补贴更像局部促用而非硬约束变更；监管与行业讨论的重心转向“监测纳管、统一调度、提升利用率”，券政策未形成跨区域、跨主体的长期变量改变。  
- observable_features_at_time:
  - 申报截止：2025-05-18 18:00（明确时间节点）
  - 申报方式：电子+纸质材料；强调材料真实性与信息安全
  - 管理服务机构明确（便于复用为制度特征）
  - 作用机制：事后兑付/补贴以降低用算成本（补贴比例/上限：Unknown）
  - 影响范围：省内项目（跨区域外溢：Unknown）
  - 约束类型：需求刺激为主，未直接改变并网/能耗/准入硬门槛
  - 量化规模：Unknown（公告未在摘要中给出总盘子）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体/观点与数据 | 2025-09-02 | https://finance.sina.com.cn/stock/t/2025-09-02/doc-infpccsz6758057.shtml | 行业人士指出平均算力使用率不足30%，反映“促用”并未系统性解决消纳问题
  - 监管/部委公告 | 2026-01-23 | https://www.news.cn/fortune/20260123/f37b3cfeb0804d469774c9d7d2540dce/c.html | 工信部推动监测与推广，显示政策抓手转向“纳管与调度”而非单纯补贴

- sources (初报与当时材料):
  - initial_report: https://www.keceyun.com/policy/newsdetail/200937.html
  - time_slice_supporting: https://www.keceyun.com/policy/newsdetail/200937.html

- notes: hard_negative理由：看似“促需求”且易引发热度，但缺乏跨区域/跨主体的持续确认与硬约束变化量；券政策更可能被后续“纳管/调度”框架吸收。
---

## news_id: CNDC-2025-05-008
- domain: 数据中心
- initial_report_date: 2025-05-19
- title: 安徽省组织申报2025年人工智能算力券（补贴时间窗口截至2025-04-30）
- label: NotMajor
- hard_negative: true
- summary: 以算力券补贴降低企业使用成本，但补贴窗口具有“追溯性/阶段性”特征，对新增装机与投运节奏的边际拉动有限。

- axes_and_direction:
  - pace: uncertain
  - cost: down
  - constraint: uncertain
  - supply_demand: loosen

- subsequent_impact_path: 该类政策多为阶段性补贴，且补贴时间窗口与申报节点显示更偏“结算支持”而非长期制度变更；后续行业仍强调利用率不足与供需错配，表明此类工具难形成结构性影响。  
- observable_features_at_time:
  - 申报截止：2025-05-19（明确节点）
  - 补贴时间范围：2024-01-01至2025-04-30（追溯性窗口）
  - 申报主体：算力服务实际使用方（需求方）需协同供给方核实条件
  - 要求提供结算与算力使用证明（可复用为审核特征）
  - 补贴比例/上限：Unknown（摘要未披露）
  - 影响范围：省内；跨省调度与互联要求：Unknown

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体/观点与数据 | 2025-09-02 | https://finance.sina.com.cn/stock/t/2025-09-02/doc-infpccsz6758057.shtml | 行业“消纳难”与低利用率持续存在，说明阶段性补贴难以改变结构性矛盾
  - 监管/部委公告 | 2026-01-23 | https://www.news.cn/fortune/20260123/f37b3cfeb0804d469774c9d7d2540dce/c.html | 政策重心继续落在监测纳管与供需匹配

- sources (初报与当时材料):
  - initial_report: https://www.ichuanghui.org/8561.html
  - time_slice_supporting: https://www.ichuanghui.org/8561.html

- notes: hard_negative理由：可观察到明确的申报与补贴窗口，但缺少后续多源证据表明其改变行业硬约束或形成长期供需拐点。
---

## news_id: CNDC-2025-06-009
- domain: 数据中心
- initial_report_date: 2025-06-03
- title: 深圳公示2025年国家人工智能券（算力券）项目资格审核结果（拟申报算力服务额11.68亿元）
- label: NotMajor
- hard_negative: true
- summary: 深圳推进算力券项目审核与补助申报，金额看似可观，但仍属于需求侧补贴与项目制管理，难以单独解决全国性供需错配与跨域调度瓶颈。

- axes_and_direction:
  - pace: accelerate
  - cost: down
  - constraint: uncertain
  - supply_demand: loosen

- subsequent_impact_path: 后续讨论与数据仍聚焦“利用率不足、结构性错配、需统一调度与监测纳管”，表明地方券政策更多是区域促用而非行业变量的长期改变。  
- observable_features_at_time:
  - 公开公示期：2025-06-04至2025-06-10（可复用为流程特征）
  - 拟上报核算后算力服务总额：11.68亿元；申请补助总额：1.29亿元
  - 审核流程：企业申报—机构审核—专家评审—公示
  - 管理服务机构明确（便于识别平台/承办主体）
  - 影响范围：深圳市；跨区域外溢：Unknown
  - 约束类型：补贴与审核为主，未直接改变并网/能耗/绿电等硬门槛

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体/观点与数据 | 2025-09-02 | https://finance.sina.com.cn/stock/t/2025-09-02/doc-infpccsz6758057.shtml | 平均使用率不足30%等“消纳难”持续存在，说明区域补贴难以解决全国性结构问题
  - 监管/部委公告 | 2026-01-23 | https://www.news.cn/fortune/20260123/f37b3cfeb0804d469774c9d7d2540dce/c.html | 政策抓手继续转向监测、纳管与推广

- sources (初报与当时材料):
  - initial_report: https://fgw.sz.gov.cn/gkmlpt/content/12/12207/post_12207806.html
  - time_slice_supporting: https://fgw.sz.gov.cn/gkmlpt/content/12/12207/post_12207806.html

- notes: hard_negative理由：当时金额与热度代理很强，但缺少后续多源证据显示其改变行业硬约束（并网/能耗/时延/芯片异构等）。
---

## news_id: CNDC-2025-06-010
- domain: 数据中心
- initial_report_date: 2025-06-06
- title: 山东省政府公报文件提出实施“算力券”奖补政策（省级支持条款）
- label: NotMajor
- hard_negative: true
- summary: 省级文件提出以算力券奖补支持算力使用与产业发展，但属于条款级支持，具体资金规模、覆盖面与持续性在当时不明确，难以判断为结构性变量改变。

- axes_and_direction:
  - pace: uncertain
  - cost: down
  - constraint: uncertain
  - supply_demand: loosen

- subsequent_impact_path: 后续行业层面的核心矛盾仍被表述为“利用率不足、供需错配、需监测与调度体系化”，说明条款级补贴难以成为全国性拐点。  
- observable_features_at_time:
  - 省级政府公报发布，政策层级较高（但为条款表达）
  - 明确提出“实施算力券奖补政策”（具体规则：Unknown）
  - 资金规模/补贴比例：Unknown
  - 覆盖对象：Unknown（企业/机构/场景未在摘要中披露）
  - 约束类型：需求侧支持为主，不直接触及并网/能耗准入
  - 影响范围：省域；跨省调度：Unknown

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体/观点与数据 | 2025-09-02 | https://finance.sina.com.cn/stock/t/2025-09-02/doc-infpccsz6758057.shtml | 低利用率与“消纳难”仍是行业共性问题
  - 监管/部委公告 | 2026-01-23 | https://www.news.cn/fortune/20260123/f37b3cfeb0804d469774c9d7d2540dce/c.html | 监管推动监测与推广，体现政策工具从“补贴”向“纳管调度”演进

- sources (初报与当时材料):
  - initial_report: https://gb.shandong.gov.cn/art/2025/6/6/art_100623_46268.html
  - time_slice_supporting: https://gb.shandong.gov.cn/art/2025/6/6/art_100623_46268.html

- notes: hard_negative理由：当时可观测信息不完整（资金/规则缺失），且后续缺少“改变硬约束/形成行业拐点”的多源确认。
---

## news_id: CNDC-2025-06-011
- domain: 数据中心
- initial_report_date: 2025-06-13
- title: 媒体解读“智能算力调度平台”价值（强调提升利用率与降低门槛）
- label: NotMajor
- hard_negative: true
- summary: 文章强调算力调度平台可解决碎片化与低利用率，但属于机制解读型内容，缺少具体政策落地与硬指标约束，易被误判为“重大拐点”。

- axes_and_direction:
  - pace: uncertain
  - cost: down
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 后续多源仍反复出现“平均使用率不足30%”的行业表述，说明“平台叙事”本身不足以构成结构性改善；真正的变量改变更多来自监测纳管、标准与规则体系等更强约束工具。  
- observable_features_at_time:
  - 内容类型：机制与技术解读，非监管文件/非项目落地公告
  - 核心主张：资源池化、虚拟化/容器化、潮汐调度以提升利用率
  - 缺失：无强制指标、无覆盖范围、无时间表（均为Unknown）
  - 可复用信号：是否出现“统一调度/跨域/池化/降低门槛”等叙事关键词
  - 约束类型：软性倡议与行业观点，证据等级偏低于监管/运营商披露

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体/观点与数据 | 2025-09-02 | https://finance.sina.com.cn/stock/t/2025-09-02/doc-infpccsz6758057.shtml | 行业人士仍称平均使用率不足30%，与“平台叙事=立即改善”不一致
  - 监管/部委公告 | 2026-01-23 | https://www.news.cn/fortune/20260123/f37b3cfeb0804d469774c9d7d2540dce/c.html | 监管强调监测与推广，说明需要更强的制度与执行框架

- sources (初报与当时材料):
  - initial_report: https://www.eet-china.com/mp/a412526.html
  - time_slice_supporting: https://www.eet-china.com/mp/a412526.html

- notes: hard_negative理由：传播度高、易被当作“解决低利用率的重大路径”，但缺少后续多源确认其在行业层面形成可验证的结构性改善。
---

## news_id: CNDC-2025-06-012
- domain: 数据中心
- initial_report_date: 2025-06-30
- title: 摩尔线程IPO招股书披露持续响应“建设新型算力基础设施”等战略（研发与产业化资金投向）
- label: Unlabeled
- hard_negative: false
- summary: 企业层面披露与算力基础设施相关的战略与投入方向，但其对行业变量的影响取决于后续融资落地、产品供给与生态采用，难以稳定做正/负例。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: Unknown（缺少≥2个独立后验来源稳定确认其对行业装机/投运/成本/约束或供需拐点产生长期影响）。  
- observable_features_at_time:
  - 信息载体：招股说明书/发行文件（信息披露属性强）
  - 关键词：强调自主可控、算力基础设施建设、持续研发投入
  - 量化信息：对数据中心行业的MW/机架/COD贡献为Unknown
  - 约束类型：供给侧（芯片/加速卡）可能影响数据中心配置结构（幅度Unknown）
  - 影响范围：依赖市场采用与生态适配，存在高不确定性

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - Unlabeled |  |  |  |
  - Unlabeled |  |  |  |

- sources (初报与当时材料):
  - initial_report: https://static.sse.com.cn/stock/disclosure/announcement/c/202506/002098_20250630_D74O.pdf
  - time_slice_supporting: https://static.sse.com.cn/stock/disclosure/announcement/c/202506/002098_20250630_D74O.pdf

- notes: 当前仅能稳定提取“企业披露与投入方向”特征；若后续出现明确产能出货、重大订单与行业渗透的多源确认，可再回补标签。
---

# 数据中心-中国-2025Q3

---
## news_id: CNDC-2025-07-001
- domain: 数据中心
- initial_report_date: 2025-07-11
- title: 发改委/能源局下达2025/2026可再生能源消纳责任权重，并首次对“国家枢纽节点新建数据中心”明确绿电消费比例
- label: Major
- hard_negative: false
- summary: 以制度方式把“枢纽节点新建数据中心=绿电消费比例要求”固化到消纳机制与绿证核算框架中，直接抬升枢纽新建项目的用电合规门槛。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: tighten
  - supply_demand: tighten

- subsequent_impact_path: 绿电消费比例要求与“以绿证核算”的制度绑定，使枢纽节点新建数据中心在选址、电力采购（绿电/绿证）、并网与用电合同上被迫前置规划；后续在国家能源主管部门复盘中被再次点名，成为绿证交易“量价齐升”和高耗能/新型负荷绿电消费扩张的重要制度抓手。
- observable_features_at_time:
  - 文件性质：约束性指标（2025）+预期性目标（2026），并配套考核/评估机制
  - 明确引入“重点用能行业绿色电力消费比例”，首次覆盖“国家枢纽节点新建数据中心”（披露口径明确）
  - 绿电消费比例：国家枢纽节点新建数据中心为80%（初报时点公开解读/报道明确）
  - 核算机制：以绿证为主要核算凭证（绿证制度与数据中心用电合规绑定）
  - 约束类型：电力采购与用能合规（绿电/绿证）、项目准入与选址（枢纽节点）
  - 影响范围：跨省、跨枢纽节点；对新建项目更刚性，存量影响偏间接
  - 缺失字段：按单项目MW、时间表（COD/送电）多为Unknown

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管/能源主管部门发布会 | 2026-01-30 | https://www.nea.gov.cn/20260130/b5b729cb7ad74723bcd614b663c75da6/c.html | 明确回顾“同年7月通知”对国家枢纽节点新建数据中心提出绿电消费比例要求，并强调以绿证核算
  - 权威财经媒体 | 2026-01-30 | https://www.21jingji.com/article/20260130/herald/e84bcb80b7d7d08a4647059116390871.html | 报道能源局披露绿证交易爆发式增长，并将“7月通知对数据中心明确比例要求+绿证核算”作为关键制度背景

- sources (初报与当时材料):
  - initial_report: https://www.ndrc.gov.cn/xxgk/zcfb/tz/202507/t20250711_1399141.html
  - time_slice_supporting: https://www.reuters.com/sustainability/boards-policy-regulation/china-sets-its-first-renewable-standards-steel-cement-polysilicon-2025-07-11/ , https://paper.people.com.cn/zgnyb/pc/content/202507/14/content_30087752.html

- notes: “80%”比例在初报时点主要以媒体/解读形式明确；避免把后续交易量、价格等数字倒灌为当时可观测特征。
---

## news_id: CNDC-2025-07-002
- domain: 数据中心
- initial_report_date: 2025-07-08
- title: 六部门启动2025年度国家绿色数据中心推荐（PUE≤1.30、上架率≥60%、规模≥3000机架、原则上位于枢纽/算电协同试点）
- label: Major
- hard_negative: false
- summary: 以“名单制+硬指标”推动数据中心供给侧出清与升级，把PUE、上架率、规模、区位与绿电消纳等要求显性化为准入与评价框架。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: 推荐工作把“能效+利用率+布局”从倡议推进到可执行的评价与名单管理；后续进入公示/发布环节，形成对新增与存量改造的持续约束（尤其是PUE、上架率、区位与可再生能源利用要求），并与国家“绿色算力设施”名单形成政策组合，强化“提质控量”的行业导向。
- observable_features_at_time:
  - 发文主体：工信部/发改委/商务部/金融监管总局/国管局/能源局六部门联合
  - 指标硬约束：PUE≤1.30；原则上达到《GB40879-2021》2级及以上；满足《绿色数据中心评价》二级及以上（以通知/转载为准）
  - 规模门槛：数据中心规模不小于3000个标准机架（部分类型除外）
  - 运营门槛：上架率不低于60%，并要求算力资源使用率行业先进
  - 区位门槛：2022年后建设的数据中心原则上位于全国一体化算力网络枢纽或算电协同试点区域
  - 约束类型：能效、利用率、布局、绿电消纳（与省级消纳权重衔接）
  - 影响范围：跨行业（工业/信息通信/互联网/金融/公共机构/能源等六类）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管/名单公示（附件PDF） | 2025-10-29 | https://kcycrawlerfile.oss-cn-beijing.aliyuncs.com/2025/10/29/ECED4E057E6DED9BCC9F4E18D9BC95ED.pdf | 体现推荐工作进入“名单化管理”阶段，覆盖多领域并形成可核验清单
  - 行业媒体/公告转发（含名单） | 2025-12-29 | https://finance.sina.com.cn/tech/digi/2025-12-29/doc-inheneyq4827378.shtml | 报道六部门公布“国家绿色算力设施名单”，将绿色低碳要求扩展到算力设施层面并形成持续约束

- sources (初报与当时材料):
  - initial_report: https://www.h2o-china.com/news/359065.html
  - time_slice_supporting: https://finance.people.com.cn/n1/2025/0709/c1004-40517992.html , https://gxt.fujian.gov.cn/jdhy/zxzcfg/gjzcfg/202507/t20250717_6968415.htm

- notes: 该条的“重大性”来自制度化的硬指标与名单制（可迁移为LLM特征）；不等同于单个项目新闻。
---

## news_id: CNDC-2025-07-003
- domain: 数据中心
- initial_report_date: 2025-07-24
- title: 中国拟建“算力资源统一售卖/调度”网络并开展全国评估，以应对地方数据中心过度建设与低利用率
- label: Major
- hard_negative: false
- summary: 国家层面拟通过统一平台/网络盘活冗余算力并抑制无序扩张，直接指向行业“供给出清+跨域调度+提升利用率”的结构性转向。

- axes_and_direction:
  - pace: mixed
  - cost: down
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 在“过度建设—低利用率—财务不可持续”的压力下，政策与产业推进从“继续建”转向“统一纳管、跨域调度、资源池化”，后续算力平台与调度体系的里程碑进展被行业组织与权威媒体持续提及，构成“提质控量+调度增效”的核心治理框架之一。
- observable_features_at_time:
  - 事件性质：国家层面“全国评估+拟建统一售卖/调度网络”的治理动作，而非单一企业项目
  - 问题指向：地方政府背书的数据中心扩张导致“容量过剩/利用率偏低”（初报明确）
  - 机制路径：通过国家级平台连接分散算力，形成可交易/可调度的“统一入口”
  - 约束类型：从土地/能耗等硬约束，转向“利用率/可交易性/可调度性”的系统性约束
  - 对行业变量的可复用信号：是否出现“全国评估/统一平台/售卖冗余算力/压降无序扩张”关键词
  - 缺失字段：具体覆盖范围、落地时间表、平台规则细则（初报多为Unknown）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 行业组织/平台里程碑复盘 | 2026-01-06 | https://www.odcc.org.cn/news/p-2008360569926410242.html | 回顾2025年中国算力平台在监测、匹配、调度等维度的推进，体现“统一平台化治理”持续落地
  - 权威媒体深度稿 | 2026-01-28 | https://www.xinhuanet.com/20260128/037b1159b26645dea4648c535571ca3e/c.html | 总结算力发展趋势由分散走向全国一体化、跨地域调度平台逐步完善，呼应初报“统一网络/调度”方向

- sources (初报与当时材料):
  - initial_report: https://www.reuters.com/technology/china-plans-network-sell-surplus-computing-power-crackdown-data-centre-glut-2025-07-24/
  - time_slice_supporting: https://www.datacenterdynamics.com/en/news/chinese-government-plans-data-center-capacity-reseller-network-amid-overbuild-concerns/ , https://www.lightreading.com/data-centers/china-to-set-up-cloud-service-selling-spare-data-center-capacity---report

- notes: 初报可观测信息偏“治理意图+机制框架”，缺少可量化KPI；但其后续影响在“纳管/平台化/调度”体系持续出现，满足多源影响门槛。
---

## news_id: CNDC-2025-08-001
- domain: 数据中心
- initial_report_date: 2025-08-06
- title: 国家数据局公开征求全国一体化算力网相关技术文件意见（算力池化/安全等），标志建设从谋划进入落地应用阶段
- label: Major
- hard_negative: false
- summary: 通过“标准/技术文件+征求意见”把算力并网、池化、监测、调度、安全等能力变为可实施的接口与规范，为跨主体调度与统一纳管提供工程化抓手。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 标准化把“算力资源并网—监测一本账—调度一张网”从概念转为工程接口，降低跨主体互联互通摩擦；后续数博会期间监测调度平台发布并在2026年初被总结为阶段性成效，形成全国一体化算力网的关键底座。
- observable_features_at_time:
  - 事件类型：监管机构牵头的“公开征求意见”（标准化/接口化信号强）
  - 明确指出：9项技术文件研制意味着从谋划布局进入落地应用阶段
  - 覆盖能力：算力并网、资源管理与调度、计费、监测接口、算力中心能力、智算中心池化、安全保护等（按通知口径）
  - 目标表述：“全国算力资源一盘棋、监测一本账、调度一张网”
  - 约束类型：技术标准接口与合规要求（并网/监测/调度/安全）
  - 影响范围：跨省、跨运营商、跨架构（通算/智算/超算）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体/阶段性成效总结 | 2026-01-09 | https://home.wuhan.gov.cn/mtbd/202601/t20260109_2709011.shtml | 将“监测调度试验验证平台正式发布并实现对枢纽/运营商等监测调度”列为算力一体化阶段性进展
  - 权威媒体/数据要素改革复盘 | 2026-01-08 | https://finance.sina.com.cn/roll/2026-01-08/doc-inhfpwux4035825.shtml | 复盘算力一体化进展，点名监测调度试验验证平台实现对枢纽、运营商与超算互联网的监测调度

- sources (初报与当时材料):
  - initial_report: https://www.nda.gov.cn/sjj/zwgk/tzgg/0806/20250806144624952259412_pc.html
  - time_slice_supporting: https://www.nda.gov.cn/sjj/ywpd/szkjyjcss/0608/ff808081-96b466bd-0197-4f0d4d76-0730.pdf

- notes: 初报可观测特征可直接抽象为“是否启动标准化征求意见/覆盖哪些接口能力/是否明确一盘棋一本账一张网”等高迁移信号。
---

## news_id: CNDC-2025-08-002
- domain: 数据中心
- initial_report_date: 2025-08-29
- title: 数博会期间全国一体化算力网监测调度试验验证平台正式发布（强调跨主体、跨架构、跨区域互联互通）
- label: Major
- hard_negative: false
- summary: 全国级监测调度平台发布把“算力纳统、监测、调度、撮合”推向可运行系统，为跨区域调度与资源池化提供可执行基础设施。

- axes_and_direction:
  - pace: accelerate
  - cost: down
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 平台发布后，算力资源从“分散建设”进入“可监测、可登记、可调度”的治理框架；在后续复盘中被用于说明全国一体化算力网建设取得阶段性进展，强化跨域调度与公共算力资源体系建设。
- observable_features_at_time:
  - 发布场景：2025数博会“数据基础设施主题交流活动”（具备国家级活动背书）
  - 平台定位：国家数据局指导建设，目标为“高质量算力供给体系”与全国范围互联
  - 明确能力口径：跨主体、跨架构（通/智/超）、跨区域互联互通（初报明确）
  - 对数据中心的可复用信号：是否出现“监测调度平台”“统一登记/标识”“跨域调度”关键词
  - 约束类型：纳管与调度规则（而非单一项目审批）
  - 缺失字段：平台规则细则、强制接入要求（初报多为Unknown）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体/阶段性成效总结 | 2026-01-14 | https://home.wuhan.gov.cn/mtbd/202601/t20260114_2711520.shtml | 明确写到平台“初步实现对枢纽、运营商及超算互联网的监测调度”，作为算力一体化进展
  - 行业组织/平台年度复盘 | 2026-01-06 | https://www.odcc.org.cn/news/p-2008360569926410242.html | 复盘2025算力平台推进路径（监测、匹配、调度），佐证平台化治理持续推进

- sources (初报与当时材料):
  - initial_report: https://www.stcn.com/article/detail/3304428.html?u_asig=ffbfd&u_atoken=1b9bad005384883b5821f2977ac26975
  - time_slice_supporting: https://www.ict.ac.cn/xwgg/jssxw/202509/t20250902_7957547.html , https://www.pcl.ac.cn/html/943/2025-09-04/content-4627.html

- notes: 注意避免把后验总结中的覆盖规模/接入数量当作“初报可观测数字”；若训练特征需量化，优先用初报文本中明确披露的口径字段。
---

## news_id: CNDC-2025-09-001
- domain: 数据中心
- initial_report_date: 2025-09-26
- title: 《关于加强数字经济创新型企业培育的若干措施》提出加快构建全国一体化算力网、推动算力资源池化并网运行
- label: Major
- hard_negative: false
- summary: 多部委联合文件把“全国一体化算力网=监测+统一调度+弹性供给+安全保障”写入政策条款，并要求枢纽节点提供低成本、广覆盖算力服务，强化需求侧可获得性。

- axes_and_direction:
  - pace: accelerate
  - cost: down
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 通过“企业培育库+算力供给支撑”将算力供给从基础设施建设延伸到面向创新企业的普惠服务供给；后续权威媒体与行业组织在2026年初的趋势/复盘中持续强调“全国一体化、跨域调度平台完善”，体现政策组合对行业运行方式的长期影响。
- observable_features_at_time:
  - 文件属性：多部门联合（发改委、国家数据局、财政、央行、金融监管、证监等参与）
  - 明确提出：算力资源“有序池化、并网运行”
  - 明确功能：算力统筹监测、统一调度、弹性供给、安全保障（条款级描述）
  - 明确对象：鼓励枢纽节点面向“数创企业”提供低成本、广覆盖、可靠安全算力服务
  - 约束类型：从“建机房”转向“服务供给能力+统一调度能力”的制度约束
  - 缺失字段：MW/机架/EFLOPS等量化目标（在该文件条款中多为Unknown）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体深度稿 | 2026-01-28 | https://www.xinhuanet.com/20260128/037b1159b26645dea4648c535571ca3e/c.html | 指出产业架构从分散走向全国一体化、跨地域调度平台逐步完善，呼应文件“池化并网+统一调度”
  - 行业组织/年度里程碑复盘 | 2026-01-06 | https://www.odcc.org.cn/news/p-2008360569926410242.html | 以监测/匹配/调度为主线复盘算力平台进展，体现“政策条款→工程化落地”的延续性

- sources (初报与当时材料):
  - initial_report: https://www.nda.gov.cn/sjj/zwgk/zcfb/0926/20250926162823983586641_pc.html
  - time_slice_supporting: https://www.nda.gov.cn/sjj/zwgk/tzgg/0806/20250806144624952259412_pc.html

- notes: 该条“重大性”来自跨部门政策把算力网络能力写入制度工具箱；对单个数据中心项目的直接量化映射在初报时点通常不可得。
---

## news_id: CNDC-2025-07-004
- domain: 数据中心
- initial_report_date: 2025-07-08
- title: 呼和浩特提出打造“最强绿色算力供给者”，披露签约项目总投资超500亿元、预计年底投用算力12万P
- label: NotMajor
- hard_negative: true
- summary: 地方愿景与签约口径具有强传播性，但缺少跨地区、跨公用事业或跨供应链的硬约束变化与后续多源持续确认，难作为行业结构性变量。

- axes_and_direction:
  - pace: uncertain
  - cost: mixed
  - constraint: uncertain
  - supply_demand: loosen

- subsequent_impact_path: 后续全国层面治理重点转向“控制无序扩张、提升利用率、统一纳管与调度”，地方“签约/目标口径”未被持续引用为全国性拐点；缺乏监管机构/系统运营商/权威研究在数月后持续跟踪其对行业装机节奏或成本结构的长期影响。
- observable_features_at_time:
  - 信息类型：地方发展表述+签约金额/算力目标（非监管约束、非并网批复）
  - 披露规模：总投资>500亿元；年底投用算力12万P（口径依赖地方披露）
  - 缺失：具体项目清单、送电/并网节点、绿电合约结构、上架率/利用率目标（多为Unknown）
  - 约束类型：更像招商与形象工程叙事，硬约束信息不足
  - 影响范围：以单城/单园区为主，跨区域外溢不明确

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体/行业治理转向 | 2025-07-24 | https://www.reuters.com/technology/china-plans-network-sell-surplus-computing-power-crackdown-data-centre-glut-2025-07-24/ | 指出地方中心扩张导致容量过剩与低利用率风险，强化“签约口径≠可持续投运”的验证
  - 监管/名单制结果（用于反证“未形成全国性拐点”） | 2025-10-29 | https://kcycrawlerfile.oss-cn-beijing.aliyuncs.com/2025/10/29/ECED4E057E6DED9BCC9F4E18D9BC95ED.pdf | 全国层面以“绿色数据中心名单”进行集中评价与筛选，地方口径未被稳定确认为全国性关键变量

- sources (初报与当时材料):
  - initial_report: https://www.news.cn/20250708/74ab5574d0ea4cb4b2f3a23bce4ea952/c.html
  - time_slice_supporting: Unknown

- notes: hard_negative理由：高热度/大数字，但缺少硬约束信息与后续多源影响确认；更适合作为“热度代理风险”样本。
---

## news_id: CNDC-2025-07-005
- domain: 数据中心
- initial_report_date: 2025-07-14
- title: “8省20个智算中心/算力项目已备案、总投资264.79亿元”汇总式文章传播
- label: NotMajor
- hard_negative: true
- summary: 汇总式“备案清单+投资额”看似重大，但备案≠开工≠送电≠上架；缺乏后续独立来源证明其对全国装机/投运节奏或供需拐点产生长期影响。

- axes_and_direction:
  - pace: uncertain
  - cost: mixed
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 后续行业治理与政策工具集中在“绿电比例、能效、上架率、统一调度”，而非对单批备案汇总进行持续跟踪；该类清单难以满足“至少两家独立来源在数月后明确描述长期影响”的门槛，因此作为hard negative。
- observable_features_at_time:
  - 信息类型：媒体/机构汇总“备案项目”并列举投资额与建设期
  - 量化信息：总投资264.79亿元；项目跨多省（但口径为“据不完全统计”）
  - 关键缺失：并网批复/送电时间、负荷协议、电价/绿电合约、上架率/利用率（多为Unknown）
  - 约束类型：备案阶段信息，离“可投运”与“可持续运营”距离远
  - 影响范围：跨省但分散，难直接映射全国供需拐点

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管/名单制结果（反证：全国关注点在提质筛选） | 2025-10-29 | https://kcycrawlerfile.oss-cn-beijing.aliyuncs.com/2025/10/29/ECED4E057E6DED9BCC9F4E18D9BC95ED.pdf | 全国层面以“绿色数据中心名单”作为可核验结果，而非“备案汇总”作为行业变量
  - 权威媒体/过度建设风险提示 | 2025-07-24 | https://www.reuters.com/technology/china-plans-network-sell-surplus-computing-power-crackdown-data-centre-glut-2025-07-24/ | 提醒地方过度建设与低利用率风险，说明备案规模并不等同结构性增量

- sources (初报与当时材料):
  - initial_report: https://www.dtdata.cn/news/show/3498.html
  - time_slice_supporting: Unknown

- notes: hard_negative理由：当时“金额+数量”极像重大，但证据等级低且缺少后续稳定确认；适合训练模型识别“备案/签约新闻的陷阱”。
---

## news_id: CNDC-2025-07-006
- domain: 数据中心
- initial_report_date: 2025-07-23
- title: 启迪设计公告中标河南空港智算中心三期一批次算力集群项目（中标价8.6亿元）
- label: NotMajor
- hard_negative: true
- summary: 单体项目金额较大、易被误判为行业拐点，但其影响边界主要在单省/单园区，难满足“多源确认的长期行业变量改变”。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: uncertain
  - supply_demand: loosen

- subsequent_impact_path: 后续全国层面的关键变量仍由“绿电比例/能效/上架率/统一调度”定义，该项目未被多家独立来源在数月后反复引用为影响全国装机或成本结构的关键事件，因此作为hard negative。
- observable_features_at_time:
  - 中标金额：8.6亿元（建设费含税，公告口径）
  - 工期：150日历天内完成安装调试并初验（项目级时间表清晰）
  - 技术路线：强调国产化与液冷（但对全国供给约束影响未知）
  - 关键缺失：并网送电节点、负荷合约、电价/绿电比例、机架规模与上架率目标（多为Unknown）
  - 影响范围：单项目/单区域为主

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管/全国筛选口径（反证“行业变量由名单/硬指标定义”） | 2025-10-29 | https://kcycrawlerfile.oss-cn-beijing.aliyuncs.com/2025/10/29/ECED4E057E6DED9BCC9F4E18D9BC95ED.pdf | 全国层面以绿色数据中心名单衡量“能效与利用率”，单项目中标难以构成行业拐点
  - 权威媒体/行业治理转向 | 2026-01-28 | https://www.xinhuanet.com/20260128/037b1159b26645dea4648c535571ca3e/c.html | 强调算力从分散走向一体化与跨域调度平台完善，行业变量更偏系统治理而非单项目

- sources (初报与当时材料):
  - initial_report: https://cj.sina.cn/articles/view/5953189932/162d6782c06702ynd8?froms=ggmp
  - time_slice_supporting: https://wap.eastmoney.com/a/202507293470570415.html

- notes: hard_negative理由：项目级“金额+工期”信息充分、传播性强，但缺少后续多源确认其对全国装机节奏/成本结构/供需拐点产生长期影响。
---

## news_id: CNDC-2025-09-002
- domain: 数据中心
- initial_report_date: 2025-09-04
- title: 新华社视点“算力热度持续攀升，如何扩容？”（以多地扩容案例与大会信息为主）
- label: NotMajor
- hard_negative: true
- summary: 典型“热度高、案例多”的综合稿，信息密集但多为叙事与案例堆叠，缺乏可迁移的硬约束变化量与后续多源确认的长期影响路径。

- axes_and_direction:
  - pace: accelerate
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: tighten

- subsequent_impact_path: 后续真正形成结构性约束的，仍是“枢纽新建绿电比例、绿色数据中心名单、统一监测调度平台与标准化接口”等制度化工具；综合稿本身难作为“初次报道的重大事件”满足多源影响门槛，因此作为hard negative。
- observable_features_at_time:
  - 信息类型：综合报道/观点型，非监管文件/非项目批复
  - 披露方式：举例多地扩容与大会信息（但缺少统一口径的可比指标）
  - 关键缺失：统一的MW/机架/送电时间表、规则条款、约束阈值（多为Unknown）
  - 可复用信号：是否为“综合稿/趋势稿”，而非具体制度或硬约束变化
  - 证据等级：权威媒体，但证据形态偏叙事而非可核验制度条款

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管/硬约束制度（对照组） | 2026-01-30 | https://www.nea.gov.cn/20260130/b5b729cb7ad74723bcd614b663c75da6/c.html | 绿电比例要求与绿证核算是更可核验的长期约束
  - 监管/名单制结果（对照组） | 2025-10-29 | https://kcycrawlerfile.oss-cn-beijing.aliyuncs.com/2025/10/29/ECED4E057E6DED9BCC9F4E18D9BC95ED.pdf | 名单制把能效与利用率落到可核验清单，区别于趋势性综合稿

- sources (初报与当时材料):
  - initial_report: https://www.news.cn/fortune/20250904/018a5799661444df96a952ad1ec27b78/c.html
  - time_slice_supporting: Unknown

- notes: hard_negative理由：内容“看起来很重大”，但缺乏制度阈值与后续多源确认的长期影响链条；适合训练模型识别“权威综合稿≠重大事件”。
---

## news_id: CNDC-2025-09-003
- domain: 数据中心
- initial_report_date: 2025-09-25
- title: 武当云谷大数据中心二期主体封顶（项目投资、机架规模与完工节点披露）
- label: NotMajor
- hard_negative: true
- summary: 单项目进度节点具备“规模/机架/完工时间”要素、易被误判为重大，但影响边界局部且缺少后续多源把其上升为行业变量拐点的确认。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: uncertain
  - supply_demand: loosen

- subsequent_impact_path: 后续行业更关注“绿电比例、能效、上架率、统一调度平台”，而单个地方数据中心工程节点难被持续引用为全国装机或成本结构拐点；因此作为hard negative，并用全国名单制与治理转向作反证。
- observable_features_at_time:
  - 工程节点：主体结构封顶（可核验的建设进度信息）
  - 规模口径：二期规划机架7000架；完工节点2026年12月底（初报披露）
  - 总体投资口径：约35亿元（项目级）
  - 冷却/资源要素：依托水库冷水资源（但对全国范围约束松紧影响未知）
  - 关键缺失：并网送电批复、用电合同与绿电比例、上架率/利用率目标（多为Unknown）
  - 影响范围：地方性单项目

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 监管/名单制结果（反证：全国可核验口径不依赖单项目节点） | 2025-10-29 | https://kcycrawlerfile.oss-cn-beijing.aliyuncs.com/2025/10/29/ECED4E057E6DED9BCC9F4E18D9BC95ED.pdf | 全国层面以名单制衡量绿色与利用率，单项目封顶难构成行业变量拐点
  - 权威媒体/行业治理转向 | 2025-07-24 | https://www.reuters.com/technology/china-plans-network-sell-surplus-computing-power-crackdown-data-centre-glut-2025-07-24/ | 指出行业存在容量过剩与低利用率风险，项目级扩张并不天然等同有效供给

- sources (初报与当时材料):
  - initial_report: https://www.suanliai.cn/shishiyaowen/618.html
  - time_slice_supporting: Unknown

- notes: hard_negative理由：信息“像重大”（有投资/机架/时间表），但缺少跨区域与制度层面的后续确认；适合作为“项目新闻误判”样本。
---

## news_id: CNDC-2025-08-003
- domain: 数据中心
- initial_report_date: 2025-08-23
- title: 工信部相关会议/报道披露我国在用算力中心机架与PUE等统计，并强调持续推进国家绿色数据中心建设
- label: Unlabeled
- hard_negative: false
- summary: 统计口径与政策表述可用于描述行业现状，但难直接满足“多源确认其造成长期行业变量改变”的重大事件门槛，暂不稳定标注。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: Unknown（更像“现状披露+政策方向”，而非清晰的单一事件冲击链条）。
- observable_features_at_time:
  - 信息类型：会议/行业现状统计披露（机架规模、智算规模、PUE等）
  - 政策方向：强调引导合理布局、持续开展国家绿色数据中心建设（方向性强）
  - 缺失：新增装机硬约束、强制性规则阈值、项目级并网/送电时间表（多为Unknown）
  - 可复用信号：是否出现官方“机架/PUE/算力规模”统计披露

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - Unlabeled |  |  |  |
  - Unlabeled |  |  |  |

- sources (初报与当时材料):
  - initial_report: https://www.stdaily.com/web/gdxw/2025-08/23/content_389429.html
  - time_slice_supporting: https://www.news.cn/info/20250825/4b42fad22aa240c4b60879005d8e5ce8/c.html

- notes: 若后续出现“该统计披露触发的监管措施/名单制调整/投资与审批拐点”的多源确认，可再回补标签。
---

# 数据中心-中国-2025Q4

---
## news_id: CNDC-2025-10-001
- domain: 数据中心
- initial_report_date: 2025-10-28
- title: 工信部公示《2025年度国家绿色数据中心名单》（公示期10/28-11/3；约60家）
- label: Major
- hard_negative: false
- summary: 以“名单制+硬指标”推进数据中心绿色化与集约化，显性化PUE、上架率、规模、可再生能源利用等准入/评价框架。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: 名单制把“能效/利用率/绿电消纳”从倡议推到可执行管理工具，形成对新建与存量改造的持续约束与政策资源分配依据（补贴、评优、监管关注等），强化行业“提质控量”的治理方向。
- observable_features_at_time:
  - 事件类型：国家级公示名单（可核验、可追踪）
  - 公示期：2025-10-28至2025-11-03（明确）
  - 覆盖领域：工业、信息通信、能源、互联网、金融、公共机构（跨行业）
  - 指标信号：强调能效、绿色低碳、布局合理、管理完善（硬约束方向明确）
  - 变化量：入选数量/名单范围为公开信息；单体MW/机架/送电节点多为Unknown
  - 约束类型：能效（PUE）、可再生能源利用、运行管理与合规（多选）
  - 证据等级：部委公示（高）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体转载/解读 | 2025-10-31 | https://js.people.com.cn/BIG5/n2/2025/1031/c360301-41396756.html | 报道“2025年度国家绿色数据中心名单公示、共60家”等关键信息并呈现地方入选情况
  - 权威媒体转载 | 2025-10-28 | https://news.qq.com/rain/a/20251028A05SKP00 | 转载公示文本要点（公示期、反馈渠道等），说明进入名单化管理流程

- sources (初报与当时材料):
  - initial_report: https://news.qq.com/rain/a/20251028A05SKP00
  - time_slice_supporting: https://jlts.com.cn/back/super/file/showImg.do?fileId=0afef163-7334-4ade-b687-2dd764f69b72.pdf

- notes: 本期距2025Q4结束仅约1个月，严格“≥3–6个月 hindsight”窗口不足；该条属于制度型事件，先行标注为Major，但建议在2026Q2后复核其执行强度与扩散路径。
---

## news_id: CNDC-2025-11-002
- domain: 数据中心
- initial_report_date: 2025-11-13
- title: 北京经开区发布2025年数据中心“白名单”（动态管理；配套算力补贴/绿色资金等支持）
- label: Major
- hard_negative: false
- summary: 以区级能耗/能效/可再生能源利用/智算转型等综合评估建立白名单，并绑定财政与政策支持，形成地方层面“能耗管理+激励约束”机制样板。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: 白名单把“能耗指标—项目准入/支持—持续改造”联动起来，通过动态管理与补贴资金引导数据中心绿色集约与智算转型，强化一线城市对能耗与产业承载的精细化治理。
- observable_features_at_time:
  - 事件类型：地方政府（园区）白名单制度（可执行、可动态更新）
  - 评估维度：能源消费、能效水平、可再生能源利用、智算转型（明确）
  - 支持工具：算力补贴、绿色发展资金、申报国家/市级政策支持（明确）
  - 影响范围：单一区域（北京经开区），但具备可复制的治理框架特征
  - 变化量：入选项目数量与企业名称（有披露）；MW/机架等细化字段多为Unknown
  - 约束类型：能耗管理、能效、绿电/可再生能源、产业转型（多选）
  - 证据等级：地方政府官网（高）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 地方政府官网 | 2025-11-13 | https://www.beijing.gov.cn/ywdt/gzdt/202511/t20251113_4279627.html | 官方说明白名单机制、评估口径与支持方式
  - 园区管委会官网 | 2025-11-13 | https://kfqgw.beijing.gov.cn/zwgkkfq/ztzl/lqztkfq/lqzx/zxxx/202511/t20251120_4288766.html | 举例披露入选数据中心与余热回收/转型方向等执行细节

- sources (初报与当时材料):
  - initial_report: https://www.beijing.gov.cn/ywdt/gzdt/202511/t20251113_4279627.html
  - time_slice_supporting: https://kfqgw.beijing.gov.cn/zwgkkfq/ztzl/lqztkfq/lqzx/zxxx/202511/t20251120_4288766.html

- notes: 地方性事件但机制强（白名单+资金激励+动态管理），对“能耗约束—产业承载”有直接训练价值；hindsight窗口仍偏短，建议后续复核是否扩展到更广区域/形成约束升级。
---

## news_id: CNDC-2025-11-003
- domain: 数据中心
- initial_report_date: 2025-11-13
- title: 云南公示2025年第一批绿电直连项目结果（含智算中心项目；风光合计约434.92MW）
- label: Major
- hard_negative: false
- summary: 省级层面进入“绿电直连”项目化落地阶段，首次批次清单公开，数据中心/智算中心作为负荷类型被纳入，提供“电力约束下的新供给路径”。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 绿电直连从政策原则推进到省级项目清单与评审流程（含电网企业意见），为数据中心获得可溯源绿电与缓解并网/电价约束提供可复制的项目范式，推动“算电协同”向工程化落地过渡。
- observable_features_at_time:
  - 事件类型：省级项目清单公示（项目化、可核验）
  - 规模：风光总规模约434.92MW（明确）
  - 负荷类型：包含智算中心（明确）
  - 流程：专家评审、听取相关部门与电网企业意见后公示（明确）
  - 公示期：5个工作日（2025-11-13至2025-11-19）（明确）
  - 约束类型：电力接入/专线与源荷匹配、绿电溯源与合规（多选）
  - 缺失字段：对应数据中心MW负荷、直连线路电压等级/里程、COD多为Unknown

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 行业媒体汇总转发 | 2025-11-13 | https://mguangfu.bjx.com.cn/mnews/20251113/1469917.shtml | 转载公示要点（规模、项目清单、时间）
  - 权威门户财经转载 | 2025-11-13 | https://finance.sina.com.cn/roll/2025-11-13/doc-infxhkct2400125.shtml | 报道入选项目数量、业主类型与流程要点

- sources (初报与当时材料):
  - initial_report: https://mguangfu.bjx.com.cn/mnews/20251113/1469917.shtml
  - time_slice_supporting: https://www.pvmeng.com/2025/11/13/48888/, https://mguangfu.bjx.com.cn/mnews/20251113/1469917.shtml

- notes: 对数据中心行业变量的直接影响依赖“直连线路与负荷侧投运节奏”，初报多为Unknown；hindsight窗口偏短，建议2026H1补充“下达/开工/并网/实际供电”确认链条。
---

## news_id: CNDC-2025-11-004
- domain: 数据中心
- initial_report_date: 2025-11-28
- title: 青海公示首批绿电直连试点项目（7个；电源规模合计约223.793万千瓦；评审含电网企业参与）
- label: Major
- hard_negative: false
- summary: 省级首批绿电直连试点清单公示，形成“第三方评估+部门+电网企业联合评审”的制度化流程，为高耗能负荷（含算力）提供可复制的直连机制环境。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 绿电直连试点通过清单化与联合评审机制进入执行阶段，后续有助于形成“绿电供给—负荷直连—产业承载”的省域模式，为算力/数据中心在资源型地区扩容提供电力合规与成本优化路径。
- observable_features_at_time:
  - 事件类型：省级首批试点项目清单公示（可核验）
  - 数量：7个项目（明确）
  - 电源规模：合计约223.793万千瓦（明确）
  - 评审机制：第三方机构+相关部门+电网企业联合评审评估（明确）
  - 公示期：2025-11-28至2025-12-04（明确）
  - 约束类型：电源侧建设与负荷匹配、专线接入、绿电物理溯源（多选）
  - 与数据中心关系：清单中是否含“智算/数据中心”需逐条核验（部分Unknown）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威门户财经转载 | 2025-12-01 | https://finance.sina.com.cn/esg/2025-12-01/doc-infzhaup3854989.shtml | 报道首批试点项目数量、规模与公示期
  - 行业媒体转载 | 2025-12-02 | https://mnewenergy.in-en.com/html/newenergy-2446426.shtml | 转载并补充政策依据与联系方式等可核验要素

- sources (初报与当时材料):
  - initial_report: https://mnewenergy.in-en.com/html/newenergy-2446426.shtml
  - time_slice_supporting: https://finance.sina.com.cn/roll/2025-12-01/doc-infzhiah4341679.shtml?froms=ggmp

- notes: 属于“制度+清单”型落地；对数据中心的直接影响需后续补齐清单中负荷类型与投运信息（hindsight窗口偏短）。
---

## news_id: CNDC-2025-12-005
- domain: 数据中心
- initial_report_date: 2025-12-17
- title: 河北公示2025年绿电直连拟安排第一批项目（共31个；总规模约427.752万千瓦；负荷覆盖数据中心等）
- label: Major
- hard_negative: false
- summary: 省级绿电直连进入大规模项目化安排阶段（GW级），且明确负荷覆盖数据中心等类型，显示“直连”从试点向批量化推进。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: loosen
  - supply_demand: loosen

- subsequent_impact_path: 河北以批量项目清单推进绿电直连，为数据中心等高负荷行业提供“新能源直供”选项；后续若进入下达与建设，将对区域数据中心电力可得性、绿电合规与电价结构产生持续影响。
- observable_features_at_time:
  - 事件类型：省级第一批项目公示（项目化、规模化）
  - 项目数量：31个（明确）
  - 总规模：约427.752万千瓦（明确）
  - 负荷类型：覆盖钢铁、制造、生物、数据中心等（明确为“包含”）
  - 公示期：至2025-12-21（媒体转述；需以原公示为准）
  - 约束类型：电力接入/专线、源荷匹配、项目并网与消纳安排（多选）
  - 缺失字段：对应具体数据中心负荷MW与投运时间表多为Unknown

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 行业媒体转载 | 2025-12-18 | https://www.ditan.com/industry/pv/9436.html | 报道“31个项目、427.752万千瓦、负荷含数据中心”等关键信息
  - 权威门户财经转载 | 2026-01-09 | https://finance.sina.com.cn/roll/2026-01-09/doc-inhfssrv0598583.shtml?froms=ggmp | 报道公示后续“下达/规模调整”等进展（用于验证从公示走向执行）

- sources (初报与当时材料):
  - initial_report: https://www.ditan.com/industry/pv/9436.html
  - time_slice_supporting: https://www.cpnn.com.cn/news/baogao2023/202512/t20251218_1854498.html

- notes: 该条对数据中心的“重大性”取决于后续是否形成可持续供电与负荷投运；hindsight窗口偏短，建议2026H1补齐“下达通知/开工/送电”证据链。
---

## news_id: CNDC-2025-12-006
- domain: 数据中心
- initial_report_date: 2025-12-29
- title: 六部门公告《2025年度国家绿色算力设施名单》（60个；覆盖工业/通信/能源/互联网/金融/公共机构）
- label: Major
- hard_negative: false
- summary: 将“绿色低碳”从数据中心扩展到更广义算力设施，并以名单方式跨行业落地，强化能效与绿色供能约束在算力基础设施层面的制度化。

- axes_and_direction:
  - pace: mixed
  - cost: up
  - constraint: tighten
  - supply_demand: mixed

- subsequent_impact_path: 名单制把绿色低碳要求扩展至“算力设施”口径并跨行业覆盖，强化政策资源配置与监管关注；与“绿色数据中心名单/白名单/绿电直连清单”形成组合拳，推动行业从“扩建”向“能效+绿电+利用率”约束下的高质量供给切换。
- observable_features_at_time:
  - 事件类型：六部门联合公告（制度强、跨部门）
  - 名单规模：60个算力设施（明确）
  - 覆盖行业：工业、信息通信、能源、互联网、金融、公共机构（明确）
  - 政策依据：引用《2024—2025年节能降碳行动方案》（明确）
  - 约束类型：能效与绿色供能、名单化管理（多选）
  - 变化量：名单条目可逐条抽取（设施类型/主体/地域等），但单体MW/机架不一定全披露（部分Unknown）
  - 证据等级：部委联合公告（高）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 权威媒体转载（人民网） | 2025-12-29 | https://finance.eastmoney.com/a/202512293604762469.html | 报道“60个上榜、来源为工信部官网消息、跨行业覆盖”等要点
  - 权威财经快讯 | 2025-12-29 | https://www.stcn.com/article/detail/3562669.html | 快讯形式确认公告发布与名单属性（用于交叉验证）
  - 科技媒体转载（含名单） | 2025-12-29 | https://www.ithome.com/0/908/939.htm | 给出名单条目明细（便于结构化抽取）

- sources (初报与当时材料):
  - initial_report: https://www.ithome.com/0/908/939.htm
  - time_slice_supporting: https://finance.eastmoney.com/a/202512293604762469.html, https://www.stcn.com/article/detail/3562669.html

- notes: 与“国家绿色数据中心名单（公示）”相比，该条更偏“算力设施”更广口径；仍建议在2026H1复核“动态调整/配套资金/监管检查”等执行链条。
---

## news_id: CNDC-2025-10-007
- domain: 数据中心
- initial_report_date: 2025-10-30
- title: 泰康科技大健康总部智算中心项目封顶（总投资约150亿元的园区叙事）
- label: NotMajor
- hard_negative: true
- summary: 单项目金额巨大、传播上极像行业拐点，但缺少电力接入/并网、客户消纳、绿电合规等“硬约束字段”与多源持续确认，难直接推断其改变全国装机/投运节奏。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 截至2026-01-31，仅能确认项目建设节点与投资口径，未见监管机构/系统运营商/公用事业或业主对“送电投运、负荷锁定、长期电价/绿电合同”作出可核验披露；行业层面的结构性约束仍主要由“名单制能效/绿电直连清单”等制度工具驱动。
- observable_features_at_time:
  - 信息类型：工程节点（封顶）+投资额叙事（150亿元级）
  - 缺失：电力接入批复、专用变电站/送电日期、负荷协议、上架率与利用率目标（Unknown）
  - 约束类型：可能涉及电力与施工，但关键字段未披露（Unknown）
  - 影响范围：单项目/单园区，跨区域外溢不明确
  - 证据等级：产业媒体转述/项目报道（中）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 国家级制度工具（对照） | 2025-12-29 | https://finance.eastmoney.com/a/202512293604762469.html | 行业硬约束更集中体现在“绿色算力设施名单”等制度化工具，而非单一工程节点
  - 省级电力约束工具（对照） | 2025-12-18 | https://www.ditan.com/industry/pv/9436.html | 绿电直连进入批量清单化，体现结构影响更多来自规则/清单而非单点项目叙事

- sources (初报与当时材料):
  - initial_report: https://www.bdiesz.com/shishiyaowen/803.html
  - time_slice_supporting: Unknown

- notes: hard negative理由：具备“高金额+大叙事”的热度代理风险，但缺少可复用硬字段与后续多源确认其形成行业变量拐点。
---

## news_id: CNDC-2025-11-008
- domain: 数据中心
- initial_report_date: 2025-11-07
- title: 新华三“图灵小镇”落地青海（总投资80亿元；规划算力里程碑口径）
- label: NotMajor
- hard_negative: true
- summary: “80亿+万P规划”高度像重大事件，但多为规划/口径叙事；缺少电力送出/直连合同、客户签约、上架率等关键字段与独立后续验证。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 截至2026-01-31，公开信息主要集中在“点亮活动/规划目标/里程碑口径”，尚不足以形成对“可投运算力、供电约束、成本结构”的稳定判断；而行业结构性约束更由“绿色名单制+绿电直连清单”持续塑形。
- observable_features_at_time:
  - 披露口径：总投资80亿、算力规模目标（以媒体报道为主）
  - 缺失字段：实际可用算力上线节奏、送电节点/电网接入、绿电采购结构（Unknown）
  - 约束类型：电力与利用率是关键，但未披露可核验字段（Unknown）
  - 影响范围：地方园区项目，跨区域外溢不明确
  - 证据等级：产业媒体（中）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 国家级制度工具（对照） | 2025-12-29 | https://www.ithome.com/0/908/939.htm | 绿色算力设施名单以“可核验清单”方式推进约束，区别于规划口径叙事
  - 省级制度落地（对照） | 2025-11-13 | https://www.beijing.gov.cn/ywdt/gzdt/202511/t20251113_4279627.html | 地方对白名单/能耗等硬约束的治理更具可执行性

- sources (初报与当时材料):
  - initial_report: https://suanliai.cn/shishiyaowen/633.html
  - time_slice_supporting: Unknown

- notes: hard negative理由：传播度强、数字大，但关键硬信息缺失且短期内难以形成“长期行业变量改变”的可验证链条。
---

## news_id: CNDC-2025-11-009
- domain: 数据中心
- initial_report_date: 2025-11-17
- title: 新疆中芯数智绿能AI智算中心项目EPC招标启动（项目总投资约25亿元的招标叙事）
- label: NotMajor
- hard_negative: true
- summary: EPC招标与大投资额容易被误判为“供给拐点”，但仍处早期阶段，缺少并网/送电、负荷锁定与消纳路径的多源确认。

- axes_and_direction:
  - pace: uncertain
  - cost: uncertain
  - constraint: uncertain
  - supply_demand: uncertain

- subsequent_impact_path: 截至2026-01-31，公开信息主要停留在“招标/投资口径”，未见电网公司/监管/业主对投运时间、接入方案、客户与利用率进行独立披露；行业层面更具结构影响的是名单制与绿电直连等制度工具。
- observable_features_at_time:
  - 信息类型：招标公告（项目阶段早）
  - 变化量：总投资约25亿元（明确口径，但仍为规划/预算类）
  - 缺失：机架/MW、变电站/接入电压等级、送电时间表、客户签约（Unknown）
  - 约束类型：电力接入、设备交付、施工许可可能是瓶颈，但信息缺失（Unknown）
  - 影响范围：单项目；跨区域外溢不明确
  - 证据等级：产业媒体转述招标（中）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 国家级制度工具（对照） | 2025-10-28 | https://news.qq.com/rain/a/20251028A05SKP00 | 绿色数据中心名单公示体现更强的制度性约束与可核验口径
  - 省级清单化落地（对照） | 2025-12-18 | https://www.ditan.com/industry/pv/9436.html | 绿电直连清单化更直接改变电力约束环境

- sources (初报与当时材料):
  - initial_report: https://www.idcsummit.cn/shishiyaowen/426.html
  - time_slice_supporting: Unknown

- notes: hard negative理由：早期招标阶段不等于投运；缺少“电力/客户/利用率”硬字段与后续多源确认。
---

## news_id: CNDC-2025-12-010
- domain: 数据中心
- initial_report_date: 2025-12-22
- title: 中国移动·团结湖AI算力赋能中心（一期）预计2026年1月投运（总投资10亿；机柜2000个口径）
- label: NotMajor
- hard_negative: true
- summary: 具备“投资额+机柜数+投运时间”要素、传播上很像重大，但边界主要是地方公共算力平台，难以满足“改变全国装机/投运/供需拐点”的多源长期影响门槛。

- axes_and_direction:
  - pace: accelerate
  - cost: mixed
  - constraint: uncertain
  - supply_demand: loosen

- subsequent_impact_path: 截至2026-01-31，该事件主要是地方平台投运与招商签约；未见其引发跨区域电力/并网约束变化或行业层面供需拐点的持续确认，更多属于地方承接与产业服务能力提升。
- observable_features_at_time:
  - 投资额：总投资约10亿元（明确）
  - 规模：建设数据机柜2000个（明确）
  - 时间表：一期预计2026年1月投运（明确，但属项目口径）
  - 缺失：接入容量（MW）、电价/绿电合同结构、上架率/利用率目标（Unknown）
  - 影响范围：单城市/单园区（外溢有限）
  - 证据等级：产业媒体（中）

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 国家级制度工具（对照） | 2025-12-29 | https://www.ithome.com/0/908/939.htm | 行业层面更强约束来自国家级名单制
  - 地方政府治理工具（对照） | 2025-11-13 | https://www.beijing.gov.cn/ywdt/gzdt/202511/t20251113_4279627.html | 地方能耗治理通过白名单等机制更具结构性

- sources (初报与当时材料):
  - initial_report: https://www.dtdata.cn/news/show/4037.html
  - time_slice_supporting: https://www.sohu.com/a/968025180_100064649

- notes: hard negative理由：项目级“投运”很容易被误判为全国性拐点；但其影响半径与结构性约束改变量不足。
---

## news_id: CNDC-2025-10-011
- domain: 数据中心
- initial_report_date: 2025-10-21
- title: 上海临港“海风直联”海底数据中心示范项目落成（总规模24MW；绿电供给率>95%；海水自然冷却）
- label: NotMajor
- hard_negative: true
- summary: “全球首个/零碳/海底数据中心”极具传播性，容易被误判为行业范式跃迁；但当前仍偏示范与单点工程，短期难直接改变全国装机节奏或电力/并网硬约束结构。

- axes_and_direction:
  - pace: uncertain
  - cost: mixed
  - constraint: mixed
  - supply_demand: uncertain

- subsequent_impact_path: 截至2026-01-31，公开信息集中在示范项目参数与扩展愿景（如战略合作意向），尚不足以证明其在全国范围形成可复制、可批量投运的供给路径；行业层面更确定的结构变化仍由“绿色名单制、绿电直连清单化”等制度工具推动。
- observable_features_at_time:
  - 项目性质：示范项目（“全球首个海风直联海底数据中心”）
  - 规模：总规模24MW；一期示范2.3MW（明确）
  - 能源与冷却：海上风电直供绿电、海水自然冷却（明确）
  - 绿电供给率：>95%（明确）
  - 缺失：批量复制的成本曲线、运维可靠性数据、全国范围推广政策/标准（Unknown）
  - 约束类型：工程可行性与运维、法规与海域使用等（多选）
  - 证据等级：央企/政府与权威媒体报道（高），但对“行业结构影响”仍需时间验证

- confirmations (后验独立来源，Major至少2条；每条写清来源类型与日期):
  - 政府机构（国资系统） | 2025-10-24 | https://www.gzw.sh.gov.cn/shgzw_zxzx_gqdt/20251024/dd07fa579b3e4d3e9f7eddc472d6fa6c.html | 记录落成活动与“500MW海风直联UDC战略合作”等扩展意向（仍属愿景）
  - 权威科技媒体 | 2025-10-23 | https://www.stdaily.com/web/gdxw/2025-10/23/content_419653.html | 报道项目参数（24MW、绿电供给率>95%）与节能逻辑

- sources (初报与当时材料):
  - initial_report: https://www.chinatelecom.com.cn/ct/news/yunjisuanjisuanli/162157.html
  - time_slice_supporting: https://www.stdaily.com/web/gdxw/2025-10/23/content_419653.html, https://www.cls.cn/detail/2176665

- notes: hard negative理由：当时“极像重大”且有强创新叙事，但截至目前仍缺少“批量复制+行业变量拐点”的多源后验确认；建议2026H2再复核是否形成规模化投运与标准化路径。
---

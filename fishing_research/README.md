# 鲫鱼/鲤鱼 习性与行为 · 权威科研资料库

本仓库收录了鲫鱼（*Carassius*，包括 Carassius carassius 与 Carassius auratus）和鲤鱼（*Cyprinus carpio*）在**生境选择、食性、昼夜活动节律、温度/溶氧影响、集群与社会行为、繁殖习性**等方面的权威科研资料，作为**野钓鲫鱼知识库**的底层科学依据。

> 注：Carassius carassius 是欧洲鲫，Carassius auratus 是中国常见的鲫（金鲫、银鲫、土鲫）。两者在食性、生境偏好上高度相似，以下均作为"鲫鱼"研究对象合并参考。

---

## 目录结构

```
fishing_research/
├── README.md                                   # 本文件：资源总索引
├── KEY_FINDINGS_FOR_FISHING.md                 # 面向野钓的关键科学结论汇总
├── official_reports/                           # 政府/国际机构与权威物种数据库资料
│   ├── 01_crucian_carp_ecological_risk_summary.pdf       # USFWS · Crucian carp 生态风险筛查总览
│   ├── 02_fao_common_carp_biology_en.htm                 # FAO · 中国主要淡水养殖鱼类的生物学
│   ├── 03_vic_carp_wetland_impacts.pdf                   # ARI Victoria · Common carp 湿地影响 fact sheet
│   ├── 04_cyprinus_carpio_fishbase_26_summary.html       # FishBase · Cyprinus carpio (Linnaeus, 1758)
│   ├── 05_carassius_carassius_fishbase_270_summary.html  # FishBase · Carassius carassius (Linnaeus, 1758)
│   ├── 06_fao_crucian_carp_zh.html                       # FAO 中文 · 鲫鱼养殖与生物学 fact sheet
│   ├── 07_fao_common_carp_zh.html                        # FAO 中文 · 鲤养殖与生物学 fact sheet
│   └── 10_croplibrary_common_carp_characteristics.html   # Crop Library · Common carp 食性与生境综述
├── research_papers/                          # 最新科研论文（主要来自《水生生物学报》等 CSCD 核心刊）
│   ├── 01_common_carp_social_isolation_and_context_zh.pdf   # 社会隔离和生态场景对鲤幼鱼群体行为的影响 (2026)
│   ├── 02_xijiang_carp_larvae_growth_digestive_enzymes_zh.pdf # 西江鲤仔稚鱼生长及消化酶活性变化 (2019)
│   ├── 03_goldfish_nutritional_status_and_aerobic_scope_on_group_behaviour_zh.pdf # 营养状态和代谢范围对锦鲫幼鱼群体行为的影响 (2023)
│   └── 04_crucian_carp_rice_crab_polyculture_zh.pdf       # 稻田混养鲫对中华绒螯蟹生长和营养的影响（含鲫生态位描述，2025）
├── monographs/                                # 经典专著/研究所史资料
│   ├── 01_hb_CAS_Changjiang_fishes_page.html  # 中科院水生所 ·《长江鱼类》著述背景
│   ├── 02_irgrid_carp_activity_level_and_rhythm_page.html # 中科院水生所IRGrid ·《饥饿和饱食状态下丰鲤与其亲本的活动水平和活动节律》(2005)
│   ├── 03_China_pond_aquaculture_book_sample_chapter.pdf  # 《中国池塘养鱼学》样章（张扬宗等 主编，科学出版社 1989）
│   └── 04_natureServe_cyprinus_carpio_profile.html        # NatureServe · Cyprinus carpio 全球保护状态/生境总览
└── international/                             # 国外科研/机构资料（10 个文件）
    ├── 01_usfws_crucian_carp_erss_2025.pdf             # 🇺🇸 USFWS · Crucian carp 生态风险筛查总览（2025 新版）
    ├── 02_fao_common_carp_en.html                      # 🇺🇳 FAO · Common carp 生物学 fact sheet（英文版）
    ├── 03_fao_chapter1_biology.html                    # 🇺🇳 FAO · 淡水鱼类生物学 Chapter 1
    ├── 04_smithsonian_nemesis_cyprinus_carpio.html     # 🇺🇸 Smithsonian · Common carp 入侵物种档案
    ├── 05_iowa_dnr_common_carp_profile.html            # 🇺🇸 Iowa DNR · Common carp 物种档案
    ├── 06_umn_carp_bait_edna_pheromone.html            # 🇺🇸 明尼苏达大学 · 诱饵点+eDNA+性信息素 野外实验 (2018)
    ├── 07_carp_behavior_review_2024.html               # 🇪🇺 Open Veterinary Journal · 鲤行为与管理综述 (2024)
    ├── 08_leibniz_carp_groundbait_2004.pdf             # 🇩🇪 Leibniz 淡水生态研究所 · 窝料对鲤捕获量影响 (2004)
    ├── 09_carpfisher_feeding_behavior_guide.html       # 🇬🇧 Carp Fisher · 鲤鱼摄食行为终极指南
    └── 10_worldfish_carp_aquaculture_review.html       # 🇲🇾 WorldFish · Common carp 水产养殖综述
```

---

## 关键结论速览（面向野钓）

详细版本见 [KEY_FINDINGS_FOR_FISHING.md](./KEY_FINDINGS_FOR_FISHING.md)。

### 1. 栖息层与环境条件

| 物种 | 栖息层 | 适宜水温 | 溶氧耐受 | 底质偏好 |
|------|--------|----------|----------|----------|
| 鲫 (*Carassius*) | 中下层为主，暖水杂食，常进入浅滩觅食；冬潜深水 | **15 – 25 ℃** 最适；<10 ℃ 活动骤减；可耐受夏季高温 | 极强，可忍受 **0.3 – 0.5 mg/L** 短期低氧；冰封池塘亦能存活 | 淤泥/腐殖质丰富的浅湾、水草区、稻田沟汊 |
| 鲤 (*Cyprinus carpio*) | 典型**底层**鱼，以"拱泥觅食"为特征 | **20 – 28 ℃** 最适摄食；<10 ℃ 基本停食 | 强，但不如鲫；浑浊水、富营养化水体反而常见 | 松软底质（淤泥、腐殖质、螺蚬床）；水草丛、进水口两侧 |

### 2. 食性（用于判断窝料/钓饵思路）

- **鲫**：杂食偏植食 + 底栖无脊椎动物。幼鱼以浮游动物为主；成鱼取食有机碎屑、丝状藻、水草碎片/种子、摇蚊幼虫、枝角类、桡足类。
- **鲤**：杂食偏动物食性。天然饵料：螺、幼蚌、蚬、摇蚊幼虫、水生昆虫幼虫、小型甲壳动物、虾；兼食水草茎、种子与有机碎屑。典型摄食动作：**口部管状凸出拱泥**（"grubbing"）——筛取食物后从鳃盖排出泥浆。国外文献补充：鲤以**化学信号（嗅觉/味觉）而非视觉**定位食物，尤其对氨基酸（丙氨酸、甘氨酸、脯氨酸）和甜菜碱高度敏感；鲤**无胃（agastric）**，食物直入肠道，因此"少量多餐"是天然习性——与欧洲钓鲤业 boilies 配方思路直接吻合。
  - 参考：`international/08_leibniz_carp_groundbait_2004.pdf`、`international/07_carp_behavior_review_2024.html`、`international/09_carpfisher_feeding_behavior_guide.html`

### 3. 昼夜节律

- **鲫**：整日可摄食，但**夜间到黎明**为高峰；清晨（4:00–8:00）与黄昏（16:00–19:00）觅食活动较强。
- **鲤**：**黄昏至夜间** 活跃度最高（在半集约化池塘与野外观测一致），投喂应向夜间倾斜；白昼在浅水区觅食易受干扰。**明尼苏达大学 2018 年野外实验**（`international/06_umn_carp_bait_edna_pheromone.html`）显示：诱饵点附近鲤鱼会形成**夜间集群**，eDNA 与性信息素浓度同步升高，形成"自我强化"的吸引效应——这正是"连续几天在同一钓点打窝"效果越来越好的直接科学依据。

### 4. 温度与季节影响

- 水温 **<10 ℃**：代谢与摄食显著下降；冬鲤、冬鲫多集群于深潭，极少主动觅食。
- 水温 **10 – 15 ℃**：逐步恢复活动；早春开钓窗口。
- 水温 **20 – 28 ℃**：**摄食与活动峰值**；野钓黄金期。
- 水温 **>30 ℃**：喜潜入深水避暑；晨昏浅滩觅食。
- 鲫鱼/鲤鱼均具**分批产卵习性**（分批成熟，多次产卵），产卵温度一般 >18 ℃，依赖沉水植物附着鱼卵——繁殖期前后的觅食/集群行为是重要锚点。

### 5. 社会行为与集群（对窝量/选点的启示）

- **鲤**：具明显**集群性**，在开放水域与隐蔽场所表现不同的游动速度同步性与极性（cohesion/polarity）。社会隔离会降低其群体协调性与活跃度（见文件 01）。
- **鲫**：在有捕食者的水体中体高较大、活动偏谨慎；在无捕食者水体身形细长、活跃度高。
- **环境复杂性越高**（水生植物/结构越多），鱼群凝聚性与极性会下降——这意味着**水草过密处，上鱼节奏更分散**；而**开阔沙泥底 + 局部结构**往往是聚窝好点。
- **国外窝料实验结论**（`international/08_leibniz_carp_groundbait_2004.pdf`，Leibniz 淡水生态研究所，2004）：专业钓鲤者平均每人每年投放 **215 kg** 窝料；窝料投放量与捕获量存在**阈值关系**——过量投放反而低效。结合"无胃 → 少量多餐"生理特征，**少量、持续、稳定的打窝策略**优于一次性大窝。

### 6. 气压、风向与溶氧的影响（国外文献特别强调）

- **气压下降（storm front）**：鲤鱼摄食活跃度显著降低，尤其大型个体更敏感。Carp Fisher（引用 *Journal of Zoology*）建议：**气压稳定或缓慢上升**时作钓效果最好。
- **下风岸（lee shore）**：风把**浮游生物/有机碎屑/水生昆虫**推向下风岸，同时**提高溶氧 + 破碎水面降低鲤鱼视觉警觉**。欧洲钓鲤指南将下风岸列为首选标点。
- **进水口**：降雨带来的地面径流携带昆虫、种子、碎屑进入水体，同时快速提升溶氧——是鲤鱼过路觅食的高频区。
- 参考：`international/09_carpfisher_feeding_behavior_guide.html`

### 7. 推荐窝料/钓饵方向（基于食性）

- 对**鲫**：麸类（麦麸/豆饼粉）、米糠、玉米粉、蚯蚓、红虫（摇蚊幼虫）、米饭、薯泥。强调**颗粒细碎 + 持续扩散气味**。
- 对**鲤**：螺肉、蚌肉、豆饼、菜籽饼、红薯块、玉米碴、发酵谷物；强调**下沉后形成"气味柱"**，配合拱泥觅食习性。

> 以上结论均有对应原文献/资料支持，详见各资源下方的关键摘录。

---

## 补充阅读（未下载但可进一步检索的文献）

- 杨严鸥、解绶启、姚峰（2005）《饥饿和饱食状态下丰鲤与其亲本的活动水平和活动节律》*动物学报* 51(5) — 鲤昼夜活动节律的经典国内研究。
- Kottelat, M. & Freyhof, J. (2007). *Handbook of European Freshwater Fishes* — 欧洲鲫与鲤的形态/分布权威参考书。
- Balon, E. K. (1995). *Origin and domestication of the wild carp, Cyprinus carpio* — 鲤驯化与原生物学经典综述。
- 《长江鱼类》（中科院水生生物研究所鱼类研究室，1976）《中国池塘养鱼学》（张扬宗、谭玉钧、欧阳海 主编，1989）—— 国内经典基础资料。

— 资料下载完成时间：2026-06-19 —

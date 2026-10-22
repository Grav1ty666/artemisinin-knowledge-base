# 青蒿素（Artemisinin）研究知识库 / Research Knowledge Base

> **中文**：面向农学/药用植物代谢与合成生物学方向的主题知识库。
> 收集范围：青蒿（*Artemisia annua* L.）**合成通路、前体物质、转录因子、激素调控、研究方法论、基因组与组学数据库**，以及**复旦-交大-诺丁汉植物生物技术研发中心（唐克轩团队）**相关文献与机构信息。全部条目含可核验的 DOI/PMID，关键结论均来自所引文献；内容采用**中英双语（每章含 English Summary）**，便于跨语言直接调用。
>
> **English**: A topic knowledge base for agro-botany / medicinal-plant metabolism and synthetic biology.
> Scope: artemisinin biosynthesis **pathway, precursors, transcription factors, hormone regulation, methodology, genome & omics databases**, plus literature and institutional info on the **Fudan–SJTU–Nottingham Plant Biotechnology R&D Center (Prof. Kexuan Tang)**. Every entry carries a verifiable DOI/PMID; each chapter includes an **English Summary**, so it can be used directly in either language.
>
> **跨机器调用（GitHub 源）**：本知识库已同步至公开仓库 https://github.com/Grav1ty666/artemisinin-knowledge-base 。在其他机器/会话中 `git clone` 或下载后，按下方"一、如何使用"即可调用；也可让任意 AI 直接读取 `literature_index.json` 做程序化检索。英文总览见 `README.md`。
> **Cross-machine use (GitHub)**: synced to the public repo https://github.com/Grav1ty666/artemisinin-knowledge-base . On another machine, `git clone` or download, then follow "一、如何使用 / How to use" below; an AI can also read `literature_index.json` for programmatic search. See `README.md` for the English overview.

## 一、如何使用本知识库（"需要时调用"）/ How to use

本知识库为**模块化本地文件**。调用方式：
1. **按主题检索**：直接说"查转录因子" / "查激素 JA" / "查方法论里酵母半合成"，我会加载对应章节文件（01–10）。
2. **按文献检索**：`07_文献索引.md` 是按主题分类、带 DOI/PMID 的论文清单；`literature_index.json` 为机器可读索引，可用于程序化检索。
3. **按基因/数据库检索**：`08_基因与序列数据库.md` 给数据库入口与登录号，`10_关键基因速查表.md` 是单页中英对照速查。
4. **按组学数据检索**：`09_组学数据库与数据集.md` 汇总可下载的基因组/转录组/单细胞/Hi-C 登陆号。
5. **按机构检索**：`06_机构_复旦交大诺丁汉植物生物技术中心.md` 汇总唐克轩团队代表成果。
6. **跨主题提问**：例如"把 CYP71AV1 的调控网络和它受的激素列出来"，我会同时调 01+03+04 并交叉对照。

> 提示：所有"关键结论"均来自下方索引所引文献；凡标注 **[to-check]** 者为二次来源转述，正式引用前请回原文确认。
> Note: key conclusions trace to the cited literature; entries tagged **[to-check]** are secondary — verify before formal citation.

## 二、目录 / Contents

| 文件 File | 内容 Content | 一级关键词 Keywords |
|------|------|-----------|
| 01_合成通路与关键酶.md | MVA/MEP→FPP→紫穗槐二烯→青蒿酸/二氢青蒿酸→青蒿素；各步酶与组织特异性 | pathway, enzyme, ADS, CYP71AV1, DBR2, ALDH1 |
| 02_前体物质.md | IPP/DMAPP、FPP、紫穗槐二烯、青蒿醇/醛/酸、二氢青蒿酸(DHAA)、青蒿素B、竞争前体 | precursor, DHAA, artemisinic acid, FPP |
| 03_转录因子.md | WRKY/AP2-ERF/bHLH/bZIP/MYB/HD-ZIP/TCP/NAC/BBX 等家族及调控层级 | TF, AaGSW1, AaORA, AaMYC2, AaWRKY1, AaHD1 |
| 04_激素调控.md | JA/MeJA、ABA、GA、SA、ET、SL 及 miRNA 模块、外源因子 | hormone, MeJA, ABA, GA, SA, JA |
| 05_研究方法论.md | 喂饲/功能验证、代谢工程、合成生物学(酵母)、组学、单细胞分离、CRISPR、生物反应器 | methodology, metabolic engineering, yeast, CRISPR, omics, LMPC |
| 06_机构_复旦交大诺丁汉植物生物技术中心.md | 中心定位、唐克轩团队、代表成果、合作网络 | Tang Kexuan, Fudan-SJTU-Nottingham, SJTU |
| 07_文献索引.md | 分类论文表（作者/年/期刊/DOI/PMID/核心贡献，含 [verified]/[to-check] 标记） | references |
| 08_基因与序列数据库.md | NCBI/Phytozome/ArtsBioCyc 等入口 + 关键基因 GenBank/基因组 ID 速查 | database, GenBank, accession, Phytozome |
| 09_组学数据库与数据集.md | 基因组/转录组/单细胞/Hi-C/蛋白-代谢组 的 BioProject/SRA/CNGBdb 登陆号与下载方式 | omics, BioProject, SRA, CNGBdb, Hi-C |
| 10_关键基因速查表.md | 单页中英对照：基因→功能→登录号→文献 | gene table, quick reference |
| literature_index.json | 同 07 的机器可读索引（含英文标题/DOI/PMID） | index |
| README.md | 英文总览（结构、调用、核心途径、重点文献） | English overview |

## 三、一句话核心结论 / Core takeaway

青蒿素在**分泌型腺毛（GST）**中合成，其特有途径为 `FPP →(ADS) 紫穗槐-4,11-二烯 →(CYP71AV1+CPR) 青蒿醇/醛/酸 →(DBR2+ALDH1) 二氢青蒿酸(DHAA) →[非酶促光氧化] 青蒿素`；DHAA 是已被同位素喂饲实验证实的**直接前体**，而终末 DHAA→青蒿素为**光依赖的非酶促反应**（单线态氧参与的 ene 反应/Hock 裂解）。上游受 **MVA（胞质）与 MEP（质体）** 双途径供前体，受 **JA/ABA/GA/SA/ET/光** 等多重激素与信号通过多级**转录因子网络**精细调控。提高产量需**多基因协同+前体供给+组织特异性表达+抑制竞争途径（SQS）** 的系统策略。
> Artemisinin is synthesized in **glandular secretory trichomes (GST)**. The specific route is `FPP →(ADS) amorpha-4,11-diene →(CYP71AV1+CPR) artemisinic alcohol/aldehyde/acid →(DBR2+ALDH1) DHAA →[non-enzymatic photo-oxidation] artemisinin`; **DHAA is the direct precursor** (isotope-feeding proven), and the terminal DHAA→artemisinin step is **light-dependent and non-enzymatic** (singlet-oxygen ene reaction / Hock cleavage). Upstream precursors come from both **cytosolic MVA and plastidial MEP** pathways and are gated by a multi-tier **transcription-factor network** responsive to **JA/ABA/GA/SA/ET/light**. Higher yield requires **multi-gene synergy + precursor supply + trichome-specific expression + suppression of the competing SQS branch**.

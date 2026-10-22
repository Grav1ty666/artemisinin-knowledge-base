# Artemisinin Research Knowledge Base

A modular, citation-backed knowledge base for researchers working on **artemisinin (青蒿素) biosynthesis, metabolic engineering, and glandular-trichome regulation in _Artemisia annua_ L.** Every entry carries a verifiable DOI / PMID, and each chapter includes a bilingual (Chinese + English) summary so the material can be used directly in either language.

> 本仓库为中文知识库的英文总览。中文入口见 [`index.md`](index.md)。

## Scope
- **Biosynthetic pathway & key enzymes** (ADS → CYP71AV1 → DBR2 → ALDH1; terminal non-enzymatic step)
- **Precursors** (MVA/MEP → FPP → amorpha-4,11-diene → artemisinic acid/aldehyde → DHAA → artemisinin; SQS competition)
- **Transcription factors** (WRKY/AaGSW1, AP2-ERF/AaORA/AaERF1-2, bHLH/AaMYC2/AabHLH1, bZIP/AabZIP1, MYB/AaMIXTA1, HD-ZIP/AaHD1, TCP/AaTCP15, BBX/AaBBX21–AaHY5, NAC, negative TLR1/2)
- **Hormone regulation** (JA/MeJA, ABA, GA, SA, ethylene, light; miRNA modules)
- **Methodology** (feeding/isotope studies, metabolic engineering, yeast semi-synthesis, omics, single-cell/LMPC, CRISPR, bioreactors)
- **Genome & omics databases** (accessions, how to download)
- **Fudan–SJTU–Nottingham Plant Biotechnology R&D Center (Prof. Kexuan Tang)** — the dominant source of the TF/GST-development literature cited here

## Repository structure
| File | Content |
|------|---------|
| `index.md` | Chinese index + how-to + core takeaway (bilingual) |
| `01_合成通路与关键酶.md` | Pathway & enzymes |
| `02_前体物质.md` | Precursors |
| `03_转录因子.md` | Transcription factors |
| `04_激素调控.md` | Hormone regulation |
| `05_研究方法论.md` | Methodology |
| `06_机构_复旦交大诺丁汉植物生物技术中心.md` | Institution (Tang Kexuan lab) |
| `07_文献索引.md` | Categorized reference list (DOI/PMID, [verified]/[to-check]) |
| `08_基因与序列数据库.md` | Gene & sequence database portals + accessions |
| `09_组学数据库与数据集.md` | Omics datasets (BioProject/SRA/CNGBdb) |
| `10_关键基因速查表.md` | One-page bilingual gene quick-reference |
| `literature_index.json` | Machine-readable index of the references |

## How to use
1. **Topical query** — ask "transcription factors", "JA hormone", or "yeast semi-synthesis"; the relevant chapters (01–10) are loaded and cross-referenced.
2. **Literature query** — `07_文献索引.md` is the categorized paper list; `literature_index.json` is the machine-readable version for programmatic search.
3. **Gene / database query** — `08_基因与序列数据库.md` gives NCBI/Phytozome/ArtsBioCyc portals and GenBank/genome IDs; `10_关键基因速查表.md` is the one-page lookup.
4. **Omics data query** — `09_组学数据库与数据集.md` lists downloadable Genome/Transcriptome/Single-nucleus/Hi-C accessions.

## Core pathway (one line)
`FPP →(ADS) amorpha-4,11-diene →(CYP71AV1+CPR) artemisinic alcohol/aldehyde/acid →(DBR2+ALDH1) DHAA →[non-enzymatic, light-dependent] artemisinin`.

**DHAA is the direct precursor** (isotope-feeding proven). The terminal DHAA→artemisinin step is **non-enzymatic** (singlet-oxygen ene reaction / Hock cleavage; Czechowski *et al.*, PNAS 2016, 10.1073/pnas.1611567113). Upstream precursors come from both cytosolic **MVA** and plastidial **MEP**; expression is gated by a multi-tier **TF network** responsive to JA/ABA/GA/SA/ethylene/light.

## Key references (verified)
- Bouwmeester HJ *et al.* (1999) ADS. *Phytochemistry* 52:843–854. **10.1016/S0031-9422(99)00206-X**
- Teoh KH *et al.* (2006) CYP71AV1. *FEBS Lett* 580:1411–1416. **10.1016/j.febslet.2006.01.065** (PMID 16458889)
- Zhang Y *et al.* (2008) DBR2. *J Biol Chem* 283:21501–21508. **10.1074/jbc.M803090200** (PMID 18495659)
- Ro DK *et al.* (2006) Yeast artemisinic acid. *Nat Biotechnol* 24:155–161. **10.1038/nbt1187**
- Paddon CJ *et al.* (2013) Semi-synthetic artemisinin. *Nature* 496:528–532. **10.1038/nature12051** (PMID 23575629)
- Czechowski T *et al.* (2016) Non-enzymatic terminal step. *PNAS* 113:15150–15155. **10.1073/pnas.1611567113**
- Shen Q *et al.* (2018) *A. annua* genome. *Mol Plant* 11:776–788. **10.1016/j.molp.2018.03.015** (PMID 29703587)
- Yu ZX *et al.* (2012) AaERF1/2. *Mol Plant* 5:353–365. **10.1093/mp/ssr087** (PMID 22104293)
- Lu X *et al.* (2013) AaORA. *New Phytol* 198:1191–1202. **10.1111/nph.12207** (PMID 23448426)
- Shen Q *et al.* (2016) AaMYC2. *New Phytol* 210:1269–1281. **10.1111/nph.13874** (PMID 26864531)
- Chen M *et al.* (2017) AaGSW1/WRKY1. *New Phytol* 214:304–316. **10.1111/nph.14373** (PMID 28001315)
- Yan T *et al.* (2017) AaHD1. *New Phytol* 213:1145–1155. **10.1111/nph.14205** (PMID 27659595)
- Shi P *et al.* (2017) AaMIXTA1. *New Phytol*. **10.1111/nph.14789**
- Ma YN *et al.* (2021) AaGSW1–AaTCP15/AaORA cascade. *Plant Biotechnol J* 19:1412–1428. **10.1111/pbi.13561** (PMID 33539631)
- He W *et al.* (2024) AaBBX21–AaHY5. *J Integr Plant Biol*. **10.1111/jipb.13708** (PMID 38980203)
- Single-nucleus trichome atlas (2025). *Nat Commun*. **10.1038/s41467-025-63770-y** (CNGBdb CNP0006977)
- Hi-C chromatin architecture (2023). *Planta*. **10.1007/s00425-023-04223-y** (SRA PRJNA991086)

## Note on accuracy
Entries tagged **[to-check]** in `07_文献索引.md` are drawn from secondary sources; verify against the original before formal citation. Gene IDs / GenBank accessions may change with annotation updates — always re-check current records at NCBI / Phytozome.

## License
Reference/citation compendium for research use. Primary data belong to the respective authors and publishers; please cite the original papers.

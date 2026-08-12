# 数据来源

本版数据快照日期为 `2026-08-12`。离线载荷含 153 个公开来源目录项；这个数字是来源记录数，不是独立机构数。

## 来源目录构成

| 来源 | 目录项 | 用途 |
|---|---:|---|
| openFDA drug label API | 138 | 药品标签、适应证、不良反应及监管文本 |
| ChEMBL REST API | 1 | 定量亲和力与效价记录 |
| IUPHAR/BPS Guide to PHARMACOLOGY | 5 | 配体、靶点、相互作用及人体组织分布 |
| Open Targets Platform | 1 | 药物—疾病与靶点证据快照 |
| QuickGO | 1 | Gene Ontology 注释 |
| Reactome Content Service | 1 | 经整理的机制通路 |
| 监管批准公告与处方资料 | 2 | 地达西尼批准信息与固定复方处方资料 |
| WHO INN、随机对照试验与编辑范围登记 | 3 | 规范名称、临床试验及扩展药物范围 |
| 项目术语与原始范围登记 | 1 | 中文术语和原始收录范围 |

## 本版公开数据量

- 1215 条互动路径
- 423 条公开靶点分布记录
- 4576 条定量亲和力/效价记录
- 138 份 openFDA 标签文档

靶点分布的中文文本是对来源记录的编辑性翻译；英文原文与来源定位保留在软件中。受体家族或复合物页面只在存在显式成员关系时汇总成员记录，并标明这是成员靶点记录，不把成员分布改写为整个家族的直接测量。

## 来源入口

- [openFDA drug label API](https://open.fda.gov/apis/drug/label/)
- [ChEMBL Web Services](https://www.ebi.ac.uk/chembl/api/data/docs)
- [IUPHAR/BPS Guide to PHARMACOLOGY downloads](https://www.guidetopharmacology.org/download.jsp)
- [IUPHAR/BPS Guide to PHARMACOLOGY web services](https://www.guidetopharmacology.org/webServices.jsp)
- [Open Targets Platform documentation](https://platform-docs.opentargets.org/)
- [QuickGO API](https://www.ebi.ac.uk/QuickGO/services/)
- [Reactome Content Service](https://reactome.org/ContentService/)

GitHub 分发载荷不包含项目内部参考书 PDF、参考书摘录、内部来源 ID、本机路径或页码定位。各外部数据集的使用、署名和再分发条件以对应提供方的当前条款为准。

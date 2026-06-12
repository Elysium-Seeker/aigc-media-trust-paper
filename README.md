# AI 生成视觉内容辨识与媒体信任

本文件夹是大英四论文项目的独立仓库，主题为 AI 生成视觉内容、人类辨识能力与媒体信任。当前论文重点关注图片、截图式视觉材料和带有平台界面的视觉证据，例如直播界面、社交媒体截图、含文字图片和普通照片。

## 文件结构

```text
Paper/
  README.md
  PAPER_OUTLINE_CN.md
  CONTRIBUTION_LOG.md
  final_report_group6.docx
  Manuscript/
    01_Introduction.md
    02_Literature_Review.md
    03_Methodology.md
    04_Results.md
    05_Discussion.md
  Appendices/
    Reconstructed_AI_Image_Prompts.md
  Experiment/
    Questionnaire_WJX.txt
    Answer_Key_Internal.md
    Materials_Manifest.csv
    Results_Summary.md
    Results_By_Material_Creation_Route.md
    Survey_Responses_Anonymized.xlsx
    material_pair_contact_sheet.png
    materials/
      images/
  References/
    References_APA.md
    Source_Links.md
    Source_Notes.docx
    files/
  Submissions/
    Class_3_Group_6_Final_Paper.md
    Class_Group_Name_IMR.md
    Class_3_Group_6_IMRD.md
    Class 3 Group 6 IMR.docx
    Class 3 Group 6 IMRD.docx
    Class 3 Group 6 IMRD revised.docx
    accuracy_by_category.png
    accuracy_by_creation_route.png
    stimulus_examples.png
    trust_by_category.png
```

## 主要文件

- `PAPER_OUTLINE_CN.md`：中文论文大纲，说明研究目的、研究问题、论文结构和当前问卷设计。
- `CONTRIBUTION_LOG.md`：小组成员名单和按日期记录的贡献日志。
- `final_report_group6.docx`：最终成品论文 Word 文件。
- `Manuscript/`：论文正文草稿。后续写作和修改主要在这里进行。
- `Appendices/Reconstructed_AI_Image_Prompts.md`：记录实验材料的 AI/真实图配对、材料生成路线，以及根据最终 AI 图片材料反推的提示词。由于原始提示词未完整保存，该文件只能作为重建版方法记录，不能当作原始生成记录。
- `Submissions/`：按课程作业格式整理出的阶段性提交文件。
- `Experiment/Questionnaire_WJX.txt`：问卷星导入文本，面向参与者，不包含答案。
- `Experiment/Materials_Manifest.csv`：实验材料清单，记录每张图片对应的配对编号、来源判断题、可信度题、真实标签、文件路径和材料生成路线。
- `Experiment/Answer_Key_Internal.md`：研究者内部使用的答案和评分规则，不应发给问卷参与者。
- `Experiment/Results_Summary.md`：问卷结果的汇总统计，不包含个人答卷元数据。
- `Experiment/Results_By_Material_Creation_Route.md`：按材料生成路线重新整理的准确率和可信度分析。
- `Experiment/Survey_Responses_Anonymized.xlsx`：去标识化后的问卷答卷数据，保留题目回答，移除提交时间、IP 等问卷星元数据。
- `References/References_APA.md`：APA 格式参考文献列表。
- `References/Source_Links.md`：引用来源链接和本地文件保存情况。

## 问卷设置流程

1. 将 `Experiment/Questionnaire_WJX.txt` 复制到问卷星文本导入功能中。
2. 根据 `Experiment/Materials_Manifest.csv` 将图片插入到对应题目。
3. 不要向参与者公开 `Experiment/Answer_Key_Internal.md`。
4. 回收问卷后，先根据 Q42 数据质量检查题筛选或标记无效回答。
5. 分别统计来源判断准确率、AI 图片准确率、真实图片准确率、不同图片类别准确率和图片可信度评分。

## 协作规则

- 论文正文统一在 `Manuscript/` 中修改。
- 原始实验材料统一放在 `Experiment/materials/` 中。
- 问卷星原始导出文件包含提交时间、IP 等元数据，只保留本地；公开仓库中使用汇总结果。
- 新增引用时，同时更新 `References/References_APA.md` 和 `References/Source_Links.md`。
- 不要把临时脚本、虚拟环境、缓存文件或本地工具文件夹放进本项目。

# AI 生成视觉内容辨识与媒体信任

本文件夹是大英四论文项目的独立仓库，主题为 AI 生成视觉内容、人类辨识能力与媒体信任。当前论文重点关注图片、截图式视觉材料和带有平台界面的视觉证据，例如直播界面、社交媒体截图、含文字图片和普通照片。

## 文件结构

```text
Paper/
  README.md
  PAPER_OUTLINE_CN.md
  CONTRIBUTION_LOG.md
  Manuscript/
    01_Introduction.md
    02_Literature_Review.md
    03_Methodology.md
  Experiment/
    Questionnaire_WJX.txt
    Answer_Key_Internal.md
    Materials_Manifest.csv
    materials/
      images/
  References/
    References_APA.md
    Source_Links.md
    Source_Notes.docx
    files/
```

## 主要文件

- `PAPER_OUTLINE_CN.md`：中文论文大纲，说明研究目的、研究问题、论文结构和当前问卷设计。
- `CONTRIBUTION_LOG.md`：小组成员名单和按日期记录的贡献日志。
- `Manuscript/`：论文正文草稿。后续写作和修改主要在这里进行。
- `Experiment/Questionnaire_WJX.txt`：问卷星导入文本，面向参与者，不包含答案。
- `Experiment/Materials_Manifest.csv`：实验材料清单，记录每张图片对应的来源判断题、可信度题、真实标签和文件路径。
- `Experiment/Answer_Key_Internal.md`：研究者内部使用的答案和评分规则，不应发给问卷参与者。
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
- 新增引用时，同时更新 `References/References_APA.md` 和 `References/Source_Links.md`。
- 不要把临时脚本、虚拟环境、缓存文件或本地工具文件夹放进本项目。

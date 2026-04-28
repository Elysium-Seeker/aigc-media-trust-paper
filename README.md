# AIGC Identifiability and Media Trust

This folder is the standalone project directory for the College English 4 paper on AI-generated visual content, human detection accuracy, and media trust.

## Structure

```text
Paper/
  README.md
  PAPER_OUTLINE_CN.md
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

## Main Files

- `PAPER_OUTLINE_CN.md`: Chinese outline explaining the research purpose, questions, structure, and current survey design.
- `CONTRIBUTION_LOG.md`: group member list and dated contribution records.
- `Manuscript/`: editable paper sections. Group members should work here when drafting the final paper.
- `Experiment/Questionnaire_WJX.txt`: participant-facing Wenjuanxing import text. It should not include answer keys.
- `Experiment/Materials_Manifest.csv`: maps each image to its source-judgement question, trust-rating question, ground truth, and material file.
- `Experiment/Answer_Key_Internal.md`: researcher-only scoring key. Do not share this with participants.
- `References/References_APA.md`: formatted reference list for the paper.
- `References/Source_Links.md`: local file availability and source links for cited works.

## Survey Setup

1. Copy `Experiment/Questionnaire_WJX.txt` into Wenjuanxing text import.
2. Insert images according to `Experiment/Materials_Manifest.csv`.
3. Keep `Experiment/Answer_Key_Internal.md` private.
4. After collecting responses, compute source-judgement accuracy, AI-item accuracy, real-item accuracy, category-level accuracy, and image trust scores separately.

## Collaboration Rules

- Edit paper text in `Manuscript/`.
- Keep raw experiment materials under `Experiment/materials/`.
- Add new citations to both `References/References_APA.md` and `References/Source_Links.md`.
- Do not put temporary scripts, virtual environments, or local tool folders into this project.

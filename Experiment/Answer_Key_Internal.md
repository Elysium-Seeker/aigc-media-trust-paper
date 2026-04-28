# Answer Key for Researchers

Do not share this file with participants.

## Scoring Rule

For source-judgement items Q5-Q14:

- Real item: "确定是真实拍摄/真实截图" or "可能是真实拍摄/真实截图" = correct.
- AI item: "可能是AI生成" or "确定是AI生成" = correct.
- "说不准" = incorrect or missing for the main binary accuracy score.

Trust-rating items Q15-Q24 and attitude items Q25-Q28 do not have correct answers. Treat them
as five-point Likert variables.

## Image Source Items

| Image | Source question | Trust question | Material | Ground truth | Category |
|---|---|---|---|---|---|
| Image 1 | Q5 | Q15 | `materials/images/ai/1.jpg` | AI-generated | Text-bearing visual artifact |
| Image 2 | Q6 | Q16 | `materials/images/real/01.png` | Real | Text-bearing visual artifact |
| Image 3 | Q7 | Q17 | `materials/images/real/02.jpg` | Real | Portrait |
| Image 4 | Q8 | Q18 | `materials/images/ai/2.jpg` | AI-generated | Portrait |
| Image 5 | Q9 | Q19 | `materials/images/ai/3.jpg` | AI-generated | Livestream commerce screenshot |
| Image 6 | Q10 | Q20 | `materials/images/real/03.jpg` | Real | Livestream commerce screenshot |
| Image 7 | Q11 | Q21 | `materials/images/ai/4.jpg` | AI-generated | Food photo |
| Image 8 | Q12 | Q22 | `materials/images/real/04.png` | Real | Food photo |
| Image 9 | Q13 | Q23 | `materials/images/real/05.png` | Real | Virtual livestream interface |
| Image 10 | Q14 | Q24 | `materials/images/ai/5.jpg` | AI-generated | Virtual livestream interface |

## Recommended Result Tables

Report at least these values:

- Overall source-judgement accuracy: Q5-Q14.
- AI-item accuracy: Q5, Q8, Q9, Q11, Q14.
- Real-item accuracy: Q6, Q7, Q10, Q12, Q13.
- Category-level accuracy: text-bearing artifact, portrait, livestream commerce screenshot, food photo, and virtual livestream interface.
- Mean trust rating for each image: Q15-Q24.
- Mean trust rating by ground truth: AI-generated images vs real images.
- Mean trust rating by category: especially screenshot/interface-like images vs ordinary photos.

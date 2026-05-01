# Answer Key for Researchers

Do not share this file with participants.

## Scoring Rule

For source-judgement items Q5, Q7, Q9, Q11, Q13, Q15, Q17, Q19, Q21, Q23, Q25,
Q27, Q29, Q31, Q33, Q35, Q37, and Q39:

- Real item: "确定是真实拍摄/真实截图" or "可能是真实拍摄/真实截图" = correct.
- AI item: "可能是AI生成" or "确定是AI生成" = correct.
- "说不准" = incorrect or missing for the main binary accuracy score.

Trust-rating items Q6, Q8, Q10, Q12, Q14, Q16, Q18, Q20, Q22, Q24, Q26, Q28,
Q30, Q32, Q34, Q36, Q38, and Q40, and attitude items Q41 and Q43-Q45 do not have correct
answers. Treat them as five-point Likert variables.

Q42 is an attention-check item. The expected answer is "1 完全不同意". Responses that fail
this item should be flagged and can be excluded from the main analysis.

## Image Source Items

| Image | Source question | Trust question | Material | Ground truth | Category |
|---|---|---|---|---|---|
| Image 1 | Q5 | Q6 | `materials/images/ai/text_artifact_ai_01.jpg` | AI-generated | Text-bearing visual artifact |
| Image 2 | Q7 | Q8 | `materials/images/real/text_artifact_real_01.png` | Real | Text-bearing visual artifact |
| Image 3 | Q9 | Q10 | `materials/images/ai/text_artifact_ai_02.jpg` | AI-generated | Text-bearing visual artifact |
| Image 4 | Q11 | Q12 | `materials/images/real/text_artifact_real_02.jpg` | Real | Text-bearing visual artifact |
| Image 5 | Q13 | Q14 | `materials/images/real/portrait_real_01.jpg` | Real | Portrait |
| Image 6 | Q15 | Q16 | `materials/images/ai/portrait_ai_01.jpg` | AI-generated | Portrait |
| Image 7 | Q17 | Q18 | `materials/images/ai/portrait_ai_02.jpg` | AI-generated | Portrait |
| Image 8 | Q19 | Q20 | `materials/images/real/portrait_real_02.jpg` | Real | Portrait |
| Image 9 | Q21 | Q22 | `materials/images/ai/livestream_commerce_ai_01.jpg` | AI-generated | Livestream commerce screenshot |
| Image 10 | Q23 | Q24 | `materials/images/real/livestream_commerce_real_01.jpg` | Real | Livestream commerce screenshot |
| Image 11 | Q25 | Q26 | `materials/images/ai/livestream_commerce_ai_02.jpg` | AI-generated | Livestream commerce screenshot |
| Image 12 | Q27 | Q28 | `materials/images/real/livestream_commerce_real_02.jpg` | Real | Livestream commerce screenshot |
| Image 13 | Q29 | Q30 | `materials/images/ai/food_photo_ai_01.jpg` | AI-generated | Food photo |
| Image 14 | Q31 | Q32 | `materials/images/real/food_photo_real_01.png` | Real | Food photo |
| Image 15 | Q33 | Q34 | `materials/images/ai/food_photo_ai_02.jpg` | AI-generated | Food photo |
| Image 16 | Q35 | Q36 | `materials/images/real/food_photo_real_02.jpg` | Real | Food photo |
| Image 17 | Q37 | Q38 | `materials/images/real/virtual_livestream_real_01.png` | Real | Virtual livestream interface |
| Image 18 | Q39 | Q40 | `materials/images/ai/virtual_livestream_ai_01.jpg` | AI-generated | Virtual livestream interface |

## Recommended Result Tables

Report at least these values:

- Attention-check pass rate: Q42.
- Overall source-judgement accuracy: Q5, Q7, Q9, Q11, Q13, Q15, Q17, Q19, Q21, Q23, Q25, Q27, Q29, Q31, Q33, Q35, Q37, and Q39.
- AI-item accuracy: Q5, Q9, Q15, Q17, Q21, Q25, Q29, Q33, and Q39.
- Real-item accuracy: Q7, Q11, Q13, Q19, Q23, Q27, Q31, Q35, and Q37.
- Category-level accuracy: text-bearing artifact, portrait, livestream commerce screenshot, food photo, and virtual livestream interface.
- Mean trust rating for each image: Q6, Q8, Q10, Q12, Q14, Q16, Q18, Q20, Q22, Q24, Q26, Q28, Q30, Q32, Q34, Q36, Q38, and Q40.
- Mean trust rating by ground truth: AI-generated images vs real images.
- Mean trust rating by category: especially screenshot/interface-like images vs ordinary photos.

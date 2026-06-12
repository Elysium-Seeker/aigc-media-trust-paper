# 03 Methodology

## 3.1 Research Design

This study used a small-scale quantitative survey design. The Wenjuanxing survey provided the
main local data for testing how university-level respondents judged AI-generated and real
visual materials. Previous studies were used as background evidence because they explain why
human detection of AI-generated images is difficult and why screenshot-like materials can
influence credibility.

The study asks two connected questions:

1. How accurately did university-level respondents in this sample distinguish AI-generated
   images from real images across selected online visual categories?
2. How did perceived trust differ by image source and category, and how did these trust
   ratings relate to respondents' confidence in judging online visual information?

## 3.2 Use of Previous Studies as Context

Four sources were used to guide the survey design and interpretation. Frank et al. (2024) and
Roca et al. (2025) were used because they report human difficulty in detecting AI-generated
media and images. Guo et al. (2025) was used because it connects realistic AI-generated
images with misinformation credibility. Inwood and Zappavigna (2024) was used because it
explains why screenshots often function as visual evidence in online communication.

| Source | Evidence type | Relevance |
|---|---|---|
| Frank et al. (2024) | Cross-national detection experiment | Baseline for human difficulty in detecting AI-generated media |
| Roca et al. (2025) | Large-scale image detection experiment | Image-specific accuracy and category differences |
| Guo et al. (2025) | Misinformation experiment | Realistic AI images can strengthen belief in false claims |
| Inwood & Zappavigna (2024) | Visual communication analysis | Screenshots function as visual evidence in online communication |

These studies did not replace the survey data. Instead, they helped explain why the survey
measured both source judgement and trust ratings, and why the materials included ordinary
photos, text-bearing images, and interface-like screenshots.

## 3.3 Survey Method

### 3.3.1 Participants

Participants were recruited through convenience sampling and completed the survey online
through Wenjuanxing. A total of 79 responses were collected. Ten responses failed the Q42
attention-check item, and three attention-check passers reported "high school or below" as
their current education level. These responses were excluded from the main analysis so that
the analytic sample matched the study's university-level focus. The final analytic sample
therefore included 66 valid university-level respondents.

Within this analytic sample, 26 respondents were first-year students, 14 were second-year
students, 10 were third-year students, and 16 were fourth-year-or-above students or recent
graduates. Most respondents used social media for at least one hour per day, and most had used
AI tools either daily or weekly.

### 3.3.2 Materials

The survey used image-only materials. It contained eighteen visual items: nine
AI-generated images and nine real images. The materials covered both ordinary photorealistic images and
screenshot-like visual evidence:

- text-bearing visual artifacts, such as postcard or document-like images;
- portrait images;
- livestream commerce screenshots;
- food photographs;
- virtual livestream or VTuber interface images.

The 18 items were selected purposively rather than randomly. Because the study focused on
online visual credibility, the materials were chosen to cover five visual types that people
commonly encounter on digital platforms. The set was also balanced by source, with nine
AI-generated images and nine real images. Therefore, the materials should not be treated as a
statistically representative sample of all online images; they were designed to compare
responses across selected image categories. The exact files, ground truth labels,
source-judgement question numbers, and trust-rating question numbers are listed in
`Experiment/Materials_Manifest.csv`. The participant-facing questionnaire did not reveal
whether a file was AI-generated or real.

The stimulus set was also prepared through two material creation routes. In five pairs, an
AI-generated image was prepared first and a visually similar real image was later selected for
comparison. In four pairs, a real image was used as the source or reference for an
AI-modified counterpart. This route variable was added after the main category analysis in
order to examine whether the production route of the stimulus was related to source judgement
and trust ratings. The route variable should be interpreted descriptively because it was not
randomly assigned and was partly connected with the available image categories.

![Figure 1. Examples of survey stimuli by source and visual category.](../Submissions/stimulus_examples.png)

### 3.3.3 Procedure

The survey had three sections. First, to describe the sample and control for relevant
background differences, participants reported their year of study, daily social media use, AI
tool use, and self-assessed ability to identify AI-generated or edited online images. Second,
to measure source judgement before credibility judgement, participants completed the image
task in two steps for each visual item. They first judged whether the image was real or
AI-generated, and after that they rated how trustworthy the same image would seem if it
appeared on social media or another online platform. Third, after finishing all image tasks,
participants answered four media-trust attitude questions, one Q42 attention-check item, and
one optional open-ended question about the cues they used.

No feedback was given during the task so that later answers would not be influenced by
earlier corrections. Because the study compared responses across visual categories, the
Wenjuanxing version grouped materials of the same type together. During analysis, responses
that failed Q42 were flagged and excluded before detection accuracy and trust scores were
calculated.

### 3.3.4 Measures

Detection accuracy was calculated as the proportion of correctly classified source-judgement
items. For binary accuracy scoring, "definitely real" and "probably real" are counted as
correct for real images, while "probably AI-generated" and "definitely AI-generated" are
counted as correct for AI-generated images. "Unsure" was treated as incorrect or missing for the
main accuracy score.

Separate accuracy scores were calculated for all image items, AI-generated items, real
items, and image categories. Category-level analysis was useful because the
materials compared ordinary photographs with screenshot-like visual evidence, such as livestream
interfaces.

Image trust was measured through one five-point trust rating for each visual item. The
analysis compared mean trust ratings for AI-generated images and real images, and also
compared screenshot/interface-like images with ordinary photographs. An additional
route-level analysis compared accuracy and trust ratings between AI-first matched-real
materials and real-to-AI modification materials. Additional attitude items measured general
trust in online images and screenshots, the persuasive effect of interface elements,
verification habits, and self-confidence in visual judgement.

The attention-check item asked participants to select "completely disagree." Responses that
failed this check were flagged and excluded from the main analysis before
calculating detection accuracy and trust scores.

## 3.4 Integration of Primary and Supplementary Findings

The survey results were interpreted together with previous research. If the local survey
showed low detection accuracy, it would support earlier findings that unaided human detection
of AI-generated content is limited. If real images were often misclassified as AI-generated,
the results would also suggest a broader trust problem: the spread of synthetic images may
make users suspicious of real visual evidence as well.

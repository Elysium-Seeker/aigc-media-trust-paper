# 03 Methodology

## 3.1 Research Design

This study adopts a mixed-methods design combining a comparative review of published
experiments with a small-scale original survey. The published studies provide the empirical
baseline for human detection of AI-generated content across different populations and media
types. The original survey provides a local supplementary test focused on Chinese university
students' judgement of AI-generated and real visual materials.

The study asks two connected questions:

1. To what extent can Chinese university students distinguish AI-generated images and
   screenshot-like visual materials from real photographs or real screenshots?
2. How is this detection task connected to students' confidence in judging online visual
   information and their trust in digital images?

## 3.2 Primary Analysis: Existing Experimental Studies

Four sources were selected because together they support the current visual focus: human
detection of AI-generated media, image-specific detection performance, the persuasive effect
of realistic AI images, and the evidential role of screenshots.

| Source | Evidence type | Relevance |
|---|---|---|
| Frank et al. (2024) | Cross-national detection experiment | Baseline for human difficulty in detecting AI-generated media |
| Roca et al. (2025) | Large-scale image detection experiment | Image-specific accuracy and category differences |
| Guo et al. (2025) | Misinformation experiment | Realistic AI images can strengthen belief in false claims |
| Inwood & Zappavigna (2024) | Visual communication analysis | Screenshots function as visual evidence in online communication |

The analysis uses these sources to interpret not only detection accuracy but also the trust
ratings collected in the original survey. This is important because the survey asks whether
screenshot-like images produce different credibility responses from ordinary photographs.

## 3.3 Supplementary Survey

### 3.3.1 Participants

Participants are recruited through convenience sampling among university students. The survey
is distributed online through Wenjuanxing. Eligible participants should be currently enrolled
university students aged 18 or above. The final paper should replace `[N]` with the number of
valid responses collected.

### 3.3.2 Materials

The current survey uses image-only materials. It contains ten visual items: five AI-generated
images and five real images. The materials cover both ordinary photorealistic images and
screenshot-like visual evidence:

- text-bearing visual artifacts, such as postcard or document-like images;
- portrait images;
- livestream commerce screenshots;
- food photographs;
- virtual livestream or VTuber interface images.

The exact files, ground truth labels, source-judgement question numbers, and trust-rating
question numbers are listed in `Experiment/Materials_Manifest.csv`. During Wenjuanxing setup,
each image should be inserted according to that manifest. The participant-facing questionnaire
does not reveal whether a file is AI-generated or real.

### 3.3.3 Procedure

The survey has four sections:

1. Background information: year of study, social media use, AI tool use, and self-assessed
   ability to identify manipulated online content.
2. Image source judgement: participants judge each visual item using a five-point scale from
   "definitely real" to "definitely AI-generated."
3. Image trust rating: participants rate how trustworthy each visual item would seem if it
   appeared on social media or another online platform.
4. Media trust and reflection: participants answer four Likert-scale questions about visual
   media trust and one optional open-ended question about the cues they used.

No feedback is given during the task. The current Wenjuanxing import file uses a fixed mixed
order for the image items. If the survey is later rebuilt manually, item randomization can be
added in Wenjuanxing as an optional improvement.

### 3.3.4 Measures

Detection accuracy is calculated as the proportion of correctly classified source-judgement
items. For binary accuracy scoring, "definitely real" and "probably real" are counted as
correct for real images, while "probably AI-generated" and "definitely AI-generated" are
counted as correct for AI-generated images. "Unsure" is treated as incorrect or missing for the
main accuracy score.

Separate accuracy scores should be calculated for all image items, AI-generated items, real
items, and image categories. Category-level analysis is especially useful because the current
materials compare ordinary photographs with screenshot-like visual evidence, such as livestream
interfaces.

Image trust is measured through one five-point trust rating for each visual item. The analysis
should compare mean trust ratings for AI-generated images and real images, and should also
compare screenshot/interface-like images with ordinary photographs. Additional attitude items
measure general trust in online images and screenshots, the persuasive effect of interface
elements, verification habits, and self-confidence in visual judgement.

## 3.4 Integration of Primary and Supplementary Findings

The published studies establish the broader empirical pattern: unaided human detection of
AI-generated content is often close to chance level, and realistic visual materials can shape
belief and trust. The supplementary survey is interpreted against this baseline, with
attention to whether Chinese university students show similar difficulty in visual judgement,
whether screenshot-like materials create different trust responses from ordinary photographs,
and whether self-confidence aligns with actual detection accuracy.

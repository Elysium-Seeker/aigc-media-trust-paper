# AI-Generated Visual Content Detection and Media Trust

Zheng Xing, Zhang Gaoxiang, Xiong Yubo, and Wang Dexing  
Class 3, Group 6

## Introduction

Generative AI is no longer limited to producing obviously artificial images. Newer image
models can generate photorealistic scenes, readable text, and interface-like layouts. OpenAI's
GPT Image 2, for example, is documented as a current image model with the snapshot
`gpt-image-2-2026-04-21` (OpenAI, 2026a). This technical shift matters socially because
online images are often treated as evidence. A screenshot of a livestream, a social media
post, or a chat interface does not merely look like a picture; it appears to carry platform
context, timestamps, comments, accounts, and other cues of authenticity.

This paper focuses on that changing status of visual evidence. Previous research has shown
that people often struggle to distinguish AI-generated media from human-created or real media
(Frank et al., 2024; Roca et al., 2025). Recent work also suggests that realistic
AI-synthesized images can increase belief in misinformation when they seem to provide strong
evidence for a claim (Guo et al., 2025), while AI-generated images are already being used by
spammers and scammers on social platforms for audience growth (DiResta & Goldstein, 2024).
At the same time, screenshots occupy a special position in online communication because they
are frequently circulated as visual proof rather than as ordinary photographs (Inwood &
Zappavigna, 2024).

This paper asks the following research question: How accurately did university-level
respondents distinguish AI-generated images from real images across common online visual
categories, and how did their trust ratings differ by image source and category? To answer
this question, the study uses a small-scale Wenjuanxing survey as its main local data source.
Existing studies on synthetic media detection, misinformation, and visual evidence are used
to frame and interpret the survey findings.

## Methods

### Research Design

This study used a small-scale quantitative survey design. The Wenjuanxing survey provided the
main local data for testing how university-level respondents judged AI-generated and real
visual materials. Previous studies were used as background evidence because they explain why
human detection of AI-generated images is difficult and why screenshot-like materials can
influence credibility.

### Participants and Sample

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

### Materials

The survey used image-only materials. It contained eighteen visual items: nine AI-generated
images and nine real images. The materials covered both ordinary photorealistic images and
screenshot-like visual evidence. The five categories were text-bearing visual artifacts,
portrait images, livestream commerce screenshots, food photographs, and virtual livestream or
VTuber interface images.

The 18 items were selected purposively rather than randomly. Because the study focused on
online visual credibility, the materials were chosen to cover five visual types that people
commonly encounter on digital platforms. The set was also balanced by source, with nine
AI-generated images and nine real images. Therefore, the materials should not be treated as a
statistically representative sample of all online images; they were designed to compare
responses across selected image categories. The participant-facing questionnaire did not
reveal whether a file was AI-generated or real.

![Figure 1. Examples of survey stimuli by source and visual category.](stimulus_examples.png)

### Measures

The survey included source-judgement items, trust-rating items, attitude items, one attention
check, and one optional open-ended question. For each image, participants first judged its
source on a five-point scale from "definitely real" to "definitely AI-generated." They then
rated how trustworthy the same image would seem if it appeared on social media or another
online platform.

Detection accuracy was calculated as the proportion of correctly classified source-judgement
items. For binary accuracy scoring, "definitely real" and "probably real" were counted as
correct for real images, while "probably AI-generated" and "definitely AI-generated" were
counted as correct for AI-generated images. "Unsure" was treated as incorrect for the main
accuracy score. Trust was measured through one five-point rating for each image.

### Procedures

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

## Results

The Wenjuanxing survey collected 79 responses. Of these, 69 responses passed the Q42
attention-check item, giving an attention-check pass rate of 87.3%. After excluding three
attention-check passers who were outside the university-level target group, the final analytic
sample included 66 valid responses.

**Table 1. Sample screening and final analytic sample**

| Screening step | Responses |
|---|---:|
| Submitted responses | 79 |
| Passed Q42 attention check | 69 |
| Excluded for non-university-level education | 3 |
| Final analytic sample | 66 |

Across all 18 image source-judgement items, the mean detection accuracy was 47.4%. Accuracy
was higher for AI-generated images (52.9%) than for real images or screenshots (41.9%).
This means that respondents were not simply accepting all images as real; many real images
were also treated with suspicion and misclassified as AI-generated.

**Table 2. Source-judgement accuracy by visual category**

| Image category | Accuracy |
|---|---:|
| Livestream commerce screenshots | 58.3% |
| Text-bearing visual artifacts | 56.8% |
| Virtual livestream interfaces | 54.5% |
| Portrait images | 39.8% |
| Food photographs | 31.1% |

![Figure 2. Source-judgement accuracy by visual category.](accuracy_by_category.png)

Trust ratings were measured on a five-point scale from 1 ("not trustworthy at all") to 5
("very trustworthy"). Real images received a slightly higher mean trust rating (M = 2.99)
than AI-generated images (M = 2.70), but the difference was modest. By category, portrait
images received the highest average trust rating (M = 3.14), followed by text-bearing visual
artifacts (M = 2.98), virtual livestream interfaces (M = 2.73), livestream commerce
screenshots (M = 2.70), and food photographs (M = 2.62).

The attitude items showed a cautious pattern of media trust. Respondents generally did not
agree that online images and screenshots usually reflect reality (M = 2.39). At the same
time, many respondents agreed that platform elements such as interfaces, comments, or
livestream features can make screenshots more believable. Most respondents also reported
verification habits: 42 out of 66 agreed or strongly agreed that they would look for sources
or context when seeing realistic online images or screenshots.

## Discussion

### Summary of Findings

This study examined how university-level respondents judged AI-generated and real online
visual materials. The main finding is that source judgement was unstable. Across 18 image
items, the overall source-judgement accuracy was 47.4%, which means that respondents
classified fewer than half of the images correctly. Accuracy was higher for AI-generated
images (52.9%) than for real images and screenshots (41.9%). This pattern suggests that
respondents were not only fooled by AI-generated images; they also became suspicious of real
images.

The category-level results show the same problem from another angle. Livestream commerce
screenshots had the highest accuracy (58.3%), followed by text-bearing visual artifacts
(56.8%) and virtual livestream interfaces (54.5%). Portrait images had lower accuracy
(39.8%), and food photographs had the lowest accuracy (31.1%). Trust ratings were also
moderate rather than high. Real images received a slightly higher mean trust rating
(M = 2.99) than AI-generated images (M = 2.70), but the difference was small. These findings
suggest that visual authenticity is becoming difficult to judge, especially when real images
look polished or artificial.

### Comparison with Previous Studies

The local survey results are consistent with previous research on AI-generated media
detection. Frank et al. (2024) and Roca et al. (2025) both show that people often have
difficulty distinguishing AI-generated media from real or human-created media. The current
survey found a similar pattern: the overall accuracy was close to chance level, even though
many respondents reported frequent exposure to AI tools. This supports the idea that general
familiarity with AI does not automatically lead to reliable detection ability.

The findings also connect with research on trust and misinformation. Guo et al. (2025) argue
that realistic AI-synthesized images can make false information more persuasive when the
images appear to provide evidence for a claim. In this study, AI-generated images did not
receive very high trust ratings overall, but they were sometimes trusted at levels close to
real images. This matters because even moderate trust in synthetic images may be enough to
make online claims seem more credible.

Finally, the findings relate to Inwood and Zappavigna's (2024) argument that screenshots
often function as visual evidence in online communication. The attitude results in this
survey support that point: many respondents agreed that platform elements such as interfaces,
comments, and livestream features can make screenshots more believable. Therefore, the risk of
AI-generated screenshots is not only that they may be hard to detect. Their platform-like
details can also make them look socially and contextually credible.

### Possible Reasons

One possible reason for the low overall accuracy is that respondents may have used surface
visual cues too heavily. Some real food photographs and portraits looked polished, staged, or
digitally processed, so respondents may have assumed that they were AI-generated. This helps
explain why real images had lower accuracy than AI-generated images. The spread of synthetic
images may lead users to over-doubt real images, especially when those images look too clean
or visually perfect.

A second reason is that the materials were selected purposively. The 18 images were chosen to
represent common online visual categories, including text-bearing images, portraits,
livestream commerce screenshots, food photographs, and virtual livestream interfaces. Because
the set was not a random sample of all online images, the results should not be generalized
too broadly. However, this purposive design was useful for comparing how respondents reacted
to different types of online visual evidence.

A third reason is that screenshot-like materials provide contextual cues. Elements such as
platform layout, comments, prices, usernames, or livestream interfaces can make an image feel
less like a standalone picture and more like a record of an online event. These cues may
increase perceived credibility even when viewers are unsure about the image source. For this
reason, AI-generated visual misinformation should be understood not only as a problem of fake
photographs, but also as a problem of fake visual context.

### Limitations and Implications

Several limitations should be noted. First, the survey used a small convenience sample of
university-level respondents, so the results should be interpreted as descriptive rather than
representative of all social media users. Second, the stimulus set was purposively selected and
contained only 18 images. Differences in image topic, resolution, platform style, and visual
quality may have influenced participants' judgements. Third, the original prompts used to
generate the AI images were not preserved. Any prompt appendix prepared for this project should
therefore be treated as reconstructed documentation rather than an exact record of the original
generation process.

Even with these limitations, the findings suggest two practical implications. Platforms and
educators should not assume that users can reliably identify AI-generated images through visual
inspection alone. In addition, media literacy training should address not only fake photographs
but also fake visual contexts, including livestream interfaces, screenshots, comments, prices,
and other platform cues that can make synthetic material appear socially credible.

Overall, the study suggests that ordinary visual judgement is not enough for evaluating
AI-generated online images. Respondents showed limited accuracy, moderate trust, and some
uncertainty about both real and AI-generated materials. As image-generation tools become
better at producing realistic images, readable text, and interface-like screenshots, users may
need clearer platform labels, stronger verification habits, and better media literacy
training.

## References

DiResta, R., & Goldstein, J. A. (2024). How spammers and scammers leverage AI-generated
images on Facebook for audience growth. *Harvard Kennedy School Misinformation Review.*
https://doi.org/10.37016/mr-2020-151

Frank, J., Herbert, F., Ricker, J., Schönherr, L., Eisenhofer, T., Fischer, A.,
Dürmuth, M., & Holz, T. (2024). A representative study on human detection of artificially
generated media across countries. *Proceedings of the 45th IEEE Symposium on Security
and Privacy.* https://arxiv.org/abs/2312.05976

Guo, S., Zhong, Y., & Hu, X. (2025). People are more susceptible to misinformation with
realistic AI-synthesized images that provide strong evidence to headlines. *Harvard Kennedy
School Misinformation Review.* https://doi.org/10.37016/mr-2020-189

Inwood, O., & Zappavigna, M. (2024). The legitimation of screenshots as visual evidence in
social media: YouTube videos spreading misinformation and disinformation. *Visual
Communication.* https://doi.org/10.1177/14703572241255664

Metzger, M. J., & Flanagin, A. J. (2013). Credibility and trust of information in online
environments: The use of cognitive heuristics. *Journal of Pragmatics, 59*, 210-220.
https://doi.org/10.1016/j.pragma.2013.07.012

Nightingale, S. J., & Farid, H. (2022). AI-synthesized faces are indistinguishable from real
faces and more trustworthy. *Proceedings of the National Academy of Sciences, 119*(8),
e2120481119. https://doi.org/10.1073/pnas.2120481119

OpenAI. (2026a). *GPT Image 2 model.* OpenAI API.
https://developers.openai.com/api/docs/models/gpt-image-2

Pennycook, G., & Rand, D. G. (2021). The psychology of fake news. *Trends in Cognitive
Sciences, 25*(5), 388-402. https://doi.org/10.1016/j.tics.2021.02.007

Roca, T., Cintron Roman, A., Torres Vega, J., Duarte, M., Wang, P., White, K., Misra, A.,
& Lavista Ferres, J. (2025). How good are humans at detecting AI-generated images?
Learnings from an experiment. *arXiv preprint.* https://arxiv.org/abs/2507.18640

Vaccari, C., & Chadwick, A. (2020). Deepfakes and disinformation: Exploring the impact of
synthetic political video on deception, uncertainty, and trust in news. *Social Media +
Society, 6*(1). https://doi.org/10.1177/2056305120903408

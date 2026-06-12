# Results by Material Creation Route

This summary uses the same 66 valid responses as the main analysis. The route variable separates stimuli prepared through two workflows: AI-generated-first matching and real-image-based AI modification.

## Accuracy and Trust by Route

| material_creation_route   |   items |   accuracy |   mean_trust |
|:--------------------------|--------:|-----------:|-------------:|
| AI-first matched real     |     660 |       52.4 |         2.69 |
| real-to-AI modification   |     528 |       41.1 |         3.04 |

## Accuracy and Trust by Route and Ground Truth

| material_creation_route   | ground_truth   |   items |   accuracy |   mean_trust |
|:--------------------------|:---------------|--------:|-----------:|-------------:|
| AI-first matched real     | AI             |     330 |       65.2 |         2.45 |
| AI-first matched real     | real           |     330 |       39.7 |         2.92 |
| real-to-AI modification   | AI             |     264 |       37.5 |         3.01 |
| real-to-AI modification   | real           |     264 |       44.7 |         3.07 |

## Pair-Level Summary

| pair_id   | material_creation_route   | category                       | ground_truth   | image_id   |   accuracy |   mean_trust |
|:----------|:--------------------------|:-------------------------------|:---------------|:-----------|-----------:|-------------:|
| P1        | AI-first matched real     | text-bearing visual artifact   | AI             | Image 1    |       74.2 |         2.5  |
| P1        | AI-first matched real     | text-bearing visual artifact   | real           | Image 2    |       39.4 |         2.95 |
| P2        | real-to-AI modification   | text-bearing visual artifact   | AI             | Image 3    |       43.9 |         2.91 |
| P2        | real-to-AI modification   | text-bearing visual artifact   | real           | Image 4    |       69.7 |         3.55 |
| P3        | AI-first matched real     | portrait                       | AI             | Image 6    |       51.5 |         2.91 |
| P3        | AI-first matched real     | portrait                       | real           | Image 5    |       42.4 |         3.32 |
| P4        | real-to-AI modification   | portrait                       | AI             | Image 7    |       25.8 |         3.3  |
| P4        | real-to-AI modification   | portrait                       | real           | Image 8    |       39.4 |         3.02 |
| P5        | AI-first matched real     | livestream commerce screenshot | AI             | Image 9    |       74.2 |         2.03 |
| P5        | AI-first matched real     | livestream commerce screenshot | real           | Image 10   |       59.1 |         3.2  |
| P6        | real-to-AI modification   | livestream commerce screenshot | AI             | Image 11   |       54.5 |         2.64 |
| P6        | real-to-AI modification   | livestream commerce screenshot | real           | Image 12   |       45.5 |         2.94 |
| P7        | AI-first matched real     | food photo                     | AI             | Image 13   |       63.6 |         2.53 |
| P7        | AI-first matched real     | food photo                     | real           | Image 14   |       10.6 |         2    |
| P8        | real-to-AI modification   | food photo                     | AI             | Image 15   |       25.8 |         3.18 |
| P8        | real-to-AI modification   | food photo                     | real           | Image 16   |       24.2 |         2.77 |
| P9        | AI-first matched real     | virtual livestream interface   | AI             | Image 18   |       62.1 |         2.3  |
| P9        | AI-first matched real     | virtual livestream interface   | real           | Image 17   |       47   |         3.15 |

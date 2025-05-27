#  Introduction
# Motivation: Why fake news detection on social media is important
# Problem statement: Lack of editorial control on social media
# overview of Our approach: We used a user reactions (comments + emotion responses)
# Methodology Summary
1. In this work, we propose a fake news detection approach that leverages user responses on social media posts created by malicious authors. Our method analyzes two types of features:
2. Textual features: Extracted from user comments using a Bag-of-Words model combined with TF-IDF vectorization.
Visual emotion responses: Represented as categorical data reflecting users’ emotional reactions.
# Dataset
For our experiments, we use the Fake-EmoReact 2021 dataset, which was introduced as part of the shared task at SocialNLP 2021 (in conjunction with NAACL 2021). This dataset contains social media posts along with user reactions in both textual comments and emotion labels, making it well-suited for investigating fake news detection based on user responses.
# COVIDFake-EmoReact 2021 Dataset
 We use the Fake-EmoReact 2021 dataset. This dataset was created for the shared task at SocialNLP 2021 (in conjunction with NAACL 2021) focusing on fake news detection in social media using user reactions.
## Overview
COVIDFake-EmoReact 2021 is a benchmark dataset for fake news detection, specifically designed to explore how user responses, including textual comments and emotional reactions, can help identify misinformation related to COVID-19 on social media platforms.
## Dataset Features
- **Social Media Posts:** Posts related to COVID-19.
- **User Reactions:**
  - Textual replies/comments.
  - Emotion annotations representing users’ affective responses.
- **Labels:** Each post is annotated as either **Fake** or **Real** based on fact-checking and ground truth.
## Use Cases
This dataset is ideal for research in:
- Fake news detection.
- Emotion and sentiment analysis on social media.
- Multi-modal learning combining textual and emotional signals.
- User behavior analysis in misinformation spread.
## Resources
- Official website and task details: [COVIDFake-EmoReact 2021](https://sites.google.com/view/covidfake-emoreact-2021/)
- Task organized as part of SocialNLP 2021 and NAACL 2021 shared tasks.





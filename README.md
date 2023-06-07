# Python Video Quality Metrics

This repository focuses on the creation and implementation of objective video quality models. These models are designed to predict the quality of digitally encoded videos by undergoing various validation tests. By comparing these objective measures with users' subjective opinions of video quality, valuable insights can be gained.

## Objective Video Quality Models

The repository encompasses objective video quality models, which can be categorized into three main types:

1. Full Reference (FR): FR models compare the original uncompressed video with the compressed version. By analyzing the differences, these models provide insights into the perceived quality of the compressed video.

2. No Reference (NR): NR models evaluate the quality of compressed videos without the need for a reference to the original video. They analyze various features and characteristics of the compressed video to estimate its quality.

3. Reduced Reference (RR): RR models strike a balance between FR and NR models. They utilize a limited set of reference information to evaluate the quality of compressed videos. This reduced set of references enables faster and more efficient quality assessment.

## Usage and Validation

The Python Video Quality Metrics repository provides tools and resources to implement and validate objective video quality models. Users can leverage these models to predict the quality of digitally encoded videos in their own projects. Additionally, the repository offers validation tests that enable users to compare the objective measures with subjective opinions of video quality.

The validation tests help identify the measures that most closely align with users' opinions. By selecting the measures that exhibit the highest correlation, more accurate predictions of video quality can be achieved.

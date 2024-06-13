# POLI 179 Final Project - Visual Elements and Their Effects on Instagram Post Popularity for Politicians
# Research Question
How does different content and graphic design choices present in politicians' Instagram posts influence their popularity? What are the prevailing themes or content for each party?


### Group 
- Karen Ha
- Ian Britton

# Summary

### Introduction
In the digital age, Instagram has become a pivotal platform for political communication. Politicians utilize it to engage with constituents, shape perceptions, and influence voter behavior. This project investigates the visual elements contributing to the popularity of politicians' Instagram posts, focusing on image content and emotional expressions. By applying advanced computer vision techniques, we aim to uncover patterns and insights that inform effective social media strategies for political candidates. The datasets and study that we replicated are referenced at the bottom of this README file. Our data processing and dataset is linked in [this](https://drive.google.com/drive/folders/1vSQgHlCuGaPpiC9AMSvyqTXj-m2gUAS6?usp=sharing) google drive link.

### Methods 
Feature Extraction
We utilized the VGG16-hybrid model for feature extraction. This model processes images to identify and encode visual elements, creating feature vectors that represent each image's content. These extracted features were saved for further analysis.

Dimensionality Reduction and Clustering
Principal Component Analysis (PCA) was employed to reduce the dimensionality of the feature vectors, retaining the most significant components. Subsequently, K-means clustering was applied to group the images based on visual similarities. This method allowed us to categorize images effectively and identify patterns based on their visual content.

### Analysis
Data Sources
Initially, we planned to use the dataset from Peng (2020), but due to access restrictions, we opted for the dataset from Bossetta and Schmokel (2022). This dataset includes Instagram posts from a 15-month period during the 2020 U.S. presidential election, comprising images and related metadata.

Data Processing
The data processing involved several steps:

  - Feature Extraction: Using the VGG16-hybrid model, features from each image were extracted and saved.
  - PCA
  - K-means Clustering:

### Conclusion
This study reveals that Instagram posts by U.S. politicians featuring personal, nonpolitical
settings, their faces, and emotional expressions significantly boost engagement, as mea-
sured by likes and comments. The preference for personalized content highlights users’
desire for relatable portrayals of politicians. Notably, politicians’ faces, particularly larger
ones displaying positive emotions, drive higher engagement. The use of computer vision
and clustering techniques to analyze visual data offers valuable insights for political com-
munication strategies on social media. The methods employed in the original study are very
easily transferable and expanded upon with other image sets and are good for noticing pat-
terns in visual data. These findings suggest that personal and emotional visual content is
crucial for enhancing audience interaction on Instagram.
In conclusion, this research underscores the importance of visual personalization in en-
hancing audience engagement on Instagram for U.S. politicians. By showcasing personal,
relatable, and emotionally engaging content, politicians can foster stronger connections
with their followers. The study’s use of computer vision and clustering techniques to an-
alyze large-scale visual data provides a robust framework for future research in political
communication. Future studies should explore the effects of personalized content across
different social media platforms and consider how these strategies impact voter perceptions
and behaviors beyond social media engagement.


# References 
Bossetta, M. (2023, October 3). Cross-Platform Emotions and Audience Engagement in Social Media Political Campaigning: Comparing Candidates’ Facebook and Instagram Images in the 2020 US Election. Retrieved from osf.io/g69tr

Peng, Y. (2020). What Makes Politicians’ Instagram Posts Popular? Analyzing Social Media Strategies of Candidates and Office Holders with Computer Vision. 
The International Journal of Press/Politics, 26(1), 143 - 166, https://doi.org/10.1177/1940161220964769. 

​




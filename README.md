# fake-news-detector [Out Dated]

## **Sumary**

The goal of this text is to analyse and elaborate on the results obtained from the fake news detector contained in this repository, a classifier aimed at dicerning between fake and real news automaticaly. There is a report on the matter as well in this repository, this text acting as a preliminary version of it.

The classifier consists of a Logistic Regression applied on a pre-processed dataset, which first had it's stop words removed, was them lemmatized and finally vectorized.

The dataset chosen for this project focuses on fake news detection in online media. It consists of labeled articles classified as either true or false, offering a clear business case for detecting misinformation. 

## **Dataset Source**:

The dataset was initially discussed in the context of bridging the gap between AI and human linguistic judgment, as highlighted in the paper "AI vs linguistic-based human judgement: Bridging the gap in pursuit of truth for fake news detection" [1]. The business application, therefore, is to leverage AI models to assist human fact-checkers in quickly filtering out potentially harmful or misleading content. The dataset used in the paper focuses on classifying news articles by their veracity, utilizing AI to detect linguistic cues associated with fake news.

In addition to the primary dataset used in our project, the paper also references the COVID Fake News Dataset, which was collected during the pandemic to track misinformation specifically related to COVID-19. This dataset contains thousands of news articles and social media posts flagged as either true or false, focusing on topics such as vaccination, infection rates, and public health measures. It provides a real-world example of how AI models can be applied to detect misleading content during crises, where the rapid spread of false information can have dire consequences.

## **Data Pre-processing**

### *Pre-processing Function*

### *Data Segmentation*

### *Subject Separation*

### *Data Downsampling*

## **Classification Pipeline**

## Results

## Conclusion

References

[1] AI vs linguistic-based human judgement: Bridging the gap in pursuit of truth for fake news detection.

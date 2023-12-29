# **Analysing Effect of COVID-19 on Songs Using Sentiment Analysis**

## **Overview**
Technology advancements have facilitated the easy showcasing of new music via streaming platforms, leading to an unprecedented abundance of musical content. This research project aims to explore the impact of COVID-19 on music sentiments using sentiment analysis. By analyzing the emotional content of songs written during the pandemic era, the study seeks to understand the recurring patterns of emotions and reactions reflected in popular music.

## **Objectives**
### **1. Research Questions**
- *How does the balance between positive and negative lyrics in songs capture the overall public emotion during the COVID-19 pandemic?*
- *How well can machine learning methods like RNN be used to predict the sentiment of music lyrics?*

### **2. Research Aim**
Utilizing deep learning and pre-trained models, the project aims to identify the emotional content of songs during the COVID-19 pandemic. RNN (Recurrent Neural Network) will be employed for sentiment analysis, and the accuracy of the models will be cross-verified using a pre-trained model.

### **3. Research Objectives**
1. **Literature Review and Data Collection**
   - Critically assess the importance of the topic, prior studies, and challenges in song sentiment analysis.
   - Gather music-lyric datasets from before and after 2019.
2. **Model Development**
   - Create a sentiment analysis model using lyric elements to determine the mood of songs during the COVID-19 period.
3. **Model Training and Validation**
   - Pre-process data, train, assess, and modify the sentiment analysis model.
   - Validate the model using a pre-trained 'en-sentiment' model and a large dataset.
4. **Performance Evaluation**
   - Assess the deep learning model's performance using visualizations and comparisons with other trained models.
5. **Presentation of Findings**
   - Present study findings through a written research paper and project viva.

## **Implementation**
The project is implemented using Google Colab and the Pandas framework for Python programming within Jupyter Notebook (Anaconda IDE).

## **Usage**
To replicate or extend this study:
1. Clone the repository.
git clone https://github.com/jiageorg/-Analysing-effect-of-Covid-19-on-Song-Using-Sentiment-Analysis

2. Follow the Jupyter Notebooks in the notebooks directory for step-by-step implementation.
3. Use the provided datasets or replace them with your own for analysis.

## **Results**
### **Results Of LSTM-GRU Model**
Analysis of sentiment data is essential in the COVID-19 era for comprehending audience reactions and emotions. To analyze such data, LSTM-GRU hybrid model was built. With 51.9% negative attitudes and 48.1% positive feelings, the test dataset, which is representative of this time period, displayed a slightly more negative sentiment distribution. It depicts a negative sentiment that captures the difficulties and unpredictability experienced globally throughout the pandemic.

![Percentage of each sentiment category in the test set of LSTM-GRU model.](https://github.com/jiageorg/-Analysing-effect-of-Covid-19-on-Song-Using-Sentiment-Analysis/blob/master/git1.1.png)

### **Results Of En-sentiment Model**
Intriguing insights were obtained from applying the en-sentiment model to the dataset that had undergone the same pre-processing procedures as the LSTM-GRU model. The model assigned 2117 of the 3655 numbers made public during the COVID-19 period as negative, and 1538 as positive. In line with the findings of the LSTM-GRU model, this sentiment classification implies that songs produced during the epidemic frequently express unpleasant sentiments. Most of these statistics consistently exhibit negative emotion, according to both models. It highlights the enormous effect of the epidemic on the emotional tone of music and captures the mood of the world during these trying times. These findings demonstrate how well both models capture emotional tendencies in the dataset and suggest how emotional contagion may affect artistic expression.

![Distribution of each sentiment category by en-sentiment model](https://github.com/jiageorg/-Analysing-effect-of-Covid-19-on-Song-Using-Sentiment-Analysis/blob/master/git1.png)
### **Results of En-sentiment Model Validation**
Using a manually annotated dataset with the lyrics to 8 songs and their associated sentiment labels, the en-sentiment classifier was validated. For model validation, this manually created dataset served as the "ground truth". In 7 out of 8 instances, the model accurately identified the sentiment, displaying an amazing accuracy of 87.5%. The model's ability to accurately identify the sentiment of lyrics is highlighted by this high level of accuracy. The pre-trained model is validated to confirm its accuracy and reliability before being used for other lyric sentiment analysis tasks.

## **Acknowledgments**
This project acknowledges the availability of public datasets and the contributions of the open-source community.

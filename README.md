# Covid-19-Predictive-Analysis

This repository contains the Twitter data (training) on Covid-19 initially from early 2020 (March-June). It is a multi-head dataset with the following parameters:

   ⦁ *serial No*
   ⦁ *Date of the tweet(s)*
   ⦁ *Time of the tweet(s) in IST*
   ⦁ *Source link*
   ⦁ *User ID*
   ⦁ *Language*
   ⦁ *Retweet counts*
   ⦁ *Hashtags (only related to Covid-19)*
   ⦁ *User mentions (if any)*
   ⦁ *Place of the tweet(s)*
   ⦁ *Tweet body*

<br>        
This dataset is part of the publication entitled:
<br>

 > Das, S., & Kolya, A. K. (2021). Predicting the pandemic: sentiment evaluation and predictive analysis from large-scale tweets on Covid-19 by deep convolutional neural network. Evolutionary Intelligence, 1-22.
<br>

## Dataset Creation

<div align="justify">
Twitter is probably the most sophisticated and popular platform for live streaming textual data. Mostly because of its “micro-blogging” nature and short targeted texts, the data which are scrolled from Twitter is full of raw data which can further be processed into insightful information. While Twitter API only lets developers to stream 1–2% number of total tweets per hour, the scale of the Twitter user’s community is large enough to gather a large source of the corpus on any given topic. From 7th November 2017, Twitter expanded its character limits to 280 characters per tweet. Hence the target probability of tweet collection is now higher than ever before. For March and April 2020, we collected tweets exclusively on Coronavirus or Covid-19. Also, we collected parallel tweets after Indian Prime Minister Modi’s live speech on 24.03.2020 and US President Donald Trump’s press briefing on 02.04.2020, to gain valuable mass opinion insight on the given topic. We scroll our tweets based on certain parameters for scaling, naming tweet id, the original tweet body, retweet count, location or region, date, and time.
 
<br>

## Abstract

<div align="justify">
Engaging deep neural networks for textual sentiment analysis is an extensively practiced domain of research. Textual sentiment classification harnesses the full computational potential of deep learning models. Typically, these research works are
carried either with a popular open-source data corpus, or self-extracted short phrase texts from Twitter, Reddit, or webscrapped
text data from other resources. Rarely do we see a large amount of data on a current ongoing event is being collected
and cultured further. Also, an even more complex task would be to model the data from a currently ongoing event, not only
for scaling the sentiment accuracy but also for making a predictive analysis for the same. In this paper, we propose a novel
approach for achieving sentiment evaluation accuracy by using a deep neural network on live-streamed tweets on Coronavirus
and future case growth prediction. We develop a large tweet corpus exclusively based on the Coronavirus tweets. We
split the data into train and test sets, alongside we perform polarity classification and trend analysis. The refined outcome
from the trend analysis helps to train the data to provide an incremental learning curvature for our neural network, and we
obtain an accuracy of 90.67%. Finally, we provide a statistical-based future prediction for Coronavirus cases growth. Not
only our model outperforms several previous state-of-art experiments in overall sentiment accuracy comparison for similar
tasks, but it also maintains a throughout performance stability among all the test cases when tested with several popular
open-source text corpora.
          
          
## Paper

The paper explaining this dataset and the detailed experimental approach can be *downloaded* from [Springer Nature SharedIt](https://rdcu.be/chI8I) or [Evolutionary Intelligence](https://link.springer.com/content/pdf/10.1007/s12065-021-00598-7.pdf).

<br>

**Please cite the following paper if you utilize the dataset in your research:**

> @article{das2021predicting,
  title={Predicting the pandemic: sentiment evaluation and predictive analysis from large-scale tweets on Covid-19 by deep convolutional neural network},
  author={Das, Sourav and Kolya, Anup Kumar},
  journal={Evolutionary Intelligence},
  pages={1--22},
  year={2021},
  publisher={Springer}
}

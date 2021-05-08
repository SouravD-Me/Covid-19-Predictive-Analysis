# Covid-19-Predictive-Analysis

This repository contains the Twitter data (training) on Covid-19 initially from early 2020 (March-June). It is a multi-head dataset with the following parameters:

          -Serial No.
          -Date of the tweet(s)
          -Time of the tweet(s) in IST
          -Source link
          -User ID
          -Language
          -Retweet counts
          -Hashtags (only related to Covid-19)
          -User mentions (if any)
          -Place of the tweet(s)
          -Tweet body
        
This dataset is part of the publication entitled:

          > Das, S., & Kolya, A. K. (2021). Predicting the pandemic: sentiment evaluation and predictive analysis from large-scale tweets on Covid-19 by deep convolutional neural
            network. Evolutionary Intelligence, 1-22.
            
## Dataset Creation

Twitter is probably the most sophisticated and popular platform for live streaming textual data. Mostly because of its “micro-blogging” nature and short targeted texts, the data
which are scrolled from Twitter is full of raw data which can further be processed into insightful information. While Twitter API only lets developers to stream 1–2% number of total
tweets per hour, the scale of the Twitter user’s community is large enough to gather a large source of the corpus on any given topic. From 7th November 2017, Twitter expanded its character limits to 280 characters per tweet. Hence the target probability of tweet collection is now higher than ever before. For March and April 2020, we collected tweets exclusively on Coronavirus or Covid-19. The tweets were extracted w.r.t to the parameters like username, date, time, retweet, and country or location, etc. of the tweet. Also, we collected parallel tweets after Indian Prime Minister Modi’s live speech on 24.03.2020 and US President Donald Trump’s press briefing on 02.04.2020, to gain valuable mass opinion insight on the given topic. We scroll our tweets based on certain parameters for scaling, naming tweet id, the original tweet body, retweet count, location or region, date, and time.
     

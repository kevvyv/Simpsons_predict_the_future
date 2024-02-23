
# Abstract

In this research project, our goal was to investigate the supposed predictive power of "The Simpsons" in anticipating real-world events. Theorists online believe the show has the ability to predict future occurrences, including Trump's presidency, Disney's Fox purchase, and the coronavirus pandemic. To further explore our topic, we completed an exploratory data analysis (EDA) utilizing a diverse range of datasets, including transcripts of all "Simpsons" episodes, New York Times headlines, and associated metadata. Our approach involved extracting topics from both "The Simpsons'' scripts and New York Times articles, allowing us to compare thematic content and assess potential overlaps. To obtain statistics for how successful the episodes were in predicting real world events, we utilized the dictionary generated after conducting a cosine similarity comparison. Our research contributes to the ongoing discourse surrounding the show's predictive nature and offers insight into the significance of considering several data sources and analytical techniques in media analysis.
# Research Question

General Question: What percentage of the Simpsons’ episodes’ transcripts reference real-world events before they appear as part of a New York Times headline. 
- Subquestion: How closely do the episode's transcripts' air date and New York Times' article publication dates coincide?

## Background and Prior Work


The Simpsons, debuting on Fox in 1989, is one of the longest-running television shows in modern American history with over 34 seasons and counting. With a growing episode count, the American cartoon family has easily made thousands of jokes about scenarios so wild that they could never come true… or could they?

Conspiracies regarding the predictive power of The Simpsons date back to the early 2000s. It is believed rather jokingly that the Simpsons predicted the presidency of Donald Trump, Disney’s purchase of Fox and even more bizarrely the coronavirus pandemic.<a name="cite_ref-1"></a>[<sup>1</sup>](#cite_note-1) CNN reported *The Simpsons* as being the "pop culture Nostradamus" for predicting Lady Gaga's eventual Super Bowl performance and the Siegfried and Roy Tiger Attack.<a name="cite_ref-2"></a>[<sup>2</sup>](#cite_note-2) These coincidences all seem to point toward The Simpsons and its uncanny ability to predict the future. Several other publications have their doubts however, including the *New York Times* themselves who argue that the *prophetic visions* in the show are at best plausible predictions and at worst a product of a massive sample size.<a name="cite_ref-3"></a>[<sup>3</sup>](#cite_note-3) This leads us to our main question: what percentage of The Simpsons’ script came true.

While data projects analyzing the Simpsons have existed prior to our own, such as the excellent "The Simpsons Meets Data Visualization by Adam Reevesman" <a name="cite_ref-4"></a>[<sup>4</sup>](#cite_note-4) and Todd W. Schneider's "The Simpsons by the Data"<a name="cite_ref-5"></a>[<sup>5</sup>](#cite_note-5), much of the data analysis there explores the structure and patterns of the show itself and not of its predictivity of real-world events. Largely, these analyses report on things like the prominence of specific characters on screen, which characters talk to whom the most, and the sentiment analysis of various characters.



1. <a name="cite_note-1"></a> [^](#cite_ref-1) Simpsons Predicts the Future. (2018, February 26). Know Your Meme. https://knowyourmeme.com/memes/simpsons-predicts-the-future 
2. <a name="cite_note-2"></a> [^](#cite_ref-2) France, L. R. (2020, May 8). Another example of “the Simpsons” predicting future. CNN. https://www.cnn.com/2020/05/08/entertainment/simpsons-coronavirus-insects-predictions/index.html 
3. <a name="cite_note-3"></a> [^](#cite_ref-3) Salam, M. (2018, February 2). “the Simpsons” has predicted a lot. most of it can be explained. The New York Times. https://www.nytimes.com/2018/02/02/arts/television/simpsons-prediction-future.html 
3. <a name="cite_ref-4"></a>[^](#cite_note-4) Reevesman, A. (2022, October 13). The Simpsons meets Data Visualization. Medium.https://towardsdatascience.com/the-simpsons-meets-data-visualization-ef8ef0819d13
4. <a name="cite_note-5"></a> [^](#cite_ref-5) Schneider, T. (2016, September 28). The Simpsons by the Data. toddwschneider.com. https://toddwschneider.com/posts/the-simpsons-by-the-data/ 

# Hypothesis

#### Less than 1% of the content in *The Simpsons'* episodes' transcript reference real-world events before they appear in the New York Times' headlines.
- Subhypothesis: Whenever these *The Simpsons'* transcripts' predate an event which is later referenced in the New York Times, the New York Times article will reference it at least 10 years afterwards.

Reasoning: We believe that *The Simpsons'* fabled ability to predict the future is reliant on coincidences. As the series has continued, their jokes have been so numerous that a select minority of them are bound to have become real.

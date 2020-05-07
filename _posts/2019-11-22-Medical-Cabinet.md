---
layout: post
title: Medical Cabinet
subtitle: Using Natural Language Processing to suggest a strain for the users needs by Jean Fraga
cover-img: /assets/jimg/medical-marijuana_cover.jpeg
tags: [data-science, NLP]
---

### My humble thoughts on the project before you dive deeper

As a note to anyone reading this, I do not use or have a need to use Marijuana. I respect anyone's opinion to use this plant as a medicine or otherwise. I hope that this small blog post will be useful to those interested in understanding how I built my flask APP on [Canabis-API2](https://cannabis-api-2.herokuapp.com/).

This project is pretty simple but makes use of some very cool NLP(natural language processing) techniques. I hope to make use of more advanced NLP in the future like I did with the next project I worked on. I will outline how I built the HTML fornt end and how the model that makes the predictions was built.

If you have any questions please feel free to send them to me and I will do my best to answer them.

Enjoy!

## The data I used to make the model

![Data](https://raw.githubusercontent.com/JeanFraga/JeanFraga.github.io/master/assets/jimg/dataframe_table.png){: .center-block :}

This dataset comes from [kaggle](https://www.kaggle.com/kingburrito666/cannabis-strains) and was kindly provided by [leafly](leafly.com).

It contains 2350 unique strains with their corresponding type(Hybrid, Indica, Sativa), rating(0.0-5.0 by users), Effects(Uplifted, Happy, Relaxed, etc.), taste(of smoke), and a description(brief, about the plants background).


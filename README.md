# Disaster Post Classification on Social media.

* In this repo a natural language model has been trained and developed to classify post as fake or real regarding natural disasters
earthquake, cyclone, etc.

Social media has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).

But, it’s not always clear whether a person’s words are actually announcing a disaster. 

* Take this example:

![kd](https://i.ibb.co/5FJPby7/tweet-screenshot.png)
* **Tweet source:** https://twitter.com/AnyOtherAnnaK/status/629195955506708480

The author explicitly uses the word “ABLAZE” but means it metaphorically. 
This is clear to a human right away, especially with the visual aid. But it’s less clear to a machine.

* In this project I  build a machine learning model that predicts which posts are about real disasters and which one’s aren’t.

* **Disclaimer: The dataset for this model contains text that may be considered profane, vulgar, or offensive.**
### Acknowledgments

* This dataset was created by the company **figure-eight** and originally shared on their [**‘Data For Everyone’**](https://www.figure-eight.com/data-for-everyone/) website.

* First step was building a language model which can learn and under stand tweets.

* I was able to get an accuracy of 49% with help of learning rate finder.

![kd](https://i.ibb.co/bdk3vtv/lm1.jpg)

* Then I build a classification model to classify the post as real or fake.
* And was able to achieve an accuracy of **80.3681 %.**

![kd](https://i.ibb.co/FqSKFH4/cl1.jpg)
![kd](https://i.ibb.co/0nRNWLZ/acc.jpg)

* Confusion Matrix:

![kd](https://i.ibb.co/C1gkFyp/confusion.jpg)

* Top losses:

![kd](https://i.ibb.co/8bppzwm/top-losses.jpg)

* For fun lets see how accurate the language learner model can complete sentenses and post.

![kd](https://i.ibb.co/Qj8RyPD/tweet-comp.jpg)

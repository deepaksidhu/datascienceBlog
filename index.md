**Title:** Ensembles assembled in Teens Mind
-----------------------------------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------------------------------

**Motivation:**
-----------------------------------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------------------------------

Teenagers are exposed to vast amount of information they see on different medias. Often these information influences and makes up the norm of how they think and process situations.  As a consequence of information overload, they usually struggle to pick one option out of combination of good and bad alternatives. Most of their instincts in decision making are influenced by the opinion of their closest friends. However, the choices made by the friends are quite varying and diverse. Leaving teens with the dilemma of not knowing what to pick? This blog post will inform teens on how to make confident choices based on the data science concept of ensemble methods for classification. They will feel more in control and assured of the decisions they will make, and reduce the indecisiveness they experience.

<img src="http://meritcd.com/blogs/wp-content/uploads/2014/04/Decision-Making.jpg" width="400" height="400">

[Source](http://meritcd.com/blogs/improve-your-decision-making-improve-your-leadership-2/)

**Explanation of Ensembles**
-----------------------------------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------------------------------
Often you are presented with a list of options, for instance your alarm wakes you up in the morning, you are immediately confronted with the choice of whether to sleep more or to get up and get ready for school. Another common situation could be you are in school, and you could either skip class or not (I advise you not to). Moreover, when you get back home, you can either decide to do your homework or play your favourite computer game, which is definitely more exciting. Just based on these few examples, you are presented with choices at every turn. It is often a hard task to deliberate all the options and choose the one that fits you.

The idea of the data science concept, ensemble, suggests you the best possible decision for your circumstance. I know I am speaking of some technical jargon with the use of the word ensemble, this ideas will be addressed by the examples below.

Consider the situation when you're family is going for picnic, there is going to be a collection of different choices for each family member for the picnic site. For an example you prefer to go to an amusement park, but your parents prefers to have the picnic by the river. Another trivial example is, the choice of movie you and your group of friends will go and watch. Again in this examples there is going to be difference in informed preferences of which movie to watch. The situation in which you have to make informed choice is where the concept of ensemble helps. You can consider ensemble as a collection of informed choices based of your friends. But, how can you select from this collection of informed choices? 



The majority choice in the collection corresponds the best option. In order to understand this concept better, I will talk about the dilemma among teens when they are confronted with the decision of buying either a *Playstation 5* or *XBOX X*.

<img src="https://cdn.vox-cdn.com/thumbor/XMqSAUQJXb2YvHqdnbOOpqFkg1U=/0x0:924x616/1200x800/filters:focal(389x235:535x381)/cdn.vox-cdn.com/uploads/chorus_image/image/66520393/ps5vsxbx.0.jpg" width="400" height="300">

[Source](https://cdn.vox-cdn.com/thumbor/XMqSAUQJXb2YvHqdnbOOpqFkg1U=/0x0:924x616/1200x800/filters:focal(389x235:535x381)/cdn.vox-cdn.com/uploads/chorus_image/image/66520393/ps5vsxbx.0.jpg)


Teenagers are confused on whether they should buy a Playstation 5 or Xbox X. Most of them will do their research, compare the specifications and look at reviews, but still have a hard time deciding. When they are torn with the options, they would ask the opinion of their friends, but they often have varying degree of preferences, which makes matter worse.

This kind of dilemma, can be dealt with the idea of ensemble methods for classification. The way this concept work in this situation is that, the teen should consider a group (ensemble) of their closest friends whose opinion they value, preferably they should choose an odd number of friends. In this approach, it is important to consider that each of the friends are unique individuals, whose thinking process has been influenced by a variety of factors such as, upbringing, ethnicity, social condition, family composition and others. It is important to stress here that the choice (playstation vs xbox) made by the friend has been trained by the factors mentioned above. Each friend is a considered as separate unit with informed thought process and mechanism to decide, hence a classification model. The question now is, how can a teen choose with this collection of inputs?


Imagine a situation when the teacher asks the class on whether the quiz should be open book or not? The teacher does a survey of yes and no's and decides the quiz to be open book, based on the majority choice. This is the idea behind how the ensemble method facilitates decision making for a particular situation. For the gaming platform question, once the preferences of the friends have been collected, this collection of choices is what we call an ensemble. Now that we have the ensemble of choices we carry out the majority vote counting principle. The most voted option is considered to be the best choice of gaming platform. Choosing an odd number of friends, helps assure that we don't have any tie breakers and we get the best option. Question now is, why is the choice suggested by the ensemble method is the best choice, rather than the you going with your gut feeling?

To get an idea of why considering an ensemble of choices works better than just going with a random choice is illustrated by the graphic below. The check marks(✅) on the graphic corresponds to the ideal choice of platform, while the cross mark(❌) corresponds to the wrong choice of platform.

| Example | Friend 1    | Friend 2   |  Friend 3  | Ensemble |
|--------|--------|--------|---------|---------------|
|  1     | ✅    |   ✅    | ❌     | ✅✅❌=>✅  |
|  2     | ✅    |   ❌    | ✅     | ✅❌✅=>✅  |
|  3     | ❌    |   ✅    | ✅     | ❌✅✅=>✅  |

We can see from the graphic that if we only consider the opinion of one our friend, or more so just our own opinion we are likely to make a mistake. But if we consider the collection of opinions and do majority voting we reduce the chances of making a mistake for which platform to purchase. This is based on the hypothetical that we know what the ideal platform of choice is, represented by the check mark. More over the idea of ensemble works well, if the opinion of our friends are varied enough.

**Conclusion:**
-----------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------

The idea for  making choices based on an ensemble method for classification can be extend to other choices that you are deliberating on. This approach will help you make better informed choices and decisions. Furthermore, once you go and study data science you will appreciate it and will have a head start compared to others.

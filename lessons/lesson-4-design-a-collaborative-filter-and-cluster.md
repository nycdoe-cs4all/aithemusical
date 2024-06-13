---
description: We both liked that so if you like this, I might like it too!
---

# 💿 Lesson 4: Design a Collaborative Filter & Cluster

{% hint style="info" %}
### Essential Questions:



What characteristics would make you describe two people as 'similar'?



To what extent do 'similar' people like 'similar' things? (e.g. books, movies, songs, ideas)
{% endhint %}



### Anchor Text(s) for this Lesson

* Slide deck&#x20;
* “[How Spotify’s AI-Driven Recommendations Work](https://www.youtube.com/watch?v=pGntmcy\_HX8)”
* Sentence strips with song titles arranged at various stations&#x20;

### Supporting Text(s)/ Resources for this Lesson

* Template for students to write their playlist&#x20;
* [How Recommendation Systems Work](https://www.youtube.com/watch?v=n3RKsY2H-NE)

### Lesson Overview

In this lesson, students will learn about collaborative filtering used in recommendation systems. Students will consider the general premise of collaborative filtering: That ‘similar’ listeners are likely to have similar song preferences. Students will first compile personal playlists by revisiting the song library (sentence strips held at each station) and engage in a fast-paced activity to find ‘similar’ listeners. The lesson concludes with a critical discussion about what other data might be used to get a more detailed idea of individual listeners’ attributes to provide ‘better’ recommendations.



### Nota Bene

You know your students best! Since students will be compiling playlists in this lesson, you might consider assigning each song a number to facilitate notetaking for students who need that scaffold. Regarding the 3-part activity in this lesson, <mark style="color:yellow;">c</mark>[<mark style="color:yellow;">heck out this video for suggestions on how to structure the lightning round</mark>](https://www.youtube.com/watch?v=I7\_PfCBBcFI)<mark style="color:yellow;">.</mark>&#x20;

### Objectives

Students will be able to...

* create a playlist from a given data set;
* compare personal playlist with peers' playlists;
* simulate a clustering algorithm by placing oneself in proximity with others based on playlist similarities;
* actively listen to peers' ideas and observations and ask follow-up questions;
* communicate observations and answer peers' follow up questions;

### Suggested duration

45 minutes (adjust according to your students' needs)

### NYS Next Generation ELA Standards

* **SL1**: Initiate and participate effectively in a range of collaborative discussions with diverse partners on complex topics, texts, and issues; express ideas clearly and persuasively, and build on those of others.
* **W1c:** Use precise language and content-specific vocabulary to express the appropriate complexity of the topic.

### NYS Computer Science & Digital Fluency Standards

* **9-12.CT.10:** Collaboratively design and develop a program or computational artifact for a specific audience and create documentation outlining implementation features to inform collaborators and users.
* **9-12.IC.5** Describe ways that complex computer systems can be designed for inclusivity and to mitigate unintended consequences.
* **9-12.IC.3** Debate issues of ethics related to real world computing technologies.
* **9-12.IC.1** Evaluate the impact of computing technologies on equity, access, and influence in a global society.

### Vocabulary

* <mark style="color:purple;">**collaborative filter**</mark>: uses similarities between users and items simultaneously to provide recommendations ([source](https://developers.google.com/machine-learning/recommendation/collaborative/basics))
* <mark style="color:purple;">**explicit**</mark>:  saying something clearly, exactly, and openly; clear and easy to understand
* <mark style="color:purple;">**implicit**</mark>: suggested without being directly expressed
* <mark style="color:purple;">**assumption**</mark>: a belief or feeling that something is true or that something will happen, although there is no proof

### Hook

Give students time to think, write, and talk with a partner about the following prompts:&#x20;

What thoughts, questions or concerns come to mind when you read this fact about recommendation algorithms: “The things that are recommended to you are based on patterns the machine has observed in other people who are similar to yourself.”

* What makes you ‘similar’ to another person?
* What information might the machine be basing this ‘similarity score’ on?
* What information might be missing that would very much impact your listening preferences (in our music app example)?

Facilitate a class-wide discussion by asking students to share what they discussed with their partner.

### Mini Lesson&#x20;

This is a short mini-lesson that should impart the following key information. The idea is to give students foundational knowledge to inform the 3-part activity, which is followed by a critical discussion about data.

Present the following information to students in one of two ways: Show the clip from the video “[How Spotify’s AI-Driven Recommendations Work](https://www.youtube.com/watch?v=pGntmcy\_HX8)” (from 1:40 to 4:01) with the following purpose for viewing questions: How does Spotify use “collaborative filtering” to make recommendations?

OR, simply present the information to students via bullet points on slides that you briefly explain. The main understanding for students to grasp at this point is that collaborative filtering is based on the idea that by grouping listeners with shared song preferences, we can make predictions about what songs they might like. In other words: We both liked that so if you like this, I might like it too!

You can also think of it as a Venn diagram representing two listeners with a fat overlap of shared song preferences; the assumption made by the collaborative filtering model is: since you share a preference for all these songs, let’s pull songs from outside the overlap as recommendations for the other. In other words, all the songs outside the overlap become potential recommendations.&#x20;

### Activity

This is a three part activity.&#x20;

1. Part One (ten minutes): Students revisit the collection of songs generated during lesson one to create a personalized playlist of 8 to 10 songs. The songs should be organized again by stations. Encourage students to visit various stations as they compile their playlists.&#x20;
2. Part Two (ten minutes): Students participate in a lightning round where they meet with several other students, one by one, to very quickly compare their playlists. The goal of this activity is for students to ‘process’ the data (the playlists generated by the class) to identify clusters of ‘similar’ listeners. &#x20;

&#x20;       As students compare playlists with others, ask     them to take note of who they share 3 or more common songs with.

3. Part Three (two minutes): Students quickly organize themselves into groups based on shared preferences. The more songs in common, the closer students will stand in relation to each other. (This is an unplugged simulation of a clustering algorithm--think of the collaborative filtering map you saw in the video “[How Spotify’s AI-Driven Recommendations Work](https://www.youtube.com/watch?v=pGntmcy\_HX8)”)

### Wrap Up&#x20;

Using Kapor Component 5 as a guide, engage students in a critical discussion about the types of data that might be used to improve the recommendation algorithm.&#x20;

<figure><img src="../.gitbook/assets/Screenshot 2024-05-30 at 1.44.43 PM.png" alt=""><figcaption><p>Kapor Framework Component 5</p></figcaption></figure>

* Can you imagine using this technique to help your friends find new songs they might like? Why or why not?
* What additional data might we include about listeners to improve our recommendation algorithm?
  * Location data?&#x20;
  * Zip code?
  * Gender?&#x20;
  * Age?
  * How many steps you take each day?
  * Your spending patterns?
* What potential risks and harms to we want to be aware of and attempt to mitigate?

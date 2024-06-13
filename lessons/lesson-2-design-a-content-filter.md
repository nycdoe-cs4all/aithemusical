---
description: Identifying common features in different songs.
---

# 🤔 Lesson 2: Design a Content Filter

{% hint style="info" %}
### Essential Question:

How can we determine whether or not we'll like something new? (e.g., a food we've never tried, a movie we haven't seen, a song we haven't heard, etc.)
{% endhint %}



### Anchor Text(s) for this Lesson

* Slide deck
* [How Recommender Systems Work](https://www.youtube.com/watch?v=n3RKsY2H-NE\&ab\_channel=ArtoftheProblem)&#x20;

### Supporting Text(s)/ Resources for this Lesson

* student created sentence strips with song names&#x20;
* Blank chart paper at each station
* Markers

### Lesson Overview

In this lesson, students will collaborate to determine categories that best describe similarities between songs. The assumption underpinning this categorization is that a person who likes x song will likely enjoy y song that shares similar qualities or attributes. This lesson will involve a lot of moving around in the classroom and conversation as students debate how to rearrange the data into five distinct categories. The lesson wrap up uses Kapor component 6 to critically reflect on potential risks and/ or harms presented by their algorithm.&#x20;



### Nota Bene

Prior to class, ensure the classroom is set up to host five distinct stations. Hang an empty piece of chart paper on the wall by each of those stations. Use your best judgment in creating bundles of songs for each station –these bundles should not include songs that are all apparently similar (same artist, same genre, etc) but will ideally include enough similarity among a few of the songs that categories will being to emerge for students once they get into the activity.&#x20;



### Objectives

Students will be able to...

* evaluate data points to identify shared features;
* categorize data points (songs) into groups based on shared features;
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

* <mark style="color:purple;">**content filter**</mark>: uses item features to recommend other items similar to what the user likes, based on their previous actions or explicit feedback ([source](https://developers.google.com/machine-learning/recommendation/content-based/basics))
* <mark style="color:purple;">**category**</mark>: a group of people or things with particular features in common
* <mark style="color:purple;">**assumption**</mark>: a belief or feeling that something is true or that something will happen, although there is no proof
* <mark style="color:purple;">**similarity**</mark> (<mark style="color:green;">similarities</mark>): being like someone or something but not exactly the same
* <mark style="color:purple;">**outlier**</mark>: a person or thing that is different from or in a position away from others in the group; a data point on a [graph](https://www.oxfordlearnersdictionaries.com/us/definition/english/graph) or in a set of results that is very much bigger or smaller than the next nearest data point
* <mark style="color:purple;">**audit**</mark>: an official examination of the quality or standard of something

### Hook

Give students time to think, write, and talk with a partner about the following prompts:&#x20;

* Think about the songs you shared yesterday as some of your favorites. What do those songs have in common?
* Do you think that new songs that share these same qualities might appeal to you? Why or why not?
* Facilitate a class-wide discussion by asking students to share what they discussed with their partner. Try to elicit as many potential ‘categories’ as possible. Students might mention a specific artist as a category, a certain tempo or feeling created by the song. Once you have gathered at least 5 different potential categories transition to the mini-lesson.

### Mini Lesson&#x20;

Kick off the mini-lesson by asking students what they think about this statement: If I like this song, I’ll probably like this other similar song. Relate it to the categories they identified in the warm up.&#x20;

Let students know that this is the assumption that content filters are based on. Highlight the fact that when engineers use data to train algorithms, they make certain assumptions that underpin the automation process. In this case, the assumption is: if you like this song by Bad Bunny, you will like any song by Bad Bunny (or fill in whichever category is chosen). Data trained algorithms that automate recommendations by suggesting songs that are similar to ones you have liked in the past are called “content filters.” These algorithms sort through the enormous collection of possible songs and identify those that are similar to those you have listened to in the past.

Let students know that today they are going to start designing their own content filter by working with the data they compiled yesterday.

### Activity

Our task today is to sort through all the songs we generated yesterday and to place them in five different categories. For example, maybe the category is “artist”...maybe it’s “genre.” You need to figure out as a class what would make the most sense as a primary category to group different songs according to a specific shared quality or similarity.

Provide students with explicit expectations on how this activity will flow and be sure to highlight the following as well as any class specific norms that you know you will need to highlight for your specific group:

* First evaluate the songs at your table and look for any categories that you see emerging, begin sorting into those different categories. You will have 5 minutes to do this! (Each group should have approximately 15-20 songs they are working with.)&#x20;
* I will call us all back together very briefly to ask for a few groups to share some categories they see emerging. We are trying to settle on a theme for our chosen categories (by artist, by genre, etc).&#x20;
* You will then have 10 minutes to start combining groups of songs with a neighboring table / station with the ultimate goal of each station containing songs that reasonably belong to that tables identified label/ category. During this portion, you can pass songs to different stations and bring new songs to your own station! Do your best! You might have outliers!&#x20;
* I will call us all back together very briefly check in with each station, so the entire class can get a sense of what is happening at each station. At this point, we will settle on our five main labels /categories.
* You will have 8-10 minutes to write the label for your station at the top of your chart paper. Then as a group, you will begin identifying sub-categories to sort songs at your station. For example, your overarching category might be HipHop and a sub-category might be ‘break-up songs.’ The idea is to find the different qualities of the songs at your station that make those songs similar.&#x20;

Circulate as students are working and provide any nudges here and there to facilitate. As you observe, take note of anything you want to highlight in the wrap-up.&#x20;

### Wrap Up&#x20;

Check in with students and elicit some feedback from them about how this activity went. In particular, highlight the main category used at each station and invite each group to share some of the subcategories they identified.&#x20;

Remind students about the potential biases and harms that were highlighted yesterday. Were we able to do anything today to mitigate those biases? If yes, what? If no, why not?

Kapor Component 6 question regarding data:

* Remember, we are building our own music app and we want this app to be fair to all artists and listeners! Keeping that in mind and knowing that the data we have collected and grouped according to our own tastes and opinions…how can we audit our own algorithm to ensure fairness?
* What are strategies for designing for justice?&#x20;

<figure><img src="../.gitbook/assets/Screenshot 2024-05-30 at 2.12.32 PM.png" alt=""><figcaption><p>Kapor Framework </p></figcaption></figure>

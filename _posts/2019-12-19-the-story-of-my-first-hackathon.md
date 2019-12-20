---
layout: post
title: 'The story of my first hackathon | 1 hackathon : 48 hours : Immeasurable learnings'
tags: [General, Learnings, Tips]
featured_image_thumbnail: assets/images/posts/2019/hackathon-cover-thumbnail.jpg
featured_image: assets/images/posts/2019/hackathon-cover.jpg
featured: true
hidden: true
---

It's been more than 2 years since that eventful weekend, still, whenever I think of it there seems to be an adrenaline rush throughout my body. Mistakes were made, friendships were forged, knowledge was tested but most importantly, life long lessons were learned.
<!--more-->


Back in 2017, I was exploring the world of machine learning. Machine Learning, Data Science, Artificial Intelligence were fast becoming buzzwords of the industry and a natural curiosity had crept in me to understand the domain and evaluate whether it would be a good fit for me for the next few years. With the thirst for knowledge, I started taking the long route of self-learning through openly available online materials. After investing some time in it I realized I needed some guidance and didn't have anybody in my network who could help me with it. That's when I started looking for boot camps and ended up zeroing in on [Greyatom School of Data Science (GA)](https://greyatom.com/) after considering the likes of Upgrad, Great Lakes and so on. This move was about to change my life!

While going through the instructor-led offline boot camp at GA, we had a hackathon mid syllabus to test the extent of our knowledge and show us where we truly stand. Working on a fin-tech based problem statement I was very much out of my comfort zone but our team of 5 had a good mix of technical knowledge and domain expertise and together we were able to pull off a brilliant performance after spending 2 whole days at the campus. In the week after the hackathon, I had some me-time to evaluate where I stood, what went right and what could I improve for similar events in the future. I quickly started noting down my thoughts and within a few minutes I had 14 points listed. After evaluating them again I decided to share it with the peers in my cohort. I'm someone who overthinks a lot of things but decided to go ahead with it and within minutes I started getting a good amount of responses which boosted my confidence a lot. Peers in my cohort poured their thoughts too and suggested me to write a blog and share this nugget of wisdom which has been on my TODO list for a long long time!

{% include image-caption.html imageurl="assets/images/posts/2019/ga-group.jpg" 
title="WhatsApp Images" %}

<br>
Here are the points that came out of that eventful weekend:


**1) Always use version control**

I've seen a lot of people learning Data Science who aren't comfortable with version control. This is one of the most fundamental things that you should incorporate in your workflow. It's always better to have your codebase/notebooks centrally managed instead of sharing the same with each other via mail, dropbox or any other file sharing mechanism. It also becomes very easy to track changes and revert whenever needed.


**2) ‎Have sample codes for different algorithms equipped beforehand to refer when required.**

A lot of times you would be trying out various algorithms to see which one works better. While juggling with these algorithms, you may get drowned in the implementation for a long time. It helps to have sample snippets for at least the main algorithms like Naive Bayes Classifier, SVM, Decision Trees, etc.


**3) Have awesome visualization**

You need to tell the beautiful story of the dataset from being just a simple set of information/numbers to becoming a full-fledged model. Judges won't judge you just your code but also on the way you can visualize it and make it easily interpretable. The numbers in the CSV won't matter much or be useful if it isn't explained visually.


**4) Reusable Code**

Try to write functional or Object-Oriented (IMHO) code to have maximum code reusability. This is where your coding skills come into play. When you write in the different cells in your Notebook you might end up writing similar code multiple times which should be clearly avoided.
Ex: A lot of times you might need to read a CSV and convert it to a data frame multiple times. It should ideally be converted into a reusable function which not only reduces your efforts but also helps in refactoring the code in the future.


**5) End to End Pipeline**

It's advisable to build your product from end to end, no matter how much crappy it is and then build on it and improve. Your problem statement might need to use different models at different stages chained together. A lot of times people get hooked on to perfect the initial algorithms that they start losing the big picture and end up getting less time to complete the whole problem statement.


**6) Focus on additional features at the end**

At some point in the hackathon, you would have made a basic list of features required as per the problem statement. As time goes by and things start shaping up you would realize the true potential of what you are building. You would think that you could add these additional features/functionalities which may help you score some brownie points with the judges. DON'T. Focus on completing the problem statement with the basic functionalities required before you start improvising! You could note these points down and start working on them later on.


**7) Understand the team dynamics before you start**

Your team could be coming from diverse backgrounds with varying skill sets. Not everybody would be a hardcode coder. Understand what people's strengths and weaknesses are and distribute work accordingly.
Ex: We were very lucky to have two members of our team from a fin-tech background which provided us the domain expertise which we needed


**8) Keep the big guns handy!**

‎Have a contingency plan in case your model can't be processed well on your laptop. In our case, we had access to a few ML/AI optimized servers at our disposal. We had kept a trial account of IBM Watson Studio which gave access to an environment similar to Google Colab which had just launched around that time.


**9) Go beyond your syllabus**

This point was related to our boot camp but applies in general too. Go beyond what you know or learned in your program. Once you have completed a basic end to end pipeline, if your team dynamics permit, you could experiment with algorithms that you might not know much about but fits your application.


**10) Understand the need for that hackathon**

If it is a Hackathon that is targetted to develop something which will be productionized, focus on the big picture. Just because your model has the best metrics doesn't mean it'll be considered if it is computationally expensive
The best example of this is the Netflix Prize 2009 $1 Million winners whose algorithm was not used even though it had the best performance due to the complexity associated with it.


**11) Document EVERYTHING!**

Document EVERYTHING. Don't document only the code which makes the final cut for the presentation, document your failures too. It'll help you in the long run. You don't need to publicize it, keep it for internal reference. A few years down the line this shows how you have grown over the years as well as what mistakes you shouldn't repeat.
P.S: This was my way of documenting stuff. This blog post was initially nothing more than 14 points


**12) Spend time understanding the data**

Take enough time to understand and clean your data.
In this case, we had a week to explore the data and think about it, in competitions you'll have exactly 48 hours or less to get used to the data and work on it. Spending some time with data helps you understand what that data truly represents and what it lacks. Also known as EDA.


**13) Move beyond the traditional Data Visualization libraries**

Explore visualization techniques beyond matplotlib or seaborn. Check out d3.js (ex: http://www.r2d3.us/visual-intro-to-machine-learning-part-1/ ) and other libraries built on top of it.


**14) DEMO!!!!**

In my opinion, the best demo is when you don't give a demo! The most powerful demo is when you give control to the audience/judges to do it themselves! One of the things that you could do is create a web app that consumes your models and gives you results on the app itself providing a seamless and easily usable way for your end-users to consume your application. Bonus points for hosting the same on a remote server! In our case, we had Sandip Baradiya with us who has extensive experience in developing Django && React-based applications. On the last day, he quickly whipped up an application that we used during our demo.


**15) Make sense of evaluation criteria**

Know the evaluation criteria of the competition and focus on everything accordingly not just on EDA or model building. Usually, all of these steps have some points but understand the evaluation criteria well so that you can cover as much ground as possible even if you aren't able to complete your application


**16) Model reasoning**

Have reasoning ready for why you chose algorithm A over algorithm B. This is usually asked by the judges while evaluating you and also to detect plagiarism.
P.S: Your documentation helps a lot in this case.


**17) Document the performance of the model at every stage and not just code.**

Documenting metrics of each model helps you in analyzing how accurate/right your end solution is as compared to the other solutions that you had thought of.
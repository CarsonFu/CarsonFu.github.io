---
layout: essay
type: essay
title: "Ask smart, be rewarded"
# All dates must be YYYY-MM-DD format!
date: 2023-09-07
published: false
labels:
  - Questions
  - Answers
  - StackOverflow
---

<img width="300px" class="rounded float-start pe-4" src="../img/smart-questions/rtfm.png">

## Asking questions is hard

One of the most difficult things in life is to ask a question. You're taking a huge risk. Obviously, you don't know the answer. You're vulnerable: you don't want to sound stupid because you're asking a question about something you should've known. However, with maturity comes the realization that asking questions, while difficult, is essential. Michael Jordan did not come out of the womb dribbling a basketball. In the same sense, you aren't expected to just know things. The things we all know today initally stemmed from a curiosity that eventually blossomed into a question followed by an answer. The people who master the art of asking smart questions bloom more elegant answers.

## Smart questions in the context of coding

Asking smart questions is a skill that is especially important in programming, as programming problems can have many different solutions in many different situations. Oftentimes programmers take to the web to aid them when they run into issues. There they can find databases holding information on the language they are working with. They can also come across websites such as StackOverflow: a website that serves as a forum where programmers post questions to be answered by other programmers.

Here, if you want your question to be answered thoroughly, it is important to ask in a smart way. What's the smart way? The smart way consists of being clear, concise and concentrated. Your title should be clear and specific. The reader should know exactly what you are asking. Your question should be concise and to the point. The longer your question, the harder it is for the reader to follow along and can mess with its clarity. Finally, your question should be concentrated. Don't ask a question that asks another question, and another. Your question should elicit singular responses. These techniques makes your questions more effective.

In general, according to the short guide listed above, it is better to ask short, specific questions, rather than broad, open-ended ones because you can receive answers that actually answer your question. I found a good example of a smart question on StackOverflow. The person asking the question titled their post: "Create button to update in django posts with javascript fetch." https://stackoverflow.com/questions/74403118/create-button-to-update-in-django-posts-with-javascript-fetch



While the heading of his question could be better, it does convey what he’s trying to figure out. Usually something as brief as “python date of previous month” is what other users would enter in as search terms on Google, making it easily found. Another good thing about the question is that it’s not just a question. The asker shows what he or she has done and that he or she has put in some effort to answer the question. And while it may not be as important as the question itself, the asker shows courtesy, which does increase the chance of getting an answer.

```
A: datetime and the datetime.timedelta classes are your friend.

1. find today
2. use that to find the first day of this month.
3. use timedelta to backup a single day, to the last day of the previous month.
4. print the YYYYMM string you're looking for.

Like this:

 >>> import datetime
 >>> today = datetime.date.today()
 >>> first = datetime.date(day=1, month=today.month, year=today.year)
 >>> lastMonth = first - datetime.timedelta(days=1)
 >>> print lastMonth.strftime("%Y%m")
 201202
 >>>

```
 
The asker received six possible answers, and he or she was successful in inciting discussion from multiple users. The answers themselves were clear and were devoid of the rumored sarcasm and hostility of “hackers.” Since I myself have referenced this page and found it useful, I can confidently say that it is a good question.

## The foolproof way to get ignored.

While there are decent questions that benefit everyone, there are those one can ask to create an entirely different effect. In the following example, a user asks how he would, in short, create a desktop application with Facebook.

```
Q: Facebook Desktop Notifier

I am a beginner programmer that have never used anything other than what's included in a language.

I am trying to create a desktop application that notifies me anytime I get an update onfacebook. 
How should go about doing this? Thanks in advance.

edit Sorry I was not clear. Is there any way to make a DESKTOP application with facebook?
```

A simple “yes” would have answered the question, but we know that’s not the sort of answer he or she is looking for. Fortunately, someone kindly responded with a link to Facebook’s developer website. The asker should have done more research on his or her potential project. Then further down the road, he or she could have asked more specific and detailed questions that wouldn’t require a thousand-paged response for a sufficient answer.

## Conclusion

When we rely on others’ generosity and expertise to provide answers to our questions, it should hold that the question we ask should be one that leads to efficient and effective help that not only benefits us, but also the people we ask and others who might ask the same question in the future. Thus, if you have a question… make it a smart one! Asking questions may not always get you the best answer, but asking them in a way that will make others want to answer them will increase the success of finding a good solution and make it a positive experience on all sides.

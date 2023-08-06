---
layout: post
title:  The “Good Omens” in Root Cause Analysis
date:   2023-08-03 15:01:35 +0300
image:  '/images/Good-Omens-RCA-1.jpg'
tags:   [Project-Management, RCA]
---

And the Root Cause Analysis in “Good Omens.” And angels. And demons.

Comparing something as fun, magical, sweet, clever, comforting, and heartbreaking as [Good Omens](https://www.imdb.com/title/tt1869454/) with something as systematic, corporate, and potentially dull as Root Cause Analysis may seem gross. Still, I am going to do it anyway 😀. After all, isn’t [Good Omens](https://www.imdb.com/title/tt1869454/) a lesson on companionship, friendship, and love (sigh) between opposing poles? 

![img]({{site.baseurl}}/images/Good-Omens-RCA-1.jpg#center)

Ok, if you have watched [Good Omens 2](https://www.imdb.com/title/tt1869454/episodes?ref_=tt_eps_sm) already, get ready, you gorgeous thing! We start in the next paragraph! If you have not watched it yet, please stop here, introspect, assess what you are doing with your life, and do yourself a favor and watch it.

As you know, my ineffable readers, [Good Omens 2](https://www.imdb.com/title/tt1869454/episodes?ref_=tt_eps_sm) opens with naked, amnesic Gabriel “knocking” on Aziraphale’s bookstore door, announcing something terrible will happen. Aziraphale and Crowley perform a “little miracle” to hide Gabriel so they have time to figure out what is going on before heaven and hell learn where Gabriel is and make a mess out of it. Of course, all this is just an excuse to wonderfully tell Aziraphale and Crowley’s love story since the very creation of the universe. You may call it “fan service,” I call it the fabric of my mental health, hopes, and dreams.

![img]({{site.baseurl}}/images/Good-Omens-RCA-2.webp#center)

*I lied. Good Omens 2 opens with Aziraphale and pre-fall Crowley being better than fresh coffee in the morning, the aroma of clean laundry, and spontaneous forehead kisses… all together.*

# The Root Cause Analysis in “Good Omens”

Root Cause Analysis (RCA from now on) is a problem-solving technique used to identify the underlying reasons or factors that led to a specific issue or incident. If you work with engineers, you are probably familiar with it: a bug in production causes mayhem and chaos. The team fixes it, but it mustn’t happen again, so we need to find the cause and fix it from the root.

Let’s see: Gabriel and his amnesia are the problem or bug in production. Aziraphale and Crowley are the engineers fixing the bug or masking it with a Band-Aid (a 25-lazarii miracle, lol you gotta love [Gaiman](https://www.neilgaiman.com/)). I have no proof, but neither doubt that Aziraphale is a frontend engineer and Crowley is a backend one, but in any case, both of them know they still have a problem they need to fix: what happened to Gabriel, and what is the looming terrible thing that is going to happen. 

This is the thing with bugs on production and RCA: if you don’t really find the real cause of the bug and fix it, sooner or later, the stupid bug will happen again. You can’t escape from it. It is like Destiny in a horror movie or something. [Every day it gets closer, faster than a roller coaster!](https://www.youtube.com/watch?v=kLBWkM0jzK0) So the looming terrible thing that is going to happen will happen, and you don’t want to have to tell your manager, or your client, or a very angry stakeholder that the looming terrible thing that happened is the same exact looming terrible thing that had already happened, but you didn’t fix it. Just saying.

![img]({{site.baseurl}}/images/Good-Omens-RCA-4.webp#center)

*The “sorry dance” will live forever rent-free in my head.* 

# RCA techniques

There are many [RCA techniques](https://www.6sigma.us/etc/what-are-common-root-cause-analysis-rca-tools/). The one that I like the most and is, IMHO, the easiest to apply is the 5 Why’s, which involves asking "why" multiple times, usually 5 (or 7 if you are god, haha), to identify the cause of an issue by progressively delving deeper into its underlying factors. You keep digging and digging until you get to the bottom by asking “why” repeatedly. In the process, you are going to find multiple causes. Focus on the deepest one, but don’t ignore the others. Work with your team to prioritize them.

In [Good Omens 2](https://www.imdb.com/title/tt1869454/episodes?ref_=tt_eps_sm), they end up “fixing” multiple problems: restore Gabriel’s memories, send Gabriel and Beelzebub to Alpha Centauri to live happily ever after, and avoid armageddon! If you think about it, they shouldn’t have had to prevent armageddon in season 2 if they had adequately gotten to the root cause of why armageddon after season 1, but then again, had they done that, season 2 wouldn’t exist, so I won’t complain 🙂.

It doesn’t escape me that Aziraphel doesn’t do the 5 Why’s thingy. Still, the curiosity and even persistence that takes him from a vague tune to an actual song and then to a pub in Edinburgh is applicable when you do the 5 Why’s. Think about it as a very cool mystery you need to solve!

![img]({{site.baseurl}}/images/Good-Omens-RCA-6.webp#center)

*Can we talk about Crowley’s bitch walk? And yeah, I know none of the pics today have anything to do with the text. My newsletter, my rules.*

All right, sweet Aziraphel doesn’t make much progress beyond Edinburgh, though. Crowley’s actions show way more effective, and that is because when doing RCA…

# Data is your friend!

Data gives you proof, can help you learn when the problem started, and may tell you how significant the impact is. The thing with data gathering is that you need to have your recording in place before the accident or bug manifests so that you can go to the logs and analyze the data after the fact. It has happened to me that during an RCA, we learned that we didn’t have logs, so we couldn’t get to the root cause of the bug. What did we do? We added some logging, monitored it, and then, days later, we could detect the problem before it had catastrophic consequences (again). 

So Crowley heads up to heaven, manages to access the records (Throne, Dominion, or above 🤔), and learns why Gabriel ran away. Yay, data! 

As the plot thickens, they end up in the bookstore with the classic end-of-mystery-movie scene where all parties get the puzzle pieces that solve Gabriel’s [MacGuffin](https://en.wikipedia.org/wiki/MacGuffin) plot. Yay, RCA! And yay, no armageddon!

Oh! One important thing when you do RCA: you will uncover problems that you can fix within your team, other issues will require a partnership with other teams, and some problems will be so systemic and structural (like, the armageddon, lol) that you will need leadership involvement. Don’t be afraid to escalate (follow your company’s process). Leadership’s job is basically to help solve these problems.

![img]({{site.baseurl}}/images/Good-Omens-RCA-7.webp#center)

*Seriously, I can’t.* 

So I hope I have not slaughtered one of the most heartwarming and heartbreaking love stories since [Our Flag Means Death](https://www.imdb.com/title/tt11000902/). I did it out of my deepest attachment to Aziraphel and Crowley, and my profound respect for the goodness in RCA. I already mentioned that Gabriel and armageddon is not really what the season is about. [Good Omens 2](https://www.imdb.com/title/tt1869454/episodes?ref_=tt_eps_sm) explores how a demon and an angel are platonic friends, companions, and lovers. And like in RCA, we need to go deep into the roots to understand that relationship. I also mentioned that RCA may be boring. Let’s make it not, now. When we do RCA, let's imagine that we are exploring the depths of something gorgeous and potentially discovering the most adorable mischief in the process. 

![img]({{site.baseurl}}/images/Good-Omens-RCA-8.webp#center)

I leave you, my beautiful ones, hoping we will eventually [hear nightingales](https://www.youtube.com/watch?v=qChVFvnTEbY) and an article that goes through the pop culture references in Good Omens 2: [All the Tasty Little Easter Eggs in Good Omens’ Season 2](https://www.themarysue.com/all-good-omens-season-2-easter-eggs-explained/). Enjoy!

------

*Do you want to receive posts like this one in your inbox every week?  [<u>Subscribe to my newsletter!</u>](https://popcultureguidetopm.substack.com/)!* 
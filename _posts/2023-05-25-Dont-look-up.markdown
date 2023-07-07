---
layout: post
title:  Look up! Your technical debt is coming to kill you!
date:   2023-05-25 15:01:35 +0300
image:  '/images/dontlookup01a.jpg'
tags:   [Project-Management,Technical-Debt]
---

![img]({{site.baseurl}}/images/dontlookup01a.jpg#center)

# The movie: Don’t Look Up

Spoilers ahead! [Don't Look Up](https://www.imdb.com/title/tt11286314/) is a satirical comedy that follows Dr. Kate Dibiasky (Jennifer Lawrence) and Dr. Randall Mindy (Leonardo DiCaprio) after they discover a comet that is hurtling toward Earth with a 100% chance of causing global destruction. Dr. Dibiasky & Dr. Mindy embark on a mission to alert the world about the impending disaster. However, they only get skepticism, disbelief, and apathy from a world obsessed with shiny and stupid distractions.

Here, the comet can be seen as climate change. Dr. Dibiasky & Dr. Mindy represent the scientific community that has been sounding the alarm for years, and the word population… well, the world population represents the world population.

We have three more players: President Janie Orlean (Meryl Streep), more concerned with her image and re-election than the impending doom; Brie Evantee (Cate Blanchett), an influential television anchor with a self-serving agenda; and Peter Isherwell (Mark Rylance), a creepy and eccentric tech mogul (do I really need to say who is he a parody of?) who seeks to capitalize on the disaster rather than prevent it. 

The film is basically a tale about the dangers of willful ignorance and the consequences of prioritizing short-term personal gain over sustainability and the greater good. **And if you haven’t been building parallelisms with tech deb already, I’ll just say that: a. Ignoring it will kill your product, and b. The root cause of tech debt is normally the need to go fast at the expense of long-term maintainability.**

So let’s talk a bit about technical debt now.

# Technical Debt

Ward Cunningham (one of the authors of the Agile Manifesto) compared some tech problems with financial debt, coining the term ***Technical Debt***. [You can watch the video here](https://www.youtube.com/watch?v=pqeJFYwnkjE), but the gist is that you can borrow money to do something sooner, but then you have to pay back the money plus interest. **When we talk code, you can rush software to deliver value faster, but you must go back and refactor. Otherwise, you’ll pay interest in the form of slower delivery,** bugs, constant troubleshooting and band-aids, customer unhappiness, etc. It does have the potential to destroy your product.

# The root cause

In the movie, the root cause of all the drama is a comet that comes out of nowhere. Instead of focusing on saving Earth, world leaders prefer to profit from the comet. In real life, the root cause of tech debt (or climate change, actually) would be **seeking immediate results to get a benefit while ignoring long-term maintainability**. This is not an exhaustive list, but some examples come to mind:

- When we rush engineers because we need the feature out there, and they need to do ugly things to deliver it, and once the feature is out, we ask them to move to the next shiny thing immediately instead of refactoring the code.
- When we ask engineers to build a prototype, and they work on a quick thing because they are learning, and of course, the plan is that the actual product will be developed later, applying all the learnings and all, but oh, surprise! We decide just to ship the prototype because YOLO.
- Continually outsourcing your engineering teams and not taking the time to mentor them, coach them, and build teams of missionaries instead of mercenaries ([channeling my inner Marty Cagan here](https://www.svpg.com/missionaries-vs-mercenaries/)), creating a culture of *the next guy will deal with this sh\*t* without optimizing decisions for the long term.

Before we move on, as I talked about delivering fast and prototyping, I feel the moral obligation to insist that **Agile is about delivering sooner, learning, and getting feedback, not delivering fast at the expense of long-term feasibility**.

# It is easy to ignore tech debt when you can’t see it

![img]({{site.baseurl}}/images/dontlookup02.jpg#center)

Like President Orlean (and the media, and the public in general), folks prefer to ignore a threat they can’t see. When Dr. Dibiasky & Dr. Mindy tell the world there’s a comet coming that will kill everyone, they are accused of being overdramatic.

**Your peers and your executives may need help understanding the threat of tech debt and the need to take action**. The sooner, the better. In the movie, the journalists and President Orlean’s team dismiss the scientists that are really struggling to get their message through. Luckily, I am inclined to think most real-life executives are not like President Orlean and Bree Evantee. If your executives are, I would suggest you start updating your resume.

If you have decent, competent leadership, **it is your job to become Dr. Dibiasky & Dr. Mindy and evangelize** why it is a good idea to stop building new value for a bit and go back to the code to ensure it will live long and prosper. You should be able to arm yourself with data: how much time are the teams spending on bug fixing? How long does it take to troubleshoot issues on production? How frequently are you forced to apply an emergency band-aid? **How are all these activities preventing the teams from building the new sexy features the executives want?**

You can return to the metaphor of maxed-out credit cards and how you go bankrupt if you have too much debt. Your executives will surely understand that. 

I will not force the Don’t Look up-Technical Debt metaphor beyond this point. Just one more thing before I finish.

# When you can see the threat, but you actively ignore it

In the movie, when President Orlean’s team confirms with their big-shot ivy-leaguers corporate scientists that there’s indeed a comet coming to destroy Earth, they actually apologize to Dr. Dibiasky & Dr. Mindy and start a pretty cool action plan to save the planet. However, at the very last moment, Peter Isherwell (the tech mogul) makes an entrance and stops the action plan. They are basically not going to save Earth because the rock coming to destroy them is a giant, very expensive piece of gold, diamonds, vibranium, or whatever. Lol, you gotta laugh.

Has it ever happened to you that you finally get your leadership on board so that you can stop rushing feature after feature and take some time to make things right but then a very powerful and high-maintenance stakeholder or client comes in and demands their feature, and you get the mandate to deliver as fast as you can no matter what, again?

Well, it has definitely happened to me, and yeah, Isherwell vibes here.

![img]({{site.baseurl}}/images/dontlookup03.png#center)

I don’t have to say that the consequences of this will be frustration, attrition, and yes, don’t forget the destruction of Earth, I mean the product, haha.

# In a nutshell

Best case scenario, excessive tech debt will affect time-to-market. Worst case scenario, you have an earth-killer rock destroying your product. Ignoring it, acting as if it doesn’t exist, or lying to your team and leadership won’t make it better. So please, do look up. Look everywhere!

But hey! The good news is that fixing technical debt is way easier than fixing climate change!

------

*Do you want to receive posts like this one in your inbox every week?  [<u>Subscribe to my newsletter!</u>](https://popcultureguidetopm.substack.com/)!* 
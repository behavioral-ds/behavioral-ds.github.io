---
title: "Some Reddit users just love to disagree, new AI-powered troll-spotting algorithm finds"
authors:
  - Lanqin Yuan
date: "2025-05-09"
output: html_document
tags: []
categories: [Research, blogpost]
image:
  placement: 1
  focal_point: "Center"
  preview_only: true
summary: "Our article from the [The Conversation](https://theconversation.com/some-reddit-users-just-love-to-disagree-new-ai-powered-troll-spotting-algorithm-finds-255879) from our paper presented at WWW'25."

---
This is a repost of our article from [The Conversation](https://theconversation.com/some-reddit-users-just-love-to-disagree-new-ai-powered-troll-spotting-algorithm-finds-255879).

**Paper citation:**
```
Lanqin Yuan, Philipp J. Schneider, and Marian-Andrei Rizoiu. 2025. Behavioral Homophily in Social Media via Inverse Reinforcement Learning: A Reddit Case Study. In Proceedings of the ACM on Web Conference 2025 (WWW '25). Association for Computing Machinery, New York, NY, USA, 576–589. https://doi.org/10.1145/3696410.3714618
```
(_see full paper here: [https://dl.acm.org/doi/pdf/10.1145/3696410.3714618](https://dl.acm.org/doi/pdf/10.1145/3696410.3714618)_)

In today’s fractured online landscape, it is harder than ever to identify harmful actors such as trolls and misinformation spreaders.

Often, efforts to spot malicious accounts focus on analysing what they say. However, our latest research suggests we should be paying more attention to what they do – and how they do it.

We have developed a way to identify potentially harmful online actors based solely on their behavioural patterns – the way they interact with others – rather than the content they share. We presented our results at the recent ACM Web Conference, and were awarded Best Paper.
Beyond looking at what people say

Traditional approaches to spotting problematic online behaviour typically rely on two methods. One is to examine content (what people are saying). The other is to analyse network connections (who follows whom).

These methods have limitations.

Users can circumvent content analysis. They may code their language carefully, or share misleading information without using obvious trigger words. 


## Beyond looking at what people say

Traditional approaches to spotting problematic online behaviour typically rely on two methods. One is to examine content (what people are saying). The other is to analyse network connections (who follows whom).

These methods have limitations.

Users can circumvent content analysis. They may code their language carefully, or share misleading information without using obvious trigger words. 

Network analysis falls short on platforms such as Reddit. Here, connections between users aren’t explicit. Communities are organised around topics rather than social relationships.

We wanted to find a way to identify harmful actors that couldn’t be easily gamed. We realised we could, focusing on behaviour – how people interact, rather than what they say.

## Teaching AI to understand human behaviour online

Our approach uses a technique called inverse reinforcement learning. This is a method typically used to understand human decision-making in fields such as autonomous driving or game theory.

We adapted this technology to analyse how users behave on social media platforms.

The system works by observing a user’s actions, such as creating new threads, posting comments and replying to others. From those actions it infers the underlying strategy or “policy” that drives their behaviour.

In our Reddit case study, we analysed 5.9 million interactions over six years. We identified five distinct behavioural personas, including one particularly notable group – “disagreers”.

## Meet the ‘disagreers’

Perhaps our most striking result was finding an entire class of Reddit users whose primary purpose seems to be to disagree with others. These users specifically seek out opportunities to post contradictory comments, especially in response to disagreement, and then move on without waiting for replies.

The “disagreers” were most common in politically-focused subreddits (forums focused on particular topics) such as r/news, r/worldnews, and r/politics. Interestingly, they were much less common in the now-banned pro-Trump forum r/The_Donald despite its political focus.

This pattern reveals how behavioural analysis can uncover dynamics that content analysis might miss. In r/The_Donald, users tended to agree with each other while directing hostility toward outside targets. This dynamic may explain why traditional content moderation has struggled to address problems in such communities.

## Soccer fans and gamers

Our research also revealed unexpected connections. Users discussing completely different topics sometimes displayed remarkably similar behavioural patterns.

We found striking similarities between users discussing soccer (on r/soccer) and e-sports (on r/leagueoflegends).

This similarity emerges from the fundamental nature of both communities. Soccer and e-sports fans engage in parallel ways: they passionately support specific teams, follow matches with intense interest, participate in heated discussions about strategies and player performances, celebrate victories, and dissect defeats. 

Both communities foster strong tribal identities. Users defend their favoured teams while critiquing rivals.

Whether debating Premier League tactics or League of Legends champions, the underlying interaction patterns – the timing, sequence and emotional tone of responses – remain consistent across these topically distinct communities.

This challenges conventional wisdom about online polarisation. While echo chambers are often blamed for increasing division, our research suggests behavioural patterns can transcend topical boundaries. Users may be divided more by how they interact than what they discuss.

## Beyond troll detection

The implications of this research extend well beyond academic interest. Platform moderators could use behavioural patterns to identify potentially problematic users before they’ve posted large volumes of harmful content.

Unlike content moderation, behavioural analysis does not depend on understanding language. It is hard to evade, since changing one’s behavioural patterns requires more effort than adjusting language.

The approach could also help design more effective strategies to counter misinformation. Rather than focusing solely on the content, we can design systems that encourage more constructive engagement patterns.

For social media users, this research offers a reminder that how we engage online – not just what we say – shapes our digital identity and influences others.

As online spaces continue to grapple with manipulation, harassment and polarisation, approaches that consider behavioural patterns alongside content analysis may offer more effective solutions for fostering healthier online communities.




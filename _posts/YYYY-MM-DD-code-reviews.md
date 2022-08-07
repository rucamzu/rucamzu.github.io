---
layout: post
title: "Code reviews"
date: 
categories: 
---

- Why this post?
    - Motivation: discussion in HN that triggered introspection
    - Optional: current circumstances as more frequently reviewer than author
- Why code reviews?
    - Traditional: code reviews as a defect detection gate
    - Different angle: code reviews as a feedback from reviewer to author
    - What's the difference? Defects are meant to be fixed, feedback is meant to help and be leveraged
- Hot take: any and all feedback is up for discussion and challenge
- Phrasing comments
    - No error messages
    - No commit messages
    - No imperatives
    - Questions
    - Inclusion: _We_ vs _You_
- Code reviews as an educational platform
    - Ubiquitous language
    - Connecting feedback to programming principles 
    - Links
    - Snippets
    - FYIs: refactorings, idioms, patterns
- Final thoughts
    - Do as you'd like to be done

A conversation in [Hacker News][hacker-news-hostile-code-reviews] around hostility in code reviews got me thinking about the techniques I employ to foster constructive reviews and leverage them as an educational platform. 

Code reviews are usually leveraged as a gate to detect defects in the code before it gets merged. While defects are indeed detected, 

> First and foremost, I like to think that as a reviewer I'm there not to point out issues but to provide useful feedback to the author. I'm not a compiler, therefore I shouldn't behave like one and dump error messages in the PR. Even if there are errors indeed.

> Any and all feedback I provide is up for discussion. This is something I always like to highlight when I'm about to review someone else's code for the first time, no matter their level or experience. I'd rather have my comments discussed and challenged than taken for granted as issues that automatically need to be addressed. I might even throw in the occassional curve ball that I know needs challenging :)

> I firmly believe the way I word my comments matters, and matters a lot - and I like to think I've managed to improve a bit over the years. PR comments are not commit messages. I avoid imperatives and quite often phrase comments as questions instead. Also, I favor using "we" as opposed to "you" ; in the end, what gets merged is the result not only of the author's but the whole team's work.

> Also, I try to leverage PRs to educate when possible. I frequently include FYI comments illustrating e.g. more idiomatic implementations, potential refactorings or applications of design patterns, not as something I expect the author to fix but to learn from. Code snippets and links to e.g. documentation pages or articles are great ways of enriching a comment and providing guidance beyond the PR itself.

> Finally, all these are things that I love to see when someone is reviewing my own PRs. 

[hacker-news-hostile-code-reviews]: https://news.ycombinator.com/item?id=32363230
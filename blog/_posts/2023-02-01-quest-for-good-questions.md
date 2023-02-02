---
layout: post
title: "The Quest for a Good Interview Question Bank"
date: 2023-02-01
categories: blog
---
I’m on the hiring panel for my company, and we’re looking to hire backend engineers of various levels. A topic of discussion has been to revisit the question bank we’ve used in the past. Are they good questions? What makes a question “good?”

I set out to find more questions for our bank and realized some of the problems I worked through didn’t fit the bill for various reasons. I had to quantify what I consider a good question.

For problem solving / pairing style questions, I came out with the following:

- No time sinks. This is where a candidate spends in inordinate amount of time tediously manipulating data required for the problem.
- Not a word problem and shouldn’t assume candidate’s life knowledge OR the concept should be easy to explain in under 5 minutes.
- Does not require knowledge of a specific algorithm to solve
- Can be expanded in at least one or two ways, ideally more
- As much as possible, mirrors code a candidate would be expected to read or write on the job
- Can be solved multiple ways

This is a tall order, surprisingly. Another piece of criteria to consider is the prevalence of the problem existing on the internet. I haven’t decided how that criteria should factor into questions. A good question is extensible, so maybe it’s okay if the base of the question is known, as long as the actual problem statement is varied enough that the candidate is unlikely to have seen or worked through the whole solution.

Maybe even if the question is not super extensible, a question that allows you to ask the question to talk through pros/cons of their approach is also okay. A candidate who memorizes a solution will likely struggle to explain why choices were made, or other approaches they could’ve taken.

I spent a few hours looking for and solving a handful of questions I found on the internet. Most of them didn’t pass the “good question” criteria by at least one thing. One of the questions did make me think of something else though: the value in having a question that starts with non-trivial existing code. Engineers spend significantly more time reading code than writing it, so problems that require a candidate to understand the existing codebase can be interesting!

One of the problems I found was very straight forward to implement, but along the way, I wrote a bunch of tests to validate my code. Maybe there was value in this problem as one where we give the candidate the full working code and ask the candidate to write tests. Writing tests is super valuable and often undervalued.

I’m still on this journey, so I don’t really have a conclusion here. Maybe I’m overthinking this problem. The fact that the industry has no standardization for interviewing makes me think I’m not, though. Maybe by putting effort into finding what makes a good problem and creating some that fit that criteria, I can help with that standardization, at least within my current company.

---
title: "An Interesting Question: Quality and Speed, Can We Have Both?"
date: 2020-01-05T15:11:26+07:00
draft: false
---

In software engineering, there's common knowledge that probrably got cited the most times:

> *"Everything is a trade-off."*

And commonly enough, **quality** and **speed** are probably the most infamous software trade-offs of all time. **But is it though?**

One evening, during dinner with my friends, one of my friends opened an interesting question: can we achieve both quality and speed?

Actually, I got asked this kind of question before, though more specific: why won't we use Rails, isn't it faster? (he asked in terms of software development speed). That got me into thinking, like really hard-thinking, why I chose Golang for building my company?

For me, at the time of language choosing, it was obvious to me that we got really low amount of time for software building (especially when it is financial software), and the team I had back there is almost composed entirely of new grads, so the choice was obvious: the fastest language to learn with the lowest amount of traps and good enough productivity. Is Rails a choice? not really. Learning Rails at the time would eat up 3/4 of the time we had *at best*.

So does Golang have both Quality and Speed? Well, for one thing, it is faster in terms of development time compared to most of the statically-typed languages ***at first***. And is good enough to extend beyond basic constructs, have a very low amount of traps, good enough ecosystems (open-sourced libs, frameworks, etc.) to cover almost all the things we need.

So it's kind of good enough for everything. But in this world, is good enough good enough? I personally think good enough is fine **but** we should strive for the best, should we can.

So basically I have two concepts competing,

1. Do something that will cause Golang to have both quality and speed
2. Use other language and maybe a framework

Choice 2 is obvious, my role of a CTO should always be looking for the best tech option for the company. Though I'm kind of stuck in the process, nothing really strikes me as the best option. Meanwhile, for choice 1, we can start ***now***. I don't even have to do it myself, I already got a team full of competency and enough experience of Golang in production.

We can start fixing one thing from choice 1 at a time. One thing that's certain is writing Golang usually means writing a lot of boilerplates, especially if we want quality in Golang, that's a lot of code. It is nice to have code sharing with safety like generics or hygienic macros like in some other languages. But currently, we do not have, and I don't think Golang 2 will come soon. Right now I'm experimenting something. We do have `go generate` and basic practice to always generate when running `go build` or `go run` and also good enough reflection support. I will use these basic constructs to solve this problem. I really think I can solve it but we will see.

(None of the above will work since Golang does not have advanced type supports, so everything will be at risk if we use too much reflection, this requires good enough testing, but testing involves a lot of boilerplates too, so eventually I will also tackle this aspect. For now, one thing at a time).

In conclusion, I think we **can** achieve both quality and speed. I just need a proof.

PS. I talked a lot of "language choice" or "language improvement" in this post, but these are just some of the things that can probably make us achieve both quality and speed, another important if not more important thing is development process obviously

---
title: "Why I Love Golang"
date: 2018-06-02T09:59:56+07:00
draft: false
---

Well, my true love is actually Ruby but I will talk about Golang here. It's also not like real relationship: you can love multiple languages (yet again you may have just really one true love &mdash; as in real relationship).

# Why Golang?

First off, let me just say that most of this content is drawn from my experience. I started programming really early in my life and I have been through many many programming languages since when I was 11 years old.

I have been through more than 30 programming languages. 80% of them I have read at least 1 of their textbooks and many many of their related blog posts. Ruby and Node.js is probably the top languages I heavily invested my time in (more than 6 books each, more than 40 blog posts/videos each, more than 2 years of real world works).

Note that there's no bragging here because, you know, it's kind of a shame that even I started long before anyone else and also with a lot of efforts, I still have no meaningful work yet.

**Golang just kind of the do-it language.**

In other languages I was almost lost in their features. I was so focused on doing things beautifully, rightfully, correctly, concisely and whatever instead of finish the work and do what's really 'meaningful' or 'impactful'.

I can say with confident that I have at least 30x knowledge of Node.js than most of developers in Thailand. Yet I couldn't do any meaningful work in it, yet.

Like I said, instead of focusing on the work itself I focused on something else.

**Golang brings what important in front of you**. Because you can't focus on something else instead of work. You just can't because it won't even let you.

## What about Golang 2

If Golang is so good why it needs improvement? Golang started in 2009. It already corrects what other languages do wrong (well, other languages was like 30 years invented before it). It has many programming language experts and many years of Google developer experience backed (though for PL experts it is arguably less than Rust). It's practical because some of the very best programs are already written in it (Docker, Kubernetes, Etcd, Geth, Syncthing, Hashicorp's etc.).

But, people learn. It might not be an explosion like in Node.js community, but, people learn. Steadily but correctly.

We have an upcoming package versioning and no, if you are thinking that other languages have solved this, like Ruby, Node.js, Rust, you're thinking it wrong, this is not a solved problem, those have their own flaws, and the Go team have enough courage to try to solve that with `vgo`. We will see though as author of `dep` againsts some of its ideas. Though as for now I'm already happy with `dep`.

We also have generics and error handling improvement proposals.

But before we're going to those features, let me just say 99.9999999999% of my code doesn't need generics and my 6 years of C# experience I would say generics is probably one of the most hard to use correctly features. If we're doing it wrong it introduces all kind of problems as in classical inheritance.

And for those who really needs generics you can use `interface`, type assertions, reflections, and much better choice IMHO: `go generate`. if you can learn and correctly use generics you can learn `generate` (and also there are a lot of generics generators out there, if you will).

And let me just say all of the languages I've learned and used, despite its criticisms, Golang probably has one the best error handling mechanism out there (though I will admit that Rust has much better error handling mechanism). But certainly it can be improved and I will be happy to see that.

## Get back to the reasons on why I love

This is the normal workflow I have with Node.js:

1. Think about problem
2. Think about how to write this beautifully and maintainably in Node.js
3. Think about how I will test it (at some point I stuck in this loop, I had like 30+ ways of doing this)
4. Do it
6. Go back to step 2, and solve the same problem again, with new way of approach
7. Finally if I can break out of step 6, it's done! But hold on ... maybe... maybe I need TypeScript, maybe I need Flow, maybe... I might want to split this into 10 packages, maybe...

This is the normal workflow I have with Golang:

1. Think about problem
2. Think about how to write this maintainably
3. Think about how to test it
4. Solve the problem
5. Done

I think without much saying, you can see why I love it.

## Last but not least

I want to say that, as much as I love Golang, this is from only my point of view. Because by my nature I'm more like an entrepreneur than a developer. I just want my task to be done and has an impact than having my task to be done in the best way but have next to nothing impact.

And maybe because I've been through many languages and maybe I'm already tired of it, I might just want something I can settle on.

So, last advice, I think you should try as many languages as you can, including Golang (as much as I love Golang, I would say that every person has different taste &mdash; even in my case my true love is actually Ruby).

Thanks for reading as always :) I would appreciate for any comments.

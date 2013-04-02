---
layout: post
title: Check you're wearing trousers first
---
It’s easy, fun, and a catastrophic mistake to over-intellectualise. Unfortunately it also pays pretty well.

I once read that Facebook’s onboarding process was almost entirely geared towards getting you to add 10 friends. They had found that this was the magic point at which your graph started to get interesting, and that once you had reached it you were well and truly an active user. I thought this was awesome. At the time I was working at a company where we had a healthy stream of traffic and signups, but very few people were returning more than a couple of times. I put on my data slicing and visualisation genius hat and set off in search of a similarly sublime and elegant explanation that would both help us plug our leaky bucket and earn me my place in startup scripture for decades to come.

However, like most of my first dates, the process was confusing, difficult and didn’t get me anywhere useful. It's only with my advancing years that I see the obvious truth: users were simply fundamentally confused about many simple aspects of the site. It would have taken a few hours of user testing to identify the worst of these problems, and maybe a day to fix a good chunk of the simplest of them. Instead I spent several weeks calculating r-squared values and improved exactly nothing.

I did slightly better on an e-commerce site I later worked on. The stories of sites that multiplied their sales by a factor of a bajillion by getting their buy button just the right shade of white were just as enticing as the Facebook tipping point discovery, and I was itching to emulate them. But this time I saw that the site had plenty of far simpler and more obvious failings than a slightly mis-hued button, and to my credit I resisted the temptation to get out my multi-armed-bandit split-testing t-shirt. To my equal if not greater discredit I also resisted the far smaller temptation to fix many of the boring and obvious things that were wrong with the site, but I still count this as a partial victory.

I'm currently working on speeding up <a href="http://www.copyin.com" target="_blank" id="copyin-link-in-trousers-post">Copyin.com</a>. Enthused by exciting talk of Rails 4, my first inclination was to immediately start getting dirty with cache digests and Russian-dolls. Fortunately, before things got too out of hand the rest of the team rudely and kindly dragged me back to reality by pointing out that we had several partials making 20 database calls where 1 would do, and that simply switching from Thin to Unicorn would give us substantial speedup practically for free. A few easy changes and a marked speed improvement later I admitted that perhaps we didn't need to go quite that far just yet.

Anecdotally it seems that when companies bring in management consultants to save them money, they expect clever things to happen. They anticipate an amortisation of 5 year debt into chunk sized collateral and a restructuring of divisional labour into synergistic working groups. Just as anecdotally it seems that what actually happens is that the consultants come in wearing nice ties and take a few weeks and several tens of thousands of pounds to conclude "STOP SPENDING SO MUCH MONEY ON HELICOPTERS AND MANAGEMENT CONSULTANTS." Do that, then we can talk about multiplexing your core competencies across a trans-global knowledge network if we still need to.

It's a pleasant delusion to believe that all our problems require hard solutions. This way we feel interesting, get to do challenging things and become more attractive to members of our preferred sex. If you're constantly feeling tired it's tempting to become concerned about your iron levels, consider painting your ceiling a relaxing shade of ochre and look into buying a new pillow that fits your personality better. But you probably just need to go to bed a bit earlier. Perhaps on some level of consciousness we find it hard to believe that anything simple could possibly make a dent in our problems, which as we already know are of course really difficult and can only be solved by a super-genius such as ourselves. But there will always be simple things you are doing badly that you should look at first, especially in a startup where you deliberately ignore 90% of things so that you can do the other 10% really, really right.

Simple solutions are almost always quickest, easiest and most effective. Maybe sometimes it does turn out that they aren't enough and you do in fact need to do something hard. But if people in the street keep giving you funny looks, make sure you're wearing trousers before you start worrying about what colour they are.

-----

<a href="https://news.ycombinator.com/item?id=5478893" target="_blank">Discussion on Hacker News</a>
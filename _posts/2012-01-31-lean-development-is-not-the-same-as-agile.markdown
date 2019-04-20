---
layout: post
title: Lean development is not the same as Agile
date: 2012-01-31
author: Paul Grayson
summary: "Management is about communication. Lean development is a conversation with the end-user,
agile is a conversation with the internal 'customer'."
---
Agile project management techniques recognise that software project management is mostly about
communication between the ‘client’ and ‘development team’. Lean techniques instead focus on
determining as quickly as possible what adds value and what does not. My experience is that lean
techniques recognise that value is added most quickly by increasing ‘communication’ with the end
user. This communication is rarely explicit. Lean techniques emphasise implicit communication
through observed usage, metrics and comparative split tests – real data quickly trumps opinion.
Lean accelerates learning, minimising work in progress and the cost of learning what really adds
value.

##Agile improves on Waterfall

Agile project management techniques recognise that software project management is mostly about
communication. Older techniques such as the
[Waterfall process](http://en.wikipedia.org/wiki/Waterfall_model) spent too much time attempting to
capture and formalize what the client actually wanted. Often vast amounts of time and money would
be spent writing and agreeing abstract specifications which invariably turned out not to
accurately reflect what the client envisaged. The creation of these abstract specifications did
not identify and predict the technical difficulties the project would face and the magnitude of
problems. Many of you will have seen the
[Tree Swing Cartoon about requirements](http://www.businessballs.com/treeswing.htm).

Agile techniques address these issues by emphasising communication between the development team
and their client throughout the project; accepting that it is very hard to determine exactly what
a client wants without delivering designs and working software. Clients will change their minds
as they see how in reality the things they envisaged actually work. Developers will discover that
some features they thought would be simple to implement are not so simple. Both party’s
understanding of the facts on the ground improve vastly as they make progress. They both accept
that they need a dialogue. Both parties accept that it is sensible to make changes to the project
“plan” as it progresses to completion and delivery.

Agile addresses the communication gap between developer and client. The dialogue leads to sensible
decisions, better use of resources (productivity) and greater predictability. Agile techniques
means software development increasingly does a better job of meeting the expectations of its
clients. However, often there is another very important person who’s been left out of the
conversation, the end-user (e.g. the customer on an e-commerce site). Agile is still relying on
the client’s ability to determine what the end-user wants and what works.

The development team can help with this process (that’s product development team, including
product management, UX and developers). UX people often use usability testing techniques to
gather opinion and identify problems with designs. These are really useful and valuable,
identifying some problems, encouraging best practices and avoiding opinion deadlock.
Unfortunately they are highly artificial, the few users in their tests are often not actual
customers, with an actual need, using their own time and money.

If used correctly usability testing techniques can smooth the edges of a design, making it flow
better and making it easier to use. However, they are based on small sample sizes, often gathered
from the same geographical source and demographic. They often miss the nuances of other
demographics and of how people actually behave when it’s their own money they’re spending. For
example, I’ve seen data that showed 6% of UK customers attempting to use just their house number
and postcode to specify their address, on many sites that is insufficient. What are the chances
that this 6%’s actual behaviour would be picked up in a artificial usability test – unfortunately
it is not high.

There is a new kid on the block which aims to address this gap and bring the 3rd and most
important party in on the conversation – the end user, in HD and in all their magnificent glory,
warts and all. The new kid is Lean Development.

##Lean

In October (2011) Eric Ries’ best selling book,
[“The Lean Startup: How Constant Innovation Creates Radically Successful Businesses”](http://www.amazon.co.uk/Lean-Startup-Innovation-Successful-Businesses/dp/0670921602/ref=sr_1_1?ie=UTF8&qid=1328015656&sr=8-1)
(which I thoroughly recommend by the way) was released to critical acclaim and quickly became a
New York Times Bestseller. Eric’s book focuses more on
startups and product development rather than specifically software development per-say. The main
theme it shares with Lean Software Development is this gap between what the experts in a business
think about a product or service and the reality of what the end-user/customer values and how they
use it.

The lean approach borrows its name from [Lean Manufacturing](http://en.wikipedia.org/wiki/Lean_manufacturing)
techniques such as the [Toyota Production System](http://en.wikipedia.org/wiki/Toyota_Production_System).
Lean manufacturing works on the basis that parts are pulled through the
manufacturing process as they are needed, work in progress is kept to a minimum. This makes the
manufacturing process highly reactive to customer demand and able to cope with day to day
manufacturing problems whilst maximising throughput. If orders for a product increase, more of its
parts are pulled through the manufacturing system. If there is a problem with manufacturing of a
part upstream, then it temporarily stops pulling the parts it depends upon up through the
manufacturing process.

In software development we’re not talking about manufacturing but product development, the
process of determining what features a product or service should have, how it should work and
making the feature available. Our goal is to build things that users value, that help them
achieve their goals. For example, in ecommerce that’s finding a site, finding the product they
want and successfully purchasing the product.

Lean development recognises that experts are making calculated guesses about what problems a user
has, what they will value and how they use a feature. There is nothing wrong with this. We need
to start somewhere and an expert’s guess is a very good place to start and with no information to
the contrary it’s also a good next move. However, it is a bet, we are betting that the expert is
correct. Lean development aims to reduce our exposure to this bet by reducing work in progress to
a bare minimum.

Using a lean process, each new release of the software contains the bare minimum additions/changes
needed to test the experts assumptions. We determine what the user thinks through observing how
they behave, collecting data through analytics and analysing our own databases and software logs.
This [Minimum Viable Product](http://en.wikipedia.org/wiki/Minimum_viable_product) (MVP) or feature (MVF) is the least work we can do, the least money
we can spend to test the expert’s hypothesis, to learn more and plan our next step.

This leanness, this minimization of work in progress is key. The emphasis is build something
quickly, try it, look at data and feedback, improve – quickly, repeat. Lean is real and fact based,
it implicitly involves the end-user, it makes them a key part of the product development
conversation. The user drives the development process, implicitly prioritizing and “pulling” the
new features or tweaks that they want through the development process.

Agile processes have plenty of regular conversation with the client, including regular
demonstration of progress. When using an agile process, releases of new software with new
features to the end-user are months apart. In a lean process, the conversation involves the
end-user, so time between releases is measured in days not months.

In a Lean process, real data quickly trumps opinion as assumptions are quickly put to the test,
features evolved – refined, modified or even removed. Ideas for what to try next are picked up
from scents in the data. These scents are not always purely quantitive, for example an increase
in the number of times a question is sent to the support email address may provide a clue to a
problem or opportunity.

Lean projects ARE typically explicit goals where success can be quantified and measured, for
example the number of sales per day increases. Agile projects often have explicit goals but ones
that are not explicitly quantified, instead Agile projects tend to be specific about how much
time is available. Lean projects tend to focus on achieving quantifiable value for the end-user.
Lean development recognises that delivering real tangible business value is more likely if you
iterate quickly and respond to what the end-user is actually doing.

Lean development is not agile development – lean extends the product development conversation to
the end-user and minimises the businesses exposure to expert bets.

Of course, the real world isn’t quite a black as white as I’ve just painted it. In reality the
differences between what Fred calls Agile and what Wilma calls Agile can be huge. Some people’s
“agile” processes will look more like the Waterfall process whilst others will share the
attributes of a lean process to a greater or lesser extent. So please forgive the blunt contrast
I’ve painted to illustrate my points. I hope you’ve enjoyed this post.


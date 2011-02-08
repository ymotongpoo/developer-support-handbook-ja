Introduction
------------

Welcome to the handbook!
Before diving into the particulars of developer support,
it's important to realize what developer support is,
why it's important, and where I'm coming from in writing this.

Why API Support is Important
^^^^^^^^^^

A few years ago, there were only a handful of APIs on the web.
Now, there are thousands, and there is almost an expectation that
a web application or data provider will provide an API.

By providing an API, you can enable developers to use their creativity
and skill to extend your products to new environments, to handle new use cases,
or to appeal to new users. In the best of worlds, you can make
your product more compelling while also giving developers an opportunity
to make a living off your product API. For example: Twitter started with a simple
web interface but also a simple API, and because of that API, developers
were able to create the clients that users wanted, so Twitter got more users
and developers got more money.

Most of the time, it is not enough to simply provide an API.
You also need to support the developers
that are currently using the API, improve the API to better meet
the balanced needs of the product direction and developers, and encourage
more developers to start using the API.
All of this is a cycle - when you have a good API (and product), more developers
will want to use it, and you will have more developers to support, and you
will need to keep improving the API. To do it right, you need to understand
the commitment that you are making when you decide to provide an API.
You need to realize that you will need someone support the API,
someone to maintain that API (if not improve it),
and often you will want someone to "evangelize" that API - and you will
need those somebodies (whether it's one person or many) for the foreseeable
lifetime of the API. If you are not willing to invest that much time
and resources into the API, then you should reconsider your decision to provide one.

In this handbook, I mostly cover the first aspect of providing an API: support.
It is probably the least glamorous aspect, but on the other hand, it is vital.
You can have the best API in the world, but if people post in your forums and the response
is just crickets chirping, then the developers will not stick around for very long.
On the other hand, if you treat your developers well, then they will (for free)
provide you with valuable insights about ways to improve your API, and they will
evangelize your API for you.

The area of developer support is quite new, and there isn't much written about
how to do it, what works, and what doesn't. Given the increasing number of APIs,
and I hope, the increasing number of people attempting to support API developers,
we need to start documenting our field. This handbook is a first attempt. :)

Who I Am
^^^^^^^^^^

I'm Pamela Fox, and I've spent the last four years of my life
supporting the developer community for various Google APIs.
I started on the Maps API, back when Google had only a handful of APIs
and we were very new to this game

In my role as an API support engineer, I am basically the middleman
(middle woman) between the API developers and the API engineering
team, and I am tasked with making sure that API developers are
successful. This means monitoring the forum for unaswered
questions, reporting bugs to the team, collating the top feature
requests, creating sample code, writing articles, authoring blog
posts, presenting at conferences, training paying customers, and
more. It's a fun role because it involves a lot of different
skills, and it brings a wide range of technical and sociological
challenges.

In this role, I have learned alot about what it means
to succesfully support a developer community, and I want to share
those learnings through this handbook.

Who Can Learn From This
^^^^^^^^

At Google, I come from a team called Developer Relations, and many
of my peers in this team have the same role as me, but for our
other APIs. This information is most directly targeted at them.
However, there are many other people that interact with the API
developer community at some point during their day, and this
information is still highly relevant to them - the API tech lead,
product manager, engineering team, marketing team, technical
writer, support team, etc.

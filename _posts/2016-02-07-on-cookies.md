---
layout: post
title: "On Cookies"
date: 2016-02-07
hero: /images/cookies.jpg
excerpt: "What are cookies, how do they work, and what do we use them for?"
---

There are a variety of reasons that cookies don’t persist for very long: user deletion, device resets, corporate policies, cleanup tools and more. 35% of users delete cookies once per month, so cookie pools that aren’t refreshed shrink down from nearly complete in the first few days, to 65% after a month, to less than 10% after six months.

The technologies that offer ways around this problem are either unreliable or continually caught in PR and legal challenges, so the main approach is to focus retargeting on strategies that prioritise recency.

##Introduction

If you’ve always wanted to know more about cookies and how they impact your digital campaigns, read on. By the end of this article I will have talked about what cookies are and how they work, what we use them for and the impact that has on how relevant they are, and the prevalence and persistence of cookies.

##What is a cookie?

A cookie is actually an incredibly simple piece of technology: it’s a single piece of text stored by a web browser, set by (and readable by) a single web domain. That’s really all: just a single piece of text. What a clever web domain can do with that text is far more interesting.

That piece of text is typically used as a set of “key-value pairs”. A key-value pair is exactly what it sounds like: a value paired up with a key that identifies what that value is for. A key value pair might be “username:alistair”, and that identifies the key as “username” and the value as “alistair”. A website that can read the cookie than then check that key, and look for the value. The result of the value might ensure that I stay logged in as I browse around the website.

A modern cookie might contain lots of key value pairs, all separated by semicolons. As a website owner I could record all kinds of facts about a user’s visit (e.g. the date/time, what pages were browsed, etc) and recover that information on subsequent visits.

Each cookie comes with a persistence: a note to the web browser about how long it should last. Typically a session (it gets deleted when the browser is closed), a fixed number of days, a fixed expiration date, or indeterminate (it will last until the web browser’s built in expiration date, typically around 18 months).

##What do we use them for?

There are a lot of very mechanical uses for cookies that keep websites running. You wouldn’t want to login on every page you open, so a session cookie will store that you’re logged in. I might want to serve first time visitors a different version of my homepage: the cookie’s presence lets me know you’ve visited before.

A cookie also lets me do a bunch of marketing by understanding who a user is in a persistent way: Google Analytics will utilise my cookies to track users across multiple visits so that I can understand frequency, recency, etc.

##What about retargeting?

Remember: a cookie can only be read by the web domain that set it in the first place. That means that if I record a value during your visit to my website another website cannot use that cookie to know who you are, even to serve advertising on my behalf. So retargeting needs to use a different mechanism: third party cookies.

A third party cookie means that it wasn’t set by my site, and isn’t being read by my site. Instead another partner sits between the two to set and read cookies. The big ad tech players (Google, Facebook, AOL, etc) all have third party cookie technology.

As the website owner I include a tiny (just one pixel) image somwhere in my page. That image is hosted on the partner’s web domain, not my own. By considering that image a visit to its own domain, the partner can set a cookie. When an ad is served somewhere else on the web, it opens from the partner’s web domain, and it can read its own cookie. Ingenious.

Third party cookies come with serious privacy implications: as a user I don’t know (without investigating) which domains are setting cookies on my machine. They can all read certain information about the page I’m on: what the domain is, the date and time, the URL path and more. In fact it can then open that same page on its own servers to read the content of that page, so it can always associate the cookie it set with the topic I read.

On a single site, this isn’t really a big deal. The major shift happens when one third party company sets cookies on lots of domains. Which happens. All. The. Time.

>There are a handful of dominant companies serving ads, which means they have pixels on every site serving ads. Which is every content page you read or every video you watch. So they know everything about your behaviour.

The biggest players (Google, Facebook, etc) have very strict policies about what they track and who gets access: nobody. An advertiser will never see that data. An advertiser will buy access to an “audience”, and the ad company will determine whether an individual is in that audience based on the contents of their cookie. For retargeting, the audience might be “people who visited a page on my site in the last seven days”.

##Cookie persistence

That qualifier is what makes this interesting: in the last seven days. Advertisers use different strategies with different recency requirements:

If a user has added an item to their basket but not bought it, the advertiser might want to show them ads for variants of that product for the next 24 hours, but then give up.

If a user visited the site but didn’t get as far as any product pages, then it might be that they should be advertised to for seven days.

If a user bought a particularly expensive piece of furniture, then maybe they should be advertised to for a year or more, to distinguish that customer from somebody who won’t buy at that high price point. An advertiser might decide to pay more for that user in future campaigns.

>Each of these has a different recency requirement (and acceptable maximum frequency), but will also have a different level of effectiveness for one key reason: cookies don’t last forever.

Cookies are an imperfect source of understanding users:
-Some browsers (e.g. mobile safari) simply don’t store third party cookies at all.
-Users move between devices a lot, and cookies are one-device, one-browser.
-People reset their machines, move their user folders, uninstall and reinstall browsers, and do other activities that don’t carry cookies with them.
-On desktops, corporate IT policies might affect how long cookies are stored.
-On home machines, households often share devices between different users.
-Private browsing or do-not-track requests won’t store any cookies beyond the session.
-Computer cleanup tools remove cookies, sometimes on a regular schedule.

What we see as a result is that cookies tend to last for different amounts of time, and a strategy targeting users in the first day or two after a cookie being set is more likely to have a big audience to target than a strategy targeting users 12 months later.

##Cookie deletion rates

Any of the above actions can be classified as a cookie deletion for our purposes, but it’s hard to measure just how often cookies are deleted. There is no “view of the truth” to compare stats against, so we rely on surveys and panels. Panels always underestimate how often cookies are deleted, because they focus on proactive deletions, excluding the other ways cookies fail to persist.

ComScore say 35% of ad cookies are deleted within a month by UK users (other countries show similar figures). At that rate, fewer than 1% of cookies would persist for a full year.

In reality the picture is more complex: some users delete frequently, others infrequently. As a result the true picture is difficult to determine. But given we know what strategies we want to use, we don’t need a full picture, only the milestones relevant to our strategies:

Cookies will be reliable with single digit drop-offs for the first 1–3 days.

By a month, assume 30–40% of cookie data is gone.

After more than a few months, the cookie pool is so small as to be impossible to target.

##Conclusion

Any technology that relies on cookies will suffer decreasing accuracy and scale over time. If our audiences are continually refreshed then our most recent data is still usable, but retargeting strategies that need data beyond a month or two become nearly worthless.

Technologies designed to match and refresh cookies vary widely. Probabilistic matching (i.e. finding users with similar behaviour and search patterns who are served ads in the same location on different device types) suffers a lack of trust and a question about whether the output is more useful than without any persistence. Verizon’s “super cookies” were broadly criticised in the press for over-riding user preferences, as was Google’s attempt to circumvent Apple’s third party cookie blocking. Even Facebook — who use a single ID in the cookie, then store all the information server side — were told by courts to stop tracking people once they’re logged out.

It’s an issue without an obvious solution, but in the environment we can learn to cope: focus on strategies that prioritise recent data.

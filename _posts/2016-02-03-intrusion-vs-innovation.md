---
layout: post
title: Intrustion vs innovation
date: 2016-02-03
hero: /images/binoculars.jpg
excerpt: How do we reconcile the fact that peope don't like their data being shared, but openly publish it on the internet?
---

How can we ensure that we’re being explicit about how we’re using a customer’s data, without scaring them with what we’re going to do with it, all within a sentence or two so that we’re being both clear and concise? What do we in the industry need to do to make sure that we’re not pushing the boundaries of trust (and regulator panic) but we’re delivering a digital experience for consumers that is more relevant and less spammy?

It’s clear that users are uncomfortable with advertisers having access to their data. When surveyed on the topic, almost everybody feels uncomfortable at advertisers using browsing history to target ads. These surveys rarely educate the participants first about what “access” means in this situation. Advertisers don’t get visibility over a person and their behaviour, they get the option to filter ads to only people who match that criteria. It’s possible to implicitly assume “if they came to my site from ad A which was targeting people reading about skiing, then this person was reading about skiing,” but it’s not possible for an advertiser to approach a media owner and ask them “Please give me information on everybody interested in skiing.” It’s a subtle difference, but an important one.

An advertiser’s goal in digital is to serve fewer ads. Whether they’re paying by CPC or CPM, fewer ads served means less money spent. Digital offers a unique opportunity, not only to target users who match a criteria, but to filter out all users who don’t, thereby saving money from being spent on users less likely to become customers. It’s a fantastic system, and huge platforms like AdWords use systems like Quality Score to help encourage that behaviour even further: showing ads only to people most likely to make a purchase saves budget, but also increases your likelihood of showing to similar people in the future.

>Ad advertiser’s goal is to serve fewer ads.

What that means is that I — an advertiser, don’t care about you — a user, unless you already like my ad. In fact, if my ad is annoying, I’ll do anything I can to stop showing it to you. We call it relevance, but it’s not just about making ads seem creepily targeted, it’s about you not having to see my ad at all.

It’s a reinforcement of something referred to as the filter bubble. The argument goes that because there is so much content on the web, users can’t take it all in. So media owners simply don’t show it all. Whether it’s being consumed in a traditional web format or in-stream, algorithms do their best to learn what people like and then eliminate the content that they don’t. It makes a lot of sense for news content (I never want to read about celebrity gossip, my wife would quite enjoy it if that was all she saw) and for social sources like Twitter where there is simply a firehose of information that needs to be curated. It makes less sense for something like Facebook, where the algorithm doesn’t know which pieces of incoming information are important to me (although they’re getting better).

Critics of the filter bubble claim that it reinforces our existing world views. That it increases our likelihood of confirmation bias: that we only notice facts, stories and anecdotes that back up our beliefs, and ignore those that don’t agree. That is bad, but how much of that is algorithms vs personal choice? Facebook released a study recently that determined the level of “filter bubbleness” of a user’s timeline was indistinguishable whether they ran the algorithms or not, and their choice of friends was a far stronger effect.

Advertisers do run the risk of targeting ads too closely and missing out on improving awareness of their products and services, but the goal is that a user who would react well to the ad sees it, and a user who would react badly won’t.

So if advertisers are working hard use tracking and targeting to reduce our ad exposure and annoy users less, why are users still so reluctant to share data? Let’s talk about what constitutes personal information. There are three major definitions at play:

The old definition. This is what is currently used in legislation, and it’s simple: Personal data is information that identifies a person. No complications, really. Names, email addresses and phone numbers are, hashed IDs and cookies aren’t.

The new definition, being proposed to become law under the new EU privacy directives: Personal data is information that can be used to identify a person. This is a subtle but important difference. If an advertiser uses a hashed ID value to track a user across sessions and devices, that ID cannot be able to be tied back to a person if the database.

What people think it means: Information about who people are, or what they do. People consider information personal even if it can’t be traced back to them. It’s possible (but difficult) to trace who I am from a log of what phone numbers I call. I still don’t want that information public, because it feels personal. On the internet, this might be a log of websites I’ve visited, or a profile of content topics I read.

The industry uses that third type of data a lot. It’s anonymised and aggregated, but still used. It can feel like a violation.

So we’ve learned that advertisers want this kind of data to save money and make the internet less annoying/spammy, but users consider that kind of data collection and use a violation. There are several players involved at this point, all with different roles to play.

>It can feel like a violation.

Advertisers typically don’t see that data. They see first party data that a user has explicitly provided and they can target against third party aggregated behavioural tracking, but the advertiser almost never actually collects, stores or processes that data. So they don’t have any kind of agreement with users about how they’ll use it. The complication is that it’s the brand’s ad they’ll eventually see, so the user will associate it with the advertiser regardless.

Tracking companies (ad platforms like DoubleClick, or data brokers like BlueKai) are the ones depositing a cookie on the user’s browser and aggregating that information. These companies rely on impeccable credentials around data protection, so they have very safe collection and storage, and clear and simple opt-outs.

The problem from a user’s point of view is that those opt-outs aren’t universal. The industry has done okay at providing some shared preferences controls (Ad Choices comes to mind) but they don’t work across everything. The technology is also a limiter, since the anonymous technology used to track behaviour is the very same tech used to store opt-outs and preferences: cookies. Clear your cookies, and not only does your profile go away, but a new one begins.

This isn’t too much of a privacy problem most of the time. Major media owners, platforms and advertisers do a decent job at not using advertising technology to breach privacy. Customer database technology is going through its own set of growing pains as major breaches happen every week. Advertising is probably the least culpable (but one of the most visible) parts of the equation. The problem grows when we look around the fringes of the industry.

Many of the checks and balances that exist are based on policy, not technical limitations. Google Analytics doesn’t allow the collection of Personally Identifiable Information (PII), according to the first of our three definitions. But it can’t actually block it. They can use automated checks to look for the presence of email addresses or IP addresses, but a human isn’t allowed to open the account to check, thanks to the very same protection policies that provide what limitations do exist.

Anybody with any significant ad tech experience could easily exploit the least mature, least technically proficient, and least concerned players in the market to conduct personal tracking on an enormous scale, never touching the major platforms and their policies. The technologies exist, the policies are difficult to enforce, so what’s stopping it? Probably nothing. I’d place a lot of money that people are making large sums collecting and selling this data now.

Can anything be done? Legislation is coming to try to improve the landscape, but it’s going to prove unenforceable if the industry doesn’t help. A website owner needs to be explicit about what they’re tracking, but how can they when a typical page carries dozens of trackers? The ICO needs to be able to audit those trackers, and enforce websites to limit, understand, and describe the functioning of every single one they place on their pages.

This isn’t too burdensome, and might clean up the speed of the mobile web too. Unless users can be informed, they can’t make decisions. They can’t be informed while the world of tracking is such a mess. It’s up to website owners to control that, and it’s up to legislators to mandate that.

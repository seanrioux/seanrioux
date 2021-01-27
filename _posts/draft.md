---
layout: post
title: "How To Fix The Web: Ban The Bots"
category: web
author: sean
summary: Social networks are inundated with bots and fake accounts.
---

Social networks are constantly being inundated with bots and fake accounts. A [2017 study](https://arxiv.org/abs/1703.03107) estimated that 9%-15% of the roughly 340 million twitter accounts were not be human. [CNN reports](https://www.cnn.com/2019/11/13/tech/facebook-fake-accounts/index.html) that In 2019 alone, Facebook shut down 5.4 million fake accounts.

While some accounts are used for novelty, many are used more nafariously, and even as part of state sactioned campaigns: programmed to applify and spread harmful discourse, sow real world polorization, and of course as we're all all too familiar, attack the results of elections.

Of course, the issue isn't limited to the US. In Canada, similar analysis has lead to [similar conclusions](https://www.nationalobserver.com/2019/06/26/news/non-human-users-threaten-hijack-canadas-twitter-discussions). While not always state sanctioned, bad actors are actively leveraging non-human activity to manipulate conversation at a global scale.

While efforts by social media companies to combat the impact of non-human activities on their platforms have been fruitful, the problem persists, and it's getting worse.

## Root Causes

Why have these platforms allowed such a persistent and identifiable problem to reach this level of severity?

### Prioritizing user volume

From the beginning these services have prioritized user volume as a key metric. As publicly traded companies, with revenue tied to advertising, user growth has been a proxy for revenue growth and general platform health. The pursuit of user volume over time has lead to a general goal of low friction sign-up, so low, that the process can be automated ad infinitum.

### Lack of user verification

In pursuit of low friction sign-up, these services have thus far resisted more effective user verification measures. While Twitter has recently begun to employ phone verification in cases of suspicious activity, and both Twitter and Facebook offering voluntary verification programs, for the general user no more than an email is a required.

This is fundamentally problematic as email can not act as a reliable indicator of authentic human activity. An email server can easily be self hosted, and email accounts easily created on mass.

While certainly at 340 million users on Twitter and 2.5 billion users on Facebook, verification of all accounts presents a non-trivial technical challenge. However, that email continues to be all that is required for sign-up for platforms of this scale and impact, signals a general lack of effort toward true human-user verification in favour of maintaining user volume and growth.

### Third party interaction via API

In the early days of these services part of the promise (of Twitter in particular) was that of a more open web. Twitter would become the defacto mass messaging service with an easy to use API (application programming interface) to allow all kinds of third-party services to leverage the platform to bring Tweets to other services, and other services to Twitter.

If you're not familiar with the technology, an API allows programmers to interact with software, like Twitter, programmatically. As human users of Twitter we typically use an interface (twitter.com or a mobile app). This interface is an abstraction layer on top of the API that makes it easy for non-programmers to interact with information. The API, conversely allows programmers to interact directly with the information. They can get information, or post information to the service using this API, close to everything that is possible through the interface, but without the limitations of the user interface.

Many business models have been built atop this API based model. If you use Buffer or Hootsuite as part of your digital marketing activities, you're leveraging APIs.

While powerful, and beneficial in some applications, for example automating brand messaging across marketing channels or simply creating interactive or informational programs, these avenues are now broadly exploited by bad actors. Sorting out legitimate use and illegitimate use is something these services are actively engaging, but again the problems persist. At the risk of dissuading legitimate use these services have yet to fully reign in misuse of their APIs, and with few users even aware this automation is possible many of us are interacting with this misuse opaquely.

### Lack of regulating AI

No-one is prepared for how disruptive artificial intelligence is to become in the coming decade and beyond, and yet policy makers and technology companies have done little to nothing to prevent their misuse, and we're already seeing the effect on these platforms.

For the most part the non-human actors on social services we're considering are simple automated bots, designed to mimic human interaction with these services, or simply use the APIs provided by these services as intended.

However, pair this with ease at which deep fakes can produce fake human profile images, video, audio, or how bots can be trained to create original and convincing written text, and the problem of these non-human actors owning these platforms may become intractable. Most solutions meant to mitigate the prevalence of bots, attempt to do so by looking for signature bot activity: monitoring frequency of posting, content originality, or even the nuanced cadence at which step by step interactions occur. Machine learning algorithms trained to mimic human behaviour accurately is not a remote possibility, it's a present reality, and so it may become impossible to stop non-human actors from dominating these platforms if we don't move aggressively to ban them from these platforms.

## Proposed platform solutions

As Jack Dorsey was apt to point out in a recent interview on the New York Times Daily podcast, there is no magic bullet to solving the issues of social media and changes must be carefully considered. For the most part the fundamental mechanisms of these platforms were not designed with a great deal of consideration for their broad social impact. Learning from that mistake, it is essential as we consider any change to these platforms carefully to mitigate future negative impact.

This, however, cannot be used as an excuse for inaction, or more importantly deep changes. This is where it is important for these companies to have the courage to challenges deeply held assumptions inherent to the their businesses, and the web. Things like the inherent anonymity of the web, and business models that rely on quantity over quality must be challenged, considered and discussed openly.

### Verify every account

Starting with new registrations and working through all accounts, all social media accounts should be verified, and determined to be held by a specific individual. While services might opt to allow unverified accounts, these accounts should be flagged as unverified (similar to the current Twitter verified badge) to ensure humans are clearly able to delineate between trusted human sources, and possible non-human actors on the platform.

There are a few methods that could be used here (some already in practice for access to certain features) either in tandem or as part of a suite of possible options:

- **SMS based verification:** a user receives an SMS containing a unique code on registration, which they use, in conjunction with their password, to access the service and on every subsequent sign-in (i.e., two factor authentication).
- **Government issued ID verification:** a user submits a photo of a valid government issued ID which is checked for authenticity and uniqueness.
- **Human profile photo verification:** a user must maintain at least one well lit, machine and human identifiable image of their face (ideally matching that of the ID).
- **Peer verification:** a new user may request verification from peers who are verified on the service to confirm their identity.
- **Address verification:** a new user must submit a mailing address to which they have access. The user receives a postcard from the service to that address, which includes return postage. The user signs the postcard, and mails it back confirming their address.
- **Payment with a credit card:** perhaps the least popular, but one of the most effective and trusted methods would be simply to require users to pay, a one time fee, to process a verification (with a credit card in their name). To some these verifications might seem draconian (though most, if not all are already a part of official verification policies). To some they might present privacy concerns. What about users seeking to hide their identities (or example, whistleblowers or other anonymous actors)? To that I would argue, that without a method to properly verify these individuals are who they say they are, that anonymity does more harm than good on these type of platforms.

The traditional news media has long had policies and methods for verifying anonymous sources as trusted, privately, in ways that protect the source but allow them to publish information they assert as truthful. Self published information from anonymous sources is unverifiable, and thus objectively, untrustworthy.

One account per individual If we are to require verification for each account, the natural conclusion is that only one personal account may be held by each human individual. The operative here is personal account, namely that each human user on these services should be presented as such, and verified as such to be trustworthy.

There is, of course, a legitimate use case for engaging via multiple accounts on social media, for example engaging as a business, organization, or a creator. In these cases additional verification measure can be employed. Should the entity hold special designation (for example, they are a registered LLC or hold a trademark) that this special designation can be submitted for verification, and be identified (e.g., as a badge) in the account profile to build trust.

In cases where this is not so, for example when an account is simply for a blog, or other creator without any sort of incorporation of registration of business then the restriction is simple: these accounts can still be maintained, but will lack badges of verification. Once these creators become established and officially designated in some verifiable way they can then apply for verification and improve their standing.

The goal should be that verification, or special badges of designation should indicate trust not truth per se, but traceability back to human actors. In this capacity badges of verification should be prominent, displayed on every post, every profile, every interface.

## Restrict activity for unverified accounts

As not all accounts will chose to verify (and of course, some may be unable to) activity for these accounts should be restricted. This should act as both an incentive for verification, to encourage verification, but also, to marginalize possible non-human actors who are unable to verify.

A number of possible restrictions might have effect:

- **Restrict frequency of posting:** reduce the rate at which unverified users are able to post to the site (e.g., by the minute or even by the hour).
- **Restrict or demote unverified comments:** reduce the prominence or visibility of comments (or other interactions) made by unverified accounts. If you want your voice to be heard, you need a face.
- **Restrict what they can see:** most effectively perhaps (if not sure to be most controversial), limit the amount of content a user can access if unverified. Restrict them to only verified publishers, limit their feed, whatever it takes to create value incentives to verify.

One might make the point, that many social users (if not most on Twitter and Instagram), are passive users who would not inclined to verify. These users might simply leave or accept a restricted experience, reducing their usage. This could amount to a massive loss of revenue to these platforms, as ad revenue is paired to audience size, and the time people spend on these platforms (both toxic key metrics we'll explore in a future post).

But, as an ad buyer, I can't help but wonder, how much of my ad spend goes to non-human actors ignore my ads? If there not more value to a verified audience?

Fundamentally it's a question quality versus quantity. These platforms may have been built on quantity, but if quantity is artificial its value is lost both to us as users and to advertisers. Refocusing to be providers of greater quality (or at least more verifiably human) engage is a value incentive on both fronts, even if it changes the business metrics.

And that's the key point isn't it? Incentives. Restrictions may be perceived as negative incentives, but if there is no or insufficient incentive to overcome a barrier to entry (like being verified), then this likely reflects a flimsy value proposition. "Easy sign-up" is not a point of value, it's a user experience optimization, and so what are humans getting when we give in to these platforms?

So as we consider restrictions, we must also consider how these platforms can increase the value on offer. Do so, and users will choose to look past restrictions, and verify.

- Flag content posted via API
- Ban AI generated content
- Flag suspected AI generated content
- Empower user moderators

Direct action

As

As brands

- Less automation more human engagement

As individuals

- Act as moderator contributors
- Media literacy "how to spot a fake account"

As governments

- Investment in digital security expertise
- Take the threat seriously

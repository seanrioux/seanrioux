---
layout: post
title: "How To Fix The Web: Ban The Bots"
category: web
author: sean
summary: Social media is inundated with bots engaged in platform manipulation. These bots are programmed to amplify harmful discourse, sow polarization, and as we have seen already this year, lead to real world chaos.
---

- [Summary](#summary)
- [Quality over quantity](#quality-over-quantity)
  - [Embrace friction](#embrace-friction)
  - [Diversify revenue streams](#diversify-revenue-streams)
  - [Set better key results](#set-better-key-results)
  - [Embrace user moderation](#embrace-user-moderation)
- [Incentivize authenticity over anonymity](#incentivize-authenticity-over-anonymity)
  - [Verify every account](#verify-every-account)
  - [Restrict unverified accounts](#restrict-unverified-accounts)
  - [Reward profile completion and accuracy](#reward-profile-completion-and-accuracy)
- [Make automation opaque](#make-automation-opaque)
  - [API Content](#api-content)
  - [Flag artificial interactions](#flag-artificial-interactions)
  - [Flag suspected AI generated content](#flag-suspected-ai-generated-content)
  - [Marginalize, reduce or outright ban all API driven content](#marginalize-reduce-or-outright-ban-all-api-driven-content)
- [Empower better user moderation](#empower-better-user-moderation)
- [Action items](#action-items)
- [Data](#data)
- [Links](#links)

## Summary

Social media, and in particular, Twitter is inundated with bots engaged in platform manipulation. These bots are programmed to post artificial content and interact in ways which amplify harmful discourse and sow polarization leading to real world chaos.

Despite violent attacks on democracy social media platforms continue to manage the problem reactively, if not retroactively. Mass culling of accounts after real world harm occurs is not a sustainable solution. Platforms need to begin to act proactively, restrictively, and on multiple fronts to battle manipulation.

This means a change to their incentives and business fundamentals, and it will cost them. In the meantime, as misinformation draws out this global pandemic and blood is shed what are their continued half measures costing society?

STUB: INTRODUCTION TO THE NEXT SECTION

As Jack Dorsey was apt to point out in a recent interview on the New York Times Daily podcast, there is no magic bullet to solving the issues of social media and changes must be carefully considered. For the most part the fundamental mechanisms of these platforms were not designed with a great deal of consideration for their broad social impact. Learning from that mistake, it is essential as we consider any change to these platforms carefully to mitigate future negative impact.

This, however, cannot be used as an excuse for inaction, or more importantly deep changes. This is where it is important for these companies to have the courage to challenges deeply held assumptions inherent to the their businesses, and the web. Things like the inherent anonymity of the web, and business models that rely on quantity over quality must be challenged, considered and discussed openly.

## Quality over quantity

Platforms have prioritized user growth and usage time as kay metrics. As publicly traded companies, with revenue tied to advertising, pressure on upward user growth is primary. This pursuit of user led-growth has lead to a general industry goal of low friction sign-up, so low, that the process can be easily automated for most services.

Furthermore, it is possible correlating user growth and revenue acts as a perverse incentive; leading companies to ignore fake users, in the interest of inflated growth metrics.

### Embrace friction

### Diversify revenue streams

- Ads are not a sustainable model (Apple's fight against trackers)
- Paid tiers for premium access to audience

### Set better key results

### Embrace user moderation

## Incentivize authenticity over anonymity

INTRODUCTION

LACK OF VERIFICATION

In pursuit of low friction sign-up, these services have thus far resisted more effective user verification measures. While Twitter has recently begun to employ phone verification in cases of suspicious activity, and both Twitter and Facebook offering voluntary verification programs, for the general user no more than an email is a required.

This is fundamentally problematic as email can not act as a reliable indicator of authentic human activity. An email server can easily be self hosted, and email accounts easily created on mass.

While certainly at 340 million users on Twitter and 2.5 billion users on Facebook, verification of all accounts presents a non-trivial technical challenge. However, that email continues to be all that is required for sign-up for platforms of this scale and impact, signals a general lack of effort toward true human-user verification in favour of maintaining user volume and growth.

LACK OF AI REGULATION WILL MAKE THE PROBLEM WORSE

No-one is prepared for how disruptive artificial intelligence is to become in the coming decade and beyond, and yet policy makers and technology companies have done little to nothing to prevent their misuse, and we're already seeing the effect on these platforms.

For the most part the non-human actors on social services we're considering are simple automated bots, designed to mimic human interaction with these services, or simply use the APIs provided by these services as intended.

However, pair this with ease at which deep fakes can produce fake human profile images, video, audio, or how bots can be trained to create original and convincing written text, and the problem of these non-human actors owning these platforms may become intractable. Most solutions meant to mitigate the prevalence of bots, attempt to do so by looking for signature bot activity: monitoring frequency of posting, content originality, or even the nuanced cadence at which step by step interactions occur. Machine learning algorithms trained to mimic human behaviour accurately is not a remote possibility, it's a present reality, and so it may become impossible to stop non-human actors from dominating these platforms if we don't move aggressively to ban them from these platforms.

This is why I'm recommending a few premptive actions:

- Ban AI generated content

This it's why companies act now: to work to ban any and all automated activity, and to allow human communications to be human scale.

STUBS

- Fake accounts and real accounts look the same
- Bots is a platform issue, but the burden of media literacy is on users

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

### Restrict unverified accounts

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

### Reward profile completion and accuracy

## Make automation opaque

API INTRO 1

In the early days of these services part of the promise (of Twitter in particular) was that of a more open web. Twitter would become the defacto mass messaging service with an easy to use API (application programming interface) to allow all kinds of third-party services to leverage the platform to bring Tweets to other services, and other services to Twitter.

If you're not familiar with the technology, an API allows programmers to interact with software, like Twitter, programmatically. As human users of Twitter we typically use an interface (twitter.com or a mobile app). This interface is an abstraction layer on top of the API that makes it easy for non-programmers to interact with information. The API, conversely allows programmers to interact directly with the information. They can get information, or post information to the service using this API, close to everything that is possible through the interface, but without the limitations of the user interface.

Many business models have been built atop this API based model. If you use Buffer or Hootsuite as part of your digital marketing activities, you're leveraging APIs.

While powerful, and beneficial in some applications, for example automating brand messaging across marketing channels or simply creating interactive or informational programs, these avenues are now broadly exploited by bad actors. Sorting out legitimate use and illegitimate use is something these services are actively engaging, but again the problems persist. At the risk of dissuading legitimate use these services have yet to fully reign in misuse of their APIs, and with few users even aware this automation is possible many of us are interacting with this misuse opaquely.

API INTRO 2

As human users of Twitter we use an app or the web interface. An API, (or application programming interface) allows programmers to build software automation to interact with the service, also known. Depending on the service, these bots can do close to everything that is possible through the app or web interface, but without the limitations of the user interface or a human user: bots can work faster, more efficiently, and around the clock.

Why would they allow this you might ask? The purpose of a social API is to allow third-party businesses to leverage the platforms to build new products and services. If you use Buffer or Hoot-suite, for example, you're leveraging APIs.

While perhaps beneficial in these applications, these same APIs may also be exploited by bad actors. Furthermore, sorting legitimate and illegitimate use is a non-trivial task, inevitably requiring human moderation for millions, if not billions of individual automated interactions.

Most problematically, perhaps, user are typically not even aware this automation is possible or prevalent, meaning legitimate or not, many of us are interacting with automated content opaquely (i.e., we have no indication that we are interacting with an API driven automation).

### API Content

### Flag artificial interactions

The social media platforms have recently begun flagging content as potentially harmful, or misleading, including both alt-right and COVID-19 disinformation. This is a step in the right direction, however it only addresses content that has been reported by users (or determined to be misleading by internal moderators). In these cases a manual intervention is required, and this simply doesn't scale to the issue of artificial content.

At scale, content must be flag proactively for the possibility that there is no human actor behind it. Similar to flags for harmful or misleading information, these flags or alerts would appear before a user is able to interact with the suspected artificial content. This additional friction or indicator would allow users the opportunity to make a value judgement about the content before interacting.

These types of flags could be applied in the following scenarios:

- **Content posted via API:** when an automation interacts with an API resulting in public facing content, for whatever purpose, this should be transparent to the end user. A indication of what specific software may have been used, as well as a warning indicating that the account may or may not be managed by an actual person could help users moderate their desired level of interaction in a more informed way.
- **Content which is highly duplicitous to other content:** while the specifics of algorithms used to determine content as artificial are much to complicated to discuss in the context of this article, there are some immediately obvious indicators, which anyone who spends enough time on social media are aware. Duplicative content for example. Bots will often have a set of templates used to create posts. While these could be sophisticated enough to rotate or rearrange words to create original sounding content, it's often the case that the content is still highly duplicated across the platforms. Even in cases where duplicate content may not be artificial but just simply reflective of a shared perspective, a flag indicating content as high duplicated would encourage greater originality and consideration before reposting.
- **Content which has been flagged, but not confirmed as artificial:**

While certainly some legitimate uses would be caught up in this kind of flagging, in both the cases of API posted content, and duplicitous or artificial seeming content, a virtuous cycle of prioritized human interaction, authenticity, and originality is perhaps the only true side effect. Any argument that supposes that somehow the echo chamber of shared outrage is a positive feature of these platforms is delusional.

Yes, certainly collective outrage associated with a movement like Black Lives Matter, or the Arab Spring may result in positive outcomes in society; a freer more fair and democratic world is the promise, but at times also disproportionate reaction and violence.

### Flag suspected AI generated content

### Marginalize, reduce or outright ban all API driven content

UNPOPULAR

On Twitter actively allowing parody bots to continue, many parody bots are adding to the disinformation discourse even if not immediately harmful way does have the negative side effect of contributing more discourse which is not human in this polluting the actual set of perspectives that might exist within a population. Should and Twitter continue to be a platform that's viable for civil discourse then the discourse should be limited to actual human civil discourse. Doesn't make sense for conversations being had about complicated political issues to be had on the same platform and to coexisting with bots which are able to post parity content which is seemingly human even fooling people.

## Empower better user moderation

## Action items

- Provide incentives for users to verify themselves and provide accurate information about who they are
-

## Data

- A 2017 study estimated that 9%-15% of Twitter accounts were bots
- A 2019 CNN report found Facebook removed 5.4 billion fake accounts

## Links

- [Nearly half of accounts Tweeting about Coronavirus are likely bots](https://www.npr.org/sections/coronavirus-live-updates/2020/05/20/859814085/researchers-nearly-half-of-accounts-tweeting-about-coronavirus-are-likely-bots)
- [The next-generation bots interfering with the US election](https://www.nature.com/articles/d41586-020-03034-5)
- [Researchers: Nearly Half Of Accounts Tweeting About Coronavirus Are Likely Bots](https://www.npr.org/sections/coronavirus-live-updates/2020/05/20/859814085/researchers-nearly-half-of-accounts-tweeting-about-coronavirus-are-likely-bots)
- [Non-human users threaten to hijack Canada's Twitter discussions](https://www.nationalobserver.com/2019/06/26/news/non-human-users-threaten-hijack-canadas-twitter-discussions)

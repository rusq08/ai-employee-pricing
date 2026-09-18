# highlevel ai employee pricing: what the $50, $97 and pay-per-use options cost per sub-account, and when adding CloseBot is cheaper

If you've ever tried to quote a client a monthly fee for an "AI employee," you already know the problem. The headline number in the marketing is $97. The invoice at the end of the month is rarely $97.

HighLevel's AI pricing is not a single line item. It's a subscription per enabled location, plus phone system charges, plus a couple of AI products that stay metered no matter which plan you pick, plus overages if usage crosses the included limits. For an agency running ten client accounts, those layers add up faster than the plan name suggests.

This breaks down what HighLevel actually charges per location, where the plans stop covering you, and how a dedicated appointment-setting layer like CloseBot fits into that budget.

## What you're actually paying for

HighLevel sells AI access under three billing modes, and all three are charged per enabled sub-account:

- **Pay-per-use** — no monthly AI fee, usage billed as it happens
- **AI Employee Growth** — $50/month per enabled location
- **AI Employee Unlimited** — $97/month per enabled location

The AI fee sits on top of whatever you're paying for the platform itself. HighLevel currently lists its Starter plan at $97/month, Unlimited at $297, and Agency Pro at $497. So a location on Unlimited tier, running under a $297 platform plan, is costing you $394/month in software before a single SMS goes out.

That word "location" is the part people miss. AI Employee is not priced per agency. It's priced per sub-account that has AI switched on. Ten active client locations on the $97 tier is $970/month in AI subscriptions alone, which can be more than double the agency's own platform bill.

## The three options side by side

Here's how the current documented pricing breaks down. All figures are USD, per enabled location.

|  | Pay-Per-Use | AI Employee Growth | AI Employee Unlimited |
| --- | --- | --- | --- |
| Monthly AI fee | None | $50 | $97 |
| Conversation AI | Token cost | 1,000 agent responses/month | Unlimited (fair use) |
| Voice AI | Voice Engine + TTS + LLM tokens | 100 minutes/month, shared across inbound, outbound and widget | Unlimited (fair use) |
| Reviews AI | $0.01 per review | Unlimited | Unlimited |
| Content AI | $0.063/image, $0.0945 per 1,000 words | Unlimited | Unlimited |
| Ask AI / AI Studio | Token cost | Included usage | 3x included usage |
| Managed Agents | Token cost | 100 runs/month | 1,000 runs/month |
| Agent Studio | Token cost | Token cost | Token cost |

Two details in that table matter more than the rest. First, **Agent Studio is pay-per-use on every plan**, including Unlimited. If your build relies on custom agents with web search and external APIs, that line never goes away. Second, the word "unlimited" is qualified by a fair-use policy — HighLevel reserves the right to throttle or require an upgrade if usage is excessive or affects platform performance.

## What no AI Employee plan covers

This is where invoices drift away from expectations. Even Unlimited doesn't remove these:

- **Phone system charges.** Phone numbers and call minutes bill separately through the wallet. HighLevel's phone billing documentation lists local numbers around $1.15/month, toll-free around $2.15/month, and outbound calls around $0.018/minute before extras like recording and transcription. A Voice AI call can be fully covered by Unlimited and still generate a phone charge.
- **SMS and messaging.** A Conversation AI reply that goes out over SMS is still an SMS charge. WhatsApp is currently listed at $10/month per enabled sub-account plus usage.
- **A2P 10DLC registration** and carrier-related fees for US business messaging.
- **Growth overages.** Once the 1,000 responses or 100 voice minutes run out, billing continues at pay-per-use rates — unless the location is set to block AI at the limit, in which case your AI simply stops mid-conversation.
- **Your platform subscription.** Starter, Unlimited or Agency Pro, unchanged by any AI plan.

So the honest framing for **highlevel ai employee pricing** is this: $50 and $97 buy coverage of specific AI products, not a fixed bill. Budget the subscription, then add telephony, messaging, Agent Studio and possible overages on top.

## Pay-per-use, Growth or Unlimited? The crossover math

The middle tier is the one agencies agonise over, and it comes down to voice minutes.

Growth costs $47 less than Unlimited and includes 100 AI Agent minutes. Under the standard voice setup, the per-minute base is $0.045 for the Voice Engine plus $0.015 for OpenAI or Cartesia text-to-speech — about $0.06/minute before language model tokens and phone charges. Divide the $47 difference by that rate and you get roughly 783 additional minutes. Add the 100 included minutes and the theoretical crossover lands near **883 minutes per month**.

Swap in ElevenLabs V3 at $0.170/minute of TTS, and the same $47 only buys about 319 minutes including the allowance. Speech-to-speech models change it again: Gemini 3.1 Flash Live Preview is listed at $0.10/minute and OpenAI's realtime models at $0.20/minute.

None of these are invoice thresholds. They're ceilings that exclude tokens and phone charges. But they're enough to make a decision:

- A location handling a handful of calls a month belongs on pay-per-use.
- A predictable, moderate volume — a receptionist answering during business hours — usually fits Growth.
- A location where calls run all day will make Unlimited easier to budget, even with fair-use caveats.

Agencies don't have to put every client on the same tier, either. Access is granted per sub-account from the AI Suite, which is the cheapest lever most agencies have.

## If you're reselling AI, read the rebilling rule first

Here's a constraint that catches agencies off guard: rebilling AI Employee usage to clients requires the **$497/month Agency Pro plan**, per HighLevel's documentation. That's a specific plan requirement, not a general capability of SaaS mode.

Once that's in place, you can either rebill supported usage with a markup or a fixed per-unit rate, or resell Growth and Unlimited as a client-facing subscription under Agency View → Reselling → Subscriptions → AI Employee.

What agencies charge varies wildly. In public agency discussions, some report flat monthly AI retainers around $100 per client while others describe single clients worth four figures a month. HighLevel doesn't publish recommended client pricing, so the number is your call — but the underlying cost is not. It's fixed per location, whether or not the client uses it.

## The alternative line item: a dedicated setter on top

This is where a lot of HighLevel users end up looking at CloseBot. The pattern is consistent: native Conversation AI covers the basics, but the moment you need reliable multi-step qualification, reschedule handling, or the ability to update more than a handful of custom fields, agencies add a purpose-built layer and keep HighLevel as the CRM.

CloseBot is the most-installed sub-account app in the HighLevel app store, and its pricing model is structurally different from AI Employee. Instead of a per-location subscription, it's a platform fee plus usage you can rebill.

The current plans page lists four options:

| Plan | Price | What's included | Billing cycle | Get started |
| --- | --- | --- | --- | --- |
| Free | $0 | 100 messages/month, 1 agent, 1 user seat, 1 MB storage, unlimited account connections | Free forever under the message cap | [Start on the CloseBot free plan](https://app.closebot.com/a?fpr=li87) |
| Core — Business | From $64/month (annual equivalent $53/month, billed as $640/yr) | Message costs included in the base price, 15+ templates (50+ on annual), human support, add-on seats at $5 each | Monthly or annual, month-to-month | [Compare the CloseBot business plans](https://app.closebot.com/a?fpr=li87) |
| Core — Agency | $397/month (about $331/month on annual billing) | Unlimited account connections, message costs billed at **$0.012 per message**, fully rebillable, white-label client portal, rebill all costs | Monthly or annual, month-to-month | [See the CloseBot agency plan](https://app.closebot.com/a?fpr=li87) |
| Growth | Custom quote | HIPAA compliance, quarterly audits, 99.99% priority uptime, priority support, 50+ templates, unlimited potential | Custom, via sales | [Talk to CloseBot about Growth](https://app.closebot.com/a?fpr=li87) |

A few honest notes on that table.

The Business track's price scales with included message volume rather than staying at $64 forever. A third-party review that verified pricing against the plans page in August 2026 lists the monthly tiers as roughly $84 for 1,000 messages, $109 for 2,000, $176 for 5,000, $454 for 20,000, $806 for 50,000, and around $1,059 at 100,000 messages. Annual billing drops the effective rate by about two months' worth and unlocks the larger template library.

The Agency track bills messages separately at $0.012 each, but the whole point is that you rebill them. You set the markup; the difference is your margin. Note that older CloseBot documentation still quotes $0.006 per message, and the plans page now says $0.012. Treat the current plans page as the number that applies.

Also worth knowing before you commit: there are no refunds. Instead there's a free-forever plan under 100 messages and a 7-day trial on any paid plan, which is where you should do your testing. Plans are month-to-month with no contract, and CloseBot doesn't allow bringing your own model API key — it's framed as a security decision, and it means your model spend is baked into the plan rather than billed by your own provider.

## Fixed per location vs metered per message

The two pricing models pull in opposite directions depending on your volume, and this is the part worth doing arithmetic on rather than arguing about.

CloseBot published its own comparison using a 102-sub-account account doing about 24,720 messages a month. On their math, CloseBot came to roughly $809/month (a $397 base, $148 in message costs, $9 in storage, $255 in model tokens), against $9,894/month for the same footprint on AI Employee Unlimited at $97 per sub-account — or about $511 on HighLevel's pay-per-use conversation pricing. That analysis is vendor-published, so read it as CloseBot's argument rather than a neutral audit. But the structural point holds: at 102 locations, per-location subscriptions compound, while per-message costs scale with actual activity.

The reverse is true at the low end. For a business with four sub-accounts doing a few hundred messages a month, AI Employee Unlimited would cost $388/month — and if those locations barely use the AI, that's a fixed bill for unused capacity.

Rough rule of thumb:

- **Low volume, few locations:** pay-per-use or CloseBot's free and entry tiers.
- **High volume, many locations:** CloseBot's agency plan with rebilled messages.
- **Heavy voice usage:** HighLevel's Voice AI is genuinely bundled well at $97 per location, and that's the one place native wins clearly.
- **HIPAA or audit requirements:** CloseBot's Growth tier or a documented Higher-level setup, depending on who's signing the compliance paperwork.

## Which one you should pick

If you're selling AI to clients on HighLevel, the decision usually comes down to three questions.

**Do your clients need AI on every location?** If yes, per-location pricing is a growing fixed cost you carry whether or not the client engages. If only some locations need it, grant access selectively from the AI Suite and keep the rest on pay-per-use.

**Is your bottleneck voice or text?** HighLevel's Unlimited plan bundles voice minutes in a way that's hard to beat for a location taking calls all day. For text-heavy qualification, booking and follow-up, a dedicated setter is usually the better spend, because that's the entire product rather than one module inside a CRM.

**Are you reselling?** The $497 agency plan requirement for AI Employee rebilling is a real cost threshold. CloseBot's agency plan is $397/month with rebillable messages, so the two don't stack comfortably for every agency. Work out which layer produces the client-facing offer before paying for both.

If you want to run the numbers on your own volume rather than someone else's case study, the cheapest way to test the second option is to build an agent on the free tier and see how the conversation quality compares with what you're currently shipping. 👉 [Build your first CloseBot agent free](https://app.closebot.com/a?fpr=li87) — no credit card, and the free plan stays free as long as you stay under 100 messages a month.

## FAQ

**How much does HighLevel AI Employee cost per month?**
$50/month per enabled location for Growth, $97/month per enabled location for Unlimited, or pay-per-use with no monthly AI fee. Your platform subscription, phone system usage, messaging, Agent Studio and any Growth overages are separate.

**Does the $97 plan include voice calls?**
The AI portion, yes — Unlimited covers inbound, outbound and widget Voice AI subject to fair use. Phone system charges still apply to every call regardless of plan.

**What happens when Growth runs out of included usage?**
It depends on the location's AI Usage Limit setting. With "keep AI running, just notify" or spending limits disabled, usage continues at pay-per-use rates. With "block AI at the limit," the AI stops when the cap is reached.

**Can I rebill AI Employee costs to clients?**
Yes, but HighLevel's documentation states agencies must be on the $497/month plan to rebill AI Employee usage. Reselling Growth or Unlimited as a recurring client subscription is configured separately under Agency View.

**Is CloseBot priced per sub-account like AI Employee?**
No. CloseBot charges a platform fee plus message usage. The agency plan is a flat $397/month with messages at $0.012 each, rebillable at whatever markup you set, and it supports unlimited account connections.

**Is there a free way to test either option?**
HighLevel offers a platform trial but no permanent free AI Employee tier — pay-per-use still generates usage charges. CloseBot has a free-forever plan capped at 100 messages a month plus a 7-day trial on paid plans, which is enough to test a real conversation flow before you commit.

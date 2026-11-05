# 08 — From views to followers to revenue

**Revised 2026-11-05 (gap-fill pass).** Sections 3, 4, 6 and 7 now carry prices read off live sales pages, store listings and one operator's own public plans endpoint, each dated. Sections 1 and 2 are unchanged from the first pass and remain weakly evidenced.

**Read this first: evidence quality.** Searches found very little primary data on view-to-follow conversion and almost nothing public on tricking-specific revenue. Most conversion advice is from creator newsletters and tool vendors, so treat their numbers as anecdotes. Where I could not verify something I say so. Anything marked `[inference]` is my reasoning, not a sourced fact. TikTok and Instagram pages were not reachable.

## 1. Why 10M views gave you ~6k followers

A view means someone watched. A follow means they expect to want more of you. Your crash video hit three gaps at once.

| Mechanism | What the evidence says | Applies to you because |
|---|---|---|
| **Audience mismatch** | Creator write-ups say a viral clip often reaches casual viewers who don't care about the account's niche ([Creator Confidential](https://catarinamello.substack.com/p/stop-chasing-virality-and-do-this); [vidIQ commentary on trend-driven spikes](https://rosetta.to/u/vidiq/one-of-our-worst-videos-just-blew-up)). Instagram says Reels are served mostly from accounts people don't follow ([onlinemarketing.de on Mosseri](https://onlinemarketing.de/social-media-marketing/instagram-impressions-profiloptimierung-mit-plattformchef)). | A crash at a famous gym is watched by people who like crashes, not tricking. They have no reason to want a second tricking clip. |
| **"No reason to expect more"** | One creator's own test: the personal-brand account had the lowest view-to-follow rate because the profile and past posts gave no reason to follow and no video had a clear CTA ([chaotic-creator](https://chaotic-creator.beehiiv.com/p/1m-views-on-8-videos-exposing-what-i-did)). Entertainment videos converted about 0.01% there; educational "system" videos converted better. Same source, small sample, self-reported. | A spectacle clip is a complete product. Nothing promises a next one. |
| **Spectacle vs identity** | Sources converge that people follow an answer to "why should I follow this person?" ([Creator Confidential](https://catarinamello.substack.com/p/stop-chasing-virality-and-do-this)). | The crash showed a body doing a trick, not who Taita is or what he'll do next. `[inference]` |
| **Profile dead-end** | Mosseri's profile advice (via German coverage): pinned posts control the top line, and photo plus bio should explain the account at a glance ([t3n](https://t3n.de/news/tipps-vom-profi-instagram-chef-mosseri-erklaert-wie-du-dein-profil-zum-hingucker-machst-1676863/)). | A visitor who taps through lands on whatever you posted last. |
| **No series, no recurring character** | Multiple sources say treat a viral video as the start of a series ([Exposed Brick](https://exposedbrickdc.substack.com/p/why-going-viral-isnt-the-goal)). I found no controlled test. | A single legendary video with unrelated posts around it has no hook to follow. |

Anecdotes from the same search: one creator reported a 9M-view video leaving an account under 200 followers, and another reported 4.5M views giving ~1,000 Instagram and ~150 TikTok followers. The search summary gave these without an extractable link, so treat both as `(unverified)`.

**Benchmarks, low confidence.** Vendor blogs say profile visits should be 2 to 5% of views and 15 to 30% of visitors follow ([TT Calculator](https://ttcalculator.net/calculators/profile-visit-rate/)). Not TikTok-official. Use them only as a rough sanity check, and measure your own: profile visits and follower conversion are in each video's analytics.

**What I could not find:** a published post-mortem from a tricking, parkour or martial-arts account specifically on a viral crash. A separate workstream owns the tricking diagnosis.

## 2. Fixes, ranked by evidence and effort

Evidence for all of these is anecdotal. The ranking is mostly my judgement of cost against plausibility.

| # | Fix | What it does | Evidence | Do this week |
|---|---|---|---|---|
| 1 | **Pinned trio + bio** | Fixes the dead-end for every future visitor. Pin up to 3 videos. | Mosseri on pinned top line (above). A pinning explainer says not to pin only the viral video ([Short](https://www.youtube.com/shorts/mNMyfU8ZiEw)). Weak but nearly free. | Pin: (1) the landed double-back, (2) your best tricking video where you speak or show a clear next step, (3) a "start here" explaining the series. Bio one line: who, what, and the promise ("8th in the US. I teach one trick breakdown a week."). 30 minutes. |
| 2 | **Explicit follow-worthy promise in the video** | Gives a reason to follow. | The chaotic-creator test: videos with a clear CTA and repeatable system converted better. A vendor claim says spoken or caption CTAs gain 2-3x, from unnamed "creator studies" `(unverified)`. | End each clip with a specific promise ("Part 2 tomorrow", "next: the one that broke my ankle"). Never a generic "follow for more". |
| 3 | **A named series** | Turns a clip into an expected habit. | Repeated in sources, no controlled data. | Pick one: "Landing the thing that crashed me, part N" or "Tricking from 8th in the US." Same title format, same first line. |
| 4 | **Follow-up to the old viral video** | Catches the leftover traffic. | Advice to post a follow-up soon after a hit (above). Yours is years old, so it only helps while the video still gets views. `[inference]` | Reply-to-comment on the crash with the landing story, pinned. |
| 5 | **Consistent cover style** | Makes the grid read as one thing. | I found no data. Mosseri's grid advice is about coherence only. | Same cover text template. Low priority. |
| 6 | **Personality / recurring character** | Gives identity beyond the trick. | Sources agree on "why follow *this person*" but none quantify it. | You already have a character: 19, Berkeley CS, building startups, ranked 8th. Say one personal fact per clip. |
| 7 | **Know which videos convert** | Stop guessing. | Analytics guides ([Printful](https://printful.com/blog/tiktok-metrics)). | Check each video's new-follower count, repeat the top 2 formats. |

**First-three-videos problem:** a visitor sees the pinned three plus the latest row. If the latest row is random, the pins don't matter. `[inference]` Keep the next 6 posts inside the series.

## 3. How people in these niches actually make money

**This section was rebuilt on 2026-11-05 with prices read off live sales pages, not estimates.** Every price below was read on **2026-11-05** unless another date is given. Prices move — re-check before you quote them.

### 3.1 Dated price table (read 2026-11-05)

| Operator | Niche | What is sold | Actual listed price | Platform | Link |
|---|---|---|---|---|---|
| **Kojo's Trick Lab** (Sam Kojo) | Tricking | **Basic** — all programmes + complete video library | **$15.00/mo** or **$120.00/yr** | Own site (Laravel app, PayPal checkout) | [kojostricklab.com](https://www.kojostricklab.com/) — prices from its own public plans endpoint [`/api/auth/available-packages`](https://www.kojostricklab.com/api/auth/available-packages) |
| **Kojo's Trick Lab** | Tricking | **Review** — library + **15 clip reviews** | **$50.00/mo** or **$200.00/yr** | same | same |
| **Kojo's Trick Lab** | Tricking | **Review Plus** — library + **50 clip reviews** | **$60.00/mo** or **$250.00/yr** | same | same |
| Sam Kojo | Tricking | "Tricking for Absolute Beginners" course (workbook + QR-linked progression videos, 5 levels, lifetime access, 30-day refund) | **Price is not public** — the page only has an "Enroll Now" button; no amount shown anywhere on the course or catalogue page | Teachable | [sam-kojo-coaching.teachable.com](https://sam-kojo-coaching.teachable.com/p/tricking-for-absolute-beginners) |
| **Jujimufu (Jon Call)** | Strength / acrobatics | Legendary Flexibility | **$40.00**, "From $30.00" (variants) | Own Shopify store | [jujimufu.com/collections/programs](https://jujimufu.com/collections/programs) |
| **Jujimufu** | " | The Next Step, Let's Grow Some Muscle, The Bridge, The Builder, The Almost Naked Athlete, The Groundbreaker, The Invincible Athlete, **Backflip Training Manual** | **$40.00** each, "From $20.00" | same | same |
| **Jujimufu** | " | Overcome Training Injuries | **$20.00**, from $15.00 | same | same |
| **Jujimufu** | " | Merch: Stretchy Pants $64.00; Baggy Movement Pants / Workout Pajamas / Very Good Sweatpants $60.00; smelling salts $25.00; Short Shorts $36.00 (sale $18.00) | as listed | same | [jujimufu.com](https://jujimufu.com/) |
| **Loopkicks** | Tricking | **The business appears gone.** `loopkicks.com` now returns **HTTP 302 to `strongdomains.com/domain/loopkicks.com`** — a parked / for-sale domain. The `inplay.org` "Team Loopkicks online tricking class" listing cited in the earlier draft now returns **404**. | **No price exists to find** | — | [inplay.org listing (404 as of 2026-11-05)](https://www.inplay.org/so/r/santa-clara/providers/team-loopkicks/online-tricking-class) |
| **Chris Heria / THENX** | Calisthenics | THENX app subscription — **web pricing** | **$18.99/mo**; **$113.99/yr** (shown against $227.88, "6 months free", "saves 50%") | app.thenx.com | [app.thenx.com/upgrade](https://app.thenx.com/upgrade) |
| **Chris Heria / THENX** | " | THENX app — **App Store IAP** | $9.99/mo and $19.99/mo; $89.99/yr and $119.99/yr; plus tip jars $9.99–$99.99. Free download, 12K ratings / 4.8 | iOS App Store | [apps.apple.com/us/app/thenx/id1192413645](https://apps.apple.com/us/app/thenx/id1192413645) |
| **Chris Heria** | " | **Heria Pro** (second app) | **$11.99/mo**, **$119.99/yr**. Free download, 7.5K ratings / 4.8 | iOS App Store | [id1356721066](https://apps.apple.com/us/app/heria-pro/id1356721066) |
| **Chris Heria / THENX** | " | *Scale of that app business* | **1.6M cumulative installs; "<$10K monthly revenue est.", 100% from IAP; weekly +483 installs, "Declining"** — third-party estimate, **last crawled 2026-11-01** | AppGoblin | [appgoblin.info/apps/1192413645](https://appgoblin.info/apps/1192413645) |
| **Hybrid Calisthenics (Hampton Liu)** | Calisthenics | App — **free, and the page commits to free**: "It's free to use and all core functions are expected to remain free." Paid tier = "Premium Supporter" (no ads, custom rest timer, 2 extra movements, early access) | **$14.99/mo**, **$25.00/quarter**, **$75.00/yr** (page also shows $89.00, $99.00 and $99.99 annual entries). Free download, 3.1K ratings / 4.8 | iOS App Store | [id6444292787](https://apps.apple.com/us/app/hybrid-calisthenics/id6444292787); [app-info page](https://www.hybridcalisthenics.com/app-info) |
| **Hybrid Calisthenics** | " | Book $29.99; eBook $14.99; book+eBook bundle $38.99 (reg $44.98); cards $25; book+cards $50 (reg $54.99); water bottle $22; rings **sold out** | as listed | Own Shopify shop | [shop.hybridcalisthenics.com](https://shop.hybridcalisthenics.com/collections/all) |
| **Storror** | Parkour | **STORROR+** membership — weekly exclusive series, live streams, community page, merch early access | **£6.99/mo**; **£17.99/3 months** (marked "Most Popular", pitched as "about 20p a day"); **£69.99/yr** ("2 months free") | storrorplus.storror.com | [storrorplus.storror.com](https://storrorplus.storror.com/) |
| **Storror** | " | STORROR+ **app** | **$6.99/mo**, **$69.99/yr**. Free download; only **16 US ratings** and **0 JP ratings** — a new app | iOS App Store | [id6744359541](https://apps.apple.com/us/app/id6744359541) |
| **Storror** | " | TECH TENS shoes | **£65.00**, reduced from £135.00 | storror.com | [storror.com/collections/all](https://www.storror.com/collections/all) |
| **Jesse Enkamp** | Karate | KNX22 seminar videos | **EUR 49.00** (confirmed in the page's own product data: `price_cents: 4900`, `currency_code: "eur"`) | Gumroad | [jesseenkamp.gumroad.com/l/knx22](https://jesseenkamp.gumroad.com/l/knx22) |
| Small anonymous seller | Calisthenics | "Calisthenics 4 weeks program" (PDF) | **$12.99 USD** — and the page's own data says **`ratings: {count: 0}`** | Gumroad | [calisthenicss.gumroad.com/l/Program](https://calisthenicss.gumroad.com/l/Program) |
| FitSet Ninja (Edmonton) | Obstacle / ninja | Summer camp, ages 5–12, certified coaches, max 12 athletes per coach | **"Starting at $79.00" + GST**; every 2026 week listed as Closed | Own site | [fitsetninja.com](https://fitsetninja.com/tricking-summer-camps) |
| Laws of Motion (Ottawa) | Acro | Season programme | $220.50 (2023–24) | Amilia | [amilia listing](https://www.amilia.com/store/en/laws-of-motion/shop/activities/5088126) |

**Notes on the Kojo numbers, because they are the most important in this report.** Kojo's Trick Lab is a single-page app that renders nothing server-side, so the prices are not on a human-readable pricing page — they come from the site's own public plans endpoint, which is what the site itself calls to draw its signup screen. The response has fields `name`, `price`, `timeRange`, `trialTimeCount`, `trialPrice`, `mostPopular`, `perks`. **Basic is flagged `mostPopular: true`.** `trialTimeCount` and `trialPrice` are **null on all six plans — there is no free trial.** The JSON carries **no currency field** and the prices are plain decimals (`"15.00"`); USD is my reading, not a stated fact `[inference]`. His Teachable page still claims Kojostricklab "has helped over 4000 paying customers" (claim read 2026-11-05; could be cumulative, not concurrent).

### 3.2 What the price table actually tells you

1. **A tricking video library is worth about $15/month. Human eyes on your clips is worth $50–60.** Kojo prices the *same* library at $15 and then charges **3.3x** for 15 clip reviews and **4x** for 50. The margin in this niche is in the coaching, not the content. That is the single most useful fact in this report for you.
2. **Nobody in movement sells a high-ticket product.** The whole verified range for digital products is **$6.99/mo to $60/mo**, and one-off programmes are **$12.99–$49**. There is no $997 course anywhere in tricking, parkour or calisthenics that I could find. Plan your revenue around volume × small price, or around hours × real coaching rate — not around a big-ticket launch.
3. **Low-ticket digital in this niche needs enormous reach to matter.** Chris Heria has two paid apps and **1.6M installs**, and the third-party estimate is still **under $10k/month, declining** (AppGoblin, crawled 2026-11-01). Storror, with roughly 11M YouTube subscribers `(unverified, per [SponsorRadar](https://sponsorradar.com/channels/storror))`, charges **£6.99/month**. `[inference]` If reach at that scale produces those numbers, a $15/mo library at 6,000 followers produces pocket change. Do not build a library.
4. **An online tricking coaching business can simply die.** Loopkicks — the operator the previous draft named as proof that online tricking coaching sells — now has a **parked, for-sale domain** and a dead class listing. Treat "sell online tricking coaching to the world" as a business with real mortality, not a safe default. `[inference]`
5. **Two opposite app models both work.** Heria gates everything behind $11.99–$18.99/mo. Hybrid Calisthenics states in writing that core functions stay free forever and charges **$14.99/mo for cosmetics** (ads off, rest timer, two extra movements) — a tip jar dressed as premium. Both have millions of followers. The choice is a positioning choice, not a revenue optimisation. Relevant to Gohantomo.
6. **Volume reality check, from a real seller's own page.** The small Gumroad calisthenics programme at $12.99 shows **zero ratings**. `[inference]` Most small digital products in this space sell almost nothing. Kojo's 4,000+ customers took years and a full programme catalogue.

**Still not found (2026-11-05):** Sam Kojo's beginner-course price (checkout-gated); any individual revenue figure self-published by a tricking or parkour creator; any Jujimufu coaching or Patreon offer (jujimufu.com sells programmes and merch only — no coaching product is listed). ["Getting Rich from Parkour ft. STORROR, MOTUS & BREACH"](https://www.youtube.com/watch?v=jrJqMMX9HEM) remains the best lead and is nominated for transcription.

### 3.3 Patreon / membership benchmarks — mostly unreachable from here

I could not get patron counts. `patreon.com/storror` and `patreon.com/jujimufu` both return **HTTP 403** to this cloud IP. Graphtreon creator pages for Storror and Jujimufu return **404**, and [graphtreon.com/patreon-creators](https://graphtreon.com/patreon-creators) loads its rows via JavaScript, so the table came back with headers only (columns: Paid Members, Earnings, Per patron, Days Running, Launched; filters at 1+/10+/30+/100+/300+ paid members). **No patron counts verified. Marked open.**

What I *can* give you instead is better than a Patreon estimate, because it is the real listed price of the two memberships that matter in your niches:

| Membership | Tiers (2026-11-05) | Structure worth copying |
|---|---|---|
| **STORROR+** | £6.99/mo · £17.99/3mo · £69.99/yr | Three durations of **one** tier. No tier ladder at all. Quarterly is pushed as "Most Popular" and reframed as "about 20p a day". |
| **Kojo's Trick Lab** | $15 / $50 / $60 per month (and ×8 for annual) | Three tiers of **one** duration, differentiated only by **how much of the coach's attention you get** (0 / 15 / 50 clip reviews). No trial. |

`[inference]` Kojo's ladder is the one to copy. Price the content at the floor, price your attention at the top, and let the tiers do the segmenting.

## 4. The coaching question, answered directly

**Short answer: yes — coach, and sell it as clip review and in-person hours. Do not build a content library, and do not price it like one.**

The evidence, and what it rules out:

**4.1 What the ceiling is.** The only live, public, tiered price list in tricking is Kojo's: **$15/mo for all his content, $50/mo for content + 15 clip reviews, $60/mo for content + 50 reviews**. That is your market's answer to "what is an online tricking coach worth per month": **$50–60**, and the $35–45 of it above the library price is *entirely* payment for a qualified human watching your video. You are nationally ranked 8th and have coached 100+ students. You can sell the $45 part. You cannot out-library a man with 4,000+ paying customers and a full programme catalogue.

**4.2 Why 6,000 followers is the constraint, not the price.** No source gives a follower-to-buyer rate for coaching, and I looked hard — see 4.5. The closest hard benchmarks are from consumer subscription apps, where the funnel is measured properly: RevenueCat's *State of Subscription Apps 2025* reports **day-35 download-to-paid medians of 2.7% for high-priced apps and 1.5% for low-priced apps**, with North America reaching **5.5% at the upper quartile and 10.5% at P90** ([RevenueCat](https://www.revenuecat.com/state-of-subscription-apps-2025/)). Those are people who already installed something — far warmer than a follower. `[inference]` A follower converts worse than an installer, so treat 1–3% of 6,000 as a generous *lifetime* ceiling on people who ever buy anything: **roughly 60–180 buyers, spread over years**. At Kojo's Review price that is a real side income and not a job. Plan for that shape.

**4.3 And most of your 6,000 are the wrong people.** This is the part the view count hides. Your audience was assembled by a crash video, and the one self-reported teardown I have on view-to-follow found the lowest conversion on the account with no clear promise, with one entertainment video converting at **0.01% view-to-follow** (self-reported, [chaotic-creator, 2025-05-30](https://chaotic-creator.beehiiv.com/p/1m-views-on-8-videos-exposing-what-i-did)). The same source found that videos showing a *system* converted better than entertainment. `[inference]` The slice of your 6,000 who want to be coached is small; content aimed at learners is how you grow it. That is the real reason to start with coaching — it is the only revenue line that works on a *small, correctly-selected* audience.

**4.4 Local in-person vs an online product — a direct answer.** Evidence here is thinner than on prices, so I'll separate what is sourced from what I am concluding.

*Sourced:* in-person movement coaching is sold in blocks, not monthly content subscriptions — **$79+GST and up per camp** ([FitSet Ninja](https://fitsetninja.com/tricking-summer-camps)), **$220.50 per season** ([Laws of Motion, 2023-24](https://www.amilia.com/store/en/laws-of-motion/shop/activities/5088126)), **$319+GST early-bird half-day** for a tricking camp (figure from a search snippet for [Canadian Dance Company](https://www.canadiandancecompany.com/); its page 404'd, so `(unverified)`). Online, the whole verified range is $6.99–$60/mo.

*My conclusion `[inference]`:* **local in-person wins on money per hour and does not depend on your follower count at all; online clip review wins on leverage and is the only thing your 6,000 can buy.** A local class needs 10–30 humans within driving distance; your 6,000 are scattered across the world, so short-form is a *bad* local-acquisition channel and a *good* credibility channel — the ranking and the landed double-back are what make a parent or a gym say yes, and they work whether the follower count is 6,000 or 600. Meanwhile the online tier monetises the global slice. Run both: **in-person for cash now, online clip review for leverage later.** And note the mortality risk: Loopkicks' online tricking coaching business is a parked domain today. A local reputation does not evaporate the same way.

**4.5 What I could not find, and I tried.** No creator in tricking, parkour, calisthenics or martial arts publicly states a short-form-to-paid-coaching conversion rate. Nobody publishes list opt-in rates or link-in-bio click-through for these niches with a verifiable source. The reachable material was vendor and agency blogs quoting each other with no methodology — one modelled a "5% Reel-to-client rate" as a chain of assumed stage rates, another asserted link-in-bio traffic at 1.5–3% and keyword-DM funnels at 12–25%, a third claimed email converts "10–40x" social. **I am deliberately not putting those in a table. They are unsourced illustrations, and citing them would make this report look stronger than it is.** Direct creator sources were also unreachable from this environment: `www.reddit.com` and `old.reddit.com` are both blocked to the fetch tool, the redlib mirror used earlier was asleep, Patreon returns 403, and the session's web-search budget was exhausted (200 calls, shared across all agents). **This gap stays open.** The honest instruction remains: measure your own funnel, because nobody will hand you the number.

## 5. Mapping to the three brands

**taita.del (tricking).** Order, now with prices attached:
1. **In-person coaching and small group sessions, locally.** Highest rate per hour, works at any follower count, and your ranking plus your 100+ students are the whole sales pitch. Comparable in-person products are sold as **$79–$320 blocks**, not monthly.
2. **Online clip review, priced $40–60/month.** This is a direct copy of Kojo's Review tier ($50/mo for 15 clips, $60/mo for 50) — his pricing is your market validation, and his tier chart tells you reviews are worth 3–4x content. Cap the number of clients; it is your hours.
3. **A one-off beginner programme, $20–40.** Only once the same DM question has been answered ten times. Price it where the whole niche prices one-off programmes: **Jujimufu $20–40, Jesse Enkamp EUR 49, small Gumroad programmes $12.99.**
4. **Skip the video library and skip merch.** Heria with 1.6M installs is estimated under $10k/mo; Storror at ~11M subs charges £6.99. You will not win there.
- 6 months `[inference]`: pins and series in place, a DM keyword offer, a handful of paying clients, local sessions running, a waitlist for the programme. Income: small and uneven. I still will not put a figure on it, because no source supports one.
- 12 months `[inference]`: the $40–60 review tier open with a capped roster; the $20–40 beginner programme live; per-trick content feeding both.

**taita.talks (startup / life).** Unchanged: at ~100 followers there is nothing to monetize directly. Its job is to be the voice that sells the other two and to build the list. `[inference]`

**ごはんとも (Gohantomo).** See section 7 — the app benchmarks are now real numbers, and they change the plan.

## 6. The funnel from 30 seconds to a purchase

The evidence here did not improve, and I am not going to dress it up. What stands:
- **DM keyword funnel** for martial arts: video, keyword CTA kept constant for 30 days, a four-step DM to book a trial ([Real Combat Media](https://realcombatmedia.com/2026/02/how-to-get-clients-for-your-mma-courses-from-social-media/)). Concrete mechanics, **no conversion data**.
- **Free asset before the paid one**: the chaotic-creator account used a free template as the CTA ahead of the course, and reports that some non-followers still joined the email list (self-reported).
- **Free first, then paid** is the actual shape of every verified operator: Hybrid Calisthenics (free course and free app core → $14.99/mo and $29.99 book), Heria (free YouTube → $11.99–$18.99/mo apps), Kojo (free YouTube → $15–60/mo), Storror (free YouTube → £6.99/mo).
- **Nobody runs a trial.** Kojo's plans endpoint shows `trialPrice: null` on all six plans. STORROR+ has no trial tier. `[inference]` In this niche the free YouTube/TikTok content *is* the trial, so a separate trial is redundant. Don't build one.
- Funnel leaks `[inference]`: sending the viral audience to a coaching link (wrong people), a bio with no clear next step, a link-in-bio with five options, a DM offer nobody has seen in the videos.

**Your build, this week** (unchanged — it is still right, and still unvalidated by any published number):
1. One bio link to a single page: a free "first 3 tricks" checklist, plus coaching enquiry.
2. One keyword CTA ("SALTO"), same for 30 days, in the video and in the pinned comment.
3. Collect LINE or email for the free asset. Keep the English (del) and Japanese (Gohantomo) lists separate.
4. Weekly check: which video produced profile visits, follows and DMs. Repeat that format.

## 7. The app angle — real subscription benchmarks

This is now the best-evidenced section in the report, because app economics are measured properly and movement-creator economics are not.

### 7.1 What a solo founder should expect (RevenueCat, *State of Subscription Apps 2025*)

All figures below are quoted from [the report](https://www.revenuecat.com/state-of-subscription-apps-2025/), read 2026-11-05.

| Benchmark | Figure | Why it matters to Gohantomo |
|---|---|---|
| **Hard paywall vs freemium, download-to-paid** | **"we see 12.11% median conversion versus just 2.18% for freemium"** (attributed in the report to Hannah Parvaz) | A **5.6x** gap. This is the single biggest lever you control, and it is a paywall-design decision, not a growth decision. |
| Day-35 download-to-paid, by price point | **2.7% median for high-priced apps vs 1.5% for low-priced** | Charging more did not reduce conversion in the data. Pricing at あすけん's ¥580 is not automatically safer than pricing above it. |
| Download-to-paying, North America | **5.5% upper quartile, 10.5% at P90** | The realistic good outcome is single-digit percent of installs. Model your revenue on that, not on 20%. |
| Trial start rate | **6.2% median, 20.3% at P90** (Phil Carter) | If you run a trial, most installs never start it. |
| Health & Fitness **trial-to-paid** | **39.9% median, 68.3% top decile** | Once someone starts a trial in this category, it converts well. The leak is upstream. |
| Health & Fitness realised LTV | **$16.44 median after 1 month**; after 1 year, **$55.21 median for high-priced apps vs $8.08 for low-priced** | A payer is worth tens of dollars, not hundreds. Your CAC ceiling is brutal. |
| Retention at 12 months | **Annual plans 44.1%** (down from 47.1%); **monthly plans 17.0%** (down from 18.8%). Annual plans see a first-month cancellation spike **"often exceeding 30%."** Thomas Petit: **"on monthly plans, barely 10% of payers reach the second year."** | Push annual. The gap is 2.6x. |
| Asia-Pacific | **"Yearly subscriptions make up the largest share in Asia-Pacific (47%)"**; median LTV **near $35**; Google Play revenue per install **$0.35 median** | Japanese buyers already prefer annual. Lead with the annual plan. |
| New apps, first 2 years | **"nearly 20% reach $1,000 in revenue while 5% reach the $10,000 mark"**; the bottom 25% **"make no more than $19"** after year one; among apps that get there, **median 60 days to reach $1,000** | This is the honest base rate. 95% of new apps never see $10k *cumulative*. Being in the 20% is the first real goal. |
| Prices generally | **"median prices remained flat year-over-year"** | No pricing tailwind. |

`[inference]` Read together: ship a **hard paywall** (or a very tight free allowance), **lead with annual**, and treat ¥1,000+ as inside the normal range rather than a risk. The data says a hard paywall and a higher price are the two things that correlate with more money, and the freemium instinct is the expensive one.

### 7.2 Japanese calorie-app pricing (App Store Japan, read 2026-11-05)

| App | Developer | Price | In-app purchases (yen, verbatim) | Ratings |
|---|---|---|---|---|
| **あすけん** ([id687287242](https://apps.apple.com/jp/app/id687287242)) | asken inc. (Tokyo) | Free + IAP | プレミアムサービス（月額会員）**¥480**; プレミアムサービス 1ヶ月 **¥580**; 6ヶ月 **¥2,300**; 1年間 **¥4,400**. プレミアム**Plus** 1ヶ月 **¥980**; 6ヶ月 **¥3,900**; 1年間 **¥7,500**. The subscription box separately showed 1年間 at **¥3,980** with a trial label. | ~15万件 (≈150,000), 4.4 |
| **カロミル** ([id963055562](https://apps.apple.com/jp/app/id963055562)) | Life Log Technology, Inc. | Free + IAP | プレミアムプラン **¥480**; then **à-la-carte add-ons**: 食事提案 ¥360, 除脂肪コース ¥540, 応援プラン ¥300, PFCバランス達成状況 ¥300, 血圧管理（基本）¥240, 血圧管理（出力＋画像解析）¥480, 血糖値管理 ¥240, 曜日ごとカロリー設定 ¥300, メモ ¥120 | 4.6万件 (≈46,000), 4.5 |
| **YAZIO** JP ([id946099227](https://apps.apple.com/jp/app/id946099227)) | YAZIO GmbH | Free + IAP | ¥1,490 / ¥2,200 / ¥3,300 / ¥4,000 (YAZIO PRO entries); duration entries 3ヶ月 ¥2,900, 6ヶ月 ¥2,900, 12ヶ月 ¥2,900 / ¥4,900 / ¥5,900 / ¥10,800. **The App Store does not say which item is which plan, so do not quote a single YAZIO price.** | 5,991, 4.3 |
| **FiNC** | FiNC Technologies | **Could not verify.** `finc.com` serves only a company page with no pricing, `/apps` and `/premium` 404, and the App Store ID I tried 404'd. Consumer-subscription pricing **unverified — open.** | — | — |

**Corrections and confirmations to the earlier draft:**
- **あすけん's ¥580/month is confirmed**, but it is one of **seven** price points, not the price. The real floor is **¥480** and there is a **Plus** tier at **¥980/mo and ¥7,500/yr** — so the Japanese market already supports roughly double the headline price. That is a materially better fact than "~580 yen/month".
- The **14M figure is a company claim and carries no date**: asken.jp says 「これまでに1400万人以上があすけんを始めています」 — "over 14 million people have *started* using Asken so far", i.e. **cumulative starts, not active users** ([asken.jp](https://www.asken.jp/), read 2026-11-05). Don't repeat it as a user base.
- **あすけん runs a 7-day free trial**; its page says so explicitly. So in this market the incumbent *does* use a trial, unlike the movement creators in section 6.
- **カロミル sells à-la-carte features at ¥120–¥540** on top of a ¥480 base. `[inference]` That is an unusual and copyable structure: a cheap base plus small paid modules, which keeps the headline price below あすけん while raising ARPU on engaged users.

`[inference]` **Pricing conclusion for Gohantomo:** ¥480–¥580/month is the anchor the Japanese user has in their head, and ¥980/mo or ¥4,400–7,500/yr is already proven at the top end. Lead with an **annual** plan (APAC is 47% yearly; annual retains 44.1% vs monthly 17.0%), and do not undercut ¥480 — the RevenueCat price-point data says the cheaper apps converted *worse* and earned $8.08 vs $55.21 in year-one LTV.

### 7.3 Distribution, unchanged

Cal AI remains the model: ~250 influencers paid flat monthly fees ([Latka interview](https://getlatka.com/interviews/cal-ai-zach-yadegari-2025)), with 2025 revenue reported at $35M by Latka and $30M by [Summify](https://summify.io/discover/zach-yadegari-selling-cal-ai-for-millions-at-18-years-old-5fQ-Jy) `(unverified, differing)`. Growth came from paid creator volume then paid ads, not from one brand account. **Whether TikTok slideshows work in Japan: still not verified.** No Japanese calorie-app slideshow case study found. Run a small test rather than assume.

## Sources

Added or re-verified 2026-11-05:
- https://www.kojostricklab.com/ and its public plans endpoint https://www.kojostricklab.com/api/auth/available-packages
- https://sam-kojo-coaching.teachable.com/p/home , https://sam-kojo-coaching.teachable.com/p/tricking-for-absolute-beginners , https://sam-kojo-coaching.teachable.com/courses
- https://jujimufu.com/ , https://jujimufu.com/collections/programs
- https://www.inplay.org/so/r/santa-clara/providers/team-loopkicks/online-tricking-class (404 as of 2026-11-05); loopkicks.com redirects to https://strongdomains.com/domain/loopkicks.com
- https://app.thenx.com/upgrade , https://www.thenx.com/ , https://apps.apple.com/us/app/thenx/id1192413645 , https://apps.apple.com/us/app/heria-pro/id1356721066 , https://appgoblin.info/apps/1192413645
- https://www.hybridcalisthenics.com/app-info , https://apps.apple.com/us/app/hybrid-calisthenics/id6444292787 , https://shop.hybridcalisthenics.com/collections/all
- https://storrorplus.storror.com/ , https://apps.apple.com/us/app/id6744359541 , https://www.storror.com/collections/all
- https://jesseenkamp.gumroad.com/l/knx22 , https://calisthenicss.gumroad.com/l/Program
- https://fitsetninja.com/tricking-summer-camps , https://www.amilia.com/store/en/laws-of-motion/shop/activities/5088126
- https://www.revenuecat.com/state-of-subscription-apps-2025/
- https://apps.apple.com/jp/app/id687287242 (あすけん) , https://apps.apple.com/jp/app/id963055562 (カロミル) , https://apps.apple.com/jp/app/id946099227 (YAZIO JP) , https://www.asken.jp/
- https://graphtreon.com/patreon-creators (rows JS-only, no data extracted)

Carried over from the first pass:
- https://catarinamello.substack.com/p/stop-chasing-virality-and-do-this
- https://exposedbrickdc.substack.com/p/why-going-viral-isnt-the-goal
- https://chaotic-creator.beehiiv.com/p/1m-views-on-8-videos-exposing-what-i-did (published 2025-05-30)
- https://rosetta.to/u/vidiq/one-of-our-worst-videos-just-blew-up
- https://www.echotik.live/blog/why-are-my-tiktok-views-high-but-followers-low/ (search result only; fetch timed out)
- https://onlinemarketing.de/social-media-marketing/instagram-impressions-profiloptimierung-mit-plattformchef
- https://t3n.de/news/tipps-vom-profi-instagram-chef-mosseri-erklaert-wie-du-dein-profil-zum-hingucker-machst-1676863/
- https://ttcalculator.net/calculators/profile-visit-rate/
- https://printful.com/blog/tiktok-metrics
- https://www.youtube.com/shorts/mNMyfU8ZiEw
- https://axebps-redlib.hf.space/r/Tricking/comments/kms7sp/helpful_links_for_beginners_and_people_just
- https://apppricinglab.com/app/apple/1192413645
- https://www.builtbyfoundry.io/blog/chris-heria-thenx-heria-pro-calisthenics-app
- https://raptive.com/?p=6114
- https://sponsorradar.com/channels/storror
- https://www.youtube.com/watch?v=jrJqMMX9HEM
- https://karatebyjesse.gumroad.com/l/insider , https://karatebyjesse.com/host-seminar
- https://realcombatmedia.com/2026/02/how-to-get-clients-for-your-mma-courses-from-social-media/
- https://getlatka.com/interviews/cal-ai-zach-yadegari-2025
- https://summify.io/discover/zach-yadegari-selling-cal-ai-for-millions-at-18-years-old-5fQ-Jy
- https://markezine.jp/article/detail/46035

**Unreachable from this environment (recorded so nobody re-spends time):** www.reddit.com and old.reddit.com (blocked to the fetch tool); www.patreon.com/storror and /jujimufu (HTTP 403); graphtreon.com/creator/storror, /Storror, /storror-parkour, /jujimufu (404); web.archive.org (blocked); www.trickingmastery.com and www.aircirclesf.com (DNS — would need allow-listing in the session's network settings); masteringtricking.com (404); www.canadiandancecompany.com/tricking-camp (404); finc.com/apps and /premium (404). The session's 200-call web-search budget was exhausted.

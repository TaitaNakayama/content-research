# 09 — Instagram: ranking, follows-per-reach, and why 10M views bought you 6,000 followers

Written for Taita. Instagram only. Every claim has a link and a date. Where the date is missing from the source, I say so.

**Why this file exists:** the rest of this research leans on YouTube evidence. Press says your viral post — the failed triple-cork compilation — was on **Instagram** ([Midpen Post, 2024-05-17](https://midpenpost.org/2024/05/17/flipping-in-finesse-gunn-juniors-mindset-grows-through-tricking/)), so the YouTube yardsticks in file 02 are the wrong ruler. This file supplies the Instagram-native replacement.

**Access note:** Instagram is not reachable from the machine this was researched on — profile pages return a login wall, `yt-dlp` demands cookies, the public post embed is an empty JS shell. **Nothing in this file is measured from your account.** Everything is published sources about Instagram. Section 6 is the part that gets primary data, and only you can run it.

---

## 0. Solid vs unverified — read this first

### Solid (primary source, dated)

| Claim | Source | Date |
|---|---|---|
| Mosseri: "More important than watch time or like and comment counts is send rates… **the rate is more important than the count**… **sends per reach correlate more, in my experience, with overall reach than anything else.**" | [Social Media Today](https://www.socialmediatoday.com/news/instagram-chief-post-share-rates-key-driver-reach/716540/) | **2024-05-19** |
| Mosseri: "The top three signals that matter most for ranking are **watch time, likes and sends**"; watch "**average watch time, likes per reach, and sends per reach**"; "**likes are slightly more important for connected content, and sends are slightly more important for unconnected content**." | [Social Media Today](https://www.socialmediatoday.com/news/instagram-shares-algorithm-2025/738034/) | **2025-01-22** |
| Mosseri's four ranking principles: **originality, recency, "breaking content" (Instagram shows small creators' public posts to non-followers to gauge response), and bigger AI models**. Advice: optimise for "**engagement rates, as opposed to total views or likes**." Post as much as you can; use Trial Reels to test. | [Social Media Today](https://www.socialmediatoday.com/news/instagram-chief-shares-algorithm-insights-and-posting-tips/831326/) on Mosseri's four-part video series | **2026-09-24** (series posted Sept 2026) |
| Instagram, first-party: non-followers see a Reel first in "a small test audience"; best performers "reach progressively wider audiences"; signals named are **watch time, retention, shares, likes, comments** plus interest-based audience matching. Design intent: "level the playing field by distributing content based on its engagement." | [creators.instagram.com](https://creators.instagram.com/blog/helping-creators-of-all-sizes-break-through) | **2025-02-26** |
| Instagram, first-party: hook in the **first 3 seconds**; track **View Rate** = share of viewers who keep watching past 3s. **Trial Reels** post only to non-followers, and you can share to followers later. | same page | **2025-02-26** |
| Instagram, first-party Reels ranking signals in rough order: (1) your activity, (2) your history with the poster, (3) information about the reel — audio, visuals, popularity, (4) **information about the poster, "popularity measures such as follower count or engagement level"**. Reels get **less distribution** if low-resolution, **watermarked**, muted, bordered, mostly text, or already posted on Instagram. | [Mosseri, "Instagram Ranking Explained"](https://about.instagram.com/blog/announcements/instagram-ranking-explained) | **2023-05-31** |
| Reposts/aggregators: accounts that mostly post others' work are no longer recommended to non-followers; extended from Reels to photos and carousels. Credit alone does not make it original; "low-effort edits" (watermarks, speed changes, screenshots) do not count. Posts still reach existing followers. | [Social Media Today](https://www.socialmediatoday.com/news/instagram-updates-algorithm-to-benefit-original-creators/819016/), [Buffer](https://buffer.com/resources/instagram-algorithms/) | policy expanded **April 2026**; Buffer updated **2026-10-23** |
| Mosseri: "We want to create a platform that gives more distribution to the original content creator than to those who repost it." | quoted in [Buffer](https://buffer.com/resources/instagram-algorithms/) | quote **undated**; article 2026-10-23 |
| Mosseri: about **half of Instagram videos are watched without sound** → Reels need a visual hook. | Colin & Samir podcast, via [Buffer](https://buffer.com/resources/instagram-algorithms/) | quote **undated**; article 2026-10-23 |
| Hashtags: Mosseri has said hashtags **do not improve reach**; Instagram **capped hashtags at 5 per post** (down from 30). | Buffer attributes the cap to a third-party Threads post, not an Instagram source; secondary coverage dates the cap to **2025-12-18/19** ([Creator Lane](https://creatorlanehq.com/blog/instagram-5-hashtag-limit-2026), [Double Barril](https://doublebarril.com/how-to/social-media-hashtag-strategy/)) | cap **Dec 2025**; Mosseri's reach remark **undated**, one source puts it Feb 2025 |
| Non-follower share of Instagram **views** rose from **30% (2024) to 49% (end of 2025)**; FYP views went 31% → 58%; Instagram views up 27% in 2025. | [Dash Social](https://www.dashsocial.com/blog/non-followers-instagram-audience) (pub. 2026-06-10) and its [April 2026 press release](https://www.dashsocial.com/press-release/2026-social-media-benchmarks) | **2026** reports on **2024–2025** data |
| Reels reach rate (reach ÷ followers, per post) by account size: **1–5K = 9.78%**, **5–10K = 7.55%**, 100K–1M = 5.00%. Skip rate (swiped away in first 3s): **1–5K = 65.5%**, **5–10K = 65.3%**. Best length band **30–60s (5.60%)**; drops to 3.50% over 120s. Sample: **9,771,822 Reels**, brands 1K–1M followers, organic only, Jan–Jun 2026. | [Socialinsider](https://www.socialinsider.io/blog/instagram-reels-statistics/) | published **2026-06-24**, updated **2026-10-21** |

### Not verified — do not build on these

- **The "sends are 3–5x the weight of likes" multiplier.** Circulates widely. Mosseri only ever said "slightly more important." No primary source. Ignore it.
- **"Watch time is the #1 Reels ranking factor," confirmed by Mosseri in January 2026.** I found no such statement. The dated statements are May 2024 (sends per reach is the strongest correlate) and Jan 2025 (watch time, likes, sends as a trio). These two are in tension and Instagram has never published weights.
- **A 30.81% Reels reach rate.** Appears in several roundups with no traceable methodology. Socialinsider's measured figure for your size band is **7.55%**, four times lower. Use Socialinsider's.
- **Any published follows-per-reach benchmark with a real sample.** See §2 — it does not exist. What exists is derivable and anecdotal, and I present it as such.
- **Cover images, grid crop, caption length, alt text, trending audio** as reach or follow drivers on Instagram. I found **no Instagram-specific evidence** for any of them (§5). The caption-length studies that exist contradict each other and none is Reels-specific.
- **Whether a viral Reel's audience gets retargeted later.** No Instagram documentation, and the one case study with numbers says the opposite (§3).
- **The 5-hashtag cap's primary announcement.** Every route I tried led to secondary coverage or a Threads screenshot. Treat the cap as near-certain but the source as secondhand. Check your own composer: if it stops you at 5, that settles it.

---

## 1. What Instagram actually says ranks a Reel

**The short version, in Instagram's own words.** Distribution to non-followers is an **audition**. Instagram first shows a new Reel to "a small test audience that Instagram predicts will enjoy it"; the best performers "reach progressively wider audiences" ([creators.instagram.com, 2025-02-26](https://creators.instagram.com/blog/helping-creators-of-all-sizes-break-through)). Mosseri's Sept 2026 series calls this **"breaking content"** and frames it as deliberately favouring small creators ([Social Media Today, 2026-09-24](https://www.socialmediatoday.com/news/instagram-chief-shares-algorithm-insights-and-posting-tips/831326/)).

**Watch time vs sends vs likes.** The two dated primary statements do not agree, and you should know that rather than be told a clean answer:

- **2024-05-19** — Mosseri: "More important than watch time or like and comment counts is send rates… sends per reach correlate more, in my experience, with overall reach than anything else" ([link](https://www.socialmediatoday.com/news/instagram-chief-post-share-rates-key-driver-reach/716540/)). Note his own hedge: "in my experience."
- **2025-01-22** — Mosseri: the top three are watch time, likes and sends, measured as **average watch time, likes per reach, sends per reach**; likes count slightly more for people who already follow you, **sends count slightly more for people who don't** ([link](https://www.socialmediatoday.com/news/instagram-shares-algorithm-2025/738034/)).

**What you do with that:** both statements agree on **rates, not counts**, and both agree that **sends are the lever for non-followers**. You already have non-follower reach. So sends are not your bottleneck — you're clearly getting them, that's how 10M happened. Your bottleneck is downstream of reach entirely (§3).

**Does follower count matter for distribution?** Instagram's own 2023 explainer lists "popularity measures such as follower count or engagement level" as a Reels ranking input ([Mosseri, 2023-05-31](https://about.instagram.com/blog/announcements/instagram-ranking-explained)). But both the 2025-02-26 creators post and the Sept 2026 series describe the system as deliberately *not* gating on follower count — "level the playing field by distributing content based on its engagement," and small creators' posts shown to non-followers on purpose. Mosseri has also said smaller creators "haven't gotten their fair share of reach… and we want to change that" ([Social Media Today](https://www.socialmediatoday.com/news/instagram-algorithm-prioritize-original-emerging-creators/714777/)). Reconciling: follower count is a weak tiebreaker, not a gate. **6,000 followers is not what is limiting you.**

**Original vs reposted.** This one matters for you more than it looks. Since **April 2026**, accounts that mostly repost others' content are **not recommended to non-followers at all** — extended from Reels to photos and carousels ([Social Media Today](https://www.socialmediatoday.com/news/instagram-updates-algorithm-to-benefit-original-creators/819016/)). Also, from the 2023 explainer, Reels get **less distribution if watermarked** or "already posted on Instagram" ([link](https://about.instagram.com/blog/announcements/instagram-ranking-explained)). Practical: **never post a TikTok export with the TikTok watermark**, and never re-upload the same Reel. If you cross-post, export clean from the editor.

**Recency.** New in Sept 2026: recency is now one of the four named principles — the feed is "roughly in chronological order" ([Social Media Today, 2026-09-24](https://www.socialmediatoday.com/news/instagram-chief-shares-algorithm-insights-and-posting-tips/831326/)). This rewards cadence over perfection, and it is Mosseri's own stated reason for "post as much as you can."

**Mosseri's own advice on which metric to chase:** "engagement rates, as opposed to total views or likes" (2026-09-24). The head of Instagram is telling you to stop looking at your 10M.

---

## 2. The key number: Instagram follows-per-reach

**Stated plainly: there is no credible published Instagram follows-per-reach benchmark with a real sample and methodology.** I looked at Socialinsider, Metricool, Hootsuite, Later, Sprout, RivalIQ, Emplifi, Dash Social, Flick and Databox. Every large study measures reach rate, engagement rate or follower *growth* — none publishes follows ÷ reach. Dash Social's own blog (2026-06-10) even recommends tracking "follow rate per reach" and then does not report one.

So here is the best that exists, with every figure's provenance exposed. **Read the caveats; these are not equivalent to each other.**

| # | Figure | Follows per reach/view | What it actually is | Source, date |
|---|---|---|---|---|
| 1 | Databox medians: New Followers **11.5**, Reach **15,367.5**, Profile Visits **266** | **≈0.075%** follows/reach; **1.73%** profile visits/reach; **4.3%** follows/profile visit | **Derived by me** from three separate medians across 1,400+ business accounts — the medians are not paired, so treat as an order-of-magnitude anchor, not a rate. Closest thing to a real benchmark I found. | [Databox](https://databox.com/benchmarks/instagram-benchmarks), updated **2026-11-04** |
| 2 | Instagram's own showcase account @pov_husband: **1.2B views → 2M+ followers** in under a year | **0.167%** followers/view | First-party, but a hand-picked best case Instagram chose to publicise. Treat as an upper bound for a format that works. | [creators.instagram.com](https://creators.instagram.com/blog/helping-creators-of-all-sizes-break-through), **2025-02-26** |
| 3 | Sarah Townsend: one Reel, **10.6M views / 9.5M reach**, account **4,200 → 9,900** followers | **0.060%** follows/reach (0.054% per view) | Single self-reported case. **This is your exact situation and your exact number.** See §3. | [sarahtownsendeditorial.co.uk](https://www.sarahtownsendeditorial.co.uk/2022/06/viral-video-post-on-instagram-lessons-learned/), **June 2022** |
| 4 | AdAnt's own two Reels, 8 days apart, ~85K views each: **3 followers** vs **145 followers** | **0.0035%** vs **0.170%** | Self-reported, not controlled, confounded (account grew from ~100 to 4,000+ between them). But the **48x spread at identical view counts** is the point. | [adant.ai](https://adant.ai/guides/instagram-reels-views-but-no-followers), updated **2026-10-11** |
| 5 | Kapwing's viral **Trial Reel**: 1.4M views → **130 followers**, **8.6K profile visits**, 290 link taps | **0.0093%** follows/view; **0.61%** profile visits/view; **1.5%** follows/profile visit | Trial Reels are **100% non-followers** by design, so this is the pure cold-audience floor. | [Kapwing](https://www.kapwing.com/resources/instagram-trial-reels-study-what-we-learned-after-a-trial-reel-hit-1-million-views/), **2025-10-07** |
| 6 | Flick: Instagram "conversion rate" (new followers ÷ profile visitors) ≈ **13.5%** avg; ~18% Aug–Dec 2024, dropping to 13.49% Jan 2025 | **profile-visit→follow**, not per reach | 4,000–29,000 accounts per month. **No stated methodology**, and the page's own average contradicts its own table. Note this is a *different* funnel step. | [Flick](https://www.flick.social/learn/instagram-analytics-benchmarks/insights/conversion-rate/3-months), data to **Jan 2025** |
| 7 | Japanese practitioner benchmark: follows ÷ reach — **<0.1% very low, 0.3–0.5% average, ≥1.0% good, ≥2.0% very good** | stated as follows/reach | **No source, no sample, no methodology.** Uses the right formula, which is why I include it, but the levels are inconsistent with #1, #2 and #3 by 4–8x. Do not use as your target. | [note.com/nken0302](https://note.com/nken0302/n/n7a27734f32e2?hl=en), **2025-07-07** |

### What to conclude

**Your 0.06% is roughly the Instagram median for a one-hit viral Reel, not a catastrophic outlier.**

Set the numbers side by side: the Databox median across 1,400+ accounts implies **~0.075%** follows-per-reach. Sarah Townsend's 10.6M-view Instagram Reel converted at **0.060%**. Yours is **0.060%**. Instagram's own showcase account and AdAnt's best Reel both land at **~0.17%**.

So the honest read is:

1. **You are at or near the Instagram median. You are not 20x below par.** The realistic ceiling in the evidence is ~0.17%, so your gap to a genuinely good Instagram account is about **3x**, not the 20x that file 02's YouTube table implies.
2. **The benchmark you were measured against in file 02 was the wrong ruler** and it made your problem look like a persuasion catastrophe. It isn't. It's a structural problem with one-hit Reels (§3).
3. **A 3x gap is extremely winnable** — AdAnt got a 48x swing between two Reels on the same account eight days apart. The variance within an account dwarfs the variance between accounts.
4. **Stop using lifetime followers ÷ lifetime views.** Instagram gives you per-Reel **Follows** and per-Reel **Reach** natively (§6). Measure the real thing.

### Non-follower share of reach

- **49%** of all Instagram views came from non-followers by end of 2025, up from **30%** in 2024; FYP views 31% → 58% ([Dash Social](https://www.dashsocial.com/blog/non-followers-instagram-audience), pub. 2026-06-10). Dash's later 2026 Trends Report says **55%**; the gap is unexplained, so quote the range **49–55%**.
- Those are platform-wide averages, dominated by established accounts. **For a 6K account with viral Reels, expect far higher** — one agency reported a client month at **97%** non-follower reach ([Viterno](https://viternogroup.com/blog/instagram-reels-reach-non-followers), single client, not a benchmark), and AdAnt's non-converting Reel had **~96%** of views from Explore and the Reels tab. Your 10M was almost certainly **90%+ non-followers**. §6 tells you how to confirm it in your own app.
- Methodology warning on Dash Social: the data note reads "July 1, 2026 to December 31, 2025," which is impossible. Probably a typo for 2025. Vendor content, not independently verified.

### Your size band, for context (this one has a real sample)

Socialinsider, **9.77M Reels**, brands 1K–1M followers, Jan–Jun 2026 ([link](https://www.socialinsider.io/blog/instagram-reels-statistics/), updated 2026-10-21):

| Metric, 5–10K follower band | Value |
|---|---|
| Reels reach rate (reach ÷ followers, per Reel) | **7.55%** |
| Skip rate (swiped away within first 3s) | **65.3%** |
| Reels posted per month | **10** |
| Best-performing length | **30–60s (5.60% reach rate)**; >120s collapses to 3.50% |

Read that skip rate: **two-thirds of plays are gone in three seconds, and that is normal.** The implied average **View Rate is ~35%**. That is your bar in §6. Caveat: this is brand accounts, not creator accounts, and Socialinsider's own methodology note contradicts its tables on the 100K band.

---

## 3. Why a viral Reel fails to convert on Instagram, mechanically

### The mechanism, in order

1. **Reels distribution is almost entirely to non-followers, by design.** Instagram shows a new Reel to a small test audience of predicted-interested strangers, then widens it ([creators.instagram.com, 2025-02-26](https://creators.instagram.com/blog/helping-creators-of-all-sizes-break-through)). So a viral Reel is not "your audience watching you." It is **millions of strangers each seeing exactly one thing you made**, in a feed, between two other strangers' Reels.
2. **Nothing in that surface shows them your account.** They see a username and a caption. Following requires a deliberate detour: tap the handle, land on your profile, evaluate it, tap Follow. Kapwing's viral Trial Reel shows the funnel's shape: **1.4M views → 8.6K profile visits (0.61%) → 130 follows (1.5% of visitors)** ([Kapwing, 2025-10-07](https://www.kapwing.com/resources/instagram-trial-reels-study-what-we-learned-after-a-trial-reel-hit-1-million-views/)). **99.4% of people never even looked at the profile.** The profile grid is the landing page and almost nobody reaches it.
3. **The profile then has to answer one question: "will I get more of what I just watched?"** AdAnt calls this the **"Follow Promise"** — "People watched. They just didn't decide they wanted more" ([adant.ai, updated 2026-10-11](https://adant.ai/guides/instagram-reels-views-but-no-followers)). A crash compilation is a **closed loop**: the payoff is complete inside the video. There is no residual question your account answers. That is the single best explanation of your 0.06%.
4. **A viral Reel's audience is not retargeted later.** No Instagram documentation says it is, and the one case with numbers says the opposite. Sarah Townsend, after 10.6M views and 5,700 new followers: the spike "did not lift views or engagement on her other content… 'simply hasn't happened'," and follower numbers were then "decreasing at the same speed they're increasing" ([June 2022](https://www.sarahtownsendeditorial.co.uk/2022/06/viral-video-post-on-instagram-lessons-learned/)). **Treat viral reach as non-recurring.** It is a one-time coupon, and it expires.
5. **Audience drift makes it worse than neutral.** Townsend concluded her new followers wanted something other than what she posts, and suspected the algorithm was now showing her posts to them — i.e. the wrong audience actively degraded her later distribution. AdAnt names the same failure: "chasing unrelated viral content can attract an audience that diverges from the intended one." **This is the real cost of your crash compilation**: it may have loaded your follower graph with spectators who don't engage with tricking tutorials, which weakens the engagement-rate signal Mosseri told you to optimise.

### The "one-hit Reel" problem, stated as the diagnosis

Your 10M views and 6,000 followers are **not two facts in tension**. They are one fact: **you have one viral artefact and no account.** A crash compilation reaches spectators, pays off completely in 15 seconds, and leaves no question open. 0.06% is what that produces. Sarah Townsend ran the identical experiment on Instagram in 2022 with a 10.6M-view Reel on a ~4,000-follower account and got **0.060%**. That's not a coincidence; it's the rate for that shape of content.

### What converters did differently — Instagram cases with numbers

| Case | Numbers | What they did |
|---|---|---|
| **@pov_husband** (Instagram's own showcase) | Created April 2024; **1.2B+ views, 0 → 2M+ followers in under a year** = **0.167%** | A **named, repeating premise** in the handle itself. Every Reel is another episode of the same thing. The follow promise is in the username. [creators.instagram.com, 2025-02-26](https://creators.instagram.com/blog/helping-creators-of-all-sizes-break-through) |
| **AdAnt Reel B** | 85,126 views → **145 followers** (**0.170%**) vs Reel A's 86,570 → **3** (0.0035%) | Reel B used a **recurring character** ("the bunny couple") the audience could expect again. Note Reel B had *worse* watch time (9s vs 18s) and *worse* skip rate (46% vs 19%) and still converted **48x better** — because like rate was 6.9% vs 0.8% and share rate 4.5% vs ~0%. **Retention did not predict follows. Resonance did.** [adant.ai, updated 2026-10-11](https://adant.ai/guides/instagram-reels-views-but-no-followers) |
| **Sarah Townsend** (the anti-case) | 10.6M views, 9.5M reach, 4,200 → 9,900 (**0.060%**), then followers bleeding at the rate they arrived | One-off, topic unrelated to her account. No repeating premise, no profile answer. [June 2022](https://www.sarahtownsendeditorial.co.uk/2022/06/viral-video-post-on-instagram-lessons-learned/) |

**The pattern across all three: the converters had a named, repeating thing. The non-converters had a great video.** This is the same conclusion file 01 reached from YouTube evidence, and it is the one cross-platform read that survives — but now it has Instagram evidence behind it, including Instagram's own showcase account.

### Trial Reels: the one Instagram feature built for your exact problem

**Trial Reels post only to non-followers**, and you can "share to everyone" later ([creators.instagram.com, 2025-02-26](https://creators.instagram.com/blog/helping-creators-of-all-sizes-break-through); mechanics via [Kapwing, 2025-10-07](https://www.kapwing.com/resources/instagram-trial-reels-study-what-we-learned-after-a-trial-reel-hit-1-million-views/)): toggle **Trial** on the last screen before publishing; analytics ~24h later under the **Trial Reels** label in your Reels grid; up to **20/day**; cannot be promoted as ads. Mosseri named them in the Sept 2026 series as the way to test ideas ([Social Media Today, 2026-09-24](https://www.socialmediatoday.com/news/instagram-chief-shares-algorithm-insights-and-posting-tips/831326/)).

Kapwing's caveats, which are real: in their small A/B (2 Reels, 4 uploads, 10 days) Trial Reels got more views (2,258 vs 949 on one) but **worse engagement rates**, and they conclude reach "did not reliably translate into engagement, follows, or conversions." Trend-based content did better as Trial Reels; product-focused content did better as regular Reels.

**Why you should use them anyway:** a Trial Reel is a **pure non-follower follows-per-reach measurement with no contamination from your existing 6,000**. That is exactly the number you need, and nothing else in Instagram gives it to you cleanly. Run your next five format experiments as Trial Reels, compare **Follows ÷ Reach** across them, and promote the winner to everyone.

---

## 4. Instagram profile conversion mechanics

**Honest framing first: this section is the weakest-evidenced in the file.** I found no Instagram-specific controlled evidence that any profile element raises follow rate. What exists is (a) mechanics documented by Instagram or reliably reported, and (b) practitioner consensus. I label which is which. Given Kapwing's funnel — **0.61% of viewers reach the profile, 1.5% of those follow** — the profile is a 1.5% → 3% lever, not a 10x one. The content decision in §3 is the 10x lever. Don't spend a week on your bio.

### Mechanics (documented)

| Element | What's actually true | Source |
|---|---|---|
| **Pinned posts** | You can pin **3** posts or Reels to the top of your grid. They sit directly under bio and Highlights. **They are ordered by when you pinned them, most-recently-pinned first** — so to control left-to-right order, unpin all three and re-pin in reverse. For a carousel, the grid shows slide 1 regardless of what was on screen when you pinned. | [Social Media Examiner](https://www.socialmediaexaminer.com/instagram-marketing-how-to-pin-posts-and-reels-to-a-profile/), [heymark.ai](https://heymark.ai/en/guides/instagram-pinned-posts/) — secondary; verify in-app |
| **Name field** | The bold line above your bio. **It is searchable, it allows spaces, and it is the main searchable profile element** — unlike the bio, which multiple guides say carries less search weight. Character limit disputed (30 vs 64). | [SEO Sherpa](https://seosherpa.com/instagram-search-results/), [Jeff Bullas](https://www.jeffbullas.com/thread/how-does-instagrams-keyword-search-work-and-how-can-i-rank-higher/) — SEO blogs, **no Instagram documentation found** |
| **Reels tab vs grid tab** | Separate tabs exist. **Which one a profile visitor lands on, and whether that affects follow rate, is undocumented.** I found nothing. | — |
| **Highlights** | Sit above the grid, persist indefinitely. No conversion evidence found. | — |

### What practitioners say drives the follow (treat as opinion, not data)

The most coherent account is the Japanese Instagram analyst at [note.com/nken0302 (2025-07-07)](https://note.com/nken0302/n/n7a27734f32e2?hl=en), whose stated reasons a viral post fails to convert are: the content is informational and "doesn't create interest in the person posting"; the profile lacks a unified theme so visitors aren't motivated; covers are cluttered so the account reads as a media outlet rather than a person. His fixes: a trustworthy **face** as the profile picture; **covers that convey a worldview**; a bio that states **who you are and what you're good at**; organised Highlights; **post yourself at least weekly**. No data behind any of it.

AdAnt's list is the same idea: **one-off content with no recurring theme, a profile that looks unrelated to the Reel, and reach from outside the target market** ([updated 2026-10-11](https://adant.ai/guides/instagram-reels-views-but-no-followers)).

### What I'd actually do on `taita.del` — opinionated

The profile has to answer "will I get more of what I just watched?" in about two seconds, mostly from **three pinned Reels and one name line**. Your three pins are the whole argument:

1. **Pin the crash compilation** — the thing they just watched, so the profile confirms they're in the right place.
2. **Pin the landing** — the payoff. This converts the closed loop into an open one: *there's an arc here and it's still going.*
3. **Pin one teaching Reel** — proves the account is a repeating thing, not two lucky videos. This is the slot that creates the follow promise.

Pin in order 3 → 2 → 1 so the crash ends up leftmost.

**Name field** (searchable, so put the search terms here, not just your name): something like `Taita · Tricking` — the word a stranger would type. Your handle `taita.del` contains no searchable noun at all, which means you are currently invisible to anyone searching "tricking."

**Bio**: state the credential and the promise, since both the Japanese analyst and AdAnt converge on "who you are + what you're good at." You have unusually strong credentials for this niche — **8th nationally in 2025, 100+ students coached** — and a named arc (**failed triple cork → landed it → next trick**). One line each.

All of this is **[inference]** from practitioner consensus. None of it is measured. The way to find out whether it worked is §6: **Profile visits** and **Follows** before vs after.

---

## 5. Instagram Reels packaging — what holds up and what doesn't

**Most of what gets said about Reels packaging has no Instagram evidence behind it.** Here is the split.

### Holds up (primary, dated)

| Item | Evidence |
|---|---|
| **Hook in the first 3 seconds; track View Rate** = share who keep watching past 3s. | Instagram, first-party, [2025-02-26](https://creators.instagram.com/blog/helping-creators-of-all-sizes-break-through) |
| **The hook must work on mute.** ~half of Instagram videos are watched without sound. | Mosseri on Colin & Samir, via [Buffer](https://buffer.com/resources/instagram-algorithms/) (quote undated, article 2026-10-23) |
| **No watermarks. No low resolution. No mostly-text Reels. No bordered video. Never re-post the same Reel.** All explicitly reduce distribution. | Instagram, first-party, [2023-05-31](https://about.instagram.com/blog/announcements/instagram-ranking-explained) |
| **30–60s is the best-performing length band** (5.60% reach rate); under 30s = 5.20%; over 120s = 3.50%. | [Socialinsider](https://www.socialinsider.io/blog/instagram-reels-statistics/), 9.77M Reels, Jan–Jun 2026 |
| **Audio is a named ranking input** ("information about the reel: audio, visuals, and popularity"), and predicted "visit the audio page" is one of the predictions Instagram makes. | Instagram, first-party, [2023-05-31](https://about.instagram.com/blog/announcements/instagram-ranking-explained) |
| **Hashtags do not improve reach; cap is 5.** | Mosseri remark undated (one source says Feb 2025); cap reported **2025-12-18** ([Creator Lane](https://creatorlanehq.com/blog/instagram-5-hashtag-limit-2026)). Secondary sourcing only. |
| **Originality**: edits need meaningful addition — commentary or new context. Credit is not enough. | [Social Media Today](https://www.socialmediatoday.com/news/instagram-updates-algorithm-to-benefit-original-creators/819016/), April 2026 policy |

### Could not verify — I am not going to make something up

- **Cover images and grid crop.** Instagram lets you choose both. **I found zero Instagram-specific evidence that either affects reach or follow rate.** The only argument for them is the Japanese analyst's claim that cluttered covers make an account read as a media outlet rather than a person ([note.com, 2025-07-07](https://note.com/nken0302/n/n7a27734f32e2?hl=en)) — a profile-coherence argument, not a distribution one. **[inference]** That argument is plausible for the pinned three, where a visitor is actively evaluating you, and worthless for Reels in the feed, where the cover is never shown. So: set covers deliberately on your three pins, ignore covers everywhere else.
- **Caption length.** The studies contradict each other flatly. Socialinsider (9.1M posts, Jan–Jul 2023) found under 30 words best; Mention found 1–20 characters best; a July 2026 study of 4,408 posts found **301–800 characters** best (4.2% median engagement); Instapect (1,763 posts) found caption length moved engagement by **4% or less** (all via [Buzzvoice](https://buzzvoice.com/blog/how-long-can-instagram-captions-be) and [Socialpilot](https://www.socialpilot.co/blog/ideal-social-media-caption-length)). **None is Reels-specific.** The honest read is that caption length is a near-zero lever and the published spread is noise. The hard limit is 2,200 characters, and feed truncation is somewhere around 125 characters — so the only thing that matters is that **your first ~125 characters carry the point**.
- **On-screen text conventions for Reels.** No Instagram evidence found. Note the real constraint from the 2023 explainer: a Reel that is **"mostly text"** gets *less* distribution, so on-screen text is a tool with a documented downside if overused.
- **Alt text.** No evidence it affects reach or follows on Instagram. Do it for accessibility; don't expect distribution from it.
- **Trending audio.** Only low-authority sources treat it as a factor, and they call it secondary at best. Instagram's own documentation names audio as *an input*, not trending audio as *a boost*. **For you there's a specific reason to be careful:** your content is movement, and the sound is part of the payoff (impact, landing, the audible crunch of a failed cork). **[inference]** Mosseri's own point that half of viewers are on mute cuts both ways — the visual must stand alone, but don't throw away original audio for a trending track that adds nothing.

### What to change on `taita.del`'s packaging

1. **Clean exports, no watermarks, never re-upload.** Documented distribution penalty. Free to fix.
2. **Aim 30–60s.** You've probably been posting shorter. The measured band says 30–60s reaches more.
3. **First 3 seconds must read on mute.** For tricking that's easy and it's your advantage: the frame is already a person mid-air. Start mid-action, not with a title card.
4. **Up to 5 hashtags, for classification, expecting no reach from them.**
5. **Stop optimising captions.** Put the point in the first 125 characters and move on.
6. **Set covers only on your three pinned Reels.**

---

## 6. Your 15-minute Instagram Insights checklist

This is the only way to get primary data about your account — nothing in this file is measured from `taita.del`. Metric names below are **Instagram's own labels**, confirmed against Instagram's Help Center and Meta's docs ([help.instagram.com/202865988324236](https://help.instagram.com/202865988324236/), [Meta developer docs on Instagram media insights](https://developers.facebook.com/documentation/instagram-platform/reference/instagram-media/insights), [Meta "Introducing Views"](https://creators.facebook.com/introducing-views-to-simplify-content)). Instagram's definitions, as documented:

- **Views** — the number of times your Reel **starts to play or replay**. Replays count. (This replaced "Plays.")
- **Initial views** — first play in a Reel session, excluding replays.
- **Reach / Viewers** — **unique accounts** that saw it at least once. Estimated.
- **Watch time** — total time your Reel was played, **including replays**.
- **Average watch time** — Watch time ÷ **initial views**. (Meta is renaming these to "Minutes Viewed" / "Average Minutes Viewed," so check which label your app shows.)
- **Follows** — "how many accounts started following you **as a result of viewing your reel**." This is the metric this entire research project has been trying to estimate. It is sitting in your app.
- **View rate** — share of viewers who keep watching **past 3 seconds** ([Instagram, 2025-02-26](https://creators.instagram.com/blog/helping-creators-of-all-sizes-break-through)).
- **Skip rate** — share of views swiped away in the first 3s (Meta marks this "in development," so it may not appear).
- **Profile activity** — actions on your profile after engaging: **profile visits**, follows, link taps.
- **Views over time** — splits a Reel's views into **followers vs non-followers** (added Jan 2025).

**Caution:** account-level Insights only go back **90 days**; per-post Insights go back **2 years**. Your viral Reel is older than 90 days, so pull it from the **post's own** Insights, not the account view. Export the numbers to a note now, because they age out.

### Run this (15 minutes)

**Step 1 — the viral Reel, from its own Insights.** Open it → View insights → tap into each section. Record: **Views, Reach (Viewers), Views over time split (followers vs non-followers), Average watch time, View rate, Likes, Sends/Shares, Saves, Comments, Profile visits, Follows.**

**Step 2 — your last 10 Reels.** Same fields. Note which were Trial Reels.

**Step 3 — compute three rates per Reel.** Instagram doesn't show these; do the division yourself:

- **Follows ÷ Reach** (this is the number)
- **Profile visits ÷ Reach**
- **Sends ÷ Reach** (Mosseri's named reach driver)

### Diagnosis table — if this number is X, do Y

| Metric | Your reading | What it means | Do this |
|---|---|---|---|
| **Non-follower share of views** (Views over time) | **>85%** | Normal for your situation; distribution is working. 49–55% is the platform average ([Dash Social](https://www.dashsocial.com/blog/non-followers-instagram-audience)), small viral accounts run far higher. | **Nothing.** Reach is not your problem. Stop trying to fix it. |
| | **<50%** | You're mostly reaching your own 6,000. Reels auditions aren't passing. | Check View rate and Sends ÷ Reach below; post more often (recency is a named 2026 principle). |
| **View rate** | **>35%** | At/above the measured average — Socialinsider's 5–10K band skips **65.3%** in the first 3s, implying ~35% view rate ([link](https://www.socialinsider.io/blog/instagram-reels-statistics/)). | Hook is fine. Leave it alone. |
| | **<30%** | First 3 seconds are failing, probably on mute. | Start mid-action; no title cards; no "hey guys." |
| **Average watch time** | vs Reel length | Instagram names watch time a top-3 signal (2025-01-22). But note AdAnt's Reel with **18s** average watch time got **3 followers** and the one with **9s** got **145**. | **Do not optimise this for follows.** It drives reach, which you already have. |
| **Sends ÷ Reach** | **top quartile of your own Reels** | Mosseri: "sends per reach correlate more… with overall reach than anything else" (2024-05-19). | This is your reach engine. Note which Reels do it and why. |
| | **~0%** | AdAnt's non-converting Reel had ~0% share rate; its converter had **4.5%**. | End on a sendable line ("send this to someone who keeps bailing on their cork"). |
| **Profile visits ÷ Reach** | **<0.6%** | Kapwing's viral Reel: **0.61%** ([link](https://www.kapwing.com/resources/instagram-trial-reels-study-what-we-learned-after-a-trial-reel-hit-1-million-views/)). Below that, the Reel gives nobody a reason to look you up. | The Reel is a closed loop. Leave a question the account answers. |
| | **>1.7%** but Follows still low | Databox median profile visits/reach is **1.73%** ([link](https://databox.com/benchmarks/instagram-benchmarks)). People ARE visiting and leaving. | **The profile is the bottleneck.** Fix the three pins and the name field (§4). |
| **Follows ÷ Profile visits** | **<1.5%** | Kapwing's viral Reel converted visitors at **1.5%**; Databox median implies **~4.3%**; Flick's (weakly sourced) all-account average is **13.5%**. | Profile fails the "will I get more of this?" test. §4. |
| **Follows ÷ Reach** | **<0.03%** | AdAnt's dud: **0.0035%**. Dead. | The content shape cannot convert. Change the format, not the edit. |
| | **~0.06%** | **Your current number**, and exactly Sarah Townsend's 10.6M-view Instagram Reel ([link](https://www.sarahtownsendeditorial.co.uk/2022/06/viral-video-post-on-instagram-lessons-learned/)). Median-ish, and the signature of a one-hit Reel. | Build the repeating thing (§3). |
| | **>0.17%** | At the ceiling in the evidence — AdAnt's best Reel (0.170%) and Instagram's own @pov_husband (0.167%). | **Found your format. Make 20 more of exactly this.** |

### Then run the real experiment

Post your next **five** format experiments as **Trial Reels** (Trial toggle on the last screen before publishing; up to 20/day; analytics ~24h later under the Trial Reels label). They go **only to non-followers**, which gives you an uncontaminated **Follows ÷ Reach** per format. Compare the five. Share the winner to everyone, then make twenty of it.

That single test answers the question this entire research project has been circling, with your own data, in about two weeks.

---

## 7. Corrections to the rest of this research

The earlier reports are good but they benchmark an Instagram problem with YouTube instruments. Specific corrections:

**1. The 0.06% benchmark and the 15-channel table in `02_taita_del_tricking.md` §3.1 must not be read as an Instagram verdict.**
That table is lifetime YouTube subscribers ÷ lifetime YouTube views for 14 channels, and it concludes your 0.06% is "the worst number in the set." **Against Instagram data it is roughly the median.** Databox's medians across 1,400+ accounts imply **~0.075%** follows-per-reach ([updated 2026-11-04](https://databox.com/benchmarks/instagram-benchmarks)); Sarah Townsend's 10.6M-view **Instagram** Reel converted at **0.060%** ([link](https://www.sarahtownsendeditorial.co.uk/2022/06/viral-video-post-on-instagram-lessons-learned/)). The realistic Instagram ceiling in the evidence is ~0.17%. **Your gap to good is about 3x, not 20x.** The file's own caveat (that the ratio partly measures format) understates the problem: it is also the wrong platform, and the two formats count views differently, which makes the comparison arithmetic unsound rather than merely noisy.

**2. Do not conclude "you are failing at the format with the worst conversion economics."**
That conclusion rests on comparing YouTube Shorts-heavy channels to YouTube long-form instructional channels. It says nothing about Instagram Reels, where Instagram's own showcase account hit **0.167%** on 1.2B views of short-form ([creators.instagram.com, 2025-02-26](https://creators.instagram.com/blog/helping-creators-of-all-sizes-break-through)). **Short-form on Instagram converts fine when it has a repeating premise.** The variable is the repeating premise, not the format length.

**3. Sam Sulek's 1.21% and THENX's 1.10% are not targets for `taita.del`.**
Those are YouTube subscribers ÷ YouTube views on long-form channels. Setting them as a bar for Instagram Reels would have you chasing a 20x improvement that nothing in the Instagram evidence suggests is reachable. **Your Instagram target is 0.17%**, and you should measure it as per-Reel **Follows ÷ Reach** from Insights, not lifetime ratios.

**4. Paddy Galloway's VVSA findings (file 01) do not transfer.**
YouTube Shorts viewed-vs-swiped-away thresholds (60% floor, 70–90% for best performers) are a 2023 YouTube study. Instagram's equivalent is **View rate** and **Skip rate**, and the measured Instagram numbers are very different: the 5–10K band skips **65.3%** in the first 3 seconds ([Socialinsider, Jan–Jun 2026](https://www.socialinsider.io/blog/instagram-reels-statistics/)). Don't apply YouTube thresholds to Instagram's metric.

**5. Galloway's "likes/shares/comments showed no strong relationship with performance" is specifically wrong for Instagram.**
Mosseri has said the opposite twice, on the record: sends per reach is the strongest correlate with reach in his experience ([2024-05-19](https://www.socialmediatoday.com/news/instagram-chief-post-share-rates-key-driver-reach/716540/)), and watch time, likes and sends are the top three ([2025-01-22](https://www.socialmediatoday.com/news/instagram-shares-algorithm-2025/738034/)). File 01 flags this tension already; this file resolves it: **on Instagram, sends matter, and they matter as a rate.**

**6. "Retention predicts follows" is contradicted by the one Instagram A/B with numbers.**
AdAnt's higher-retention Reel (18s average watch time, 19.2% skip rate) got **3 followers**; the lower-retention one (9s, 46.1% skip) got **145** — because like rate was 6.9% vs 0.8% and share rate 4.5% vs ~0% ([updated 2026-10-11](https://adant.ai/guides/instagram-reels-views-but-no-followers)). **On Instagram, retention buys reach; resonance buys follows.** They are different problems and you have already solved the first one.

**7. The "0.5–3% follow rate" folklore in file 01 §6 should be dropped entirely.**
Its source gave no data, and the only Instagram figures with a stated formula are the unsourced Japanese practitioner levels (0.3–0.5% "average") which are **4–8x above** every measured Instagram figure I could find ([note.com, 2025-07-07](https://note.com/nken0302/n/n7a27734f32e2?hl=en)). Quoting that as a target would set an unreachable bar.

**8. One cross-platform conclusion survives, and is now stronger.**
File 01's "viewers need a named, repeating thing to follow" and file 02's recurring-series recommendation hold up on Instagram evidence: Instagram's own showcase account puts the premise **in the username** (@pov_husband, 0 → 2M in under a year), and AdAnt's 48x conversion swing came from a recurring character. Keep that recommendation. It is the one thing in the earlier files that Instagram data independently confirms.

**9. Add to file 02's "checks you can do in 10 minutes."**
It asks for "share of views from non-followers" and "follows per 1,000 views" generically. On Instagram the exact labels are **Views over time** (followers vs non-followers split), **Follows**, **Profile visits**, **View rate**, **Average watch time** and **Sends**. §6 above replaces that checklist with the Instagram-native version, including the 90-day expiry warning: **pull your viral Reel's numbers from the post's own Insights before they are unreachable.**

---

## Sources

Instagram / Meta first-party:
- https://about.instagram.com/blog/announcements/instagram-ranking-explained (Mosseri, 2023-05-31)
- https://creators.instagram.com/blog/helping-creators-of-all-sizes-break-through (2025-02-26)
- https://help.instagram.com/202865988324236/ (Reels insights)
- https://developers.facebook.com/documentation/instagram-platform/reference/instagram-media/insights
- https://creators.facebook.com/introducing-views-to-simplify-content

Mosseri reported, dated:
- https://www.socialmediatoday.com/news/instagram-chief-post-share-rates-key-driver-reach/716540/ (2024-05-19)
- https://www.socialmediatoday.com/news/instagram-shares-algorithm-2025/738034/ (2025-01-22)
- https://www.socialmediatoday.com/news/instagram-chief-shares-algorithm-insights-and-posting-tips/831326/ (2026-09-24)
- https://www.socialmediatoday.com/news/instagram-updates-algorithm-to-benefit-original-creators/819016/
- https://www.socialmediatoday.com/news/instagram-algorithm-prioritize-original-emerging-creators/714777/
- https://buffer.com/resources/instagram-algorithms/ (updated 2026-10-23)

Benchmarks and studies:
- https://www.socialinsider.io/blog/instagram-reels-statistics/ (9,771,822 Reels, Jan–Jun 2026; pub 2026-06-24, upd 2026-10-21)
- https://databox.com/benchmarks/instagram-benchmarks (1,400+ companies; updated 2026-11-04)
- https://www.dashsocial.com/blog/non-followers-instagram-audience (2026-06-10)
- https://www.dashsocial.com/press-release/2026-social-media-benchmarks (April 2026)
- https://www.flick.social/learn/instagram-analytics-benchmarks/insights/conversion-rate/3-months (data to Jan 2025)
- https://liahaberman.substack.com/p/the-best-instagram-content-formats (2025-10-14; Metricool + HypeAuditor, up to 70M posts)

Cases and post-mortems:
- https://www.sarahtownsendeditorial.co.uk/2022/06/viral-video-post-on-instagram-lessons-learned/ (June 2022)
- https://adant.ai/guides/instagram-reels-views-but-no-followers (updated 2026-10-11)
- https://www.kapwing.com/resources/instagram-trial-reels-study-what-we-learned-after-a-trial-reel-hit-1-million-views/ (2025-10-07)
- https://viternogroup.com/blog/instagram-reels-reach-non-followers (single client case)
- https://note.com/nken0302/n/n7a27734f32e2?hl=en (2025-07-07, unsourced benchmarks)

Secondary / weakly sourced (used only where labelled):
- https://creatorlanehq.com/blog/instagram-5-hashtag-limit-2026
- https://doublebarril.com/how-to/social-media-hashtag-strategy/
- https://www.socialmediaexaminer.com/instagram-marketing-how-to-pin-posts-and-reels-to-a-profile/
- https://heymark.ai/en/guides/instagram-pinned-posts/
- https://seosherpa.com/instagram-search-results/
- https://www.jeffbullas.com/thread/how-does-instagrams-keyword-search-work-and-how-can-i-rank-higher/
- https://buzzvoice.com/blog/how-long-can-instagram-captions-be
- https://www.socialpilot.co/blog/ideal-social-media-caption-length

**Not reached:** instagram.com itself (login wall, per task constraint). Instagram Help Center article 202865988324236 rendered as an empty shell on fetch; its metric definitions are quoted here via search extraction of that page plus Meta's developer docs — **verify the exact labels in your own app**, since Meta is mid-rename from "Watch Time" to "Minutes Viewed." Also not reached: Mosseri's original Reels/posts (they live on instagram.com), the full Socialinsider and Metricool PDFs, and Dash Social's underlying trends report.

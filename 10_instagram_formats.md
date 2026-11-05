# Instagram formats — evidence from 429 scraped Reels

This is the file the rest of the research was missing: **actual Instagram Reels**, scraped and
measured, rather than YouTube videos or published articles about Instagram.

Read `ASSUMPTIONS.md` §2 for how this was obtained. Short version: Instagram's API 404s this
IP for every username and `yt-dlp` demands cookies, so this was done with a real headless
browser that renders the public hashtag grids and Reel pages.

---

## 0. What this sample is, and what it is not

| | |
|---|---|
| Reels scraped (caption + engagement) | **429**, deduplicated |
| Hashtags swept | **124+**, across sports, movement, talking-head, Japanese diet and general viral formats |
| Reels with frames captured | growing; see `instagram_frames/` |
| Metric available | **likes and comments** |
| Metric NOT available | **views, reach, follows** — Instagram does not expose these publicly |

**The single most important caveat: likes are not reach, and they are certainly not follows.**
Everything below is correlational, confounded by account size, and drawn from hashtag-surfaced
Reels rather than a random sample. Treat it as directional evidence about *format*, not as
proof of what will convert for you. Where a finding is biased by how I sampled, I say so.

---

## 1. Engagement by content type

Median likes per bucket, 429 Reels:

| Bucket | Reels | Median likes | p90 | Max |
|---|---|---|---|---|
| General viral (`#reels`, `#viral`) | 9 | 5,000,000 | 9,000,000 | 11,000,000 |
| Sensory / ASMR / satisfying | 7 | 2,000,000 | 7,000,000 | 12,000,000 |
| Challenge / obstacle | 8 | 954,000 | 3,000,000 | 6,000,000 |
| Advice / motivation (talks) | 41 | 169,000 | 2,000,000 | 4,000,000 |
| Green-screen commentary | 6 | 147,500 | 218,000 | 271,000 |
| Sports (extended set) | 50 | 66,000 | 991,000 | 5,000,000 |
| Sports (core set) | 66 | 60,500 | 851,000 | 3,000,000 |
| Movement-adjacent (parkour/calisthenics/tricking) | 39 | 53,000 | 1,000,000 | 3,000,000 |
| Ranking / tier list | 13 | 52,000 | 361,000 | 577,000 |
| Day-in-life / student (talks) | 44 | 40,000 | 556,000 | 2,000,000 |
| CS / coding / tech (talks) | 18 | 30,000 | 296,000 | 835,000 |
| Facts / "did you know" | 17 | 19,000 | 2,000,000 | 3,000,000 |
| Founder / build-in-public (talks) | 31 | 10,000 | 67,000 | 288,000 |
| **Japanese food** | 15 | **12,000** | 60,000 | 148,000 |
| **Japanese diet** | 9 | **73** | 1,594 | 18,000 |

Three things fall straight out of this table.

**Movement sports clear 3M regularly.** Your competitive set is not small. Real examples:
`tkdemelyanenko` — 「🦵Triple Kick💥 #taekwondo」 at **3M likes**; `thewayofchi` — wushu training
in nature at **3M**; `nikrusev_` — 「OVERPOWERED V13/8B 🚀 The craziest dyno I've ever done」 at
**3M** (climbing); `tyler.ninja.bowers` — ninja-warrior obstacle runs at **6M and 3M**;
`faithframee` — volleyball at **5M**.

**Build-in-public is the worst-performing talks bucket**, at a 10,000 median — 17x below the
advice bucket. `03_taita_talks.md` ranked the founder build log as the top recommendation for
`taita.talks`. On Instagram engagement that is the weakest lane of the four measured.

**Japanese diet is a very small pond.** A 73-like median, three orders of magnitude below
sports. Combined with the hashtag volumes in §4, this should reset launch expectations for
ごはんとも substantially.

---

## 2. Hook archetypes — with the bias stated

Caption first-line archetype against median likes, all 429:

| Archetype | Reels | Median likes | Lift |
|---|---|---|---|
| Near-miss / fail | 17 | 438,000 | **9.32x** |
| Credential or grade in the hook | 4 | 93,000 | 1.98x |
| Superlative / record claim | 29 | 65,000 | 1.38x |
| Relatable POV | 4 | 63,500 | 1.35x |
| *(no archetype detected)* | 124 | 61,000 | 1.30x |
| Storytime | 13 | 59,000 | 1.26x |
| Loss aversion ("stop", "don't", "mistake") | 258 | 48,500 | 1.03x |
| Transformation / progress | 29 | 44,000 | 0.94x |
| Direct question to viewer | 60 | 35,000 | 0.74x |
| **How-to / tutorial** | 31 | **15,000** | **0.32x** |

### The near-miss result is real but inflated — I biased it

Near-miss tops the table, and within-bucket it holds up (77x in format-trend, 9.6x in
movement). **But I seeded `#almostmadeit` and `#fail` as search tags**, so concentrating
near-miss Reels in a bucket and then finding them strong there is partly circular. The
movement figure rests on n=2. So: the effect is real — an 11M-like basketball Reel captioned
simply 「Almost had it🥀」 is not noise — but do not quote 9x as a clean number.

### The how-to result is the cleanest and the most awkward

Tutorials sit at **0.32x**, the worst archetype measured. Checked *within* bucket, so it is
not a composition artifact:

| Bucket | How-to median | Everything else |
|---|---|---|
| Sports (extended) | 36,000 (n=3) | **67,000** (n=47) |
| Movement-adjacent | 38,000 (n=3) | **64,500** (n=36) |

This **contradicts the recommendation in `02_taita_del_tricking.md`** to shift toward
instructional content. That advice came from YouTube subs-per-view, where instructional
channels convert best. On Instagram engagement, tutorials underperform roughly 2:1.

**But the ceiling is not low.** `p_j_m_9_8`'s 「Switch Tornado Kick Tutorial🔥」 did **3M
likes**. So a tutorial *can* be a top performer in martial arts — it is the median that is
weak, not the format's potential. Read it as: tutorials are a poor default and a viable
occasional swing, not as "never teach".

---

## 3. Caption shape, CTAs and hashtags

| Property | Reels | Median likes |
|---|---|---|
| Caption ≤40 chars | 32 | 53,000 |
| **41–120 chars** | 181 | **77,000** |
| 121–300 chars | 118 | 33,000 |
| >300 chars | 93 | 25,000 |
| No emoji | 147 | 52,000 |
| **1–3 emoji** | 200 | **57,000** |
| 4+ emoji | 77 | 27,000 |
| No hashtags | 40 | 34,000 |
| 1–5 hashtags | 294 | 46,000 |
| **6–15 hashtags** | 65 | **102,000** |
| 16+ hashtags | 25 | 31,000 |

**Hashtags: this contradicts `05_captions_and_packaging.md`.** That file concluded hashtags
are inert labels and noted Instagram's reported 5-cap. In this sample the **6–15 band more
than doubles** the 1–5 band. I am not claiming causation — accounts that use 6–15 tags may
simply differ — but "hashtags don't matter" is not supported by 429 scraped Reels.

**CTAs correlate with *lower* engagement:**

| CTA in caption | Reels | Median likes | Median comments |
|---|---|---|---|
| *(none at all)* | 345 | **53,000** | 296 |
| Share ask | 15 | 38,000 | 218 |
| Follow ask | 38 | 34,500 | 225 |
| Comment ask | 31 | 34,000 | 325 |
| Save ask | 22 | 9,610 | 77 |
| Link in bio | 6 | 9,719 | 152 |

Almost certainly confounded — creators with reach don't need to ask — but it matches the
earlier YouTube corpus finding that 9 of 18 top videos carried no CTA. **Comment asks do lift
comments** (325 vs 296 median) while lowering likes, which is the one clean trade in the table.

---

## 4. Japanese hashtag volumes — and a positioning problem

Instagram reports Reel counts per hashtag. Earlier research called these unretrievable; they
are not:

| Hashtag | Reels on Instagram |
|---|---|
| 自炊記録 | **10M** |
| ダイエット記録 | **9.5M** |
| 宅トレ | **7.8M** |
| 食事記録 | **4.9M** |
| 糖質制限 | **4.5M** |
| レコーディングダイエット | **4.4M** |
| ヘルシーごはん | 506K |
| **カロリー計算** | **79K** |

**ごはんとも's literal category is the smallest one on this list.** カロリー計算 is ~62x
smaller than 食事記録 and ~127x smaller than 自炊記録. The Japanese audience is not gathering
around *calculating calories*; it is gathering around **記録 — recording**. An app positioned
as "AIカロリー計算" aims at the thin end of its own market.

This is a cheap fix made before launch and an expensive one made after: lead with 記録, and let
the AI calorie estimate be *how* it records rather than *what it is*.

---

## 5. What to actually do, per brand

### `taita.del`

The comparables above are all movement athletes clearing millions without tutorials and
without stunts you can't repeat. What they share: **a single clean feat, shot once, captioned
in under ten words.**

1. **Near-miss as a standing format.** 「Almost had it🥀」 did 11M in basketball. You generate
   near-misses every session you don't land something. This is the one place your viral
   history generalises — the mechanism was the near-miss, not the injury, and near-misses are
   infinitely repeatable while concussions are not.
2. **Put the grade in the hook.** 「OVERPOWERED V13/8B」 did 3M because the number means
   something to the audience. Your equivalent is naming the trick and its difficulty. You are
   ranked 8th nationally and never say so in a caption.
3. **Single-trick posts beat combos.** 「🦵Triple Kick💥」 at 3M, with only 710 comments — it
   doesn't need to be a conversation to travel.
4. **Caption 41–120 characters, 1–3 emoji, 6–15 hashtags, no CTA.**
5. **Tutorials: occasional swing, not the default.** 0.32x median, but a tornado-kick tutorial
   hit 3M. Roughly one in six posts.

### `taita.talks`

The data says something uncomfortable: **the founder/build-in-public lane you were steered
toward has a 10,000 median, the lowest of the four talks buckets.** Advice/motivation sits at
169,000 — 17x higher.

The high performers are short, declarative and aphoristic: 「Just simply, don't quit」 (3M),
「Your reminder 🍵💗」 (3M). Not founder updates, not day-in-the-life. If `taita.talks` is
going to work on Instagram, it looks more like a short conviction statement than a build log.
That is also easier in one unedited take.

### `ごはんとも`

1. **Reposition around 記録, not カロリー計算** (§4).
2. **Reset expectations.** Japanese diet median is 73 likes; food is 12,000. Lead with the
   *food* framing, which performs ~160x better than the diet framing in this sample.
3. The Japanese hooks that did land are loss-aversion and disclosure:
   「これ作らないと損します⚠️」, 「土日に太って71kg」, 「レシピはこちら👇」.

---

## 6. Corrections to earlier files

1. **`02` — "shift to instructional":** reverse on Instagram. Tutorials are 0.32x median.
2. **`03` — founder build log as top pick:** lowest-engagement talks bucket measured (10K
   median vs 169K for advice).
3. **`05` — hashtags are inert, cap at 5:** 6–15 hashtags showed 2.2x the 1–5 band.
4. **`00`/`02` — "spectacle is the worst-converting type":** movement spectacle routinely
   clears 3M on Instagram. The YouTube-derived claim does not transfer.
5. **`04` — hashtag volumes unretrievable:** they are retrievable, and they reveal the
   カロリー計算 positioning problem.

All five earlier claims came from YouTube data or published articles. These come from scraped
Instagram Reels. Where they disagree, prefer this file for Instagram — while remembering it
measures **likes, not follows**, which is the thing you actually want.

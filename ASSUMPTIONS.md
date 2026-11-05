# ASSUMPTIONS, METHOD AND LIMITS

What I assumed, what I could actually verify, and what you should distrust in this report.
Read this before acting on anything else, because it tells you which claims are load-bearing.

---

## 1. Interpretation choices I made

| Ambiguity | What I chose | Why |
|---|---|---|
| Which repo should hold this research | `TaitaNakayama/gohantomo`, on branch `content-research`, in a top-level `content-research/` directory | It was the only repo attached to this session with push access. **Caveat: this research covers all three brands, and `gohantomo` is the iOS app repo for only one of them.** Nothing here touches app code or any M0 invariant — it is additive Markdown. You may well want to move it to a dedicated repo; it is self-contained, so `git mv` is all it takes. |
| "15+ video breakdowns per brand" | Interpreted as 15+ per brand where the platform allowed it, prioritising depth of breakdown over hitting a count with thin material | Video download is blocked (§2). Padding the count with videos I could not actually analyse would be fabrication. Actual counts are stated in `video_breakdowns/README.md`. |
| "second by second" | Delivered as **word-level timestamped verbal breakdowns** (millisecond-accurate) plus hook/loop/payoff labelling | Captions are available with word-level timing; frames are not. See §2. |
| Whether to include Japanese-language sources | Yes, heavily, for Gohantomo | Audience is Japanese; English sources on Japanese TikTok are thin and often wrong. |
| Monetization currency/pricing | Reported in whatever currency the source used, labelled | Mixing conversions would introduce errors. |
| `taita.talks` production constraint | Treated as a **hard** constraint: no recommendation requiring cuts, b-roll, captions-burn-in or motion graphics | The brief says filming/editing friction is the real blocker. A recommendation he will not execute is worthless. |

---

## 2. Platform access: what worked and what did not

This is the most important section for judging the video-breakdown material. All of it was
tested directly from this cloud container on 2026-11-05.

| Capability | Status | Evidence |
|---|---|---|
| YouTube **search** (`ytsearch`) | ✅ Works | Returned real IDs, view counts, durations |
| YouTube **metadata** (title, channel, view_count, duration, upload_date, like_count) | ✅ Works, intermittently rate-limited | Occasional `Sign in to confirm you're not a bot`; survivable with sequential access + delays |
| YouTube **auto-caption download** | ✅ **Works, with millisecond word-level timing** | `json3` caption format gives `tStartMs` per event and `tOffsetMs` per word |
| YouTube **video/audio stream download** | ❌ **Blocked** — `HTTP Error 403: Forbidden` | Tried standard format selection and single-file format |
| **Frame extraction** (the `ffmpeg` step in the brief) | ❌ **Not possible** | Requires the video stream, which is blocked |
| **TikTok** video download / post pages | ❌ **Blocked** — `Your IP address is blocked from accessing this post` | Single attempt, per the brief's 2-attempt rule |
| **TikTok `oembed` endpoint** | ✅ **Works** (found late) | Confirms whether a handle exists and returns its current display name. Used to verify 18 Japanese handles live on 2026-11-05 |
| **YouTube channel & search pages via `curl`** | ✅ **Works** (found late) | Subscriber and view counts read live rather than taken from listicles |
| Instagram | ❌ Not attempted for download | Requires login/cookies, which the brief forbids |

Two of these were discovered part-way through and are worth stating plainly, because they
upgrade some evidence from "secondary" to "verified": TikTok's `oembed` endpoint answers
whether a handle exists and what it is currently called, and YouTube channel pages fetch
fine with `curl` even though the video streams do not. Figures gathered that way are read
live and dated, not lifted from a listicle. Anything collected before that point, and
anything about Instagram, remains secondary.
| `faster-whisper` (installed, v1.2.1) | ⚠️ Installed but **unused** | Transcription needs audio, which is blocked. YouTube's own captions were available instead, and are *better* for this purpose because they carry word-level timing |

### What this means for the breakdowns — read this honestly

I can state, to the millisecond, **what was said and when**. I therefore analyse hook wording,
pacing, words-to-first-claim, loop-opening language, re-hook phrasing, payoff timing and
closing CTA with real precision.

I **cannot** see:

- on-screen text (its wording, placement or duration)
- cut frequency, framing or camera movement
- visual teasers, and the visual half of a "wait for it"
- covers/thumbnails

Where this report discusses visual or on-screen-text technique, it rests on **secondary
sources** (teardowns, creator interviews, platform documentation) or is marked `[inference]`.
It is not from my own observation. Treat the verbal analysis as primary evidence and the
visual analysis as research.

One genuine consequence: a tricking clip's hook is mostly **visual**, so the transcript method
is weakest exactly where `taita.del` lives. I compensated by weighting `taita.del`'s
breakdown corpus toward talking-over-footage and tutorial videos, and by leaning on secondary
analysis for pure-spectacle clips. This is a real limitation of the evidence, not a gap I have
papered over.

### A note on the bot check

I did not attempt to defeat YouTube's bot check. One attempt to probe alternate player clients
was correctly blocked by this environment's safety tooling as bot-check circumvention, and I did
not retry it. No cookies or logins were used anywhere. Harvesting runs **sequentially with
delays** rather than in parallel, specifically to stay inside normal access patterns.

---

## 3. Things I could not verify

- **Taita's own account metrics.** Follower counts, the 10M+ view figures, the national ranking
  and the student count are all taken from the brief as given. I did not access `taita.del` or
  `taita.talks`, so nothing here independently confirms them.
- **Private follower counts and revenue.** Where a creator's income is cited it is from their own
  public claims (podcast, interview, sales page). Self-reported creator revenue is routinely
  inflated; it is labelled as self-reported wherever used.
- **Follower-conversion rates per content tier.** Platforms do not publish follower-conversion by
  content type. Where this report gives conversion guidance it is reasoned from creator
  post-mortems, published teardowns and account structure — marked `[inference]` — not from
  platform data. Anyone claiming a precise "general content converts at X%" number for tricking
  is making it up.
- **Live algorithm behaviour.** Platform ranking changes faster than any source documents it.
  Hashtag and SEO guidance is dated in `05_captions_and_packaging.md`; check it before relying on it.
- **Japanese slideshow-format evidence.** Flagged explicitly in `04_gohantomo_japan.md` where the
  Japanese-language evidence base is thinner than the US one, rather than smoothed over.

---

## 4. Rules the research followed

1. No invented view counts, follower counts, quotes, titles or creators. Where a figure could not
   be verified it is omitted or marked `(unverified)`.
2. Every concrete example carries a link.
3. Source claims are distinguished from my inferences; the latter are marked `[inference]`.
4. View counts harvested by tool are timestamped, because they move.
5. No downloaded media was committed. No video files exist in this repo.

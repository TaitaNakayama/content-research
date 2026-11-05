# 11. Instagram Reels: what is actually on screen (visual hook analysis, refreshed at n = 52)

For Taita (taita.del tricking / taita.talks raw one-take talking / ごはんとも Japanese calorie app).

This replaces the 18-Reel version. Sample is now **52 Reels** from `igframes/manifest.tsv` (the first 52 rows; three more rows were appended to the manifest while I was working and are not analysed). For every Reel I opened a 12-frame contact sheet that always contains all seven hook-window frames (t0, t0_5, t1, t1_5, t2, t2_5, t3) plus up to five later frames (an even spread for long Reels; the exact later frames are in the appendix). Everything below was read off a frame I opened. Text is transcribed as printed; `[illegible]` where I could not read it. Non-English glosses are mine and approximate.

**Conventions used throughout**

- **Tiers** by manifest likes: **≥3M** (n = 22), **500K–3M** (n = 23), **<500K** (n = 7). Likes are rounded in the manifest, so the nine Reels listed as "3M" sit on the tier boundary.
- **Opening class** (my coding of what the subject is doing in t0 and by t3): **A** = the feat or process is already in motion at t0; **B** = setup or low-motion at t0, main action starts by about 3 s; **C** = no main action by 3 s (static scene, title card, black frame, slow build); **T** = a person talking to camera, speaking from t0.
- **Format family** (needed because format and engagement are tangled together here): **Visual-demo** (V, n = 30): near-miss, single-feat, sensory/ASMR, POV sport, challenge-run, tutorial, compilation, 3D animation, food game, product demo. **Speech/text-led** (S, n = 22): talking-head, skit/meme, facts card, ranking, quote, before/after montage.
- "Words" means author-added overlay text. I do not count in-scene signage, product prints or watermarks (e.g. `@AGBAPS`, `Sara Daily recipes`, `HariXFilm`, `LOVB`).

---

> **Sample note:** this analysis covers **52 Reels**. The drip kept capturing while it ran,
> so the frame corpus on disk is now larger (see `instagram_frames/frames_manifest.tsv`).
> Nothing here covers the Reels captured after the analysis started.

## 1. What changed from the 18-Reel version

| # | Claim at n = 18 | Original figure | New figure at n = 52 | Verdict |
|---|---|---|---|---|
| 1 | "Burned-in headline text is rare in winners." (text correlated with *worse* performance) | 5/18 had a headline at t0; 10/18 nothing; the 18M and 12M Reels had no text, all three ~170K Reels did | **t0 headline words:** ≥3M **6/22 (27%)**, 500K–3M **8/23 (35%)**, <500K **6/7 (86%)**. **Words by t3** (counting captions that start after t0): 9/22 (41%), 13/23 (57%), 7/7. **Any overlay by t3 in ≥3M, incl. numerals: 11/22 (50%).** Of the four ≥9M Reels, 2 have headlines (11M, 9M), 2 have none (18M, 12M). **Inside a format family the gradient vanishes:** visual-demo Reels, ≥3M 3/16 headline at t0 (19%) vs 500K–3M 3/14 (21%); speech/text-led Reels carry words by t3 in 22/22 at every tier. | **WEAKENED.** The raw gradient held (86% / 35% / 27%), but "rare in winners" is not true (half of ≥3M carry overlay text within 3 s) and the gradient is a format effect: all 7 Reels under 500K are speech/text-led, so they must have text. There is no visible within-format penalty or bonus for text. |
| 2 | "Winners open mid-action." | 13 of 15 Reels at 3M+ opened mid-action or reached action in 1–3 s; static/talking-head clustered in low buckets | **≥3M: 17/22 (77%)** are A or B (A = 7, B = 10; C = 3; T = 2). 500K–3M: 17/23 (74%). <500K: 3/7 (43%). All 52: 37 (71%). Visual-demo **27/30 (90%)** A or B; speech/text-led **10/22 (45%)**, flat across tiers (3/6, 4/9, 3/7). Alternative codings of 6 borderline Reels move ≥3M A+B between 13 and 18 of 22. | **HELD** as "most winners start in motion" (77% vs 87%). The sub-claim "static/talking-head clusters in low-engagement buckets" is **WEAKENED**: it is format again (speech formats are 45% A/B at every tier). The "no winner opens on a title card or black frame" line is also weakened: DUQ4 (5M) opens on a static poster-frame card, DT-I (2M) and DU_o (2M) open on black. |
| 3 | "Caption and on-screen text diverge." | 5 of the 6 Reels with burned-in words diverged | 29 Reels have author-added words anywhere in the sampled frames. **16 diverge outright, 5 are partial (same theme, different words), 8 match** (21/29 = 72% if partials count as diverging). By tier, clean divergence: ≥3M 2/9, 500K–3M 9/13, <500K 5/7. | **WEAKENED.** Still a majority diverge, but 55% rather than 83%, and it depends on format: facts/ranking title cards usually repeat in the caption (5 of 6). |
| 4 | "9M+ headlines are ≤4 words, end in an emoji, and name a feeling." | n = 2 (`Dear basketball...🥀`, `AAJ TOH BACH GYE 😮‍💨`) | **Still n = 2 at ≥9M:** no new Reel at 9M or above. At ≥5M, three overlay phrases fit (`Dear basketball....🥀`, `AAJ TOH BACH GYE` + face emoji, `First day in gym😅`, all 4 words or fewer, ending in an emoji); the fourth (DUQ4 5M) is a 3-word template label with no emoji. Across all tiers, 6/14 hook headlines are ≤4 words *and* end in an emoji: ≥3M 3/5, 500K–3M 2/5, <500K 1/4. | **STILL TOO SMALL.** Direction is consistent but every cell is under 8. "Names a feeling" cannot be tested: `No arms 💪` (2M) and `the only game we play😋😋` (2M) carry non-deflated emoji. |

**Other things that moved** (each is a sub-point of the old Section 2, 3 or 4):

| Old point | Change |
|---|---|
| "No question headlines." | One now exists: DVW0 (53K) `"How did you know he was the one?"`. 1 of 52. Original held for the big Reels. |
| "Text is on from the first frame and stays." | 12 of the 20 Reels with words at t0 keep them through every sampled frame. 8 change or drop: DVD2 (gone t18), DYOW (gone by t10), DWq2 (gone by t30), DDHW (to t1.5 then numerals), DTI1 (to t1.5), DUQ4 (gone by t0.5), DZ7n and DT_g (text swaps at about 0.3–0.45 of the Reel). |
| "Single-feat Reels land the feat after the first third (0.63–0.91)." | Reversed with more data: of 11 single-feat / near-miss / stunt Reels with a visible feat, **8 land it before the halfway point** (about 0.05 to 0.47); only 3 land late (DGdw 0.65, C6W 0.63–0.84, DV79 0.91). |
| DYOW emoji "droopy-eyed, glyph unclear". | At this resolution the two emoji read as flushed faces (😳😳). The caption uses 😭😭, so the emoji differ. |
| "No winner opens on a title card, black frame, or establishing shot." | See claim 2 row. |

---

## 2. All 52 Reels

Columns: **Open** = opening class (A/B/C/T, defined above). **Text at t0** is verbatim. **vs caption**: match / partial / diverges / n.a. (no overlay words to compare). **Payoff** is the fraction of the duration where a payoff is visible in sampled frames. Rows are grouped by tier, then manifest order.

### ≥3M (22 Reels)

| Shortcode | Likes | Dur (s) | Format | Text at t0 | Persistence | vs caption | Open | Payoff |
|---|---|---|---|---|---|---|---|---|
| DcJZ3nbvXJA | 18M | 25.9 | near-miss (slip on pier) | (none) | no text in any of 12 frames | n.a. | A | slip ~0.04–0.06 (t1–1.5); rest is people walking at sunset, no second event seen |
| DKYTBJ6pjY2 | 12M | 8.0 | ASMR/sensory | (none) | none | n.a. | A | loop, no single payoff |
| DV79WToDXwb | 11M | 8.8 | near-miss (hoop shatters) | `Dear basketball....🥀` | all 10 frames | diverges (shares 🥀 only; caption is "Almost had it🥀") | A | glass shatters 0.91 |
| DVD2QASk3pi | 9M | 19.1 | other (scripted skit) | `AAJ TOH BACH GYE` + small yellow open-mouth face emoji | t0–t14, absent t18 | match (caption begins "Aaj toh Bach giye") | B (t0 static selfie, hard cut and action at t0.5) | not identifiable |
| Dd3DS5NCBxA | 7M | 86.1 | ASMR/sensory (marble run) | (none) | none | n.a. | B | hole close-up at t86 (1.0) |
| DVpZdSlE5yW | 7M | 13.4 | other (3D animation) | (none; `HariXFilm` engraved in-scene) | none | n.a. | A | machine finished 0.90 |
| DTbCZsqEjeq | 6M | 18.6 | challenge-run | no words; numerals `7` `6` `8` pinned to obstacles | numerals count down to `1`; active one flashes | complementary (caption lists the moves) | B | last ring 0.97 |
| DXy83WxIA0W | 6M | 14.6 | other (skit) | (none at t0); `First day in gym😅` by t0.5 | t0.5–t14 | partial (Marathi caption, shares 😅) | B | exhaustion 0.68–0.82 |
| C-5RrctAoPq | 5M | 60.8 | ASMR/sensory | (none) | none | n.a. | A | first cut by 0.05, then repeats |
| Dcb8yXZyRsi | 5M | 14.6 | compilation | (none) | none | n.a. (caption is credits) | A | none |
| DUQ4KdeE4y1 | 5M | 24.4 | other (skit) | `INDIA` (top-left) + `ROAD LIFE` (bottom-right), poster frame | gone by t0.5, no later overlay | diverges | B (static card t0, acting from t2) | not identifiable |
| DUuRWW_ie96 | 4M | 18.0 | talking-head | (none at t0); Hindi subtitle by t0.5 | sentence-by-sentence to t14 | partial (same theme) | T | n.a. |
| C6W_ZcyN_El | 4M | 9.5 | near-miss (bail) | (none) | none | n.a. | C (slow approach ~4 s) | bail 0.63–0.84 |
| DcJdD-qTlWA | 3M | 24.1 | single-feat (dyno) | (none) | none | n.a. | C (tiny climber hangs in place until t6) | dyno 0.25, catch 0.41 |
| COhjyGoJU6h | 3M | 14.9 | other (solo martial montage) | (none) | none | n.a. | B | kick 0.20 |
| DGdwNO3MHGX | 3M | 3.1 | single-feat (board break) | (none) | none | n.a. | B | contact 0.48–0.65 |
| DRDFfJykhas | 3M | 25.4 | challenge-run | no words; numerals `2` `1` | `1` green t1.5, `2` green t2.5–3, up to `8` | complementary | B | last bar 0.94 |
| DVcUo1UiO9I | 3M | 10.1 | ASMR/sensory + quote | five lines printed on the milk: `as long as` / `you can` / `as you` / `start over` / `are alive` (`you can` and `start over` faint) | all 11 frames; weights swap as matcha pours | partial (same theme) | B (pour enters ~t1.5) | stir 0.8–1.0 |
| DdR_XpIxnSn | 3M | 14.2 | talking-head | (none at t0); word captions from t0.5 | `Winners` / `Winners Never` / `Winners Never quit` / `Quitters` / `Quitters Never` / `out of it` / `YOU can` | partial ("Just simply, don't quit") | T | n.a. |
| DDHWGlShoYv | 3M | 11.7 | tutorial | `Switch Tornado Kick Tutorial` | t0–t1.5, then numerals `1` `2` `3`, then `Final` t10 | match | B (kick at t1) | kick 0.09–0.13; `Final` 0.86 |
| DTaaTbQEnl2 | 3M | 12.5 | tutorial (recipe) | (none; in-scene `Sara Daily recipes`) | none | n.a. (caption is recipe title + ingredients) | A | cheese pull 0.96 |
| DRpOyeNj6th | 3M | 6.4 | other (facts card) | `Meta Minutes` `@metaminutes` / `Japanese kids learning about road safety` + sign emoji | all 9 frames | match | C (static observation, car at t2) | car enters 0.31 |

### 500K–3M (23 Reels)

| Shortcode | Likes | Dur (s) | Format | Text at t0 | Persistence | vs caption | Open | Payoff |
|---|---|---|---|---|---|---|---|---|
| DYGJj_hh-AG | 597K | 22.7 | POV (surf) | (none) | none | n.a. | A | none |
| DehBTdARxwn | 2M | 11.9 | other (home product) | `my morning lineup` (tiny, centre) | all 11 frames | diverges (caption is a "Comment HOME" CTA) | A | under blanket 0.84 |
| DV81W7jjlI4 | 2M | 14.0 | other (facts card) | `Unpacked Knowledge` `@unpackedknowledge` / `Why this metal ruler makes that strange sound` | all 12 frames | diverges (screen asks, caption answers) | A | ruler 0.43 |
| DWFWX7EETHM | 2M | 7.7 | talking-head (interview clip) | (none); word captions from t1: `is if`, `you have`, `text me`, `number`, `a problem` | to t6 | diverges (caption is a bio) | T | n.a. |
| DU_ojQkktjI | 2M | 11.6 | other (film clip) | black frame; captions from t0.5: `by the way`, `am i`, `talking to`, `who's the` | to t2 only | diverges | C | n.a. |
| DTkXR5mDDBb | 2M | 21.2 | other (skit/prank) | (none); captions from t0.5: `girl hello`, `Hey`, `good evening`, `look`, `Thank you` | intermittent | diverges (caption is hashtags) | A | man drops to push-up 0.28 |
| DUieJX4k04B | 2M | 11.3 | talking-head | (none); kinetic words from t0.5: `discipline`, `your`, `thought's`, `stop`, `thinking`, `too`, `much`, `don't`, `be`, `the`, `in`, `present` | to t8, end card `TWENTY2™` at t10 | diverges (caption is a bio) | T | end card 0.88 |
| DVOaskok8Ju | 2M | 14.4 | other (food game) | `the only game we play😋😋` | all 12 frames | match (reworded) | A | final board 0.83–0.97 |
| DSvXnkWiK3t | 2M | 20.4 | other (3D animation) | (none; in-scene `@AGBAPS`) | none | n.a. | B | ignition 0.12 |
| DX7J0KZgJtY | 2M | 13.6 | other (juggling sequence) | (none) | none | n.a. | A | none |
| DCBqQUIM416 | 2M | 8.7 | single-feat | (none) | none | n.a. | A | airborne 0.34, inverted 0.69 |
| DEoXfBqvcbH | 2M | 16.2 | POV (snowboard) | (none) | none | n.a. | A | none |
| DT-ICI1EX4x | 2M | 35.1 | tribute/compilation | black frame; green text `EVERYONE SEE SILENCE...` t2–t3 (t2 clipped to `EVERYONE SEE SILEN`) | absent from t8 | diverges | C (static bow t0.5–t3) | match cuts 0.4–1.0 |
| DUqpt5SgW64 | 908K | 23.4 | challenge-run | (none) | none | n.a. | A | cups nearly gone 0.94 |
| CbIDNhuBWcQ | 907K | 3.2 | near-miss (handstand fail) | (none) | none | n.a. | A (held pose) | fall 0.47 |
| DMYJp2EPjTU | 2M | 15.0 | single-feat (tricking combo) | (none) | none | n.a. | A | first flip 0.13, crowd reaction 0.67–0.93 |
| DZ7nucvPhwX | 584K | 12.5 | other (before/after montage) | `Life before exam` + row of 5 small emoji (alarm clock, books, laptop, coffee, crying face) | t0–t3; `Life after exam` + a different emoji row (glyphs `[illegible]`) t6–t12 | partial | A | switch ~0.3–0.45 |
| DWFFTuMjA6B | 579K | 78.9 | challenge-run (food) | (none) | none | n.a. | A | reactions 0.79–0.99 |
| DVevrXHDexl | 577K | 57.5 | other (ranking) | `RANKING BEST` / `CELEBRITY LOOKALIKE` / `(LAST ONE IS HILARIOUS)`, rank slots `2.` `3.` `4.` `5.`, `@omgitsgeraldhuston`; video area black | all 12 frames; slots fill `5. KANYE WEST` … `1. HOME SAY YOUNG` | match (reworded) | C (black card at t0, footage t0.5) | #1 revealed 0.97 |
| Dc9TLv9tdIu | 2M | 150.6 | challenge-run (experiment) | (none; 12-icon checklist, no words) | ticks fill up | n.a. | A | checklist completes 1.0 |
| DTI1-P8kU8B | 2M | 29.0 | challenge-run | `No arms 💪` | t0–t1.5 only | diverges | B | plate reached 0.62 |
| DMxCWfiNJFk | 2M | 10.7 | other (facts card) | `Explain Everythings` `exploresciencedaily` / `When scientist found water in the bottom of the ocean` | all 11 frames | match | A | 0.56–0.75 |
| DT_g52IDEPt | 1M | 9.3 | other (narrative skit) | `"she's probably sleeping"` | t0–t2.5, then `wrong girl.` + `6:02 AM` `6:32 AM` `7:32 AM` `8:02 AM` | diverges | T | text switch 0.32 |

### <500K (7 Reels)

| Shortcode | Likes | Dur (s) | Format | Text at t0 | Persistence | vs caption | Open | Payoff |
|---|---|---|---|---|---|---|---|---|
| DXkamtjkX7U | 218K | 11.3 | other (green-screen meme) | (none); fragment `you doin` (t2) / `you doing?` (t2.5) | ~0.5–1 s flash | diverges | A | none |
| DYOWKXztMak | 170K | 23.9 | talking-head | `Automatic Transmissions` + 😳😳 | t0–t6; gone t10–t22 | diverges | T | n.a. |
| DcSyV_8TteX | 169K | 12.2 | other (meme) | `3 Din daily college attend karliya !!!` | all 12 frames | diverges | C | n.a. |
| DWq2uH5EYRr | 169K | 48.8 | talking-head | `Advice I WISH I knew when  I started College` | t0–t20; gone t30–t48 | diverges (caption is hashtags only) | T | n.a. |
| DVW04JmAJ9M | 53K | 8.9 | other (skit reveal) | `"How did you know he was the one?"` | all 10 frames | diverges (screen = setup, caption = punchline subject) | C | reveal 0.67 |
| DX01rywuFBU | 52K | 6.5 | other (ranking) | tier-list graphic titled `Calisthenics skills Tier-List` | all 9 frames | match | A | none |
| DcB1eeyKhVT | 49K | 20.2 | other (facts card) | `People withdraw money from ATMs daily but this is the first time you've seen the internal system behind it all` | all 12 frames | match (reworded) | A | cash 0.5–0.8 |

Counts by format (primary): near-miss 4, ASMR/sensory 4, single-feat 4, POV 2, challenge-run 6, tutorial 2, compilation/tribute 2, talking-head 6, other 22.

---

## 3. On-screen-text playbook, by engagement tier

### 3a. Text in the hook window (t0 to t3), by tier

| Tier | n | Words at t0 | Words only after t0 (by t3) | Numerals only | No overlay in t0–t3 |
|---|---|---|---|---|---|
| ≥3M | 22 | 6 (DV79, DVD2, DUQ4, DVcU, DDHW, DRpO) | 3 (DXy8 0.5 s, DUuR 0.5 s, DdR_ 0.5 s) | 2 (DTbC, DRDF) | 11 |
| 500K–3M | 23 | 8 (DehB, DV81, DVOa, DZ7n, DVev, DTI1, DMxC, DT_g) | 5 (DU_o 0.5, DTkX 0.5, DUie 0.5, DWFW 1.0, DT-I 1.5–3) | 0 | 10 (+ Dc9T has icons but no words) |
| <500K | 7 | 6 | 1 (DXka, 2–2.5 s flash) | 0 | 0 |
| All | 52 | 20 (38%) | 9 | 2 | 21 (40%) |

### 3b. The same data split by format family (this is the table that matters)

| Family × tier | n | Words by t3 | No overlay |
|---|---|---|---|
| Visual-demo, ≥3M | 16 | words 3/16 (DV79, DVcU, DDHW), numerals 2/16 | 11/16 (69%) |
| Visual-demo, 500K–3M | 14 | words 4/14 (DehB, DVOa, DTI1, DT-I) | 10/14 (71%) |
| Visual-demo, <500K | 0 | none in sample | n.a. |
| Speech/text-led, ≥3M | 6 | 6/6 | 0 |
| Speech/text-led, 500K–3M | 9 | 9/9 | 0 |
| Speech/text-led, <500K | 7 | 7/7 | 0 |

Reading: text rate is set by format (23% of visual-demo Reels, 100% of speech/text-led Reels). Among visual-demo Reels it is the same at ≥3M and 500K–3M (31% incl. numerals vs 29%). The sample has **no visual-demo Reel under 500K**, so a "text hurts" or "text helps" effect on a clean visual Reel cannot be tested below 500K.

### 3c. Headline phrases in the ≥3M Reels (exact)

| Reel | Likes | Text | Words | Ends in emoji | Position | Behaviour |
|---|---|---|---|---|---|---|
| DV79 | 11M | `Dear basketball....🥀` | 2 | yes (wilted rose) | lower third ~73% | whole Reel |
| DVD2 | 9M | `AAJ TOH BACH GYE` + small yellow face emoji | 4 | yes | upper ~18%, red caps | t0–t14 of 19.1 s |
| DXy8 | 6M | `First day in gym😅` | 4 | yes | very top ~4% | from t0.5 to end |
| DUQ4 | 5M | `INDIA` / `ROAD LIFE` | 1 + 2 | no | corners of a poster frame | gone by t0.5 |
| DVcU | 3M | five lines on the milk (10 words) | 10 | no | on the milk surface | whole Reel, two layers swap |
| DDHW | 3M | `Switch Tornado Kick Tutorial` | 4 | no | top ~15% | to t1.5, then numerals `1` `2` `3`, then `Final` |
| DRpO | 3M | `Japanese kids learning about road safety` + sign emoji (under a `Meta Minutes` header) | 6 | yes | top | whole Reel |

### 3d. What the text actually does (counts)

- **Hook headline phrases (author-written, at t0 or by 0.5 s), n = 14:** 8/14 are ≤4 words; 7/14 end in an emoji; 6/14 do both. By tier (both conditions): ≥3M 3/5, 500K–3M 2/5, <500K 1/4. All under 8, so provisional.
- **Running captions** (word-by-word or sentence-by-sentence), n = 6 (DUuR, DdR_, DWFW, DU_o, DTkX, DUie): **none start at t0**; first caption at 0.5 s in 5, at 1.0 s in DWFW. Likes: 4M, 3M, 2M, 2M, 2M, 2M. Three are other people's speech (DWFW and DUie are interview/talk clips, DU_o is a film clip); DUuR's source is unclear; DdR_ and DTkX look like original creators. Captioning someone else's clip is not the same job as captioning your own talking.
- **Numerals pinned to obstacles**, n = 2 (DTbC 6M, DRDF 3M): both are ninja-course Reels; the numeral in use flashes (DTbC) or turns green (DRDF). Related progress devices: DDHW step numerals `1` `2` `3` then `Final` (3M); Dc9T checklist of 12 icons that fills with ticks (2M, no words); DVev rank slots that fill in (577K).
- **In-scene branding** as part of the picture, n = 3 (DVpZ `HariXFilm` 7M, DSvX `@AGBAPS` 2M, DTaa `Sara Daily recipes` 3M): no overlay headline in any of the three.
- **Card header + title style** (avatar + handle + title text over a small video window), n = 4 (DV81, DcB1, DMxC, DRpO): 2M, 49K, 2M, 3M. All four open in the first frame with the same layout and keep it for the whole Reel.
- **Position** does not converge: top (DDHW, DXy8, DVD2), centre (DTI1, DZ7n, DT_g, DehB), lower third (DV79), on the subject (DVcU).

---

## 4. Caption vs on-screen text

29 of 52 Reels carry author-added words. 21 have none (nothing to compare). Two have numerals only (complementary to a caption that lists the moves).

| Group | n | Match | Partial | Diverges |
|---|---|---|---|---|
| ≥3M | 9 | 3 (DVD2, DDHW, DRpO) | 4 (DVcU, DXy8, DUuR, DdR_) | 2 (DV79, DUQ4) |
| 500K–3M | 13 | 3 (DVOa, DVev, DMxC) | 1 (DZ7n) | 9 (DehB, DV81, DWFW, DU_o, DTkX, DUie, DT-I, DTI1, DT_g) |
| <500K | 7 | 2 (DX01, DcB1) | 0 | 5 (DXka, DYOW, DcSyV, DWq2, DVW0) |
| **All** | **29** | **8** | **5** | **16** |

By what the text is doing:

| Role of the text | n | Match | Partial | Diverges |
|---|---|---|---|---|
| Title card on a facts/ranking/graphic (DV81, DcB1, DMxC, DRpO, DX01, DVev) | 6 | 5 | 0 | 1 (DV81: screen asks "Why…", caption gives the answer) |
| Running captions of speech (DUuR, DdR_, DWFW, DU_o, DTkX, DUie) | 6 | 0 | 2 | 4 |
| Hook line on a skit, talking-head, meme or montage (DVD2, DYOW, DcSyV, DWq2, DVW0, DT_g, DXy8, DUQ4, DXka, DZ7n) | 10 | 1 | 2 | 7 |
| Hook line on a visual demo (DV79, DDHW, DehB, DVOa, DTI1, DVcU, DT-I) | 7 | 2 | 1 | 4 |

The facts/ranking row is n = 6, provisional. Jobs I can see:

- **Screen:** a title that states the premise (facts, ranking), the setup line of a skit (DcSyV, DVW0, DT_g, DXy8), a rule (`No arms 💪`), a topic label (DYOW), the speech itself (running captions), numbering.
- **Caption:** the punchline subject (DVW0 names the Dyson vacuum that the screen never mentions), the answer to the screen's question (DV81), a CTA keyword (DehB `Comment "HOME"`), a bio (DWFW, DUie, DU_o), credits (Dcb8: `🤝 @noemie.glover #asu #volleyball #avca video by: @shotbyklvg`), hashtags only (DWq2, DTkX), recipe text (DTaa).
- **Hashtag-only captions with the hook on screen:** DWq2 (169K) and DTkX (2M). A caption-only read sees no hook for those two.

---

## 5. Opening composition, with counts by tier

| Opening class | ≥3M (22) | 500K–3M (23) | <500K (7) | All (52) |
|---|---|---|---|---|
| A: already in motion | 7 | 15 | 3 | 25 |
| B: setup, action within ~3 s | 10 | 2 | 0 | 12 |
| C: nothing happens for 3 s+ | 3 | 3 | 2 | 8 |
| T: talking to camera from t0 | 2 | 3 | 2 | 7 |
| **A + B** | **17 (77%)** | **17 (74%)** | **3 (43%)** | **37 (71%)** |

By family: visual-demo A 18, B 9, C 3 (A+B = 27/30); speech/text-led A 7, B 3, C 5, T 7 (A+B = 10/22).

- **A, ≥3M (7):** DcJZ3 (walking, slips at ~1.5 s), DKYT, DV79, C-5R, Dcb8, DVpZ, DTaa.
- **B, ≥3M (10):** DVD2, Dd3D, DTbC, COhj, DGdw, DRDF, DXy8, DUQ4, DVcU, DDHW.
- **C, ≥3M (3):** C6W (slow walk ~4 s before the trick), DcJdD (tiny climber hangs in place until the dyno at t6), DRpO (kids sitting, car at t2).
- **Black or title-card first frame:** DT-I (2M, black t0), DU_o (2M, near-black t0), DVev (577K, black video area under a title), DUQ4 (5M, static poster frame). 4 of 52; only DUQ4 is above 3M.
- **Static pose that is really a pose:** DVW0 (53K) holds a mirror selfie for 4 s before the Snapchat reveal; DcSyV (169K) is a still classroom photo with an inset clip.

**Payoff position** (fraction of duration, where a single payoff is visible):

| Format | Reels | Where the payoff lands |
|---|---|---|
| Challenge-run / sequence / tutorial finale | DTbC 0.97, DRDF 0.94, DUqp 0.94, DWFF 0.79–0.99, DTaa 0.96, Dd3D 1.0, Dc9T 1.0, DVev 0.97 | last 3–20% of the Reel in 8 of 8 |
| Single-feat / near-miss / stunt | DcJZ3 0.05, DSvX 0.12, DMYJ 0.13, COhj 0.20, DTkX 0.28, DCBq 0.34–0.69, DcJdD 0.25–0.41, CbID 0.47, C6W 0.63–0.84, DGdw 0.48–0.65, DV79 0.91 | 8 of 11 before the halfway point; median about 0.34 |
| Sensory / loop | DKYT, C-5R (first cut by 0.05, then repeats), DVcU (stir at 0.8–1.0) | no single payoff or end-loaded |

Durations of the eight feat/near-miss Reels (DcJZ3, DV79, DcJdD, DGdw, DCBq, DMYJ, C6W, CbID) sort to 3.1, 3.2, 8.7, 8.8, 9.5, 15.0, 24.1, 25.9 s; median about 9 s.

---

## 6. What Taita should do, per account (only what the frames support)

### taita.del (tricking)

What the frames show. The closest comparables are DMYJ (2M, "5 gainers to dub cork in the kitchen", a tricker in a crowded kitchen), DDHW (3M, taekwondo kick tutorial), DGdw (3M, 3.1 s board break), C6W (4M, parkour bail), CbID (907K, handstand fail), DcJdD (3M, boulder dyno), DCBq (2M, snowboard jump), and the two ninja-course Reels with numerals (DTbC 6M, DRDF 3M).

- **Default to no overlay on a clean trick.** Of the 8 single-feat / near-miss Reels, 7 have no overlay text anywhere in the sampled frames (DV79 is the exception). DMYJ, the nearest tricking clip, has none and sits at 2M.
- **Open already moving, or with the run-up in the first second.** DMYJ is mid-stride at t0 with the first flip at about 2 s; DCBq, CbID and DcJZ3 are in motion at t0; DGdw's kicker is running by 1 s. Two of the eight (C6W, DcJdD) open slowly and still reach 3M–4M, so this is not a hard rule.
- **Put the feat early.** 8 of 11 stunt-type Reels land it before the halfway point. This sample cannot say whether that is a cause of reach.
- **Keep the clip short if the feat is single.** The median feat/near-miss Reel here is about 9 s.
- **If you post a tutorial,** DDHW (3M) is the only one: title in the first frame (`Switch Tornado Kick Tutorial`), then numbered steps from a new camera angle, then `Final` at full speed. n = 1; I am not claiming the numbers caused anything.
- **For a combo,** the numerals in DTbC and DRDF are the one device native to sport content here (n = 2): the numeral being attempted flashes or turns green. Pinning `1 2 3 …` to each trick is my inference from that, not something these Reels prove.
- **A reaction at the end** is visible in DMYJ (crowd hugging, big smile at 0.67–0.93); n = 1.

### taita.talks (raw one-take talking)

What the frames show. All 7 Reels coded T (the six talking-heads DUuR, DdR_, DWFW, DUie, DYOW, DWq2, plus DT_g, who speaks to camera in a narrative skit) have words by 1 s. Four use running captions that start at 0.5–1.0 s (4M, 3M, 2M, 2M); three use a headline at t0 (1M, 170K, 169K).

- **Closest match to a one-take: DdR_ (3M).** One dim camera, no cutaway in any sampled frame, speaker already mid-speech with hands moving at t0, no overlay at t0, word-by-word captions from 0.5 s, short caption ("Just simply, don't quit"). The other six are not pure one-takes (DWq2 cuts to tablet shots; DYOW is a green-screen over slides; DT_g cuts to a wide time-lapse at 3 s; DWFW, DUie are clips of someone else).
- **Open on the speaker, speaking.** 7 of 7 do; none opens on a title card.
- **Words should start within the first second.** That held for all 7. Whether burned-in headline vs running captions drives the 3M vs 170K gap cannot be separated from account size (limit 2 below).
- **The caption can carry something the screen does not.** DWq2 (169K) puts the entire hook on screen and uses hashtags only; DVW0 does the reverse (setup on screen, punchline subject in caption).

### ごはんとも (Japanese calorie app)

What the frames show. Nothing in the sample is a calorie, nutrition or Japanese-language overlay. Food-process Reels: DTaa (3M recipe), DVOa (2M momo game), DWFF (579K spicy-chip challenge).

- **All 3 food-process Reels open with hands or the process already moving (A).** DTaa and DWFF have no overlay; DVOa has one line, `the only game we play😋😋` (5 words + emoji).
- **DTaa's payoff (the cheese pull) is the last 4% of a 12.5 s Reel**; DWFF's is at 0.79–0.99; DVOa's final board at 0.83–0.97. Food payoffs here are end-loaded.
- **Progress/tally overlays exist at scale:** Dc9T (2M, a 12-icon checklist that fills with ticks), DVev (577K, rank slots that fill). That a running tally could carry a calorie total is my inference only.
- **Japanese conventions are untested here.** The one Japan-themed Reel (DRpO) uses an English title card. Test your own: the same clip posted with and without a short overlay.

---

## 7. Honest limits

1. **Sample size.** 52 Reels. Most format cells are under 8: tutorial 2, compilation 2, POV 2, near-miss 4, sensory 4, single-feat 4, challenge 6, talking-head 6, facts/ranking 6. Anything about a single format is provisional.
2. **Format and engagement are tangled, and the sample is lopsided.** All 7 Reels under 500K are speech/text-led; none is a visual demo. 22 of the 52 are speech/text-led and 30 visual. The manifest's bucket labels are not reliable (e.g. DVcU is filed under talks_advice but is a matcha pour; DTkX and DU_o are also under talks_advice), so I coded format from the frames.
3. **Likes, not reach.** No views, saves, shares, follower counts or watch-time. 18M vs 49K is driven by account size and distribution as much as by the Reel. Likes cannot say whether a hook worked. The 3M tier boundary has nine Reels sitting on rounded "3M" values.
4. **Seeding bias.** Reels were pulled from bucket lists, not sampled at random, and several are re-uploads, clips of other people's talks, or AI/CG renders.
5. **Still frames at 0.5 s steps.** I cannot see fade-ins or motion. Text that appears and disappears between sampled frames would be missed. DXka's flash (`you doin` at t2, `you doing?` at t2.5, absent at t0–t1.5 and t3+) was caught only because two sampled frames fell inside it. DT-I's text was visible in 3 of 7 hook frames.
6. **Contact sheets, not full-size frames.** Each sheet showed 12 frames at about 380 px wide. Small text can be misread: DUuR's Devanagari subtitles are tiny and my transcriptions are approximate; DZ7n's second emoji row is `[illegible]`; DX01's tier-list title is small and I give my best reading; the DVD2 face emoji could be 😯 or 😮 (the caption uses 😮‍💨).
7. **No audio.** Music, voiceover and spoken hooks are invisible to me. For the six running-caption Reels and the seven talking-head Reels the spoken first sentence may be the real hook.
8. **Opening class is my judgment.** Borderline: DUQ4, DVD2, DVcU, COhj (B vs C), DcJdD (C vs A), DSvX (A vs B). Re-coding them moves ≥3M A+B between 13 and 18 of 22 (59%–82%).
9. **Non-English text.** Hinglish, Hindi, Marathi, Portuguese and Russian glosses are mine and approximate. I did not translate beyond what is flagged.
10. **Frames per Reel.** Every Reel's t0 and all seven hook frames were opened. Later frames are a spread (longest Reels: Dc9T 81 frames on disk, Dd3D 49, DWFF 45, DVev 34, DWq2 30); an event between two sampled late frames can be missed. A few Reels have only 7 frames in total (CbID, DGdw).
11. **Excluded rows.** Three manifest rows appended after this analysis started (Dbrpj8MTJNm, C92oMDBIywp, DeXG5cpxVwj, all talks_advice at about 1M) are not included.

---

## Appendix: frames opened per Reel (audit)

| Shortcode | Frames on disk | Hook window opened | Later frames opened |
|---|---|---|---|
| DcJZ3nbvXJA | 18 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t6, t10, t16, t20, t24 |
| DKYTBJ6pjY2 | 10 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t4, t6, t8 |
| DV79WToDXwb | 10 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t4, t6, t8 |
| DVD2QASk3pi | 15 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t6, t8, t12, t14, t18 |
| Dd3DS5NCBxA | 49 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t18, t36, t52, t70, t86 |
| DTbCZsqEjeq | 15 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t6, t8, t12, t14, t18 |
| C-5RrctAoPq | 36 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t14, t26, t36, t48, t60 |
| Dcb8yXZyRsi | 13 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t4, t6, t10, t12, t14 |
| DUuRWW_ie96 | 15 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t6, t8, t12, t14, t18 |
| C6W_ZcyN_El | 10 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t4, t6, t8 |
| DcJdD-qTlWA | 18 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t6, t10, t16, t20, t24 |
| COhjyGoJU6h | 13 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t4, t6, t10, t12, t14 |
| DGdwNO3MHGX | 7 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | (none: Reel is 3.1-3.2 s) |
| DRDFfJykhas | 18 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t6, t10, t16, t20, t24 |
| DVpZdSlE5yW | 12 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t4, t6, t8, t10, t12 |
| DYOWKXztMak | 17 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t6, t10, t14, t18, t22 |
| DcSyV_8TteX | 12 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t4, t6, t8, t10, t12 |
| DWq2uH5EYRr | 30 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t12, t20, t30, t38, t48 |
| DYGJj_hh-AG | 17 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t6, t10, t14, t18, t22 |
| DVW04JmAJ9M | 10 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t4, t6, t8 |
| DX01rywuFBU | 9 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t4, t6 |
| DXy83WxIA0W | 13 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t4, t6, t10, t12, t14 |
| DUQ4KdeE4y1 | 18 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t6, t10, t16, t20, t24 |
| DVcUo1UiO9I | 11 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t4, t6, t8, t10 |
| DdR_XpIxnSn | 13 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t4, t6, t10, t12, t14 |
| DDHWGlShoYv | 11 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t4, t6, t8, t10 |
| DehBTdARxwn | 11 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t4, t6, t8, t10 |
| DV81W7jjlI4 | 13 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t4, t6, t10, t12, t14 |
| DcB1eeyKhVT | 16 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t6, t10, t12, t16, t20 |
| DTaaTbQEnl2 | 12 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t4, t6, t8, t10, t12 |
| DRpOyeNj6th | 9 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t4, t6 |
| DWFWX7EETHM | 9 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t4, t6 |
| DU_ojQkktjI | 11 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t4, t6, t8, t10 |
| DTkXR5mDDBb | 16 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t6, t10, t12, t16, t20 |
| DUieJX4k04B | 11 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t4, t6, t8, t10 |
| DVOaskok8Ju | 13 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t4, t6, t10, t12, t14 |
| DSvXnkWiK3t | 16 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t6, t10, t12, t16, t20 |
| DX7J0KZgJtY | 12 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t4, t6, t8, t10, t12 |
| DCBqQUIM416 | 10 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t4, t6, t8 |
| DEoXfBqvcbH | 14 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t4, t8, t10, t14, t16 |
| DT-ICI1EX4x | 23 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t8, t14, t22, t28, t34 |
| DUqpt5SgW64 | 17 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t6, t10, t14, t18, t22 |
| CbIDNhuBWcQ | 7 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | (none: Reel is 3.1-3.2 s) |
| DMYJp2EPjTU | 13 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t4, t6, t10, t12, t14 |
| DZ7nucvPhwX | 12 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t4, t6, t8, t10, t12 |
| DWFFTuMjA6B | 45 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t18, t32, t48, t62, t78 |
| DVevrXHDexl | 34 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t12, t24, t34, t46, t56 |
| DXkamtjkX7U | 11 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t4, t6, t8, t10 |
| Dc9TLv9tdIu | 81 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t32, t62, t90, t120, t150 |
| DTI1-P8kU8B | 20 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t8, t12, t18, t22, t28 |
| DMxCWfiNJFk | 11 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t4, t6, t8, t10 |
| DT_g52IDEPt | 10 | t0, t0_5, t1, t1_5, t2, t2_5, t3 | t4, t6, t8 |

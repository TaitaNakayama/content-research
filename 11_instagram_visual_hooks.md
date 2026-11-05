# 11. Instagram Reels: what is actually on screen (visual hook analysis)

For Taita (taita.del / taita.talks / ごはんとも). Source: 18 real Reels, frames captured from a rendered video element, so burned-in text is visible. Likes, duration and captions are from `manifest.tsv`. Everything below is something I saw in a frame I opened, or is marked as inference.

**Frames I actually opened.** All 18 Reels: t0, t1 and t3, which bracket the hook window. I also opened t2 on 12 of them and t0_5 on 2 (DcJZ3nbvXJA, DUuR). Late frames were sampled per Reel to find the payoff or ending. I did NOT open every hook-window frame (t0_5, t1_5, t2_5 are mostly unseen), so text that flashes on and off between sampled frames could be missed. Per-Reel frame lists are in section 7.

A 19th folder, `DRpOyeNj6th`, exists on disk but has no manifest row. I did not analyse it.

---

## 1. All 18 Reels

"Text at t0" means burned-in text visible in the t0 frame, transcribed exactly. "Diverges" compares on-screen words with the caption: yes / no (match) / n.a. (no on-screen words to compare).

| # | Shortcode | Bucket | Likes | Dur (s) | On-screen text at t0 (verbatim) | Diverges from caption? | Format |
|---|---|---|---|---|---|---|---|
| 1 | DcJZ3nbvXJA | format_trend | 18M | 25.9 | (none) | n.a. | other: audio-synced beat-match trend (caption says Peking-opera beat sync; audio unseen) |
| 2 | DKYTBJ6pjY2 | fmt_sensory | 12M | 8.0 | (none) | n.a. | ASMR/sensory |
| 3 | DV79WToDXwb | viral_format | 11M | 8.8 | `Dear basketball...🥀` | **yes** | single-feat (dunk) with tribute/eulogy framing |
| 4 | DVD2QASk3pi | viral_format | 9M | 19.1 | `AAJ TOH BACH GYE 😮‍💨` | **no** (near-identical to caption's first words) | other: scripted comedy skit |
| 5 | Dd3DS5NCBxA | fmt_sensory | 7M | 86.1 | (none) | n.a. | ASMR/sensory (marble track) |
| 6 | DVpZdSlE5yW | viral_format | 7M | 13.4 | (none; 3D saw blade carries in-scene watermark "HariXFilm" at t2) | n.a. | other: 3D animation, "trick revealed" |
| 7 | DTbCZsqEjeq | fmt_challenge | 6M | 18.6 | no headline; numerals `8` `7` `6` pinned to obstacles | partial (labels only, caption lists the moves) | challenge-run |
| 8 | C-5RrctAoPq | fmt_sensory | 5M | 60.8 | (none) | n.a. | ASMR/sensory (cutting foam) |
| 9 | Dcb8yXZyRsi | sport_extra | 5M | 14.6 | (none) | n.a. | compilation / cinematic highlight montage |
| 10 | DUuRWW_ie96 | talks_advice | 4M | 18.0 | (none at t0); Hindi subtitle appears by t0.5 | **yes** | talking-head (speech clip with burned subtitles) |
| 11 | C6W_ZcyN_El | format_trend | 4M | 9.5 | (none) | n.a. | near-miss (bail) |
| 12 | DcJdD-qTlWA | other_sport | 3M | 24.1 | (none) | n.a. | single-feat (dyno) |
| 13 | COhjyGoJU6h | movement_adj | 3M | 14.9 | (none) | n.a. | other: solo martial-arts form in nature |
| 14 | DGdwNO3MHGX | movement_adj | 3M | 3.1 | (none) | n.a. | single-feat (triple kick, board break) |
| 15 | DRDFfJykhas | fmt_challenge | 3M | 25.4 | no headline; numerals `2` `1` pinned to obstacles | partial (caption asks "Which move do you think is the hardest?") | challenge-run |
| 16 | DYOWKXztMak | fmt_commentary | 170K | 23.9 | `Automatic Transmissions` + two droopy-eyed face emoji (exact glyph unclear to me) | **yes** | talking-head (green-screen commentary) |
| 17 | DcSyV_8TteX | talks_life | 169K | 12.2 | `3 Din daily college attend karliya !!!` | **yes** | other: relatable skit / meme-reaction, text-led |
| 18 | DWq2uH5EYRr | talks_life | 169K | 48.8 | `Advice I WISH I knew when  I started College` | **yes** | talking-head (advice listicle) |

Counts at t0:
- Real headline text: **5 of 18** (DV79, DVD2, DYOW, DcSyV, DWq2).
- Numeric obstacle labels only: **2** (DTbC, DRDF).
- Subtitles starting around t0.5: **1** (DUuR).
- Nothing at all in the hook window: **10**.

---

## 2. The on-screen-text playbook

### What the sample says first

Burned-in headline text is not what the biggest Reels run on.

| Likes tier | Reels | Headline at t0 | Numeric labels / subtitles | Nothing |
|---|---|---|---|---|
| 9 Reels, 5M to 18M | DcJZ3, DKYT, DV79, DVD2, Dd3D, DVpZ, DTbC, C-5R, Dcb8 | 2 (DV79, DVD2) | 1 (DTbC) | 6 |
| 6 Reels, 3M to 4M | DUuR, C6W, DcJdD, COhj, DGdw, DRDF | 0 | 2 (DUuR subtitles, DRDF labels) | 4 |
| 3 Reels, about 170K | DYOW, DcSyV, DWq2 | **3 of 3** | 0 | 0 |

The three lowest-like Reels all lead with a text headline. The two 18M and 12M Reels have none. This is almost certainly a bucket effect, not a text effect (see section 6). Pure-visual formats (sensory, athletic feat) do not need text. Talk and commentary formats cannot work without it. Do not read this as "text hurts".

### The five real headlines

| Text (verbatim) | Likes | Words | Position in frame (my estimate) | Style | Shape |
|---|---|---|---|---|---|
| `Dear basketball...🥀` | 11M | 2 + ellipsis + 1 emoji | lower third, about 73% down | black text in a white rounded box | unfinished fragment (open loop) |
| `AAJ TOH BACH GYE 😮‍💨` | 9M | 4 + 1 emoji | upper third, about 18% down | red all-caps, white outline | exclamation fragment, Hinglish |
| `Automatic Transmissions` + 2 emoji | 170K | 2 + 2 emoji | very top, about 8 to 15% down | black on white box, wraps to 2 lines because of the emoji | topic label |
| `3 Din daily college attend karliya !!!` | 169K | 6 | middle-lower, about 60 to 64% down | yellow bold, black outline | statement with `!!!`, Hinglish |
| `Advice I WISH I knew when  I started College` | 169K | 8 | upper-middle, about 27 to 31% down, over the forehead | white with dark outline, TikTok-native caption style, "WISH" capitalised | title / promise |

### Patterns I can actually support (n = 5, so treat as hypotheses)

1. **Both headlines on the 9M+ Reels are 4 words or fewer and end in an emoji.** The three at about 170K are a topic label with emoji (2 words), then 6 and 8 words with no emoji. Short plus emoji is the only thing the two big ones share. With n = 2 I can't say it caused anything.
2. **The big two describe a feeling or a stance, not the content.** "Dear basketball...🥀" and "AAJ TOH BACH GYE 😮‍💨" say nothing about what happens. The smaller three say what the video is about ("Automatic Transmissions", "Advice I WISH I knew when I started College"). Inference: the big ones sell an emotional frame, the smaller ones sell a topic.
3. **The three emoji are all deflated or low-energy.** The wilted rose is loss, the exhaling face is relief or exhaustion, and the two droopy-eyed faces are weary (glyph unclear to me). None is a high-energy emoji like fire or a rocket. This is n = 3.
4. **No question headlines.** All five are statements or fragments. None is a question. (One caption is a question: DRDF's "Which move do you think is the hardest?", which is the caption doing the engagement job.)
5. **Text is on from the first frame and stays.**
   - DV79: seen at t0, t1, t3, t6, t8 (the whole 8.8 s).
   - DVD2: seen at t0, t1, t3, t6, t14 (the whole 19 s).
   - DcSyV: seen at t0, t1, t3, t10.
   - DWq2: seen at t0, t1, t3, t20.
   - DYOW is the exception. The headline is on at t0, t1, t3 and t6 and gone by t10, where the background has switched to a different slide.
   This is persistent static text, not animated or timed text. I can't see motion or fade-ins from still frames.
6. **Positioning does not converge.** Headlines sit at top, upper-middle, middle-lower and lower third. No single "right place" is visible. In DV79 and DcSyV the text is over the empty floor or desk area, not the face or the action. In DWq2 it sits over the forehead.
7. **Numeric labels are a separate device.** The two ninja-course Reels (DTbC 6M, DRDF 3M) have no headline. They pin large outlined numerals to the obstacles themselves (`8`, `7`, `6`... and `2`, `1`...). Some numerals change colour to green as the kid reaches them (DRDF t3 `2` green, t24 `8` green). Inference: the numerals give viewers a shared vocabulary to answer the caption's "which move is hardest" question. I didn't verify this against comments.
8. **Subtitles are a third device (DUuR, 4M).** No headline at t0. A small white sentence sits in the lower-middle (about 62% down). Frames I read:
   - t1: `लोग कहते हैं बादाम खाने से अक्ल बढ़ती है।`
   - t3: `पर भैया!`
   - t12: `उतनी बुद्धि सही होगी`
   My rough reading: "people say almonds make you smarter" / "but, brother!" / "that much sense will be right". These are my translations and approximate. The structure is claim, then a pivot. The speaker is seated in a framed window on a black background, so the 9:16 frame has large black bars. The proverb in the caption never appears on screen in the frames I opened.
9. **In-scene branding is a fourth.** DVpZ (7M) renders its handle "HariXFilm" onto the 3D saw blade at t2. It is a watermark made part of the scene, not a hook.

---

## 3. Caption vs on-screen text (the section a caption-only analysis cannot produce)

**Of the 6 Reels with any burned-in words (5 headlines plus the DUuR subtitles), 5 diverge from the caption and 1 matches (DVD2).** Two more (DTbC, DRDF) have only numerals, which complement their captions. The other 10 have no on-screen words, so caption-only analysis is not wrong about text for those. It is still blind to their visuals.

| Reel | On-screen | Caption (manifest) | What each is doing |
|---|---|---|---|
| DV79 (11M) | `Dear basketball...🥀` | "Almost had it🥀 #basketball #ballislife #viral #reels #dunk" | **Diverges.** Screen frames it as a tribute (the "Dear Basketball" phrasing, wilted rose). Caption reads as a near-miss. They share only the 🥀 emoji. The actual footage: a 1v1 at t0, a hoop shot at t3, a dunk at t6, and a **shattering backboard at t8**. Inference: the eulogy framing is ironic, because what dies is the hoop. The tribute reading comes from the on-screen text, not the caption. |
| DVD2 (9M) | `AAJ TOH BACH GYE 😮‍💨` | "Aaj toh Bach giye 😮‍💨🙏 ... Disclaimer ... scripted" | **Match.** The caption's opening is the overlay almost word for word (spelling differs: GYE vs giye). Text and caption are doing the same job, hooking with the line. The caption adds 🙏, hashtags and a "scripted" disclaimer. |
| DYOW (170K) | `Automatic Transmissions` + droopy-face emoji | "Can't tell me this isn't alien technology😭😭 #car ..." | **Diverges.** Screen is a topic label with a weary emoji. Caption is the opinion and awe line with crying emoji. The registers differ: tired label, amazed caption. |
| DcSyV (169K) | `3 Din daily college attend karliya !!!` | "Motivation high hogyi😭😂 . . . ( reels Instagram , college students ... )" | **Diverges, and they read in sequence.** Screen is the setup ("attended college 3 days in a row!!!"). Caption is the punchline and mood ("motivation is high"), then a long keyword dump. Translations are mine, approximate. |
| DWq2 (169K) | `Advice I WISH I knew when  I started College` | "#collegelife #collegehacks #student #advice #college" | **Diverges completely.** The caption is hashtags only. The entire hook lives on screen. A caption-only read sees no hook at all. |
| DUuR (4M) | Running Hindi subtitles | "जितनी ठोकरें उतनी समझदारी!🌸 #Reality ..." (my rough reading: "the more stumbles, the more wisdom") | **Diverges.** Subtitles carry the spoken argument line by line. Caption is the thesis. They point at the same theme, so I count this as different jobs, not contradiction. |
| DTbC (6M) | numerals only | Full obstacle-by-obstacle description | **Complementary.** Numerals on screen, move names in the caption. |
| DRDF (3M) | numerals only | "Ring tech on skyhooks, gotta go hook to slot and out ... Which move do you think is the hardest?" | **Complementary.** Numerals on screen, comment prompt in the caption. |

### Jobs I can see

- **On-screen text:** hook, frame or stance, setup line, topic label, running subtitle, or obstacle numbering.
- **Caption:** mood or punchline, thesis, the question to answer in comments, description of the feat, credits and tags (Dcb8's whole caption is "🤝 @noemie.glover #asu #volleyball #avca video by: @shotbyklvg"), disclaimers, hashtag dumps.

---

## 4. Opening frame composition

I sorted every Reel by what the subject is doing at t0 (and what t1/t3 confirmed).

**Mid-action (7)**: motion or process already underway at t0.
- DKYT: macro of a bubble-wrap flattening device in progress.
- DV79: 1v1 dribble already live.
- C-5R: a foam slab already descending, a hand in frame.
- Dcb8: a setter mid-set at the net.
- DcJdD: climber already on the overhanging wall.
- DGdw: a runner already running in at the back of the room (the kick lands by t2 of a 3.1 s Reel).
- DVpZ: a saw already descending toward a rolling pin.

**Setup, action begins within about 1 to 3 s (6)**
- DcJZ3: wide ambient pier, the odd move starts at t1.
- Dd3D: hand placing the marble at the top of the track.
- DTbC: kid standing on a step, arms up, hanging from a bar by t1.
- C6W: walking up to the obstacle, the jump comes at t6.
- COhj: standing, jogging at t1, kick at t3.
- DRDF: kid on a step, on the bar by t1.

**Static / talking / text-led (5)**
- DVD2: selfie in a car, mouth closed.
- DcSyV: static classroom shot, text-led, with a meme clip inserted.
- DUuR, DYOW, DWq2: talking heads (DYOW mid-gesture, DWq2 mid-sentence, DUuR smiling with subtitles starting by t0.5).

**Where they sit by likes**
- 13 of the 15 Reels at 3M or more open mid-action or in setup (7 + 6). The two exceptions are DVD2 (9M, scripted skit) and DUuR (4M, talking-head clip).
- All 3 of the ~170K Reels are in the static/talking group.
- **No winner opens on a title card, black frame or establishing shot with no subject.** The static ones still have a person and a situation on screen from frame 0.

Important caveat in section 6: "static" openings cluster in the low-likes buckets, so I can't separate the opening from the format.

### Payoff timing where I could see it

Fractions of duration. Reels with no clear single payoff are marked.

| Reel | Payoff | When |
|---|---|---|
| DV79 | dunk at t6, backboard shattering at t8 | about 0.68 to 0.91 of 8.8 s |
| DGdw | kick contact with the boards flying | about t2 of 3.1 s, about 0.65 |
| C6W | jump onto the green arch at t6, then a blurred falling-camera frame at t8 (the bail) | about 0.63 to 0.84 of 9.5 s |
| DcJdD | dyno launch at t8 to t10, a different-angle later climb at t20; I did not see the finish | dyno about 0.33 to 0.41 of 24.1 s |
| COhj | kick at t3 | about 0.20 of 14.9 s (rest of the form unseen) |
| C-5R | the first cut is already done by t3 (smoke over cut pile), t30 shows another block over the pile | repeating loop, first payoff in the first 5% of 60.8 s |
| DKYT | progressive flattening, already a large flattened area by t2 | continuous loop, no single payoff |
| Dcb8 | montage; celebration frame at t14 | about 0.96 of 14.6 s |
| Dd3D | marbles falling through a hole at t80 | about 0.93 of 86.1 s (which marble "wins" not confirmed) |
| DTbC | last numbered obstacle, `1`, being attempted by t16 | about 0.86 of 18.6 s |
| DRDF | `8` highlighted green with the kid on the last trapeze at t24 | about 0.94 of 25.4 s |
| DVD2, DcJZ3, DUuR, DVpZ, DYOW, DcSyV, DWq2 | no single payoff identifiable from the frames I opened (several are audio-driven or speech-driven) | not determined |

Pattern: short single-feat Reels (DV79, DGdw, C6W) land the feat after the first third, in the 0.63 to 0.91 range. Long challenge-run Reels put the finish at the very end (0.86 to 0.94). Sensory Reels have no moment, they have a loop.

---

## 5. What Taita should put on screen (observed, then inferred)

Everything labelled "inference" is my extrapolation, not something the frames show.

### taita.del (tricking)

What the frames show: the closest comparables are single-feat and challenge Reels (DGdw 3M, DcJdD 3M, COhj 3M, C6W 4M, DTbC 6M, DRDF 3M). None has a headline. They open mid-action or in a 1 to 2 s setup, and the feat lands between about 0.3 and 0.9 of the runtime.

- **Default to no headline** on a clean trick. Open with the run-up already in motion, not a standing pose.
- **If you want a framing line**, copy what the one big framed athletic Reel did (DV79, 11M): 2 to 4 words, a fragment, a single emoji, lower third, left on for the whole Reel. Frame a feeling, not the trick name. "Dear basketball...🥀" never says "dunk".
- **For combos or chains**, the ninja Reels' numeral overlay is the one device that is native to sport content in this sample. Inference: pin `1 2 3 ...` to each trick in a chain and turn it a different colour as each one lands, then ask "which was the hardest?" in the caption as DRDF does.
- **For a bail or near-miss**, C6W (4M) uses no text. The context ("Goodbye 🫡👋🏻 пока... A bail from previous years") is entirely in the caption, and the bail lands about 2/3 of the way through.

### taita.talks (raw one-take talking)

What the frames show: three talking-head Reels (DWq2 169K, DYOW 170K, DUuR 4M). All open mid-speech or mid-gesture. None opens on a title card.
- DWq2: the whole 8-word title on screen from the first frame to at least t20.
- DYOW: a 2-word topic label that drops by about t10 when the background slide changes.
- DUuR (the 4M one): no title, a running subtitle starting within the first half second.

Suggestions:
- **First frame is mid-sentence.** All three do it.
- **Put the promise on screen in the first frame**, not in the caption. DWq2's caption is hashtags only, so if the title weren't on the video there would be no hook anywhere.
- **Consider subtitles**, since the 4M talking-head used a claim-then-pivot subtitle chain ("people say X" then "but, brother!"). I can't tell whether subtitles or the bigger audience drove the gap between DUuR and the other two (see limits).
- **Keep the caption for the thing the screen doesn't say** (the take, the question), not a copy of the title. Only DVD2 copied its overlay into the caption, and it was a skit, not a talking head.
- Your raw one-take style has no match in this sample. The closest talking heads here use cutaways (DYOW changes the slide every roughly 10 s) or a face-only hold (DWq2). I have no data on pure one-take, no-cut talking.

### ごはんとも (Japanese calorie app)

What the frames show: **nothing in this sample is food, health or Japanese.** Everything below is inference from adjacent formats only.
- The sensory Reels (DKYT 12M, Dd3D 7M, C-5R 5M) have zero text and open with a process already underway. If you film food prep or plating, the sample supports opening on the action with no headline.
- The text-led relatable Reels (DcSyV, DWq2, both about 169K) show the typical shape: one situation line of 6 to 8 words on screen, with the punchline or mood in the caption. These are the lower-reach examples here.
- The 9M skit (DVD2) shows the short mood-line version: 4 words and an emoji.
- I have no observations of Japanese-language overlays. The sample's text is English, Hinglish (romanised Hindi) and Devanagari. Do not assume the length, line-break or emoji conventions above carry to Japanese. Test your own.
- Suggested test: post the same clip twice, once with a 2 to 4 word fragment plus one emoji at the lower third and once with none, and compare. This sample cannot settle it.

---

## 6. Honest limits

1. **18 Reels.** Five headline examples, two with 9M+ likes, three at about 170K. Every "pattern" in section 2 is a hypothesis. Several rest on 2 or 3 data points.
2. **Likes, not reach.** I have no views, shares, saves, follower counts or watch-time. 18M vs 170K is a 100x spread driven by account size and distribution as much as by the Reel. Likes can't show if the hook worked.
3. **Buckets are uneven and confounded with format.** The three lowest-like Reels are all talk or commentary buckets. They also are the three that depend on text. I can't separate "text-led" from "talk bucket" from "smaller account". The finding "winners are visual, with no text" is as much about bucket choice as about text.
4. **Seeding bias.** These were picked from bucket lists (viral formats, trending formats, sensory, sport extras). They aren't a random sample of posts, and a large share are re-uploads or trend clips.
5. **Still frames can't show timing.** I can't see whether text animates in, fades or flashes, how long a caption stays between my sampled frames, or edit rhythm. A flash of text between two sampled frames would be missed. I looked at t0, t1, t3 for all 18, t2 for 12, and t0_5 for 2. Many hook-window frames were not opened.
6. **No audio.** Music, voiceover, trending sounds and spoken hooks are invisible to me. For DcJZ3 (18M), the trend is a Peking-opera beat sync. The frames show a man walking, flailing and sitting in water, and nothing explains why it's at 18M. In the Hindi talking-head, the burned subtitles may only be part of the hook. For DYOW, DWq2 and DUuR the spoken first sentence is probably the real hook and I can't hear it.
7. **My translations are approximate.** Hindi and Hinglish glosses in sections 2 and 3 are my own and flagged. The two droopy-faced emoji in DYOW I could not pin to an exact glyph. I did not invent any other text.
8. **Blurry or unreadable frames:** DWq2 t46 shows a tablet screen with a document. The heading looks like "Playbooks" but is mostly blurred, and I can't read the body text. I treat it as `[illegible]`. It may be a call-to-action, which I can't confirm.
9. **Payoff times are estimates** from sampled frames at 1 to 2 s steps, with some at 10 s or longer. Treat them as ranges.

---

## 7. Frames opened per Reel (for audit)

| Shortcode | Frames opened |
|---|---|
| DV79WToDXwb | t0, t1, t3, t6, t8 |
| DcJZ3nbvXJA | t0, t0_5, t1, t2, t3, t12 |
| DKYTBJ6pjY2 | t0, t1, t2, t3 |
| DVD2QASk3pi | t0, t1, t3, t6, t14 |
| Dd3DS5NCBxA | t0, t1, t2, t3, t80 |
| DTbCZsqEjeq | t0, t1, t2, t3, t16 |
| C-5RrctAoPq | t0, t1, t2, t3, t30 |
| Dcb8yXZyRsi | t0, t1, t2, t3, t8, t14 |
| DUuRWW_ie96 | t0, t0_5, t1, t3, t12 |
| C6W_ZcyN_El | t0, t1, t2, t3, t6, t8 |
| DcJdD-qTlWA | t0, t1, t2, t3, t8, t10, t20 |
| COhjyGoJU6h | t0, t1, t2, t3, t12 |
| DGdwNO3MHGX | t0, t1, t2, t3 |
| DRDFfJykhas | t0, t1, t2, t3, t24 |
| DVpZdSlE5yW | t0, t1, t2, t3, t10 |
| DYOWKXztMak | t0, t1, t3, t6, t10, t14, t22 |
| DcSyV_8TteX | t0, t1, t3, t10 |
| DWq2uH5EYRr | t0, t1, t3, t20, t46 |

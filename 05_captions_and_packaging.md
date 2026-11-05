# 05 — Captions, On-Screen Text, Packaging, Platform/SEO Mechanics

Written for Taita. Research date: 2026-11-05.

## Read this first: how strong is the evidence?

Be skeptical of this whole area. What I found:

- **Platform primary sources are thin.** TikTok's Integrity & Authenticity guideline page was reachable and is quoted below. TikTok's "how we recommend content" page and Instagram/YouTube help pages would not load or gave no usable text. The Social Media Today write-up of Instagram's hashtag cap quotes Instagram directly.
- **Almost all the TikTok SEO material is vendor/agency blog content.** It repeats itself, cites no studies, and contradicts itself on weights. I treat it as "practitioner consensus, unmeasured".
- **No source I found has controlled tests of on-screen hook text.** Recommendations on text are practitioner opinion. I mark my own reasoning `[inference]`.
- **I could not reach TikTok/Instagram pages**, so I could not read on-screen text of real videos. The "real examples" I can give are YouTube titles and pages that surfaced in search; I did not see their on-screen text. Where I give example text, it is a template, not a quote.
- Nothing here is tied to Taita's own analytics. The fastest way to settle most open questions is an A/B hook-text test on your own `taita.del` posts (see the end).

---

## 1. On-screen hook text

### What the sources actually say

| Claim | Source | Quality |
|---|---|---|
| Put the core message in text in the first 3 seconds because many viewers start muted; bigger text for the first 3s; one message per video; highlight keywords in a contrasting color | [bloomeria.jp hook templates 2026](https://bloomeria.jp/blog/short-video-hook-templates-2026) | Agency blog, no data, says so itself ("testing recommended") |
| For talk-driven channels, a hook that states the conclusion in text works well | same, and [0120.co.jp](https://0120.co.jp/blog/video-125/) summary snippets | Opinion |
| Bold white text with black outline "highest retention" | bloomeria (attributes to CapCut/Vrew/Adobe, no figures) | Unverified |
| Japanese telop readability baseline: max 13 full-width chars per line, 2 lines, max 4 chars/second (Netflix Japanese Timed Text Style Guide, as cited); the author's own advice for vertical short video: 8-10 chars/line, 1-2 lines, centre to slightly below centre, avoid bottom edge and right side | [0120.co.jp video-125](https://0120.co.jp/blog/video-125/) | Netflix numbers are for subtitles, not TikTok; the 8-10 figure is the author's recommendation |
| Contrast ratio at least 4.5:1 (WCAG 2.1) | same | Standard, but not TikTok-specific |
| First slide of a photo carousel "has one job": earn the swipe with a specific claim or curiosity gap, not a topic label; bottom ~20% is covered by TikTok UI | [CineRads](https://www.cinerads.com/blog/how-to-add-text-hooks-to-tiktok-product-slideshows) (via search snippet) | Vendor |

### What I recommend (inference, built from the above)

**Length.** Hook text of 2 lines, 8-12 full-width characters per line in Japanese, or 4-8 words total in English. If it needs a third line, the hook is two ideas; cut one. [inference]

**Duration.** Hook text sits on screen for the first ~2.5-3 seconds, then is replaced. At the 4 chars/second ceiling a 12-character hook needs ~3s to read, so a Japanese hook of ~12 characters should live for the full 3 seconds. [inference from the 4 cps figure]

**Whole-video or not?**

| Account | Keep text up? | Why [inference] |
|---|---|---|
| `del` | Hook text 0-3s only, then clear the frame. Optional tiny persistent label (corner/top) naming the trick. | The trick is the product; text over the flip hurts the clip. Viewers who rewatch should see clean motion. |
| `talks` | Hook line 0-3s, then **auto-captions** (not a hand-edited timeline) for the rest. | Your hard constraint is zero editing. In-app auto captions cost nothing and double as searchable text (see section 3). |
| `gohantomo` | Slide 1 = hook. Every slide carries one short line. | Photo posts have no audio hook; text is the whole hook. |

**Placement.** Upper-middle, clear of the top status area and the bottom ~20% where caption/username/buttons sit. [vendor claim, widely repeated; consistent with how TikTok and Reels UI render]. For Reels, keep key text in the central 1080x1350 region so it survives both the 4:5 feed preview and the 3:4 grid crop ([HopperHQ](https://www.hopperhq.com/blog/instagram-reel-size/), [Socialkit](https://socialk.it/en/blog/instagram-reel-covers-guide) — vendor).

### Contradict vs. reinforce the spoken hook

There is no measured evidence either way. My working rules [inference]:

- **Reinforce** when the goal is search + clarity (`talks`, `gohantomo` how-to). Same keywords in speech, text and caption is the one thing the SEO sources agree on (section 3).
- **Add a second layer** when the video is visual and has no speech (`del`). The text states the stakes, the video shows them: text "I crashed this 10M-view trick. Today I land it." over a clean run-up. The text carries a promise the video pays off.
- **Contradict** only as a loop/curiosity device, and only if the payoff comes inside the clip: speech says "this is easy", text says "(it took me 4 years)". It costs a viewer a beat of confusion, so use it on `talks` where spoken delivery is the product, and test it before relying on it.

### Per-niche example patterns (templates, not observed on-screen text)

Real pages that show the *pattern in titles* (I could not view on-screen text):

- Tricking contrast format: ["Right vs Wrong Backflip"](https://www.youtube.com/shorts/wOHbaI46l1E), contrarian tutorial: ["How to TRICK people you can BACKFLIP"](https://www.youtube.com/shorts/RtbYn4fhU_k), failure framing: ["I Tried a WORLD RECORD Backflip in Tricking 0 (and failed)"](https://www.youtube.com/watch?v=AVMTxD85qoY).
- Japanese diet "contrarian + reason" titles from dietitian Shorts: ["1200kcalは痩せない！代謝が下がる危険なダイエット法"](https://www.youtube.com/shorts/pV0XyRGg-gA), ["夕食抜きがあなたを太らせる！？"](https://www.youtube.com/shorts/HEWj4qFElYQ), ["【カロリーメイトの真実】..."](https://www.youtube.com/shorts/HkrjA21vcFw). These are what Japanese viewers are used to seeing in the diet niche; their claims are the creators' own and unverified.
- Japanese student-founder framing: ["19歳で起業するも5回失敗。残高200円から..." (Kakedas)](https://www.youtube.com/watch?v=kmTNDl15x_A), ["【前編】大学にオフィスを作ってしまった学生社長に年収聞いてみた"](https://www.youtube.com/shorts/k_ennX2pOlY).

### Cal AI reference (the format Gohantomo is copying)

- A Playkit newsletter breakdown lists Cal AI-linked formats: text overlay + background video + sound effects (no dialogue), a "guess the calories" challenge, skits and day-in-the-life; it also claims 40M+ views across 200+ videos (**unverified, third-party**). [Playkit](https://playkit.beehiiv.com/p/calorie-tracker-app)
- The founder interviews I found emphasise a paid-influencer system (~250 creators on fixed monthly fees as of May 2025, per Latka) and hook/format testing at volume, not a magic caption. [Latka](https://getlatka.com/companies/calai.app/interviews/cal-ai-zach-yadegari-2025), [NetInfluencer](https://www.netinfluencer.com/cal-ai-founder-zach-yadegari-breaks-down-the-influencer-playbook-behind-his-apps-growth/), [TechCrunch](https://techcrunch.com/?p=3178431). I did not find a slide-by-slide teardown with actual slide-1 wording. **Do not assume the US wording transfers**; there is no Japan-specific evidence I could find that photo slideshows work for Japanese calorie apps (the only Japan photo-mode results were 2022 how-to articles, e.g. [find-model.jp](https://find-model.jp/insta-lab/tiktok-photo-post/)).

---

## 2. Captions / descriptions

### What is evidenced

- **TikTok caption limit** is reported as 2,200 characters, with the app sometimes allowing more, and only the first ~1-2 lines visible before "more" (vendor figures; [howmanywords.app](https://howmanywords.app/ja/ブログ/tiktok文字数制限) via search). A note.com marketing post says the description was extended from 300 to 2,200 ([Union](https://note.com/union_ad_master/n/ndafc20c9dc94)). A 2022 Japanese note says the visible description is about 150 characters ([CDA Inc., 2022-02-10](https://note.com/cdainc/n/n61a213b892ae)). Treat all as approximate and check the app.
- **Same wording across speech, on-screen text and caption** is the single consistent recommendation in both English and Japanese sources ([Capcut guide](https://www.capcut.com/create/tiktok-caption-keywords-discoverability), [ざわ所長 note, 2026-08-01](https://note.com/client_worker/n/n70335a790916)).
- **Question-ending captions raised comments on one account.** CDA Inc. reports one post ending with a question got 10x its usual views and 41 comments vs. 1-2 usual; and a "share to LINE and the 3rd person confesses to you" caption took shares from 1-2 to 1,096 and the video past 1.3M views. This is one agency's own account, 2022, anecdotal.
- **Caption-writing also drives search** (section 3).

### What I recommend [inference unless cited]

| Question | Answer |
|---|---|
| Length | 1 line for `del` (a keyword phrase + one CTA). 2-3 short lines for `talks`. For `gohantomo`, 1-2 lines for the answer to the hook + one search phrase. Long captions only if they are search copy for a how-to. |
| Restate the hook? | Not word-for-word. Restate the **topic keyword**, not the punchline: the caption should say what the video is about so search can match it, while the video keeps the surprise. |
| CTA | One ask, tied to the content. Follow CTA only works when attached to a series ("Part 2 tomorrow, follow so it doesn't get buried"). A generic "follow for more" has no evidence behind it. |
| Comment-bait | Ask a question that only your audience can answer ("Which trick should I teach next?"), not "like if you agree". |
| Deliberate incompleteness | Works if the video is a series and the next part exists. If it is a one-off, it reads as a trick. |
| "Wrong on purpose" | Use only for trivia where the correction is harmless (e.g. "this is a front flip, right?" on a clearly different trick). Never for health, calorie or diet claims. |

### Risk of comment-bait that harms the account

- TikTok's Integrity & Authenticity guideline says content that tries to "manipulate people into giving gifts or inflating likes or follows isn't eligible for the FYF," and prohibits services that "artificially boost engagement or trick the recommendation system." [TikTok Community Guidelines](https://www.tiktok.com/community-guidelines/en/integrity-authenticity) (fetched 2026-11-05). The page does not use the phrase "engagement bait"; claims that "like if you agree" is penalised or that a shadowban follows come from vendor blogs and I could not verify them ([auditsocials](https://www.auditsocials.com/blog/tiktok-engagement-bait-community-guidelines) — vendor).
- Reasoned risks [inference]: (1) "Wrong on purpose" attracts correction-comments from non-audience viewers and trains the algorithm toward people who argue, not people who buy; (2) for a diet app, wrong-on-purpose calorie/nutrition claims create misinformation exposure; the TikTok page also says misinformation that could cause significant harm is removed and moderate-harm content is FYF-ineligible; (3) in Japan, health/diet claims also sit under Japanese advertising law (薬機法/景品表示法) — **I did not research this; check before launch**; (4) comment-bait that gets 500 comments from people who will never install the app inflates views without followers, which is already your core problem.

---

## 3. TikTok search / SEO

### What the evidence says

- Consensus across vendor guides: TikTok indexes **caption text, spoken audio (speech-to-text), on-screen text (OCR) and hashtags**; matching the same target phrase in all of them is the practical advice ([search summary of 15+ vendor guides](https://www.capcut.com/create/tiktok-caption-keywords-discoverability); [WeTheFlywheel](https://wetheflywheel.com/en/ai-search/how-to-rank-in-tiktok-search/)).
- The weights are **not agreed**: one guide calls the caption the highest-weighted field, another ranks hashtags medium. "First 3 seconds of audio, on-screen text, and first 80 characters of caption" appears as a definition in one agency post ([Rise at Seven](https://riseatseven.com/blog/tiktok-seo-statistics/)). The "first 50 characters" claim has no basis. Treat these numbers as folklore.
- A Japanese marketer's note (2026-08-01) points to **TikTok's own tools**: Creator Search Insights (shows search topics, popular searches, related searches, and a "Content gap" filter for demand without enough videos; "Searches by followers" reportedly needs over 1,000 followers) and Comment Insights. It argues the key is that content answers the searcher's specific problem, using the viewer's words from comments ("1 comment = 1 search = 1 video"). I only saw these tools via that note, not on TikTok's pages. [ざわ所長 note](https://note.com/client_worker/n/n70335a790916)
- **Gen Z search usage stats conflict** between sources (74% vs 65% vs 49%) — do not cite them.

### Filenames
I found **no evidence** that video filenames affect TikTok search. Skip.

### Spoken keywords
Auto-caption accuracy matters: vendor sources note poor auto-transcription can hurt. For `talks`, enunciate the target phrase and check the auto-caption spelling. For Japanese, check kanji conversion of keywords. [inference]

### Practical SEO routine (about 2 minutes per post)
1. Pick one phrase a person would type (e.g. `トリッキング 初心者 バク宙`, `カロリー 計算 写真`, `startup founder college`).
2. Say it in the first sentence. Show it in the hook text. Put it in the first line of the caption.
3. 2-4 hashtags max (below).

### Outdated warning
Every item above dates 2025-2026 and comes from marketing blogs. Several 2022-2023 Japanese notes (e.g. CDA 2022) predate the search push. Re-check Creator Search Insights in your own app; it is the only first-party instrument.

---

## 4. Hashtags — do they still matter?

| Platform | Current evidence | Practical call |
|---|---|---|
| **Instagram Reels** | Instagram said in Dec 2025 it would gradually cap hashtags at 5 per post/Reel, writing: "We find that using fewer (up to 5) more targeted hashtags, rather than many generic ones, can improve both your content's performance and people's experience on Instagram." ([Social Media Today, 2025-12-18](https://www.socialmediatoday.com/news/instagrams-implementing-new-limits-on-hashtag-use/808309/)). Mosseri said in Feb and May 2025 that hashtags don't boost reach but are "a great way to let people know what a post is about" (same article). | 3-5 specific tags max. They label; they do not distribute. |
| **TikTok** | No official limit found. Platform docs I could reach do not say hashtags drive reach. Vendors call them a secondary search signal. A 2022 Japanese agency note says hashtags "aren't that important" ([CDA](https://note.com/cdainc/n/n61a213b892ae)); a 2026 Japanese note warns more tags can blur the topic ([ざわ所長](https://note.com/client_worker/n/n70335a790916)). | 2-4: one topic tag, one niche tag, optionally one language tag. Caption keywords matter more. |
| **YouTube Shorts** | Only vendor sources (no YouTube help page reached). They say hashtags are minor, up to three show above the title, #Shorts is no longer required ([Social Media Today on suggested hashtags](https://www.socialmediatoday.com/news/youtube-experiments-with-suggested-hashtags-for-shorts-clips/639748/), [fluxnote](https://fluxnote.io/guides/do-youtube-hashtags-still-work-2026)). | 1-3 plus put the keyword in the **title**. |

Bottom line: hashtags are labels, not levers. Spend the effort on the first line of the caption and the spoken/on-screen phrase.

---

## 5. Covers / thumbnails

| Platform | Do covers matter? |
|---|---|
| **YouTube Shorts** | Custom Shorts thumbnails exist (rollout reported through 2025 and into 2026, sources disagree on timing; Partner Program first per some). They do **not** show in the swipe feed; they show in search, channel pages, subscriptions. YouTube's own stance in May 2025, per reports, was that "most thumbnails are never seen". [vidIQ](https://vidiq.com/blog/post/youtube-shorts-custom-thumbnails), [PPC Land](https://ppc.land/youtube-ends-2-year-wait-for-shorts-thumbnails-but-blocks-a-b-testing/), [AlternativeTo 2026](https://alternativeto.net/news/2026/7/youtube-introduces-custom-thumbnails-for-shorts-and-ask-studio-ai-thumbnail-generation/). Pick a clean frame; don't design. |
| **Instagram Reels** | Yes, for the **profile grid** (visitors deciding to follow). Grid shows ~3:4 crop of the 9:16 frame, losing roughly the top and bottom 240px of 1080x1920 (vendor claim, repeated across sources). Keep cover text inside the central band and re-pick the cover in Edit cover. |
| **TikTok** | Covers matter on profile grid and pinned posts only; in For You they do not. For photo posts, slide 1 is the cover [inference]. |

### What a good cover is [inference; no tests found]

- **del**: a clear mid-air frame of the hardest moment, **plus** 2-4 words naming the trick or stakes ("DOUBLE BACK", "after 3 years"). Consistent frame style across the grid so a new visitor sees a "tricking channel", which helps views→follows.
- **talks**: a clean face frame with the hook's keywords (topic, not question). Same font/colour every time so the grid reads as a series.
- **gohantomo slideshow**: slide 1 is the cover. Big food photo + mogumogu mascot + the number or claim. Katakana for the key word. (Do not clutter: Japanese users already see dense layouts; one focal point.)

---

## 6. Caption and hook-text bank

Legend: `del` tricking, `talks` talking head, `gohantomo` Japanese calorie app. Fill-ins in `[ ]`. JA lines are written for a mass Japanese audience, plain polite/casual register, no medical claims. Adjust to your voice. For `gohantomo` photo slides, JA hooks are slide-1 text; EN for `gohantomo` is for reference only (the audience is Japanese).

### Curiosity

| # | English | 日本語 | Acct |
|---|---|---|---|
| 1 | I landed [trick] after [N] years. Here's what changed. | [N]年かけて[技]をやっと決めた。変えたのは、たった1つ。 | del |
| 2 | Nobody told me this about [trick]. | [技]、誰も教えてくれなかったコツがあります。 | del |
| 3 | The one thing I wish I knew before [milestone]. | [出来事]の前に知りたかったこと、1つだけ。 | talks |
| 4 | I tracked [thing] for [N] days. Result: [number]. | [N]日間[こと]を記録した結果、[数字]でした。 | talks, gohantomo |
| 5 | This [food] has more calories than you think. | 実は[食品]、思ってるよりカロリー高いです。 | gohantomo |
| 6 | Guess the calories. (Answer on slide [N].) | これ何kcalでしょう？答えは[N]枚目。 | gohantomo |
| 7 | I tried [thing] so you don't have to. | [こと]、先に試してきました。 | talks, gohantomo |
| 8 | What happens when a [age] tries [thing]? | [年齢]歳が[こと]をやってみたら、こうなった。 | talks, del |

### Contrarian

| # | English | 日本語 | Acct |
|---|---|---|---|
| 9 | Stop doing [common thing]. Do this instead. | [よくあるやり方]はやめて。代わりにこれ。 | del, talks |
| 10 | [Popular advice] is actually backwards. | [よく聞くアドバイス]、実は逆でした。 | talks, gohantomo |
| 11 | You don't need [expensive thing] to [goal]. | [目標]に[高いもの]はいりません。 | talks, gohantomo |
| 12 | Everyone teaches [trick] wrong. Here's the fix. | [技]の教え方、みんな間違ってます。直し方はこれ。 | del |
| 13 | Counting calories isn't the hard part. [Real hard part]. | カロリー計算が大変なんじゃない。本当に大変なのは[こと]。 | gohantomo |
| 14 | Hot take: [opinion]. | ぶっちゃけ、[意見]だと思う。 | talks |
| 15 | You're not [lazy/weak]. Your [method] is the problem. | あなたが[怠け/弱い]んじゃない。やり方が合ってないだけ。 | talks, gohantomo |

### Tutorial / how-to

| # | English | 日本語 | Acct |
|---|---|---|---|
| 16 | How to [trick] in [N] steps. | [技]のやり方、[N]ステップで解説。 | del |
| 17 | [Trick] drill you can do at home. | おうちでできる[技]の練習法。 | del |
| 18 | Fix your [body part] on [trick] with this. | [技]で[部位]が崩れる人はこれを試して。 | del |
| 19 | How to log [meal] in [N] seconds. | [食事]を[N]秒で記録する方法。 | gohantomo |
| 20 | Photo to calories: how it works. | 写真を撮るだけでカロリーがわかる仕組み。 | gohantomo |
| 21 | How I [do thing] as a student with no [resource]. | [リソース]がなくても[こと]をやる方法（大学生版）。 | talks |
| 22 | Save this before your next [trip/meal/test]. | [旅行/外食/試験]の前に保存しておいて。 | gohantomo, talks |

### Authority

| # | English | 日本語 | Acct |
|---|---|---|---|
| 23 | Ranked 8th in the US. Here's how I train. | 全米ランキング8位が実際にやっている練習。 | del |
| 24 | I've coached 100+ students. Same mistake every time. | 100人以上教えて分かった、みんな同じところで間違える。 | del |
| 25 | UC Berkeley CS student, building [startup]. [Lesson]. | カリフォルニア大学バークレー校のCS学生が、[事業]で学んだこと。 | talks |
| 26 | I've built [N] startups. This is what I'd do first. | [N]個の事業をつくって分かった、最初にやるべきこと。 | talks |
| 27 | Built by a [dietitian/engineer]: why this app logs your meals. | [管理栄養士/エンジニア]の視点で作った、食事記録アプリ。 | gohantomo |
| 28 | The real numbers: [N] months of [thing]. | 実際の数字を公開。[N]ヶ月やった結果。 | talks, gohantomo |

(Claim "管理栄養士" only if true. Do not invent credentials.)

### Relatability

| # | English | 日本語 | Acct |
|---|---|---|---|
| 29 | POV: you finally land the trick you've failed for a year. | POV：1年失敗し続けた技がついに決まった瞬間。 | del |
| 30 | Me at 2am debugging instead of sleeping. | 深夜2時、寝ずにバグを直してる大学生。 | talks |
| 31 | When you say "just one snack" and it's 600 kcal. | 「ちょっとだけ」のつもりが600kcalだった時。 | gohantomo |
| 32 | Being 19 and not knowing what to do with life. | 19歳、人生どうしたらいいか分からない人へ。 | talks |
| 33 | Nobody warns you how scary the first flip is. | 初めてのバク宙、実はめちゃくちゃ怖い。 | del |
| 34 | I thought I ate healthy until I logged it. | 健康的に食べてると思ってたのに、記録してみたら違った。 | gohantomo |

### Comment-bait (use sparingly, see risk section)

| # | English | 日本語 | Acct |
|---|---|---|---|
| 35 | Which trick should I teach next: A or B? | 次に教える技はどっち？AかB、コメントで教えて。 | del |
| 36 | What would you ask a [college student/founder] about [topic]? | [大学生/起業家]に[テーマ]のこと、何でも聞いて。 | talks |
| 37 | Guess the calories before swiping. Comment your number. | スワイプする前に予想してコメントしてみて。 | gohantomo |
| 38 | Rate my landing 1-10. | 着地、10点満点で何点？ | del |
| 39 | Do you agree or is this overrated? | あなたはどっち派？ | talks, gohantomo |
| 40 | Tell me your most embarrassing fail and I'll reply. | 一番恥ずかしい失敗談、教えて。返信します。 | del, talks |
| 41 | What's the food you never count? | 数えたことがない食べ物、ある？ | gohantomo |

### Series

| # | English | 日本語 | Acct |
|---|---|---|---|
| 42 | [Trick] progression, day [N]. | [技]の練習記録 Day[N]。 | del |
| 43 | Part [N]: [topic]. Follow so you don't miss part [N+1]. | Part[N]：[テーマ]。次回[N+1]も見逃さないでね。 | all |
| 44 | Week [N] of building [startup] in public. | [事業]を作る日記 Week[N]。 | talks |
| 45 | What I ate in a day #[N]. | 1日の食事記録 #[N]。 | gohantomo |
| 46 | Mogumogu rates [food] (kcal edition). | もぐもぐが[食べ物]のカロリーを判定。 | gohantomo |
| 47 | Landing it: attempt [N] of [total]. | 成功まで残り[N]回。挑戦[N]回目。 | del |
| 48 | Ask Taita #[N]: [question]. | Taitaに聞け #[N]：[質問]。 | talks |

### Extra short hook-text lines (any intent)

| # | English | 日本語 | Acct |
|---|---|---|---|
| 49 | Wait for the landing. | 最後の着地まで見て。 | del |
| 50 | I almost quit. | 本気でやめようと思った。 | del, talks |
| 51 | This took [N] tries. | [N]回目でやっとできた。 | del |
| 52 | Before and after: [N] weeks. | [N]週間のビフォーアフター。 | gohantomo |
| 53 | Saves: this one's for you. | 保存して見返してね。 | gohantomo |
| 54 | The mistake costing you [thing]. | [損すること]の原因、これかも。 | talks, gohantomo |
| 55 | Three things I'd tell my 16-year-old self. | 16歳の自分に伝えたい3つのこと。 | talks |
| 56 | Why I [unusual choice]. | なぜ僕は[選んだこと]をしたのか。 | talks |
| 57 | Free, no signup: [thing]. | 無料・登録なしで[こと]。 | gohantomo |
| 58 | Japan edition: what [food] really has. | 日本のコンビニ版：[食品]の中身を調べた。 | gohantomo |
| 59 | I tried this for [N] days. Do not copy me. | [N]日間やってみた。真似はしないで。 | talks, del |
| 60 | Same trick, [N] years apart. | 同じ技、[N]年後。 | del |

---

## 7. Japanese-specific conventions

What the Japanese sources I could reach actually say:

- **Line length / speed**: Netflix Japanese timed-text guide baseline cited by 0120.co.jp: 13 full-width characters/line, max 2 lines, 4 characters/second; the same author suggests 8-10 characters/line for vertical short video ([0120.co.jp](https://0120.co.jp/blog/video-125/)).
- **Breaks**: split at phrase boundaries (bunsetsu), not mid-word; drop particles and filler; if text won't fit in 2 lines, split into two telops (same source).
- **Color**: one base style (white with black outline) plus 1-2 emphasis colors; emphasis color for one spot per sentence (same source). The article does not address katakana-specific rules.
- **Hook phrasing patterns** (bloomeria, [2026](https://bloomeria.jp/blog/short-video-hook-templates-2026)): conclusion-first「◯◯するなら〜〜が正解」, contrarian「実は◯◯は逆効果」, number「3秒で覚える◯◯」, question「◯◯って知ってる？」, comparison「Aより断然Bが良い理由」, failure「私が◯◯で失敗した話」, warning「これだけはやらないで」, before/after「◯日後の変化を見て」, statistic「実は80%の人が知らない」, exclusive「公式が言わない◯◯」. Sample lines: 「知らないと損する◯◯」「3秒でわかる◯◯のコツ」「実はこれ、逆効果でした」「プロがやっている◯◯」. These are agency templates, with no performance data. Note "80%"-style statistics need a real source or they are fabrication.
- **Avoid**: self-intro openers like「みなさんこんにちは、今日は〜について話したいと思います」(same source).
- **Search-keyword consistency**: ざわ所長 note (2026-08-01) gives a worked example of aligning spoken first line, screen text and caption to the viewer's wording.
- **Dietary video context**: a content analysis of diet content on TikTok found humour was significantly associated with engagement ([PubMed 39310984](https://pubmed.ncbi.nlm.nih.gov/39310984/)) — not Japan-specific.

What I could **not** source (so these are [inference] from general knowledge of Japanese social media): katakana for emphasis and kaomoji/emoji density norms, whether「保存推奨」「〜な人は見て」are common phrasings, and what typical line-break habits are on TikTok Japan. I searched and found no analytics-backed page. Suggested working rules, to be verified by looking at 20 Japanese diet-niche accounts on your phone:

- Use **katakana for the one key noun** (「カロリー」「ヘルシー」「ダイエット」) and 「！」 sparingly; avoid stacking kaomoji in a hook.
- Break after phrases, 2 lines, with the number or the kcal big.
- Use polite-casual (です/ます mixed with casual) for a mass audience; keep `gohantomo` friendly and non-medical. Mascot voice (もぐもぐ) can use a distinct sentence ending, but only in series, not hook text.
- Emoji at the **end** of caption lines (🍙 🔥) rather than inside hook text.

---

## 8. Profile / bio packaging

TikTok facts (all vendor/third-party; check in-app): bio limit reported as 80 characters; link-in-bio requires ~1,000 followers or a business account, sources disagree ([Shopify](https://www.shopify.com/blog/how-to-add-link-to-tiktok-bio), [Rocketlink](https://rocketlink.io/blog/tiktok-link-in-bio-requirements)). I found **nothing** confirming the name field is weighted in search; the argument that it is searchable is reasonable [inference] — TikTok has a user search tab — but unmeasured.

| Account | Name field | Bio structure | Link | Pinned videos (3) |
|---|---|---|---|---|
| `taita.del` | `Taita | Tricking` (include "tricking" and "ranked 8th") | Line 1: who ("Ranked 8th in US tricking, coach of 100+ students"). Line 2: what to expect ("I post [crash→landing / tutorials]"). Line 3: where next (`talks` or coaching). | Coaching/application page or your `talks` handle until you have an offer. | 1) the best origin story (crash→landing), 2) your best tutorial, 3) "start here" video saying what you post and why to follow. |
| `taita.talks` | `Taita | Building startups` | "19, Berkeley CS. Building [startup]. Posting what I learn raw." | Product/waitlist. | Best 3 one-takes on one topic so the profile reads as a theme. |
| `ごはんとも` | `ごはんとも｜AIカロリー記録` (the searchable phrase) | 「写真を撮るだけでカロリー記録🍙」「もぐもぐと食事管理」「無料ダウンロード↓」 | App Store/Google Play via smart link; use link in bio if eligible, else business account. | 1) how it works, 2) before/after style result post, 3) a "start here" mascot intro. |

Strategy [inference]: the conversion problem (10M views → 6k followers) is likely a *profile/identity* problem; a viewer from a one-off crash video has no reason to follow unless the bio and pinned posts promise more of the same. Pin the posts that explain the channel, not just the biggest views.

---

## Open questions I could not close

1. Whether TikTok weights captions, speech or on-screen text more. No independent test found.
2. Whether photo slideshows work for Japanese calorie apps. No Japan data found. Test with 10 posts.
3. Whether profile name affects TikTok search.
4. Katakana/emoji/line-break conventions backed by data.
5. Instagram's official statement on caption keywords: not found; claims come from blogs.

## Suggested test (this week)

Post the same `del` clip twice (different days): once with hook text "after 3 years" and once with none. Compare 3-second hold and follow rate per 1,000 views. Do the same with `gohantomo` slide-1 wording once you have it.

## Sources

- https://www.capcut.com/create/tiktok-caption-keywords-discoverability
- https://seoquick.com.ua/en/tiktok-seo/
- https://riseatseven.com/blog/tiktok-seo-statistics/
- https://wetheflywheel.com/en/ai-search/how-to-rank-in-tiktok-search/
- https://www.socialmediatoday.com/news/instagrams-implementing-new-limits-on-hashtag-use/808309/
- https://www.socialmediatoday.com/news/youtube-experiments-with-suggested-hashtags-for-shorts-clips/639748/
- https://fluxnote.io/guides/do-youtube-hashtags-still-work-2026
- https://www.tiktok.com/community-guidelines/en/integrity-authenticity
- https://www.auditsocials.com/blog/tiktok-engagement-bait-community-guidelines
- https://note.com/client_worker/n/n70335a790916
- https://note.com/cdainc/n/n61a213b892ae
- https://note.com/union_ad_master/n/ndafc20c9dc94
- https://note.com/ayane2022/n/n735c46fdc0e1
- https://0120.co.jp/blog/video-125/
- https://bloomeria.jp/blog/short-video-hook-templates-2026
- https://howmanywords.app/ja/ブログ/tiktok文字数制限
- https://find-model.jp/insta-lab/tiktok-photo-post/
- https://www.cinerads.com/blog/how-to-add-text-hooks-to-tiktok-product-slideshows
- https://playkit.beehiiv.com/p/calorie-tracker-app
- https://getlatka.com/companies/calai.app/interviews/cal-ai-zach-yadegari-2025
- https://www.netinfluencer.com/cal-ai-founder-zach-yadegari-breaks-down-the-influencer-playbook-behind-his-apps-growth/
- https://techcrunch.com/?p=3178431
- https://pubmed.ncbi.nlm.nih.gov/39310984/
- https://vidiq.com/blog/post/youtube-shorts-custom-thumbnails
- https://ppc.land/youtube-ends-2-year-wait-for-shorts-thumbnails-but-blocks-a-b-testing/
- https://alternativeto.net/news/2026/7/youtube-introduces-custom-thumbnails-for-shorts-and-ask-studio-ai-thumbnail-generation/
- https://www.hopperhq.com/blog/instagram-reel-size/
- https://socialk.it/en/blog/instagram-reel-covers-guide
- https://www.shopify.com/blog/how-to-add-link-to-tiktok-bio
- https://rocketlink.io/blog/tiktok-link-in-bio-requirements
- YouTube pages cited: https://www.youtube.com/shorts/wOHbaI46l1E , https://www.youtube.com/shorts/RtbYn4fhU_k , https://www.youtube.com/watch?v=AVMTxD85qoY , https://www.youtube.com/shorts/pV0XyRGg-gA , https://www.youtube.com/shorts/HEWj4qFElYQ , https://www.youtube.com/shorts/HkrjA21vcFw , https://www.youtube.com/watch?v=kmTNDl15x_A , https://www.youtube.com/shorts/k_ennX2pOlY

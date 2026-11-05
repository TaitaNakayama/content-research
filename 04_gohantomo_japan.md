# Gohantomo (ごはんとも) — Japan content research

Written for Taita. **Revised 2026-11-05** (gap-fill pass) — this version replaces the first pass. Evidence rules apply.

**What is verified in this version, and how.** YouTube channel pages and search result pages fetch fine from this environment, so every YouTube subscriber count and view count below was read off the live page on **2026-11-05**. TikTok's oEmbed endpoint (`tiktok.com/oembed`) also works, so every TikTok handle below was checked for existence and its **current display name** read live on 2026-11-05. What still does **not** work: TikTok profile and tag pages (return an empty JS shell), Instagram (429/301), Markezine (403), X (402). So **no Instagram follower count in this report is verified by me** — the Instagram figures are agency-listicle numbers and are labelled with their date. TikTok follower counts are likewise listicle numbers; what I verified is that the account exists and what it calls itself today.

`[inference]` = my reasoning, not a source.

---

## 0. Bottom line — read this if you read nothing else

1. **The Japanese growth engine for this category is not slideshows. It is the app's score becoming a content object.** あすけん's 100-point daily score is the single most content-ified thing in Japanese food logging. A Nijisanji VTuber made a video literally titled 「あすけんで絶対に100点とりたい女」 — **1,995,761 views** ([9oAnJWk8LdA](https://www.youtube.com/watch?v=9oAnJWk8LdA)). A gaming channel did 「【あすけん】わしらの栄養状態ヤバすぎ…!? **キャラクリ感覚で**食事管理！」 — **406,790 views** ([XNNQADq7xiA](https://www.youtube.com/watch?v=XNNQADq7xiA)). The top-viewed 食事記録 video in Japanese, **2,734,684 views**, has 【あすけん活用術】 in its title ([_G_q7s9DA8w](https://www.youtube.com/watch?v=_G_q7s9DA8w)). Individual creators post 「【あすけん優等生】95点‼️1日の食事記録。」 (33K) and 「使ってるカロリー管理アプリ別に偏見言ってみた」 (62K). **None of this was paid by あすけん as far as I can tell** — it is people reacting to a number the app gave them. Build Gohantomo so もぐもぐ hands the user a screenshot-worthy verdict every day, and that is your distribution. This is the biggest thing the first pass missed.
2. **あすけん — the #1 app — has no TikTok.** Its own official-SNS page lists only X and Instagram ([more.asken.jp](https://more.asken.jp/)); the handle `@askenjp` on TikTok belongs to an unrelated person (oEmbed display name "Jean-Pierre Kaho", checked 2026-11-05). カロママプラス has no TikTok either (`@calomama_plus` → 400). カロミル (`@calomeal`) and FiNC (`@finc`) do have accounts. **The category leader is absent from the platform where the audience is.** That is your whitespace, and it is specific, not hand-wavy.
3. **Handle warning, act today:** `@gohantomo` on TikTok is **already taken** (display name 「めし」) and so is `@mogumogu`. `@gohantomo_jp`, `@gohantomo.app`, `@gohan_tomo` and `@mogumogu_app` returned oEmbed 400 (no public account) on 2026-11-05 — likely free. Go claim one across TikTok/IG/YouTube/X before you write a single post.
4. **Slideshows: still unproven in Japan, now with a sharper reason.** Japanese sources are unanimous that photo mode is used as a **catalog / save / reference** format (GU, Uniqlo, Sushiro, Gong cha), and not one Japanese case publishes view numbers. The only hard numbers anywhere are TikTok's own, reported in Japanese trade press: carousels get **2.9× comments, 1.9× likes, 2.6× shares** vs video ([DIGIDAY Japan, 2024-04-17](https://digiday.jp/modern-retail/tiktok-is-pushing-brands-to-post-photos-instead-of-videos/)) — US-sourced, platform-self-reported. Section 4 gives you a 3-week test with a pass/fail line instead of a guess.
5. **Compliance is simpler than the first pass implied, and the risk lands on you, not your creators.** The 景品表示法 ステマ告示 regulates **only the advertiser** — 「広告主から広告・宣伝の依頼を受けて表示を行うインフルエンサーやアフィリエイターは規制の対象外」 ([消費者庁 Q&A](https://www.caa.go.jp/policies/policy/representation/fair_labeling/faq/stealth_marketing/)). And your own founder posts about your own app **count as 事業者の表示**. Section 7 has the exact four approved labels and the phrasings to drop.

---

## 1. The Japanese app landscape

Prices are from [calorix.ai's JP price comparison](https://calorix.ai/ja/compare/calorie-app-prices/), checked by that page on **2026-10-23** (note: that site publishes a competing app, so treat it as a secondary source — but it is dated and specific, which is rarer than it should be). Social presence was verified by me on 2026-11-05.

| App | Operator | Price | Scale claim | Social presence (verified 2026-11-05) |
|---|---|---|---|---|
| **あすけん** | asken, Inc. | Premium ¥580/mo, ¥4,400/yr; Plus ¥980/mo, ¥7,500/yr | Media kit claims 6,000+ posts/month tagged #あすけん | **X [@askenjp](https://x.com/askenjp) + IG [@askenjp](https://www.instagram.com/askenjp/) only** — its own SNS page lists no others. **No TikTok, no YouTube.** IG ~37K (unverified, 1st-pass snippet) |
| **カロミル** | **ライフログテクノロジー株式会社** (verified, own PR) | Premium **¥480**/mo; 応援プラン ¥300 | **「会員数は200万人を超えました（2023年5月時点）」** — [own press release](https://www.calomeal.com/pressrelease/20230526.html) | IG [@calomeal](https://www.instagram.com/calomeal/) ~7.1K, X [@calomeal](https://x.com/calomeal) ~6.3K (both unverified); **TikTok [@calomeal](https://www.tiktok.com/@calomeal) does exist** — corrects the first pass, which said it didn't. Content unverified |
| **FiNC** | FiNC Technologies | FiNC Plus **¥480**/mo, ¥1,950/6mo | 累計1,200万DL (company-authored [Wantedly post](https://sg.wantedly.com/companies/finc/post_articles/972079); cumulative downloads, not actives) | **TikTok [@finc](https://www.tiktok.com/@finc) exists.** FiNC Plus launched Jul 2020 at ¥480 ([own PR](https://company.finc.com/news/14275), 503 when I fetched — figure is from search snippet) |
| **カロママプラス** | Wellmira (unverified) | **Free, no in-app purchases** | 旧カロママ Android 10万+ DL (2021, [AndroRank](https://androrank.com/?id=jp.co.lc.caloriemama)) | **No TikTok.** Monetises B2B/health-insurer side, not consumer subs [inference] |
| **YAZIO** | YAZIO GmbH (DE) | Free tier; PRO annual only, ¥2,900–¥10,800, **no monthly plan** | App Store JP 4.3 / 2,221 reviews (per [appmatch](https://appmatch.jp/946099227-2/)) | Global TikTok [@yazio](https://www.tiktok.com/@yazio) exists; **no Japanese account found.** JP reviews complain the food DB is thin for Japanese food and support is English-only ([みん評](https://minhyo.jp/yazio)) |
| **Umax** | multiple, unclear | varies by clone | — | **No Japanese presence found, and it is not a calorie app.** See below |

**On Umax specifically** (the first pass had nothing, and you asked): Umax is an AI **face-rating / "looksmax"** app, not food logging. Searching it in Japanese returns only App Store listings — **no Japanese marketing case, no Japanese press, no Japanese social account, no teardown**. What the store listings do show is instructive in a different way: **at least four separate apps called some variant of "Umax" by different developers** sit in the JP App Store (`id6478508605`, `id6761284153`, `id6782038062`, plus "Umaxx" `id6479165516`), some with Japanese metadata that doesn't match the app ("顔ヨガ"/face-yoga copy on a face-rating app). **Lesson for you: the US viral-AI-app category gets cloned within weeks, and the clones compete on ASO keyword-stuffing in the JP store.** If ごはんとも works, expect a 「ごはんとも風」 clone. Pick a name and handles you can defend, and make the mascot — not the feature — the thing people search for. [inference]

**What this table means.** Every serious Japanese competitor prices at **¥480–¥980/month**, which is roughly a third of what US AI calorie apps charge. Cal AI's JP charges run ¥780–¥6,000 (calorix, undated period). So: do **not** anchor Japanese pricing to Cal AI. ¥480–¥680/month is the market, and the free tier is expected to include photo analysis (カロミル gives photo nutrition analysis away free). Your paid wedge has to be something other than "the camera works".

---

## 2. Real Japanese diet / food-log creators — the UGC template

This was the biggest hole in the first pass. Below are real accounts. **Read the verification column carefully** — I verified existence and current display name for every TikTok handle, and subscriber counts for every YouTube channel, but the follower numbers come from agency listicles whose dates I give.

### 2a. YouTube — subscriber counts read live 2026-11-05

| Channel | Subs (verified 2026-11-05) | What they actually post | Why it matters to you |
|---|---|---|---|
| [片倉岳人/ダイエットの知恵袋](https://www.youtube.com/@gakutoktkr) | **108万** | Trainer explainers, talking-to-camera. 「トレーナーがお腹の脂肪が落ちない原因と解決策を**布教する**動画です。」 (3,973,060 views) | The authority lane. Caps out highest. Not your lane — you're not a trainer |
| [Marina Takewaki](https://www.youtube.com/@MarinaTakewaki) | **446万** | Home workouts + diet recipes | Ceiling of the category. Workout-led, not log-led |
| [おさき日記](https://www.youtube.com/@osakinikki) | **113万** | Daily-life diary vlogs | — |
| [Amaneあまね](https://www.youtube.com/@amane) | **63.5万** | Korea-study-abroad daily vlog + diet. 「食事制限なし！無理せず簡単に６キロ痩せたダイエット方法🏃💨【明日からできる】」 (882,833) | Lifestyle-first, diet-second. Converts because people like *her* |
| [すず 스즈](https://www.youtube.com/@suzu_ch_) | **58.1万** | Lifestyle vlog; her diet video 「【本気のダイエット🔥】4日間の食生活記録🗒🥗食事改善で見た目痩せ大成功したので**全公開**✨」 did **1,100,408** views | A non-diet creator's single food-log video outperformed her channel average. **This is your influencer target: lifestyle creators, one food-log video.** |
| [まみやで](https://www.youtube.com/@mamiyade) | **28.2万** | 「【現実vlog】ダイエットしたいけど食べ飲み大好き女の食欲止まらん1週間の食事【秋の爆食編】」 (1,046,083) | The **anti-discipline** persona out-performs the disciplined one |
| [きょうかちゃんねる](https://www.youtube.com/@_kyokachannel) | **21.4万** | Diet vlogs with hard numbers in titles. TikTok [@___ky0.o](https://www.tiktok.com/@___ky0.o) ("KYOKA", verified) | Cross-posts YT↔TikTok↔IG. Model for a 3-platform creator deal |
| [ねこくらりえch / 40代から人生ぶん回す主婦](https://www.youtube.com/@nekokurarie_ch) | **15.3万** | 40s housewife, 82kg→−25kg. Bio: 「「痩せてからが本番です」38歳、82kg→−25kg」. Her **【あすけん活用術】** video is the most-viewed 食事記録 video I found (2,734,684) | **The single best creator fit for Gohantomo.** She already makes app-usage content, she's in an underserved age bracket, and she's small enough to be affordable |
| [リナエット rina×diet](https://www.youtube.com/@rinaet_diet) | **10.7万** | Pure diet-record channel. Bio: 「ダイエット歴10年｜発信歴6年目🌿163cm｜MAX75kg → 51kg → 現在58kg」. 「【ダイエットvlog】20kg痩せた私の1週間食事\| **食べながら痩せる** 75kg→55kg」 (542,973) | **Note the bio formula** — 身長 ｜ MAX体重 → 現在. And note she states a *regain* (51→58kg). Honesty is the convention, not a liability |

### 2b. TikTok — existence and current display name verified 2026-11-05 via oEmbed

Follower figures are from [beaus.net's 20-account list](https://beaus.net/note/2933/) (**undated**, treat as stale) and [studio15](https://studio15.co.jp/media/diet-tiktok-influencer/) (page dated 2026-08-05, phrased as "over X"). The **display names are live and mine.**

| Handle | Display name, live 2026-11-05 | Followers (source, stale) | What they post |
|---|---|---|---|
| [@noponopisu2](https://www.tiktok.com/@noponopisu2) | ほのぴす🐰👑 | 75万+ (studio15) | Diet meals + training + beauty; did a PR tie-up with Mitsukan フルーティス |
| [@pina.diet](https://www.tiktok.com/@pina.diet) | *oEmbed 400 — account not resolvable* | 47.8万 (beaus) / 27万+ (studio15) | Face/leg slimming. **Figures conflict ~2×; do not cite** |
| [@chihiro27chictivity](https://www.tiktok.com/@chihiro27chictivity) | **1分で痩せるダイエットちひろ先生** | 22.3万 (beaus) | Mindset + 1-minute massage |
| [@diet50_38](https://www.tiktok.com/@diet50_38) | **hazu🐱12kgのダイエットに成功！** | 11.7万 (beaus) | Lower-body slimming after −12kg |
| [@dietvlog_miii160cm](https://www.tiktok.com/@dietvlog_miii160cm) | miii | 11.3万 (beaus) | Diet vlogs, −8kg/3mo |
| [@diet_hikarun](https://www.tiktok.com/@diet_hikarun) | **【ダイエット】ひかるん** | 9.5万 (beaus) | Ex-model, −10kg |
| [@shinozukalavie](https://www.tiktok.com/@shinozukalavie) | ラヴィ先生の美意識塾✨ | 8.54万 (beaus) | Reset-diet method, face shaping |
| [@hinatiiii214](https://www.tiktok.com/@hinatiiii214) | ひぃぃこ | 7.43万 (beaus) | Colour coordination + training + diet |
| [@fujitan_diet](https://www.tiktok.com/@fujitan_diet) | 藤たん/パーソナルトレーナー | 6.8万 (beaus) | 宅トレ + diet tips |
| [@niwatori__tk](https://www.tiktok.com/@niwatori__tk) | **ボディメイクのにわちゃん🐓** | 6.7万 (beaus) | Balanced eating after −12kg. *Renamed from ダイエットの→ボディメイクの* |
| [@marufuwabody](https://www.tiktok.com/@marufuwabody) | YUKA🫶自愛ボディメイクメソッド | 4.7万 (beaus) | Mindset-first body shaping |
| [@moepi_kintore](https://www.tiktok.com/@moepi_kintore) | もえぴー | 2.8万 (beaus) | 宅トレ + healthy cooking |
| [@honkidasumaru](https://www.tiktok.com/@honkidasumaru) | **まる@おトク大好き-15kgダイエッター☺︎** | 2.5万 (beaus) | Postpartum diet |
| [@sakura_23f9](https://www.tiktok.com/@sakura_23f9) | さくら | 2.4万 (beaus) | −32kg story + beauty |
| [@momoshacho](https://www.tiktok.com/@momoshacho) | **もも➖15キロ** | 2.0万 (beaus) | Diet content |
| [@memeron_me](https://www.tiktok.com/@memeron_me) | めめろん🍈 | 6万+ (studio15) | −25kg; mindset, stretching |
| [@muton_0000](https://www.tiktok.com/@muton_0000) | ムートン🏃 | 1万+ (studio15) | −40kg; diet + beauty + dance |
| [@___ky0.o](https://www.tiktok.com/@___ky0.o) | KYOKA | not given | Cross-poster, see 2a |

Returned oEmbed 400 (gone or renamed since the listicle): `@rena20001201`, `@sy__bodymake`, `@mio_yasetai`, `@arichan_ari`, `@meru.0903`, `@u_mi170`→exists, `@pina.diet`. **Churn in this cohort is high** — roughly a quarter of a listicle's accounts are unresolvable. Build your creator list fresh, not from listicles. [inference]

### 2c. Three conventions these accounts share — and you should copy

1. **The result lives in the display name, not the bio.** 「hazu🐱12kgのダイエットに成功！」「もも➖15キロ」「まる@おトク大好き-15kgダイエッター☺︎」「1分で痩せるダイエットちひろ先生」. One claim + one emoji + one identity word. On YouTube the same thing runs longer: 「163cm｜MAX75kg → 51kg → 現在58kg」.
2. **The format is "a day of my food", not "a transformation".** See 3a. The highest-view short-form food content in Japanese is literally `身長+体重 + 1日のご飯`.
3. **Nobody is faceless.** Every account above is a person with a body and a number. **This is the real problem with a mascot-only account** — the category's trust currency is a personal before/after, and もぐもぐ has no body. Section 3c says what to do about it.

---

## 3. Japanese hook, caption and register conventions — now evidenced

The first pass marked this section "inference only". It no longer is. Below is drawn from a live corpus of the highest-viewed Japanese diet videos and Shorts, read 2026-11-05. Every quoted title is real; view counts are as YouTube displayed them.

### 3a. The two title formulas that actually dominate

**Formula A — the food-log short (this is the one you clone):**

> `身長 + 体重` + `1日のご飯` + one emoji + a long hashtag block

- 「**163cm42kg**１日のご飯🫶🏻」 — **455万 views**
- 「**166cm47kg**リアルな1日のご飯🍚」 — 36万
- 「**166cm47kg**リアルすぎる1日のご飯🍚」 — 9.3万
- 「【1日の食事】リアルな普段のご飯記録✍️」 — 26万

No verb. No promise. No hook sentence. **The hook is the number pair.** This is the single most reproducible format in the Japanese market and it is three words long.

**Formula B — the bracketed claim (for your explainer/utility posts):**

> `【…】` front-loaded + a number + a reveal verb

- 「【ダイエット迷子必見】38歳人生最後のダイエット、食事はこれからやりました！【あすけん活用術】」 — 2,734,684
- 「【本気のダイエット🔥】4日間の食生活記録🗒🥗食事改善で見た目痩せ大成功したので**全公開**✨」 — 1,100,408
- 「【保存版】これで痩せた！ココアダイエットのやり方教えます！」 — 593,010
- 「【永久保存版】1ヶ月で4.5キロ痩せた私の正しいダイエットの方法！」 — 3,077,376
- 「【密着vlog】毎日ギリギリ食べ過ぎかもしれないぽっちゃり女の春の1週間の食事www🌸」 — 727,800

**Verified bracket vocabulary**, in descending usefulness for you: 【保存版】【永久保存版】【〇〇必見】【全員必見】【密着vlog】【現実vlog】【初公開】【徹底比較】【検証】【各コンビニ】【-4kg】【過酷】.
**Verified reveal verbs:** 全公開 / 大公開 / 公開 / 見せます / 教えます / 徹底解説 / 比べてみた / やってみた / 〜した結果.

### 3b. Register, emoji and text density — settled

- **Register: plain form (だ・である is wrong, ですます is wrong for titles).** Short-form titles and on-screen text are casual plain-form or noun-ending: 「ダイエット中ならセブンでコレ買え。」(45万) 「減量中のコンビニ飯の選び方」(134万). Imperative 〜買え and bare nouns both read as native. **Use ですます in the app and in replies; use plain/noun-ending in on-screen text.** [inference on the split; the plain-form-in-titles part is evidenced]
- **Emoji: heavy, not sparse.** The first pass hedged on this. The corpus is unambiguous — **multiple emoji per title is the norm**, including in million-view titles: 🔥🗒🥗✨🪄🍚🫶🏻🩵‼️💖. 「【📣ウエスト-8cm🔥】食べながらゆるダイエット🪄リアルな5日間の食事記録🍝【自炊 \| 運動】」 (492,485). Kaomoji appear in display names (☺︎ in @honkidasumaru). **Do not westernise this to one tidy emoji.**
- **Hashtag blocks are long and in the caption, 8–12 tags.** Real example: `#自分磨き #腸活ダイエット #ダイエット #食事vlog #ダイエット記録 #ダイエット日記 #食べ痩せ #健康的に痩せる #1日の食事 #食事記録`. US "3 hashtags max" advice does not apply.
- **On-screen text density:** I could not measure Japanese on-screen character counts without frame extraction, so this stays **[inference]**: Japanese is ~2× denser per character than English, so a line that reads at a glance is **roughly 10–16 characters**, and titles in the corpus above cluster at **15–35 characters** total. Treat 16 chars/line, 2 lines max as the working rule and revise it from your own retention data.
- **Self-deprecating identity labels are a convention**, built with 〜女 / 〜人: 「食べ飲み大好き女」「ぽっちゃり女」「年中ダイエット1日5食女」「限界地雷系会社員」「挫折のプロ」. This is the tonal register もぐもぐ should sit in — **not** a coach.

### 3c. Permission-giving beats discipline, and it is not close

Every high-view title in the corpus gives the viewer permission to eat. Verified phrasings, with views:

| Phrase | Example | Views |
|---|---|---|
| 食べながら痩せる | 「20kg痩せた私の1週間食事\| 食べながら痩せる 75kg→55kg」 | 542,973 |
| 食事制限なし / 無理せず | 「食事制限なし！無理せず簡単に６キロ痩せた」 | 882,833 |
| 健康的に沢山食べて | 「【健康的に沢山食べて絶対痩せる】永久保存版！」 | 3,077,376 |
| ゆるダイエット | 「食べながらゆるダイエット🪄」 | 492,485 |
| 罪悪感ゼロ | 「【ダイエット中でも罪悪感ゼロ！】コンビニで買えるお菓子」 | 680,705 |
| 食べ痩せ (as a tag) | used across the Shorts corpus | — |

**Also verified as live hashtags** (seen in the captions of posts in the corpus, not just as phrases): `#食べ痩せ` `#痩せ飯` `#健康的に痩せる` `#垢抜け` `#自分磨き` `#ダイエッターさんと繋がりたい` `#ダイエット仲間募集中` `#爆美女` `#腸活ダイエット` `#リバウンド卒業`. (「無理しない」「無理せず」 I saw only in title text, not as a hashtag.)

**Two of those are directly about your real problem.** `#ダイエッターさんと繋がりたい` and `#ダイエット仲間募集中` are the native Japanese *follow-me* conventions. You have 10M+ views and 6,000 followers on `taita.del` because nothing in the post asked for the relationship. In this vertical there is an idiomatic way to ask, and it is not "follow for more" — it is 「一緒にがんばろ」/「ダイエッターさんと繋がりたい」. Verified in a 77万-view Short: 「太もも隙間できた🥺-8cmできた方法載せるからみんなも**一緒に頑張ろ**！🔥」.

### 3d. Where the ceilings are — pick your lane on evidence

| Topic | Best observed view count | Read |
|---|---|---|
| コンビニ + カロリー | 493万 (「ダイエット中によく食べる最強のコンビニ飯 -ダイエット6日目-」); 134万; 45万 | **High ceiling, repeatable, kcal-native. Your #1 lane.** |
| 1日のご飯 (food log) | 455万 | **High ceiling, lowest production cost. Your #2 lane.** |
| 痩せた方法 / −〇kg | 1,133万 | Highest ceiling — **and the one you legally cannot run as a brand.** Leave it to creators (§7) |
| あすけん / app-score reaction | 1,995,761 | **Medium-high, and nobody owns it in your name yet.** Your strategic lane |
| PFCバランス | **84万 top, most under 3万** | **Low ceiling.** Good for conversion, bad for reach. Do not open with it |
| 爆食 | YouTube Shorts search returned nothing usable | First pass was right: not a retrievable lane |

That PFC row matters: the first pass called PFC 「strong」. The data says PFC explainers top out around 30–50× lower than コンビニ content. Keep PFC posts, but as post #11 not post #2.

---

## 4. The slideshow question — settled as far as evidence allows

### What I found in Japanese
- **Format mechanics are consistent and current:** 2–35 images, captions up to 4,000 characters, mobile-only to post, 9:16 to avoid letterboxing ([Insta Lab, 2026-03-25](https://find-model.jp/insta-lab/tiktok-photo-post/); [active-note](https://www.active-note.jp/sns/photomode/)).
- **Every Japanese brand use I can verify is a catalog or a comparison, not a growth engine.** GU ([@gu_official](https://www.tiktok.com/@gu_official) — existence verified) puts a headline on slide 1 (example phrasing given: 「今週の新作まとめ」) then colours and prices as a catalog; the article attributes higher **saves** to viewers pausing on price/material slides. Gong cha's swipeable menu guide and Lilyanna's lens-colour comparison are the two photo-mode entries among **18** best-of-2025 TikTok cases at [Comnico](https://www.comnico.jp/we-love-social/best-tiktok-posted-case-2025) — the other 16 are video. Also cited for photo mode: Uniqlo, Sushiro, Toyota ([utakata](https://utakata.co.jp/media/tiktok-photo/)), and a Shogakukan manga label that posted manga excerpts in photo mode with a claimed ebook-sales lift (via the ByteDance-sponsored Nikkei X-Trend feature — **the page 404s for me now, so I am reporting it as a second-hand claim with no number**).
- **Zero Japanese cases with published view numbers.** I looked at agency blogs (Comnico, utakata, find-model, studio15, e-pace, one-carat, active-note), the Nikkei/ByteDance sponsored feature, and DIGIDAY Japan. The only quantified claims in Japanese are two anecdotes from single operators — "reach doubled" and "completion rate went way up" ([active-note](https://www.active-note.jp/sns/photomode/)) — with no data behind either, and one source explicitly warns 「すべてのスライドショーが再生数やエンゲージメントにつながるわけではない」.
- **The only hard numbers are TikTok's own, published in Japanese trade press:** carousels earn **2.9× comments, 1.9× likes, 2.6× shares** vs video; a cosmetics brand reported carousels reaching **11% more people** than video and its top-ever post (6.6M views) being a carousel ([DIGIDAY Japan, 2024-04-17](https://digiday.jp/modern-retail/tiktok-is-pushing-brands-to-post-photos-instead-of-videos/)). **US brands, US audience, platform-self-reported, 2024.** Useful as a prior, not as Japanese evidence.

### Verdict
**Unproven in Japan. Plausible. Cheap to test. Do not build the account on it.** Note what the evidence actually says the format is *good at*: **saves and shares on reference content**. That is a real match for 「コンビニおにぎり kcal早見表」 — and it is *not* a match for a mascot's personality posts, which need motion and voice.

Note also the one piece of counter-evidence worth respecting: **the entire verified Japanese creator corpus in §2 and §3 is video.** Not one high-view Japanese food-log post I found was a photo slideshow. If slideshows were the unlock in this vertical in Japan, someone in that cohort would be doing it.

### The cheapest possible test — run this, exactly

**Setup.** One account. 3 weeks. 30 posts, 10/week, same posting time, same sound strategy, same hashtag block. Hold the *topic* constant and vary only the *format*, in an interleaved A/B so TikTok's weekly volatility can't fake a result:

- **15 SS** (photo slideshow, 6–8 slides, slide 1 = headline only)
- **15 V** (short video, same topic, your voice or もぐもぐ over the same images)
- Pair them: each topic gets made both ways, posted 3 days apart, SS first for odd pairs and V first for even pairs.

**Cost:** zero in cash. The 15 videos are the only real labour, and they are one-take voiceovers over the slideshow images you already made.

**The metrics, in priority order.** Not views. Views in week 1 are noise.
1. **Follows per 1,000 views** — this is your actual business problem, and it is the pass/fail metric.
2. **Saves per 1,000 views** — the thing Japanese sources claim photo mode wins on.
3. Shares per 1,000 views.
4. Median views per post (ignore the max — one outlier proves nothing).

**Pass / fail, decided on medians of 15 vs 15:**

| Result | Call |
|---|---|
| SS follows/1k ≥ **1.3×** V, and SS median views ≥ 0.7× V | **Pass.** Slideshows are your main format. Go 70% SS |
| SS and V within ±30% on follows/1k | **Inconclusive, which means V wins.** Video is cheaper for you per unit of personality and travels further in this vertical. Go 70% V, keep SS only for 早見表/保存版 posts |
| SS follows/1k ≤ **0.7×** V | **Fail.** Drop slideshows except as Instagram carousels |
| Fewer than 5 posts in either arm clear 1,000 views | **Test invalid** — the account is too cold to measure format. Re-run after you have one post over 50K |

**Write the numbers down before you start.** The failure mode here is running 30 posts, remembering the one slideshow that hit 80K, and concluding slideshows work.

---

## 5. Hashtag and search reality — what is actually knowable

**Honest state of the data: TikTok hashtag volumes are not retrievable.** TikTok tag pages return HTTP 200 but an empty JavaScript shell to this environment, and TikTok no longer publishes view counts on public tag pages. The first pass's "#ダイエット記録 ~215K / #ダイエット飯 ~29K" came from a search snippet I could not reproduce or confirm — **treat both as unverified and do not put them in a deck.**

**Instagram post counts, from one dated secondary source** ([SAKIYOMI](https://sns-sakiyomi.com/blog/tips/instagram-diet-account/), an SNS agency; the article is internally inconsistent on some of its own figures, so these are **unverified**):

| Tag / term | Instagram posts | Note |
|---|---|---|
| ダイエット | 1,781万 | Bigger than グルメ (1,005万) and コスメ (641万) — the genre is top-tier on Japanese Instagram |
| ダイエット記録 | 274万 | Called a ビッグハッシュタグ |
| ダイエット日記 | 102万 | |

**What I can state with confidence instead**, because I observed it in live high-view captions (§3c): the tag set Japanese food-loggers actually use is `#食事記録` `#ダイエット記録` `#ダイエット日記` `#1日の食事` `#食事vlog` `#ダイエットvlog` `#食べ痩せ` `#痩せ飯` `#健康的に痩せる` `#自分磨き` `#垢抜け` `#腸活ダイエット` `#ダイエッターさんと繋がりたい` `#ダイエット仲間募集中`. **Observed usage by high-performing posts is a better targeting signal than a post count anyway** — a count tells you competition, not whether the tag is live.

**Underweighted and worth claiming:** `#レコーディングダイエット` has essentially no competitive short-form content (YouTube's by-view search for it surfaces mostly 岡田斗司夫 clips about the 2000s book, plus sub-20K-view personal logs). It is the exact Japanese name for what your app does, and it is empty. **Put it in every caption.**

---

## 6. Mascot-led accounts in Japan

Unchanged from the first pass and still the weakest-evidenced section — I could not read any mascot TikTok. Base: [Comnico's character-account guide](https://www.comnico.jp/we-love-social/character-account), [Oricon](https://www.oricon.co.jp/special/54774/), [hashout](https://hashout.jp/?p=12312).

| Account | What it does | Lesson |
|---|---|---|
| 日清 ひよこちゃん (X) | Surreal, self-deprecating "venting" persona; one post >100K likes (Oricon). Persona built from accumulated posts, not one hit | Give もぐもぐ a *flaw*: always hungry, bad at saying no to ramen |
| SMBC ミドすけ | Ties posts to calendar days (喫茶店の日 etc.) | Use 〇〇の日 food-day hooks |
| Zespri Kiwi Brothers | High frequency, entertainment, no overt promotion | Most posts should not mention the app |
| くまモン | Real-life "staff" photos | A mascot can act as an employee |
| Expo 2025 ミャクミャク | Observed third-person rather than speaking in first person | Fallback if a first-person もぐもぐ voice feels forced |

**Comnico's persona-sheet checklist for もぐもぐ:** first-person pronoun (ボク/わたし), politeness level, emoji rules, post energy, trend rules, banned topics, reply policy. Suggested 8:2 everyday-to-promotional ratio. Risk named by the same source: inconsistency across operators — you're solo, so write the sheet once.

**My take, now sharpened by §2c [inference]:** もぐもぐ cannot carry the account alone, because the category's trust currency is a human body with a number and he hasn't got one. Run it as **your face + もぐもぐ as the voice of the number.** He narrates the photo — 「これ、500kcalくらい？」 then reveals — and never scolds. And per §0, the thing he hands over at the end of each day is the asset: **a scoreable, screenshot-able verdict**, the Gohantomo answer to あすけん's 100点.

---

## 7. Compliance — concrete rules. This is not legal advice; get a 薬機法/景表法 review before you ship paid promotion.

The useful reframe: **ごはんとも is a recording tool, so keep every claim about the *recording*, never about the *body*.** The moment a claim is about the body, you are in 景表法 優良誤認 territory and arguably 薬機法.

### 7a. Which law actually bites
- **景品表示法 第5条第1号 (優良誤認表示)** — the main exposure. Misrepresenting quality/performance. Sanctions: 措置命令, and 課徴金 for 優良誤認/有利誤認 ([消費者庁](https://www.caa.go.jp/policies/policy/representation/fair_labeling/stealth_marketing/)).
- **景品表示法 ステマ告示 (令和5年内閣府告示第19号)** — in force **2023-10-01**. Covered conduct: 「一般消費者が事業者の表示であることを判別することが困難である表示」. Sanction is 措置命令; **課徴金 does not apply to ステマ alone**, but does if 優良誤認 is also present ([消費者庁 Q&A](https://www.caa.go.jp/policies/policy/representation/fair_labeling/faq/stealth_marketing/)).
- **薬機法 第66条第1項 (虚偽・誇大広告) / 第68条 (未承認品の広告禁止)** — applies if you claim medical/therapeutic effect, which can also drag the app toward being treated as a 医療機器プログラム ([Monolith](https://monolith.law/corporate/beauty-diet-advertising-restrictions)). A calorie *recorder* that claims nothing medical is outside it. **So claim nothing medical.**

### 7b. Who is liable — the thing worth knowing
From the 消費者庁 Q&A, verbatim:
> 「広告主から広告・宣伝の依頼を受けて表示（例えば、SNSへの投稿等）を行うインフルエンサーやアフィリエイターは規制の対象外となります。」

**You are the regulated party. Your creators are not.** Two consequences:
1. Your creator contract must do the compliance work, because the regulator will come to you, not to them. Put the banned-phrase list in the contract.
2. **Your own posts about your own app are 事業者の表示.** The Q&A is explicit that someone in a sales/development/management role posting to promote the product counts, and that merely writing 「私は○○社の社員です。」 is **not** sufficient disclosure. A clearly-branded ごはんとも account is self-evidently the company's. **Your personal `taita.talks` account promoting ごはんとも is the actual risk** — label those posts.

### 7c. The four approved labels, and where they must go
The 運用基準 names exactly four: **「広告」「宣伝」「プロモーション」「PR」**. Other wording is allowed if the whole post makes it clear — the Q&A gives the approved sentence form 「A社から商品の提供を受けて投稿している」.

Two placement rules straight from the Q&A, both of which people get wrong:
- **Not in a reply or comment.** 「投稿の本文ではなくツリー（リプライ）に『広告』などの記載がされている場合は、通常、一般消費者が当該記載に気付かないおそれがあり、事業者の表示であることが明瞭とはいえない場合が多い」. **So: in the caption body, not the first comment.**
- **Not only at the start of a video.** 「動画の場合、一般消費者が途中から視聴する場合も考えられるため、冒頭に『広告』などと表記するだけでは、当該表記を見逃すおそれがあります」. **So: persistent on-screen 「PR」 for the whole video, plus 「PR」 in the caption.**
- And you may **not** republish a paid creator post on your own site as 「お客様の声」: 「『事業者の表示』に当たるインフルエンサーの投稿を、『お客様の声』として自社のウェブサイト上に掲載することは適当ではありません」.

### 7d. The phrase list — ban these, use these

| ❌ Do not say | Why | ✅ Say instead |
|---|---|---|
| 「1ヶ月で-5kg痩せます」「-5.3kg実績」 | Body-result claim + time guarantee. 優良誤認 risk; this is カロミル's bio pattern — **do not copy it** | 「記録が続くアプリです」「食べたものが、数字でわかる」 |
| 「必ず」「確実に」「絶対痩せる」 | Guarantee | 「目安がわかります」「続けやすい設計です」 |
| 「飲むだけ/撮るだけで痩せる」 | Implies the app causes weight loss | 「撮るだけで記録できる」 ← *the verb must be 記録, never 痩せる* |
| 「〇〇が改善」「代謝が上がる」「便秘に効く」「予防」「治療」 | 医薬品的効能効果 → 薬機法 | say nothing about bodily function at all |
| 「医療レベルの精度」「AIが診断」 | Medical-device framing | 「AIが推定した目安値です」「**誤差があります**」 |
| Before/after body photos | Restricted for 医薬品等; for an app it reads as a 効能 claim and is the archetypal 優良誤認 fact pattern | screenshots of the **log**, not the body |
| User testimonial as the headline claim | A testimonial used as a performance claim needs substantiation that it is typical | keep testimonials about **the app** ("記録が続いた") not **the body** |
| 「栄養士監修」 without a named, consenting 管理栄養士 | Unsubstantiated authority claim | name them, or drop the word |
| Ideal-weight / target-weight numbers aimed at minors, extreme-restriction content | Not strictly a statute issue but asken's own survey says ~30% of Z-gen app users first dieted in elementary/junior high ([asken](https://www.asken.inc/news/20240605investigation)) | 記録 / 理解 framing only |

**One caption boilerplate to reuse:** 「AIが出す数値は目安です。医療・治療を目的としたものではありません。」 Put it in the caption of every post that shows a number. It costs you nothing and it is the single cheapest piece of protection you have.

**Note the asymmetry you can exploit legally.** Creators may say 「-15kg痩せた」 about their own experience — that's their lived claim, and §2b shows the whole cohort puts it in their display name. **You may not say it about your app.** So: let creators tell the body story, and keep the brand account on 記録・数字・コンビニ. That's not a compromise — it's the same division of labour that gets you better content anyway.

---

## 8. LINE — worth it, but not at launch

**Scale is not in doubt.** LY Corporation's own business site states **月間1億人** LINE MAU in Japan as of end-March 2026, i.e. 「日本人口の約80%以上」 against a 1億2,336万7千人 population ([lycbiz](https://www.lycbiz.com/jp/service/line-official-account/)). LINEミニアプリ: **2,897万** monthly users and **33,000** released services, end-March 2026 ([lycbiz](https://www.lycbiz.com/jp/service/line-mini-app/)). These are vendor figures.

**Pricing, verified** ([lycbiz plans](https://www.lycbiz.com/jp/service/line-official-account/plan/)):

| Plan | Monthly | Free messages/mo | Overage |
|---|---|---|---|
| コミュニケーション | **¥0** | 200 | not available |
| ライト | ¥5,000 | 5,000 | not available |
| スタンダード | ¥15,000 | 30,000 | ~¥3/message, tiered |

**Should you open one at launch? Yes — the free plan, and nothing more.**

- The ¥0 plan gives you 200 messages/month. At launch you will have fewer than 200 friends, so **it costs nothing and you can broadcast once a month.** There is no reason not to.
- But **do not build a LINE retention programme at launch.** 200 messages/month is one broadcast to 200 people. The moment you want a daily 「記録しましたか？」 reminder to even 300 people you are at 9,000 messages/month → ライトプラン (¥5,000) won't cover it either → スタンダード (¥15,000 + overage). **Daily reminders over LINE do not scale on a pre-revenue budget. Daily reminders belong in iOS push, which is free.** [inference]
- **LINEミニアプリ is the wrong tool for you.** Its stated value is removing the install barrier (「初回利用のハードルを大きく下げられます」) for things like mobile ordering and digital membership cards. You are shipping a native iOS app whose core interaction is the camera; the mini-app has nothing to remove. Cost is quote-only. Skip it.
- **What LINE is genuinely for, later:** the handoff from paid creator campaigns. A LINE friend is a channel you own, where App Store users are not. Revisit when you're spending money on creators and need the leads to survive a failed install.

---

## 9. First 30 posts

Unchanged in structure. **Hooks rewritten against §3** — the big changes: food-log posts now use the verified `身長+体重+1日のご飯` formula; brackets are front-loaded; emoji density raised to match the corpus; every result word removed; and the 「一緒に」 ask added where it belongs.

Legend: 🐾 = もぐもぐ appears, 🙋 = you appear. SS = photo slideshow, V = short video. **The SS/V split is deliberately 15/15 — this list *is* the §4 test.** Check every claim against §7 before posting.

| # | Format | Hook (slide-1 / first-frame text) | Goal | Who |
|---|---|---|---|---|
| 1 | V | はじめまして、もぐもぐです。ごはん、撮るだけで記録します | Intro | 🐾 |
| 2 | SS | 【保存版】コンビニの朝ごはん、実は何kcal？ | Save | 🐾 |
| 3 | V | 19歳が「ごはんとも」を作った理由 | Founder trust | 🙋 |
| 4 | SS | 【保存版】セブンのおにぎり kcal早見表🍙 | Save | 🐾 |
| 5 | V | 撮るだけで数字が出るの、見て📸 | Demo | 🙋🐾 |
| 6 | SS | ローソンのパン、カロリー順に並べてみた🥐 | Save | 🐾 |
| 7 | V | もぐもぐ、今日もごはんを食べすぎました | Persona | 🐾 |
| 8 | SS | 170cm◯kg、ある1日のごはん記録🍚 | **UGC template (Formula A)** | 🙋 |
| 9 | SS | 【徹底比較】吉野家の牛丼、並と大盛りの差 | Save | 🐾 |
| 10 | V | 「ラーメンは罪」って誰が決めたの？🍜 | Persona/opinion | 🐾 |
| 11 | SS | PFCバランスって？1分でわかる【保存版】 | Education | 🐾 |
| 12 | V | AIがカロリーを間違えた日 | Honest trust | 🙋 |
| 13 | SS | 【保存版】定番ごはん10選のPFC | Save | 🐾 |
| 14 | V | 今日は〇〇の日！もぐもぐ的ごはん | Calendar hook | 🐾 |
| 15 | SS | スタバの新作、実はこれくらい【目安】☕️ | Save/trend | 🐾 |
| 16 | V | アプリの作り方、バイト代で始めた話 | Founder story | 🙋 |
| 17 | SS | 【現実vlog】食べすぎた日のごはん、全公開 | Entertainment | 🙋 |
| 18 | V | もぐもぐと対決：どっちが多い？ | Quiz | 🐾 |
| 19 | SS | 外食でも数字がわかる、選び方3つ | Utility | 🐾 |
| 20 | V | ユーザーさんのごはん、見せてもらいました（許可済） | UGC | 🐾 |
| 21 | SS | コンビニ夜ごはん3パターン🌙 | Save | 🐾 |
| 22 | V | 記録、三日坊主でもいい理由 | Retention | 🙋 |
| 23 | SS | 【保存版】定食屋メニュー kcal早見表 | Save | 🐾 |
| 24 | V | みんなのアンケート結果発表！ | Engagement | 🐾 |
| 25 | SS | 一週間のごはん記録、まとめて見せます📝 | Proof | 🙋 |
| 26 | V | 管理栄養士さんに聞いてみた（※要・実名と同意） | Authority | 🙋 |
| 27 | SS | 【検証】おやつ、どれを選ぶ？kcal比べ🍫 | Save | 🐾 |
| 28 | V | 「ごはんとも」開発ログ #1 | Build in public | 🙋 |
| 29 | SS | 今月よく食べたもの、ランキング🏆 | Recap | 🐾 |
| 30 | V | 質問に答えます（Q&A）／一緒に記録はじめよ🤝 | Community | 🙋🐾 |

**Caption template for every post:**
```
<1–2 lines, plain form, 1–2 emoji>
AIが出す数値は目安です。医療・治療を目的としたものではありません。
#ごはんとも #レコーディングダイエット #食事記録 #ダイエット記録 #1日の食事
#食べ痩せ #健康的に痩せる #カロリー計算 #コンビニ飯 #ダイエッターさんと繋がりたい
```

**Four things to add that aren't posts:**
1. **Claim the handles today** (§0.3). `@gohantomo` and `@mogumogu` are gone on TikTok.
2. **Ship the score before post #1.** §0.1 is the whole strategy and it is a *product* requirement: もぐもぐ must hand over one screenshot-able daily verdict. Without it you have no reaction content and no reason for anyone to post about you.
3. **DM ねこくらりえ (@nekokurarie_ch, 15.3万).** She already made the most-viewed 食事記録 video in Japanese *about using a calorie app*, she's in an age bracket nobody is serving, and at 15万 subs she's affordable. She is the highest-expected-value single outreach on this entire list.
4. **Write the §4 numbers down before post #1** and re-read them after post #30.

---

## Sources

**Primary / government**
- 消費者庁 ステマ告示: https://www.caa.go.jp/policies/policy/representation/fair_labeling/stealth_marketing/
- 消費者庁 ステマ Q&A (approved labels, video/reply placement, お客様の声): https://www.caa.go.jp/policies/policy/representation/fair_labeling/faq/stealth_marketing/
- LY Corporation — LINE公式アカウント (1億人 MAU): https://www.lycbiz.com/jp/service/line-official-account/
- LY Corporation — plans/pricing: https://www.lycbiz.com/jp/service/line-official-account/plan/
- LY Corporation — LINEミニアプリ (2,897万 users): https://www.lycbiz.com/jp/service/line-mini-app/
- ライフログテクノロジー press release (カロミル 200万人, ¥480): https://www.calomeal.com/pressrelease/20230526.html
- asken official SNS list (X + IG only): https://more.asken.jp/ (redirected from https://column.asken.jp/officialsns/)
- asken Z-gen diet survey: https://www.asken.inc/news/20240605investigation
- FiNC Plus launch PR (503 on fetch; figure via snippet): https://company.finc.com/news/14275

**Verified live by me, 2026-11-05** — YouTube channel/search pages and TikTok oEmbed
- Channels: https://www.youtube.com/@gakutoktkr · @MarinaTakewaki · @osakinikki · @amane · @suzu_ch_ · @mamiyade · @_kyokachannel · @nekokurarie_ch · @rinaet_diet
- Videos: https://www.youtube.com/watch?v=_G_q7s9DA8w · 9oAnJWk8LdA · XNNQADq7xiA · WWhFWoRItNk · 918dzJSZeRY · cuGIQhQxKqo · 0Zz3FL4XjYM · OejxiAvtY7c
- TikTok handles verified via https://www.tiktok.com/oembed — all accounts listed in §2b

**Creators (secondary, stale — dates noted inline)**
- https://beaus.net/note/2933/ (20 TikTok diet accounts, undated)
- https://studio15.co.jp/media/diet-tiktok-influencer/ (page dated 2026-08-05)
- https://find-model.jp/insta-lab/instagram-diet-influencer/ (July 2021 figures)
- https://krafit.studio/diet-blog/instagram-diet/ (no figures)
- https://tokyo-mbfashionweek.com/diet-youtuber.html (2023)
- https://sns-sakiyomi.com/blog/tips/instagram-diet-account/ (IG hashtag volumes; internally inconsistent)

**Photo mode / slideshows**
- https://digiday.jp/modern-retail/tiktok-is-pushing-brands-to-post-photos-instead-of-videos/ (2024-04-17; TikTok's 2.9×/1.9×/2.6× carousel figures)
- https://find-model.jp/insta-lab/tiktok-photo-post/ (2026-03-25; GU case, 35 images, 4,000 chars)
- https://www.comnico.jp/we-love-social/best-tiktok-posted-case-2025 (2 of 18 cases are photo mode)
- https://utakata.co.jp/media/tiktok-photo/ · https://www.active-note.jp/sns/photomode/ · https://e-pace.co.jp/column/tiktok-syashin/
- https://special.nikkeibp.co.jp/atclh/NXR/23/bytedance1024/ (**404 at time of writing** — Shogakukan claim is second-hand)

**Apps / pricing**
- https://calorix.ai/ja/compare/calorie-app-prices/ (checked 2026-10-23; publisher sells a competing app)
- https://apps.apple.com/jp/app/id963055562 (カロミル) · https://apps.apple.com/jp/app/id1124333484 (カロママプラス) · https://apps.apple.com/jp/app/id946099227 (YAZIO)
- https://minhyo.jp/yazio · https://appmatch.jp/946099227-2/ · https://androrank.com/?id=jp.co.lc.caloriemama
- https://sg.wantedly.com/companies/finc/post_articles/972079 (company-authored)
- Umax (no JP presence): https://apps.apple.com/jp/app/umax-ai-face-scan-rate-face/id6478508605 · id6761284153 · https://apps.apple.com/us/app/umaxx-looksmax-ai-umax/id6479165516

**Compliance / mascot (carried from first pass)**
- https://monolith.law/corporate/beauty-diet-advertising-restrictions · https://atsoho.com/blog/trainer-before-after-ad-rules
- https://www.comnico.jp/we-love-social/character-account · https://www.oricon.co.jp/special/54774/ · https://hashout.jp/?p=12312

**US comparators (carried from first pass)**
- https://www.netinfluencer.com/cal-ai-founder-zach-yadegari-breaks-down-the-influencer-playbook-behind-his-apps-growth/
- https://youmind.com/it-IT/landing/x-viral-articles/rizz-app-faceless-creator-growth · https://www.shortimize.com/blog/rizz-apps-b-roll-strategy-that-got-them-half-a-billion-views-on-tiktok

**Could not reach:** TikTok profile/tag pages (empty JS shell), Instagram (429/301), Markezine (403), X (402), caa.go.jp PDFs (403), Nikkei X-Trend ByteDance feature (404), company.finc.com (503).

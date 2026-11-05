# Instagram frame capture — data notes

`scraped_reels.tsv` — 429 Reels: caption, likes, comments, author, date, bucket, hashtag.
Analysis in [`../10_instagram_formats.md`](../10_instagram_formats.md).

`frames_manifest.tsv` — the Reels that had frames captured: shortcode, bucket, likes,
author, duration, frame count, caption. Analysis in
[`../11_instagram_visual_hooks.md`](../11_instagram_visual_hooks.md).

**The frame images themselves are deliberately not committed.** They are media, and the
brief said to keep video out of the repo. They lived in the session scratchpad, which is
ephemeral — so the manifest and the written analysis are the durable record, not the JPGs.
Any Reel listed here can be re-captured from its shortcode:
`https://www.instagram.com/reel/<shortcode>/`.

## How frames were obtained

Instagram serves video as blob/DASH, so there is no file to download and `ffmpeg` cannot be
used. Frames come from seeking a real headless browser's live `<video>` element to fixed
timestamps and screenshotting it — 0.5s intervals through the first 3 seconds, then every
2s. This captures burned-in on-screen text; it does **not** capture audio.

Capture rate is limited by an Instagram per-IP burst budget. A fresh browser context per
Reel helps but does not defeat it; sustained runs collapse to ~2% yield. The working
approach is small bursts with long gaps (`tools/ig_drip.sh`). See `../ASSUMPTIONS.md` §2b.

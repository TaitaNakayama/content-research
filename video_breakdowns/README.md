# Video breakdowns — what these are and how to read them

One file per analysed video. Each contains a timestamped transcript and a
hook/loop/payoff breakdown.

## Read this before you trust a breakdown

The brief asked for frame extraction every 0.5s and a merged visual + on-screen-text +
speech analysis. **That was not possible from this machine.** YouTube returns `HTTP 403`
for video and audio streams from this cloud IP, and TikTok blocks the IP outright. No
video file was ever downloaded, so no frame was ever extracted.

What *did* work is better than it sounds: YouTube's automatic captions come in a `json3`
format that carries a **start time per word**, in milliseconds. So every breakdown here is
built on real, precisely-timed speech from the actual video — not a paraphrase, and not
guesswork.

**Therefore:**

| Dimension | Status in these breakdowns |
|---|---|
| What was said, and exactly when | ✅ Primary evidence, millisecond-accurate |
| Words-to-first-claim, pacing, hook wording | ✅ Primary evidence |
| Loop-opening language, re-hook phrasing, payoff timing | ✅ Primary evidence |
| Closing line / verbal CTA | ✅ Primary evidence |
| On-screen text (wording, placement, duration) | ❌ Not observed |
| Cut frequency, framing, camera movement | ❌ Not observed |
| Visual teasers, the visual half of "wait for it" | ❌ Not observed |
| Cover / thumbnail | ❌ Not observed |

Anything about visuals in the wider report comes from secondary sources or is marked
`[inference]`. It is not from observation of these videos.

### The honest consequence for `taita.del`

A tricking clip's hook is mostly **visual**. The transcript method is therefore weakest
exactly where the tricking account lives. Two things were done about it rather than
glossing over it: the `del` corpus is weighted toward talking-over-footage, tutorial and
commentary videos where the structure is verbal, and pure-spectacle clips are treated
through secondary analysis instead. Treat verbal findings as evidence and visual findings
as research.

## Method

1. Candidate videos were nominated by the seven research workstreams, each giving a reason.
   **No video ID was ever guessed** — every ID came from a search result or a channel page.
   A guessed 11-character ID would be a fabrication, and a few nominations that only had a
   title were marked `SEARCH:` and resolved separately or dropped.
2. Metadata (title, channel, view count, duration, upload date) was fetched with `yt-dlp`,
   sequentially and with delays. **View counts in these files are tool-verified and stamped
   with a harvest time**, because they move.
3. Captions were fetched preferring the **original-language** track (`en-orig` / `ja-orig`).
   This matters: requesting `en` and `ja` together on an English video also returns a
   machine-*translated* Japanese track, which would have corrupted the Japanese analysis.
4. `tools/ytcap.py` converted the `json3` into two views: a **word-by-word hook window**
   (first 3 seconds, the window the brief cares about) and a **~1-second bucketed
   transcript** for the rest.
5. A breakdown was then written per video, labelling hook archetype, loops opened, re-hooks,
   payoff and ending.

Metadata requests were intermittently bot-checked. Where that happened the file records
`metadata_status: meta_blocked` and the view count reads `UNKNOWN` — the transcript is
still valid, only the view count is missing. No bot check was circumvented, no cookies or
logins were used, and harvesting ran sequentially rather than in parallel specifically to
stay within normal access patterns.

Videos whose captions were unavailable (`NOCAP`) were dropped from the corpus rather than
analysed from their titles.

## Files

`INDEX.md` lists every analysed video with its verified view count and caption track.
Counts per brand are given there, so the corpus size is visible rather than claimed.

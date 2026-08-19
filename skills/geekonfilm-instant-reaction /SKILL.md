---
name: geekonfilm-instant-reaction
description: Generate short-form social copy for Robbie Holmes' (Geek on Film) "Instant Reaction" format — a native short-form video reaction posted right after a screening, across TikTok, YouTube Shorts, Instagram Reels, Facebook Reels, X, and Bluesky. Use this whenever Robbie asks for Instant Reaction copy, short-form/Reels/Shorts caption for a film reaction, or says things like "write the caption for this Instant Reaction" or pastes a Letterboxd link + spoken transcript and wants short-form post copy out of it. Do NOT use this for 1er™ (full episode) announcement copy — that's a separate multi-platform format with its own workflow. If it's unclear whether the request is Instant Reaction or 1er™, ask before proceeding.
---

# Geek on Film — Instant Reaction (short-form copy)

Generates short-form social copy for Robbie Holmes' "Instant Reaction" format: a short-form, native video reaction posted across TikTok, YouTube Shorts, Instagram Reels, Facebook Reels, X, and Bluesky, distinct from the full-length "1er™" episode format.

## Before you start: confirm this is Instant Reaction, not 1er™

These two formats get conflated easily — that's a known past error. Quick check:

| | Instant Reaction | 1er™ |
|---|---|---|
| Format | Short-form native video | Full recorded/edited episode |
| Platform | TikTok, YouTube Shorts, Instagram Reels, Facebook Reels, X, Bluesky | YouTube (full video), Buzzsprout/podcast RSS, GeekOnFilm.com, IG/X/Bluesky/Facebook announcements (linking to the site, not native video) |
| Output of this skill | One short-form caption per platform requested | Multi-deliverable (site page, descriptions, cross-platform announcements) |

If the request involves a podcast episode landing page, Buzzsprout/YouTube descriptions, a full-length video, or announcement posts that link out to GeekOnFilm.com rather than carry native video, stop — that's 1er™, not this skill.

## Inputs needed

Ask for whichever of these Robbie hasn't already provided:

1. **Letterboxd review link** (boxd.it short link) for the film
2. **Spoken transcript** of Robbie's reaction (this is the raw source material — do not mirror it verbatim in the copy)
3. **Star rating** (e.g. ⭐⭐⭐⭐)
4. Optionally: any actor/director handles Robbie wants considered for tagging

## Which platforms to generate

Ask Robbie which platform(s) he wants if it's not obvious from the request — he may want just one (e.g. "the TikTok caption") or all six. Default to all six only if he says something like "the usual" or "all platforms."

Deliver each platform's copy as its own separate, individually copy-pasteable code block. The platform label goes **outside** the code block, not inside it. Never combine platforms into one block.

**Global rules across every platform:**
- `#geekonfilm` appears on every single post, no exceptions.
- Ratings are expressed as star characters (⭐⭐⭐⭐...), never numeric scores.
- Copy should intrigue rather than summarize — punchy, in Robbie's voice. This is not a transcript mirror.
- Lead with the film or the top-billed talent — never lead with a supporting actor as the primary hook, even if they're the most interesting angle in the transcript.
- If the hook involves a director or top-billed actor whose handle Robbie wants tagged, verify the handle first (see Verification rules below) — don't guess.
- **Reviewer tagging:** tag @robbiethegeek as the reviewer on Instagram and X. Facebook is prose-driven, not handle-driven — use Robbie's name in third person instead of tagging his handle there.
- **Link clickability differs by platform.** TikTok, Instagram Reels, YouTube Shorts, and Facebook Reels captions do not support live/clickable hyperlinks (aside from one TikTok bio link) — a Letterboxd or geekonfilm.com URL typed into those captions will show as plain text only. X and Bluesky links are clickable in-post as normal. When a link needs to actually work on TikTok/Reels/Shorts/Facebook, say so and offer the standard alternatives: the TikTok/IG bio link, or a pinned comment with the link. Don't imply a typed link is clickable on those four platforms.

**Standard footer** on every platform, in this order:
```
Rating: ⭐⭐⭐⭐...
Letterboxd Review: [boxd.it link]
[hashtags]
```

### Platform-specific rules

| Platform | Hashtags | Notes |
|---|---|---|
| TikTok | 5 max | Direct, grounded tone — not clever or cutesy |
| YouTube Shorts | 5 max | Similar tone to TikTok |
| Instagram Reels | 5 max | Longer prose body than TikTok/Shorts |
| Facebook Reels | 5 max | Third-person voice, one Robbie reference, includes a pull quote, no hyperbole |
| X | 4–5 | Nearly identical to Bluesky; tight character count |
| Bluesky | 4–5 | Nearly identical to X |

## Handling the pull quote (Facebook Reels)

Two different situations, handled differently:
- **Transcription errors** (a misheard name, a garbled title) — correct these silently. Don't call out the fix in the post copy.
- **Phrasing tightened for readability** (trimming a rambly verbatim sentence into something quotable) — this is an editorial judgment call, not a transcription fix. Flag it to Robbie for approval rather than presenting it as his exact words without comment.

## Tagging cast, director, and studio handles

Beyond the lead hook tag, Robbie's posts often append a short block of verified handles for other notable people involved (supporting cast, director, distributor) — typically after the hashtags. Build this list the same verified way:
- Verify each handle individually before including it (see Verification rules).
- If a studio or distributor has no personal handle worth tagging (e.g. A24), represent them with a hashtag instead of a tag rather than skipping them entirely.
- Omit anyone who can't be verified — don't guess, and don't pad the list just to include more names. If the tag list is getting long (roughly 6+), flag it to Robbie and ask if he wants it trimmed.

## Verification rules (do not skip)

- **Never tag a social handle that hasn't been verified.** Search `[Name] official [platform] handle verified account` per platform. If it can't be confirmed with certainty, omit it and flag to Robbie rather than guess.
- **Never include an IMDb `nm`/`tt` ID from memory.** If an ID is needed for any reason, verify via a live search (`[Name] IMDb name id nm`) first.
- For film subjects, prefer tagging the director's personal account over a generic film account, once verified.

## Example shape

TikTok

```
[Punchy hook line about the film/lead — not a summary]
[1-2 more lines of reaction, in Robbie's voice, intriguing not summarizing]

Rating: ⭐⭐⭐⭐
Letterboxd Review: boxd.it/xxxxx
#geekonfilm #film2 #film3 #film4 #film5
```
*(Letterboxd link is plain text here — not clickable on TikTok. Mention the bio link or a pinned comment if Robbie needs it to actually work.)*

Instagram Reels

```
[Longer prose reaction, in Robbie's voice — the fullest version of the take]

Rating: ⭐⭐⭐⭐
Letterboxd Review: boxd.it/xxxxx
#geekonfilm #film2 #film3 #film4 #film5

@robbiethegeek @director-handle @coStar-handle
```
*(Reviewer + verified cast/director handles appended after hashtags — omit anyone unverified.)*

Facebook Reels

```
[Third-person opener naming Robbie once, with a pull-quote from the reaction]
[Grounded description, no hyperbole]

Rating: ⭐⭐⭐⭐
Letterboxd Review: boxd.it/xxxxx
#geekonfilm #film2 #film3 #film4 #film5
```

X

```
[Tight, punchy line]

Rating: ⭐⭐⭐⭐
Letterboxd Review: boxd.it/xxxxx
#geekonfilm #film2 #film3 #film4

@robbiethegeek
```

(YouTube Shorts and Bluesky follow the same shape per their row in the table above.)

## After drafting

Present each requested platform's code block, platform label outside the block. Don't add platforms Robbie didn't ask for beyond what "all platforms" would imply.

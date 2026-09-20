<h1>Binay Bhandari</h1>

**I build browser extensions that take a tedious job and make it one click.**

Bardiya, Nepal · [webmatrices.com](https://webmatrices.com)

---

Most of what I ship starts the same way: something on the internet is deliberately slow to undo. Unsubscribing one sender at a time. Unliking three thousand TikToks. Skipping the same sponsor read on every video. Paying monthly for a feature the browser can already do.

So I write the thing that does it in bulk — and I write it so it runs **on your machine, not my server.** No backend to trust, no account to create, no telemetry. Where an API key is needed, it's yours and it stays in your browser.

Four are public. One is a paid product. All of them are vanilla JavaScript with no build step, because a browser extension that needs a toolchain to install isn't really solving anything.

<br>

## Selected work

### [KarmaFarm](https://github.com/binay-py/karmafarm) — Reddit copilot
Drafts comments and posts in your own voice. You give it three real upvoted comments; it matches their rhythm, slang and length rather than being told to "write casually." Reads the live thread, studies the subreddit from its own top-scored posts, and runs on your LLM key across eight providers.

`Chrome MV3` · `JavaScript` · sold at [webmatrices.com/karmafarm](https://webmatrices.com/karmafarm)

<br>

### [sanduk](https://github.com/binay-py/storagesystem) — your locked chest in the cloud
An encrypted photo and video library with no storage bill. Telegram holds the bytes, a Cloudflare Worker routes them, and your browser holds the only key — filenames, albums and thumbnails are all AES-GCM encrypted before they leave. There are no accounts; a 32-byte secret is your identity. The server can't decrypt your files, and can't recover them either.

`Cloudflare Workers` · `D1` · `Zero-knowledge` · `AGPL-3.0`

<br>

### [PremiumTube](https://github.com/binay-py/youtube-premium) — YouTube, unbundled
Auto-skips sponsors, intros and ads; adds background play, picture-in-picture and automatic max quality. Four detection methods run in parallel — SponsorBlock, chapter metadata, description timestamps and caption keyword matching — so a segment missed by one is usually caught by another.

`Chrome MV3` · `SponsorBlock` · `Declarative Net Request`

<br>

### [TikTok Bulk Unlike](https://github.com/binay-py/tiktokvidunlike) — clear thousands of likes
A browser console script that works through a liked-videos list in batches. No extension to install, no API keys, no dependencies — paste it and let it run.

`JavaScript` · `Browser console`

<br>

## How I build

**No backend unless the problem needs one.** Every project above stores its data in the browser. It's less to run, less to breach, and less to ask people to trust.

**Your key, not mine.** Where a service costs money per request, you bring your own credentials. Nothing routes through me.

**Vanilla, mostly.** No framework, no bundler, no build step. It keeps extensions small and makes a five-year-old repo still openable.

**Docs that match the code.** Every README here has been read back against its own source. A README that describes a folder which no longer exists is worse than no README at all.

<br>

## Working with

```
JavaScript · Chrome Extensions (Manifest V3) · Cloudflare Workers · D1 · SQLite
TypeScript · Node · Web Crypto · REST + OAuth2 · PWA / Service Workers
```

<br>

---

<sub>Products at <a href="https://webmatrices.com">webmatrices.com</a> · Open to interesting problems — reach me through GitHub.</sub>

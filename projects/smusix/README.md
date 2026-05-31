# Smusix — Music Discovery App Case Study

## Summary

Smusix was a music discovery app built to help users discover emerging artists through a TikTok-style mobile experience. Users could swipe through music content, discover new artists and listen to songs they had not found on other platforms.

![Smusix brand](./assets/01-brand.png)

## Context

I started Smusix while writing about app and game growth on my blog. The initial idea received enough feedback that I decided to focus on the product. I learned mobile development and built the first MVP natively in Java for Android and Swift for iOS.

In 2025, I entered Lanzadera with Smusix and launched the app three months into the program.

## Problem

Emerging artists struggle to get discovered because most music platforms are optimized around already-known artists, playlists and algorithms with strong historical signals.

## What I built

- Native Android app.
- Native iOS app.
- Music discovery feed.
- Artist and listener experience.
- Artist upload flow.
- Large video upload flow.
- Server-side media size reduction before playback.
- Weekly discovery and playlist mechanics.
- Public showcase repository with sanitized mobile code previews.

## Technical highlights

- Built the MVP natively in Java and Swift.
- Designed a swipe-based discovery flow for music.
- Supported large video uploads between roughly 500 MB and 1 GB.
- Used server-side processing to reduce file size before serving media back to users, making playback feel fast after upload processing.

## Visual walkthrough

Additional app screenshots can be added to this folder over time:

```text
assets/03-discovery-feed.png
assets/04-artist-profile.png
assets/05-upload-flow.png
assets/06-video-processing-architecture.png
```

## Demo videos

[Watch Spanish presentation](https://youtu.be/DWOtsSV2IXY?si=7-LkfMndioc40wn9)

[Watch English presentation](https://youtu.be/F7sIa4aciTc?si=y076RbCxUidXqJKC)

## Results

- 30,000 downloads.
- 15,000 artists.
- 5,000 daily active users.
- 20,000 songs.
- Large media upload and compression flow working in production.

## Related repository

[View public source showcase](https://github.com/davidtrotonda/smusix-mobile-showcase)

The public repository is a sanitized showcase of the original iOS and Android code. Sensitive configuration, credentials and private production data are not included.

## What I learned

- Native mobile development is powerful, but maintaining two platforms adds complexity.
- Media-heavy products need strong upload, compression and playback architecture from the beginning.
- Discovery products need both product quality and a repeatable acquisition loop.
- Focus matters: adding too many features before validating revenue can slow down progress.

## What I would improve today

- Use a more modular backend architecture.
- Add clearer analytics around listener-to-artist discovery loops.
- Build stronger monetization experiments earlier.
- Invest earlier in moderation, observability and media pipeline monitoring.


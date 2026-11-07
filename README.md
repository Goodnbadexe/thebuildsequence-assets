# The Build Sequence — Social Slide & Reel Assets

Public asset host (`jsDelivr` + `raw.githubusercontent.com`) for Instagram, Facebook, and YouTube Shorts publishing via **[tbs-poster](https://github.com/Goodnbadexe/tbs-poster)**.

## Structure & Retention Policy

- `day-NN-<category>-<slug>/` — Carousel PNG slides (`slide-1.png` … `slide-N.png`) for each daily edition.
- `reels/day-NN-v3.mp4` — Active rendered vertical reel MP4s (`ReelV3` format). Superseded earlier renders (`v1`/`v2`) are pruned once a newer version is published to keep repository size within CDN limits.
- `ship-log/` — Weekly ship-log carousel assets.

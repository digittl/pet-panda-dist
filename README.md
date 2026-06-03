# pet-panda-dist

Public distribution feed for **PandaPal**.

The source repo ([digittl/pet-panda](https://github.com/digittl/pet-panda)) is
private, so its GitHub Pages site and release assets aren't publicly reachable —
and Sparkle can't authenticate to fetch them. This repo exists purely to host
the update feed in the open:

- `appcast.xml` — the Sparkle feed PandaPal polls daily
- `PandaPal.zip` — the signed app archive the appcast points at

Both are published automatically by the `release` workflow in the private
source repo on every GitHub Release. Don't edit anything here by hand.

Served at: https://digittl.github.io/pet-panda-dist/

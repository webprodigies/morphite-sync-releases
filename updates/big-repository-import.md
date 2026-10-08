---
id: big-repository-import
title: Big repositories, without the flood
date: 2026-10-07
tags: [improved]
summary: Turning on issue sync for a repository with hundreds of open issues now asks first. Bring them all, only the labelled ones, or none.
cover: big-repository-import/big-import.png
---
When a repository has more than 300 open issues, Morphite asks before bringing them onto your board:

- **Sync all**: every open issue, newest first, in the background, with progress in Issue sync
- **Only labelled**: just the issues carrying labels you pick from the repository's own
- **Cancel**: none of the existing issues come in

Either way, sync stays on: issues opened or changed from now on keep arriving.

## Improved

- Boards with thousands of synced tickets open and scroll smoothly
- Big imports read quickly, and slow down on their own when GitHub asks
- One repository shared by several projects can send its issues to each project by label
- A label that was removed on GitHub can be removed from your intake labels too

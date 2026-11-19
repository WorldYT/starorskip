# Star or Skip — repo list

Public link-in-bio page for [Star or Skip](https://www.youtube.com/@starorskip) (YouTube Shorts `@starorskip`, Instagram `@starorskip.repos`).

**Live site:** https://worldyt.github.io/starorskip/

This repository holds only the generated static page. The list is rebuilt from the channel tracker after each public post:

```bash
node scripts/build-repo-list.mjs --deploy
```

The page lists posted reviews only (a YouTube Short or Instagram Reel URL in the tracker), newest first, one entry per repo. No analytics or trackers.

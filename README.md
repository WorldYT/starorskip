# Star or Skip — repo list

Public link-in-bio page for [Star or Skip](https://www.youtube.com/@starorskip) (YouTube Shorts `@starorskip`, Instagram `@starorskip.repos`).

**Live site:** https://worldyt.github.io/starorskip/

Hosted on GitHub Pages from the user site [WorldYT/WorldYT.github.io](https://github.com/WorldYT/WorldYT.github.io) (path `/starorskip/`). The companion repo [WorldYT/starorskip](https://github.com/WorldYT/starorskip) holds a copy of the generated files; project Pages could not be enabled from Actions (`Resource not accessible by integration`).

This page is rebuilt from the channel tracker after each public post:

```bash
node scripts/build-repo-list.mjs --deploy
```

The list includes posted reviews only (a YouTube Short or Instagram Reel URL in the tracker), newest first, one entry per repo. No analytics or trackers.

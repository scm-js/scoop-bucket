# scm-js/scoop-bucket

A [Scoop](https://scoop.sh) bucket for `scmjs`, the [scmJS](https://scmjs.dev) command line for
StarCraft: Brood War maps, replays and bots.

```powershell
scoop bucket add scm-js https://github.com/scm-js/scoop-bucket
scoop install scmjs
```

The manifest follows the releases of [scm-js/scm-js](https://github.com/scm-js/scm-js): the
Excavator workflow reads the newest release and its `SHA256SUMS`. The command line's guide is at
[docs.scmjs.dev/cli](https://docs.scmjs.dev/cli/).

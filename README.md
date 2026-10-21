# nickprignano.github.io

**The AVD repos moved.** On 2026-10-21 the public Azure Virtual Desktop repos moved from this
account to the [avd-ops](https://github.com/avd-ops) organization. Start at
[avd-ops.dev](https://avd-ops.dev/).

| Old link | New home |
|---|---|
| github.com/nickprignano/avd-landing-zone | [github.com/avd-ops/avd-landing-zone](https://github.com/avd-ops/avd-landing-zone) |
| nickprignano.github.io/avd-landing-zone/portal/ | [avd-ops.github.io/avd-landing-zone/portal/](https://avd-ops.github.io/avd-landing-zone/portal/) |
| github.com/nickprignano/avd-current-state | [github.com/avd-ops/avd-current-state](https://github.com/avd-ops/avd-current-state) |
| github.com/nickprignano/avd-second-brain | [github.com/avd-ops/avd-second-brain](https://github.com/avd-ops/avd-second-brain) |
| github.com/nickprignano/avd-swarm | [github.com/avd-ops/avd-swarm](https://github.com/avd-ops/avd-swarm) |
| github.com/nickprignano/avd-assess | [github.com/avd-ops/avd-assess](https://github.com/avd-ops/avd-assess) |
| github.com/nickprignano/avd-ops | [github.com/avd-ops/avd-ops](https://github.com/avd-ops/avd-ops) |

Old GitHub links, `git clone` URLs and existing clones keep working: GitHub redirects a moved repo.
To point a clone at the new home anyway: `git remote set-url origin https://github.com/avd-ops/<repo>.git`.

## What this repo does

GitHub does not redirect a moved repo's Pages site, so links to `nickprignano.github.io/<repo>/...`
would break. This user site catches them and forwards them to `avd-ops.github.io/<repo>/...`:
`404.html` handles any path, and plain pages cover the portals for browsers without JavaScript.

To cover another moved repo, add its name to `moved` in `404.html`.

Personal project, not for production, provided as is, not affiliated with the author's employer,
Liquidware or Microsoft.

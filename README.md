# games.torvellan.com

The small public website for Squeak Machine and Sky Glider: a home page, the privacy policy, and `app-ads.txt` (which tells advertisers which ad networks may sell ad space in the apps). Served by GitHub Pages; the domain stays at GoDaddy.

| File | Purpose |
|---|---|
| `index.html` | Home page with both games |
| `privacy.html` | Privacy policy (linked from both store listings) |
| `app-ads.txt` | Authorized ad sellers. Add the AdMob line once the account exists |
| `CNAME` | Tells GitHub Pages to serve this site at `games.torvellan.com` |

## DNS (at GoDaddy)

| Type | Name | Value |
|---|---|---|
| CNAME | `games` | `jatchison67.github.io` |

GitHub issues the HTTPS certificate automatically once DNS resolves. Then enable "Enforce HTTPS" in the repo's Pages settings.

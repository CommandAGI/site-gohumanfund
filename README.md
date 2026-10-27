# site-gohumanfund

The site of Go Human Fund, live at <https://gohuman.commandagi.app>.

`index.html`, `styles.css`, `script.js` and `CNAME` are copied verbatim from
[`gohumanfund/gohumanfund.github.io`](https://github.com/gohumanfund/gohumanfund.github.io) at commit
`a36edf51cb5bca686f4506825ccf0a6533258127` (read 2026-10-27). The wording — the thesis, the checks, the
portfolio, the outcomes and the founder's letter — is the fund's own; it is published unchanged, because
investment wording needs the owner's lawyer before any change of meaning.

`site.json` is what makes this folder a site on CommandAGI (`docs/site-hosting.md` in the CommandAGI
repository): slug `gohuman`, production branch `main`.

`CNAME` is GitHub Pages' own file and nothing here reads it. **`gohuman.fund` stays on its current host**: the
site is reachable at `gohuman.commandagi.app` until the owner moves the domain.

```sh
commandagi sites deploy seed/drive/platform/org-gohumanfund/sites/gohuman --prod
commandagi sites logs gohuman
```

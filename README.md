# chuckowen.github.io

Personal site, served by GitHub Pages at [chuckowen.co](https://chuckowen.co).

## Structure

Static hand-written HTML, no build step. `index.html` is the landing page;
articles are standalone pages under `research-articles/`, `leadership-articles/`,
and `engineering-articles/`, each carrying its own copy of the shared styles.

## Analytics

Pageview analytics via [GoatCounter](https://www.goatcounter.com/) — dashboard at
[chuckowen.goatcounter.com](https://chuckowen.goatcounter.com) (login required).
Every page includes the counting snippet just before `</body>`:

```html
<script data-goatcounter="https://chuckowen.goatcounter.com/count"
        async src="//gc.zgo.at/count.js"></script>
```

New pages must include this snippet — there is no shared template to inherit it
from. The snippet contains no secrets; the site code is visible in every page's
source anyway, and dashboard access is controlled by the GoatCounter account,
not by anything in this repo.

# SwitchFlip website

Marketing site for SwitchFlip LLC, served by GitHub Pages at https://switchflip.ai.

Single static page: edit `index.html` and push to `main`.

Other files:

- `404.html`: the not-found page. It uses absolute paths, since it can be served at any address.
- `robots.txt` and `sitemap.xml`: add a new page to the sitemap when you add one.
- `img/share.png`: the 1200 by 630 image that shows when the site is shared in a text, on LinkedIn, or in Slack.

`www.switchflip.ai` needs a DNS record at the registrar: a CNAME for `www` that points to `jakeryannelson.github.io`. GitHub Pages then redirects it to `switchflip.ai`.


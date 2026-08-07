# datebook-web

The public face of [Datebook](https://github.com/chrissav/datebook) — an app for two
people to plan dates together and keep the ones they went on.

Served by GitHub Pages from the `main` branch:

| Page | URL |
|---|---|
| Privacy policy | https://chrissav.github.io/datebook-web/privacy.html |

`privacy.html` is generated from `docs/privacy-policy.md` in the app repo, which stays the
source of truth — edit it there and copy the page across, so the words people read and the
words in the codebase can't drift apart.

Still to come: a landing page at `index.html`, a support page Apple asks for, and
`EXPO_PUBLIC_WEB_BASE_URL` pointed here so share links become real links rather than a
`datebook://` scheme that only works if you already have the app.

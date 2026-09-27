# heshiz.com

Landing page, privacy policy and support page for Heshiz Family. Plain HTML,
served by GitHub Pages at https://heshiz.com.

| Page | Used for |
|---|---|
| `index.html` | landing |
| `privacy.html` | privacy policy URL in App Store Connect and Play Console |
| `support.html` | support URL, and the account-deletion URL Play's Data safety asks for |

Colours and type follow the app's design system (`push-fit/HeshiisApp/docs`).
`icon.svg` and `icon.png` are copies of the app icon.

## Hosting

GitHub Pages, branch `main`, folder `/`. `CNAME` holds `heshiz.com`.

DNS at the registrar:

```
A     @    185.199.108.153
A     @    185.199.109.153
A     @    185.199.110.153
A     @    185.199.111.153
CNAME www  introinnovation.github.io
```

Then in the repo settings, Pages, set the custom domain to `heshiz.com` and
tick "Enforce HTTPS" once the certificate is issued.

## Mailboxes the pages promise

`support@heshiz.com` and `privacy@heshiz.com` must deliver somewhere before
the app is submitted.

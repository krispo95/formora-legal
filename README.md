# Formora — legal

Public Privacy Policy and Terms of Service for the **Formora** iOS app,
served via GitHub Pages.

> The app itself lives in a separate (private) repository; this repo
> only holds static HTML so App Store Connect and the in-app Settings
> links have a stable public URL to point at.

## Live site

<https://krispo95.github.io/formora-legal/>

| Locale | Privacy | Terms |
|--------|---------|-------|
| EN | [privacy.html](https://krispo95.github.io/formora-legal/privacy.html) | [terms.html](https://krispo95.github.io/formora-legal/terms.html) |
| RU | [privacy.ru.html](https://krispo95.github.io/formora-legal/privacy.ru.html) | [terms.ru.html](https://krispo95.github.io/formora-legal/terms.ru.html) |
| ES | [privacy.es.html](https://krispo95.github.io/formora-legal/privacy.es.html) | [terms.es.html](https://krispo95.github.io/formora-legal/terms.es.html) |

The English Privacy URL is the one to paste into App Store Connect's
"Privacy Policy URL" field; the in-app Settings → Privacy link routes
to the locale that matches the user's device language and falls back to
English.

## Editing

Open the relevant `.html`, edit, bump the "Last updated" date at the
top, commit. GitHub Pages rebuilds within ~1 minute.

If a substantive change ships, mention it in the next app release notes
so users know the policy was updated.

## Hosting setup (one-time)

1. **Settings → Pages**
2. *Source*: **Deploy from a branch**
3. *Branch*: `main` · *Folder*: `/ (root)`
4. Save.

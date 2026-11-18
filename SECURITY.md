# Security

## Supported versions

Only the latest release receives fixes.

## Reporting a vulnerability

Please **don't open a public issue**. Use **Security › Report a vulnerability** in this
repository (GitHub's private reporting): only the maintainer can read it. Include the
Brsket version, macOS version and the steps to reproduce.

## How Brsket protects you

Brsket opens links from the internet and runs a small engine on your Mac, so its entry
points are deliberately narrow:

- **App Sandbox** is on for the app and for every tool it runs. They can reach only their
  own folders, Downloads › Brsket and the files you choose.
- **The local engine** listens on 127.0.0.1. It accepts only its exact host name (no DNS
  rebinding), refuses requests coming from web pages (`Origin`, `Sec-Fetch-Site`) and
  requires a key created at each launch, known only to Brsket's window.
- **Links can't reach the engine itself.** Addresses on this Mac are refused.
- **Photos chosen by a web page** can't point to this Mac or to your home network, also
  through redirects or through names that resolve to private addresses. They are saved only
  with image and video extensions.
- **Phone access** is off by default. When on, it works on your local network and needs a
  code, which you can replace at any time. Failed attempts are limited.
- **Site sign-ins** happen on the site's own page. Brsket keeps the cookies needed to
  download and never reads or stores your password. "Forget sign-ins" removes them.
- Brsket has no account and no analytics.

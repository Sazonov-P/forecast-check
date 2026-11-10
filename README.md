# forecast-check

Public pages of the Forecast Check browser extension, served by GitHub Pages: https://sazonov-p.github.io/forecast-check/

- [Privacy policy](privacy.md)
- [25-second demo](demo.html) — MP4/GIF and real-data example of the published 0.1.4 release.
- [After removal](uninstalled.html) — opened by the extension (0.1.7+) when it is removed: a thank-you and a link to a short survey. Address parameters: `v` (version) and `lang` (interface language) only. The survey link is the `FORM_URL` line of the page; until it is set, the page offers an email.

Public demo: https://sazonov-p.github.io/forecast-check/demo.html

Media assets are small ordinary Git files, not LFS pointers. Publish with `python ../scripts/publish-site.py` using the existing GitHub CLI login; `../scripts/publish-site.ps1` is also available where PowerShell scripts are enabled. Only public site files belong here, never extension ZIPs or browser profiles.

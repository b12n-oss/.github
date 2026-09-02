# .github

Organization-wide defaults for [b12n-oss](https://github.com/b12n-oss).

GitHub serves `profile/README.md` as the organization's landing page, and applies
every community health file here to any repo in the org that does not have its
own. Adding a file here changes every repo at once, so change it deliberately.

| File | Where it shows up |
| --- | --- |
| `profile/README.md` | The org page at github.com/b12n-oss |
| `CODE_OF_CONDUCT.md` | Every repo without its own |
| `CONTRIBUTING.md` | Every repo without its own, and the "Contributing" link on new issues and PRs |
| `SECURITY.md` | The Security tab of every repo without its own |
| `.github/ISSUE_TEMPLATE/` | The issue composer, org-wide |
| `.github/PULL_REQUEST_TEMPLATE.md` | The PR composer, org-wide |

Only the profile lives here so far. The homepage it points at is a separate
repo, [`b12n-oss.github.io`](https://github.com/b12n-oss/b12n-oss.github.io).

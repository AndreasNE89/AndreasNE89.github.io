# AndreasNE89.github.io

Public privacy, support and contact pages for all apps, served at <https://andreasne89.github.io/>.

| App | Pages |
| --- | --- |
| Pryglass (formerly Signal/Block) | `/pryglass/` (about, privacy, support); `/signal-block/` redirects there |
| Dioptra | `/dioptra/privacy.html` (privacy), `/dioptra/support.html`; `/dioptra/` carries the same policy text (see below) |
| Clipwell | `/clipwell/` (privacy, generated from the clipwell repo), `/clipwell/plus.html` |
| StampStack | `/quell/privacy-policy.html`, `/quell/attributions.html` |
| Brolly | `/brolly-privacy/` |
| X Country Block | `/x-country-block/privacy.html` |

Paths match the URLs already used in store listings — do not rename them without adding a redirect.

## Dioptra: two copies of one policy

`/dioptra/privacy.html` is the Dioptra privacy policy's permanent address. `/dioptra/index.html` carries the
same full text, because Dioptra 1.1 opens `/dioptra/` from Help ▸ Privacy Policy and the App Store record
points there until it is changed. Keep the two identical, including the "Last updated" date, apart from the
note at the top of `index.html` and the canonical link in `privacy.html`, and keep both in step with
`docs/PRIVACY.md` in the app repository. Dioptra's pages keep their own look (teal and amber, inline mark)
and load nothing: each carries a `Content-Security-Policy` meta tag of `default-src 'none'`.

The support page's "Known issues in versions 1.0 and 1.1" section, and the version-1.0 note in the Photos
and Mail answer, come out once 1.2 is on the App Store and 1.0 is no longer in use. Check the 1.2 release
notes against each known issue first.

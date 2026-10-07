# trackcapture-legal

Public legal pages for **TrackCapture (트랙캡처)**, a free running and cycling camera app by Matelog (메이트로그). Published with GitHub Pages at <https://matelogdev-create.github.io/trackcapture-legal/>.

The app's source code lives in a separate private repository. This repository only holds documents that must be publicly reachable (app stores, Meta app review, in-app settings links).

## Pages

| Document | Language hub (auto-redirects by browser language) | ko | en | zh-Hans | ja |
|---|---|---|---|---|---|
| Privacy Policy | [/privacy/](https://matelogdev-create.github.io/trackcapture-legal/privacy/) | [ko](ko/privacy.md) | [en](en/privacy.md) | [zh-Hans](zh-Hans/privacy.md) | [ja](ja/privacy.md) |
| Terms of Use (incl. location-based service terms) | [/terms/](https://matelogdev-create.github.io/trackcapture-legal/terms/) | [ko](ko/terms.md) | [en](en/terms.md) | [zh-Hans](zh-Hans/terms.md) | [ja](ja/terms.md) |
| Data Deletion | [/data-deletion/](https://matelogdev-create.github.io/trackcapture-legal/data-deletion/) | [ko](ko/data-deletion.md) | [en](en/data-deletion.md) | [zh-Hans](zh-Hans/data-deletion.md) | [ja](ja/data-deletion.md) |

## Where these URLs are used

- App settings links: `EXPO_PUBLIC_PRIVACY_URL` → `/privacy/`, `EXPO_PUBLIC_TERMS_URL` → `/terms/`
- App Store Connect: Privacy Policy URL, Support URL
- Google Play Console: Privacy policy, Data safety
- Meta for Developers (Instagram Stories sharing): Privacy Policy URL, User data deletion URL → `/data-deletion/`

Changing a path breaks those links, so keep the URLs stable.

## Editing

- The Korean version is the source of truth. Update all four languages in the same commit.
- Keep the facts in sync with the app: no sign-up, no servers, data stored on device only, external calls limited to map tiles (OpenFreeMap) and user-initiated sharing.
- When a change is material, update the effective date and announce it in the app update notes (terms: 7 days ahead, 30 days for unfavorable changes).
- Pages rebuild automatically on push to `main` (Jekyll, `jekyll-theme-minimal`).

## Status

Drafts dated 2026-10-07. Replace the effective date with the release date and remove the "(초안)/(draft)" markers before the store submission. Legal review is recommended before release.

## Contact

lucymoon.d@gmail.com

# Brainigo — legal documents

Public hosting for the legal pages referenced by the Brainigo app and its store listings (Google Play, the
App Store). The app's own source repository is private, so these live here, published with GitHub Pages.

| Document | URL |
|---|---|
| Privacy Policy | https://danteata.github.io/brainigo-legal/ |
| Terms of Use | https://danteata.github.io/brainigo-legal/terms/ |
| Delete your account | https://danteata.github.io/brainigo-legal/delete-account/ |

## Editing

Plain HTML with one shared `style.css`; no build step. Change the "Last updated" date on a page whenever its
content changes.

The privacy policy describes the app's real data flows: on-device microphone analysis (never recorded),
optional sign-in (Clerk), the backend (Convex), tutors, lessons and messages, video lessons (LiveKit), the
AI coach (Google Gemini, checked by TypeSafe), email, web push, and web-only usage statistics (Amplitude,
held for Under 13 profiles). If the app adds a third-party service, a Convex table holding personal data, a
permission, or changes what account deletion removes, update these pages in the same change.

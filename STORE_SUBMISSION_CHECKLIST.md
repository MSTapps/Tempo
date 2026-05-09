# Store Submission Checklist

This project is closer to store-ready. Final icon/screenshot assets, public hosting, and live browser/store-account testing remain before submission.

## Completed

- Uses `activeTab`, `scripting`, and `storage` only.
- Removed automatic `<all_urls>` content script injection.
- Injects the content script only after the user clicks a popup action.
- Skips sensitive fields such as passwords, SSNs, tax IDs, birth dates, and payment fields.
- Does not submit forms.
- Stores profile data locally in browser storage.
- Includes local text/HTML/Markdown/JSON document import.
- Includes resume-like page scanning after user click.
- Includes first-pass Firefox manifest variant.
- Includes draft privacy policy.
- Includes recommended category: Productivity.
- Includes recommended privacy declarations: no analytics, no telemetry, no remote services, no data sale, no third-party data sharing.
- Includes homepage copy.
- Includes Safari distribution notes.

## Still Needed Before Publishing

- Add production PNG icons and store screenshots.
- Host `index.html` and `privacy.html` publicly, recommended at `https://mstapps.github.io/Tempo/` and `https://mstapps.github.io/Tempo/privacy.html`.
- Build Safari package with Apple's Safari Web Extension Packager or Xcode tooling.
- Test install packages in Chrome, Edge, Firefox, and Safari.
- Review each store's latest policy checklist again immediately before submitting.

## Prepared Store Files

- `STORE_METADATA.md`: listing copy, single-purpose statement, category, and permission justifications.
- `STORE_PRIVACY_DECLARATIONS.md`: Chrome/Mozilla-style privacy and data declaration answers.
- `HOMEPAGE_COPY.md`: public homepage copy.
- `privacy.html`: public privacy policy source.
- `SAFARI_DISTRIBUTION.md`: Safari packaging/distribution notes.

## Permission Justification

- `storage`: saves profile details, settings, and imported document metadata locally.
- `activeTab`: lets the extension inspect/fill only the current tab after a user click.
- `scripting`: injects the autofill script into the active tab only when requested.

## Known Limits

- PDF, DOC, and DOCX files are accepted as document records but are not parsed yet.
- File upload fields on job sites cannot be set programmatically by browser extensions.
- CAPTCHA, account login, identity verification, and eligibility questionnaires require user action.

## Current External Blockers

- Public homepage URL is not live until `index.html` is hosted.
- Public privacy policy URL is not live until `privacy.html` is hosted.
- Safari package/testing requires App Store Connect Safari Web Extension Packager access or macOS/Xcode testing access.

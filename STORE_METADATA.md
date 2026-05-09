# Tempo Store Metadata

Publisher: MSTapps  
Support email: TempoSupportApp@gmail.com  
Recommended category: Productivity  
Recommended homepage URL: `https://mstapps.github.io/Tempo/`  
Recommended privacy policy URL: `https://mstapps.github.io/Tempo/privacy.html`

## Short Description

Tempo helps you store resume, CV, cover letter, work history, education, and reference details locally, then autofill repetitive job application fields after you click the extension.

## Full Description

Tempo is a local-first job application autofill assistant for people who repeatedly enter the same resume, CV, cover letter, work history, education, and reference information into job application portals.

Tempo stores your profile in your browser and only runs on a page after you click a popup action. You can preview detected fields, autofill empty visible fields, import text-based resume documents, or scan a resume-like page to merge missing profile details.

Tempo is designed for privacy-sensitive job application workflows:

- Profile data is stored locally in browser storage.
- Resume and cover letter text is not sent to external servers.
- The extension does not run automatically on every website.
- The extension does not submit applications.
- Sensitive fields such as passwords, SSNs, tax IDs, birth dates, and payment details are skipped.

Tempo includes first-pass support for common employer and public-sector application styles, including government, education, Greenhouse-style, Breezy-style, Workday-style, and reference-heavy forms. Some complex portals may still require manual review, especially pages with CAPTCHA, login-only workflows, custom eligibility questionnaires, or file upload requirements.

## Single Purpose

Tempo helps users locally store job application profile details and fill repetitive job application form fields after a user click.

## Chrome Privacy Declarations

Data collection: No data is collected or transmitted by MSTapps.  
Data sale: No.  
Data transfer to third parties: No.  
Remote code: No.  
Analytics or telemetry: No.  
User activity tracking: No.  
Website content access: Only the active tab after a user clicks a Tempo action.  
Primary purpose: Productivity.

## Chrome Permission Justifications

`storage`: Saves the user's profile, settings, and imported document metadata locally in the browser.

`activeTab`: Allows Tempo to inspect and fill the current tab only after the user clicks preview, autofill, or scan.

`scripting`: Injects the autofill script into the active tab only after a user action.

## Mozilla Data Collection Declaration

Tempo stores personal data locally in the browser as part of its functionality. MSTapps does not collect, receive, sell, transmit, or share this data.

Personal data handled locally:

- Name and contact information
- Resume, CV, cover letter, work history, education, skills, and references
- Imported text/HTML/Markdown/JSON document content used to populate the local profile

Technical and interaction data collected by MSTapps: None.

## Safari Notes

Recommended category: Productivity.  
Distribution path: Safari Web Extension Packager in App Store Connect.  
Apple Developer Program access required: Yes.  
Mac/Xcode required: Not necessarily for the web packager route, but still useful for local Safari testing.

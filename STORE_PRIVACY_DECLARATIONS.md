# Tempo Privacy and Data Declarations

These answers are prepared for store submission forms.

## Recommended Answers

Analytics or telemetry: No  
Remote logging or crash reporting: No  
Remote AI or parsing services: No  
User account required: No  
Data sold: No  
Data shared with third parties: No  
Data transmitted to MSTapps: No  
Data stored locally: Yes  
Category: Productivity

## Data Handled Locally

Tempo locally stores user-provided job application profile information:

- Name
- Email address
- Phone number
- Address
- LinkedIn and portfolio URLs
- Resume, CV, cover letter, and summary text
- Work history
- Education
- Skills
- References
- Imported text/HTML/Markdown/JSON document content used to populate the profile
- Document names and parsed/not-parsed status

## Data Not Collected by MSTapps

MSTapps does not collect or receive:

- Browsing history
- Website activity
- Resume/profile contents
- Job application contents
- Analytics events
- Crash logs
- Device identifiers
- Location data
- Financial/payment information
- Health information
- Authentication credentials

## Permission Justification

`storage`: Required to save the local profile, local settings, and imported document metadata.

`activeTab`: Required so Tempo can inspect the current page only after the user clicks a popup action.

`scripting`: Required to inject the form-detection/autofill script into the active tab only after a user action.

## Public Policy Language

Tempo stores resume, CV, cover letter, work history, education, reference, and related job application profile information locally in your browser. MSTapps does not collect, receive, sell, transmit, or share this information. Tempo runs on a page only after you click a Tempo action, and it never submits job applications automatically.

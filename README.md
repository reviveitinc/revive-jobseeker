# Revive Job Seeker Registration

Job seeker registration portal and SMS communication consent form for Revive Software Systems.

## Features

- **Candidate Registration:** Collects candidate contact information, job title/role of interest, and preferred location.
- **SMS Communication Consent:** TCPA-compliant optional SMS consent checkbox with disclosures, opt-out instructions, and links to Terms & Privacy Policy.
- **Firebase Hosting:** Pre-configured for deployment with Firebase Hosting.

## Project Structure

```
.
├── .firebaserc          # Firebase project configuration ("revive-jobseeker")
├── firebase.json        # Firebase Hosting settings
├── .gitignore           # Git ignore rules for Firebase & Node
├── public/              # Production web root
│   ├── index.html       # Registration page
│   └── 404.html         # 404 error page
└── y/                   # Compatibility web root
    ├── index.html
    └── 404.html
```

## Local Development

You can preview the site locally using any static file server:

```bash
# Using Python
python3 -m http.server 8000 --directory public
```

Then visit `http://localhost:8000`.

## Deployment

Deploy to Firebase Hosting:

```bash
firebase deploy
```


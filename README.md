# Revive Job Seeker Registration

Job seeker registration portal and SMS communication consent form for Revive Software Systems.

## Features

- **Candidate Registration:** Collects candidate contact information, job title/role of interest, and preferred location.
- **SMS Communication Consent:** TCPA-compliant optional SMS consent checkbox with disclosures, opt-out instructions, and links to Terms & Privacy Policy.
- **Static Web Ready:** Standalone HTML/CSS/JS page ready to host on any static hosting platform or web server.

## Project Structure

```
.
├── .gitignore           # Git ignore rules
├── README.md            # Project documentation
└── public/              # Web root
    └── index.html       # Registration page
```

## Local Development

You can preview the site locally using any static file server:

```bash
# Using Python
python3 -m http.server 8000 --directory public
```

Then visit `http://localhost:8000`.

## Deployment

Deploy the `public/` directory (or contents) to any static web hosting provider (e.g., GitHub Pages, Cloudflare Pages, Netlify, Vercel, AWS S3, or Nginx/Apache).

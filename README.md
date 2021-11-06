# Intro:
The problem occur when you try running localhost with port else than 80, ex: 3000.

## Step:
1. Install Custom SSL Certificate
2. Import .cert to your browser (chrome/firefox/explorer)

### Install Custom SSl Certificate
- Copy localhost-cert.js
- Windows: Open bash / cmd (must install openssl)
- Paste and enter
- Add Cert manual on your browser

### Import .cert to Chrome:
- Go to Settings / chrome://settings/security
- Click Manage Certificates
- Trusted Root Certification Authorities
- Import your .cert
- Restart Browser

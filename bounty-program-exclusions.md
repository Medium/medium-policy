# Exclusions from bug bounty eligibility :/

- Self-XSS.
- Login/logout CSRF.
- CSRF configuration issue without exploitable proof of concept.
- Missing security headers which do not lead directly to a vulnerability.
- Vulnerabilities in third party components in use at Medium, depending on severity and exploitability. For instance, we try to keep up to date with OpenSSL versions but not all security issues impact Medium’s configuration.
- Bugs that require unlikely user interaction or phishing.
- Newly acquired companies are subject to a blackout period to allow us to review and get everything up to speed. Acquisitions coming out of the blackout period will be added to the scoping list once they are in-scope. Bugs reported sooner than that will typically not qualify for a reward.
- Rate Limit on emails sent during sign-up, sign-in, and change email confirmations.
- Previous email login links not invalidated in the event multiple login links are requested. All links expire in 15 minutes.
- Not signed out of Android native app when signing out of all other sessions from the web. We provide a read-only experience to the user, and prevent the ability to post, recommend, respond, highlight, and access to drafts, bookmarks, history and settings.
- Using an email spoofing tool to send an email spoofed as sent from a medium.com domain (ex. security@medium.com) sends an email but is marked as Spam, as opposed to the email not being sent at all.
- Logging-in to medium.com in several browsers/tabs, or logging-in and logging-out repeatedly, thereby creating a large number of user sessions.

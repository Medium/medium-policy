# Medium’s Bug Bounty Disclosure Program

The software security research community makes the web a better, safer place. We support their bug-hunting efforts with a bounty program.

To report a vulnerability, please email us at [security@medium.com](mailto:security@medium.com).

See others who have made responsible disclosures [here](https://medium.com/humans.txt).

## Qualifying Vulnerabilities

The following domains and apps are within the scope of the program:

- *.medium.com
- *.embed.ly
- *.embedly.com
- *.superfeedr.com
- Medium for iOS
- Medium for Android
- Medium Custom Domains (excluding any subdomains or related domains that are not hosted by Medium).

To be eligible, you must demonstrate a security compromise on any of these domains using a reproducible exploit, including the following:

- Cross-site scripting exploits
- Cross-site request forgery exploits
- Authentication or authorization flaws
- Official Medium mobile apps or API flaws
- Server-side code execution bugs
- Injection flaws
- Significant security misconfigurations
- Recommendation and ranking systems

[These vulnerabilities](./bounty-programs-exclusions.md) do not qualify for the bounty program.

## Rules for You

- Don’t make the bug public before it has been fixed.
- Don’t attempt to gain access to another user’s account or data. Use your own test accounts for cross-account testing.
- Don’t perform any attack that could harm the reliability/integrity of our services or data. DDoS/spam attacks are not allowed.
- Only test for vulnerabilities on sites or apps you know are operated by Medium. Some sites hosted on subdomains of medium.com are operated by third parties and should not be tested.
- Do not impact other users with your testing, this includes testing for vulnerabilities in accounts you do not own. We may suspend your Medium account and ban your IP address if you do so.
- Don’t use scanners or automated tools to find vulnerabilities. They’re noisy and we may suspend your Medium account and ban your IP address.
- No non-technical attacks such as social engineering, phishing, or physical attacks against our employees, users, or infrastructure.
- The more thorough the proof-of-concept, the higher the chance a payout will be awarded.
- When in doubt, [email us](mailto:security@medium.com).

## Rules for Us

- We will respond as quickly as possible to your submission.
- We will keep you updated as we work to fix the bug you submitted.
- We will not take legal action against you if you play by the rules and act in good faith.

## Rewards

Based on severity of the bug and completeness of the submission, which we will decide at our sole discretion, we offer the following rewards:

- Remote code execution: $1500
- Unrestricted access to file systems or databases: $1000
- Bugs leaking or bypassing significant security controls: $1000
- Bugs allowing artificial manipulation of ranking and recommendation systems: $250
- Execute code on the client, including XSS: $100
- Open redirect: $100
- Other valid security vulnerabilities: schwag and recognition on [humans.txt](https://medium.com/humans.txt).
- Vulnerabilities to auxiliary services or 3rd party dependencies: schwag and recognition.

## Legal things and final notes

We deal only with principals, not vulnerability brokers.

If you reside in a country on a United States restricted export control list, or are on a United States state or federal criminal wanted list or restricted export control list, you are not eligible to participate in this program.

We will make the final decision on bug eligibility and value. This program exists entirely at our discretion and may be modified or canceled at any time. Any changes we make to these programs terms do not apply retroactively. Thanks for helping us make Medium more secure.

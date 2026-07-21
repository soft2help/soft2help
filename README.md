## Soft2Help

I build custom software and set up **private AI** for companies that would rather
not hand their documents to someone else's cloud. Models run on infrastructure I
manage, so the data stays where it belongs.

[soft2help.net](https://soft2help.net)

### What's here

Small, self-contained tools that came out of real work. Nothing is a demo for its
own sake: if it is here, it is because I needed it and it kept being useful.

| | |
|---|---|
| [start-stop-ec2-rds-machines](https://github.com/soft2help/start-stop-ec2-rds-machines) | Schedule EC2/RDS start-stop. The boring script that quietly cuts an AWS bill |
| [update-securitygroups-route53-domain](https://github.com/soft2help/update-securitygroups-route53-domain) | Keep Route53 records and security groups in sync with a dynamic public IP |
| [powershell-profile](https://github.com/soft2help/powershell-profile) | Modular PowerShell profile. Setting up a new machine should take minutes |
| [onframer-js](https://github.com/soft2help/onframer-js) | JS SDK for embedding and driving OnFramer from a web app |
| [capture](https://github.com/soft2help/capture) | Image capture and perspective correction from IP cameras |

### Coming next

Publishing the pieces behind what I actually run in production:

- Secret management for deploys — pull from Bitwarden, cache with TTL, detect drift
- Critical CSS + purge pipeline — cut one site's CSS by 59% and its FCP by half
- PII gatekeeper — strip personal data before it reaches a cloud model

### Writing

I write up the reasoning behind this kind of work at
[soft2help.net/blog](https://soft2help.net/blog) — in Spanish, mostly about
document management, private AI and not over-engineering things.

Reach me at **info@soft2help.net**.

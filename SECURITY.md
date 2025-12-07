# Interguess Open Source Security Policy

This security policy applies to all open source projects operated by Interguess. We may also be the point of contact for other issues. Further information on this can be found in the next section.

# Get in touch with us

Although Interguess Information Security serves as the point of contact for all IT security-related reports within Interguess, we kindly ask you to first find the direct point of contact for the respective project in our [organizational overview](https://docs.google.com/document/d/1Y8CmVZXLHYyDaXSd1zjf0zkNycGX92pVxekedAHoFmA/edit?tab=t.0#heading=h.3c0i4zb0jm9l) and contact them to obtain information about any existing bug bounty programs.

**If you do not know who to contact, please ALWAYS contact us.**

Our standard method of contact is by email. Please contact us at security@interguess.de.

## Encrypted communication via email
If desired, you can use our public key to send us encrypted information about security risks.
```pem
-----BEGIN PGP PUBLIC KEY BLOCK-----
xsFNBGk17nEBEADLZvGu0elAiGzFil830gsra82eGIXKpgdK/CwsaUnxfARASBwP
AqgG+namumvq/dV62lvbE+3v+PCjMOAKrjvrL7G5xn34gr//vvd+UMMmYTsQtF8Q
xrSV0FZQrkLGMJo6N52Ji8UKS9bxWeWTYroRzBSHIX/niYUgwiGTwTGheXi6/B/E
oWqd2XFsaq+hTrnZD+9gWVl2K5MskNf1AAz1cV3nOzNsOBG/08EWKbP/QDQG0+bl
bUu0o2T/7GHt6gwhiZR7zcdhPTSl7hE8n7E5OIftgdXLuX74YFKMf3GYHKDmFifk
G6xhmZueoIJ7NQTpIN41UZEVOOqXpFXFjslzwzNsPHyX8q02c8lRVCISQRGUlS9F
/dwWzUBTw5exE7kYa2c3HRREXeQ/vnQYxdfzEh5fwBEg7OCEfk7JewNO/sbiDQ2r
PlkzPakEP0NhBYU5piVBo8JC2nrVyS5HDCkIQhXTh2DwqTPlW89vTaXOPEVOqnmu
V0eCnXA6YypGZx8sg2VJNZavHfkQMqPABKKiMrywbP6hKlrIPJ6kSFkQ6QHrwz7R
AaWdB7vWy0hdgC2RPORc7tOx/9C5IcpmV6z7dDoZrvb+TezvDjt/N2JfM5S/mFrz
YWclPNqcJNFC7InXljzI9Y+WMlqUdFlJxvC8YXr6Gfe5AAostFsTuKmC8wARAQAB
zTpJbnRlcmd1ZXNzIEluZm9ybWF0aW9uc3NpY2hlcmhlaXQgPHNlY3VyaXR5QGlu
dGVyZ3Vlc3MuZGU+wsGIBBMBCAAyBQJpNe5xAhsGBQkB4TOAAgsJAhUIAhYCAh4B
FiEEgTC58lo0f0gZIc3DFG2ztXN2ZhgACgkQFG2ztXN2ZhgMZxAAqOsJK+xSGJKl
prVvldIf4kvAKKyeVDivFig+HnhrDaoeRgy3rIlXseDysE/jSTYPWXngeWkn0rv2
O9cuDnJxvmUIjPEcGRSh59uFTM25VPYTfCL2gdGD/KiYEAiim2uQNeP8zS65imif
2sto6+NDDpI/P/eBiiUmpovdAIiIfP+cwSLKEW9lLyOOFTGlG0EWFQ0UFOm6TGAK
GadNswESRkZEWpzxfQA0fceyZ6dsdqm3dV7pQB2Pmff4xcsYX7nNhoiJkrASJTtj
XDB6Fk8mQ4axTmVUytQxjmFOyOB9qAbtG9AdrmUiPnro7HU8NgZcXyD9nVI7yC+a
ARm6k8P/d1uDzJYVBslvtXEdGo+tqs2WuAUA+TQ1kuuHyocrzUAdSJkQj4n64r6N
Z09f33lE0LRA+Y0Zm0fZMLoNoZpjZ2p4HJfBzuJ4qMC8dMuXrRxNx5oYs0wEe8kh
9lPQceZaw6mAoLX4dQgpW6k1PMSn5mKCBLJJouy0lMgKGDouA4eqJkA/iHkrxUIR
zu+FcLDpIEBziwMu4GyfYPCOrNlkYVUB50wuT0ua4qZX0TcAYOsfQEic34gW+ru7
m+1dV5bLSGI5xwWyJdNTKbqaGAyr+KNYJqpDPwC6Uw4M80m/4IvvfK9zn97+DY+P
ujWvpW6Nb7cJPr5ekX3LX4otGWqd+pQ=
=kKF6
-----END PGP PUBLIC KEY BLOCK-----
```

Fingerprint: `8130B9F25A347F481921CDC3146DB3B573766618`

Expires: `07.12.2026`

## Response time

You’ll usually get a confirmation within **2 business days**. We prioritize critical issues immediately and aim to address valid reports as quickly as possible.
Clear reproduction steps and impact descriptions help us respond faster.
Rewards may be available for eligible reports.

Thanks for supporting a secure experience for all users.

## Disclosure Process
- External security researchers can submit vulnerabilities via the published security contact. Each report is logged and forwarded to the security team, which acknowledges receipt and assigns an internal reference number without assessing validity.
- During triage, the team checks reproducibility, affected products or versions, and scope. Out-of-scope or non-reproducible reports are rejected and the reporter is informed. Valid reports move on to technical validation; additional information is requested if needed.
- If the issue meets the CNA’s scope and criteria, the CNA coordinator reserves or assigns a CVE ID. The security team then works with engineering or product teams to develop a fix or a reliable mitigation and determine which versions are affected. The vulnerability is not published until a fix or mitigation is ready. If no fix is possible, this is stated transparently.
- The publication includes the CVE ID, a description, affected versions, and—if permitted—the reporter’s name. All triage decisions, communication, and publication details are archived internally afterward.

## CVE Assignment Policy & Publication Commitment
Interguess Information Security publishes a CVE record for every reported and confirmed security vulnerability that falls within our scope and is verifiably qualified as a CVE. At the request of the reporter, they will also be named as the reporter of the security vulnerability in this CVE record.

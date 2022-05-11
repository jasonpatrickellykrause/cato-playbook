# Policy

- Critical and high severity vulnerabilities detected via Static Analysis Security Testing (SAST) must be mitigated 
prior to deployment into both staging and production environments. Detection and enforcement is **automated** via the
[Secure Release Pipeline]((https://github.com/department-of-veterans-affairs/lighthouse-tornado)).
- Critical and high severity vulnerabilities detected via Software Composition Analysis (SCA) must be mitigated prior to
deployment into both staging and production environments. Detection and enforcement is **automated** via the
[Secure Release Pipeline]((https://github.com/department-of-veterans-affairs/lighthouse-tornado)).
- Critical and high severity vulnerabilities detected via Container Security Analysis must be mitigated prior to 
deployment into both staging and production environments. Additionally, containers must not be run as the root user and 
must pass a maleware scan. Detection and enforcement is **automated** via the
[Secure Release Pipeline]((https://github.com/department-of-veterans-affairs/lighthouse-tornado)).
- Critical and high severity vulnerabilities in production are remediated or mitigated within 3 business days of 
discovery. 
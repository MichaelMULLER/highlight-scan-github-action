# highlight-scan-github-action
This repo contains a sample Github Action for running CAST Highlight scans on repositories. CAST Highlight offers automated source code analysis of hundreds of applications in a week for Cloud Readiness, Open Source risks, Resiliency, Agility. Objective software insights combined with qualitative surveys for business context.


# Prerequisites:
- Valid CAST Highlight user account, company and application IDs to upload the results to in `hl.env'.
- Define a GitHub Action environment with a secret CAST_HIGHLIGHT_API_TOKEN for the Highlight API/CLI token.

For more info on how to enable CAST Highlight API/CLI tokens, see this page: https://doc.casthighlight.com/feature-focus-api-cli-user-token-management/

For more info about CAST Highlight and Software Intelligence: https://www.castsoftware.com/products/highlight/

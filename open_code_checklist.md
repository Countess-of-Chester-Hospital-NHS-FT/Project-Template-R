# Open Code Checklist
This checklist is adapted from the [NHSE Repo Template](https://github.com/nhsengland/nhse-repository-template/blob/main/OPEN_CODE_CHECKLIST.md)
Please use this checklist to document adherence to best practice for published projects.

## When publishing your code you need to make sure:
  
### you’re clear about who owns the code and how others can use it

- [ ] Does your code have an appropriate licence and copyright notice?
- [ ] Is there a clear and concise README and does it document intended purpose?
- [ ] Could the output of this project be considered a medical device according to MHRA 'software as a medical device' regulation? (use [flowchart](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/999908/Software_flow_chart_Ed_1-08b-IVD.pdf))
- [ ] Are package dependencies and libaries documented with versions?

### You do not release information that should remain closed (in either source code, commits, discussions, outputs or documentation, now or at any time in the git history)

- [ ] The repo does not include any sensitive, personal, secret or top secret data/information? 
- [ ] The repo does not include any unreleased policy? 
- [ ] The repo does not include business sensitive algorithms (e.g. finance allocations)? 
- [ ] The repo does not include any credentials, keys or passwords?
- [ ] The repo does not include any SQL server addresses or connection strings in the source code? 
- [ ] The repo does not include notebooks, or the strategy for removing outputs from notebooks is detailed in the README (e.g using nbstripout).
- [ ] Is configuration written as code and separated from analytical code? 
- [ ] have you checked any screenshots or figures in your outputs and documentation for information that shouldn't be released? 

### Any third-party tools you use to host or manage your code follow the National Cyber Security Centre’s cloud security guidance

- [ ] Are third party tools used within the code (apart from GitHub or PyPI)? 
- [ ] If so do they adhere to the NCSC's [Cloud Security Principles](https://www.ncsc.gov.uk/collection/cloud-security/implementing-the-cloud-security-principles)? 

### An internal code review has been completed

- [ ] Has the code been reviewed for sensitive data content and security vulnerabilities?
- [ ] Has a code quality review been completed focussing on the end usability and clarity?

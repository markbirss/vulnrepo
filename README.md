<div align="center"><img src="/src/assets/logo/vulnrepo_logo.png" width="300"></div>

# VULNRΞPO - Vulnerability Report Generator & Repository

Check online: https://vulnrepo.com/

Video walkthrough/Tutorial:  
[![Guide](https://img.youtube.com/vi/k32Oo57ZQdY/0.jpg)](https://www.youtube.com/watch?v=k32Oo57ZQdY)

## Features

 - Security
    - Project use browser for encrypt/decrypt (AES) and store data in locally. Full confidentiality of data, end-to-end encryption, by default nothing is sent out. No backend system, only front-end technology, pure JS client.
 - Use custom issues templates!
    - The use of templates greatly speeds up the work for pentester or security auditor. Import CVE, CWE, MITRE ATT&CK or PCI DSS data also possible.
 - Import issues from security scanners
    - Supported import from: Nmap, Nessus, Burp, OpenVAS. After importing, easily manage and edit vulnerabilities.
 - TXT & HTML & PDF
    - You can download report in TXT, HTML formats!. If you need PDF just 'print as PDF' html report.
 - Attachments
    - You can easly attach any file you want to. Screenshot, movie or scanner output in txt. Automatically doing checksum sha256 of attached file.
 - Changelog
    - All important changes in report will be logged in to changelog and update to the next version of the report.
 - Export Issues
    - You can export issues to popular bugtrackers like Atlassian JIRA or use secure way to share only issues.
 - Share report
    - You can share your report using AES encryption by default.
 - API Integration
    - Build your own backend system to store reports!

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-c production` flag for a production build.

## DEV Environment

You can test our latest changes from dev branch, visit: https://dev.vulnrepo.com/

## Lgtm

[![Total alerts](https://img.shields.io/lgtm/alerts/g/kac89/vulnrepo.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/kac89/vulnrepo/alerts/)
[![Language grade: JavaScript](https://img.shields.io/lgtm/grade/javascript/g/kac89/vulnrepo.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/kac89/vulnrepo/context:javascript)

## Licencing

VULNRΞPO is released under the [Apache 2.0 Licence](https://www.apache.org/licenses/LICENSE-2.0)
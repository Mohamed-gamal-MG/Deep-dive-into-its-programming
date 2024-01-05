# html file to exploit the vulnerability Subdomain takeovers
> What is a security vulnerability and how can one exploit it?
## The best explanation for the security vulnerability [open link](https://github.com/EdOverflow/can-i-take-over-xyz).
## My way of finding a Subdomain takeovers

![Screenshot_1](https://github.com/Mohamed-gamal-MG/Deep-dive-into-its-programming/assets/155613024/0a9e0ce6-5b41-4020-8623-52e7e1603181)

### 1- Enumerate all the subdomains using subfiner, asset finder, amass ....
### 2- asset finder, amass | tee ALL-sub-domains.txt
### 3- nuclei –l livesubdomains.txt -t /nuclei-templates-directory/subdomain-takeover

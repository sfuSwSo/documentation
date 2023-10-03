---
sidebar_position: 1
---

# Overview

Docusaurus is open-source software developed by Facebook. Our club utilizes Docusaurus for internal documentation for developers working on our ongoing projects and for future contributions.

There are two repositories for our documentation:

**Docusaurus repository**  
https://github.com/sfuSwSo/docusaurus.   

**Documentation source repository**  
https://github.com/sfuSwSo/documentation. 

The first repository is a forked version of Docusaurus from Facebook, containing all the configuration and deployment settings for our Docusaurus instance.

The second repository contains the actual markdown files used to display documentation pages. When our Docusaurus is scheduled for deployment or updates, it first syncs the markdown files from this repository. Therefore, any changes made to this repository will be reflected in the hosted Docusaurus instance.

For security reasons, any PRs or commits made to the Docusaurus repository must be supervised by users with admin roles. To add a new document to Docusaurus, you don't need to make a change on the Docusaurus repository; instead, you are going to make a PR of markdown files to the documentation source repository.

## Getting Started

For developers and designers,

1. [Deploy Local Site](deploy-local-site)

2. [Create a Document](create-a-document)

3. [Extra features](extra-features)

For project leads,

4. [Create a Project](create-a-project)
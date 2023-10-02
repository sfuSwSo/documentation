---
sidebar_position: 3
---

# Deploy Local Site

In case you want to check the rendering of your changes on markdown files immediately, rather than waiting to be reflected on our Docusaurus hosting instance, you can set up your local Docusaurus website.

Clone the Docusaurus repository with the following command:
`git clone https://github.com/sfuSwSo/docusaurus.git`  

Then navigate to our documentation website directory using the command:  
`cd project-documentation`  

Build your local site with the following command. This will automatically sync with the documentation source repository:

```bash
npm run build
```

To test your local website, use the following command:

```bash
npm run serve
```

The `project-documentation/build` folder is now served at [http://localhost:3000/](http://localhost:3000/).


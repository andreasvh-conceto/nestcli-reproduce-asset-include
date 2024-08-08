## Description
reproduces the issue in nestcli to include files only in the outdir as expected if watchAssets is true

## Installation

```bash
$ npm install
```

## how to reproduce

```bash
# build 
$ npm run build
# look inside dist directory some excpected files according to nest-cli.json are not in the expected directories

# go inside nest-cli.json and set the watchAssets: true
npm run build
# go again inside dist directory. Files are located as expected accoring to nest-cli.json

```

# CodeYourFuture Wiki

This is the CYF Wiki portal contains useful information for students and mentors.

## Getting started

Start up a local server

```
cd website
npm install
npm start
```

## Deployment

Deploy to https://codeyourfuture.github.io/wiki/

```
cd website
npm install
GIT_USER=ChrisOwen101 CURRENT_BRANCH=master USE_SSH=true npm run publish-gh-pages
```
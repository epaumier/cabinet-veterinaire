# Eleventy Website for a veterinary's office

## Tai11s - the Eleventy + Tailwind CSS starter

## Credit
This is a fork of a starter repo originally created by [Ian Rose](https://github.com/ianrose/deventy/).

### How to use in development

```
$ npm run dev
```
 And in debug mode:
 
```
$ npm run dev:debug
```

You can view the rendered site at the given access URL served up by light-server:
```
$ light-server is listening at http://localhost:4000
```

The local url is configured in `.lightserverrc`

### To build ready for production

```
npm run build
```

## BONUS: Travis Github Pages deployment script

`.travis.yml` can be modified to suit your own needs. This simple script will build from a named branch and deploy to Github Pages via your [Travis CI](https://travis-ci.org/) account. 

Store your Github Token securely in the Travis control panel

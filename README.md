Bootstrap web application

## Deploy
On merge to main, Github actions deploy `src` directory to website.
Assumes webpack done it's job generating `scripts/main.js`

## Set up
* `bootstrap` directory is from npm install and pulled from node modules. Will need to revisit build process if need to upgrade bootstrap

## Dependencies
* Google Form for contact
* Github account with Github pages set up against repo
* Deploy from gh-pages branch

## Run locally
1. Build files required with 
`npm install`
`npx webpack --config webpack.config.js`

2. Run with `npm start`
Go to http://localhost:8080

## TODO
- [ ] Maybe look at Jekyll
- [ ] Get github actions to do the webpack script generation on deploy

```

```
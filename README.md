Bootstrap web application

## Dependencies
* Google Form for contact
* Github account with Github pages set up against repo
* Deploy from gh-pages branch

## Set up
Build files required with 
```
npm install
npx webpack --config webpack.config.js
```
## Deploy
On merge to main, Github actions deploy `src` directory to website.
Assumes webpack done it's job generating `scripts/main.js`

## Run locally
Run with `npm start`
Go to http://localhost:8080

## TODO
- [ ] Maybe look at Jekyll
- [ ] Get github actions to do the webpack script generation on deploy

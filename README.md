# OctoBay Website

## Build Setup

Create a `.env` file:

```
API_URL=http://localhost:3000/api
GITHUB_CLIENT_ID=...
GITHUB_CLIENT_SECRET=...
GITHUB_APP_ACCESS_TOKEN=...
OCTOBAY_ADDRESS=...
ETH_NODE=ws://localhost:9545
ORACLE_ADDRESS=...
ORACLE_GAS_REGISTRATION=35000
ORACLE_GAS_CLAIMPR=53000
ORACLE_GAS_RELEASEISSUE=35000
MAX_CLAIMPR_AGE=180
TWITTER_API_KEY=...
TWITTER_API_SECRET=...
TWITTER_APP_ACCESS_TOKEN=...
TWITTER_APP_SECRET=...
TWITTER_APP_BEARER_TOKEN=...
```

```bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production and launch server
$ yarn build
$ yarn start
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).

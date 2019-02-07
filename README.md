# bch-email-frontend
The repository is the Gatsby front end for a BCH-based email server.
[The back end](https://github.com/Permissionless-Software-Foundation/bch-email-api)
provides an API to interact with an [iRedMail](https://iredmail.com/download.html)
email server.

The goal of this project is to create an easy-to-setup email server that allows
permissionless account creation using BCH or tokens. Cost-per-email is configurable,
but will default to $3 USD for 300 emails (to _and_ from)

This front end was originally forked from
the [gatsby-login](https://github.com/Permissionless-Software-Foundation/gatsby-login) boilerplate.

## Installation and Usage
- Install [iRedMail](https://iredmail.com/download.html) on a Digital Ocean Droplet or equivalent VPS.
- Install and run the [bch-email-api](https://github.com/Permissionless-Software-Foundation/bch-email-api) back end.
- Clone this repository `git clone https://github.com/Permissionless-Software-Foundation/bch-email-frontend`
- Install dependencies: `npm install`
- Run development server: `npm run develop`

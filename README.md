# Chemalot
Chemalot workspace

## Pre-requisites:
- Setup SSH keys and register to Github. [Instructions](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
- nodejs v16, use [NVM](https://www.freecodecamp.org/news/nvm-for-windows-how-to-download-and-install-node-version-manager-in-windows-10/) to manage multiple versions of nodejs


## Tech stack used 
- Web - [Nextjs](https://nextjs.org/), tailwind
- Rest API - [nestjs](https://nestjs.com)

## Steps to start the app

- `yarn install`
- `yarn dev:api` - Starts REST API
- In a new terminal `yarn dev:shop` - Starts web application
- Load http://localhost:3003/ in browser

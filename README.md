# ADAM TODOS

* Feature planning page?
* Help links from production sites
* Add feature - set time zones for accounts / time zone standard for tenants
* Finish research on Users page features
* Tweak email notifications to use the time zone of the sending account, or at least specify the time is UTC.
* Add request relationship button - partner center REST API has an endpoint
* https://docs.microsoft.com/en-us/partner-center/develop/verify-domain-availability

# Website

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

## Installation

```sh
yarn
```

## Local Development

```sh
yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

## Build

```sh
yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## Deployment

Using SSH:

```sh
USE_SSH=true yarn deploy
```

Not using SSH:

```sh
GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.

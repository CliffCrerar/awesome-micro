# Awesome Micro [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<a href="https://github.com/zeit/micro"><img align="right" src="https://camo.githubusercontent.com/67335088cb7b156fb779f6d60635e70780efe714/68747470733a2f2f636c6475702e636f6d2f4a446d6d4858337568462e737667" /></a>

A collection of awesome things regarding ZEIT's [Micro](https://github.com/zeit/micro) — Asynchronous HTTP microservices.

## Modules

- Routing
  - [router](https://github.com/pillarjs/router) - Simple middleware-style router.
  - [fs-router](https://github.com/jesseditson/fs-router) - Use the FS as your micro router.
  - [micro-route](https://github.com/dotcypress/micro-route) - Tiny http routing helper.
  - [micro-router](https://github.com/pedronauck/micro-router) - A tiny and functional router for Zeit's Micro.
  - [micro-method-router](https://github.com/jamo/micro-method-router) - Minimal routing layer for HTTP methods.
  - [micro-ex-router](https://github.com/Masquerade-Circus/micro-ex-router) - Express style router for Zeit's Micro.
  - [micro-action](https://github.com/zhaoyao91/micro-action) - Define actions for Zeit's Micro using micro-action protocol.
  - [micro-http-router](https://github.com/protocol114/micro-http-router) - Express-like router built with a radix tree for lightning-fast performance.
  - [micro-fork](https://github.com/amio/micro-fork) - A fast and functional router for ZEIT's Micro.
  - [@synvox/router](https://github.com/Synvox/router) - A tiny routing library inspired by react hooks and express.js.
- [micro-mw](https://github.com/mhamann/micro-mw) - A simple library for abstracting middleware away from ZEIT Micro routes / functions.
- [microauth](https://github.com/microauth) - Collection of authentication modules for ▲zeit's micro.
  - [microauth-twitter](https://github.com/microauth/microauth-twitter) | [microauth-facebook](https://github.com/microauth/microauth-facebook) | [microauth-github](https://github.com/microauth/microauth-github) | [microauth-slack](https://github.com/microauth/microauth-slack) | [microauth-google](https://github.com/microauth/microauth-google)
- [micro-compress](https://github.com/joakimbeng/micro-compress) - Compression for HTTP microservices.
- [micro-cors](https://github.com/possibilities/micro-cors) - Simple CORS middleware.
- [micro-ajv](https://github.com/igat64/micro-ajv) - An Ajv (Another JSON Schema Validator) middleware for Micro.
- [micro-boom](https://github.com/onbjerg/micro-boom) - Wraps errors in micro with Boom.
- [micro-analytics](https://github.com/mxstbr/micro-analytics) - Public analytics as a Node.js microservice, no sysadmin experience required.
- [micro-stats](https://github.com/dotcypress/micro-stats) - Statsd helper for Micro.
- [micro-visualize](https://github.com/onbjerg/micro-visualize) - Development tool that visualizes requests and responses for services written with Micro.
- [micro-chain](https://github.com/dimapaloskin/micro-chain) - Builds flexible requests chains and pass them into micro handler.
- [micro-cookie-session](https://github.com/billymoon/micro-cookie-session) - Simple cookie-based session storage for micro.
- [micro-ratelimit](https://github.com/dotcypress/micro-ratelimit) - Rate limiting middleware for Micro.
- [micro-get](https://github.com/romuloalves/micro-get) - Only accepts GET request for microservices built with Micro.
- [micro-post](https://github.com/romuloalves/micro-post) - Only accepts POST request for microservices built with Micro.
- [micro-jwt-auth](https://github.com/kandros/micro-jwt-auth) - Json web token(jwt) authorization wrapper for Micro.
- [micro-redirect](https://github.com/timReynolds/micro-redirect) - A redirect function for Zeit's micro.
- [micro-joi](https://github.com/stearm/micro-joi) - Joi wrapper for Micro.
- [micro-upload](https://github.com/julianduque/micro-upload) - A express-fileupload wrapper for Zeit's micro.
- [micro-hoofs](https://github.com/KaleoSoftware/micro-hoofs) - Higher-order functions for zeit/micro.
- [micro-compose](https://github.com/microauth/micro-compose) - Hight-order "compose" function.
- [micro-query](https://github.com/nerdify/micro-query) - Simple querystring parser for Zeit's Micro.
- [micro-cookie](https://github.com/zakjholt/micro-cookie) - Cookie parsing for Zeit's Micro.
- [micro-sentry](https://github.com/tanmulabs/micro-sentry) - Send micro errors to the Sentry service.
- [micro-match](https://github.com/nblackburn/micro-match) -  A simple url matching utility for micro.
- [micro-superstruct](https://github.com/brandon93s/micro-superstruct) - Superstruct wrapper for Micro enabling validation of request body and query parameters.
- [micro-bunyan-request](https://github.com/maximeshr/micro-bunyan-request) - Request, response logger middleware using bunyan for micro framework.
- [micro-correlation-id](https://github.com/tafarij/micro-correlation-id) - Correlate http requests across microservices.
- [micro-cacheable](https://github.com/fmiras/micro-cacheable) - A micro utility for data caching
- [micro-health](https://github.com/fmiras/micro-health) - An extension of micro with a Health Check API
- [micro-notify](https://github.com/pauldariye/micro-notify) - A simple [.notify](https://github.com/bugsnag/bugsnag-js) wrapper to send micro errors to Bugsnag.
- [micro-logzio](https://github.com/littledumb/micro-logzio) - A middleware for micro framework that logs requests and responses using logz.io service.
- [micronize](https://github.com/nickcis/micronize) - Simple way of enhacing a function with Zeit's Micro framework (usefull for serverless environment, ie: now & aws lambda).
- [micro-morgan](https://github.com/nickcis/micro-morgan) - [Morgan](https://github.com/expressjs/morgan) HTTP request logger middleware for Zeit's Micro framework.
- [serve-handler](https://github.com/zeit/serve-handler) - Static file serving and directory listing handler, used by [Serve](https://github.com/zeit/serve)

## Deployment Tools
- [aws-serverless-micro](https://github.com/nathancahill/aws-serverless-micro) - Deploy Micro functions on AWS Lambda

## Development Tools

- [micro-dev](https://github.com/zeit/micro-dev) - The development environment for `micro`.
- [micro-proxy](https://github.com/zeit/micro-proxy) - Run multiple micro servers and a front proxy at a time.
- [serve-micro-cluster](https://github.com/tylersnyder/serve-micro-cluster) - It's like Path Alias on now, but for local development.
- [dev-gateway](https://github.com/dimapaloskin/dev-gateway) - Local development gateway with [path aliases](https://zeit.co/docs/features/path-aliases) support.
- [instantapi](https://github.com/martinstarman/instantapi) - Local instant development api.

## Boilerplates

- [generator-micro-service](https://github.com/vadimdemedes/generator-micro-service) - Yeoman generator to kick-start your microservice with `micro` and `ava`
- [create-micro](https://github.com/romuloalves/create-micro) - a generator for `micro` projects
- [micro-authentication-starter](https://github.com/littleStudent/micro-authentication-starter) - Starter kit with built in authentication using bcrypt and jsonwebtokens
- [micro-graphql](https://github.com/hyperfuse/micro-graphql) - GraphQL Microservice
- [nuxt-micro](https://github.com/nuxt-community/micro-template) - A [Vue-CLI](https://github.com/vuejs/vue-cli) template to generate a [Nuxt.js](https://github.com/nuxt/nuxt.js) project with micro as a backend

## Articles & FAQ

- [Minimum Viable Async with Node 6](https://gist.github.com/rauchg/8199de60db48026a6670620a1c33b700)
- [Regarding no-middleware](https://github.com/zeit/micro/issues/8)
- [Use Micro with routes](https://github.com/zeit/micro/issues/16#issuecomment-193518395)
- [Difference between Micro and Koa](https://github.com/zeit/micro/issues/309#issuecomment-332503863)

## Built with Micro

- [Serve](https://github.com/zeit/serve) - Static file serving and directory listing
- [micro-github](https://github.com/mxstbr/micro-github) - Add authentication with GitHub to your application
- [micro-figma](https://github.com/jongold/micro-figma) - Add authentication with Figma to your application
- [marked](https://github.com/amio/marked) - Markdown render service
- [font-mess](https://github.com/amio/font-mess) - Obscure text with messed font
- [gh-latest-repos](https://github.com/sindresorhus/gh-latest-repos) - Get the latest public GitHub repos from a user
- [imagemin-micro](https://github.com/imagemin/imagemin-micro) - Minify images
- [Caravaggio](https://gitlab.com/ramiel/caravaggio) - Image manipulation proxy
- [micro-gallery](https://github.com/andreasmcdermott/micro-gallery) - Like zeit's serve, but for images.


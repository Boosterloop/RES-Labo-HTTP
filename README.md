# HTTP Infrastructure Lab

_Authors: Alison Savary, Luc Wachter_

## Step 1: Static Apache httpd server

- A docker image ready to setup a static Apache `httpd` server to serve a simple bootstrap landing page.
- Full documentation in directory `1_httpd-php-static`'s readme: [link](1_httpd-php-static/README.md).

## Step 2: Dynamic express.js server

- A docker image ready to setup a dynamic `express.js` server, built on `Node.js`.
- It serves a random number of witty comments in JSON through HTTP.
- Full documentation in directory `2_express-dynamic`'s readme: [link](2_express-dynamic/README.md).

## Step 3: Reverse proxy with apache (static configuration)

- In directory `3_httpd-reverse-proxy`.

## Step 4: AJAX requests with JQuery

- Wouldn't work without a reverse proxy because of the same-origin policy.
- The website comes from one static server while the dynamic content comes from another.
- This isn't allowed by the browser, but the reverse proxy is a single origin.

## Step 5: Dynamic reverse proxy configuration

# Lupus Decoupled Nuxt.js Demo

A demo setup for testing https://www.drupal.org/project/lupus_decoupled

## Overview

This is simply a new nuxt (v2) project with https://github.com/drunomics/nuxtjs-drupal-ce installed and configured.

## Try it 

[Launch it on StackBlitz ⚡️](https://stackblitz.com/edit/nuxt-starter-wuxxcy?file=README.md) or clone the repo and launch it locally.

When using gitpod/DrupalPod as a backend, make sure to set your environment to "Shared" (via management Dashhboard at https://gitpod.io), such that the frontend can connect to it.

After spinning it up you'll get some network error, until base URLs are set right. To do so:

1. Set the Drupal base URL in `nuxt.config.js` and append the API-prefix /ce-api, e.g. `https://8080-shaal-drupalpod-8m3z0ms7mb6.ws-eu67.gitpod.io/ce-api`
2. Set the frontend base URL in Drupal at `/admin/config/system/lupus-decoupled/settings`, e.g.. `https://nuxt-starter-wuxxcy--3000.local-corp.webcontainer.io`
3. Test it. Best add some content nodes and some menu-items pointing to them. /node/1 of the backend is available under /node/1 in the frontend. You should see some naked frontend with menus, breadcrumbs & basic node-content (body field) working.

## Development

 * Clone the repo
 * Run:
 
      npm install
      npm run dev
      
      
 ## Documentation
 
  Check out the [nuxt docs](https://nuxtjs.org/docs/) to get started, e.g. [Commands and Deployment](https://nuxtjs.org/docs/get-started/commands)

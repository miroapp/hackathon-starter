[<img src="https://raw.githubusercontent.com/miroapp/.github/main/profile/banner.png" alt="Miro Developer Platform" />](https://miro.com/api/)

# Hackathon starter kit

If you have attended hackathons in the past, you know how much time it takes to get a project started. From that first second when you get thinking on what to build, to picking a programming language, and then deciding what framework to use&mdash;it doesn't end there, and the list goes on! That's why this page is here! These resources help you get started with minimal time and effort.

Happy hacking!

## Table of contents

- [Hackathon starter kit](#hackathon-starter-kit)
  - [Table of contents](#table-of-contents)
  - [Miro Developer Platform concepts](#miro-developer-platform-concepts)
  - [Miro Web SDK resources](#miro-web-sdk-resources)
    - [Getting started with the Miro Web SDK](#getting-started-with-the-miro-web-sdk)
    - [Miro Web SDK tutorials](#miro-web-sdk-tutorials)
    - [Miro Web SDK reference guide](#miro-web-sdk-reference-guide)
  - [Miro REST API resources](#miro-rest-api-resources)
    - [Miro REST API client](#miro-rest-api-client)
    - [Getting started with the Miro REST API](#getting-started-with-the-miro-rest-api)
    - [Miro REST API tutorials](#miro-rest-api-tutorials)
    - [Postman collection](#postman-collection)
  - [Miro App Examples](#miro-app-examples)
    - [Web SDK](#web-sdk)
    - [REST API](#rest-api)
    - [Full-stack apps](#full-stack-apps)
  - [Miro CSS library](#miro-css-library)
  - [Support and community](#support-and-community)

## Miro Developer Platform concepts

- New to the Miro Developer Platform? Interested in learning more about platform concepts?<br />
  [Read our introduction page](https://developers.miro.com/docs/introduction) and familiarize yourself with the Miro Developer Platform capabilities in a few minutes.

- Not sure about whether you should use the Miro Web SDK or the REST APIs?<br />
  [Here's a table](https://developers.miro.com/docs/miro-web-sdk-vs-rest-apis) that provides helpful guidelines on Miro Web SDK and REST API usage.

## Miro Web SDK resources

### Getting started with the Miro Web SDK

- [Quickstart (video):](https://developers.miro.com/docs/try-out-the-web-sdk-in-less-than-1-minute) try the Web SDK in less than 1 minute.
- [Quickstart (article):](https://developers.miro.com/docs/try-out-the-web-sdk) get started, try the Web SDK in less than 1 minute, and use the Miro Web SDK in the developer console to get acquainted with its feature set.
- [Build your first Hello World app](https://developers.miro.com/docs/build-your-first-hello-world-app): bootstrap the Hello World app, create a Developer team in Miro, create and configure your app in Miro.

### Miro Web SDK tutorials

Check out our [how-tos and step-by-step tutorials](https://developers.miro.com/docs/web-sdk-how-tos) to walk you through typical use cases when working with the Miro Web SDK.

### Miro Web SDK reference guide

Look up methods, board item properties, and copy-paste code examples from the [Miro Web SDK reference guide](https://developers.miro.com/docs/web-sdk-reference).

## Miro REST API resources

### Miro REST API client

The Miro Node.js client is a JavaScript library that enables Miro REST API functionality in Miro apps based on Node.js. You can use Node.js and JavaScript to send requests to and handle responses from the Miro REST API. Here are some resources that might come handy:

- [Miro NodeJs Client library doc](https://developers.miro.com/docs/miro-nodejs-readme)
- [Quickstart for task automation](https://developers.miro.com/docs/miro-nodejs-quickstart): a simple quick start guide to get up and running.
- [Quickstart with OAuth and Express](https://developers.miro.com/docs/miro-nodejs-quickstart-with-oauth-and-express): a quick start guide to build a Node.js app with OAuth 2.0 authentication and a web server based on the Express web framework.
- [Implement storage for data persistence](https://developers.miro.com/docs/miro-nodejs-implement-storage-for-data-persistence): implement data storage in a Node.js app.
- [Reference documentation](https://miroapp.github.io/api-clients/index.html): look up methods, interfaces, and properties.

### Getting started with the Miro REST API

- [Quickstart (video):](https://developers.miro.com/docs/try-out-the-rest-api-in-less-than-3-minutes) try the REST API in less than 3 minutes.
- [Quickstart (article):](https://developers.miro.com/docs/build-your-first-hello-world-app-1) get started and try the REST API in less than 3 minutes.

### Miro REST API tutorials

Check out our [how-tos and step-by-step tutorials](https://developers.miro.com/docs/rest-api-how-tos) to walk you through typical use cases when working with the Miro REST API.

### Postman collection

[![Run in Postman](https://run.pstmn.io/button.svg)](https://www.postman.com/miro-developer-platform/workspace/miro-developer-platform/documentation/20467754-1a7d3514-f19f-4a86-9001-d694f160da3d)

## Miro App Examples

Clone our [Miro App Examples repository](https://github.com/miroapp/app-examples) to get inspiration, customize, and explore apps built on top of Miro's Developer Platform 2.0.

### Miro Web SDK

| App Example                                             | Description                                                                                                                                        |
| ------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| [csv-to-mindmap](examples/csv-to-mindmap)               | Import data from CSV and create mind map on a Miro board                                                                                           |
| [drag-and-drop](examples/drag-and-drop)                 | This example shows you how to drag and drop images from your app onto the board.                                                                   |
| [asset-search](examples/asset-search)                   | This example shows you how to filter and search through assets by name and/or multiple tags.                                                       |
| [digital-asset-manager](examples/digital-asset-manager) | This example shows you how to build a digital asset manager using Bynder's API.                                                                    |
| [connect-firebase](examples/connect-firebase)           | This example shows you how to connect an SDK app to a Firebase backend.                                                                            |
| [stickynotes-to-shapes](examples/stickynotes-to-shapes) | This example allows you to select several stickies, click the plugin button in the bottom bar, and replace any selected stickies with shapes.      |
| [template-builder](examples/template-builder)           | This example shows how to create and position on the board multiple widgets of different types and render create custom interfaces in the library. |
| [calendar](examples/calendar)                           | This example shows you how to add a calendar made with shapes and text for a given month and year.                                                 |
| [wordle](examples/wordle)                               | This example shows you how to create a Wordle-like game using the Miro Web SDK.                                                                    |
| [blob-maker](examples/blob-maker)                       | This example shows you how to create a drag and drop blobmaker using Miro's Web SDK.                                                               |
| [youtube-room](examples/youtube-room)                   | This example shows you how to sync a YouTube player across multiple users through Socket.IO.                                                       |
| [custom-actions](examples/custom-actions)               | This example shows you how register [custom actions](https://developers.miro.com/docs/add-custom-actions-to-your-app) in the item context menu.    |

<p>&nbsp;</p>

### REST APIs

| App Example                                                       | Description                                                                                                                                                                                                                                                                                                     |
| ----------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [python-oauth](examples/python-oauth)                             | This Python sample demonstrates how to implement the Oauth 2.0 authorization code flow in Miro.                                                                                                                                                                                                                 |
| [node-oauth](examples/node-oauth)                                 | This Node.js sample demonstrates how to implement the Oauth 2.0 authorization code flow in Miro and make an API request to a Miro endpoint.                                                                                                                                                                     |
| [node-passport-oauth](examples/node-passport-oauth)               | This Node.js sample demonstrates how to implement the Oauth 2.0 authorization code flow in Miro and make an API request to a Miro endpoint using [Passport.js](https://www.passportjs.org/).                                                                                                                    |
| [nextjs-oauth](examples/nextjs-oauth)                             | This app demonstrates how to implement the Oauth 2.0 authorization code flow from Miro into a client side application built with Next.js.                                                                                                                                                                       |
| [node-stickies-csv](examples/node-stickies-csv)                   | This Node.js sample app uses server side rendering (Handlebars.js) to provide a lightweight, CRUD-oriented REST example in the browser for Miro's sticky notes and tags APIs.<br />It demonstrates a structured > unstructured use case via CSV import, creating Miro sticky notes with tags based on CSV data. |
| [python-flask-starter](examples/python-flask-starter)             | This Python/Flask boilerplate will allow to start using the Miro REST API in a few minutes.<br />This sample implements the full Miro authorization (OAuth 2.0 with refresh token) flow.                                                                                                                        |
| [python-external-oauth](examples/python-external-oauth)           | This Python/Flask app shows you how to set up an OAuth 2.0 flow with GitHub.<br />This sample allows you to log in with GitHub and post some details to a Miro Board.                                                                                                                                           |
| [enterprise-team-management](examples/enterprise-team-management) | This Node.js sample demonstrates how to manage teams and organizations within Miro using Miro's REST API.<br />ℹ️ _This example requires an Enterprise plan subscription and an [Enterprise Team account](https://miro.com/enterprise/)._                                                                       |

<p>&nbsp;</p>

### Full-stack apps

| App Example                                                   | Description                                                                                                                               |
| ------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| [monetization-with-stripe](examples/monetization-with-stripe) | This full-stack example shows how use Stripe to add a paywall for certain features in your app.                                           |
| [html-preview](examples/html-preview/)                        | Use the Miro API to generate HTML pages from Miro boards. Each frame on the board produces an HTML page.                                  |
| [github-appcards](examples/github-appcards)                   | This full-stack example shows how to build an integration with GitHub that syncs data between GitHub issues and Miro app cards.           |
| [plant-uml](https://github.com/miroapp/miro-plantuml)         | This full-stack example shows how to import [Plant UML](https://plantuml.com/) diagrams into Miro as editable board items.                |
| [nextjs](examples/nextjs-full-stack)                          | This full-stack example shows a Next.js application that uploads a camera image to the Miro board using Web SDK and REST API integration. |
| [webhooks-manager](examples/webhooks-manager/)                | This full-stack example demonstrates how to interact with the webhooks API, and how to handle the webhooks challenge.                     |

<p>&nbsp;</p>

## Miro CSS library

[Mirotone](https://www.mirotone.xyz/css) is a CSS library that enables everyone to design and build their Miro apps. The goal of this design system is to enable makers to quickly jump into a simple, yet consistent and efficient user experience while creating their functional solutions. The framework aims to provide ready-to-use frontend components that you can incorporate into your app in Miro.

<p>&nbsp;</p>

## Support and community

- Stuck somewhere? Encountered any blockers or errors? Need assistance? We're here to help you! Ask your question on our [developer community forum](https://community.miro.com/developer-platform-and-apis-57).
- Feel free to open an `issue` or a `pull request` to improve this guide.
- Join our [Developer community on Discord](https://bit.ly/miro-developers) to exchange ideas and to chat with other Miro developers.

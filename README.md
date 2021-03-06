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
    - [Getting started with the Miro REST API](#getting-started-with-the-miro-rest-api)
    - [Miro REST API tutorials](#miro-rest-api-tutorials)
    - [Postman collection](#postman-collection)
  - [Miro App Examples](#miro-app-examples)
    - [Web SDK](#web-sdk)
    - [REST API](#rest-api)
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

Check out our how-to articles with step-by-step instructions and code examples so you can:  

- [Use the browser developer tools with the Miro Web SDK](https://developers.miro.com/docs/use-the-developer-tools-with-the-miro-web-sdk)
- [Update and sync item properties](https://developers.miro.com/docs/update-and-sync-item-properties)
- [Add icon click to your app](https://developers.miro.com/docs/add-icon-click-to-your-app)
- [Add an icon to your app](https://developers.miro.com/docs/add-a-logo-to-your-app)
- [Build a calendar app in Miro](https://developers.miro.com/docs/building-a-calendar-app-in-miro)
- [Convert sticky notes to shapes](https://developers.miro.com/docs/converting-sticky-notes-to-shapes)


### Miro Web SDK reference guide

Look up methods, board item properties, and copy-paste code examples from the [Miro Web SDK reference guide](https://developers.miro.com/docs/web-sdk-reference). 

## Miro REST API resources

### Getting started with the Miro REST API

- [Quickstart (video):](https://developers.miro.com/docs/try-out-the-rest-api-in-less-than-3-minutes) try the REST API in less than 3 minutes.
- [Quickstart (article):](https://developers.miro.com/docs/build-your-first-hello-world-app-1) get started and try the REST API in less than 3 minutes.

### Miro REST API tutorials

Check out our how-to articles with step-by-step instructions and code examples so you can:  

- [Get started with OAuth 2.0 and Miro](https://developers.miro.com/docs/getting-started-with-oauth)

### Postman collection

[![Run in Postman](https://run.pstmn.io/button.svg)](https://god.gw.postman.com/run-collection/20467754-1a7d3514-f19f-4a86-9001-d694f160da3d?action=collection%2Ffork&collection-url=entityId%3D20467754-1a7d3514-f19f-4a86-9001-d694f160da3d%26entityType%3Dcollection%26workspaceId%3Dc9b8d26d-0e45-472f-8c3a-d04a3d43b17b)

## Miro App Examples

Clone our [Miro App Examples repository](https://github.com/miroapp/app-examples) to get inspiration, customize, and explore apps built on top of Miro's Developer Platform 2.0.

### Web SDK

The fastest way to bootstrap a new app is by using [`create-miro-app`](https://www.npmjs.com/package/create-miro-app).<br />
[Learn more about building your first Hello World app](https://developers.miro.com/docs/build-your-first-hello-world-app).

These are app examples that use the Miro Web SDK: 

|                   App example                                      | Description                                                                                                                                        |
| :------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------- |
| [drag-and-drop](https://github.com/miroapp/app-examples/tree/main/examples/drag-and-drop)                 | This example shows you how to drag and drop images from your app onto the board.                                                                    |
| [stickynotes-to-shapes](https://github.com/miroapp/app-examples/tree/main/examples/stickynotes-to-shapes) | This example allows you to select several sticky notes, click the app button in the app toolbar, and replace any selected sticky notes with shapes.      |
| [template-builder](https://github.com/miroapp/app-examples/tree/main/examples/template-builder)           | This example shows how to create and position on the board different types of items and create a custom user interfaces in the app panel. |
| [calendar](https://github.com/miroapp/app-examples/tree/main/examples/calendar)                           | This example shows you how to add a calendar made with shapes and text for a given month and year.                                                 |
| [wordle](https://github.com/miroapp/app-examples/tree/main/examples/wordle)                               | This example shows you how to create a Wordle-like game using the Miro Web SDK.                                                                      |
| [blob-maker](https://github.com/miroapp/app-examples/tree/main/examples/blob-maker)                       | This example shows you how to create a drag-and-drop blobmaker using the Miro Web SDK.                                                               |
| [youtube-room](https://github.com/miroapp/app-examples/tree/main/examples/youtube-room)                   | This example shows you how to sync a YouTube player across multiple users through [Socket.IO](https://socket.io/).                                                       |


### REST API

These are app examples that use the Miro REST API:

|                   App example                                      | Description                                                                                                                                        |
| :------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------- |
| [python_oauth](https://github.com/miroapp/app-examples/tree/main/examples/oauth/python) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| This Python sample shows how to implement the Oauth 2.0 authorization code flow in Miro.                                            |
| [node_oauth](https://github.com/miroapp/app-examples/tree/main/examples/oauth/node)     | This Node.js sample shows how to implement the Oauth 2.0 authorization code flow in Miro and make an API request to a Miro endpoint. |
| [rest-stickies-csv](https://github.com/miroapp/app-examples/tree/main/examples/rest-stickies-csv)     | This Node.js sample uses SSR (HandlebarsJS) to provide a browser-based tool for leveraging Miro's Sticky Notes and Tag APIs, as well as a .csv import functionality. |

## Support and community

- Stuck somewhere? Encountered any blockers or errors? Need assistance? We're here to help you! Ask your question on our [developer community forum](https://community.miro.com/developer-platform-and-apis-57).
- Feel free to open an `issue` or a `pull request` to improve this guide.
- Join our [Developer community on Discord](https://bit.ly/miro-developers) to exchange ideas and to chat with other Miro developers.

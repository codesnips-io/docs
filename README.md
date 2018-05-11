# Code Snips

CodeSnips is a site for posting, sharing and fetching code snippets and file templates. This documentation covers how it works, how you can contribute and how to interact with the developer resources offered by the site. 

## Ideology

In programming we're constantly reusing the same bits of code, over time it becomes repetitive. Or sometimes there are several different ways to do the same things and we need to find alternatives. We're also forgetful, whether it's something as simple as sorting an array or something a little more complex like [left-pad](https://www.npmjs.com/package/left-pad).

CodeSnips is a place to store and share that code, whether it's small code "snippets" or larger customizable "templates". 

## Access Methods

There are a few different ways to interactive with the application, all of which are documented here.

### Website

The website [https://codesnips.co/](https://codesnips.co/) is the main way to access the system. It allows access to everything, account creation, creating new snippets, finding snippets, etc.

### CLI

One of the other ways to interact with the system is via the Node.JS based CLI. The CLI allows you to search the snippets and fetch them, as well as limited uploading and updating capabilities.

```bash
npm i -g @codesnips/cli
```

View the CLI documentation

### REST API

The last method for interacting with the system is via the REST API. The API allows full access to every bit of the system. The API is oriented towards making things like third party programs for viewing and creating snippets and IDE plugins.

View the API documentation


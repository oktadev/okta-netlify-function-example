# Build a Serverless Function with Netlify Example

This project is the source code for the blog post "[Build and Deploy Secure Serverless Functions with Netlify](https://developer.okta.com/blog/2020/07/15/secure-serverless-functions-with-netlify)." A complete walkthrough video is also available on [YouTube](https://youtu.be/J2DV_H23lEs).

## Requirements

* [Node.js](https://nodejs.org/) version 12 or higher
* A free [Netlify account](https://app.netlify.com/signup)
* A free [Okta developer account](https://developer.okta.com/signup/)
* A good code editor, such as [Visual Studio Code](https://code.visualstudio.com/)

## Setup

The complete steps are explained in the blog post or video. 

* Clone or download this source code
* Open your terminal/command prompt, change to the project folder, and install dependencies using `npm install`
* Copy the `.env.sample` file to `.env`
* Create a new "Single-Page Application" in the Okta Developer dashboard
* Copy your application's **Client ID** and **Org URL** to the `.env` file
* Edit `client/index.js` and change the `oktaOrgUrl` and `oktaClientId` values to match your Okta Org URL and Client ID
* Build the project from the command line using `npm run build`

## Running locally

```sh
npx netlify-cli dev
```

> Note: You can also install the `netlify-cli` tool locally using `npm install --save-dev netlify-cli` or globally using `npm install -g netlify-cli`. After installing locally, you can use `npx netlify dev` or globally you can use `netlify dev`.

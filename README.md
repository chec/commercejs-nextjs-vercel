# Demo Store with Commerce.js and Next.js 🛍️💳

A high-fidelity fully-fledged eCommerce demo store built using the Commerce.js SDK and Next.js with live deployment to Vercel.

[![Live demo](https://cdn.chec.io/email/assets/marketing/chec-demo-btn_gray.svg) ](https://commercejs-nextjs-vercel.now.sh/)

[![Vercel Demo Preview](https://i.ibb.co/m8dVzrG/demo-preview-2.png)](https://commercejs-nextjs-vercel.now.sh/)

**Note**
- This app is built using Commerce.js v2 SDK

## Overview

This README will guide you in getting up and running with a fully-fledged eCommerce template. We have configured this template for you to one-click deploy directly to Vercel. Alternatively, you can manually deploy to your choice of hosting platform.


## Prequisites

- IDE or code editor of your choice
- Node (v8.2.0 or higher)
- NPM or Yarn
- Chec CLI `yarn global add @chec/cli`

## Setup

### Create a Chec account. 

Now that you’ve installed Chec CLI globally, you will be able to access the list of `chec [COMMANDS]`, one of which is registering for a Chec account. Let’s go ahead and get that set up!

```bash
# Open the Chec registration page in your browser
chec register
```

Follow the rest of the walk-through to set up your merchant details. Alternatively, you can go [here](https://authorize.chec.io/signup) to register for a Chec account. 


## One-click Deploy with Vercel (recommended)

The one-click deploy allows you to add the Vercel application to your GitHub account to clone the `commercejs-nextjs-vercel` repository and deploy it automatically. Be sure to go to [Vercel](https://vercel.com/signup) and sign up for an account with Github, GitLab, or GitBucket before clicking the deploy button.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/project?template=https://github.com/chec/commercejs-nextjs-vercel)

Please note that the site deploy will first fail as we have yet to enter in the environment variables for your Vercel site. Configure your site by going under the **Project Settings** in the **General** tab then scroll down to **Environment Variables** to enter your public API key. The value is automatically encrypted and stored in Vercel system. The variable name input is **CHEC_PUBLIC_KEY** and the value input is the Public Key. Please note that for the purpose of getting you up and running with a live deploy preview of the demo store, we have provided you with the public_key from our demo merchant account. Access this key [here](https://github.com/chec/commercejs-nextjs-vercel/blob/master/.env.example) and copy over the `CHEC_PUBLIC_KEY` value.

## 🥞 Stack

- Framework - [Next.js](https://nextjs.org)
- eCommerce - [Chec/Commerce.js](https://commercejs.com)
- Hosting - [Vercel](https://vercel.com)
- Styling - Bootstrap and SASS

## Customization and Extendability

- Add shipping zones and enable shipping options in each product
- Adding new features or extending existing features
- Customizing the styling
    - All global styles are done using SASS and Bootstrap
- A/B testing unique checkout designs and flow
- Integrating other backend tools like Content Management Systems, Customer Support, Fulfillment services, and more.
- Fetching real client reviews from reviews APIs
- Adding search functionality
- Leveraging webhooks to automate post checkout actions

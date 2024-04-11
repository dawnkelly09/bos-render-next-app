# Render BOS components in Next.js apps

Loving building BOS components with the online editors but missing your favorite React libraries? 

Follow this guide to learn how to customize the create-near-app to render your BOS components inside a Next.js app. 

## Quickstart 🏃🏾

### Prerequisites ✅
Ensure you have [Node.js](https://nodejs.org/en/download/current) installed. You'll need `version 18+` to use the frontend/gateways to build this app.

### Installation 🏗️

To create a new NEXT.js app which can interact fully with NEAR and render your BOS components:

- Open your terminal, navigate to the directory where you want to create your project. Run the create command and follow the interactive prompts:
```
npx create-near-app@latest
```
🚧 TODO: walk through this, take screenshots, document the selections I used

- Once the installation is complete, navigate to your project directory and start the development server:
```
pnpm dev
```
You can view your BOS compatible Next.js app at http://localhost:3000 You should see the landing page of the Hello NEAR Gateway which looks like this:

<img src="https://docs.near.org/assets/images/hello-near-landing-page-2b5dd73c1781ad60fd87651a046d015e.png" alt="Landing page of Hello NEAR Gateway" width="90%">

## Key files & modifications
Let's take a look at some important files you'll need to understand before you can effectively use this template. 

There are a few changes you'll need to make before you can successfully develop render your BOS components in this application. 

🚧 TODO: Go through the setup/modification process, take notes and screenshots

### layout.js
`./src/app/layout.js`
<br><br>
Defines the apps template. Like a typical Next app, things you want to appear on every page should be should applied here. This file does two things:

1. Initializes a [wallet selector](https://docs.near.org/tools/wallet-selector) and stores it so other components can access it later.
2. Renders the navigation menu and the page's content




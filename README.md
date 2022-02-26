# plies nft collection

Plies in a completely on chain NFT project.

> The Shannon number is a conservative lower bound of the game-tree complexity of chess of 10120, the number of possible unique games.
> This collection represents the first move, or pair of **plies**, accounting for 40 possible outcomes.

The plies NFT metadata is rendered completely on chain as a base64 encoded data uri -- the image is a base64 encoded svg that is generated and rendered on chain.

This repo holds the frontent minting website for the plies NFT project. The repo with smart contracts can be found [here](https://github.com/alstonwhite/plies-contracts).

The plies NFT project was guided by [Buildspace](https://buildspace.so/).

## Deployed Site

Check out the deployed site [here](https://nft-starter-project.alstonwhite.repl.co).

## Installation and Usage

To run this on your local machine, clone this project and insall dependencies with the below:

```
git clone https://github.com/alstonwhite/plies-client
npm install
```

In the project directory, you can run the following scripts:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

***

This project was originally built and deployed through Replit, see notes below for usage with Replit:

## Running React on Repl.it

[React](https://reactjs.org/) is a popular JavaScript library for building user interfaces.

[Vite](https://vitejs.dev/) is a blazing fast frontend build tool that includes features like Hot Module Reloading (HMR), optimized builds, and TypeScript support out of the box.

Using the two in conjunction is one of the fastest ways to build a web app.

### Getting Started
- Hit run
- Edit [App.jsx](#src/App.jsx) and watch it live update!

By default, Replit runs the `dev` script, but you can configure it by changing the `run` field in the `.replit` file.

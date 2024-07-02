

<h1 align="center">
  <br>
  <a href="https://lakshman-natours.herokuapp.com/"><img src="https://github.com/Youssefawzy/rbay/assets/116081592/85bec72a-a4af-4210-b1af-8fac9307a9b1" alt="rBay" width="200">
</h1>

 <p align="center">
  <a href="#Description">Description</a> •
  <a href="#key-features">Key Features</a> •
  <a href="#demonstration">Demonstration</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#api-usage">API Usage</a> •
  <a href="#deployment">Deployment</a> •
  <a href="#build-with">Build With</a> •
  <a href="#to-do">To-do</a> •
  <a href="#installation">Installation</a> • 
  <a href="#known-bugs">Known Bugs</a> • 
  <a href="#future-updates">Future Updates</a> • 
  <a href="#acknowledgement">Acknowledgement</a>
</p>

# Description

<h2 align="center">
  <br>
  <a href="https://lakshman-natours.herokuapp.com/"><img src="https://github.com/Youssefawzy/rbay/assets/116081592/b5e15d44-fcbf-4194-9648-56d96a0b1089" alt="rBay" width="500">
</a>
  <br>
     rBay is an E-commerce application inspired by Ebay. users can create an account and begin selling or buying goods or services.

  This project is built using Redis, an open-source, in-memory data structure store.
  <br>
</h2>

# key-features
<h3>Item Search</h3>
 users can search for items by entering the item's name or description in the search bar. The platform uses Redis for rapid data retrieval and fuzzy search to handle spelling errors and partial matches. The most viewed items are prominently displayed, helping users find popular products quickly and easily.

  <br>

![Untitled design](https://github.com/Youssefawzy/rbay/assets/116081592/7091a467-7e94-43b3-a26d-a011bbd9b405)


<h3>Showing the ending soon items, the most expensive items and the most viewed items</h3>
 users can quickly discover items with bids ending soon and the most expensive listings, making it easier to spot urgent deals and high-value products. The most viewed items are also prominently displayed, helping users find trending products easily.

  <br>

![Untitled design (2)](https://github.com/Youssefawzy/rbay/assets/116081592/4b04983b-95d3-4187-bed5-ce89c816ce90)

![Untitled design (1)](https://github.com/Youssefawzy/rbay/assets/116081592/f7f8f750-754b-4630-8d5a-910819b2c2fb)

<h3>Bids</h3>

The platform also allows users to place bids on items, ensuring their bid is higher than the current highest bid and submitted before the auction ends.

![Untitled design (3)](https://github.com/Youssefawzy/rbay/assets/116081592/c1f6951d-4b43-45c5-97b0-716c8964e25d)

# create-svelte

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npm init svelte@next

# create a new project in my-app
npm init svelte@next my-app
```

> Note: the `@next` is temporary

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.

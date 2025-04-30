# <img src="/static/favicon.png" align="right" height="75px" /> GambiConf

> 🐒 The Blow Your Mind Conference

<p align="center">
  <img width="1643" alt="image" src="https://github.com/user-attachments/assets/0adb5159-4432-41a8-8efb-7241cb868cea" />
</p>

# How to run

1 - Clone this repo

```
git@github.com:gambiconf/gambiconf.github.io.git
```

2 - Install the dependencies

```
cd gambiconf.github.io.git && npm i
```

3 - Start the SvelteKit's development mode

```
npm run dev
```

4 - Then the website will be available at [`http://localhost:3000/`](http://localhost:3000/)

## How to deploy

### Prod

Deploying to GitHub Pages is an easy task. Just run it:

```
npm run build:prod && npm run deploy:prod
```

> [!IMPORTANT]  
> If you're deploying outside the root path (example: youruser.github.io/gambiconf), you need to set the environment variable `BASE_PATH` to the target base path (example: `/gambiconf`).

### Staging

We have a [staging repository/environmnet](https://github.com/gambiconf/website-staging).

```
npm run build:staging && npm run deploy:staging
```

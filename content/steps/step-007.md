---
title: Step 7 - Node.js
order: 8
---

## Install Node

Now it's time to install Node.js. Visit the [Node Homepage](https://nodejs.org/) and download the installer for your system.

We need at least Node v10 so you can use LTS (v12) or Current (v14) without any problems.

## Check if it is installed

Again, if you want to check if node is installed (and also check the version) you can run `node -v` in your terminal

```bash
node -v
```

Once you have installed Node you can run `node -v` in your terminal again to see if it is there. You might need to restart your terminal again for it to pick it up

## Install Yarn

Some of the Ember repos use an alternative package manager called Yarn, so if you want to contribute to them then you need to install Yarn. Make sure that you insatll Yarn v1.x because Yarn v2.0 is a very different project that won't work for most repos. 

You can install it from https://classic.yarnpkg.com/

If you want to know if a repo is using yarn instead of the default npm, you can check to see if there is a `yarn.lock` file in the top-level of the repo (instead of a `package-lock.json`). If you see a `yarn.lock` file then you should use yarn to install dependencies.
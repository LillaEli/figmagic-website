# Figmagic website

[![Netlify Status](https://api.netlify.com/api/v1/badges/18034985-3c47-4c04-b997-174a8017167c/deploy-status)](https://app.netlify.com/sites/figmagic/deploys)

This is the source code for the public [https://github.com/mikaelvesavuori/figmagic](Figmagic) website, hosted through Netlify on [https://www.figmagic.com](https://www.figmagic.com).

## Development

At the moment, the site is deliberately very simple: merely a short presentation. Therefore the technology to support the site should be equally plain and uncomplicated.

The current tech stack is just regular HTML and CSS.

There's two primary ways you can go about developing for the site.

### 1. Plain vanilla "old school"

To do this, just open up your web browser of choice and open up `src/index.html` inside of it. Proceed to making changes in your code editor/IDE and reload the browser to see changes. Really old-school but should be enough for the site, I guess.

### 2. Netlify dev

Since the site is run on Netlify, the repo is wired to use the `netlify dev` command to do local development.

- First you need the Netlify CLI; install it by running `npm install netlify-cli -g`
- Inside of this repo, run `netlify dev` and your web browser should start up

## Deployment and site updates

The GitHub Actions CI pipeline deploys code automatically from the `master` branch.

### Branching

You should use a `feature` branch and submit a pull request towards `master`, which I can then accept or reject.

### Deployment permissions

As project owner I will manually approve of changes and accept those before code changes get deployed.

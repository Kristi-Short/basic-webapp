# basic-webapp

> A Vue.js project

## Build Setup

``` bash

# after running npm install,  do npm run dev to development server and it should be running on Localhost:8080. run command npm install -g vue-cli. -g for global for use anywhere. Check version install by running vue --version. after install open code in Visual studios to alter data such as add calculation button and title heading.
npm install

#how to open project into browser, run npm run dev in comman line. We should see our page loaded onto a new tab under our Localhost:8080. Page should be live with instand changes.
npm run dev

# build for production with minification , first change directory dist/ to docs in config/index.js for Webpack to be able read file. Once configured we run npm run build, changes to docs make files "minified" and "uglified"
npm run build

# execute build command by running npm run build. Shows in browser file break down of size and type.
npm run build --report

# We have already set up our repository in GitHub to be able to commit and push out code to. We can from the comman line do a git add docs, git commit, and a git push origin to be able to make our work public on Github.
deploy site
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

# Welcome
This project is intended to serve as a lightweight example for creating a [create-react-app](https://facebook.github.io/create-react-app/) application that can be deployed to [Zeit Now 2.0](https://zeit.co/now).

You can view a [live demo](https://demo-create-react-app-nowv2.now.sh/) at [https://demo-create-react-app-nowv2.now.sh/](https://demo-create-react-app-nowv2.now.sh/).

This demo has been based off the original tutorial created by Zeit at [https://github.com/zeit/now-examples/tree/master/create-react-app](https://github.com/zeit/now-examples/tree/master/create-react-app)

## Cheat sheet
```
// Step 1 - Create the default React app using create-react-app
$ npx create-react-app demo-zeit-now-v2-create-react-app
$ cd demo-zeit-now-v2-create-react-app/

// Verify your local app is up and running
$ npm start

// Step 2 - Create `now.json` for deployment to Zeit Now v2
//  Note that we have added a "now-build" script to build our React app

// Step 3 - Deploy to now
$ npm run deploy

> demo-zeit-now-v2-create-react-app@0.1.0 deploy /Users/rob/repos/demo-zeit-now-v2-create-react-app
> now && now alias

> Deploying ~/repos/demo-zeit-now-v2-create-react-app under therobbrennan
> Using project demo-create-react-app-nowv2
> Synced 4 files (416.42KB) [1s]
> https://demo-create-react-app-nowv2-q7bc89uod.now.sh [v2] [in clipboard] [11s]
┌ package.json        Ready               [2m]
├── asset-manifest.json (779B)
├── favicon.ico (3.78KB)
├── index.html (2.01KB)
├── manifest.json (306B)
├── precache-manifest.aab4cbc75d3da43eae65977b3c583b59.js (606B)
├── service-worker.js (1.02KB)
├── static/css/main.cf084238.chunk.css (984B)
├── static/css/main.cf084238.chunk.css.map (1.49KB)
├── static/js/main.a3d3a657.chunk.js (1.31KB)
├── static/js/main.a3d3a657.chunk.js.map (7.17KB)
├── static/js/runtime~main.229c360f.js (1.47KB)
├── static/js/runtime~main.229c360f.js.map (7.81KB)
├── static/media/logo.5d5d9eef.svg (2.61KB)
├── static/js/1.13eeb203.chunk.js (116.55KB)
└── static/js/1.13eeb203.chunk.js.map (335.7KB)
> Success! Deployment ready [2m]
> Assigning alias demo-create-react-app-nowv2.now.sh to deployment demo-create-react-app-nowv2-q7bc89uod.now.sh
> Success! demo-create-react-app-nowv2.now.sh now points to demo-create-react-app-nowv2-q7bc89uod.now.sh [2s]

```
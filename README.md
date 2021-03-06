# JS Knowhow Share

```
"...how long does it take to become a JS developer.."
"...how can we learn or go about learning modern JS..."
```
This is a formal-ish response which aims to address those, and related, concerns.

## Learning Resources

*  [Current State of JS - 2018 Edition](https://2018.stateofjs.com/introduction/) - informative high level and interactive overview of what's going on in the JS world
*  [Eloquent JavaScript - 3rd Edition](https://eloquentjavascript.net/) - authoritative JS intro/overview including modern ES6
*  [MDN Web Docs](https://developer.mozilla.org/en-US/) - single source of truth for modern web development IMHO
*  [ECMAScript 6](http://es6-features.org/#Constants) - Latest overview of JavaScript's built-in features
*  [Learning About Git](https://try.github.io/) - Git's learning dashboard with many git-related resources 

Note: Be weary of blogs. The majority of them have been scrapped by some crawler from one another and can be misleading. **If you do stumble upon a post, be mindful of the version of the respective technology that is used in said post. The JavaScript world is a developing one. As a language itself as well as the general supporting ecosystem. There can be paradigm-changing differences between major version releases.** In short, I always find it helpful to go to the core tech docs from the distributor of each respective technology. IHMO this saves times and ensures you're consuming valid information.

## Box Config: Node, NPM, and Local Development

[Node](https://nodejs.org/en/) is a JavaScript **runtime environment** (similar to CLR) and [npm](https://www.npmjs.com/) is Node's package manager (similar to NuGet).

1. [Set up Node and NPM](https://blog.teamtreehouse.com/install-node-js-npm-windows)
2. [Git for Windows](https://git-scm.com/download) - Comes with a MinGW (Minimalist GNU for Windows) terminal

## Getting Into It

### Sand-boxing

[CodePen](https://codepen.io/#) is a great learning environment. This tool allows you to start messing with different JavaScript technologies in real-time without the need to configure a local environment. Great for building out small modules. It also provides a ton of features! Below you'll find links to some of my pens for you to fork then play with.

* [Basic React Component Reference](https://codepen.io/SpeauDetcR/full/VdwEJP) - General overview of a basic React component
* [React and Semantic UI - User Interface](https://codepen.io/SpeauDetcR/full/qYvERm) - This is a code challenge I did about a year ago. All the details are in the pen.
* [React + Redux used to consume API](https://codepen.io/SpeauDetcR/full/ELEozX) - This pen uses the DC Metro open API to check arrival times of upcoming trains

Note: [You can change the view of each pen to edit the source code](http://prntscr.com/mjq25r)

[Update: You can add npm packages to a pen through the pen's settings opts - screencast link](https://screencast-o-matic.com/watch/cqnI3R381G)

### Generators

Some contributors in the community have created tools referred to as "Generators." These generators are a useful way to get up and running with a full-fledged Node application. These generators, once installed properly/globally on your machine (i.e., ```npm i -g```), have the ability to run a scaffolding process which creates a local instance of a particular application. Links contain instructions.

* [Express](https://expressjs.com/en/starter/generator.html)
* [Create React App](https://github.com/facebook/create-react-app)
* [Create Redux App](https://github.com/jonidelv/generator-create-redux-app)

### Demo Apps

So CodePen is primarily used for front-end and API related development. Below you'll find links to some Git repositories I've worked on in the past.

* [Minimalist Real World React App](https://github.com/speaud/SMART-on-FHIR-exercise)
* [Haystack's Developer Exercise](https://github.com/speaud/takehome-exercise)
* [React and Redux Static Pool Game](https://github.com/speaud/o3_pool_app_exercise)

Note: There are many more examples out there. The above items are intended to "get you going," and are not to be considered as a absolute.

### "Hello World!" Tutorials and Misc. Resources

* [Based Node App by MDN](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/development_environment)
* [React Based Demo App Collection](https://reactjs.org/community/examples.html) - Collection of React-based demo apps approved by the core distro team
* [Express](https://expressjs.com/en/starter/hello-world.html) - Basic example to setup a simple http server using Node and Express
* [D3 Gallery](https://github.com/d3/d3/wiki/Gallery) - There's a ton of stuff here! We only use D3 for the 'network graph," so some of the examples here may be out of the scope in which we use D3.

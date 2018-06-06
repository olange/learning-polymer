# Learning Google Polymer

Articles, useful resources, courseware, homework and personal notes.

[![Join the chat at https://gitter.im/olange/learning-polymer](https://badges.gitter.im/olange/learning-polymer.svg)](https://gitter.im/olange/learning-polymer?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Events

* [Polymer Summit 2016](https://www.polymer-project.org/summit/schedule) London, Tobacco Docks, 17-18.10.2016  
[Videos of the conferences](https://www.youtube.com/playlist?list=PLNYkxOF6rcICc687SxHQRuo9TVNOJelSZ) YouTube, 41 videos of the 2 days
* [Google I/O 2017](https://events.google.com/io/)  
  [Future, faster: Unlock the power of Web Components with Polymer](https://www.youtube.com/watch?v=cuoZenpQveQ&list=PLNYkxOF6rcICniLJ2rfj0FexlA-9zmJJE&index=2) Google, Wendy Ginsberg and Kevin Schaaf, 17.05.2017 (video, 43 min.)

## Codelabs

* [Build a Progressive Web App with Firebase, Polymerfire and Polymer Components](https://codelabs.developers.google.com/codelabs/polymer-firebase-pwa/index.html) _18.10.2016 Polymer Summit_  
([My codelab source code](https://github.com/olange/learning-polymer/tree/master/codelabs/pwa-firebase)) _A beginner project, demonstrating reuse of prepared Polymer elements to build an online note editor app, with Google OAuth authentication and Firebase persistence._
* [Building an Image Carousel Element with Polymer 2.0](https://codelabs.developers.google.com/codelabs/polymer-2-carousel/) _17.10.2016 Polymer Summit_  
([My codelab source code](https://github.com/olange/learning-polymer/tree/master/codelabs/carousel)) _A beginner project, demonstrating how to use Polymer 2.0 with ES2015 class syntax, while building a simple image carousel and gradually adding features to it._
* [Data Visualization Using Polymer and WebGL](https://codelabs.developers.google.com/codelabs/polymer-webgl/) _Google Codelabs_ ([My codelab source code](https://github.com/olange/learning-polymer/tree/master/codelabs/googlemap-viz)) _A visualization of thousands of data points over an interactive Google Map, taking advantage of Polymer and some Google Web Components to easily cobble together a pipeline to load data, pass it into WebGL, and then manipulate it in real time._
* [Auth0 › Build Your First App with Polymer and Web Components](https://auth0.com/blog/build-your-first-app-with-polymer-and-web-components/) _Auth0 blog, Kim Maida, 05.10.2016_  
  _Build an app using web components and Polymer that interacts with an API and authenticates users with JSON Web Tokens (JWT)._

## Supporting or related technologies

* [Google Material Design](https://material.io/guidelines/material-design/introduction.html) _A graphical system and visual language, that synthesizes classic principles of good design with the innovation and possibility of technology and science; develops a single underlying system that allows for a unified experience across platforms and device sizes_
* [Polymer App Toolbox](https://www.polymer-project.org/2.0/toolbox/index) _A collection of components, tools and templates for building Progressive Web Apps with Polymer, which features: component-based architecture; responsive design; modular routing; localization; turnkey support for app local storage;
offline caching; build tooling to support serving your app multiple ways (unbundled/HTTP2, bundled/HTTP1)_
* [Progressive Web Apps · Guidelines](https://developers.google.com/web/progressive-web-apps) _A set of guidelines, that provide user experiences that have the reach of the web, and are_ reliable: _load instantly, even in uncertain network conditions_; fast: _respond quickly to user interactions_; engaging: _feel like a natural app on the device_
* [Polymer App Toolbox · PRPL Pattern](https://www.polymer-project.org/2.0/toolbox/prpl) Push _critical resources for the initial route_; Render _initial route_; Pre-cache _remaining routes_; Lazy-load _and create remaining routes on demand_; see also the [PRPL Server for Node](https://github.com/Polymer/prpl-server-node)

## Articles

* [ECMAScript modules in browsers](https://jakearchibald.com/2017/es-modules-in-browsers/) (Jake Archibald, 02.05.2017)
* [Polymer 2.0 Cheat Sheet](https://meowni.ca/posts/polymer-2-cheatsheet/) (Monica Dinculescu, @notwaldorf)
* [What is shady DOM?](https://www.polymer-project.org/1.0/blog/shadydom) (Polymer Project Blog, Scott Miles, 28.05.2015)
* The four [Web Components standards](https://developer.mozilla.org/en-US/docs/Web/Web_Components) (Mozilla Developer Network)
 * [Shadow DOM v1: Self-Contained Web Components](https://developers.google.com/web/fundamentals/getting-started/primers/shadowdom) (Google Web Fundamentals, Eric Bidelman)
 * [Shadow DOM specification](http://w3c.github.io/webcomponents/spec/shadow/) (W3C Editor's Draft, 28.11.2016)
 * [HTML's New Template Tag](https://www.html5rocks.com/en/tutorials/webcomponents/template/) (HTML5Rocks, Eric Bidelman, 26.02.2013)
 * [Custom Elements v1: Reusable Web Components](https://developers.google.com/web/fundamentals/getting-started/primers/customelements) (Google Web Fundamentals, Eric Bidelman)
 * [HTML Imports](https://www.html5rocks.com/en/tutorials/webcomponents/imports/) (HTML5Rocks, Eric Bidelman, 11.11.2013)
* [Are we componized yet?](http://jonrimmer.github.io/are-we-componentized-yet/) (John Rimmer) _a matrix synthetizing current support status of the four Web Components Standards in the various browsers_
* [«Real» Mixins with JavaScript Classes](http://justinfagnani.com/2015/12/21/real-mixins-with-javascript-classes/) (Justin Fagnani's blog, 21.12.2015) _what mixins should do, what's wrong with current JavaScript mixins, and how simple it is to build a very capable mixin system in JavaScript that plays extremely well with classes_
* [Regarding the broken promise of Web Components](https://robdodson.me/regarding-the-broken-promise-of-web-components/) Rob Dodson, 15.03.2017, in response to  
  [The broken promise of Web Components](https://dmitriid.com/blog/2017/03/the-broken-promise-of-web-components/#brief-incomplete-and-mostly-incorrect-history-of-web-components) Dmitrii Dimandt, 14.03.2017
* [Custom Elements That Work Anywhere](https://medium.com/dev-channel/custom-elements-that-work-anywhere-898e1dd2bc48#.xbmcc634v) Rob Dodson, 30.06.2016
* [Javascript Tools: A Story in Disgrace](https://dmitriid.com/blog/2016/10/javascript-tools/) Dmitrii Dimandt, 14.03.2017 _an opinion article, about state of JavaScript app dev; many interesting references_
* [Polymer Guides › Flexbox layout with iron-flex-layout](https://elements.polymer-project.org/guides/flex-layout) _A guide to the two different ways of using the `iron-flex-layout` component – which provides simple ways to use CSS flexible box layout (flexbox): either the layout classes, which let us specify layout properties directly in markup; or the_ [custom CSS mixins](https://www.polymer-project.org/1.0/docs/devguide/styling.html#custom-style), _that can be `@apply`-ied inside CSS rules_
* [Polymer Guides › Responsive Material Design Layouts](https://elements.polymer-project.org/guides/responsive-material-design-layouts) _A short guide, that teaches how to use_ [Paper](https://www.webcomponents.org/collection/PolymerElements/paper-ui-elements), [Iron](https://www.webcomponents.org/collection/PolymerElements/iron-elements) _and_ [Iron Flex](https://www.webcomponents.org/element/PolymerElements/iron-flex-layout) _elements to create a responsive layout; beware: refers to Polymer 1 elements!_
* [Polymer Guides › Using Elements](https://elements.polymer-project.org/guides/using-elements) _An overview of the primary collections of elements, how-to install and use them in a main page or an element; provides also a quick overview of_ [data binding](https://www.polymer-project.org/1.0/docs/devguide/data-binding.html), _of_ [mapping attribute names to property names](https://elements.polymer-project.org/guides/using-elements#polymer-element-apis) _and of_ [DOM manipulation](https://www.polymer-project.org/1.0/docs/devguide/local-dom.html#dom-api) _concepts_
* [WebComponents › Best practices](https://www.webcomponents.org/community/articles/web-components-best-practices) first published 29.04.2014 _a list of best practices, that evolves over time with community suggestions_

## Case studies and fun apps

* [Google Polymer Shop](https://www.polymer-project.org/2.0/toolbox/case-study) _A complete case study of the Shop, a full-featured e-commerce PWA demo, built using the Toolbox_
* [Google Polymer News](https://www.polymer-project.org/2.0/toolbox/news-case-study) _A complete case study of News, a full-featured PWA demo, built using the Toolbox_
* [Google Polymer Cheese](https://cheese.polymer-project.org/) _Say « cheese » and take a photo; try it on a mobile device_
* [Google Polymon](https://polymon.polymer-project.org/) _A multiplayer, location-based monster hunting game designed and maintained by the Polymer team; hint, when outside of a Polymer Summit: start at https://twitter.com/0xcda7a to find monsters_
* [Google Santa Tracker](https://santatracker.google.com/codeboogie.html) _Use Google Santa Tracker to follow Santa Claus on Google Maps as he makes his journey around the world_
* [vpusher Game Card WebComponent](https://www.webcomponents.org/element/vpusher/game-card) _Playing game card element based on ES6 and Polymer 2.0; infinitely scalable, thanks to unicode characters and SVG_
* [vpusher The Grid WebComponent](https://www.webcomponents.org/element/vpusher/the-grid) _Grid layout custom element based on ES2015 and Polymer 2.0_
* [Hacker News readers as Progressive Web Apps](https://hnpwa.com/) _unofficial collection of Hacker News clients built with a number of popular JavaScript frameworks and libraries; each implementation is a complete Progressive Web App, that utilizes different progressive technologies to provide a fast, reliable and engaging experience_

## Books

* [Production-Ready Microservices](https://www.safaribooksonline.com/library/view/production-ready-microservices/9781491965962/) by Susan J. Fowler, O'Reilly, 12.2016
* [Microservice Architecture](https://www.safaribooksonline.com/library/view/microservice-architecture/9781491956328/) by Mike Amundsen, Matt McLarty, Ronnie Mitra, Irakli Nadareishvili, O'Reilly, 08.2016

## See also

* [10 Best ReactJS UI Frameworks for rapid prototyping](https://hashnode.com/post/10-best-reactjs-ui-frameworks-for-rapid-prototyping-cit49tqx414z89c53equ4zc5k) hashnode, Tom Alter, 15.09.2016
* [React · Material UI](http://www.material-ui.com/#/) _A set of React Components that Implement Google's Material Design_
* [Foundation](http://foundation.zurb.com) _A family of responsive front-end frameworks, for any device, medium, and accessibility; semantic, readable, flexible, and completely customizable; can be applied to websites, apps and e-mails_

## Tools

### Material Design

* [Material Design · Color tool](http://material.io/color/) _create, share, and apply color palettes to your UI, as well as measure the accessibility level of any color combination_

### Polymer

* [Polymer CLI](https://github.com/Polymer/polymer-cli)
* [Polymer Build](https://github.com/Polymer/polymer-build)
* [Polymer Editor plug-in](https://github.com/Polymer/polymer-editor-service)
* [Polymer Designer](http://designer.polymer-project.org/) _see also [Introducing Polymer Designer Tools](https://www.youtube.com/watch?v=djQh8XKRzRg) by Rob Dodson (video, 18 min.)_

### Storage

* [Firebase Console](https://console.firebase.google.com)
* [Firebase CLI](https://firebase.google.com/docs/cli/)

### Auditing PWA apps

* [Chrome Lighthouse](https://github.com/GoogleChrome/lighthouse) _auditing and performance metrics for Progressive Web Apps_ [Lighthoust Quick Start](http://bit.ly/lighthouse-quickstart)
* Chrome Inspect `chrome://inspect` and Chrome Tracing `chrome://tracing`

### For IDE enthusiasts

* [Visual Studio · Polymer IDE](https://marketplace.visualstudio.com/items?itemName=polymer.polymer-ide) _Unlocks all of the power of the [Polymer Analyzer](https://github.com/Polymer/polymer-analyzer) in VS Code: provides linting, autocompletion, and more for web components_ `ext install polymer-ide`
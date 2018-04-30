# Awesome Polymer

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![GitHub Stars](https://img.shields.io/github/stars/StartPolymer/awesome-polymer.svg?label=GitHub%20Stars)](https://github.com/StartPolymer/awesome-polymer)
[![GitHub Watchers](https://img.shields.io/github/watchers/StartPolymer/awesome-polymer.svg?label=GitHub%20Watchers)](https://github.com/StartPolymer/awesome-polymer)
[![PRs welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://help.github.com/articles/about-pull-requests/)

> A collection of awesome Polymer resources.

- [General resources](#general-resources)
- [Polymer Communities](#polymer-communities)
- [Polymer & Web Components Blogs](#polymer--web-components-blogs)
- [Polymer Codelabs / Playgrounds](#polymer-codelabs--playgrounds)
- [Directories](#directories)
- [Elements](#elements)
- [Mixins / Behaviors](#mixins--behaviors)
- [Libraries](#libraries)
- [Patterns](#patterns)
- [Polymer is SEO-friendly](#polymer-is-seo-friendly)
- [Tutorials / Guides](#tutorials--guides)
- [Case Studies](#case-studies)
- [Integration with other frameworks](#integration-with-other-frameworks)
- [Articles](#articles)
- [Videos](#videos)
- [Templates](#templates)
- [Tools](#tools)
- [Editor Plugins](#editor-plugins)
- [Testing](#testing)
- [Notable projects](#notable-projects)
- [Polymer Authors](#polymer-authors)
- [Other awesome resources](#other-awesome-resources)

## General resources

- [Polymer Official Site](https://www.polymer-project.org)
- [Polymer Project repo](https://github.com/polymer/project) - Roadmap, Code of Conduct, How to Contribute, and more.
- [Polymer Library repo](https://github.com/polymer/polymer)
- [Polymer repos](https://github.com/polymer)
- [Polymer Elements repos](https://github.com/polymerelements)
- [Polymer Labs repos](https://github.com/polymerlabs)
- [Polymer Summit](https://summit.polymer-project.org)
- [Chrome Dev Summit](https://developer.chrome.com/devsummit/)

### Hashtags

- [#UseThePlatform](https://www.polymer-project.org/about)
- [#UseWebPlatform](https://github.com/UseWebPlatform/motto-UseWebPlatform)

## Polymer Communities

- [Slack](http://polymer-slack.herokuapp.com)
- [StackOverflow](http://stackoverflow.com/questions/tagged/polymer)
- [GoogleGroup](https://groups.google.com/forum/#!forum/polymer-dev)
- [Twitter](https://twitter.com/polymer)
- [Google+ Profile](https://plus.google.com/+PolymerProject/)
- [Google+ Community](https://plus.google.com/communities/115626364525706131031)
- [Reddit](https://www.reddit.com/r/PolymerJS/)
- [Chinese QQ Group](http://shang.qq.com/wpa/qunwpa?idkey=9df0a6fdd100374f1097330ad6327d4d3c40dc734aa8e7a841ae41cda5012980)
- [Polymeristi](https://github.com/Polymeristi/readme) - Czech & Slovak Polymer community.

## Polymer & Web Components Blogs

- [Polymer Blog](https://www.polymer-project.org/blog/)
- [Web Components Community](https://www.webcomponents.org/community)
- [Chromium Dev Channel](https://medium.com/dev-channel)
- [Captain Codeman](https://www.captaincodeman.com/tag/polymer)
- [Collaborne Engineering](https://medium.com/collaborne-engineering/tagged/polymer)

## Polymer Codelabs / Playgrounds

- [Polymer Summit 2017 Codelabs](https://codelabs.developers.google.com/polymer-summit-2017)
- [Polymer Summit 2016 Codelabs](https://codelabs.developers.google.com/polymer-summit-2016)
- [Google Developers Web Codelabs](https://codelabs.developers.google.com/?cat=Web)
- [StartPolymer Playgrounds](https://github.com/StartPolymer/playgrounds)

## Directories

- [WebComponents.org](https://webcomponents.org)

## Elements

- [Polymer Catalog](https://www.webcomponents.org/collection/Polymer/elements)
- [Awesome Elements](https://www.webcomponents.org/collection/StartPolymer/awesome-elements)
- [StartPolymer Elements](https://www.webcomponents.org/collection/StartPolymer/s-elements)
- [Vaadin Core Elements](https://github.com/vaadin/vaadin-core-elements) - Themable UI elements (Material and Valo themes).

## Mixins / Behaviors

- [Mixins](https://www.webcomponents.org/search/mixin)
- [Behaviors](https://www.webcomponents.org/search/behavior)

## Libraries

### TypeScript

- [TypeScript decorators for Polymer 2.0](https://github.com/Polymer/polymer-decorators)

## Patterns

### Managing State

#### Mediator Pattern

- [Thinking in Polymer (The Polymer Summit 2015)](https://www.youtube.com/watch?v=ZDjiUmx51y8&index=3&list=PLNYkxOF6rcICdISJclfQhj2S8QZGjXV8J)

#### Global Mediator Pattern

- [Mediator Pattern vs Global Mediator Pattern](https://www.youtube.com/watch?v=Wu2GCRkDecI&feature=youtu.be&t=22m40s)

##### UniFlow

- [UniFlow - uni-directional data flow + maintains state of entire application](https://github.com/google/uniflow-polymer)
  - [Difference between UniFlow and Redux](https://github.com/google/uniflow-polymer/issues/9)
  - [ToDo MVC Demo](https://github.com/google/uniflow-polymer/tree/master/todomvc)
  - [UniFlow Polymer Starter Kit](https://github.com/LostInBrittany/uniflow-polymer-starter-kit)
  - Answers from author @militeev on Slack
    - With UniFlow you move all your complex logic to action dispatchers, leaving to the visual elements only tasks of rendering the data and reacting to user events. This simplifies things a lot, especially when it comes to unit testing.
    - Answering the question if this is another alternative to Redux, the answer is probably yes. We started the project in early 2016, and Flux and Redux ideas definitely influenced it.
    - I would say it's implementation of basic principles of Flux/Redux + convenience methods for views.
    - Yes, it was developed as part of an internal project at Google, then we separated it out, documented and open-sourced.
    - From my experience, patterns are easier to follow if they're implemented in the code. For small projects it's not critical. When you have large group of people working on a project, chances are that different people will attempt doing same thing in various different ways. Having library and guidelines how to use it helps in this case.
    - Yes, you can easily implement all these concepts yourself, customizing the way you want. The advantage of having the library is that someone already thought about different scenarios that may occur, coded those and unit-tested.

##### Redux

- [How to use Redux in Polymer -- Polycasts #61](https://www.youtube.com/watch?v=PahsgJn0sgU)
- [Project Structure for Using Redux with Polymer 2.0](https://www.captaincodeman.com/2017/07/19/project-structure-for-using-redux-with-polymer-20)
- [Why not to store objects in Redux](https://medium.com/collaborne-engineering/why-not-to-store-objects-in-redux-7f41243020fc) - 2017-07

### PRPL Pattern

[PRPL Pattern](https://www.polymer-project.org/2.0/toolbox/prpl) is alternative for a benefits of server-side rendering.

- [End to End Apps with Polymer (Polymer Summit 2017)](https://www.youtube.com/watch?v=0A-2BhEZiM4)

#### PRPL Servers

- [prpl-server-node](https://github.com/Polymer/prpl-server-node)
- [prpl-server-go](https://github.com/CaptainCodeman/prpl-server-go)

##### Features

- [Differential Serving](https://github.com/Polymer/prpl-server-node#differential-serving)
- [HTTP/2 Server Push](https://github.com/Polymer/prpl-server-node#http2-server-push)
- [Rendering for Bots (SEO, Open Graph)](https://github.com/Polymer/prpl-server-node#rendering-for-bots)

## Polymer is SEO-friendly

Polymer Project develops [PRPL server](https://github.com/Polymer/prpl-server-node) using [Rendertron](https://github.com/GoogleChrome/rendertron) server which runs [Headless Chrome](https://developers.google.com/web/updates/2017/04/headless-chrome) to render and serialize web pages for search bots, so all the content is contained in one network request.

- [PRPL server - Rendering for Bots](https://github.com/Polymer/prpl-server-node#rendering-for-bots)
- [Solving SEO with Headless Chrome (Polymer Summit 2017)](https://www.youtube.com/watch?v=ydThUDlBDfc&index=21&list=PLNYkxOF6rcIDP0PqVaJxqNWwIgvoEPzJi)
- [Puppeteer Playground](https://try-puppeteer.appspot.com)
- [Rendertron - headless rendering service](https://render-tron.appspot.com)
- [StartPolymer Playground #1 is simple SEO-friendly template with fragment links.](https://github.com/StartPolymer/playgrounds)

### Searchbots

- [Polymer 2 and Googlebot](https://medium.com/dev-channel/polymer-2-and-googlebot-2ad50c5727dd) - 2017-12

## Tutorials / Guides

- [Build your first Polymer 2 element](https://www.polymer-project.org/2.0/start/first-element/intro)
- [Build your first Polymer 2 app](https://www.polymer-project.org/2.0/start/toolbox/set-up)
- [The Gold Standard Checklist for Web Components](https://github.com/webcomponents/gold-standard/wiki)
- [Flexbox layout guide](https://www.webcomponents.org/element/PolymerElements/iron-flex-layout/page/GUIDE.md)
- [Polymer Cheat Sheets](https://github.com/StartPolymer/polymer-cheat-sheets)

### Style Guides

- [Document your elements](https://www.polymer-project.org/2.0/docs/tools/documentation)
- [Chromium Web Development Style Guide](https://chromium.googlesource.com/chromium/src/+/master/styleguide/web/web.md)
- [Polymer Style Guide](https://github.com/ageapps/polymer-style-guide)
- [FamilySearch Polymer Style guide](https://github.com/fs-webdev/polymer)

### Upgrade Guides

- [Upgrade guide from v1.x to v2.0](https://www.polymer-project.org/2.0/docs/upgrade)
- [Migration guide from v0.5 to v1.0](https://www.polymer-project.org/1.0/docs/migration)

## Case Studies

- [Polymer @ YouTube - The YouTube site is comprised of over 400 web components.](https://www.youtube.com/watch?v=tNulrEbTQf8) - 2017-08
- [Santa Tracker as a PWA](https://developers.google.com/web/showcase/2017/santa) - 2017-03
- [NET-A-PORTER](https://developers.google.com/web/showcase/2016/net-a-porter) - 2016-04
- [Creating a Lightsaber with Polymer](https://developers.google.com/web/showcase/case-study/lightsaber) - 2015-12

## Integration with other frameworks

- [Aurelia + Polymer integration](http://aurelia.io/hub.html#/doc/article/aurelia/framework/latest/integrating-with-polymer)
- [How to use Polymer with Webpack](https://medium.com/dev-channel/how-to-use-polymer-with-webpack-b41812d78b15) - 2017-07

### GraphQL

- [Polymer Apollo Integration](https://github.com/aruntk/polymer-apollo)

## Articles

- [Learn Polymer - From Beginner to Expert](https://medium.com/collaborne-engineering/learn-polymer-from-beginner-to-expert-6581be9b6982) - 2018-04
- [How to combine Web Components with Storybook](https://medium.com/@stijn.koopal/how-to-combine-web-components-with-storybook-a-match-made-in-heaven-9d9939eedc76) - 2018-03
- [Make Polymer 2.0 Web Components work on IE11 and Edge](https://medium.com/@andrejsabrickis/make-polymer-2-0-web-components-work-on-ie11-and-edge-8d82eb1b9e5e) - 2017-12
- [Thoughts on Polymer 3.0 after Polymer Summit 2017](https://www.captaincodeman.com/2017/09/08/thoughts-on-polymer-30-after-polymer-summit-2017) - 2017-09
- [Building Polymer apps with gulp](https://medium.com/collaborne-engineering/building-polymer-app-with-gulp-dee266d348df) - 2017-08
- [Localize Polymer apps with translation platform](https://medium.com/collaborne-engineering/localize-polymer-apps-with-translation-platform-46a2acb9373b) - 2017-08
- [Shadow DOM: fast and encapsulated styles](https://meowni.ca/posts/shadow-dom/) - 2017-08
- [Polymer + Cordova: Can’t access device images](https://medium.com/collaborne-engineering/polymer-cordova-cant-access-device-images-a2059fb979ab) - 2017-08
- [Project Structure for Using Redux with Polymer 2.0](https://www.captaincodeman.com/2017/07/19/project-structure-for-using-redux-with-polymer-20) - 2017-07
- [Managing State in Polymer 2.0 - Beyond Parent / Child Binding](https://www.captaincodeman.com/2017/07/06/managing-state-in-polymer-20-beyond-parent-child-binding) - 2017-07
- [Polymer anti-patterns: Prevent leaking internals between components](https://medium.com/collaborne-engineering/polymer-anti-patterns-prevent-leaking-internals-between-components-8b22d2b9cace) - 2017-07
- [Don’t use jQuery plugins with Shadow DOM](https://medium.com/dev-channel/dont-use-jquery-plugins-with-shadow-dom-e161f1891511) - 2017-06
- [Polymer 2.0 pitfalls: key bindings (Accessibility)](https://medium.com/collaborne-engineering/polymer-2-0-pitfalls-key-bindings-accessibility-75865bd7101c) 2017-06
- [Polymer 2.0 + IE11: Don’t use <dom-bind> in your index.html](https://medium.com/collaborne-engineering/polymer-2-0-ie11-dont-use-dom-bind-in-your-index-html-846b0127acf5) - 2017-06
- [Polymer Tips: Prevent Inactive Views Responding To Other Route Changes](https://www.captaincodeman.com/2017/05/18/polymer-tips-prevent-inactive-views-responding-to-other-route-changes) - 2017-05
- [Custom Elements That Work Anywhere](https://medium.com/dev-channel/custom-elements-that-work-anywhere-898e1dd2bc48#.m5ict2tce) - 2016-11
- [Property Change Observers in Polymer](http://www.ericfeminella.com/blog/2016/01/06/property-change-observers-in-polymer/) - 2016-01
- [Building web components using ES6 classes](https://www.polymer-project.org/1.0/articles/es6.html) - 2015-09
- [Live-reload for Polymer Chrome Apps](http://codingwithgerwin.blogspot.it/2015/07/live-reload-for-polymer-chrome-apps.html) - 2015-06
- [Guitar Tuner with Web audio API](https://aerotwist.com/blog/guitar-tuner/) - 2015-06
- [Polymer for the Performance-obsessed](https://aerotwist.com/blog/polymer-for-the-performance-obsessed/) - 2015-06
- [What is shady DOM](https://www.polymer-project.org/1.0/articles/shadydom.html) - 2015-05
- [Using Polymer webcomponents with Angular JS](http://jcrowther.io/2015/05/26/using-polymer-webcomponents-with-angular-js/) - 2015-05
- [Setting up your Production-ready Polymer 1.0 Application Development](http://blogs.walkingtree.in/2015/06/29/setting-up-your-production-ready-polymer-1-0-application-development/) - 2015-06
- [Dynamically Loading Elements & ES6 Modules](http://addyosmani.github.io/webcomponent-samples/polymer/modules/)
- [The Cost of Frameworks](https://aerotwist.com/blog/the-cost-of-frameworks/) - 2015-11

## Videos

- [Polycasts](https://www.youtube.com/playlist?list=PLOU2XLYxmsII5c3Mgw6fNYCzaWrsM3sMN)
- [Building a Polymer 2 Progressive Web App with the Polymer CLI](https://www.youtube.com/watch?v=e_7i9evLJpw) - 2017-07
- [State of Polymer Jan '17 at This.JavaScript with Rob Dodson](https://www.youtube.com/watch?v=UUljsYOdt1Y) - 2017-02
- [Make your Polymer web-app Progressive](https://slideslive.cz/38899314/make-your-polymer-webapp-progressive) - 2016-11
- [Learn Polymer 1.0](https://www.youtube.com/playlist?list=PLPaj_o9gjMYll0sSb47TrzQCjIo5iqQZm) - 2015
- [Level up Tutorials](https://www.youtube.com/playlist?list=PLLnpHn493BHGhoGAb2PRKzv4Zw3QoatK-) - 2015

### Polymer Summit

- [Polymer Summit 2017](https://www.youtube.com/playlist?list=PLNYkxOF6rcIDP0PqVaJxqNWwIgvoEPzJi) - 2017-08
- [Polymer Summit 2016](https://www.youtube.com/playlist?list=PLNYkxOF6rcICc687SxHQRuo9TVNOJelSZ) - 2016-10
- [Polymer Summit 2015](https://www.youtube.com/playlist?list=PLNYkxOF6rcICdISJclfQhj2S8QZGjXV8J) - 2015-10

### Progressive Web App Summit

- [Progressive Web App Summit 2016](https://www.youtube.com/playlist?list=PLNYkxOF6rcIAWWNR_Q6eLPhsyx6VvYjVb) - 2016-06

### Chrome Dev Summit

- [Chrome Dev Summit 2017](https://www.youtube.com/playlist?list=PLNYkxOF6rcICUD5nBfRdAR6Fveosnqa5m) - 2017-10
  - [End-to-End Polymer Apps with the Modern Web Platform](https://www.youtube.com/watch?v=Wu2GCRkDecI&list=PLNYkxOF6rcICUD5nBfRdAR6Fveosnqa5m&index=18)
  - [lit-HTML](https://www.youtube.com/watch?v=Io6JjgckHbg&list=PLNYkxOF6rcICUD5nBfRdAR6Fveosnqa5m&index=19)
- [Chrome Dev Summit 2016](https://www.youtube.com/playlist?list=PLNYkxOF6rcIBTs2KPy1E6tIYaWoFcG3uj) - 2016-11
  - [Web Components and Polymer](https://www.youtube.com/watch?v=Ihdp63FaRKA&index=15&list=PLNYkxOF6rcIBTs2KPy1E6tIYaWoFcG3uj)
  - [Planning for Performance: PRPL](https://www.youtube.com/watch?v=RWLzUnESylc&index=25&list=PLNYkxOF6rcIBTs2KPy1E6tIYaWoFcG3uj)
- [Chrome Dev Summit 2015](https://www.youtube.com/playlist?list=PLNYkxOF6rcICcHeQY02XLvoGL34rZFWZn) - 2015-11
  - [Polymer - State of the Union](https://www.youtube.com/watch?v=lck68wyVUo4&index=9&list=PLNYkxOF6rcICcHeQY02XLvoGL34rZFWZn)
  - [Building Progressive Web Apps with Polymer](https://www.youtube.com/watch?v=g7f1Az5fxgU&index=11&list=PLNYkxOF6rcICcHeQY02XLvoGL34rZFWZn)

### Google I/O

- [Polymer @ Google I/O 2017](https://www.youtube.com/playlist?list=PL_c6rbXV248du6m1VJABo32mP7sXWVb4m) - 2017-05
- [Chrome and Web @ Google I/O 2017](https://www.youtube.com/playlist?list=PLNYkxOF6rcICniLJ2rfj0FexlA-9zmJJE) - 2017-05
- [Polymer @ Google I/O 2016](https://www.youtube.com/playlist?list=PLNYkxOF6rcIDnSm7bZRJC36Ca1DYXSQ70) - 2016-05
- [Web and Chrome @ Google I/O 2016](https://www.youtube.com/playlist?list=PLNYkxOF6rcIDz1TzmmMRBC-kd8zPRTQIP) - 2016-05
- [Polymer and modern web APIs: In production at Google scale @ Google I/O 2015](https://www.youtube.com/watch?v=fD2As5RmM8Q) - 2015-05

## Templates

- [Polymer Starter Kit](https://github.com/Polymer/polymer-starter-kit)
- [Polymer Starter Kit Plus](https://github.com/StartPolymer/polymer-starter-kit-plus)
- [Polymer News](https://news-docs.polymer-project.org)
- [Polymer Shop](https://github.com/Polymer/shop)
- [Polymer Hacker News client v2](https://github.com/Polymer/hn-polymer-2)
- [Polymer Hacker News client v3 (lit-html + Redux)](https://github.com/PolymerLabs/polymer-redux-hn)

## Tools

- [Polymer CLI](https://github.com/Polymer/polymer-cli) - Command-line tool for initialization, serving, linting, testing, building, azalyzing.
- [Polymer Chrome DevTools Extension](https://github.com/PolymerLabs/polydev)
- [Polymer Ready Chrome Extension](https://chrome.google.com/webstore/detail/polymer-ready/aaifiopbmiecbpladpjaoemohhfjcbdk) - Show an icon in the address bar when it detects some Polymer and Custom components.
- [Polymer Iconset Generator](https://poly-icon.appspot.com)
- [Polymer Magic Server](http://polygit.org) - The Magic Server serves files directly from github (via `cdn.rawgit.com`) in a manner that is compatible with HTML Imports natural deduplication feature.
- [StartPolymer CDN](https://github.com/StartPolymer/cdn)
- [On-the-fly Polymer style modules](https://github.com/PolymerLabs/polystyles)
- [StartPolymer Toolbox](https://github.com/StartPolymer/toolbox) - Hot Reloading and more tools...

## Editor Plugins

[Polymer Editor Plugins @ Polymer Summit 2016](https://www.youtube.com/watch?v=guYHn0P8bKQ&feature=youtu.be&t=36m)

### Atom

- [Polymer IDE](https://atom.io/packages/polymer-ide)
- [Polymer Snippets](https://atom.io/packages/polymer-snippets)
- [Polymer Syntax](https://atom.io/packages/language-polymer)

### VS Code

- [Polymer IDE](https://marketplace.visualstudio.com/items?itemName=polymer.polymer-ide)
- [Polymer Snippets](https://marketplace.visualstudio.com/items?itemName=chimon2000.polymer-snippets)
- [Polymer 2 Snippets](https://marketplace.visualstudio.com/items?itemName=justinribeiro.Polymer2Snippets)
- [Polymer Syntax](https://marketplace.visualstudio.com/items?itemName=jonwolfe.language-polymer)
- [lit-html](https://marketplace.visualstudio.com/items?itemName=bierner.lit-html)

### Sublime Text

- [Polymer IDE](https://github.com/Polymer/polymer-sublime-plugin)
- [Polymer & Web Component Snippets](https://packagecontrol.io/packages/Polymer%20%26%20Web%20Component%20Snippets)
- [Polymer Syntax](https://packagecontrol.io/packages/Polymer%20Syntax)

## Testing

- [Web components tester](https://github.com/Polymer/web-component-tester) - Makes testing your web components a breeze!
- [test-fixture](https://github.com/PolymerElements/test-fixture) - Element that can simplify the exercise of consistently resetting a test suite's DOM.
- [iron-test-helpers](https://github.com/PolymerElements/iron-test-helpers) - Utility classes to make testing easier.
- [Testing Tips](https://medium.com/google-developer-experts/polymer-testing-tips-f217ba94a64) - 2016-01

## Notable projects 

- [Polymer Projects](https://github.com/abdonrd/PolymerProjects) - List of websites and apps built with Polymer.
- [Built with Polymer](http://builtwithpolymer.org)
- [Who's using Polymer?](https://github.com/Polymer/polymer/wiki/Who's-using-Polymer%3F)
- [Gold Elements Demo](https://github.com/notwaldorf/polymer-gold-elements-demo)
- [Google Analytics Dashboard](https://ga-dev-tools.appspot.com/polymer-elements/)
- [Google I/O 2015](https://github.com/GoogleChrome/ioweb2015) - v0.5
- [Guitar Tuner](https://github.com/GoogleChrome/guitar-tuner)
- [Chat Demo](https://github.com/kevinpschaaf/chat-view-paper)
- [Padlock](https://github.com/MaKleSoft/padlock) - A minimalist open source password manager.
- [Scan Chrome OS App](https://github.com/beaufortfrancois/scan-chrome-app)
- [SFTP File System Chrome OS App](https://github.com/yoichiro/chromeos-filesystem-sftp)
- [Snapdrop](https://snapdrop.net) - The easiest way to transfer files across devices.
- [TimeDoser](https://github.com/DaniGuardiola/TimeDoser/) - Pomodoro Timer
- [Voice Memos](https://aerotwist.com/blog/voice-memos/)

## Polymer Authors

- [GitHub People](https://github.com/orgs/Polymer/people)
- [Polymer Summit Speakers](https://summit.polymer-project.org/speakers)

## Other awesome resources

- [Awesome Elements](https://github.com/StartPolymer/awesome-elements)
- [Awesome Web Components](https://github.com/obetomuniz/awesome-webcomponents)
- [Awesome Service Workers](https://github.com/StartPolymer/awesome-service-workers)
- [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

---

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

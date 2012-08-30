# frontend-toolbox

Actively maintained list of useful web developments tools, libraries, assets and any other open-source goodies.

Shamelessly aggregated from the following resources:

- [Brunch plugin wiki](https://github.com/brunch/brunch/wiki/Plugins)
- [Tooling & The Webapp Development Stack](https://gist.github.com/2713513): Notes from a talk by Paul Irish
- [DailyJS](http://dailyjs.com/): Excellent JavaScript blog
- [JavaScript Jabber Podcase](http://javascriptjabber.com/): Kick-ass JavaScript podcast
- [Smashing Magazine](http://www.smashingmagazine.com/): Best web-development magazine
- [Hipster Dev Stack](http://hipsterdevstack.tumblr.com/): A curated directory of artisanal development tools that we used to like before they went mainstream.
- [NetTutsPlus](http://net.tutsplus.com/): Web development tutorials, from beginner to advanced
- [Sublime Text Workflow That Beats Coda and Espresso](http://tarantsov.com/blog/2012/02/sublime-text-workflow-that-beats-coda-and-espresso/)

_"★" recommended and currently used by the maintainer_

## General

- ★ [HTML5 Spec for Web Developers](http://developers.whatwg.org/): This specification is intended for authors of documents and scripts that use the features defined in this specification.
- [DocHub](http://dochub.io/): Alternative documentation repository for: CSS, HTML, JavaScript, DOM, jQuery, PHP, Python
- [Hypertext Transfer Protocol -- HTTP/1.1](http://www.w3.org/Protocols/rfc2616/rfc2616.html): you should read through it at least once

### Compatibility

- [When can I use...](http://caniuse.com/): Compatibility tables for support of HTML5, CSS3, SVG and more in desktop and mobile browsers.
- [HTML5 & CSS3 Readiness](http://html5readiness.com/): We don't have to wait for entire specs to be completed, we can start using some hawtness now.
- [HTML5 Please](http://html5please.com/): Use the new and shiny responsibly.

### Documentation

- ★ [Docco](http://jashkenas.github.com/docco/): Quick and dirty, literate-programming documenation generator
- [Groc](http://nevir.github.com/groc/): is an attempt to further enhance the idea [of Docco]

### Build Tools, Assemblers, et al

- ★ [Brunch](http://brunch.io/): A lightweight approach to building HTML5 applications with an emphasis on elegance and simplicity.
- ★ [Middleman](http://middlemanapp.com/): a static site generator using all the shortcuts and tools in modern web development.
- ★ [Grunt](http://gruntjs.com/): a task-based command line build tool for JavaScript projects
- ★ [Yeoman](http://yeoman.io/): a robust and opinionated client-side stack, comprised of tools and frameworks that can help developers quickly build beautiful web applications.
- [LiveReload](http://livereload.com/): CSS edits and image changes apply live. CoffeeScript, SASS, LESS and others just work. (OSX only)
- [CodeKit](http://incident57.com/codekit/): CodeKit helps you build websites faster and better. (OSX only)
- [Lumbar](http://walmartlabs.github.com/lumbar/): Lumbar is a js-build tool that takes a general codebase and list of platforms to generate modular platform specific applications. (from Walmart Labs)

## JavaScript

- [Modernizr](http://modernizr.com/): detects HTML5 and CSS3 features in the user’s browser.
- [Underscore](http://underscorejs.org/): JavaScript utility belt
- [JSON3](http://bestiejs.github.com/json3/): JSON parser/stringifier

### jQuery

- [jQuery](http://jquery.com/): Write less; do more.
- [Zepto](http://zeptojs.com/): jQuery alternative for mobile apps (super light-weight)
- [jQAPI](http://jqapi.com/): Alternative jQuery Documentation

### [Transcompilation](http://en.wikipedia.org/wiki/Source-to-source_compiler) Languages

- ★[CoffeeScript](http://coffeescript.org/): a little language that compiles into JavaScript
- [IcedCoffeeScript](http://maxtaco.github.com/coffee-script/): drop-in replacement interpreter for CoffeeScript with **async control flow semantics**.
- [LiveScript](http://gkz.github.com/LiveScript/): aims for increased expressiveness and code beauty, while adding features to assist in functional style programming, imperative and object oriented programming, and has an optional class system with inheritance, calls to super, and more.
- [Roy](http://roy.brianmckenna.org/): an experimental programming language that targets JavaScript and tries to meld JavaScript semantics with some features common in static functional languages.

### Linters

- [JSHint](http://www.jshint.com/): JSHint is a tool to detect errors and potential problems in JavaScript code.

### Frameworks ([MV* et al](http://lostechies.com/derickbailey/2011/12/23/backbone-js-is-not-an-mvc-framework/))

- [Backbone.js](http://documentcloud.github.com/backbone)
  - [Backbone Forms](https://github.com/powmedia/backbone-forms)
  - [backbone-deep-model](https://github.com/powmedia/backbone-deep-model)
  - [Backbone-Nested](http://afeld.github.com/backbone-nested/)
  - [Backbone.Memento](https://github.com/derickbailey/backbone.memento)
  - [Backbone.actAs.Mementoable](https://github.com/iVariable/Backbone.actAs.Mementoable)
  - [Backbone.actAs.Configurable](https://github.com/iVariable/Backbone.actAs.Configurable)
  - [Backbone.Articulation](https://github.com/kmalakoff/backbone-articulation)
    - [underscore.awesomeer](https://github.com/kmalakoff/underscore-awesomer)
  - [Backbone.Validations](http://github.com/n-time/backbone.validations)
  - [Backbone.Validation](http://github.com/thedersen/backbone.validation)
  - [Backbone.Validator](http://github.com/toddself/Backbone.Validator)
  - [Backbone.ModelRef](https://github.com/kmalakoff/backbone-modelref)
  - [workflow.js](https://github.com/kendagriff/workflow.js)
  - [Backbone Dotattr](https://github.com/amccloud/backbone-dotattr)
  - [Backbone.Mutators](https://github.com/asciidisco/Backbone.Mutators)
  - [Backbone.Chosen](https://github.com/asciidisco/Backbone.Chosen)
  - [Backbone.localStorage](https://github.com/jeromegn/Backbone.localStorage)
  - [backbone.couchdb.js](https://github.com/pyronicide/backbone.couchdb.js)
  - [Small Backbone ORM](https://github.com/juggy/backbone-orm)
  - [Backbone.ioBind](https://github.com/logicalparadox/backbone.iobind)
  - [Backbone-websql](https://github.com/MarrLiss/backbone-websql)
  - [Backbone-slet](https://github.com/jrs2ea/backbone.slet)
  - [Backbone.SharePoint](https://github.com/lstak/Backbone.SharePoint)
  - [Backbone.SAP](https://github.com/lstak/Backbone.SAP)
  - [Backbone.Offline](https://github.com/Ask11/backbone.offline)
  - [Backbone.Rpc](https://github.com/asciidisco/Backbone.Rpc)
  - [Ligament](https://github.com/dbrady/ligament.js)
  - [Backbone-relational](https://github.com/PaulUithol/Backbone-relational)
  - [Backbone-associations](https://github.com/dhruvaray/backbone-associations)
  - [Backbone.actAs.Paginatable](https://github.com/iVariable/Backbone.actAs.Paginatable)
  - [Nesting.js](https://gist.github.com/1610397)
  - [Backbone Query](https://github.com/davidgtonge/backbone_query)
  - [Query Engine](https://github.com/bevry/query-engine)
  - [LayoutManager](https://github.com/tbranyen/backbone.layoutmanager)
  - [Backbone.Marionette](https://github.com/derickbailey/backbone.marionette)
  - [Yabbe (Yet Another Backbone Binding Exension)](https://github.com/tantaman/yabbe)
  - [Synapse](https://github.com/bruth/synapse)
  - [Backbone.ModelBinder.js](https://github.com/theironcook/Backbone.ModelBinder)
  - [Backbone Bindings](https://github.com/amccloud/backbone-bindings)
  - [Backbone.ModelBinding](https://github.com/derickbailey/backbone.modelbinding)
  - [Knockback.js](https://github.com/kmalakoff/knockback)
  - [Backbone on the Couch](http://tomphilip.me/index.php/backbone-on-the-couch/)
  - [ProxyDollar](https://github.com/h4rry/backbone-proxyDollar)
  - [Backbone.declarative](https://github.com/Codecademy/backbone.declarative)
  - [outback.js](https://github.com/politician/outback)
  - [Backrub](https://github.com/juggy/backrub)
  - [Builder (DOM Builder for Backbone Views)](https://github.com/syntacticx/builder)
  - [Slickback(integration with SlickGrid)](http://github.com/teleological/slickback)
  - [Vienna IKS Editables](http://bergie.github.com/VIE/)
  - [Backbone.Aura](https://github.com/addyosmani/backbone-aura)
  - [jQuery Mobile Routing](https://github.com/azicchetti/jquerymobile-router)
  - [Before/After Filters](https://github.com/angelo0000/backbone_filters)
    - [[https://github.com/boazsender/backbone.routefilter]]
  - [Query Parameters](https://github.com/jhudson8/backbone-query-parameters)
  - [Backbone Boilerplate](https://github.com/tbranyen/backbone-boilerplate)
  - [Backbone.CQRS](https://github.com/jamuhl/backbone.CQRS)
  - [Capt by Ben Nolan](http://bennolan.com/2010/12/13/capt-a-tool-for-backbone.html)
  - [Mixin.js](https://github.com/kmalakoff/mixin)
  - [Backbone Module](https://github.com/juggy/backbone-module) (Module loader for Backbone apps)
  - [Singool.js](http://fahad19.github.com/singool/)
  - [Backbone-Traversal](https://github.com/dgreisen/Backbone-Traversal)
  - [Backbone.Analytics: Drop-In Google Analytics For Backbone's Router](https://github.com/kendagriff/backbone.analytics)
  - [Backbone-Callbacks: Node.js style callbacks for asynchronous methods](https://github.com/lorenwest/backbone-callbacks)
  - [Backbone.jFeed: RSS/ATOM Feeds For Collections](https://github.com/kendagriff/backbone.jfeed)
  - [Cleaning Up And Preventing Memory Leaks With Your Views](http://lostechies.com/derickbailey/2011/09/15/zombies-run-managing-page-transitions-in-backbone-apps/)
  - [Thingy-Client](https://github.com/mlanza/thingy-client)
  - [Backbone (adapted for MooTools)](https://github.com/jeromegn/backbone-mootools)
  - [Backbone-Factory](https://github.com/SupportBee/Backbone-Factory)
  - [Backbone.StateMachine](https://github.com/sebpiq/backbone.statemachine)
  - [Backbone.Shortcuts](https://github.com/bry4n/backbone-shortcuts)
    - [keymaster.js](https://github.com/madrobby/keymaster)
  - [Backbone Tastypie](https://github.com/amccloud/backbone-tastypie)
  - [Backbone Interface](https://github.com/luke-siedle/backbone-interface)
- [Ember.js](http://emberjs.com)
  - [ember-controls](https://github.com/emberjs-addons/ember-controls)
  - [sproutcore-statechart](https://github.com/emberjs-addons/sproutcore-statechart)
  - [sproutcore-utils](https://github.com/emberjs-addons/sproutcore-utils)
  - [sproutcore-datetime](https://github.com/emberjs-addons/sproutcore-datetime)
  - [sproutcore-routing](https://github.com/emberjs-addons/sproutcore-routing)
  - [sproutcore-datastore](https://github.com/emberjs-addons/sproutcore-datastore)
  - [sproutcore-touch](https://github.com/emberjs-addons/sproutcore-touch)
  - [sproutcore-ui](https://github.com/emberjs-addons/sproutcore-ui)
  - [sproutcore-statechart](https://github.com/emberjs-addons/sproutcore-statechart)
  - [etgryphon/stativus](https://github.com/etgryphon/stativus)
  - [capitainetrain/ember-addons : A collection of addons for Ember.js framework](https://github.com/capitainetrain/ember-addons)
  - [Port of the Sproutcore 1.7 browser detection to Ember.js](https://github.com/ud3323/ember-browserdetection)
  - [ember-i18n](https://github.com/zendesk/ember-i18n)
  - [ember-layout](https://github.com/ghempton/ember-layout)
  - [ember-routemanager](https://github.com/ghempton/ember-routemanager)
  - [ember-facebook](https://github.com/luan/ember-facebook)
  - [ember-formbuilder](https://github.com/luan/ember-formbuilder)
  - [ember-bootstrap](https://github.com/jzajpt/ember-bootstrap)
  - [Flash message system for Ember.js](https://github.com/cheapRoc/ember-flash)
  - [EmberJs Mix with POST, PUT and DELETE methods](https://github.com/beautifulnode/ember.request)
  - [pagination](https://github.com/interline/travelstar-pagination)
  - [ember-memento - Undo/Redo functionality for Ember.Object's](https://github.com/pangratz/ember-memento)
  - [ember-history - Undo/Redo implementation with a global history for Ember.js](https://github.com/ignasbernotas/ember-history)
  - [ember-forms - Easy creation of forms and extracting their data](https://github.com/codegram/ember-forms)
  - [A data library for ember.js](https://github.com/wiredprairie/ember-ezdata)
  - [ember with jQuery Mobile](https://github.com/LuisSala/emberjs-jqm)
  - [ember-titanium](https://github.com/ebryn/ember-titanium)
  - [Mobile Kit for ember.js](https://github.com/ppcano/ember-mk)
- [AngularJS](http://angularjs.org)
- [Spine](http://spinejs.com)
- [KnockoutJS](http://knockoutjs.com) (MVVM)
- [Dojo](http://dojotoolkit.org)
- [YUI](http://yuilibrary.com)
- [Batman.js](http://batmanjs.org)
- [Closure](http://code.google.com/closure/library/)
- [Agility.js](http://agilityjs.com)
- [Knockback.js](http://kmalakoff.github.com/knockback)
- [Google Web Toolkit](https://developers.google.com/web-toolkit/)
- [CanJS](http://canjs.us)
- [Maria.js](https://github.com/petermichaux/maria)
- [cujo.js](http://cujojs.github.com)
- [Meteor](http://meteor.com)
- [Derby](http://derbyjs.com)
- [SocketStream](http://www.socketstream.org) + [jQuery](http://jquery.com)
- [Ext.js](http://www.sencha.com/products/extjs)
- [Sammy.js](http://sammyjs.org)
- [JavaScriptMVC](http://javascriptmvc.com)
- [Stapes.js](http://hay.github.com/stapes)
- [Epitome](http://dimitarchristoff.github.com/Epitome)
- [TroopJS](https://github.com/troopjs)
- [soma.js](http://somajs.github.com/somajs)
- [DUEL](https://bitbucket.org/mckamey/duel/wiki/Home)
- [Fidel](https://github.com/jgallen23/fidel)
- [Olives](https://github.com/flams/olives)
- [PlastronJS](https://github.com/rhysbrettbowen/PlastronJS)
- [Dijon](https://github.com/creynders/dijon-framework)
- [rAppid.js](http://www.rappidjs.com)
- [o_O](http://weepy.github.com/o_O)
- [Fun](https://github.com/marcuswestin/fun)
- [KnockoutJS](http://knockoutjs.com) + [RequireJS](http://requirejs.org) (using AMD)
- [AngularJS](http://angularjs.org) + [RequireJS](http://requirejs.org) (using AMD)
- [AngularJS](http://angularjs.org) (optimized)
- [Backbone.xmpp](https://github.com/ggozad/Backbone.xmpp)

## CSS

- [CSS3.info](http://www.css3.info/): All you ever needed to know about CSS3
- [CSS3 Please](http://css3please.com/): The Cross-Browser CSS3 Rule Generator
- [Semantic Grid System](http://semantic.gs/): Page layout for tomorrow (SCSS, LESS, Stylus)

### Preprocessors

- [Stylus](http://learnboost.github.com/stylus/): Expressive, dynamic, robust CSS
  - [Nib](https://github.com/visionmedia/nib)
- [Sass](http://sass-lang.com/): Sass is an extension of CSS3, adding nested rules, variables, mixins, selector inheritance, and more.
  - [Compass](http://compass-style.org/): Compass is an open-source CSS Authoring Framework.
  - [Susy](http://susy.oddbird.net/):Responsive grids for Compass.

## Editors

### Sublime Text 2

Install and use [Sublime Text 2 Package Control](http://wbond.net/sublime_packages/package_control) for these and other plugins.

- ★ [ZenCoding](https://github.com/sublimator/ZenCoding): editor plugin for high-speed HTML coding and editing
- ★ [Markdown Preview](https://github.com/revolunet/sublimetext-markdown-preview): A simple plugin to help you preview your **markdown** files; works with _LiveReload_.
- ★ [LiveReload](https://github.com/dz0ny/LiveReload-sublimetext2): A web browser page reloading plugin.
- ★ [Sidebar Enhancements](https://github.com/titoBouzout/SideBarEnhancements): Enhancements to Sublime Text sidebar. Files and folders.
- ★ [SublimeREPL](https://github.com/wuub/SublimeREPL):run an interpreter inside ST2
- ★ [Git](https://github.com/kemayo/sublime-text-2-git): Plugin for some git integration
- ★ [SublimeLinter](https://github.com/SublimeLinter/SublimeLinter): Inline lint highlighting
- ★ [JsFormat](https://github.com/jdc0589/JsFormat): javascipt formatting plugin (prettifier)
- [Sublime Prefixr](http://wbond.net/sublime_packages/prefixr): run CSS through the [Prefixr](http://prefixr.com/) API
- [Search StackOverflow](https://github.com/ericmartel/Sublime-Text-2-Stackoverflow-Plugin): Simple search on Stack Overflow utility

#### Themes (TextMate or SublimeText)

- [NodeJS](http://textmatetheme.com/node-js): dark
- [Tomorrow](https://github.com/chriskempson/tomorrow-theme): multiple, dark/light
- [Django](https://code.djangoproject.com/attachment/wiki/TextMate/Django.tmTheme.zip): dark green

## Design

### Icons

- ★ [FontAwesome](http://fortawesome.github.com/Font-Awesome/): The iconic font designed for use with Twitter Bootstrap
- [IconSweets](http://iconsweets2.com/): a huge FREE icon set containing over a 1,000+ icon
- [Glyphicons](http://glyphicons.com/): designed primarily for toolbars and navigation bars in OS X Lion, the application for iPhone, iPhone 4, iPad and other Apple devices. (CC license)
- [Glyphish](http://www.glyphish.com/): Free set published under a Creative Commons Attribution license
- [FamFamFam](http://www.famfamfam.com/lab/icons/): oldie, but goodie
- [LED Icon Set](http://led24.de/iconset/): .png icons make a professionally looking small icon set and are totally free in commercial and open source apps / websites.
- [Fugue Icons](http://p.yusukekamiyamane.com/): 3,480 icons are included in PNG format (16x16 pixels) + bonus. (CC license)

### Typography

- [Beautiful Web Type](http://hellohappy.org/beautiful-web-type/): A showcase of the best typefaces from the Google web fonts directory.
- [FontBomb](http://fontbomb.ilex.ca/): To blow up other websites, drag and drop this link fontBomb to your favorites bar

### Textures

- [Noise Texture Generator](http://www.noisetexturegenerator.com/)

#### Favicons

- [Piecon](http://lipka.github.com/piecon/): Pie charts in your favicon!

## Education

- [CodeAcademy](http://www.codecademy.com/): the easiest way to learn to code. It's interactive, fun, and you can do it with your friends.
- [NCZOnline: 'Computer Science'](http://www.nczonline.net/blog/tag/computer-science/): Nicholas C. Zakas presents computer science concepts using JavaScript as language of choice
- [Stanford OpenClassroom](http://openclassroom.stanford.edu/MainFolder/HomePage.php): Full courses. Short Videos. Free for everyone.

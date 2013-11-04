# Cluster

Alpha Version 0.3.0

## About

Cluster is a modular and customisable web design framework written with the full power of SCSS. Cluster makes it super easy to create a lightweight design framework that is custom built for your latest project using minimal effort and time.

Cluster includes a healthy set of default styles but is designed to be customised.

##Why Cluster?

I wrote Cluster because I found other frameworks to be bloated and wasteful, often including a lot of styles that were not used or needed.

Another reason I wrote cluster was so I could mix and match bits of my favourite frameworks and other reusable design patterns.

For example - don't use navbars in your design? No problem, just comment out the _navigation.scss file in the main cluster.scss. The main cluster.scss file acts like a controller (for those familiar for MVC) and provides a central place to manage parts of the framework.

I figured if I could make it easy to customise people would create their own reusable design patterns and avoid the typical problem of all websites of a framework all looking the same.

##How to get set up

You'll need a few things, I'll share my workload with you here but there are many other ways of working with Cluster.

1. Grab the files, either download the zip or clone
2. Install SCSS/SASS my favourite install instructions [can be found here](http://sass-lang.com/install "Imstall Sass instruction from Sass HQ")
3. Include **src/css/cluster.css** in the head of your html file
3. Make global changes to the **src/scss/cluster.scss** file
4. Project specific styles should be added to **src/scss/project.scss** (this file will be loaded last)
5. If you want code highlighting add **src/css/syntax/highlight.min.css** to the head of your page and **src/js/highlight.min.js** to the bottom (just before the closing body tag)

###Pro tip: Compiling SCSS on the go for free

I use a free application on my mac called [Prepros](http://alphapixels.com/prepros/ "Use Prepros to compile your SCSS") to compile SCSS on the fly. Prepros watches your project folder for changes to your SCSS files and compiles them everytime you save the file. There's also a paid version but the free version works great.

###Code highlighting: how to add languages

The current version of the highlight.min.js script only highlights HTML (I did this to save space) check out [Prism.js](http://prismjs.com/download.html "Prism.js custom download") to make your own custom build and add highlighting for other languages and add different highlighting css themes. All you'll need to do is rename your outputted JS file to highlight.min.js (if using a minified version) or alternatively update your reference to the highlighting js file in your web page.

##To do

1. Documentation
2. Icons (fix or swap to a new default icon pack)
2. More complicated form styles
3. Table styles
4. Media styles
5. Resuable examples

## Attribution

Special thanks to a couple of frameworks and open source projects for their hard work or inspiration:

- [Pure CSS by Yahoo](http://purecss.io "Pure CSS")
- [Bootstrap](http://getbootstrap.com "Bootstrap")
- [Prism.js](http://prismjs.com "Prism.js")
- [Entypo Icons](http://entypo.com "Entypo Icons"")
- [Dalek Ipsum](http://dalekipsum.com/ "Dalek Ipsum")
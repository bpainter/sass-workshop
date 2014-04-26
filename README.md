# Modular & Maintainable Sass Workshop

So you can start tinkering immediately you should create an account at [CodePen.io](http://codepen.io/collection/ocevd). All examples will be available during the workshop so you can follow along and experiment.

A secondary set of static files will be provided after the workshop. You can download them from [Github.com](http://github.com/bpainter/sass-workshop).

## Installation

We won't spend any time during the workshop doing installation. It just never works and takes up too much time. After the workshop I'm happy to help. Otherwise, there are two ways that you can start using Sass:

1. **Purchase a GUI Application** – If you're using OSX your best bet is to use [CodeKit](http://incident57.com/codekit/) or [Compass.app](http://compass.handlino.com/). For Windows users [Scout](http://mhs.github.io/scout-app/) or [Compass.app](http://compass.handlino.com/) work pretty well.
2. **Use the command line** – If you aren't afraid of the command line then there's a simple guide for Windows and OSX users over at [Adobe.com](http://www.adobe.com/devnet/html5/articles/introduction-to-sass-part-1-installation.html). If you're new to the command line here's a nice [tutorial](http://wiseheartdesign.com/articles/2010/11/12/the-designers-guide-to-the-osx-command-prompt/).

## Workshop Sections

The workshop will be divided up into the following sections:

1. [Frameworks](#frameworks)
2. [Basic](#basic)
3. [Intermediate](#intermediate)
4. [Advanced](#advanced)

### <div id="frameworks">Frameworks</div>

1. [Bourbon](http://bourbon.io/) | [Neat](http://neat.bourbon.io/)
2. [Compass](http://compass-style.org/) | [Susy](http://susy.oddbird.net/)

### <div id="basic">Basic</div>

#### Exercise 1 - Syntax

- [Sass Syntax](http://codepen.io/bpainter/pen/wrdLo)
- [SCSS/Sassy Syntax](http://codepen.io/bpainter/pen/cpdeb)

#### Exercise 2 - Variables

- [Basic Usage](http://codepen.io/bpainter/pen/ntxLb)

#### Exercise 3 - Nesting

- [Native CSS](http://codepen.io/bpainter/pen/IkByq)
- [Overview](http://codepen.io/bpainter/pen/aophg)
- [Inception Rule of 3](http://codepen.io/bpainter/pen/fztwl)

#### Exercise 4 - Parent Selectors:

- [Referencing a Parent](http://codepen.io/bpainter/pen/jHfkz)
- [Tricks with Modernizr](http://codepen.io/bpainter/pen/eIJyh) | [Modernizr Docs](http://modernizr.com/docs/#features-css)

### <div id="intermediate">Intermediate</div>

#### Exercise 5 - Operations

- [Basic Operations](http://codepen.io/bpainter/pen/EmeiL)

#### Exercise 6 - Mixins

- [Simple Mixin](http://codepen.io/bpainter/pen/yAJiE)
- [Complex CSS Version](http://codepen.io/bpainter/pen/mguFy)
- [Complex Sass Version](http://codepen.io/bpainter/pen/fcHIJ)

#### Exercise 7 - @extend 

- [Basic Extend Directive](http://codepen.io/bpainter/pen/rnHgt)

#### Exercise 8 - Placeholders

- [Basic Placeholder](http://codepen.io/bpainter/pen/BDhuf)

#### Exercise 9 - Mixins vs. Extend

- http://codepen.io/bpainter/pen/qKEmL
- http://codepen.io/bpainter/pen/fEirL


### <div id="advanced">Advanced</div>

#### Exercise 10 - Functions

- [Math Functions](http://codepen.io/bpainter/pen/BtIiu)
- [Color Functions](http://codepen.io/bpainter/pen/igGao)

#### Exercise 11 - Control Directives

- [if, else if, else](http://codepen.io/bpainter/pen/nJuHk)
- [each loop](http://codepen.io/bpainter/pen/LaquJ)
- [while loop](http://codepen.io/bpainter/pen/mIvjx)

#### Exercise 12 - Media Queries

- [Basic Media Query](http://codepen.io/bpainter/pen/zjJvG)
- [@content](http://codepen.io/bpainter/pen/rJeLA)

#### Exercise 13 - Maps

- [Basic Map](http://codepen.io/bpainter/pen/Fdpxs)


### <div id="modular-systems">Modular Systems & Pattern Libraries</div>

#### Boilerplates

1. [Foundation](http://foundation.zurb.com/)
2. [Rock Hammer](http://github.com/malarkey/Rock-Hammer)
3. [Bootstrap](http://github.com/jlong/sass-twitter-bootstrap)

#### Custom Systems

##### Creating a Modular System

In order to create a modular system, modules must be:

1. Nestable
2. Combinable
3. Clearfixed
4. Flexible
5. Sepatared by Structure and Aesthetics

##### Pattern Libraries and Rapid Prototyping 

Provide the following:

1. Consistent user experience
2. Consistent aesthetics
3. Reusable architecture
4. Maintainable and tested structure

### LibSass

[LibSass](https://github.com/hcatlin/libsass), C implementation of Sass. Insanely fast, works as a system level library on OSX, Linux and Windows, wrappers for multiple languages.

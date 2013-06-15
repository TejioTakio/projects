## REST + HATEOS (SOA)

http://de.slideshare.net/trilancer/why-hateoas-1547275

## Atomic design

http://de.slideshare.net/bradfrostweb/atomic-design

### Principles

 - Provides a methodology for crafting an effective design system
 - Easily traverse from abstract to concrete
 - Promotes consistency and cohesion
 - Assembles rather than deconstructs

### Definitions 

#### Atoms

 - Building blocks of an interface
 - Cant be broken down any further without losing their meaning
 - Abstract
 - Often not too useful on thei own
 - Good as an at-a-glance reference
 - See all your global styles laid out at one

#### Moleculs

 - Group of atoms bonded together
 - Smallest fundamentals units of a compound
 - More concrete than atoms
 - Encourage a "do one thing and do it well" philosophy
 - Often serve as the backbone for a more complex system

#### Organisms

 - Group of molecules joined together to form a distinct section
 - Complex molecules
 - Can consist of similar and/or different molecule types
 - Encourages creating standalone, portable, resuable components

#### Templates

 - Page-level
 - Mostly comprised of groups of organisms
 - Begin their life as HTML wireframes, increase fidelity over time
 - Client facing. Very concrete
 - Eventually becomes the deliverable / production code

#### Pages

 - Specific instance of a template
 - Highest fidelity. Template content is replaced with real / sample content
 - The hub for most people involved in the process
 - Test the effectiveness of the system
 - Test variations in the template: design / content tweaks, include / exclude organisms, etc

## RESS

Responsive Design + Server Side Components

 - http://de.slideshare.net/4nd3rsen/ress-responsive-design-server-side-components-10084972
 - http://www.netmagazine.com/tutorials/getting-started-ress

## RWD

Responsive Websites, depends on the features of the device, for example Tablet, Smartphones, TVs or Laptops. Part of the base are media queries. 

http://mobile.smashingmagazine.com/2013/05/29/the-state-of-responsive-web-design/

## FBP

Flow-based programming is a way of separating the control flow of software from the actual software logic.

http://noflojs.org/

## BEM

Block, Element, Modifier

http://coding.smashingmagazine.com/2013/02/21/the-history-of-the-bem-methodology/

### Definitions

#### Block

A block is an independent entity, a “building block” of an application. A block can be either simple or compound (containing other blocks)

#### Element

An element is a part of a block that performs a certain function. Elements are context-dependent: they only make sense in the context of the block that they belong to.

#### Modifier

### Guidelines

Place related files together in the same folder, like stylesheets, scripts and images. They made to be a compilation of resuable components.

## SMACSS

Scalable and modular architecture for CSS

http://smacss.com/book/categorizing

### Ideas

Categorizing CSS rules in Base, Layout, Module, State, Theme

 - Base rules: Default element styles
 - Layout rules: Divide the page into sections
 - Modules: reusable, modular parts
 - State rules: State of layout or module
 - Theme rules: alternative look for modules or layouts

## OOCSS

Object oriented CSS

http://coding.smashingmagazine.com/2011/12/12/an-introduction-to-object-oriented-css-oocss/

### Ideas

 - Separation of Structure from Skin
 - Separation of Containers and Content
 
#### Some Guidelines

 - Avoid the descendent selector (i.e. don’t use .sidebar h3)
 - Avoid IDs as styling hooks
 - Avoid attaching classes to elements in your stylesheet (i.e. don’t do div.header or h1.title)
 - Except in some rare cases, avoid using !important
 - Use CSS Lint to check your CSS (and know that it has options and method to its madness)
 - Use CSS grids

## Misc
### Ideas

 - shame.css
 - reset.css / normalize.css
 - Moodboards (roughly design style)
 - Style Tiles (Show style choices)
 - Wireframes (Layout)
 - Prototype (Concrete styles and layouts)
 - Design guide lines
 - Grid layouts

### Pages

 - http://mobiledesignpatterngallery.com/

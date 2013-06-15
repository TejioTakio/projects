## REST + HATEOS (SOA)

## Atomic design

## RESS

## RWD

## FBP

## BEM

Block, Element, Modifier

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

### Ideas

Categorizing CSS rules in Base, Layout, Module, State, Theme

 - Base rules: Default element styles
 - Layout rules: Divide the page into sections
 - Modules: reusable, modular parts
 - State rules: State of layout or module
 - Theme rules: alternative look for modules or layouts

## OOCSS

Object oriented CSS

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
 - reset.css / normalize.css / base.css

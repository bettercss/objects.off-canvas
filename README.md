# Objects.Off-Canvas

The `Off Canvas` module uses the space outside a browser’s viewport to hide elements until users need them.

## Installation

Install via [npm](http://npmjs.org/):
 
 	npm install bettercss-objects-off-canvas
    
## Configuration Variables

### Enable Features

All features are turned off by default. To enable a feature just override the default variable. 

```scss
$bc-o-off-canvas-enable-layout
```

### Others

```scss
$bc-o-off-canvas-width
$bc-o-off-canvas-height
```

## Available Classes

You can view a more in depth description of the classes usage in the source see [_objects.off-canvas.scss](https://github.com/bettercss/objects.off-canvas/blob/master/lib/_objects.off-canvas.scss)

```scss
// Base
.o-off-canvas

// Off Canvas Position
.o-off-canvas--left
.o-off-canvas--right
.o-off-canvas--top
.o-off-canvas--bottom

// Off Canvas Layout Items
.o-off-canvas--layout\@t
.o-off-canvas--layout\@s
.o-off-canvas--layout\@m
```
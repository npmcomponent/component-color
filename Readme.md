*This repository is a mirror of the [component](http://component.io) module [component/color](http://github.com/component/color). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-color`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# color

  RGBA / HSLA color manipulation

## Installation

    $ component install component/color

## API

### .rgba(r, g, b, a)

  Return an `RGBA` object.

### .hsla(h, s, l, a)

  Return an `HSLA` object.

### .RGBA(r, g, b, a)

  The `RGBA` constructor.

### .HSLA(h, s, l, a)

  The `HSLA` constructor.

### RGBA#toRGBA()

  Returns itself.

### HSLA#toRGBA()

  Return the `RGBA` representation.

### RGBA#toHSLA()

  Return the `HSLA` representation.

### HSLA#toHSLA()

  Returns itself.

### RGBA#toString()

  Return the string representation, for example "#f00", or "rgba(255,0,0,.5)".

### HSLA#toString()

  Return the string representation, for example "hsla(0,100,50,1)".

# License

  MIT

  
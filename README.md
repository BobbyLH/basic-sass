# basic-sass


### How to install:

Using **npm**:

```
npm install basic-sass -S
```

Using **yarn**:

```
yarn add basic-sass
```

```scss
@import "basic-sass";
```

## mixin

### media query
#### @include phone {}
#### @include handheld {}
#### @include tablet {}
#### @include laptop {}
#### @include desktop {}
#### @include mobile {}
#### @include pc {}

### icon
#### @include arrow-tip ($position, $width: 2px, $size: 7px, $color: #ccc) {}
#### @include arrow ($position, $width: 2px, $size: 16px, $color: #484848) {}
#### @include pseudoArrow ($position, $width: 2px, $size: 7px, $color: #ccc) {}
#### @include cross ($size: 20px, $bold: 2px, $color: gray, $bgColor: transparent) {}
#### @include add ($size: 14px, $bold: 2px, $color:#fc5832) {}
#### @include menu ($width: 18px, $bold: 2px, $color:#FFFFFF) {}
#### @include exclamatory ($width, $height, $color, $inclination: 0.1) {}
#### @include triangle ($direction, $width, $color, $inclination: 0.5) {}
#### @include ring ($radius, $bold, $color) {}
#### @include pseudoRing ($width: 16px, $height: $width, $color: #ff3737 ) {}
#### hook ($width: 8px, $height: 4px, $rotateDeg: -45deg, $color: #ff3737) {}
#### ringHook ($top: 0, $left: 0) {}


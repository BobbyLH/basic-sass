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

Start using **sass**:
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

### layout
#### @include clearfix {}
#### @include centralize-pseudo {}
#### @include centralize-translate($position: 'vh') {}
#### @include centralize-margin($position: 'vh') {}
#### @include ellipsis {}
#### @include ellipsis-line($line: 2) {}

### font
#### @include font-opensans {}
#### @include font-montserrat {}
#### @include force-font ($fontSize: 12) {}


## variable

### screen size
#### $screen-xs: 320px;
#### $screen-sm: 576px;
#### $screen-md: 768px;
#### $screen-lg: 1024px;
#### $screen-xl: 1440px;
#### $screen-xxl: 1600px;

### z-index
#### $zindex-toast-download: 10;
#### $zindex-form: 99;
#### $zindex-footer: 99;
#### $zindex-header: 100;
#### $zindex-header-crumb: 101;
#### $zindex-menu: 101;
#### $zindex-player: 900;
#### $zindex-dropdown: 901;
#### $zindex-mask: 999;
#### $zindex-toast: 1000;
#### $zindex-loading: 9999;
#### $zindex-highest: 99999;
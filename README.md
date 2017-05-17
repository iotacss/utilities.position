**iotaCSS is now a monorepo and all individual repositories are part of it. Please open issues or PRs here: [https://github.com/iotacss/iotacss](https://github.com/iotacss/iotacss).**

# Position Utility #

The position utility contains helper classes for the CSS position property.


### Installation ###

```
npm install --save iotacss-utils-position
```


### Options ###

```sass
$iota-utils-position-namespace            : '' !default;
$iota-utils-position-absolute-name        : 'absolute' !default;
$iota-utils-position-fixed-name           : 'fixed' !default;
$iota-utils-position-relative-name        : 'relative' !default;
$iota-utils-position-static-name          : 'static' !default;

$iota-utils-position-res                  : false !default;
$iota-utils-position-breakpoints          : $iota-global-breakpoints !default;
```


### Classes ###

```css
.u-absolute
.u-fixed
.u-relative
.u-static


// Responsive Class Syntax

.u-[name]@[breakpoint-name]  // Example: u-absolute@sm
```

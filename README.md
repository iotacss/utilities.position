# Position Utility #

The position utility contains helper classes for the CSS position property.


### Installation ###

```
npm install --save iotacss-position
```


### Dependencies ###

* [Settings.Default](https://github.com/iotacss/settings.default)
* [Settings.Breakpoint](https://github.com/iotacss/settings.breakpoint)


### Options ###

```
$iota-position--res               : false !default;
$iota-position-absolute-namespace : 'absolute' !default;
$iota-position-fixed-namespace    : 'fixed' !default;
$iota-position-relative-namespace : 'relative' !default;
$iota-position-static-namespace   : 'static' !default;
```


### Classes ###

```
.u-absolute
.u-fixed
.u-relative
.u-static


// Responsive Class Syntax

.u-[name]@[breakpoint-name]  // Example: u-absolute@sm
```

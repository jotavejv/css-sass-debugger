# Sass debugger

This scss file provides a way to debug your project with a visual highlight style preview based in some options that you can customize.

## How to install
Download this repo and import the file `_debugger.scss`

If you prefer using `bower` just install it `bower install css-sass-debugger`.

## How to use
In your sass file import the ***_debugger.scss*** if you have downloaded it or if you are using `bower` just import from `bower_components/css-sass-debugger/_debugger.scss`

```scss
@import 'debugger.scss'
```
OR
```scss
@import 'bower_components/css-sass-debugger/_debugger.scss'
```
## Basic examples
![demo1](https://github.com/jotavejv/css-sass-debugger/blob/master/demo1.gif "A List Apart")

For this example I've used these options:
```scss
$outline: true;
$tags: (h1, h2, h3, h4, a);
$attrs: (style);
```

![demo2](https://github.com/jotavejv/css-sass-debugger/blob/master/demo2.gif "A List Apart")

For this example I've used these options:
```scss
$tags: (h1, h2, h3, h4, a);
$attrs: (style);
$classes: (jumbotron, featurette);
```

## Todo
- Bookmarklet or chrome extension



# Sass debugger

This scss file provides a way to debug your project with a visual highlight style preview based in some options that you can customize.

## How to install
Download this repo and import the file `_debugger.scss`

If you prefer using `bower` just install it `bower install css-sass-debugger`.

## Basic examples
![demo1](https://github.com/jotavejv/css-sass-debugger/blob/master/demo1.gif "A List Apart")

For this example I've used these options:
```scss
$outline: true;
$tags: (h1, h2, h3, h4, a);
$attrs: (style);
```

![demo2](https://github.com/jotavejv/css-sass-debugger/blob/master/demo2.gif "Github")

For this example I've used these options:
```scss
$tags: (h1, h2, h3, h4, a);
$attrs: (style);
$classes: (jumbotron, featurette);
```

## How to use
In your sass file import the *_debugger.scss* if you have downloaded it or if you are using `bower` just import from `bower_components/css-sass-debugger/_debugger.scss`

```scss
@import 'debugger.scss'
```
OR
```scss
@import 'bower_components/css-sass-debugger/_debugger.scss'
```

Then you need add this line in your sass file to activate the debugger mixin:
```scss
body{
  @include debugger();
}
```
The options default are:
```scss
$outline: true;
$tags: ();
$attrs: (style);
$classes: ();
```
Where `$outline` is the outside element's border, `$tags` are the DOM element's tag, `$attrs` are the element's attributes like `style`, `data-*`, `class`, `id`, `alt`, etc... and the `$classes` are the element's class.
By default the `$outline` is true, see below the difference between be true or false:
![outline](https://github.com/jotavejv/css-sass-debugger/blob/master/outline.png "Outline option")

If you want to change theses options you can do it inside of `_debugger.scss` and modify them as you need.
just it! Be creative and debug your project in the best way.

## Todo
- Bookmarklet or chrome extension



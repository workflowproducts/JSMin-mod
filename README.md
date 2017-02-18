# JSMin-mod
JSMin, The JavaScript Minifier (Modified to Allow Multi-Line Strings)

In our javascript, we use a function called ml() like this:

    console.log(
    ml(function () {/*This is a multi-
    line string!*/})
    );

We also use jsmin, but jsmin strips out multi line comments. I modified it to allow multi-line comments so we can use ml() in our minified code.

The Software shall be used for Good, not Evil.

Please see source repo: https://github.com/douglascrockford/JSMin

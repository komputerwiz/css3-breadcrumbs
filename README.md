CSS3 Breadcrumbs
================
This is my humble contribution to the general movement to make image-based web
page layouts obsolete in favor of semantic HTML and CSS3 styling.

Download &amp; Use
------------------
Clone this repository with

    git clone git://github.com/komputerwiz/css3-breadcrumbs.git

There are three usage options

1.  Copy [`css/breadcrumbs.css`][breadcrumb-css] and include it in your
    layout.
    
2.  Copy [`css/breadcrumbs-slim.css`][breadcrumb-slim], modify it to include
    any necessary browser prefixes (needed for declarations separated by blank
    line), and use that in your theme.

3.  Use the files under [`scss`][breadcrumb-scss] to build your own distribution using the
    [SASS Stylesheet Language][sass].

Demo
----
[See this code in action!][demo]

File Manifest
-------------
* `index.html`: Sample markup for your breadcrumbs.
* `css/breadcrumbs-slim.css`: The minimum required CSS to get the basic styling.
  This file does not have any vendor prefixes and will probably not display well
  in all web browsers. Please modify to fit your needs.
* `css/breadcrumbs.css`: A plug-and-play CSS stylesheet with hover and click
  states.
* `css/demo.css`: Stylesheet for [demo web page][demo].
* `scss/breadcrumbs.css`: All of the logic used to build the `breadcrumbs.css`
  file. This might be a little easier to understand.
* `scss/_*.scss`: other libraries that you might find useful. Credit to
  [Adam Savitzky][adambom] for the _Sass-Math_ functions: it brought
  to mind several good memories of sequences and series from my Calculus 2
  course!

License
-------
Apart from [_Sass-Math_][adambom-sass-math], this is my own work, which I hereby release to the
public domain. Feel free to do whatever you want with this code. Enjoy!

[breadcrumb-css]: https://github.com/komputerwiz/css3-breadcrumbs/blob/master/css/breadcrumbs.css
[breadcrumb-slim]: https://github.com/komputerwiz/css3-breadcrumbs/blob/master/css/breadcrumbs-slim.css
[breadcrumb-scss]: https://github.com/komputerwiz/css3-breadcrumbs/tree/master/scss
[sass]: http://sass-lang.com "Syntactically Awesome StyleSheets"
[demo]: http://komputerwiz.net/demos/css3-breadcrumbs/
[adambom]: https://github.com/adambom/Sass-Math
[adambom-sass-math]: https://github.com/adambom/Sass-Math/blob/master/math.scss

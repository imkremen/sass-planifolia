Sass-Planifolia - Vanilla Sass helper functions

[Sass](http://sass-lang.com/) is great, but some of its libraries not so much.
[Compass](http://compass-style.org/), the most popular of them all, seems to be
unmaintained. In addition, the rise of [libSass](http://sass-lang.com/libsass)
means that ruby extensions are no longer a good way forward.

# Quick start

    bower install xi/sass-planifolia

Import it in your Sass files:

    @import "bower_components/sass-planifolia/sass/math";
    @import "bower_components/sass-planifolia/sass/contrast";

    .test {
        background: red;
        color: contrast-color(red);
    }

# Features

Planifolia is a collection of vanilla Sass implementations of common framework
functionality. Features include:

-   Does not depend on a specific Sass implementation
-   Leightweight
-   Unit tests
-   Fully documented
-   High performance math algorithms
-   WCAG compatible [color contrast](www.w3.org/TR/WCAG20/#contrast-ratiodef)
    functions
-   More functionality may be added when required
-   Can be installed with bower. Npm (eyeglass) or rubygem support may be added
    when required.

# What is not included?

-   Vendor prefixes, polyfills or browser hacks. There are plenty of librariers
    for that.
-   pt/px/em/rem conversion. That is (a) not possible and (b) not helpful. Each
    unit has its specific use case. Learn to use the right units directly!
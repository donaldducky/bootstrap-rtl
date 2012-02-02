Twitter Bootstrap RTL
=====================

Right-to-left version of Twitter's Bootstrap:
https://github.com/twitter/bootstrap/

Created using:
https://github.com/ded/R2

Usage
-----

Just replace the original `bootstrap.min.css` and `bootstrap-responsive.min.css` files when displaying RTL pages.

    <link rel="stylesheet" href="bootstrap-rtl.min.css">
    <link rel="stylesheet" href="bootstrap-responsive-rtl.min.css">

The last thing you need to do, if you haven't already, is specifying the direction on the body element.

    <body dir="rtl">

Or using CSS:

    body {
      direction: rtl;
    }

How it was made
---------------

Follow instructions on the R2 project page to install it: https://github.com/ded/R2

`r2 bootstrap.css bootstrap-rtl.min.css`
`r2 bootstrap.responsive bootstrap-responsive-rtl.min.css`

Notes:

* the unminified version was used because r2 couldn't convert the minified version correctly
* the bootstrap.zip (http://twitter.github.com/bootstrap/assets/bootstrap.zip) I downloaded had a css/bootstrap.responsive file instead of some sort of .css file haha

Special Thanks
--------------

Mark Otto and Jacob Thornton for working on and maintaining Twitter Bootstrap.

Dustin Diaz for creating R2.

Without these tools, writing CSS and reversing it for right to left would be a pain in the ass :D

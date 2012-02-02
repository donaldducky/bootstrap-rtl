Twitter Bootstrap RTL
=====================

Right-to-left version of Twitter's Bootstrap:
https://github.com/twitter/bootstrap/

Created using:
https://github.com/ded/R2

Usage
-----

Just include this CSS file instead of Bootstrap's `bootstrap.min.css` when displaying RTL.

    <link rel="stylesheet" href="bootstrap-rtl.min.css">

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

Note: the unminified version was used because r2 couldn't convert the minified version correctly

Special Thanks
--------------

Mark Otto and Jacob Thornton for working on and maintaining Twitter Bootstrap.

Dustin Diaz for creating R2.

Without these tools, writing CSS and reversing it for right to left would be a pain in the ass :D

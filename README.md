tv-rating-icon-css
=============

CSS for TV classification ratings. See the
[demo](http://bradcornford.github.io/tv-rating-icon-css/).

Usage
-----

For using the TV classification ratings inline with text add the classes `tv-rating-icon` and
`tv-rating-icon-xx` (where `xx` is the code for the rating, i.e. 14) to an empty `<span>`.
If you want to have a light version of the classification rating `tv-rating-icon-light`,
and three different sizes `tv-rating-icon-sm`, `tv-rating-icon-md`, `tv-rating-icon-lg` as well. Example:

    <span class="tv-rating-icon tv-rating-icon-dark tv-rating-icon-14"></span>
    <span class="tv-rating-icon tv-rating-icon-light tv-rating-icon-14"></span>
    <span class="tv-rating-icon tv-rating-icon-light tv-rating-icon-md tv-rating-icon-14"></span>
    <span class="tv-rating-icon tv-rating-icon-dark tv-rating-icon-lg tv-rating-icon-14"></span>


Development
-----------

Run the `npm install` to install the dependencies after cloning the project and
you'll be able to:

To watch for changes and live reload if served

    $ grunt

To build `*.less` files

    $ grunt build

To serve it on `localhost:8000`

    $ grunt connect


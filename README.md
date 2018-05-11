Simple HTML Gallery
===================

Create a single-page HTML gallery with:

    $ ./create-gallery.py -i vacation-photos -o gallery

where `vacation-photos` is the input directory and `gallery` is the output
directory. The script first searches for all image files within the input
directory and then creates the output directory with a generated
`index.html` file and all image files found in the input directory.

Optionally, you can specify a title for the generated page using the
`--title` option.

The created directory (in this case, `./gallery`) can then be moved into
your document root (e.g. `/var/www/html/`).

local-photos
============

Deeply experimental code to explore photo exif data in node

Initial simplest useful thing, or simplest least useless thing...

(notes which are only interesting to me)

get_exif_date_descend.pl took a directory as the starting point, then descended from
there, checking a local list of images and reading exif data for every image file (just jpegs?)
which was not already in the local file, then writing some of the exifdata, especially
create date, to the local list.

The new code:
-start in var clientId = process.argv[2] || '';

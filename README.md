EXPath web files
================

The files in the download area of the EXPath website, at
[http://expath.org/files](http://expath.org/files).

To publish new files to the website, just commit to the branch
`master`.  Never commit directly to `master`, commit first to the
branch `sandbox`, which publishes to
[http://test.expath.org/files](http://test.expath.org/files), and
never commit directly to the branches but pass through a pull request.

Updates take more or less 5 minutes to be actually published to the
websites.

The file `files/files.xml` lists the files to appear directly under
[http://expath.org/files](http://expath.org/files) (the latest version
of each component).  Each subdirectory in `files/` is a specific
download area, containing each one or several components, each with
one or several version.  Each subdirectory contains its own file
`__files.xml`, which describes the content on this area.  For instance
`files/servlex/__files.xml`.  The files `__google-code.xml` are an
export of the associated properties of the files which were published
on Google Code first (where the download areas are going to be shut
early 2014).

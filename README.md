EXPath web files
================

The files in the download area of the EXPath website, at
[http://expath.org/files](http://expath.org/files).

## Updates

To publish new files to the website, commit to the branch `sandbox`.
Once everything is fine on [the sandbox](http://test.expath.org/)
website, create a pull request from `sandbox` to `master` (e.g. using
Github web interface).

Updates take more or less 5 minutes to be actually published to the
websites.

## Descriptors

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

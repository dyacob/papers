## An Archive of Papers, Articles, & Presentations that I've Authored

For better it worse, this seems to be it. At least what I can still locate, which I believe is most of it.
Adding all to a repository is done in large part so I can find things when I want them.  They have otherwise
been scattered across various, decaying, media and leaving me unsure of what the final version of a document
was. Getting organized is also meant to set the stage for me to write additional papers in the years ahead.

## Digitally Remastered

Many of the older documents have been “digitallly remastered”, meaning that a file previously in `HTML`
or `DOC` format was opened in modern Microsoft Word (2021, Mac v16.95) where some typefaces might be changed
(for better quality, or to avoid dependency on a commercially licensed product),
spell checker suggestions applied, as well as grammar checker suggestions (usually just for commas).
Broken hyperlinks have been updated when the new link is known (and sometimes linked into archive.org).
Minor layout and formatting changes may also have been made when it improved readability.
The qualitative content remains unchanged.

Many of the papers in this repository have also been posted to [Academia.edu](https://vt.academia.edu/DanielYacob).

## TODO

* When copying in .tex sources, verify that the fonts are available under the latex-fonts directory.
* Letters stored in .epsi and .gif files will get clobbered when case collides on MacOS.  For example:  ge.epsi, gE.epsi , Ge.epsi, GE.epsi will merge into the same file.
* Continue migrating old SERA documents.
* Eventually update the LaTeX files to use UTF-8 and a TrueType font.
* Add presentations.

## GZIPPED Files

A number of files are in `gzip` form. This is done simply because gzip will preserve the file date of the compressed artifact.
To view the file date, the following Unix (or MacOS) command can be used:

`dd bs=4 skip=1 count=1 if=LibEth.html.gz 2> /dev/null | perl -nle 'print scalar localtime unpack("i",$_);'`

## The `latex-fonts` Directory

This is a collection of (hopefully) all of the non-Roman LaTeX fonts that I've used.  They are referenced
from the various `.tex` files in subdirectories, albiet with paths that will have to be corrected if any
attempt is made to compile the respective files.

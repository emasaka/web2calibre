# web2calibre

Convert web pages to small PDF and register to Calibre

## USAGE

    $ web2calibre [OPTION]... url [url2]...

## OPTIONS

### -n

Do not allow web pages to run javascript

### -s SIZE

Set paper size to: A4, Letter, etc. (default: A5)

## SOFTWARE REQUIREMENTS

- Calibre (including calibredb command)
- wkhtmltopdf
- Perl
    - Regexp::Common
    - URI::Escape;
    - LWP::Simple
    - File::Slurp
    - HTML::TreeBuilder
    - PDF::API2

## NOTES

- Characters may be splitted into upper and lower half by pagebreak
  (wkhtmltopdf mattter)

## AUTHOR

emasaka

Lambeth Council Open Data
=========================

An unofficial project by [Adrian Short](http://about.adrianshort.co.uk/)

Source: [Lambeth Open Data](http://www.lambeth.gov.uk/Services/CouncilDemocracy/DataProtectionFOI/OpenData.htm)

All data is provided by [Lambeth Council](http://www.lambeth.gov.uk/) under the [Open Government Licence](http://www.nationalarchives.gov.uk/doc/open-government-licence/).

All contributions are very welcome.

Rules
-----

- All files in [UTF-8 encoding](http://en.wikipedia.org/wiki/UTF-8). Here's how to [export to UTF-8 CSV in Excel](http://stackoverflow.com/questions/4221176/excel-to-csv-with-utf8-encoding).
- Open file formats only. CSV, XML, JSON, KML, RSS etc. all good. No .doc, .xls etc. (See the .gitignore file.)
- Readme files are named README.md and are in [Github-Flavo(u)red Markdown](http://github.github.com/github-flavored-markdown/). Like everything else they're UTF-8 encoded.

Converting files to UTF-8
-------------------------

[Various charset conversion tools discussed.](http://stackoverflow.com/questions/64860/best-way-to-convert-text-files-between-character-sets)

I'm using [recode](https://github.com/pinard/Recode).

To convert a file in place from ISO-8859-1 (Windows Latin 1) to UTF-8:

    $ recode l9..UTF8 community-toilets.csv
    
On OS X, recode is available through [Homebrew](http://mxcl.github.com/homebrew/):

    $ brew install recode

Changing/adding to the data
---------------------------

- Fork the project
- Make your changes and commit them with good commit messages
- Send a pull request

Bug reports and enhancement requests
------------------------------------

Please use the project's Issues system.

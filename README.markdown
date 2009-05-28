# DocBook 5 TextMate bundle

This bundle provides a basic support for editing DocBook 5 documents in TextMate.

**Contributions are more than welcome!**


**WARNING**: This library has not been released yet. This package seems stable, but should be considered a development release.
Changes to specifications may occur at any time and without notice. For the full list of changes look at the CHANGELOG file. 


## Installation
 
To install via Git:

    cd ~/"Library/Application Support/TextMate/Bundles/"
    git clone git://github.com/weppos/docbook5-tmbundle.git "DocBook 5.tmbundle"

Source can be viewed or forked via GitHub: [http://github.com/weppos/docbook5-tmbundle/tree/master](http://github.com/weppos/docbook5-tmbundle/tree/master)

To install without Git:

    wget http://github.com/weppos/docbook5-tmbundle/tarball/master
    open weppos-docbook5-tmbundle*
    rm weppos-docbook5-tmbundle*.tar.gz
    mv weppos-docbook5-tmbundle* "DocBook 5.tmbundle"
 
Either way, restart TextMate or select "Reload Bundles" from the Bundles >> Bundle Editor menu.
If you don't want to leave the command line, type the following command:

    osascript -e 'tell app "TextMate" to reload bundles'


## Author

[Simone Carletti](http://www.simonecarletti.com) (<weppos@weppos.net>)


## Thanks to
 
[Dr Nic Williams](http://drnicwilliams.com/) (this README is a merely adapted from his github-tmbundle project)

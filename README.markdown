# DocBook 5 TextMate bundle

This bundle provides a basic support for editing DocBook 5 documents in TextMate.

*Note.* This package should be considered an early alpha preview.
API might change in the future, including shortcuts and tab triggers.

**Contributions are more than welcome!**


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
    osascript -e 'tell app "TextMate" to reload bundles'
 
Either way, restart TextMate or select "Reload Bundles" from the Bundles >> Bundle Editor menu.


## Author

Simone Carletti <weppos@weppos.net>, [www.simonecarletti.com](http://www.simonecarletti.com)


## Thanks to
 
Dr Nic Williams (this README is a merely adapted from his github-tmbundle project)

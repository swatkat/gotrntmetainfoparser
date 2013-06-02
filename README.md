gotrntmetainfoparser
====================

Torrent metafile parser written in Go lang.

Usage
====================
* `MetaInfo::ReadTorrentMetaInfoFile(<file>)` parses `.torrent` metainfo file and stores result in MetaInfo structure.
* `MetaInfo::DumpTorrentMetaInfo()` prints `.torrent` metainfo file content in text format.

Installation
====================
* Install packages:

    go get code.google.com/p/bencode-go
    go get github.com/swatkat/gotrntmetainfoparser

* Import package in your source:

    import (
        "github.com/swatkat/gotrntmetainfoparser"
    )

